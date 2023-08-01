# TEMPI2Cdisp_PIC32MX
FreeRTOS sobre PIC32MX y medición de temperatura con TCN75A sobre I 2C.
Este proyecto comprende la realización de varias tareas programadas en Mplab con Harmony ademas usa el Chipckit uc32 y el ChipKit Basic I/O Shield para visualizar las diferentes actividades codificadas, a continuación se listan algunas de ellas.

    Parpadeo intermitente de dos leds con la utilización de Timers 1 y 2.
    Lectura del adc y codificación de leds para su encendido en función de la lectura del ADC.
    Visualización de la lectura del adc a travez del puesto UART1 en consola y en la pantalla del I/O Shield
    Finalmente uso del protocolo I2C para el visualización de temperatura del sensor digital TCN75A.
