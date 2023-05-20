# Day-1
# 10 days internship
## 10 days internship
10 days internship
> 10 days internship in jyothi eng college

1. createbig size heading-add the symbol # before subject
2. for bold the letters [** subject **]
3. for continues numbering for the lines add the number with dot(1.) enter
4. write a program/code for copy -write the program in side backdot (```program```)

 ```
 #include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}
```



## day 2

>Creating circuit using Thinkercad

1.creating a circuit using tinkercad simulator tool

2.[Thinkercad Tool](https://www.tinkercad.com/)

3.created a simple led circuit using various components

# circuit without switch


![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-09%2012-06-44.png)


# circuit with switch 
![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-11%2014-09-26.png)

# Day-3

> AND GATE using Tinkercad 

1.**collect the components that switch,led,resistor,powersupply,bread board**
![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-11%2010-23-57.png)

2.**introduced new website to know easily about arduino circuits** 
[circuito.io](https://www.circuito.io/)

3.**make a led light citcuit using arduino**
![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-11%2011-18-32.png)
**program**
```
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}
https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot 2023-05-11 at 11-33-09 Circuit design Tremendous Jarv Tinkercad.png
void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
4.**make arduino with two led circuit**
![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-11%2012-54-01.png)
## program ##
```
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
  pinMode(12, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(200); // Wait for 1000 millisecond(s) 
  digitalWrite(12, HIGH);
  delay(50); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(50); // Wait for 1000 millisecond(s)
}  
```
5.**4 led ciruit with aurdino**
![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-12%2009-57-53.png)
## program ##
```
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(200); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(400); // Wait for 1000 millisecond(s)
  digitalWrite(11, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(11, LOW);
  delay(200); // Wait for 1000 millisecond(s)
  digitalWrite(10, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  delay(300); // Wait for 1000 millisecond(s)
 
  
}
```
6.7 segment display with arduino thinkercad

# Day-4
> introduction to AI & ML
1. Introduced a programming platform named as [Blockly](https://developers.google.com/blockly)
![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-15%2014-31-46.png)
2. The platform like Blockly are mostly used by  fresher's in programming
3. It's like a game 
4. The blockly helps to know about the programming easly
5. To create a multifunction program like a calculator
![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%20from%202023-05-12%2012-51-46.png)

> STM 32 NUCLEO DEVELOPMENT BOARD

![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/index.jpeg)
1. the board is programmeble
2. Can program th board by nucleo software
3. it can build a sound detecting device by using microphone sensor 

# Day-5
> Introducing drones by NAVANEETH 3rd year student of robotics
1. Introducing Drones
2. explained about drones parts
3. also speaked about the technical specifications like (Thrust,altitude,propeler diamention,weight management) 
4. To config the drones with software named as mission planner![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Screenshot%202023-05-16%20at%2009-28-33%20mission%20planner%20-%20Google%20Search.png)
> Analog reader potentiometer

![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/Capture.PNG)
```
const int potpin=A0;

void setup() {
   Serial.begin(9600);
}
void loop() {
  int potValue =analogRead(potpin);
  Serial.println(potValue);
  delay(100);
}
```
# Day-6
 > Basics of 3D printing conducted by 3rd year student robotics
1. first introduced of the 3d printing
2. creating  models by the tinkercad 3D modeling
3. start with basic shapes
4. also cover the previous design's
5. created a base and top cover for the flower bottel by using [Tinkercad](https://www.tinkercad.com/)
6. then introduced the 3D printer 
7. also printed a design (duration 19 min)

# Day-7
> Introduced the yaskawa arm robot
1. The introduction of yaskawa AR1440 ![no image](https://github.com/jyothis-vb/10daysinternship/blob/main/IMAGE/gp25yaskawa.jpg)
> Then introduced about the EV (electric vehicle)
# Day-8
> Arduino 
1. Programming the arduino for the 7 segment display with pot 
2. adjusting the speed of the display by varing the pot [thinker the circuit](https://www.tinkercad.com/things/7hNg1XcCvKV-copy-of-fantastic-gaaris-jaiks/editel)  ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-18%2010-51-29.png)

**program**
```
// C++ code
//
const int potpin=A0;


void setup()
  
{
  Serial.begin(9600);
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  int potValue =analogRead(potpin);
  Serial.println(potValue);
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(potValue); // Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(potValue);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(potValue);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(potValue);
  
  delay(potValue); // Wait for 1000 millisecond(s)
}
```
# Day-9
> Arduino interface LCD

introduced the arduino interface with various components

# Day-10
> mini project 
**my  project was a Design a Quiz buzzer**
[link](https://www.tinkercad.com/things/6Xa7QyjaUWb-ingenious-rottis-kup/editel)

[assingment](https://www.tinkercad.com/things/67ikmpxghy3-copy-of-superman-keychain/edit)
```
#define button1 2 //the number of the button 1
#define button2 3 //button2 attach to
#define button3 4 //button3 attach to 
#define button4 9 //button4 attach to
#define buzzerPin 5 //the buzzer attach to 
#define LED1 6 //LED1  attach to 
#define LED2 7 //LED2  attach to 
#define LED3 8 //LED3  attach to 
#define LED4 10 //LED4 attach to
#define uint8 unsigned char
uint8 flag = 0; //used to indicate the state of button4 key
uint8 b1State,b2State,b3State,b4State= 0;

void setup()
{
  //initialize buzzer,LED1, LED2, LED3 and LED4 as output
   pinMode(buzzerPin, OUTPUT); 
   pinMode(LED1, OUTPUT);
   pinMode(LED2, OUTPUT); 
   pinMode(LED3, OUTPUT); 
   pinMode(LED4, OUTPUT);
  //initialize button1,button2 andbutton3  as input,combined with pullup
  pinMode(button1, INPUT_PULLUP);
  pinMode(button2, INPUT_PULLUP);
  pinMode(button3, INPUT_PULLUP); 
  pinMode(button4, INPUT_PULLUP);
  
  //turn all the led off
 
  digitalWrite(LED1, LOW); 
  digitalWrite(LED2, LOW); 
  digitalWrite(LED3, LOW);
  digitalWrite(LED4, LOW);
}
void loop()
{
  //read the state of the button4
  b4State = digitalRead(button4);
  //when button4 pressed
  if(b4State == 0)
  {
    if(b4State == 0) //confirm that the button4 is pressed
   {
      flag = 1; //if so,flag is 1
      digitalWrite(LED4, HIGH); //turn the host LED on
      delay(200); 
    } 
    //turn all the led off
    digitalWrite(LED1, LOW);
    digitalWrite(LED2, LOW); 
    digitalWrite(LED3, LOW); 
    digitalWrite(LED4, LOW); 
    }
  if(1 == flag)
  {
    //read the state of the button of buttons
    b1State = digitalRead(button1); 
    b2State = digitalRead(button2);
    b3State = digitalRead(button3);
    //If the button1 press the first
  if(b1State == 0)
  {
      flag = 0;
      digitalWrite(LED4, LOW);
      Alarm(); //buzzer sound
      digitalWrite(LED1,HIGH); //turn the LED1 on only
      digitalWrite(LED2,LOW); 
      digitalWrite(LED3,LOW); 
     while(digitalRead(button4));
  }
   //If the button2 press the first
    if(b2State == 0)
    {
      flag = 0;
      digitalWrite(LED4, LOW);
      Alarm(); //buzzer sound
      digitalWrite(LED1,HIGH); //turn the LED1 on only
      digitalWrite(LED2,LOW); 
      digitalWrite(LED3,LOW);
      while(digitalRead(button4)); //detect the button4,if pressed,out of the while loop
    }
    
    //If the button3 press the first
    if(b3State == 0)
    {
      flag = 0;
      digitalWrite(LED4, LOW);
      Alarm();
      digitalWrite(LED1,LOW);
      digitalWrite(LED2,LOW);
      digitalWrite(LED3,HIGH);
      while(digitalRead(button4));
    }
     
  }
}
//buzzer sound
void Alarm() 
{
  for(int i=0;i<100;i++)

  {
    digitalWrite(buzzerPin,HIGH); //the buzzer sound
    delay(2);
    digitalWrite(buzzerPin,LOW); //without sound
    delay(2); //when delay time changed,the frequency changed
  }
}
```



