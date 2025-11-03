# 🧪 Lab 12.9.2 – Configurar Endereços IPv6 em Dispositivos de Rede

Este laboratório tem como objetivo aplicar configurações de endereçamento IPv6 em dispositivos de rede, como PCs, switches e roteadores, utilizando o Cisco Packet Tracer. A atividade foca na atribuição manual de endereços, ativação de interfaces e verificação de conectividade.

## 🎯 Objetivos do Laboratório

- Atribuir endereços IPv6 estáticos a interfaces de rede
- Ativar interfaces e configurar gateways padrão
- Verificar endereços link-local e globais
- Testar conectividade entre dispositivos usando IPv6
- Consolidar práticas de configuração IPv6 em ambientes simulados

## 🛠️ Etapas Realizadas

### Parte 1: Configuração dos Roteadores

- Atribuição de endereços IPv6 globais às interfaces:
  ```bash
  R1(config)# interface g0/0
  R1(config-if)# ipv6 address 2001:DB8:1::1/64
  R1(config-if)# no shutdown
- Ativação do roteamento IPv6:

  ```bash
  R1(config)# ipv6 unicast-routing
  Parte 2: Configuração dos PCs
  Atribuição de endereços IPv6 estáticos

- Definição do gateway padrão com o endereço do roteador

- Verificação com ipconfig para confirmar atribuições

### Parte 3: Verificação de Conectividade
- Testes de ping entre PCs e roteadores usando IPv6

- Verificação das interfaces com show ipv6 interface brief

- Análise da tabela de vizinhos com show ipv6 neighbors

- Diagnóstico com traceroute IPv6

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores e PCs)

- Comandos: ipv6 address, ipv6 unicast-routing, ping, ipconfig, show ipv6 interface, show ipv6 neighbors, traceroute

### 📎 Arquivos
lab-12.9.2.pkt – Arquivo do Packet Tracer com a topologia configurada

README.md – Este documento com a descrição do laboratório

💡 Este laboratório é essencial para aplicar configurações IPv6 em dispositivos de rede, reforçando práticas modernas de endereçamento e conectividade.
