## -Sensor PIR

|       Montaje            |       Programa  |
| -------------            |      -------------         |
|      <img src="Fotos/sensor_pir.jpg" width="400" height="400" />                   |      <img src="Fotos/servo.pir.png" width="400" height="400" />                    |














## -Sensor de humedad

|       Montaje            |       Programa  |
| -------------            |      -------------         |
|      <img src="Fotos/sensor_humedad_montaje.jpg" width="400" height="400" />                   |      <img src="Fotos/programacion de humedad.png" width="400" height="400" />                    |


### Objetivo: 
El objetivo de este programa es que el sensor de humedad detecte la humedad de donde lo pongamos en nuestro caso detectar la humedad de la tierra.

### Programa:
Al empezar este programa creamos 2 variables una con __int__ llamada __sensor__ que es la que se va a referir al sensor de huemedad y otra variable __float__ que la usamos para mostrar numeros con decimales llamada __temperatura__.

En el __void setup__ unicamente indicamos la velocidad de transmision de datos a __9600__.

En el __void loop__ de primeras indicamos que nuestra variable llamada __sensor__ esta conectado al pin __A0__ de nuestra placa de arduinos y por ultimo indicamos con el __Serial.println__ que el valor que nos de en el sensor se pueda ver en el monitor serie.



## -Sensor de presion

|       Montaje            |       Programa  |
| -------------            |      -------------         |
|      <img src="Fotos/sensor_presion.jpg" width="400" height="400" />                   |      <img src="Fotos/sesnsor_presion (2).png" width="400" height="400" />                    |



### - ¿Como funciona?
 
Funciona conectando a una placa arduino y protoboard junto a una resistencia a GND, 5V y a un Pin (ejempl: 8) para que al presionar el circulo con la minima presión que tu programes lo detecte y envie la información a la placa de arduino o al monitor en la pantalla con la cifra que el sensor de presión detecte.

### - ¿Para que sirve?

Sirve para dectectar una presión cual a detectar una minima presión envie la información a la placa y asi la placa con esa información haga una cosa o otra. Pero su función es enviar la información a la placa.

### - ¿De que componentes esta hecho?

Esta compuesto de cableado, placa protoboard, placa arduino, resistencia, sensor de presión.

### - ¿Como funciona el programa?

Funciona con tres variables cuales son el valor de presión y el pin, la presión el void setup solo contiene un serial begin 9600 y el void loop valora la presión con analogRead y map ajusta la presión para que sea menos o más sensible a la presión que se le aporta y usa un SerialPrinting para que los datos que detecte la placa de presión lo mande a la pantalla de la consola de monitor de arduino con un delay de 500 milisegundos.







## -Sensor LDR

|       Montaje            |       Programa  |
| -------------            |      -------------         |
|      <img src="Fotos/ldr_real.jpg" width="400" height="400" />                   |      <img src="Fotos/ldr_code.png" width="400" height="400" />                    |





## -Sensor de agua






##  -Sensor de temperatura
