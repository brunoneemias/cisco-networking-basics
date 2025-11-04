# 🔐 Lab 16.4.7 – Configurar Dispositivos de Rede com SSH

Este laboratório tem como objetivo configurar o acesso remoto seguro a dispositivos de rede Cisco utilizando o protocolo SSH (Secure Shell), substituindo o Telnet como método de administração remota. A atividade reforça práticas de segurança e autenticação em ambientes simulados no Cisco Packet Tracer.

## 🎯 Objetivos do Laboratório

- Ativar e configurar o serviço SSH em roteadores e switches
- Criar usuários locais com senhas criptografadas
- Definir nome de domínio e gerar chaves RSA
- Restringir o acesso remoto apenas via SSH
- Testar a conectividade SSH entre dispositivos

## 🛠️ Etapas Realizadas

### Parte 1: Preparação do Dispositivo

- Definição de nome de host:
  ```bash
  hostname R1
- Configuração do nome de domínio:

  ```bash
  ip domain-name rede.local

### Parte 2: Criação de Usuário e Chave RSA
- Criação de usuário local:

  ```bash
  username admin secret SenhaSegura123

- Geração de chave RSA:

  ```bash
  crypto key generate rsa
- Tamanho recomendado: 1024 bits ou superior

### Parte 3: Configuração das Linhas VTY
- Ativação do login local e restrição ao SSH:

  ```bash
  line vty 0 4
  login local
  transport input ssh
Parte 4: Testes de Conectividade

- Acesso remoto via SSH a partir de um PC:

- Ferramenta de terminal → SSH

- Informar IP do dispositivo, usuário e senha

- Verificação com:
    ```bash
      show ip ssh
      show users

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores, switches e PCs)

- Comandos: hostname, ip domain-name, username, crypto key generate rsa, line vty, transport input ssh, show ip ssh

### 📎 Arquivos
- lab-16.4.7.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório

💡 Este laboratório é essencial para garantir acesso remoto seguro a dispositivos de rede, utilizando autenticação local e criptografia com SSH em substituição ao Telnet.
