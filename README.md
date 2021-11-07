# Raspberry PI para dispositivo de Streaming

## Introduccion

Para entender como funcionaria esto, debemos entender que es un **Chrome Cast**; el Chrome Cast funciona para converitr en Smart TV un televisor que ya sea por modelo o por antiguedad, no es compatible con esta opcion. 
 ![Chrome Cast](https://www.alkosto.com/medias/193575001371-001-750Wx750H?context=bWFzdGVyfGltYWdlc3wxMTExODl8aW1hZ2UvanBlZ3xpbWFnZXMvaDU3L2g2NS85NTQ0MzE3NzMwODQ2LmpwZ3w2YWJhZjAyNjFkYTBlOTk4YjcyN2U2ZGFlOTlhODJmZGJkNGY1ZWM2ZmI3YjAzMTRkZmU5YmY0MWRlNzQ2YzZm)

El adaptador se concecta por _HDMI_ al televisor y por _USB_ a la fuente de poder. A su vez es necesario una _APP_ para disposditivo movil la cual es la parte escencial del adaptador, puesto que esta es la que da la señal que se proyectara, sin embargo, una vez que empiece la transmisión. no es necesario mantener la _App_ abierta pra usar el Chrome Cast

## Procedimiento
Para realizar este montaje es necesario: 
1. Raspberry Pi 3 (**cualquier modelo puede funcionar, pero para algunos ser anecesario el adaptador WIfi**)
2. Raspberry Pi case
3. Tarjeta MIcro SD para almacenamiento
4. Cable y cargador micro USB
5. Cable HDMI
6. Lector de tarjeta SD
7. Mouse y Teclado
Para poder mirar paso y detalladamente como realizar el montaje, puedes [dar click aqui](https://www.instructables.com/Raspberry-Pi-As-Chromecast-Alternative-Raspicast/) Y te llevará a una pagina donde se te mostrara. 

## Limitaciones del Proyecto

Para esto haremos una tabla comparativa entre el Chrome Cast y el proceso Analogico de stream.

     Pros         |       Contras
  --------------- | ---------------- 
   Usar sin necesidad de cables | Dependencia de un dispositivo externo para su funcionamiento
  Posibilidad de usar el dispositivo, del cual se conecta. Asi este este transmiteindo | Dependencia del Raspberry Pi a estar conectado a WiFi
  
  
