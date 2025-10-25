# 🧪 Lab 7.3.7 – Labview: A Tabela de Endereços MAC do Switch

Este laboratório tem como objetivo demonstrar como os switches de camada 2 constroem e utilizam a tabela de endereços MAC para encaminhar quadros Ethernet de forma eficiente dentro de uma rede local.

## 🎯 Objetivos do Laboratório

- Criar uma topologia com dois switches e dois PCs
- Configurar endereços IP nos dispositivos
- Observar como os switches aprendem os endereços MAC
- Visualizar e interpretar a tabela de endereços MAC
- Limpar e reconstruir a tabela com base em testes de comunicação

## 🛠️ Etapas Realizadas

### Parte 1: Criar e Configurar a Rede
- Conexão física entre os switches (S1 e S2) e os PCs (PC-A e PC-B)
- Configuração de endereços IP e máscara de sub-rede nos PCs
- Configuração básica dos switches: hostname, IP da VLAN 1, senhas de acesso

### Parte 2: Examinar a Tabela de Endereços MAC
- Execução de `ipconfig /all` nos PCs para identificar os endereços físicos (MAC)
- Uso do comando `show interface F0/1` nos switches para visualizar o endereço MAC da porta
- Execução de `show mac address-table` para listar os MACs aprendidos

### Parte 3: Limpeza e Reconstrução da Tabela
- Comando `clear mac address-table dynamic` para limpar a tabela
- Execução de testes de ping entre os dispositivos para forçar o aprendizado dos MACs
- Verificação da tabela atualizada com `show mac address-table`

### Parte 4: Análise ARP e Comunicação
- Execução de `arp -a` nos PCs para visualizar os pares IP/MAC aprendidos
- Verificação da resposta dos pings e análise de conectividade
- Discussão sobre como os switches lidam com MACs desconhecidos (flooding)

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (Switch e PC)
- Comandos: `ipconfig`, `arp`, `ping`, `show`, `clear`

## 📎 Arquivos

- `lab-7.3.7.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para entender como os switches operam na Camada 2, aprendem os endereços MAC e garantem a entrega eficiente dos quadros Ethernet na rede local.*
