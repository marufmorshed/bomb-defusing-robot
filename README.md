#include<Servo.h>

Servo servo2;

const int angle=0;
void setup() {
  servo2.attach(7);//servo2
  servo2.write(angle);
  
  // put your setup code here, to run once:

}

void loop() {
  servo2.write(9 0);
  delay(1000);
  servo2.write(0);
  delay(1000);
  // put your main code here, to run repeatedly:

}
