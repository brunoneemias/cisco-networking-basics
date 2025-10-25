# 🧪 Lab 9.1.3 – Packet Tracer: Identificação de Endereços MAC e IP

Este laboratório tem como objetivo observar o comportamento dos pacotes em uma rede local e remota, utilizando o modo de simulação do **Cisco Packet Tracer** para identificar os endereços MAC e IP envolvidos na comunicação entre dispositivos.

## 🎯 Objetivos do Laboratório

- Coletar informações de PDUs (Protocol Data Units) em redes locais e remotas
- Identificar os endereços MAC e IP de origem e destino
- Compreender o processo de encapsulamento de dados nas camadas OSI
- Analisar o papel de dispositivos como switches, hubs, roteadores e pontos de acesso

## 🛠️ Etapas Realizadas

### Parte 1: Comunicação em Rede Local

- Execução do comando `ping` entre dois dispositivos da mesma rede (ex: 172.16.31.5 → 172.16.31.2)
- Ativação do modo de simulação e captura da PDU gerada
- Inspeção dos campos:
  - Endereço MAC de origem e destino
  - Endereço IP de origem e destino
  - Dispositivo atual
- Avanço da PDU com `Capture/Forward` até o destino final
- Registro das informações em uma tabela de análise

### Parte 2: Comunicação com Rede Remota

- Execução do comando `ping` de um host local para um IP remoto (ex: 172.16.31.5 → 10.10.10.2)
- Identificação do gateway e dos dispositivos intermediários
- Análise dos endereços MAC e IP em cada salto
- Verificação da troca de endereços MAC ao atravessar o roteador

### Parte 3: Questões para Reflexão

- Tipos de cabos utilizados e seu impacto na comunicação
- Comportamento de hubs e pontos de acesso sem fio
- Perda ou alteração de endereços durante a transmissão
- Camadas OSI envolvidas em cada dispositivo
- Diferença entre comunicação local e remota

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer (modo simulação)
- Terminal CLI (Prompt de Comando)
- Painel de PDU Details e OSI Model

## 📎 Arquivos

- `lab-9.1.3.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório


> 💡 *Este laboratório é essencial para entender como os dados são encapsulados e transmitidos em redes locais e remotas, além de reforçar o papel dos endereços MAC e IP na comunicação entre dispositivos.*
