int redPin =12;
void setup() {
  // put your setup code here, to run once:
pinMode(redPin, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(redPin,HIGH);
delay(5000);

digitalWrite(redPin,LOW);
delay(5000);
}
