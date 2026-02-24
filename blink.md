# Aufgabe: LED Blinken
Schließe eine LED an GPIO 2 an und lass sie im Sekundentakt blinken.

<details>
<summary>👉 Hier klicken für die Lösung</summary>

```cpp
void loop() {
  digitalWrite(2, HIGH);
  delay(1000);
  digitalWrite(2, LOW);
  delay(1000);
}
