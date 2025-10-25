# 🧪 Lab 7.2.7 – Endereços MAC do dispositivo de rede (Labview)

Este laboratório tem como objetivo explorar os endereços MAC atribuídos a dispositivos de rede em uma LAN Ethernet, utilizando comandos de diagnóstico em PCs e switches Cisco para identificar e analisar os componentes de um endereço MAC.

## 🎯 Objetivos do Laboratório

- Configurar dispositivos de rede e verificar conectividade
- Exibir e analisar endereços MAC em PCs e switches
- Compreender a estrutura de um endereço MAC (OUI + número de série)
- Identificar o fabricante da NIC com base no OUI
- Utilizar comandos como `ipconfig /all`, `show interfaces`, `show arp` e `show mac address-table`

## 🛠️ Etapas Realizadas

### Parte 1: Configuração da Rede
- Cabeamento da topologia com PC-A e Switch S1
- Atribuição de endereços IP e máscara de sub-rede
- Configuração da interface VLAN 1 no switch
- Teste de conectividade com `ping` entre PC e switch

### Parte 2: Análise do Endereço MAC no PC
- Execução do comando `ipconfig /all` no PC-A
- Identificação do endereço físico (MAC) da NIC
- Separação do OUI (Organizationally Unique Identifier) e número de série
- Consulta ao site da IEEE para identificar o fabricante da NIC

### Parte 3: Análise do Endereço MAC no Switch
- Acesso ao switch via console
- Execução do comando `show interfaces vlan 1` para visualizar o MAC da interface
- Uso do comando `show arp` para mapear IPs aos MACs
- Execução de `show mac address-table` para listar os MACs aprendidos nas portas

### Parte 4: Reflexão e Diagnóstico
- Identificação de broadcasts na Camada 2 (endereço MAC: `FF:FF:FF:FF:FF:FF`)
- Discussão sobre a importância de conhecer os endereços MAC na administração de redes

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (Switch e PC)
- IEEE OUI Lookup Tool

## 📎 Arquivos

- `lab-7.2.7.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório


> 💡 *Este laboratório é essencial para compreender como
