# Informações:

- Linguagem: C ou C++; python através do micropython ou circuitpython
- Led: Tem, dois. Vermelho geralmente para mostrar que está ligado; o azul (GPIO 2), esse é para programar o pino 2 digital.
- Placa: ESP-WROOM-02 
- Modelo: ESP32 nodeMCU

## Link: https://support.arduino.cc/hc/en-us/articles/360019833020-Download-and-install-Arduino-IDE

- Código:

int led = 2;


void setup() {


pinMode(led, OUTPUT);


}


void loop() {


  digitalWrite(led, HIGH);

  
  delay (1000);

  
  digitalWrite(led, LOW);

  
  delay(1000);

  
}


## 28/08
Estava sem drive, o código estava certo. Depois disso a luz piscava.
