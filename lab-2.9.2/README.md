# 🧪 Lab 2.9.2 – Packet Tracer: Configuração básica do switch e do dispositivo final

Este laboratório tem como objetivo construir uma rede simples com dois switches e dois PCs, realizando configurações básicas nos dispositivos para garantir conectividade e segurança.

## 🎯 Objetivos do Laboratório

- Montar a topologia física com switches e PCs
- Configurar endereços IP nos hosts
- Realizar configurações iniciais nos switches (nome, senhas, banner)
- Verificar conectividade entre os dispositivos usando `ping`
- Salvar configurações e verificar status das interfaces

## 🛠️ Etapas Realizadas

### Parte 1: Montagem da Topologia
- Inserção dos switches S1 e S2 no rack
- Conexão dos PCs aos switches com cabos de cobre
- Conexão entre os switches com cabo crossover
- Verificação visual das luzes de link (âmbar → verde)

### Parte 2: Configuração dos Hosts
- Atribuição de IP estático aos PCs conforme tabela de endereçamento
- Verificação com `ipconfig /all`
- Teste de conectividade com `ping` entre os PCs

### Parte 3: Configuração dos Switches
- Acesso via cabo console e terminal
- Definição de hostname (S1, S2)
- Configuração de senhas locais (`class`, `cisco`)
- Criação de banner MOTD
- Configuração da interface VLAN 1 com IP
- Verificação com `show running-config`, `show version`, `show ip interface brief`
- Salvamento com `copy running-config startup-config`

### Parte 4: Testes de Conectividade
- Ping dos PCs para os switches
- Ping dos switches para os PCs
- Verificação do status das interfaces (F0/1, F0/6, F0/18, VLAN 1)

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer (modo físico)
- Terminal CLI (Command Line Interface)

> 💡 *Este laboratório reforça os fundamentos da configuração de switches e hosts em uma rede local, além de introduzir práticas de verificação e segurança essenciais para administradores de rede.*
