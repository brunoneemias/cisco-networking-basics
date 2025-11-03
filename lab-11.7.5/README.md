# 🧪 Lab 11.7.5 – Packet Tracer: Cenário de Subnetação IPv4

Este laboratório tem como objetivo aplicar os conceitos de subnetação IPv4 em um cenário prático, utilizando o Cisco Packet Tracer para configurar dispositivos de rede com base em um plano de endereçamento previamente calculado.

## 🎯 Objetivos do Laboratório

- Planejar e aplicar sub-redes IPv4 com base em requisitos de hosts
- Configurar endereços IP em PCs, switches e roteadores
- Ativar interfaces e verificar conectividade entre dispositivos
- Testar comunicação entre sub-redes distintas
- Consolidar o entendimento sobre roteamento entre sub-redes

## 🛠️ Etapas Realizadas

### Parte 1: Planejamento de Sub-redes

- Análise da rede principal fornecida (ex: 192.168.1.0/24)
- Cálculo de sub-redes com base no número de hosts por segmento
- Determinação de:
  - Endereço de rede
  - Máscara de sub-rede
  - Intervalo de IPs válidos
  - Endereço de broadcast
  - Gateway padrão

### Parte 2: Configuração dos Dispositivos

- Atribuição de IPs estáticos aos PCs conforme a sub-rede
- Configuração das interfaces dos roteadores com IPs válidos
- Ativação das interfaces com `no shutdown`
- Configuração de gateway padrão nos PCs
- Verificação da configuração com `show ip interface brief`

### Parte 3: Testes de Conectividade

- Testes de `ping` entre PCs da mesma sub-rede
- Testes de `ping` entre PCs de sub-redes diferentes
- Verificação da tabela de roteamento com `show ip route`
- Diagnóstico de falhas e correções de IPs ou gateways

### Parte 4: Análise Final

- Validação da comunicação ponta a ponta
- Discussão sobre eficiência da subnetação aplicada
- Reflexão sobre escalabilidade e organização da rede

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (PCs e roteadores)
- Comandos: `ipconfig`, `ping`, `show`, `interface`, `ip address`, `no shutdown`

## 📎 Arquivos

- `lab-11.7.5.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório
- Tabela de sub-redes e capturas de tela (opcional)

---

> 💡 *Este laboratório é essencial para aplicar subnetação IPv4 em cenários reais, promovendo o uso eficiente de endereços IP e o domínio da configuração de redes segmentadas.*
