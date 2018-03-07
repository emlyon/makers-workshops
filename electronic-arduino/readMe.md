## Atelier electronique / arduino


#### exemple 1 : Make a led glow
[Test me on Tinkercad](https://www.tinkercad.com/things/03WDZBVcr39)
![alt text](./imgs/diode-explode.png "simple led")
Arduino Code :
```java
///Nothing here
```


#### exemple 2 : Make a led glow with a button
[Test me on Tinkercad](https://www.tinkercad.com/things/163mTSp0VBm)
![alt text](./imgs/simple-button.png "simple button")
Arduino Code :
```java
///Nothing here
```


#### exemple 3 : Make a led blink
[Test me on Tinkercad](https://www.tinkercad.com/things/163mTSp0VBm)
![alt text](./imgs/diode-blink.png "led blink")

Arduino Code :
```java
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
