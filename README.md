# Sensor Detector de moviento

## Integrantes
- González Hernández Omar Martín 
- Martinez Aldavera Alma Yesenia
- Mata Rojas Carlos Eduardo
- Gutierrez Rodríguez José Armando

## Objetivo General

Se busa realizar una mecanismo el cual funcionaría como sistema de seguridad para tu hogar, siendo una conexión en la cual el usuario podrá saber lo que pase en su hogar por medio de una app, en la cual buscaremos utilizar varios sensores, para que el usuario reciba una notificación a su celular por medio de una red social de su elección o por medio del correo electronico, en el cual se le notificará a el usuario si hubo detección de movimiento en el cual se utilizaran varios sensores para que el usuario pueda ver lo que sucede; la distancia del objeto, humo en caso de un incendio o por incidentes que conlleven humo, y un sensor que le ayudará al usaurio conocer la temperatura y humedad del lugar.  

## Tabla de Software utilizado 
| id |  Software          |  Versión  |  Tipo  |
|----|--------------------|-----------|--------|
|  1 | Arduino            |  2.0.0    |  IDE   |
|    |                    |           |        |


## Tabla con el hardware utilizado
| Id | Componente | Descripción |                                          Imagen                                                   | Cantidad | Costo total |
|----|------------|-------------|---------------------------------------------------------------------------------------------------|----------|-------------|
| 1  |   ESP32    | El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos|![image](https://user-images.githubusercontent.com/114530252/198726741-b71c3606-65e7-45dc-a166-b199497f7f95.png)|   1      |   165 |      
| 2  |Sensor DTH11     |El módulo Ray Optics Module puede utilizarse para modelar propagación de ondas electromagnéticas en sistemas en los que la longitud de onda es mucho menor que el menor detalle geométrico en el modelo. |![image](https://user-images.githubusercontent.com/114530252/198726655-864da248-5d4f-4c82-9e12-7507dafcd445.png)|   2    |   30   |
| 3  |Cables Dupont|Cables Dupont para Protoboard M/M son cables jumper de 15cm de largo terminados como macho a hembra. Estos se usan para conectarse desde cualquier header hembra o macho en cualquier placa. Múltiples jumpers se pueden conectar uno al lado del otro en un conector de 2.54mm.|![image](https://user-images.githubusercontent.com/114530252/193132887-4ce7f032-468d-4945-b6e2-941ffb6ba5cc.png)|   10      |      20     |
| 5  |LED    |Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz|![image](https://user-images.githubusercontent.com/99991865/192933021-f55b80cb-b9ae-44ac-99c5-23cd6ff9bc79.png)|   2      |      5     |
| 6  |Sensor RIP|se utilizan en los circuitos para limitar el valor de la corriente o para fijar el valor de la tensión, según la Ley de Ohm|![image](https://user-images.githubusercontent.com/114530252/193268355-81a4d57e-f668-4347-89de-3418aef29596.png)|   5      |  10         |
| 7  |Pines Macho  |Tira de pines macho quebrantables. Este tipo de conector es ampliamente usado en múltiples aplicaciones. Pueden separarse en segmentos para adecuarse a la cantidad de conexiones requeridas. Excelentes para ser usados con Cables Jumper Hembra, Pines hembra, Protoboard etc|![image](https://user-images.githubusercontent.com/114530252/193268571-78af554a-6a0c-4360-ae71-48fce80e0a77.png)|   1       |    110  |
| 8  |Zòcalo   de 40 pines  |Es una herramienta de alta calidad y sencilla conexión que facilita la programación a circuitos integrados DIP o de microcontroladores, como su nombre lo indica (fuerza de inserción cero) el chip solo caerá en el zócalo y una presión de la palanca bloqueará en su lugar.|![image](https://user-images.githubusercontent.com/114530252/198727482-90ab6998-e775-4f2f-8824-0b60c5bbd3d2.png)|   5      |    55        |
| 9  |Modulo Ray|El módulo Ray Optics Module puede utilizarse para modelar propagación de ondas electromagnéticas en sistemas en los que la longitud de onda es mucho menor que el menor detalle geométrico en el modelo.|![image](https://user-images.githubusercontent.com/114530252/193269171-54ac87d8-d8fa-4e5e-98c2-ccfbd0052e72.png)|   1      |    48        |
|  10    |  sensor de humo| El módulo del sensor de gas MQ-2 es un dispositivo que se utiliza para detectar y medir la concentración de gases en el aire. Puede detectar tales gases como: GLP, propano, metano, hidrógeno, alcohol, humo y carbono monóxido. |![image](https://user-images.githubusercontent.com/114530252/198729872-53c7f8cf-ab0a-437f-b917-543df0e18423.png)|   1   | 72  |

## Epicas del proyecto
- Detecta si hay algo en un rango del sensor
- Calcula la distancia de dicho objeto
- Envía una notificicación al dueño por medio de telegram
- Emite una luz para alertar de que ese algo se aproxima
- Envía una notificación en caso de detectar humo
- El usuario sabrá en tiempo real la temperatura y humedad del lugar

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  | Funcionalidad del proyecto                    |  Alta         | 0.5           |Realizar prubas correspondientes con alguna detección de gas para comprobar que su funcionamiento sea el correcto.            |Integrantes de equipo             |
| 2  |Funcionalidad del sensor   | Alta          | 0.5          | Realizar prueba con algùn objeto y verofocar que llegue la nptofocaciòn del mismo.             | Integrantes de equipo |
| 3  | Funcionalidad del foco             | Media         |  0.3          | Realizar prueba para verificar el funcionamiento del foco             |   integrantes del equipo          |

## Boceto
![image](https://user-images.githubusercontent.com/114530252/193131130-8c1bf856-4f02-4f27-a49c-0fe42ffa8b16.png)
