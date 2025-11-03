# 🧮 Lab 11.6.6 – Calcular Sub-redes IPv4

Este laboratório tem como objetivo desenvolver habilidades práticas no cálculo de sub-redes IPv4, utilizando técnicas de sub-rede de tamanho fixo (FLSM – Fixed Length Subnet Masking) para dividir uma rede maior em sub-redes menores, com base em requisitos de número de hosts.

## 🎯 Objetivos do Laboratório

- Compreender os fundamentos da subnetação IPv4
- Calcular sub-redes com base em diferentes tamanhos de rede
- Determinar endereços de rede, broadcast e intervalos válidos de host
- Aplicar máscaras de sub-rede adequadas para diferentes cenários
- Preencher tabelas de sub-redes com precisão

## 🛠️ Etapas Realizadas

### Parte 1: Análise da Rede Principal

- Identificação da rede base fornecida (ex: 192.168.100.0/24)
- Determinação do número de sub-redes necessárias
- Cálculo do número de bits de sub-rede adicionais
- Determinação da nova máscara de sub-rede (ex: /26, /27, /28)

### Parte 2: Cálculo das Sub-redes

- Cálculo dos seguintes elementos para cada sub-rede:
  - Endereço de rede
  - Primeiro e último endereço de host utilizável
  - Endereço de broadcast
  - Máscara de sub-rede em notação decimal e CIDR

### Parte 3: Preenchimento da Tabela de Sub-redes

- Organização das sub-redes em uma tabela clara com:
  - Nome da sub-rede
  - Endereço de rede
  - Máscara
  - Intervalo de hosts válidos
  - Endereço de broadcast

### Parte 4: Verificação e Aplicação

- Revisão dos cálculos para evitar sobreposição de sub-redes
- Discussão sobre como aplicar os endereços em uma topologia real
- Considerações sobre eficiência e desperdício de endereços

## 🧰 Ferramentas Utilizadas

- Calculadora de sub-rede (manual ou online)
- Papel e lápis ou planilha eletrônica
- Conhecimento de binário e conversão decimal

## 📎 Arquivos

- `lab-11.6.6.pdf` – Instruções completas do laboratório
- `README.md` – Este documento com a descrição do laboratório
- Tabela de sub-redes preenchida (opcional)

---

> 💡 *Este laboratório é essencial para dominar o planejamento de endereçamento IPv4, uma habilidade fundamental para projetar redes escaláveis e eficientes.*
