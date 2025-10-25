# 🧪 Lab 3.5.5 – Packet Tracer: Rastreador de pacotes – Investigue os modelos TCP/IP e OSI em ação

Este laboratório tem como objetivo explorar o processo de encapsulamento de dados em uma rede, utilizando o modo de simulação do **Cisco Packet Tracer** para visualizar como os pacotes se comportam em cada camada dos modelos OSI e TCP/IP.

## 🎯 Objetivos do Laboratório

- Examinar o tráfego Web via protocolo HTTP
- Visualizar os elementos da suíte de protocolos TCP/IP
- Compreender o encapsulamento de dados em cada camada
- Identificar as PDUs (Protocol Data Units) associadas às camadas OSI e TCP/IP
- Utilizar filtros de eventos e ferramentas de inspeção de pacotes

## 🛠️ Etapas Realizadas

### Parte 1: Tráfego Web via HTTP
- Alternância do modo Realtime para Simulation
- Aplicação de filtros para exibir apenas eventos HTTP
- Geração de tráfego Web simulando acesso ao site `www.osi.local`
- Captura e avanço dos pacotes para análise detalhada

### Parte 2: Análise das Camadas OSI
- Inspeção das PDUs em cada camada (Camada 7 até Camada 1)
- Identificação de informações como:
  - Porta de destino (Camada 4)
  - Endereço IP de destino (Camada 3)
  - Endereço MAC de destino (Camada 2)

### Parte 3: Detalhes da PDU de saída
- Visualização dos formatos de encapsulamento no modelo TCP/IP
- Análise das seções Ethernet II, IP, TCP e HTTP
- Comparação entre os dados exibidos nas guias OSI Model e PDU Details

### Parte 4: Protocolos Adicionais
- Ativação de filtros para exibir DNS, ARP e TCP
- Análise de eventos DNS e resposta de resolução de nomes
- Verificação de sessões TCP estabelecidas e encerradas

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer (modo Simulation)
- Navegador Web interno do PT
- Painel de Simulação e Filtros de Eventos

> 💡 *Este laboratório é fundamental para entender como os dados são encapsulados e transmitidos em uma rede, e como cada camada dos modelos OSI e TCP/IP contribui para a comunicação entre dispositivos.*
