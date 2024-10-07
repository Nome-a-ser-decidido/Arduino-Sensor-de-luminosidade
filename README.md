# CP1_VINHARIA_EDCS

Para nosso primeiro CP1 da matéria de Edge Computing & Computer Systems, foi passado um desafio para solucionarmos para a Vinheria Agnello, que consiste em criar um sistema que possua um sensor de luminosidade, LEDS e um Buzzer/Piezo. O objetivo do desafio, é monitorar a luminosidade do ambiente e alertar os níveis de luz através de indicadores de luz e som.

<h2> Projeto no tinkercad </h2>

O projeto pode ser acessado pelo link: [https://www.tinkercad.com/things/giGfnG08Ewd-teste-de-luminosidade-com-display](https://www.tinkercad.com/things/kQKpJFqjxT6-teste-de-luminosidade)
É utilizado os seguintes componentes nesse projeto:
<li> Arduino UNO R3</li>
<li> 3 LEDs</li>
<li> 1 Piezo</li>
<li> 5 resistores </li>
<li> 1 fotorresitor</li>


<h2> Sistema </h2>
O código lê o valor de luminosidade que está sendo exercida no Fotorresistor, fazendo com que, dependendo da quantidade de luz sendo emitida, irá acionar um LED, onde quando acionado o LED vermelho, quer dizer que tem muita luminosidade na adega, o LED amarelo, passa uma sensação de cuidado, e o LED verde quer dizer que está tudo funcionando perfeitamente bem.

É necessário configurar a função map(), pois pode haver uma variação de luminosidade dependendo de qual fotorresistor está sendo utilizado

<h2> Visualização </h2>

![image](https://github.com/user-attachments/assets/e88ed5bf-5707-465d-bd6b-6726655eac4f)

<h2> Video </h2>

[![Video](https://img.youtube.com/vi/gikVGDdt4sY/0.jpg)](https://youtu.be/gikVGDdt4sY)
