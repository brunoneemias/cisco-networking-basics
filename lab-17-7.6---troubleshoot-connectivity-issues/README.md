# 🧪 Lab 17.7.6 – Solucionar Problemas de Conectividade

Este laboratório tem como objetivo aplicar técnicas de diagnóstico e correção de falhas de conectividade em uma rede simulada no Cisco Packet Tracer. A atividade permite identificar erros comuns de configuração e utilizar comandos de verificação para restaurar a comunicação entre dispositivos.

## 🎯 Objetivos do Laboratório

- Identificar e corrigir problemas de conectividade em uma rede IPv4/IPv6
- Utilizar comandos de diagnóstico como `ping`, `traceroute` e `show`
- Verificar configurações de IP, gateway e interfaces
- Aplicar boas práticas de solução de problemas em redes Cisco

## 🛠️ Etapas Realizadas

### Parte 1: Análise Inicial da Rede

- Verificação da topologia e dos dispositivos conectados
- Identificação de falhas de comunicação entre PCs, switches e roteadores
- Testes iniciais com `ping` para detectar onde ocorre a interrupção

### Parte 2: Diagnóstico com Comandos Show

- Verificação de interfaces com:
  ```bash
  show ip interface brief
  show ipv6 interface brief
- Análise de tabelas de roteamento:

   ```bash
  show ip route
  show ipv6 route
- Verificação de vizinhança IPv6:

   ```bash
  show ipv6 neighbors
###  Parte 3: Correção de Configurações
- Ativação de interfaces com no shutdown

- Ajuste de endereços IP, máscaras e gateways padrão

- Correção de erros de digitação ou omissão de comandos

- Salvamento das configurações corrigidas:

   ```bash
  copy running-config startup-config
###  Parte 4: Validação Final
- Repetição dos testes de conectividade com ping e traceroute

- Confirmação da comunicação entre todos os dispositivos

- Discussão sobre o processo de troubleshooting e documentação das correções

## 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (PCs, switches e roteadores)

- Comandos: ping, traceroute, show ip interface, show ipv6 interface, show ip route, show ipv6 route, show ipv6 neighbors, copy

📎 Arquivos
- lab-17.7.6.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório

💡 Este laboratório é essencial para desenvolver habilidades práticas de solução de problemas em redes, utilizando ferramentas de diagnóstico e comandos Cisco para restaurar a conectividade.
