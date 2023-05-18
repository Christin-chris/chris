### 10 day internship

### day 1

1 open github 

2 create github

3 create new file

4 change repository

>use simpols for respository file

1 [swabiribrahim](https://github.com/swabiribrahim)

### DAY 2

>kunamakkulam poliy students list
>
[kunamkkulampoly](https://github.com/tata-iiic/KunnamkulamPolyInternMay23/blob/main/index.md)

>tinkercad

1 open tinkecard software

2 open new simulation folder

3 create an a led simulation circuit with switch and without switch

>project-1

![ photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-09%2012-24-05.png)

>project-2

![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-09%2012-14-59.png)

 ### DAY 3
 
 >PROJECT-3
  
![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-11%2010-29-31.png)

>project-4
 
 # LED BLINKING CIRCUIT #
 
 >PROGRM
 
 // C++ code

  This program blinks pin 13 of the Arduino (the built-in LED)
  

```

void setup()

{

  pinMode(LED_BUILTIN, OUTPUT);
  
}

void loop()

{

  // turn the LED on (HIGH is the voltage level)
  
  digitalWrite(LED_BUILTIN, HIGH);
  
  delay(1000); // Wait for 1000 millisecond(s)
  
  // turn the LED off by making the voltage LOW
  
  digitalWrite(LED_BUILTIN, LOW);
  
  delay(1000); // Wait for 1000 millisecond(s)
  
}


```

![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-11%2011-10-59.png)

>PROGRAM-5

## DANCING LED

![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-11%2012-53-48.png)

>dancing led progaram

// C++ code

```
void setup()

{

  pinMode(13, OUTPUT);
  
  pinMode(8,OUTPUT);
  
}

void loop()

{

  digitalWrite(13, HIGH);
  
  delay(1000);//wait for 1000millisecond(s)
  
  digitalWrite(13, LOW);
  
   // Wait for 1000 millisecond(s)
   
  digitalWrite(8, HIGH);
  
  delay(1000);
  
  digitalWrite(8, LOW);
  
  delay(1000);
  
}

```
##LED CHASER

>PROGRAM-6

// C++ code

```
void setup()

{

  pinMode(13, OUTPUT);
  
  pinMode(8, OUTPUT);
  
  pinMode(7, OUTPUT);
  
  pinMode(2, OUTPUT);
  
 }

void loop()

{

  digitalWrite(13, HIGH);
  
  delay(250); // Wait for 1000 millisecond(s)
  
  digitalWrite(13, LOW);
  
  delay(250);// Wait for 1000 millisecond(s)
  
  digitalWrite(8, HIGH);
  
  delay(500); // Wait for 1000 millisecond(s)
  
  digitalWrite(8, LOW);
  
  delay(500);// Wait for 1000 millisecond(s)
  
  digitalWrite(7,HIGH);
  
  delay(500); // Wait for 1000 millisecond(s)
  
  digitalWrite(7, LOW);// Wait for 1000 millisecond(s)
  
  delay(500);
  
  digitalWrite(2, HIGH);
  
  delay(500); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, LOW);
  
  delay(250); // Wait for 1000 millisecond(s)
  
}

```
![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-11%2016-05-07.png)

## DAY-4

 ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2010-34-11.png)
 1. Introduced a programming platform named as (Blockly) 
 
2. The platform like Blockly are mostly used by  fresher's in programming

3. It's like a game 

4. The blockly helps to know about the programming easly

5. To create a multifunction program like a calculator

6. ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2012-21-17.png)

**AI & ML** 

>>MACHINE LEARNING
>> 
> STM 32 NUCLEO DEVELOPMENT BOARD
 
![IMAGE](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Untitled.jpeg)

1. the board is programmeble

2. Can program th board by nucleo software

3. it can build a sound detecting device by using microphone sensor 

 
## DAY-5

>DRONE 

drone class and explanation

##7 sigment counding 

>programm-7
```

(unsigned const int A = 11;
unsigned const int B = 10;
unsigned const int C = 7;
unsigned const int D = 8;
unsigned const int E = 9;
unsigned const int F = 12;
unsigned const int G = 13;
unsigned const int DP = 6;


void setup(void)
{
  pinMode(A, OUTPUT);
  pinMode(B, OUTPUT);
  pinMode(C, OUTPUT);
  pinMode(D, OUTPUT);
  pinMode(E, OUTPUT);
  pinMode(F, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(DP, OUTPUT);
}



void zero(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, LOW);
  digitalWrite(DP, LOW);
}

void one(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, LOW);
  digitalWrite(DP, LOW);
}

void two(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, LOW);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(DP, LOW);
}

void three(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(DP, LOW);
}

void four(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(DP, LOW);
}

void five(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(DP, LOW);
}

void six(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(DP, LOW);
}

void seven(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, LOW);
  digitalWrite(DP, LOW);
}

void eight(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(DP, LOW);
}

void nine(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, LOW);https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-15%2014-27-59.png
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(DP, LOW);
}

// Start
void loop(void)
{
  zero();
  delay(1000);
  
  one();
  delay(1000);
  
  two();
  delay(1000);
  
  three();
  delay(1000);
  
  four();
  delay(1000);
  
  five();
  delay(1000);
  
  six();
  delay(1000);```
  
  seven();
  delay(1000);
  
  eight();
  delay(1000);
  
  nine();
  delay(1000);
}
```
![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-15%2009-49-50.png)

##INTERFACING POTETIOMETR USING ARDINO

>PROGRAMM -8

![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-15%2014-27-59.png)

>PROGRAMM CODE

```
void setup() {
  
  Serial.begin(9600);
}


void loop() {
  
  int sensorValue = analogRead(A0);
  
  float voltage = sensorValue * (5.0 / 1023.0);
  
  Serial.println(voltage);
}
```
## DAY -7

>SERVO MOTER

![image](https://github.com/Christin-chris/chris/assets/132876614/d99e64c6-cf70-4231-b897-438c1f06e25a)

> PROGRAMM CODE
```
#include <Servo.h>

int pos = 0;

Servo servo_9;

void setup()
{
  servo_9.attach(9, 500, 2500);
}

void loop()
{
  // sweep the servo from 0 to 180 degrees in steps
  // of 1 degrees
  for (pos = 0; pos <= 180; pos += 1) {
    // tell servo to go to position in variable 'pos'
    servo_9.write(pos);
    // wait 15 ms for servo to reach the position
    delay(15); // Wait for 15 millisecond(s)
  }
  for (pos = 180; pos >= 0; pos -= 1) {
    // tell servo to go to position in variable 'pos'
    servo_9.write(pos);
    // wait 15 ms for servo to reach the position
    delay(15); // Wait for 15 millisecond(s)
  }
}
```

## rgb work

> programm code 
```
// C++ code
//
void setup()
{
 Serial.begin(9600);
}

void loop()
{
  
  int r=random(0,255);  
  int g=random(0,255);
  int b=random(0,255);
  
  
  Serial.print(r);
   Serial.print("-");
   Serial.print(g); 
  Serial.print("-");
  Serial.println(b);
  
  
  analogWrite(9, r);
  analogWrite(10, g);
  analogWrite(11,b);
  
  delay(3000);
    
  
}
```
](https://github.com/Christin-chris/chris/assets/132876614/d9ea52b8-94ed-4e19-b813-2c806b4bb744)
