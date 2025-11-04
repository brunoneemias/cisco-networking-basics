# 🧪 Lab 17.7.7 – Packet Tracer: Solucionar Problemas de Conectividade – Modo Físico

Este laboratório tem como objetivo diagnosticar e corrigir problemas de conectividade em uma rede simulada no Cisco Packet Tracer, utilizando o **Modo Físico** para inspecionar cabos, conexões e dispositivos. A atividade reforça a importância da verificação visual e física na solução de problemas de rede.

## 🎯 Objetivos do Laboratório

- Identificar falhas de conectividade causadas por problemas físicos
- Utilizar o Modo Físico do Packet Tracer para inspecionar conexões
- Corrigir cabos mal conectados, portas erradas ou dispositivos desligados
- Validar a comunicação entre dispositivos após os ajustes

## 🛠️ Etapas Realizadas

### Parte 1: Análise Inicial no Modo Lógico

- Verificação da topologia e dos endereços IP atribuídos
- Testes de conectividade com `ping` entre PCs e roteadores
- Identificação de falhas de comunicação

### Parte 2: Diagnóstico no Modo Físico

- Alternância para o Modo Físico no Packet Tracer
- Inspeção visual dos cabos conectados:
  - Verificação de tipo de cabo (crossover, direto, console)
  - Verificação de portas corretas (FastEthernet, GigabitEthernet)
- Identificação de dispositivos desligados ou desconectados
- Correção de conexões físicas e ativação de dispositivos

### Parte 3: Validação da Conectividade

- Retorno ao Modo Lógico
- Repetição dos testes de `ping` e `traceroute`
- Confirmação da comunicação entre todos os dispositivos
- Verificação com comandos:
  ```bash
  show ip interface brief
  show ip route

## 🧰 Ferramentas Utilizadas
-  Cisco Packet Tracer

-  Modo Físico e Modo Lógico

-  Terminal CLI (PCs, switches e roteadores)

-  Comandos: ping, traceroute, show ip interface, show ip route

###📎 Arquivos
-  lab-17.7.7.pkt – Arquivo do Packet Tracer com a topologia configurada

-  README.md – Este documento com a descrição do laboratório

-  Capturas de tela do Modo Físico e correções aplicadas (opcional)

💡 Este laboratório é essencial para desenvolver habilidades de troubleshooting em redes, combinando análise lógica com inspeção física para garantir conectividade total.
