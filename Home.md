Hola!! 

Pasos:
1. Clona el repositorio en donde desees o hacer un fetch total y en lo posible forzado.
2. En el branch master, pasa el codigo a la ESP32.
3. La primera vez la placa arrancará en modo AP por lo que podrás conectarte a ella por medio de WiFi.
 * Encontrarás la red AP del ESP32 como AP-IOT y la contraseña será iotserver.
 * Una vez conectado, podrás acceder a la pagina de la ESP32 desde cualquier navegador en la ip 192.168.4.1
 * En la web solo podrás configurar un WiFi donde conectarte.
 * Una vez lo hagas la placa se reiniciará. Tendrás que repetir el proceso si por alguna razon no logra conectarse al wifi.
4. Ahora la placa inicia en modo Station.
5. Opcionalmente puedes ver en el monitor serial la ip (en un futuro se puede implementar que la misma sea reproducida por audio a travez del ESP32).
6. Opcionalmente puedes ver tu router la ip del ESP32.
7. Tras conectarte a travéz de la IP local al ESP32 podrás configurar los distintos campos.
8. Configura primero la estacion.
9. Configura el broker.
10. COMIENZA A PROBAR EL SENSOR!!! 