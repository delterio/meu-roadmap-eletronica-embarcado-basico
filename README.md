# **Roadmap de Estudos em Sistemas Embarcados: Do zero(lammer) ao avançado?**
**Acho que não, so sei que nada sei ;)**

Este roadmap foi elaborado para guiá-lo em sua jornada no mundo dos sistemas embarcados, começando do básico até tópicos avançados. Seguindo este plano, você desenvolverá uma base sólida e progredirá de forma estruturada.


---

## **Etapa 1: Fundamentos de Eletrônica e Programação**

### **1.1. Conceitos Básicos de Eletrônica**

**Objetivos de Aprendizado**:

- Compreender **tensão**, **corrente** e **resistência**.
- Aplicar a **Lei de Ohm** e as **Leis de Kirchhoff**.
- Identificar componentes eletrônicos: **resistores**, **capacitores**, **diodos**, **transistores**.
- Utilizar instrumentos de medição: **multímetros**, **osciloscópios**.

**Recursos**:

- **Curso Online**: [Eletrônica Básica](https://youtu.be/nsFBDCR1vLc?si=mlahTJpeFdd4FL9B)
- **Vídeos Educativos**: Canais no YouTube como [Brincando com Ideias](https://www.youtube.com/user/Brincandocomideias) e [Engenharia no Papel](https://www.youtube.com/user/EngenhariaNoPapel).

### **1.2. Introdução à Programação em C/C++**

**Objetivos de Aprendizado**:

- Familiarizar-se com a **sintaxe básica** de C/C++.
- Entender **variáveis**, **tipos de dados**, **operadores**, **estruturas de controle**.
- Escrever programas simples para consolidar o aprendizado.

**Recursos**:

- **Tutorial**: [Programação em c++](https://youtube.com/playlist?list=PLx4x_zx8csUjczg1qPHavU1vw1IkBcm40&si=D8tOBM8PZ60iyEAC)
- **Livro**: [Linguagem C ](https://www.inf.ufpr.br/lesoliveira/download/c-completo-total.pdf)

---

## **Etapa 2: Iniciando com o Arduino**

### **2.1. Configuração do Ambiente de Desenvolvimento**

**Objetivos de Aprendizado**:

- Instalar o **Arduino IDE**.
- Conhecer a interface e as funcionalidades do IDE.
- Entender a **estrutura básica** de um sketch (programa Arduino).

**Recursos**:

- **Site Oficial**: [Arduino - Software](https://www.arduino.cc/en/software)
- **Guia para Iniciantes**: [Iniciando com Arduino - FilipeFlop](https://www.filipeflop.com/blog/tutorial-arduino-iniciando-com-arduino/)

### **2.2. Projetos Práticos Iniciais**

**Atividades**:

- **Blink**: Fazer um LED piscar.
- **Entrada Digital**: Ler o estado de um botão.
- **Entrada Analógica**: Ler valores de um potenciômetro.
- **PWM**: Controlar o brilho de um LED.

---

## **Etapa 3: Aprimorando Habilidades em Eletrônica e Programação**

### **3.1. Conceitos Intermediários de Eletrônica**

**Objetivos de Aprendizado**:

- Compreender circuitos **RC** e **RL**.
- Utilizar **transistores** como chave.
- Entender **filtros** e **fontes de alimentação**.

### **3.2. Programação em C/C++ Avançada**

**Objetivos de Aprendizado**:

- Trabalhar com **funções** e **bibliotecas**.
- Entender **arrays**, **strings** e **manipulação de memória**.
- Introdução a **ponteiros** e **estruturas**.

---

## **Etapa 4: Explorando Sensores e Atuadores com Arduino**

### **4.1. Integração de Sensores**

**Atividades**:

- **Sensor de Temperatura**: Ler dados de um sensor **LM35** ou **DHT11**.
- **Sensor Ultrassônico**: Medir distância com o **HC-SR04**.
- **Display LCD**: Exibir informações em um display **16x2**.

### **4.2. Controle de Atuadores**

**Atividades**:

- **Servomotores**: Controlar a posição de um servo.
- **Motores DC**: Controlar velocidade e direção com **ponte H**.
- **Relés**: Acionar dispositivos de maior potência.

---

## **Etapa 5: Introdução ao ESP32 e Conectividade**

### **5.1. Configurando o ESP32**

**Objetivos de Aprendizado**:

- Instalar **bibliotecas** e **drivers** para ESP32 no Arduino IDE.
- Conhecer as características e recursos do **ESP32**.

**Recursos**:

- **Documentação**: [Espressif ESP32 Guides](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/)
- **Tutoriais**: [Random Nerd Tutorials - ESP32](https://randomnerdtutorials.com/projects-esp32/)

### **5.2. Projetos com Wi-Fi**

**Atividades**:

- **Web Server**: Criar um servidor web simples para controlar LEDs.
- **HTTP Requests**: Enviar e receber dados via HTTP.
- **Atualização Over-The-Air (OTA)**: Atualizar firmware sem cabo USB.

### **5.3. Projetos com Bluetooth**

**Atividades**:

- **Bluetooth Classic**: Comunicação serial via Bluetooth.
- **BLE (Bluetooth Low Energy)**: Enviar dados de sensores.

---

## **Etapa 6: Sistemas Operacionais de Tempo Real (RTOS)**

### **6.1. Introdução ao FreeRTOS no ESP32**

**Objetivos de Aprendizado**:

- Compreender o conceito de **multitarefa**.
- Criar **tarefas**, **filas** e **semáforos** no FreeRTOS.

**Recursos**:

- **Tutorial**: [Introdução ao FreeRTOS - LAB de Garagem](https://labdegaragem.com/profiles/blogs/introducao-ao-freertos-no-esp32)

### **6.2. Projetos com FreeRTOS**

**Atividades**:

- Implementar multitarefas para leitura de sensores e comunicação.
- Gerenciar recursos compartilhados entre tarefas.

---

## **Etapa 7: Microcontroladores de Baixo Custo - ATtiny85**

### **7.1. Programação do ATtiny85**

**Objetivos de Aprendizado**:

- Configurar o Arduino como programador **ISP**.
- Entender as limitações e recursos do **ATtiny85**.

**Recursos**:

- **Tutorial**: [Programando ATtiny85 com Arduino - Laboratório de Garagem](https://labdegaragem.com/profiles/blogs/attiny85-com-arduino)
- **Datasheet**: [Microchip - ATtiny85 Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/ATtiny85-Data-Sheet-40002085A.pdf)

### **7.2. Projetos com ATtiny85**

**Atividades**:

- Criar um **pisca-LED** compacto.
- Desenvolver um controlador simples para sensores.

---

## **Etapa 8: Protocolos de Comunicação**

### **8.1. Comunicação Serial (UART)**

**Objetivos de Aprendizado**:

- Estabelecer comunicação entre microcontroladores.
- Depurar programas usando comunicação serial.

### **8.2. Protocolos I2C e SPI**

**Atividades**:

- Conectar e usar módulos como displays **OLED** (I2C).
- Interfacear com cartões **SD** ou módulos **RF** (SPI).

**Recursos**:

- **Tutorial**: [I2C e SPI - Embarcados](https://www.embarcados.com.br/comunicacao-spi-e-i2c/)

### **8.3. Comunicação Sem Fio Avançada**

**Objetivos de Aprendizado**:

- Utilizar módulos **LoRa** para comunicação de longa distância.
- Implementar redes **Mesh** com ESP32.

---

## **Etapa 9: Desenvolvimento de Projetos Integrados**

### **9.1. Projeto Prático: Estação Meteorológica IoT**

**Atividades**:

- Coletar dados ambientais com sensores.
- Enviar dados para a nuvem usando **MQTT**.
- Visualizar dados em **dashboards online**.

### **9.2. Projeto Prático: Automação Residencial**

**Atividades**:

- Controlar iluminação e dispositivos via **smartphone**.
- Implementar reconhecimento de **voz** ou **gestos**.

---

## **Etapa 10: Design e Fabricação de PCB**

### **10.1. Introdução ao Design de PCB**

**Objetivos de Aprendizado**:

- Conhecer softwares como **KiCad** ou **Eagle**.
- Criar **esquemáticos** e **layout de placas**.

**Recursos**:

- **Tutorial**: [Introdução ao KiCad - Embarcados](https://www.embarcados.com.br/kicad/)
- **Curso**: [Curso de KiCad - WR Kits](https://www.wrkits.com.br/curso/kicad)

### **10.2. Fabricação e Montagem**

**Atividades**:

- Enviar o projeto para fabricação em serviços como **PCBWay**.
- Montar e testar a placa desenvolvida.

---

## **Etapa 11: Otimização e Boas Práticas**

### **11.1. Gestão de Energia**

**Objetivos de Aprendizado**:

- Implementar modos de baixo consumo (**sleep modes**).
- Otimizar código para **eficiência energética**.

### **11.2. Segurança em Sistemas Embarcados**

**Objetivos de Aprendizado**:

- Entender vulnerabilidades comuns.
- Aplicar **criptografia básica** e **autenticação**.

---

## **Etapa 12: Especialização e Atualização Contínua**

### **12.1. Exploração de Novas Plataformas**

**Atividades**:

- Experimentar com microcontroladores **ARM (STM32)**.
- Utilizar **Raspberry Pi** para projetos mais complexos.

### **12.2. Temas Avançados**

**Objetivos de Aprendizado**:

- **Machine Learning** em dispositivos embarcados.
- Protocolos avançados de comunicação (**CAN**, **Ethernet**).

---

## **Recursos Complementares**

- **Comunidades e Fóruns**:
  - [Fórum Arduino](https://forum.arduino.cc/)
  - [Stack Overflow em Português](https://pt.stackoverflow.com/)
  - [Reddit - r/arduino](https://www.reddit.com/r/arduino/)
  - [Reddit - r/esp32](https://www.reddit.com/r/esp32/)

- **Cursos Online**:
  - **Udemy**:
    - [Arduino Para Iniciantes: Crie Projetos com o Arduino](https://www.udemy.com/course/arduino-para-iniciantes/)
    - [Programação Embarcada com ESP32](https://www.udemy.com/course/programacao-embarcada-com-esp32/)
  - **Coursera**:
    - [Interfacing with the Arduino](https://www.coursera.org/learn/interface-with-arduino)
  - **edX**:
    - [Embedded Systems Essentials with Arm](https://www.edx.org/course/embedded-systems-essentials-with-arm)

- **Livros Recomendados**:
  - *Arduino: Guia para colocar suas ideias em prática* Fernando Bryan Frizzarin
  - *Programação Sistemas Embarcados* Rodrigo Almeida

---

## **Dicas para o Sucesso**

- **Prática Constante**: Aplique os conceitos em projetos reais.
- **Documentação**: Leia **datasheets** e manuais para aprofundar o conhecimento.
- **Networking**: Participe de eventos, workshops e comunidades online.
- **Aprendizado Contínuo**: A área de sistemas embarcados está em constante evolução. Mantenha-se atualizado.

---

Seguindo este roadmap, você construirá uma base sólida e estará preparado para enfrentar desafios cada vez mais complexos na área de sistemas embarcados. Lembre-se de que a jornada é tão importante quanto o destino. Aproveite cada etapa do aprendizado e **bons estudos**!