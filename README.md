# ArduinoPractica1

 componentes:
Un led (luz de color rojo)
Una protoboard (investiga cómo funcionan las placas protoboads)
Una placa Arduino (por ejemplo la R3)

// Pin 13 has an LED connected on most Arduino boards.
// give it a name:
int led = 13;

// the setup routine runs once when you press reset:
void setup() {
  // initialize the digital pin as an output.
  pinMode(led, OUTPUT);
}

// the loop routine runs over and over again forever:
void loop() {
  digitalWrite(led, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);               // wait for a second
  digitalWrite(led, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);               // wait for a second
}

4- Inicia la simulación y comprueba que la luz se enciende y apaga cada 1 segundo.
