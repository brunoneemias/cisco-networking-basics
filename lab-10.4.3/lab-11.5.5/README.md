# 🧪 Lab 11.5.5 – Packet Tracer: Subnetear uma rede IPv4

Este laboratório tem como objetivo aplicar o conceito de **sub-redes IPv4** em uma rede corporativa simulada no Cisco Packet Tracer, realizando o planejamento de endereçamento, configuração de dispositivos e testes de conectividade.

## 🎯 Objetivos do Laboratório

- Calcular sub-redes com base em requisitos de hosts
- Atribuir endereços IP válidos a PCs, switches e roteadores
- Configurar interfaces de rede com os endereços atribuídos
- Verificar conectividade entre dispositivos usando `ping`
- Compreender o impacto da subnetação no roteamento

## 🛠️ Etapas Realizadas

### Parte 1: Planejamento de Sub-redes

- Análise da rede principal fornecida (ex: 192.168.1.0/24)
- Identificação do número de sub-redes e hosts necessários
- Cálculo de máscara de sub-rede apropriada (ex: /27, /28)
- Determinação de intervalos de IP válidos para cada sub-rede
- Preenchimento da tabela de endereçamento com:
  - Endereço de rede
  - Primeiro e último IP utilizável
  - Gateway padrão
  - Broadcast

### Parte 2: Configuração dos Dispositivos

- Atribuição de endereços IP estáticos aos PCs
- Configuração das interfaces dos roteadores com IPs válidos
- Ativação das interfaces com `no shutdown`
- Verificação da configuração com `show ip interface brief`

### Parte 3: Testes de Conectividade

- Testes de `ping` entre PCs da mesma sub-rede
- Testes de `ping` entre PCs de sub-redes diferentes
- Verificação da tabela de roteamento com `show ip route`
- Diagnóstico de falhas de conectividade e correção de IPs ou gateways

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (PCs e roteadores)
- Comandos: `ipconfig`, `ping`, `show`, `interface`, `ip address`, `no shutdown`

## 📎 Arquivos

- `lab-11.5.5.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório
- Tabela de sub-redes e capturas de tela (opcional)

---

> 💡 *Este laboratório é essencial para dominar o processo de subnetação IPv4, permitindo o uso eficiente de endereços IP e o controle da comunicação entre diferentes segmentos de rede.*
