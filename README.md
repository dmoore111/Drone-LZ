//# Drone-LZ
//Lighting for drone landing zone
//The approach path requires 2 X 4 flashing leds in a row plus position leds


int led1 = A1; 

int led2 = A2; 

int led3 = A3;

int led4 = A4;

void setup() {

  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(led3, OUTPUT);
  pinMode(led4, OUTPUT);
}

void loop() {
  
  digitalWrite(led1, HIGH);
  
  delay(100);
  
  digitalWrite(led2, HIGH);
  
  delay(100);
  
  digitalWrite(led3, HIGH);
  
  delay(100);
  
  digitalWrite(led4, HIGH);

  delay(100);

  digitalWrite(led1, LOW);
  digitalWrite(led2, LOW);
  digitalWrite(led3, LOW);
  digitalWrite(led4, LOW);

  delay(2000);

}

