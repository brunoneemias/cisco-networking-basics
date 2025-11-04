# 🔐 Lab 16.5.1 – Packet Tracer: Proteger Dispositivos de Rede

Este laboratório tem como objetivo aplicar práticas fundamentais de segurança em dispositivos de rede Cisco, como switches e roteadores, utilizando o Cisco Packet Tracer. A atividade foca na proteção do acesso ao dispositivo, criptografia de senhas e configuração de banners de aviso.

## 🎯 Objetivos do Laboratório

- Configurar senhas seguras para acesso local e remoto
- Criptografar senhas armazenadas na configuração
- Criar banners de aviso para acesso não autorizado
- Restringir o acesso remoto com autenticação local
- Salvar e verificar as configurações aplicadas

## 🛠️ Etapas Realizadas

### Parte 1: Configuração de Segurança Básica

- Definição de nome do dispositivo com `hostname`
- Criação de senha privilegiada criptografada:
  ```bash
  enable secret [senha]
### Parte 2: Configuração de Acesso Local e Remoto
- Configuração de senha para acesso via console:
  ```bash
  line console 0
  password [senha]
  login
- Configuração de senhas para acesso remoto (VTY):
  ```bash
  line vty 0 4
  password [senha]
  login

### Parte 3: Criptografia de Senhas e Banner de Aviso
- Criptografia de senhas simples:

  ```bash
  service password-encryption
- Criação de banner de aviso legal:

  ```bash
  banner motd #Acesso não autorizado é proibido!#

### Parte 4: Salvamento e Verificação
- Salvamento da configuração:

  ```bash
  copy running-config startup-config
- Verificação com:
  ```bash
  show running-config

  show startup-config

  show version

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores e switches)

- Comandos: hostname, enable secret, line, password, login, service password-encryption, banner motd, copy, show

### 📎 Arquivos
- lab-16.5.1.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório

Capturas de tela das configurações aplicadas (opcional)

💡 Este laboratório é essencial para garantir a segurança básica de dispositivos de rede, protegendo o acesso administrativo e promovendo boas práticas de configuração em ambientes Cisco.
