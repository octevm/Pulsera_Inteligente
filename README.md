# Sensor Detector de moviento

## Integrantes
- González Hernández Omar Martín 
- Martinez Aldavera Alma Yesenia
- Mata Rojas Carlos Eduardo
- Gutierrez Rodríguez José Armando

## Objetivo General
Elaborar una aplicación que tenga la funciòn de Sensor para alertar al usuario si es que algo pasa cerca del rango, mandando una notificaciòn a Telegram y a su vez, encenderia una luz al momento de detectar el movimiento

## Tabla de Software utilizado 
| id |  Software          |  Versión  |  Tipo  |
|----|--------------------|-----------|--------|
|  1 | Arduino            |  2.0.0    |  IDE   |
|    |                    |           |        |


## Tabla con el hardware utilizado
| Id | Componente | Descripción |                                          Imagen                                                   | Cantidad | Costo total |
|----|------------|-------------|---------------------------------------------------------------------------------------------------|----------|-------------|
| 1  |   ESP32    | El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos|![image](https://user-images.githubusercontent.com/114530252/193129351-bd6be0c7-6dee-45eb-87a9-7538fc797dd2.png)|   1      |   165       
| 2  |Sensor      |El módulo Ray Optics Module puede utilizarse para modelar propagación de ondas electromagnéticas en sistemas en los que la longitud de onda es mucho menor que el menor detalle geométrico en el modelo. |![image](https://user-images.githubusercontent.com/114530252/193268184-aff403bb-0334-428c-b4ee-b16ccd35e9df.png)
|   1      |   15          |
| 3  |Cables Dupont|Cables Dupont para Protoboard M/M son cables jumper de 15cm de largo terminados como macho a hembra. Estos se usan para conectarse desde cualquier header hembra o macho en cualquier placa. Múltiples jumpers se pueden conectar uno al lado del otro en un conector de 2.54mm.|![image](https://user-images.githubusercontent.com/114530252/193132887-4ce7f032-468d-4945-b6e2-941ffb6ba5cc.png)|   1      |      15     |
| 5  |Un foco    |Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz|![image](https://user-images.githubusercontent.com/99991865/192933021-f55b80cb-b9ae-44ac-99c5-23cd6ff9bc79.png)|   1      |      15     |
| 6  |Sensor RIP|se utilizan en los circuitos para limitar el valor de la corriente o para fijar el valor de la tensión, según la Ley de Ohm|![image](https://user-images.githubusercontent.com/114530252/193268355-81a4d57e-f668-4347-89de-3418aef29596.png)|   5      |  10         |
| 7  |Pines Macho  |Tira de pines macho quebrantables. Este tipo de conector es ampliamente usado en múltiples aplicaciones. Pueden separarse en segmentos para adecuarse a la cantidad de conexiones requeridas. Excelentes para ser usados con Cables Jumper Hembra, Pines hembra, Protoboard etc|![image](https://user-images.githubusercontent.com/114530252/193268571-78af554a-6a0c-4360-ae71-48fce80e0a77.png)
|   1      |     110        |
| 8  |Zòcalo   de 40 pines  |Es una herramienta de alta calidad y sencilla conexión que facilita la programación a circuitos integrados DIP o de microcontroladores, como su nombre lo indica (fuerza de inserción cero) el chip solo caerá en el zócalo y una presión de la palanca bloqueará en su lugar.|![image](https://user-images.githubusercontent.com/99991865/192934122-6938a1d7-55a6-4caa-85c9-80a27cf06301.png)|   5      |    55        |
| 9  |Modulo Ray|El módulo Ray Optics Module puede utilizarse para modelar propagación de ondas electromagnéticas en sistemas en los que la longitud de onda es mucho menor que el menor detalle geométrico en el modelo.|![image](https://user-images.githubusercontent.com/114530252/193269171-54ac87d8-d8fa-4e5e-98c2-ccfbd0052e72.png)|   1      |    85        |


## Epicas del proyecto
- Detecta si hay algo en un rango del sensor
- Calcula la distancia de dicho objeto
- Envía una notificicación al dueño por medio de telegram
- Emite una luz para alertar de que ese algo se aproxima

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  | Funcionalidad del proyecto                    |  Alta         | 0.5           |Realizar prubas correspondientes con alguna detección de gas para comprobar que su funcionamiento sea el correcto.            |Integrantes de equipo             |
| 2  |Funcionalidad del sensor   | Alta          | 0.5          | Realizar prueba con algùn objeto y verofocar que llegue la nptofocaciòn del mismo.             | Integrantes de equipo |
| 3  | Funcionalidad del foco             | Media         |  0.3          | Realizar prueba para verificar el funcionamiento del foco             |   integrantes del equipo          |

## Boceto
![image](https://user-images.githubusercontent.com/114530252/193131130-8c1bf856-4f02-4f27-a49c-0fe42ffa8b16.png)
