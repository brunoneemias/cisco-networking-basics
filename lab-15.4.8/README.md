# 🌐 Lab 15.4.8 – Observar a Resolução de DNS

Este laboratório tem como objetivo explorar o processo de resolução de nomes de domínio (DNS – Domain Name System) em uma rede simulada, utilizando o Cisco Packet Tracer para observar como os dispositivos convertem nomes amigáveis em endereços IP.

## 🎯 Objetivos do Laboratório

- Compreender o funcionamento básico do DNS
- Observar a troca de mensagens entre cliente e servidor DNS
- Verificar como os nomes de domínio são resolvidos para endereços IP
- Diagnosticar falhas de resolução e corrigir configurações

## 🛠️ Etapas Realizadas

### Parte 1: Configuração da Topologia

- Inserção de PCs, servidores e roteadores na área de trabalho
- Atribuição de endereços IP estáticos
- Configuração de um servidor DNS com registros de nomes
- Definição do servidor DNS nos PCs

### Parte 2: Testes de Resolução de DNS

- Acesso a um navegador web no PC e digitação de um nome de domínio (ex: www.acad.pt)
- Observação da solicitação DNS no Simulation Mode
- Verificação da resposta do servidor DNS com o endereço IP correspondente
- Testes de conectividade com `ping` usando nome de domínio

### Parte 3: Diagnóstico e Correção

- Identificação de falhas de resolução (ex: nome não encontrado, servidor DNS ausente)
- Verificação das configurações de IP e DNS nos PCs
- Ajuste de registros DNS no servidor
- Repetição dos testes após correções

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Simulation Mode (modo de simulação de pacotes)
- Terminal CLI e navegador web nos PCs
- Serviços de rede: DNS, HTTP

## 📎 Arquivos

- `lab-15.4.8.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

---

> 💡 *Este laboratório é essencial para entender como funciona a resolução de nomes na internet, permitindo diagnosticar e configurar corretamente serviços DNS em redes locais.*
