# 🧪 Lab 17.4.6 – Testar a Latência da Rede com Ping e Traceroute

Este laboratório tem como objetivo medir e analisar a latência em uma rede simulada utilizando os comandos **ping** e **traceroute** no Cisco Packet Tracer. A atividade permite observar o tempo de resposta entre dispositivos e identificar possíveis gargalos ou falhas de comunicação.

## 🎯 Objetivos do Laboratório

- Medir a latência entre dispositivos de rede
- Utilizar ping para verificar tempo de resposta e conectividade
- Utilizar traceroute para mapear o caminho dos pacotes
- Identificar saltos intermediários e tempos de cada salto
- Diagnosticar problemas de desempenho na rede

## 🛠️ Etapas Realizadas

### Parte 1: Configuração da Topologia

- Inserção de PCs, switches e roteadores
- Atribuição de endereços IP estáticos
- Verificação de conectividade básica entre dispositivos

### Parte 2: Testes com Ping

- Execução do comando `ping` entre diferentes dispositivos
- Análise do tempo de resposta (em milissegundos)
- Verificação de perda de pacotes e variação de latência
- Comparação entre dispositivos na mesma sub-rede e em sub-redes diferentes

### Parte 3: Testes com Traceroute

- Execução do comando `tracert` (Windows) ou `traceroute` (roteadores Cisco)
- Identificação dos roteadores intermediários entre origem e destino
- Análise do tempo de resposta por salto
- Verificação de possíveis atrasos ou falhas em segmentos da rede

### Parte 4: Diagnóstico e Otimização

- Identificação de dispositivos com latência elevada
- Verificação de configurações incorretas ou interfaces inativas
- Discussão sobre fatores que afetam a latência (congestionamento, distância, roteamento)
- Propostas de melhoria na topologia ou configuração

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (PCs e roteadores)
- Comandos: `ping`, `traceroute`, `tracert`, `show ip interface`, `show ip route`

## 📎 Arquivos

- `lab-17.4.6.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para compreender como medir e interpretar a latência em redes IP, utilizando ferramentas simples e eficazes para diagnóstico e otimização de desempenho.*
