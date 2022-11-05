# STM32F407-OV7670-ili9341
El proyecto es una integración de una cámara ov7670 junto con un LCD ili9341 de interfaz paralela de 8 bits conectados a una placa STM32F407 DISCOVERY


El proyecto continua en fase de desarrollo, todo esta programado en STM32 CUBE IDE. Las fallas actuales se centran en la integración de la cámara y la captura de imágen, es posible cargar una imagen que sea visible en el LCD 

Las limitaciones actuales son: ILI9341 de 8 bits, no permite redireccionar la infomración de la cámara de forma efectiva
No se ha asignado correctamente la dirección de memoria donde el protocolo DCMI debe enviar la imagen. 

Sugerencias: Generar una IMAGEN JPEG y guardarla en la memoria Flash
