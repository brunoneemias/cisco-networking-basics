# 🧪 Lab 13.2.7 – Packet Tracer: Usar Ping e Traceroute para Testar a Conectividade da Rede

Este laboratório tem como objetivo utilizar os comandos **ping** e **traceroute** para verificar a conectividade entre dispositivos em uma rede IPv4 e IPv6, identificando possíveis falhas de comunicação e analisando o caminho percorrido pelos pacotes.

## 🎯 Objetivos do Laboratório

- Testar conectividade entre dispositivos usando ping
- Utilizar traceroute para identificar o caminho dos pacotes
- Diagnosticar falhas de rede e verificar gateways padrão
- Compreender o comportamento dos protocolos ICMP e IPv6

## 🛠️ Etapas Realizadas

### Parte 1: Testes com Ping

- Execução de `ping` entre PCs da mesma sub-rede
- Testes de `ping` entre PCs de sub-redes diferentes
- Verificação de resposta positiva (sucesso) ou negativa (falha)
- Análise de tempo de resposta e número de saltos

### Parte 2: Testes com Traceroute

- Execução de `tracert` (Windows) ou `traceroute` (roteadores Cisco)
- Identificação dos dispositivos intermediários entre origem e destino
- Verificação do caminho dos pacotes em redes IPv4 e IPv6
- Análise de saltos e tempo de resposta por salto

### Parte 3: Diagnóstico de Problemas

- Verificação de configurações IP e gateway com `ipconfig` e `show ip interface brief`
- Identificação de interfaces inativas ou mal configuradas
- Correção de endereços IP, máscaras ou gateways padrão
- Repetição dos testes após ajustes

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (PCs e roteadores)
- Comandos: `ping`, `tracert`, `traceroute`, `ipconfig`, `show ip interface`, `show ipv6 interface`

## 📎 Arquivos

- `lab-13.2.7.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para validar a conectividade de rede e entender o caminho dos pacotes entre dispositivos, utilizando ferramentas fundamentais de diagnóstico como ping e traceroute.*
