# Socket UDP

Para poder ejecutar este programa nos ubicamos en la carpeta donde se encuentra el paquete

## Compilar
Se compila la solución y si se codifica de forma correcta, se generan archivos .class de cada archivo .java
```console
your@terminal:~$ cd A4-socket-udp/E4
your@terminal:~$ javac *.java
```

## Terminal 2
Se inicia el servidor
```console
your@terminal:~$ cd A4-socket-udp/E4
your@terminal:~$ java ServidorUDP
```

## Terminal 3
Se inicia el cliente y se agrega la dirección IP del servidor a conectarse
```console
your@terminal:~$ cd A4-socket-udp/E4
your@terminal:~$ java ClienteUDP <<DIRECCION_IP>>
```
