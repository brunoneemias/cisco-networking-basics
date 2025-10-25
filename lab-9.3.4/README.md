# 🧪 Lab 9.3.4 – Packet Tracer: Descoberta de Vizinhos de IPv6

Este laboratório tem como objetivo explorar o processo de descoberta de vizinhos em redes IPv6, utilizando o protocolo **Neighbor Discovery Protocol (NDP)** no modo de simulação do Cisco Packet Tracer para observar como os dispositivos determinam os endereços MAC de destino.

## 🎯 Objetivos do Laboratório

- Compreender o funcionamento do protocolo NDP em redes IPv6
- Capturar e analisar PDUs ICMPv6 e NDP no modo de simulação
- Identificar os endereços MAC e IP envolvidos na comunicação
- Comparar o processo de descoberta em redes locais e remotas
- Utilizar filtros e ferramentas de inspeção para entender o encapsulamento

## 🛠️ Etapas Realizadas

### Parte 1: Descoberta de Vizinhos em Rede Local

- Limpeza da tabela de vizinhos com `clear ipv6 neighbors`
- Ativação do modo de simulação e aplicação de filtros ICMPv6 e NDP
- Execução de `ping` entre dispositivos na mesma LAN
- Captura de eventos e análise das PDUs geradas
- Identificação de endereços MAC multicast e mensagens de solicitação/resposta

### Parte 2: Descoberta de Vizinhos em Rede Remota

- Repetição do processo com dispositivos em LANs diferentes
- Observação da atuação do roteador na determinação do próximo salto
- Análise das PDUs ICMPv6 e NDP geradas entre os dispositivos e o roteador
- Verificação da tabela de vizinhos com `show ipv6 neighbors`

### Parte 3: Reflexão e Diagnóstico

- Diferença entre descoberta local e remota
- Papel do roteador na minimização do tráfego NDP
- Impacto do processo ND nos hosts da rede
- Identificação de endereços MAC aprendidos e comportamento da Camada 2

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer (modo simulação)
- Terminal CLI (Router e PCs)
- Painel de PDU Details e OSI Model

## 📎 Arquivos

- `lab-9.3.4.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para entender como os dispositivos IPv6 descobrem seus vizinhos na rede, reforçando o papel do protocolo NDP na comunicação eficiente entre hosts e roteadores.*
