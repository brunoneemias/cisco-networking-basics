# 🧪 Lab 3.7.10 – Use o Wireshark para visualizar o tráfego de rede

Este laboratório tem como objetivo capturar e analisar pacotes ICMP em uma rede local e remota utilizando o **Wireshark**, uma ferramenta poderosa de análise de tráfego de rede.

## 🎯 Objetivos do Laboratório

- Capturar pacotes ICMP locais e remotos
- Identificar endereços IP e MAC nos quadros Ethernet
- Aplicar filtros no Wireshark para facilitar a análise
- Compreender o encapsulamento de dados em diferentes camadas do modelo OSI
- Comparar o comportamento de pacotes locais e remotos

## 🛠️ Etapas Realizadas

### Parte 1: Captura de Dados Locais
- Recuperação dos endereços IP e MAC do PC com `ipconfig /all`
- Início da captura de pacotes na interface de rede com Wireshark
- Aplicação do filtro `icmp` para visualizar apenas pacotes de ping
- Execução de `ping` para outro PC na LAN
- Análise dos quadros capturados: origem e destino IP/MAC

### Parte 2: Captura de Dados Remotos
- Execução de `ping` para sites externos: `www.yahoo.com`, `www.cisco.com`, `www.google.com`
- Observação da resolução DNS e conversão de URLs em IPs
- Análise dos pacotes ICMP gerados e comparação com os pacotes locais

### Parte 3: Análise dos Dados
- Identificação dos endereços IP e MAC nos quadros Ethernet
- Verificação do encapsulamento: ICMP → IPv4 → Ethernet II
- Discussão sobre por que o Wireshark mostra MACs reais apenas para hosts locais

## 🧰 Ferramentas Utilizadas

- Wireshark
- Prompt de Comando (Windows)
- Rede LAN com múltiplos PCs

> 💡 *Este laboratório é essencial para compreender como os dados trafegam em uma rede e como ferramentas de análise como o Wireshark podem ser utilizadas para diagnóstico e aprendizado técnico.*
