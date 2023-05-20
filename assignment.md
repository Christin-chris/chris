
## day - 10

>automatic street light

![_photo](https://github.com/Christin-chris/chris/blob/main/Screenshot%20from%202023-05-20%2010-38-50.png)

>programm code
```
// C++ code
//
int brightess = 0;

void setup()
{
  pinMode(A0, INPUT);
  Serial.begin(9600);
  pinMode(8, OUTPUT);
}

void loop()
{
  brightess = analogRead(A0);
  Serial.println(brightess);
  if (brightess <= 300) {
    digitalWrite(8, HIGH);
  } else {
    digitalWrite(8, LOW);
  }
  delay(10); // Delay a little bit to improve simulation performance
}
