# 🧪 Lab 10.4.3 – Packet Tracer: Construir uma rede de switch e roteador – Modo Físico

Este laboratório tem como objetivo montar fisicamente uma rede com switches, roteadores e PCs no **modo físico do Cisco Packet Tracer**, realizando a configuração dos dispositivos e verificando a conectividade entre eles.

## 🎯 Objetivos do Laboratório

- Montar a topologia física com roteador, switch e PCs
- Configurar endereços IPv4 e IPv6 nos dispositivos
- Ativar interfaces e aplicar descrições
- Proteger o acesso ao roteador com senhas e banner
- Verificar conectividade entre os dispositivos

## 🛠️ Etapas Realizadas

### Parte 1: Configurar a Topologia

- Mover roteador e switch para o rack
- Posicionar os PCs na bancada
- Conectar os dispositivos com cabos apropriados
- Ligar todos os equipamentos

### Parte 2: Configurar os Dispositivos

#### Roteador R1
- Atribuição de hostname
- Configuração de senhas:
  - `enable secret class`
  - `console` e `vty` com senha `cisco`
- Criptografia de senhas com `service password-encryption`
- Criação de banner de aviso com `banner motd`
- Configuração das interfaces G0/0/0 e G0/0/1 com IPv4 e IPv6
- Ativação das interfaces com `no shutdown`
- Descrição das interfaces indicando os dispositivos conectados
- Ativação do roteamento IPv6 com `ipv6 unicast-routing`
- Salvamento da configuração com `copy running-config startup-config`
- Configuração do relógio do roteador

#### Switch S1
- Atribuição de hostname
- Configuração da interface VLAN 1 com IP e IPv6
- Definição do gateway padrão
- Ativação da interface VLAN
- Salvamento da configuração

#### PCs
- Atribuição de IP estático, máscara e gateway padrão
- Testes de conectividade com `ping`

### Parte 3: Verificar Conectividade

- Teste de ping entre PC-A e PC-B
- Teste de ping entre switch e PCs
- Verificação da tabela de roteamento com `show ip route` e `show ipv6 route`
- Análise das interfaces com `show ip interface brief` e `show ipv6 interface brief`

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer (modo físico)
- Terminal CLI (roteador, switch, PCs)
- Comandos: `ping`, `show`, `interface`, `ip address`, `ipv6 address`, `hostname`, `banner`, `copy`

## 📎 Arquivos

- `lab-10.4.3.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para consolidar conhecimentos sobre montagem física de redes, configuração de dispositivos Cisco e verificação de conectividade em ambientes IPv4 e IPv6.*
