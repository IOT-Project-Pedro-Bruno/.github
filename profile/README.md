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


Fotos:

![cb62a312-4557-4269-8d9f-3e7e6808e453](https://github.com/user-attachments/assets/8e5c2a86-f578-47bd-b717-da8173d2384a)
![0b48c79b-f![754ba32e-e898-44e4-b1f6-4f9abbe22ba4](https://github.com/user-attachments/assets/94a69262-00b6-4941-8bed-b5e1cd62e98a)
25d-4c7f-862a-09dd195bde05](https://github.com/user-attachments/assets/6914a2d0-7b47-4bba-a615-bc23df6c0988)
![20dbb3ce-1f51-4aa2-a17e-401603fe7c74](https://github.com/user-attachments/assets/746c6bae-efc7-4e83-a02b-06957d536e68)
![d6faba71-b425-41c7-a7a3-e674133d09c2](https://github.com/user-attachments/assets/3ca568af-d517-4a15-a422-3dd55d07cd8e)
![de99b06a![52ab7223-c312-427b-8c0c-00588c5dd810](https://github.com/user-attachments/assets/3931ecd1-fb8b-4016-9fa8-48c06a0c3c5c)
-58bf-4d04-a906-0ad596c479b3](https://github.com/user-attachments/assets/6ead99e7-ddf6-4229-a430-84dcb6fa00f3)
![9608346f-d9c3-40ea-830b-1a6998bfd547](https://github.com/user-attachments/assets/b94ac972-5e1e-41b2-a798-83ebcbccfa16)
![35e64430-3902-4f09-8c7b-881426418132](https://github.com/user-attachments/assets/7266926d-a666-4412-b79b-d7996e3957ee)
![afffd981-72b2-4dcd-81d4-0cf0659ac27f](https://github.com/user-attachments/assets/fb861210-16cd-4387-8bb8-730f9e97e784)
![363c529b-34eb-4752-b36b-3fd545a65256](https://github.com/user-attachments/assets/7ddcf8ac-3eb7-4c7d-b760-cd1e6b701902)
![91cb5625-454d-4752-b67d-4d2e956717d8](https://github.com/user-attachments/assets/9e46868f-c29b-44c6-9336-b889a9422a19)

