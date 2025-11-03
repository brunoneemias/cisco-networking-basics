# 🧪 Lab 12.7.4 – Identificar Endereços IPv6

Este laboratório tem como objetivo desenvolver a habilidade de reconhecer e interpretar diferentes tipos de endereços IPv6 em uma rede simulada, utilizando o Cisco Packet Tracer e comandos de diagnóstico para análise de conectividade e estrutura de endereçamento.

## 🎯 Objetivos do Laboratório

- Identificar os diferentes tipos de endereços IPv6:
  - Global Unicast
  - Link-local
  - Multicast
- Reconhecer a estrutura e os prefixos de endereços IPv6
- Utilizar comandos para visualizar endereços atribuídos a interfaces
- Compreender como os endereços IPv6 são gerados e atribuídos

## 🛠️ Etapas Realizadas

### Parte 1: Análise de Endereços IPv6

- Acesso à CLI de PCs e roteadores
- Uso do comando `ipconfig` nos PCs para visualizar endereços IPv6
- Uso do comando `show ipv6 interface brief` nos roteadores
- Identificação de endereços link-local (prefixo FE80::/10)
- Verificação de endereços globais (ex: 2001:DB8::/32)

### Parte 2: Classificação dos Endereços

- Classificação dos endereços observados:
  - Endereço de rede
  - Endereço de host
  - Endereço de gateway
  - Endereço de broadcast (não utilizado no IPv6)
- Análise dos prefixos e sufixos dos endereços
- Discussão sobre a geração automática de endereços link-local

### Parte 3: Testes de Conectividade

- Testes de `ping` entre dispositivos usando endereços IPv6
- Verificação da tabela de vizinhos com `show ipv6 neighbors`
- Diagnóstico de conectividade com `traceroute` IPv6

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (PCs e roteadores)
- Comandos: `ipconfig`, `ping`, `show ipv6 interface`, `show ipv6 neighbors`, `traceroute`

## 📎 Arquivos

- `lab-12.7.4.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para reconhecer e interpretar endereços IPv6 em ambientes de rede, fortalecendo a base para configurações e diagnósticos avançados.*
