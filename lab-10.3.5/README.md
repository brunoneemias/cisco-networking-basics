# 🧪 Lab 10.3.5 – Packet Tracer: Solucionar problemas de gateway padrão

Este laboratório tem como objetivo aplicar uma abordagem metódica para identificar e corrigir problemas de conectividade relacionados à configuração de gateways padrão em uma rede local com múltiplos dispositivos.

## 🎯 Objetivos do Laboratório

- Verificar a documentação de rede e identificar falhas
- Testar conectividade local e remota entre dispositivos
- Corrigir configurações incorretas de IP e gateway padrão
- Implementar e validar soluções de rede
- Documentar problemas e correções aplicadas

## 🛠️ Etapas Realizadas

### Parte 1: Verificar a Documentação de Rede

- Análise da tabela de endereçamento para identificar campos ausentes
- Preenchimento dos gateways padrão para switches e PCs
- Testes de conectividade local (ex: PC1 ↔ PC2, PC1 ↔ S1)
- Registro de problemas detectados e hipóteses de causa

### Parte 2: Implementar Soluções

- Correção de endereços IP incorretos nos PCs
- Configuração dos gateways padrão ausentes
- Verificação das interfaces dos switches e roteadores
- Testes de ping para validar conectividade local

### Parte 3: Testar Conectividade Remota

- Ping entre dispositivos de redes diferentes (ex: PC1 ↔ PC4)
- Verificação da rota entre os dispositivos e atuação do roteador
- Confirmação de que os gateways padrão permitem comunicação entre redes

### Parte 4: Documentar Soluções

- Registro das alterações realizadas
- Marcação de problemas resolvidos na tabela de verificação
- Análise final da conectividade ponta a ponta

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (PCs, switches, roteadores)
- Comandos: `ipconfig`, `ping`, `show ip interface brief`, `show running-config`

## 📎 Arquivos

- `lab-10.3.5.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para desenvolver habilidades de diagnóstico e solução de problemas em redes, utilizando uma abordagem estruturada para garantir conectividade entre dispositivos locais e remotos.*
