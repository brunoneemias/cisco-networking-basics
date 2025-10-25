# 🧪 Lab 2.5.5 – Packet Tracer: Definir configurações iniciais do switch

Este laboratório tem como objetivo realizar a configuração básica de um switch Cisco, protegendo o acesso à interface de linha de comando (CLI), configurando mensagens de aviso e salvando as configurações na NVRAM.

## 🎯 Objetivos do Laboratório

- Verificar a configuração padrão do switch
- Configurar nome do dispositivo, senhas e banner MOTD
- Proteger o acesso via console e modo privilegiado
- Criptografar senhas em texto simples
- Salvar as configurações na NVRAM
- Repetir o processo em um segundo switch (S2)

## 🛠️ Etapas Realizadas

### Parte 1: Verificar a configuração padrão
- Acesso ao modo EXEC privilegiado com `enable`
- Comando `show running-config` para visualizar configurações atuais
- Identificação de interfaces e linhas VTY

### Parte 2: Configuração básica do switch
- Definição de hostname (`hostname S1`)
- Proteção da linha de console com senha `letmein`
- Configuração da senha de modo privilegiado (`enable password c1$c0`)
- Substituição por senha criptografada (`enable secret itsasecret`)
- Criptografia de senhas com `service password-encryption`

### Parte 3: Banner MOTD
- Criação de mensagem de aviso com `banner motd "This is a secure system. Authorized Access Only!"`

### Parte 4: Salvamento na NVRAM
- Comando `copy running-config startup-config` para preservar configurações após reinicialização

### Parte 5: Repetição no Switch S2
- Aplicação das mesmas configurações no segundo switch da topologia

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (Command Line Interface)

> 💡 *Este laboratório é essencial para garantir segurança básica em dispositivos de rede, reforçando boas práticas de configuração e gerenciamento de switches Cisco.*
