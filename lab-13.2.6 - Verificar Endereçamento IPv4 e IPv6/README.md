# 🧪 Lab 13.2.6 – Packet Tracer: Verificar Endereçamento IPv4 e IPv6

Este laboratório tem como objetivo validar a configuração de endereços IPv4 e IPv6 em uma rede simulada no Cisco Packet Tracer, utilizando comandos de diagnóstico para garantir que os dispositivos estejam corretamente configurados e conectados.

## 🎯 Objetivos do Laboratório

- Verificar endereços IPv4 e IPv6 atribuídos a interfaces de rede
- Confirmar gateways padrão e conectividade entre dispositivos
- Utilizar comandos de verificação e diagnóstico
- Identificar e corrigir erros de configuração de endereçamento

## 🛠️ Etapas Realizadas

### Parte 1: Verificação de Endereçamento IPv4

- Acesso à CLI dos PCs e roteadores
- Uso do comando `ipconfig` nos PCs para verificar:
  - Endereço IPv4
  - Máscara de sub-rede
  - Gateway padrão
- Testes de conectividade com `ping` entre dispositivos IPv4
- Verificação das interfaces com `show ip interface brief`

### Parte 2: Verificação de Endereçamento IPv6

- Uso do comando `ipconfig` para visualizar endereços IPv6 nos PCs
- Verificação das interfaces dos roteadores com `show ipv6 interface brief`
- Identificação de endereços globais e link-local
- Testes de conectividade com `ping` usando IPv6
- Diagnóstico com `show ipv6 route` e `show ipv6 neighbors`

### Parte 3: Correção de Configurações

- Identificação de erros como:
  - Endereços incorretos
  - Máscaras incompatíveis
  - Gateways ausentes
- Ajustes nas configurações de IP e ativação de interfaces com `no shutdown`
- Salvamento das configurações com `copy running-config startup-config`

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (PCs, switches e roteadores)
- Comandos: `ipconfig`, `ping`, `show ip interface`, `show ipv6 interface`, `show ipv6 route`, `show ipv6 neighbors`, `traceroute`

## 📎 Arquivos

- `lab-13.2.6.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para validar configurações de endereçamento IPv4 e IPv6, garantindo que todos os dispositivos estejam corretamente integrados à rede.*
