# 🔐 Lab 16.4.6 – Packet Tracer: Configurar Senhas Seguras e SSH

Este laboratório tem como objetivo aplicar práticas de segurança em dispositivos de rede Cisco, configurando senhas seguras e acesso remoto via SSH (Secure Shell) em roteadores e switches simulados no Cisco Packet Tracer.

## 🎯 Objetivos do Laboratório

- Configurar senhas locais e criptografadas para acesso ao dispositivo
- Criar banners de aviso para segurança legal
- Ativar e configurar o serviço SSH para acesso remoto seguro
- Verificar e testar a conectividade SSH entre dispositivos

## 🛠️ Etapas Realizadas

### Parte 1: Configuração de Senhas Seguras

- Definição de senha privilegiada com criptografia:
  ```bash
  enable secret [senha]
- Configuração de senhas nas linhas de console e VTY:
  ```bash
      line console 0
      password [senha]
      login

      line vty 0 4
      password [senha]
      login
- Criptografia de todas as senhas com:
   ```bash
      service password-encryption
### Parte 2: Banner de Aviso

- Criação de banner legal com:
     ```bash
    banner motd #Acesso não autorizado será monitorado!#
     
### Parte 3: Configuração de SSH
  - Definição de nome de domínio:
     ```bash
    ip domain-name [domínio]
  - Criação de usuário local:
     ```bash
    username admin secret [senha]
  - Geração de chave RSA:
     ```bash
    crypto key generate rsa
     
  - Ativação do SSH nas linhas VTY:
     ```bash
    line vty 0 4
    transport input ssh
    login local
### Parte 4: Testes de Conectividade
- Teste de acesso remoto via SSH usando PC:

- Ferramenta de terminal → SSH

- Informar IP do roteador, usuário e senha

- Verificação com:
   ```bash
    show ip ssh
    show users

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores, switches e PCs)

- Comandos: enable secret, line, username, ip domain-name, crypto key, transport input, show ip ssh

###📎 Arquivos
- lab-16.4.6.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório

💡 Este laboratório é essencial para aplicar práticas de segurança em redes Cisco, garantindo acesso remoto protegido e controle de autenticação confiável.
