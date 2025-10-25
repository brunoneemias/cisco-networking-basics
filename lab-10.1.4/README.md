# 🧪 Lab 10.1.4 – Packet Tracer: Configurar definições iniciais do roteador

Este laboratório tem como objetivo realizar a configuração básica de um roteador Cisco, garantindo segurança no acesso à interface de linha de comando (CLI), definindo mensagens de aviso e salvando as configurações na NVRAM.

## 🎯 Objetivos do Laboratório

- Verificar a configuração padrão do roteador
- Definir hostname, senhas e banner de aviso
- Proteger o acesso via console e modo privilegiado
- Criptografar senhas em texto simples
- Salvar configurações na NVRAM e opcionalmente na memória flash

## 🛠️ Etapas Realizadas

### Parte 1: Verificar a Configuração Padrão

- Conexão via cabo console entre PC e roteador
- Acesso ao terminal e entrada no modo EXEC privilegiado (`enable`)
- Visualização da configuração atual com `show running-config`
- Verificação das interfaces disponíveis e status da NVRAM (`show startup-config`)

### Parte 2: Definir Configurações Iniciais

- Alteração do nome do dispositivo com `hostname R1`
- Criação de banner de aviso com `banner motd`
- Configuração de senhas:
  - `enable password cisco` (não criptografada)
  - `enable secret itsasecret` (criptografada)
  - Senha de console: `letmein`
- Criptografia de senhas com `service password-encryption`

### Parte 3: Verificar Configurações

- Saída da sessão e verificação do banner de aviso
- Teste de acesso com senha ao modo EXEC privilegiado
- Análise do arquivo de configuração para verificar se as senhas estão criptografadas

### Parte 4: Salvar Configuração

- Salvamento da configuração atual na NVRAM com `copy running-config startup-config`
- Verificação do conteúdo da NVRAM com `show startup-config`
- Opcional: salvamento na memória flash com `copy startup-config flash`

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (Console)
- Comandos: `enable`, `show`, `copy`, `banner`, `hostname`, `service password-encryption`

## 📎 Arquivos

- `lab-10.1.4.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório


> 💡 *Este laboratório é essencial para garantir segurança e organização na configuração inicial de roteadores Cisco, preparando o ambiente para futuras configurações de rede.*
