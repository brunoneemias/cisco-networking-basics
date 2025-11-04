# 🔐 Lab 16.5.2 – Proteger Dispositivos de Rede

Este laboratório tem como objetivo aplicar práticas de segurança em dispositivos de rede Cisco, como switches e roteadores, reforçando a proteção contra acessos não autorizados e garantindo a integridade das configurações administrativas.

## 🎯 Objetivos do Laboratório

- Configurar senhas seguras e criptografadas
- Restringir o acesso remoto com autenticação local
- Criar banners de aviso legal
- Ativar criptografia de senhas simples
- Salvar e verificar configurações de segurança

## 🛠️ Etapas Realizadas

### Parte 1: Configuração de Senhas

- Definição de senha privilegiada criptografada:
  ```bash
  enable secret SenhaSegura123
- Configuração de senhas nas linhas de console e VTY:

  ```bash
    line console 0
    password Console123
    login
    
    line vty 0 4
    password Remoto123
    login

### Parte 2: Criptografia e Banner de Aviso
- Criptografia de senhas simples:

  ```bash
  service password-encryption

- Criação de banner de aviso:

  ```bash
  banner motd #Acesso não autorizado é proibido!#

### Parte 3: Verificação e Salvamento
- Verificação das configurações aplicadas:

  ```bash
  show running-config

- Salvamento da configuração:

  ```bash
  copy running-config startup-config

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores e switches)

- Comandos: enable secret, line, password, login, service password-encryption, banner motd, show, copy

### 📎 Arquivos
- lab-16.5.2.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório


💡 Este laboratório é essencial para garantir a segurança básica de dispositivos de rede, protegendo o acesso administrativo e promovendo boas práticas de configuração em ambientes Cisco.
