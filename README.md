### STAPi
```
   _____ _______       _____ _ 
  / ____|__   __|/\   |  __ (_)  SYSTEM
 | (___    | |  /  \  | |__) |   TARGETED
  \___ \   | | / /\ \ |  ___/ |  ATTACK
  ____) |  | |/ ____ \| |   | |  WITH
 |_____/   |_/_/    \_\_|   |_|  RASPBERRY Pi
 ############################################
     ###### BIENVENIDO A STAPi ########    
```

STAPi
==========


Stapi son una serie de scripts para autmatizar diversos ataques o acciones desde una raspberry pi.
El proyecto se ha desarrollado sobre una raspberry pi 3 modelo B, con una de las siguientes imagenes de kali preinstalado:

kali-linux-2018-3-rpi3-nexmon-img-xz \
kali-linux-2018-3-rpi3-img-xz

https://www.offensive-security.com/kali-linux-arm-images/

Documentacion de STAPi
======================
- Canal \
https://www.youtube.com/channel/UCNn4iXrlHpq2lhi8bK1FbvA
- Instalacion \
https://www.youtube.com/watch?v=zxuyDmJ2qsM 
- PiTunel (conexion reversa ssh) 1 parte (red local) \
https://www.youtube.com/watch?v=O3aRwEt1XkM
- PiTunel (conexion reversa ssh) 2 parte (Fuera de red local) \
https://www.youtube.com/watch?v=xFVGuHjLKt4
- STAPi en ADN40 porgrama ojo socultos. (tv mexicana) \
https://www.youtube.com/watch?v=qVDNcJDnCJs
- Stapiando (grabacion de pantalla durante las acciones en el reportaje. Solo musica y comandos.) \
https://www.youtube.com/watch?v=dWmAYyG3XYc
- Proyecto STAPi \
https://www.youtube.com/watch?v=00BBBcfRLV4
- STAPi & deby Comprometiendo netbios (solo musica y comandos) \
https://www.youtube.com/watch?v=huRcoKNzuRY



Instrucciones de instalacion:
==============================
```
git clone https://github.com/javierbu/stapi.git
cd stapi
tar -xf stapi-0.0.13.tar
cd install
./install_stapi.sh
```
DURANTE EL PROCESO DE INSTALACION DE LAS DEPENDENCIAS, NOS HARAN 3 PREGUNTAS, A LAS QUE RESPONDER ENTER CON LAS OPCIONES POR DEFAULT.

Con este script instalamos todas las dependencias necesarias desde los repositorios, ademas instalamos/actualizamos reaver y aircrack-ng

Adcionalmente, el scrit descargara e intalara el proyecto create_ap

https://github.com/oblique/create_ap

Nos ayudaremos de create_ap para algunas de las herramientas.

Tambien se crearan algunas carpetas, se haran copias de seguridad de algunos archivos de configuracion, y se restauraran por otros.

STAPizar
========

Esta accion no es necesaria para que funcionen las herramientas.

Stapizando nuestro kali conseguiremos algunas ventajas al usar stapi:

- Aviso de ataques en marcha al inicia sesion 
- Algunos alias para trabajar mas comodo en consola 
- Banner de bienvenida al inicio 
- Funcion autocompletar en la consola 
- Cambio de color de prompt a amarillo 
- Cambio hostmane STAPi 

stapizar:
(Desde la carpeta install/)
```
cd stapi
./stapizar.sh
```
Dispositivos wifi usb compatibles con ataque mana STAPI
=======================================================
https://github.com/javierbu/stapi/wiki/Dispositivos-compatibles-con-ataque-mana-STAPi



