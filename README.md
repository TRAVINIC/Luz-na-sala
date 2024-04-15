# Luz-na-sala
Código e instrução para a criação de um sistema simples de lâmpada que ascende captando o sinal de sensores de distancia utilizando arduino, sensor de distancia ultra sonico,
modulo relé e uma lampada.
esse sistema custa por volta de R$110,00

Luz_na_sala é um projeto de automatização de uma lampada para 
ascender quando alguem se aproximar a um sensor de distancia


O item Luz_na_sala_read.me explica como a Luz_na_sala ascende atráves 
da distancia lida pelos metodos indicados no codigo do item 
Luz_por_distancia.

A distancia é medida pelo sensor de distancia que usa
método Trig para enviar os sinais até a pessoa,
logo após receber de volta os sinais o sensor utiliza 
o método Echo para ler a distancia advinda da pessoa
assim concluindo a distancia medida que se menor que 45cm
faz a lampada ligar 

/*Ligar lampada */
Se a distancia for menor que 45cm,
deve ligar a o modulo rele, que faz a luz da lampada ligar junto.

/*Desligar lampada */
Já se a distancia da pessoa for maior que  45cm,
deve desligar o modulo rele, que faz a luz da lampada desligar junto.

Entao para automatizar uma lampada, só precisa de um sensor 
de distancia ligado ao arduino nas portas corretas 
assim realizando leitura da distancia 

Após a leitura da distancia estar pronta será necessário 
um modulo rele para regular a tensão entre a energia 
da lampada para o arduino.

apos isso basta implementar 
o codigo Luz_por_distancia no arduino via usb 
e terá uma lampada de proximidade
