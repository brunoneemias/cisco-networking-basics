# 📡 Lab 14.8.1 – Packet Tracer: Comunicações TCP e UDP

Este laboratório tem como objetivo explorar o funcionamento dos protocolos de transporte **TCP (Transmission Control Protocol)** e **UDP (User Datagram Protocol)** em uma rede simulada no Cisco Packet Tracer. A atividade permite observar como os dois protocolos se comportam em diferentes cenários de comunicação entre dispositivos.

## 🎯 Objetivos do Laboratório

- Compreender as diferenças entre TCP e UDP
- Simular comunicações entre clientes e servidores usando ambos os protocolos
- Observar o processo de estabelecimento de conexão TCP (three-way handshake)
- Verificar a entrega de dados e confiabilidade dos protocolos
- Utilizar ferramentas de simulação para analisar pacotes e fluxos de dados

## 🛠️ Etapas Realizadas

### Parte 1: Configuração da Topologia

- Inserção de PCs, servidores e roteadores na área de trabalho
- Conexão dos dispositivos com cabos apropriados
- Atribuição de endereços IP estáticos
- Configuração de serviços nos servidores (HTTP, DNS, FTP, etc.)

### Parte 2: Comunicação TCP

- Simulação de acesso a serviços como HTTP e FTP
- Observação do processo de conexão TCP (SYN, SYN-ACK, ACK)
- Verificação da confiabilidade e controle de fluxo
- Análise de pacotes com a ferramenta Simulation Mode

### Parte 3: Comunicação UDP

- Simulação de serviços como DNS e streaming
- Observação da ausência de conexão prévia
- Verificação da entrega rápida e sem confirmação
- Comparação com o comportamento do TCP

### Parte 4: Análise Comparativa

- Identificação das principais diferenças entre TCP e UDP:
  - Confiabilidade
  - Ordem de entrega
  - Controle de congestionamento
  - Velocidade e overhead
- Discussão sobre aplicações ideais para cada protocolo

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Simulation Mode (modo de simulação de pacotes)
- Terminal CLI e navegador web nos PCs
- Serviços de rede: HTTP, FTP, DNS, DHCP

## 📎 Arquivos

- `lab-14.8.1.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para entender como os protocolos TCP e UDP operam na prática, permitindo a escolha adequada conforme os requisitos de confiabilidade e desempenho de cada aplicação.*
