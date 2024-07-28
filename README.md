# Connecting-and-programming-an-electronic-circuit-containing-6-servo-motors-using-simulation-software

  ## #include <Servo.h>: 
  This line includes the Servo library, which allows you to control servo motors.

  
  
## Defining Variables
Here, six Servo objects are declared. Each one represents a servo motor.
#### Servo R;
#### Servo F;
#### Servo B;
#### Servo S;
#### Servo N;


## setup Function
void setup(): This function runs once when the Arduino starts up.
R.attach(3);: This connects the servo motor R to digital pin 3 on the Arduino. Similarly, other servos are connected to digital pins 4, 7, 8, 12, and 5 respectively.

void setup()
{
#### R.attach(3);
#### L.attach(4);
#### F.attach(7);
#### B.attach(8);
#### S.attach(12);
#### N.attach(5);


## loop Function

}

void loop()
{
 #### R.write(90);
 #### delay(1000);
 #### R.write(180);
 #### delay(1000);

#### L.write(90);
####  delay(1000);
####  L.write(180);
####  delay(1000);
  
 #### F.write(90);
####  delay(1000);
####  F.write(180);
 #### delay(1000);
  
  
 #### B.write(90);
####  delay(1000);
####  B.write(180);
####  delay(1000);
  
 ####  S.write(90);
 #### delay(1000);
####  S.write(180);
####  delay(1000);

#### N.write(90);
####  delay(1000);
 #### N.write(180);
####  delay(1000);  
  
}

 void loop(): This function runs repeatedly after the setup() function completes.
 R.write(90);: Sets the angle of servo motor R to 90 degrees.
 delay(1000);: Waits for 1000 milliseconds (1 second) before executing the next line of code.
 R.write(180);: Sets the angle of servo motor R to 180 degrees.
 The same process is repeated for all servos (R, L, F, B, S, N), where each servo is set to two different angles (90 and 180 degrees) with a 1-second delay between each angle change.

## Summary
The code controls six servo motors connected to digital pins on the Arduino.
In each loop iteration, each servo motor’s angle is alternated between 90 and 180 degrees with a 1-second delay between each change.
This causes the servos to move back and forth sequentially.
Feel free to ask if you need any more details or further explanations!


https://github.com/user-attachments/assets/10354a4e-15b4-4d14-b54a-bfef584bed46



