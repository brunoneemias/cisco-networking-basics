# 🧮 Lab 11.10.2 – Projetar e Implementar um Esquema de Endereçamento com VLSM

Este laboratório tem como objetivo aplicar o conceito de **VLSM (Variable Length Subnet Masking)** para criar um esquema de endereçamento IPv4 eficiente, baseado nos requisitos de cada segmento da rede. A atividade envolve planejamento manual, preenchimento de tabelas e análise de uso de endereços.

## 🎯 Objetivos do Laboratório

- Planejar sub-redes com máscaras de tamanho variável (VLSM)
- Calcular intervalos de IPs válidos para cada sub-rede
- Preencher tabelas de endereçamento com base nos requisitos de host
- Otimizar o uso de endereços IPv4 evitando desperdício
- Consolidar o entendimento sobre subnetação avançada

## 🛠️ Etapas Realizadas

### Parte 1: Análise da Rede Principal

- Identificação da rede base fornecida (ex: 192.168.0.0/24)
- Levantamento do número de hosts necessários por segmento:
  - LANs com diferentes tamanhos
  - Links ponto a ponto entre roteadores

### Parte 2: Cálculo das Sub-redes com VLSM

- Determinação da máscara ideal para cada segmento
- Cálculo dos seguintes elementos para cada sub-rede:
  - Endereço de rede
  - Máscara de sub-rede (CIDR e decimal)
  - Intervalo de IPs válidos
  - Endereço de broadcast
  - Gateway padrão

### Parte 3: Preenchimento da Tabela de Endereçamento

- Organização das sub-redes em uma tabela clara com:
  - Nome da sub-rede
  - Endereço de rede
  - Máscara
  - Intervalo de hosts válidos
  - Endereço de broadcast

### Parte 4: Verificação e Aplicação

- Revisão dos cálculos para evitar sobreposição de sub-redes
- Discussão sobre como aplicar os endereços em uma topologia real
- Considerações sobre escalabilidade e eficiência

## 🧰 Ferramentas Utilizadas

- Calculadora de sub-rede (manual ou online)
- Papel e lápis ou planilha eletrônica
- Conhecimento de binário e conversão decimal

## 📎 Arquivos

- `lab-11.10.2.pdf` – Instruções completas do laboratório
- `README.md` – Este documento com a descrição do laboratório
- Tabela de sub-redes preenchida (opcional)

---

> 💡 *Este laboratório é essencial para dominar o planejamento de endereçamento IPv4 com VLSM, permitindo a criação de redes escaláveis e eficientes com uso inteligente de espaço de endereçamento.*
