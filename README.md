# Raspberry PI para dispositivo de Streaming

## Introduccion

Para entender como funcionaria esto, debemos entender que es un **Chrome Cast**; el Chrome Cast funciona para converitr en Smart TV un televisor que ya sea por modelo o por antiguedad, no es compatible con esta opcion. 
* Algunas Apps que se pueden usar en el TV gracias al dispostitivo que simula un Chrome Cast
  *  Netflix 
  *  Spotify
  *  Google Music
  *  YouTube
  *  Cualquier  App de Stream disponible para Android
   
      
 ![Dispositivo terminado](https://content.instructables.com/ORIG/FZN/15J1/JCAUC1H4/FZN15J1JCAUC1H4.jpg?auto=webp&frame=1&width=700&height=1024&fit=bounds&md=65de648f49a80918b530e2e5b4ab90f5)

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
Posibilidad de usar el dispositivo, del cual se conecta. Asi este esté transmiteindo | Dependencia del Raspberry Pi a estar conectado a WiFi
Convertir cualquier televisor que tenga entrada HDMI a un Smart TV | La App presentada, solo esta para Android, es necesario crear una para Apple.

Su propio creador dice: 
> This is not a direct clone to Chromecast and that there are limitations. This method does not support the cast button but will stream Youtube videos as well as local audio and video files directly from your smartphone using an Android application. And I believe this application is only for android devices. 


## Referencias

 * https://www.instructables.com/Raspberry-Pi-As-Chromecast-Alternative-Raspicast/
  
  
