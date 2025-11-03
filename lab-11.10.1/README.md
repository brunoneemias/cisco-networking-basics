# 🧮 Lab 11.10.1 – Packet Tracer: Projetar e Implementar um Esquema de Endereçamento com VLSM

Este laboratório tem como objetivo aplicar o conceito de **VLSM (Variable Length Subnet Masking)** para criar um esquema de endereçamento IPv4 eficiente, baseado nos requisitos de cada segmento da rede. A atividade envolve planejamento, configuração e testes de conectividade em uma topologia simulada no Cisco Packet Tracer.

## 🎯 Objetivos do Laboratório

- Planejar sub-redes com máscaras de tamanho variável (VLSM)
- Atribuir endereços IP otimizados para cada LAN e link ponto a ponto
- Configurar interfaces de roteadores e dispositivos finais
- Implementar rotas estáticas para interconectar as sub-redes
- Validar a conectividade ponta a ponta entre todos os dispositivos

## 🛠️ Etapas Realizadas

### Parte 1: Planejamento do Endereçamento com VLSM

- Análise da rede principal fornecida (ex: 192.168.0.0/24)
- Identificação do número de hosts necessários por segmento
- Cálculo das sub-redes com máscaras adequadas (ex: /30 para links ponto a ponto, /27 para LANs maiores)
- Preenchimento da tabela de endereçamento com:
  - Endereço de rede
  - Máscara de sub-rede
  - Intervalo de IPs válidos
  - Endereço de broadcast
  - Gateway padrão

### Parte 2: Configuração dos Dispositivos

- Atribuição de IPs estáticos aos PCs e interfaces dos roteadores
- Ativação das interfaces com `no shutdown`
- Configuração de descrições nas interfaces
- Verificação com `show ip interface brief`

### Parte 3: Implementação de Rotas Estáticas

- Configuração de rotas estáticas em cada roteador com o comando:
  ```bash
  ip route [rede_destino] [máscara] [próximo_salto]
  Verificação da tabela de roteamento com show ip route

- Diagnóstico de conectividade com ping e traceroute

### Parte 4: Testes e Validação
Testes de ping entre PCs em diferentes sub-redes

- Verificação da comunicação entre roteadores

- Análise de falhas e correções de IPs, máscaras ou rotas

### 🧰 Ferramentas Utilizadas
- Cisco Packet Tracer

- Terminal CLI (roteadores e PCs)

- Comandos: ip route, ping, traceroute, show ip route, show running-config, interface, ip address

### 📎 Arquivos
- lab-11.10.1.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório



💡 Este laboratório é essencial para dominar o uso de VLSM, permitindo o planejamento eficiente de endereçamento IPv4 e a configuração de redes escaláveis com múltiplos segmentos.
