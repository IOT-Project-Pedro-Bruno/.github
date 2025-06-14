# Sistema de Monitorização para Abrigos de Cães e Armazém

Este projeto tem como objetivo a monitorização remota de dois abrigos de cães e de um armazém, recorrendo a microcontroladores e comunicação em rede. O sistema permite recolher, transmitir e visualizar dados ambientais e de consumo de forma eficiente, através de uma interface acessível e interativa.

## ✨ Funcionalidades Principais

- Monitorização de:
  - Temperatura e humidade
  - Nível de água nos bebedouros
  - Stock de ração nos comedouros
- Transmissão de dados em tempo real para servidor central (Raspberry Pi)
- Armazenamento dos dados numa base de dados InfluxDB (séries temporais)
- Interface gráfica com:
  - Node-RED para visualização e controlo
  - Grafana para dashboards históricos
- Bot Telegram integrado para consulta rápida dos dados mais recentes
- Envio de alertas por e-mail com base em limites configuráveis

## 🧠 Arquitetura do Sistema

![IOT drawio](https://github.com/user-attachments/assets/0b574956-1cf8-4ec3-bd08-95240590f4c6)

- **Microcontroladores utilizados:**
  - PIC32 e ESP8266 (casotas)
  - PIC18 (armazém)
- **Comunicação:**
  - TCP/IP via Wi-Fi (ESP-01)
- **Servidor central:**
  - Raspberry Pi com Node-RED, InfluxDB e Grafana

## 📁 Conteúdo do Repositório

Este repositório contém:

- Firmware dos microcontroladores
- Ficheiros `.json` com os fluxos do Node-RED (incluindo o bot do Telegram)




