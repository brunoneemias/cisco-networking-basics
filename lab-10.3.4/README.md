# 🧪 Lab 10.3.4 – Packet Tracer: Conexão de um Roteador a uma LAN

Este laboratório tem como objetivo configurar as interfaces de um roteador Cisco e conectá-lo corretamente a uma LAN, utilizando comandos de verificação e testes de conectividade para garantir que os dispositivos estejam operando conforme esperado.

## 🎯 Objetivos do Laboratório

- Exibir informações das interfaces do roteador
- Configurar endereços IP e ativar interfaces Ethernet
- Verificar a configuração com comandos de diagnóstico
- Testar conectividade entre roteador e dispositivos finais

## 🛠️ Etapas Realizadas

### Parte 1: Exibir Informações do Roteador

- Acesso à CLI do roteador R1
- Uso de comandos como:
  - `show ip interface brief`
  - `show interfaces`
  - `show running-config`
  - `show ip route`
- Identificação de interfaces GigabitEthernet e Serial
- Verificação de status, endereços IP e largura de banda

### Parte 2: Configurar Interfaces do Roteador

- Configuração da interface GigabitEthernet 0/0 com:
  ```bash
  R1(config)# interface gigabitethernet 0/0
  R1(config-if)# ip address 192.168.10.1 255.255.255.0
  R1(config-if)# no shutdown
  R1(config-if)# description LAN connection to S1
Repetição do processo para outras interfaces conforme tabela de endereçamento

Configuração da interface Serial com IP e ativação

Parte 3: Verificar a Configuração
Teste de conectividade com ping entre R1 e PC1

Verificação da tabela de roteamento com show ip route

Análise das rotas conectadas (código C) e rotas OSPF (código O)

Diagnóstico de interfaces “up/up” e validação de endereços IP

🧰 Ferramentas Utilizadas
Cisco Packet Tracer

Terminal CLI (Console do roteador)

Comandos: show, ping, ip address, no shutdown, description

📎 Arquivos
lab-10.3.4.pkt – Arquivo do Packet Tracer com a topologia configurada

README.md – Este documento com a descrição do laboratório
