# 🧪 Lab 17.8.3 – Packet Tracer: Desafio de Solução de Problemas

Este laboratório representa um desafio prático final, no qual o aluno deve aplicar suas habilidades de diagnóstico e correção de falhas em uma rede simulada no Cisco Packet Tracer. A atividade exige análise crítica, domínio dos comandos de verificação e capacidade de restaurar a conectividade em uma topologia com múltiplos erros.

## 🎯 Objetivos do Laboratório

- Identificar e corrigir problemas de conectividade em uma rede IPv4/IPv6
- Utilizar comandos de diagnóstico para localizar falhas
- Aplicar correções em interfaces, endereçamento, roteamento e serviços
- Validar a comunicação entre todos os dispositivos após os ajustes

## 🛠️ Etapas Realizadas

### Parte 1: Análise da Topologia

- Estudo da estrutura da rede simulada
- Identificação de dispositivos com falhas de comunicação
- Testes iniciais com `ping` e `traceroute` para mapear os pontos de falha

### Parte 2: Diagnóstico com Comandos Show

- Verificação de interfaces:
  ```bash
  show ip interface brief
  show ipv6 interface brief
- Análise de tabelas de roteamento:

   ```bas
  show ip route
  show ipv6 route
- Verificação de vizinhança IPv6:

   ```bash
  show ipv6 neighbors
- Inspeção da configuração atual:

   ```bash
  show running-config
### Parte 3: Correção de Configurações
- Ativação de interfaces com no shutdown

- Ajuste de endereços IP, máscaras e gateways

- Correção de rotas estáticas ou dinâmicas

- Verificação de serviços como DHCP, DNS e SSH (se aplicável)

### Parte 4: Validação Final
- Repetição dos testes de conectividade

- Confirmação da comunicação ponta a ponta

- Documentação das correções aplicadas e justificativas técnicas

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores, switches e PCs)

- Comandos: ping, traceroute, show ip interface, show ipv6 interface, show ip route, show ipv6 route, show running-config, show ipv6 neighbors, copy running-config startup-config

### 📎 Arquivos
- lab-17.8.3.pkt – Arquivo do Packet Tracer com a topologia com falhas

- README.md – Este documento com a descrição do laboratório

💡 Este laboratório é essencial para consolidar as habilidades de troubleshooting em redes Cisco, desafiando o aluno a restaurar a funcionalidade de uma rede com múltiplos problemas.
