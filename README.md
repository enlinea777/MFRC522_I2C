# MFRC522_I2C
Libreria arduino pra trabajar los MFRC522 por defecto en SPI a I2C

Con el fin de usar solo 2 lineas de datos en lugar de 4 y aprobechar el bus i2c con el cual podemos montar mas de un dispositivo en Paralelo, asi liberamos 2 GPIO para uso en otas funciones.
Espesificamente para ESP8266 pero igual funciona con arduino.

Para ESP8266 recomiendo usar GPIO5 GPIO4 o bien  D1 D2 (Wemos)

