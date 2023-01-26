# Esp32-Reinicio-Con-Codigo

### Codigo
```c++
void setup()
{
  //Inicia el puerto serial
  Serial.begin(115200);
}

void loop()
{
  //Mensaje para el puerto serial
  Serial.println("Se reiniciara en 5 segundos");

  //Espera 5 segundos
  delay(5000);

  //Realiza el reinicio del esp32
  ESP.restart();
}
```

### Debug
<img src="https://github.com/IDiegoUlises/Esp32-Reinicio-Con-Codigo/blob/main/Images/Puerto-Serial.png" />
