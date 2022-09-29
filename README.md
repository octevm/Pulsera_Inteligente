# Pulsera_Inteligente

## Integrantes
- González Hernández Omar Martín 
- Martinez Aldavera Alma Yesenia
- Mata Rojas Carlos Eduardo
- Gutierrez Rodríguez José Armando

## Objetivo General
Elaborar una aplicación que nos permita utilizar funciones del celular (hora,)

## Tabla de Software utilizado 
| id |  Software          |  Versión  |  Tipo  |
|----|--------------------|-----------|--------|
|  1 | Arduino            |  2.0.0    |  IDE   |
|    |                    |           |        |






## Tabla con el hardware utilizado
| Id | Componente | Descripción |                                          Imagen                                                   | Cantidad | Costo total |
|----|------------|-------------|---------------------------------------------------------------------------------------------------|----------|-------------|
| 1  |   ESP32    | El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos|![image](https://user-images.githubusercontent.com/99991865/192933367-82d60a6b-83a0-4d76-9aa7-742fb42d2d3c.png)|   1      |   165       
| 2  |Led verdes  |Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz |![image](https://user-images.githubusercontent.com/99991865/192932983-84794e7e-a316-4e55-825b-cfb9cd3e808a.png)|   1      |   15          |
| 4  |Led amarillo|Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz|![image](https://user-images.githubusercontent.com/99991865/192933020-9a90e9b7-8c89-410f-a89d-7dc7f99814ef.png)|   1      |      15     |
| 5  |Led rojo    |Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz|![image](https://user-images.githubusercontent.com/99991865/192933021-f55b80cb-b9ae-44ac-99c5-23cd6ff9bc79.png)|   1      |      15     |
| 6  |Resistencias de 1k|se utilizan en los circuitos para limitar el valor de la corriente o para fijar el valor de la tensión, según la Ley de Ohm|![image](https://user-images.githubusercontent.com/99991865/192933039-0b857725-d306-4ced-ae16-679589196f19.png)|   5      |  10         |
| 7  |Protoboard  |es un tablero con orificios que se encuentran conectados eléctricamente entre sí de manera interna, habitualmente siguiendo patrones de líneas, en el cual se pueden insertar componentes electrónicos, cables para el armado|![image](https://user-images.githubusercontent.com/99991865/192933683-d1955de9-b1fa-4063-8218-b822c8b7eedf.png)|   1      |     110        |
| 8  |Cables     |sirve para conectar todos los compenetes a la protoboard|![image](https://user-images.githubusercontent.com/99991865/192934122-6938a1d7-55a6-4caa-85c9-80a27cf06301.png)|   5      |    55        |
| 9  |sensor de alcohol|Dispositivo que detecta vapor de alcohol y entrega una salida análoga dependiendo de la concentración. Descripción: Dispositivo que detecta vapor de alcohol y entrega una salida análoga dependiendo de la concentración de alcohol|![image](https://user-images.githubusercontent.com/99991865/192934822-a7126c55-1201-467f-b89a-ab26aeb36c17.png)|   1      |    85        |


## Epicas del proyecto
- Detecta si hay algo en un rango del sensor
- Calcula la distancia de dicho objeto
- Envía una notificicación al dueño por medio de telegram
- Emite una luz para alertar de que ese algo se aproxima

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  | Funcionalidad del proyecto                    |  Alta         | 0.5           |Realizar prubas correspondientes con alguna detección de gas para comprobar que su funcionamiento sea el correcto.            |Integrantes de equipo             |
| 2  |Funcionalidad del sensor de gas MQ 3   | Alta          | 0.5          | Realizar prueba con algún gas posible de verificar el funcionamiento del mismo.             | Integrantes de equipo |
| 3  | Funcionalidad de los leds             | Media         |  0.3          | Realizar prueba segun el nivel del gas se encenderan             |   integrantes del equipo          |
