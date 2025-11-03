# 🧪 Lab 12.9.1 – Packet Tracer: Implementar um Esquema de Endereçamento IPv6 com Sub-redes

Este laboratório tem como objetivo aplicar o conceito de subnetação em redes IPv6, utilizando o Cisco Packet Tracer para planejar, configurar e testar um esquema de endereçamento eficiente com base em requisitos específicos de rede.

## 🎯 Objetivos do Laboratório

- Planejar sub-redes IPv6 com base em um prefixo global
- Atribuir endereços IPv6 a interfaces de roteadores e PCs
- Ativar interfaces e configurar roteamento IPv6
- Verificar conectividade entre dispositivos usando comandos de diagnóstico
- Consolidar o entendimento sobre hierarquia e agregação de endereços IPv6

## 🛠️ Etapas Realizadas

### Parte 1: Planejamento do Endereçamento IPv6

- Análise do prefixo global fornecido (ex: 2001:DB8:ACAD::/48)
- Criação de sub-redes /64 para cada segmento da rede
- Atribuição de endereços IPv6 válidos para:
  - Interfaces de roteadores
  - Interfaces de switches (VLANs, se aplicável)
  - Dispositivos finais (PCs)

### Parte 2: Configuração dos Dispositivos

- Configuração das interfaces dos roteadores com:
  ```bash
  interface g0/0
  ipv6 address 2001:DB8:ACAD:1::1/64
  no shutdown
- Configuração dos PCs com endereços IPv6 estáticos e gateway padrão

### Parte 3: Verificação de Conectividade
- Testes de ping entre dispositivos usando endereços IPv6

- Verificação das interfaces com show ipv6 interface brief

- Análise da tabela de roteamento com show ipv6 route

- Diagnóstico de vizinhança com show ipv6 neighbors

### 🧰 Ferramentas Utilizadas
Cisco Packet Tracer

- Terminal CLI (roteadores e PCs)

- Comandos: ipv6 address, ipv6 unicast-routing, ping, show ipv6 interface, show ipv6 route, traceroute

###📎 Arquivos
lab-12.9.1.pkt – Arquivo do Packet Tracer com a topologia configurada

README.md – Este documento com a descrição do laboratório

💡 Este laboratório é essencial para aplicar subnetação em redes IPv6, promovendo um planejamento eficiente e escalável de endereçamento em ambientes corporativos ou acadêmicos.
