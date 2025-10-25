# 🧪 Lab 2.3.8 – Packet Tracer: Navegue pelo IOS usando um cliente terminal para conectividade de console

Este laboratório tem como objetivo ensinar como acessar dispositivos Cisco por meio de uma conexão local direta utilizando a porta de console, simulando o processo com o **Cisco Packet Tracer** em modo físico.

## 🎯 Objetivos do Laboratório

- Conectar um PC ou laptop a um switch ou roteador Cisco via cabo de console
- Utilizar o programa Terminal para acessar a CLI do dispositivo
- Navegar pelos modos do IOS (EXEC usuário e privilegiado)
- Exibir e configurar parâmetros básicos como o relógio do sistema

## 🛠️ Etapas Realizadas

### Parte 1: Acesso ao Switch via Porta Serial
- Instalação de um switch 2960 no rack
- Conexão com um PC usando cabo rollover (RS-232 → Console)
- Acesso à CLI via Terminal com parâmetros padrão (9600 baud, 8 data bits, etc.)

### Parte 2: Exibição e Configuração de Parâmetros
- Comando `show version` para verificar a versão do IOS
- Comando `show clock` para visualizar o horário atual
- Comando `enable` para entrar no modo EXEC privilegiado
- Comando `clock set` para configurar manualmente o relógio

### Parte 3: Acesso ao Roteador via Mini-USB
- Instalação de um roteador 4321 e conexão com laptop via cabo mini-USB
- Acesso à CLI após inicialização do roteador
- Navegação pelos modos do IOS e verificação de conectividade

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer (modo físico)
- Terminal CLI (emulador de terminal interno)

> 💡 *Este laboratório reforça a importância da conexão física e da configuração inicial de dispositivos Cisco, além de introduzir a navegação prática pelo IOS via terminal.*
