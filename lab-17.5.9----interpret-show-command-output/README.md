# 🧪 Lab 17.5.9 – Packet Tracer: Interpretar a Saída de Comandos Show

Este laboratório tem como objetivo desenvolver a habilidade de interpretar corretamente a saída dos comandos de diagnóstico **show** em dispositivos Cisco, utilizando o Cisco Packet Tracer para analisar o estado da rede, interfaces, tabelas de roteamento e conectividade.

## 🎯 Objetivos do Laboratório

- Utilizar comandos show para verificar o status dos dispositivos
- Interpretar informações sobre interfaces, endereçamento IP e protocolos
- Diagnosticar problemas de conectividade com base na saída dos comandos
- Compreender o funcionamento interno dos dispositivos de rede

## 🛠️ Etapas Realizadas

### Parte 1: Comandos Show em Interfaces

- Verificação do estado das interfaces com:
  ```bash
  show ip interface brief
  show ipv6 interface brief
- Identificação de interfaces ativas/inativas e endereços atribuídos

### Parte 2: Verificação de Roteamento
- Análise das tabelas de roteamento:

   ```bash
  show ip route
  show ipv6 route
- Identificação de rotas diretamente conectadas, estáticas e dinâmicas

### Parte 3: Diagnóstico de Conectividade
- Verificação de vizinhança IPv6:

   ```bash
  show ipv6 neighbors
- Verificação de sessões SSH e usuários conectados:

   ```bash
  show users
  show ip ssh
### Parte 4: Análise de Configuração
- Exibição da configuração atual:

   ```bash
  show running-config
- Verificação de senhas, banners, hostname, serviços ativos

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores e switches)

- Comandos: show ip interface, show ipv6 interface, show ip route, show ipv6 route, show running-config, show users, show ip ssh, show ipv6 neighbors

### 📎 Arquivos
- lab-17.5.9.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório

💡 Este laboratório é essencial para interpretar corretamente os comandos de diagnóstico em dispositivos Cisco, permitindo identificar e resolver problemas de rede com precisão.

Code
