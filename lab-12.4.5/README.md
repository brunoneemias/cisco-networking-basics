# 🧪 Lab 12.4.5 – Packet Tracer: Configuração Básica de Dispositivos

Este laboratório tem como objetivo realizar a configuração inicial de dispositivos de rede Cisco, como switches e roteadores, utilizando o Cisco Packet Tracer. A atividade foca em boas práticas de segurança, organização e conectividade básica.

## 🎯 Objetivos do Laboratório

- Atribuir nomes aos dispositivos
- Configurar senhas de acesso locais e remotas
- Criar mensagens de aviso (banner MOTD)
- Ativar interfaces e atribuir endereços IP
- Verificar conectividade entre dispositivos

## 🛠️ Etapas Realizadas

### Parte 1: Configuração do Roteador

- Alteração do nome do dispositivo com `hostname`
- Configuração de senhas:
  - `enable secret`
  - `line console 0` e `line vty 0 4` com senha e login
- Criptografia de senhas com `service password-encryption`
- Criação de banner de aviso com `banner motd`
- Configuração de interfaces com IP e `no shutdown`
- Salvamento da configuração com `copy running-config startup-config`

### Parte 2: Configuração do Switch

- Alteração do nome do switch com `hostname`
- Configuração da interface VLAN 1 com IP e gateway padrão
- Ativação da VLAN com `no shutdown`
- Aplicação das mesmas práticas de segurança (senhas, banner, criptografia)
- Salvamento da configuração

### Parte 3: Configuração dos PCs

- Atribuição de endereços IP estáticos
- Definição de gateway padrão
- Testes de conectividade com `ping`

### Parte 4: Verificação e Diagnóstico

- Uso de comandos como:
  - `show ip interface brief`
  - `show running-config`
  - `ping` entre dispositivos
- Validação da comunicação entre PCs, switches e roteadores

## 🧰 Ferramentas Utilizadas

- Cisco Packet Tracer
- Terminal CLI (roteadores, switches e PCs)
- Comandos: `hostname`, `enable secret`, `line`, `banner`, `interface`, `ip address`, `no shutdown`, `copy`, `ping`, `show`

## 📎 Arquivos

- `lab-12.4.5.pkt` – Arquivo do Packet Tracer com a topologia configurada
- `README.md` – Este documento com a descrição do laboratório

> 💡 *Este laboratório é essencial para consolidar as práticas iniciais de configuração em dispositivos Cisco, garantindo segurança, organização e conectividade básica na rede.*
