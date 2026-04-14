# Nó Multissensor LoRa com MSP430 (PCB IoT de Baixo Consumo)

## 📌 Visão Geral
Este projeto apresenta o desenvolvimento de um **nó IoT multissensor de baixo consumo** baseado no **microcontrolador MSP430FR2155**, integrando múltiplos sensores ambientais e de monitoramento em uma PCB personalizada.

O sistema foi projetado com foco em **eficiência energética**, **comunicação sem fio** e **sensoriamento modular**, sendo adequado para aplicações como monitoramento ambiental, agricultura inteligente e sensoriamento remoto.

---

## ⚙️ Funcionalidades
- 🔋 **Projeto de Baixo Consumo**
  - Modos de sleep para sensores e MCU
  - Gerenciamento de energia otimizado para operação com bateria

- 📡 **Comunicação LoRa**
  - Transmissão de dados sem fio de longo alcance e baixo consumo

- 🌡️ **Integração Multissensor**
  - Sensor de temperatura e umidade
  - Sensor de gás
  - Sensor de peso (interface com célula de carga)

- 🔌 **Alimentação Flexível**
  - Entrada USB
  - Operação via bateria

- 🔄 **Confiabilidade do Sistema**
  - Circuito de reset externo para estabilidade do MCU
  - Interface de programação/debug

---

## 🧠 Arquitetura de Hardware
- **Microcontrolador:** MSP430FR2155  
- **Comunicação:** Módulo LoRa  
- **Sensores:**
  - Temperatura & Umidade  
  - Sensor de Gás  
  - Sensor de Peso (Célula de Carga)  

- **Sistema de Alimentação:**
  - Entrada USB  
  - Entrada por bateria  
  - Circuito de comutação de energia  

- **Outros Circuitos:**
  - Controle de alimentação dos sensores (sleep/power gating)  
  - Circuito de reset  
  - Interface de programação  

---

## 🔋 Estratégia de Baixo Consumo
O sistema foi projetado com foco em **eficiência energética**, incluindo:
- Ativação seletiva dos sensores (controle de modo sleep)
- Uso dos modos de baixo consumo do MSP430 (LPM)
- Seleção eficiente da fonte de energia (USB/Bateria)
- Redução do consumo em estado ocioso

---

## 🖥️ Projeto da PCB
- PCB personalizada desenvolvida para integração compacta  
- Separação das seções analógica e digital  
- Técnicas de redução de ruído para maior precisão dos sensores  
- Projetado utilizando (adicione seu software aqui: KiCad / Altium / etc.)  

---

## 📊 Aplicações
- Monitoramento ambiental  
- Agricultura inteligente  
- Sensoriamento industrial  
- Nós IoT remotos  

---

## 🚀 Melhorias Futuras
- Integração com plataformas em nuvem  
- Dashboard web/mobile  
- Suporte a energy harvesting  
- Otimização de firmware para ultra baixo consumo  

---

## 🛠️ Tecnologias & Habilidades
- Sistemas Embarcados  
- Projeto de PCB  
- Eletrônica de Baixo Consumo  
- Integração de Sensores  
- Sistemas IoT  
- Comunicação LoRa  

---

## 📷 Preview

<img width="672" height="543" alt="multsensor" src="https://github.com/user-attachments/assets/65b4fd39-2988-4c5b-8c96-a22daec3cb20" />

---

## 👩‍💻 Autor
Desenvolvido por Mickaelly Freitas Nobre

---

# MSP430 LoRa Multisensor Node (Low Power IoT PCB)

## 📌 Overview
This project presents the design and development of a **low-power multisensor IoT node** based on the **MSP430FR2155 microcontroller**, integrating multiple environmental and monitoring sensors into a custom PCB.

The system is designed for **energy efficiency**, **wireless communication**, and **modular sensing**, making it suitable for applications such as environmental monitoring, smart agriculture, and remote sensing.

---

## ⚙️ Features
- 🔋 **Low Power Design**
  - Sleep modes for sensors and MCU
  - Power management optimized for battery operation

- 📡 **LoRa Communication**
  - Long-range, low-power wireless data transmission

- 🌡️ **Multisensor Integration**
  - Temperature and humidity sensor
  - Gas sensor
  - Weight sensor (load cell interface)

- 🔌 **Flexible Power Supply**
  - USB power input
  - Battery-powered operation

- 🔄 **System Reliability**
  - External reset circuit for MCU stability
  - Programming/debug interface

---

## 🧠 Hardware Architecture
- **Microcontroller:** MSP430FR2155  
- **Communication:** LoRa module  
- **Sensors:**
  - Temperature & Humidity  
  - Gas Sensor  
  - Weight Sensor (Load Cell)  

- **Power System:**
  - USB input  
  - Battery input  
  - Power switching circuit  

- **Other Circuits:**
  - Sensor power gating (sleep control)  
  - Reset circuit  
  - Programming interface  

---

## 🔋 Low Power Strategy
The system was designed with a focus on **energy efficiency**, including:
- Selective sensor activation (sleep mode control)
- MSP430 low-power modes (LPM)
- Efficient power path selection (USB/Battery)
- Reduced idle consumption

---

## 🖥️ PCB Design
- Custom PCB developed for compact integration  
- Separation of analog and digital sections  
- Noise reduction techniques for sensor accuracy  
- Designed using (add your software here: KiCad / Altium / etc.)

---

## 📊 Applications
- Environmental monitoring  
- Smart agriculture  
- Industrial sensing  
- Remote IoT nodes  

---

## 🚀 Future Improvements
- Integration with cloud platforms  
- Mobile/web dashboard  
- Energy harvesting support  
- Firmware optimization for ultra-low power  

---


---

## 🛠️ Technologies & Skills
- Embedded Systems  
- PCB Design  
- Low Power Electronics  
- Sensor Integration  
- IoT Systems  
- LoRa Communication  


---

## 📷 Preview

<img width="672" height="543" alt="multsensor" src="https://github.com/user-attachments/assets/65b4fd39-2988-4c5b-8c96-a22daec3cb20" />

---

## 👩‍💻 Author
Developed by Mickaelly Freitas Nobre

---
