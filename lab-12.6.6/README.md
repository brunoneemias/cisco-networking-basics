# 🧪 Lab 12.6.6 – Packet Tracer: Configurar Endereçamento IPv6

Este laboratório tem como objetivo configurar endereços IPv6 em dispositivos de rede Cisco, utilizando o Cisco Packet Tracer para aplicar conceitos de endereçamento manual, roteamento básico e verificação de conectividade em uma rede IPv6.

## 🎯 Objetivos do Laboratório

- Compreender os tipos de endereços IPv6 (global, link-local, unicast)
- Atribuir endereços IPv6 manualmente a PCs, switches e roteadores
- Ativar interfaces e configurar roteamento IPv6
- Verificar conectividade entre dispositivos usando `ping` e `show`
- Consolidar práticas de configuração IPv6 em ambientes simulados

## 🛠️ Etapas Realizadas

### Parte 1: Configuração dos Endereços IPv6

- Atribuição de endereços IPv6 globais às interfaces dos roteadores:
  ```bash
  R1(config)# interface g0/0
  R1(config-if)# ipv6 address 2001:DB8:ACAD:1::1/64
  R1(config-if)# no shutdown  
- Ativação do roteamento IPv6 com:
  
- R1(config)# ipv6 unicast-routing

- Configuração de PCs com endereços IPv6 estáticos e gateway padrão

### Parte 2: Verificação de Conectividade
- Testes de ping entre PCs e roteadores usando endereços IPv6

- Verificação das interfaces com show ipv6 interface brief

- Análise da tabela de vizinhos com show ipv6 neighbors

- Diagnóstico de conectividade com traceroute IPv6

### Parte 3: Análise e Diagnóstico
- Identificação de endereços link-local gerados automaticamente

- Verificação da tabela de roteamento com show ipv6 route

- Discussão sobre a diferença entre IPv4 e IPv6 na configuração de rede

### 🧰 Ferramentas Utilizadas
Cisco Packet Tracer

- Terminal CLI (roteadores e PCs)

- Comandos: ipv6 address, ipv6 unicast-routing, ping, show ipv6 interface, show ipv6 route, traceroute

📎 Arquivos
lab-12.6.6.pkt – Arquivo do Packet Tracer com a topologia configurada

README.md – Este documento com a descrição do laboratório
