# 🧮 Lab 11.9.3 – Packet Tracer: Prática de Design e Implementação com VLSM

Este laboratório tem como objetivo aplicar o conceito de **sub-redes de comprimento variável (VLSM)** em uma rede IPv4, utilizando o Cisco Packet Tracer para planejar, configurar e testar uma topologia com múltiplos segmentos de rede e diferentes requisitos de host.

## 🎯 Objetivos do Laboratório

- Planejar sub-redes com VLSM com base em requisitos específicos de cada segmento
- Atribuir endereços IP otimizados para evitar desperdício
- Configurar interfaces de roteadores e dispositivos finais
- Implementar rotas estáticas para interconectar as sub-redes
- Verificar conectividade ponta a ponta entre todos os dispositivos

## 🛠️ Etapas Realizadas

### Parte 1: Planejamento com VLSM

- Análise da rede principal fornecida (ex: 192.168.0.0/24)
- Identificação do número de hosts necessários por segmento (LANs, links ponto a ponto)
- Cálculo das sub-redes com máscaras adequadas (ex: /30, /27, /28)
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

- Testes de ping entre PCs em diferentes sub-redes

- Verificação da comunicação entre roteadores

- Análise de falhas e correções de IPs, máscaras ou rotas

### 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer

- Terminal CLI (roteadores e PCs)

- Comandos: ip route, ping, traceroute, show ip route, show running-config, interface, ip address

### 📎 Arquivos

- lab-11.9.3.pkt – Arquivo do Packet Tracer com a topologia configurada

- README.md – Este documento com a descrição do laboratório
