# 🧪 Lab 7.1.6 – Use o Wireshark para examinar os quadros Ethernet

Este laboratório tem como objetivo capturar e analisar quadros Ethernet II utilizando o **Wireshark**, permitindo a compreensão da estrutura de um quadro na Camada 2 do modelo OSI e a identificação de protocolos como ARP e ICMP.

## 🎯 Objetivos do Laboratório

- Examinar os campos do cabeçalho de um quadro Ethernet II
- Capturar pacotes locais e remotos com o Wireshark
- Identificar endereços MAC de origem e destino
- Analisar protocolos encapsulados como ARP e ICMP
- Compreender o processo de encapsulamento na Camada 2

## 🛠️ Etapas Realizadas

### Parte 1: Análise dos Campos do Quadro Ethernet II
- Estudo dos campos: preâmbulo, endereço de destino, endereço de origem, tipo de quadro, dados e FCS
- Identificação do tipo de protocolo encapsulado (ex: 0x0806 para ARP)

### Parte 2: Captura de Quadros com Wireshark
- Configuração da interface de rede no PC
- Aplicação de filtros para visualizar apenas ARP e ICMP
- Execução de ping para o gateway padrão
- Análise dos quadros gerados: requisição ARP, resposta ARP, solicitações e respostas ICMP

### Parte 3: Interpretação dos Dados Capturados
- Identificação dos endereços MAC e IP envolvidos
- Verificação do tipo de quadro e protocolo encapsulado
- Análise dos octetos destacados no painel de bytes
- Comparação entre quadros locais e remotos

## 🧰 Ferramentas Utilizadas

- Wireshark
- Prompt de Comando (Windows)
- Rede LAN com gateway e dispositivos ativos

## 📎 Arquivos

- `lab-7.1.6.pdf` – Instruções completas do laboratório
- `README.md` – Este documento com a descrição do laboratório


> 💡 *Este laboratório é essencial para compreender como os dados são encapsulados e transmitidos na Camada 2, além de reforçar o uso do Wireshark como ferramenta de análise de tráfego de rede.*
