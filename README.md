# 💡 Sistema de Controle de Iluminação com ESP32 e Display OLED

## Descrição

Este projeto foi desenvolvido utilizando MicroPython e a plataforma ESP32 para controlar um sistema simples de iluminação através de botões físicos e exibição de mensagens em um display OLED.

O sistema permite ligar e desligar LEDs utilizando botões conectados às portas GPIO do microcontrolador. Além disso, o display OLED informa ao usuário o estado atual da iluminação em tempo real.

## Funcionalidades

* Controle de LEDs por botões;
* Exibição de mensagens em display OLED;
* Indicação visual de luz ligada e desligada;
* Atualização instantânea do display;
* Utilização de entradas digitais com Pull-Up interno;
* Sistema embarcado em tempo real.

## Componentes Utilizados

* ESP32
* Display OLED SSD1306 (128x64)
* 2 LEDs
* 2 Botões
* Jumpers
* Protoboard

## Tecnologias Utilizadas

* MicroPython
* Biblioteca SSD1306
* Comunicação I2C
* GPIO (Entradas e Saídas Digitais)

## Como Funciona

O sistema monitora continuamente dois botões:

### Botão Azul

Quando pressionado:

* Exibe a mensagem **"Luz acesa"** no display OLED;
* Liga o LED verde;
* Liga o LED vermelho.

### Botão Verde

Quando pressionado:

* Exibe a mensagem **"Luz apagada"** no display OLED;
* Desliga o LED verde;
* Desliga o LED vermelho.

## Conceitos Aplicados

* Programação embarcada;
* Controle de GPIO;
* Comunicação I2C;
* Manipulação de displays OLED;
* Estruturas condicionais;
* Sistemas em tempo real;
* Integração entre hardware e software.

## Aprendizados

Durante o desenvolvimento deste projeto foram trabalhados conhecimentos relacionados a:

* Microcontroladores ESP32;
* Programação com MicroPython;
* Controle de componentes eletrônicos;
* Comunicação com periféricos;
* Automação básica;
* Desenvolvimento de sistemas embarcados.

## Melhorias Futuras

* Controle individual dos LEDs;
* Exibição de animações no OLED;
* Integração com sensores;
* Controle remoto via Wi-Fi;
* Automação residencial;
* Monitoramento por aplicativo móvel.

## Autor

Projeto desenvolvido para fins acadêmicos e de aprendizagem em sistemas embarcados, eletrônica e programação com MicroPython.
