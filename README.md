# TEMPI2Cdisp_PIC32MX
FreeRTOS sobre PIC32MX y medición de temperatura con TCN75A sobre I 2C.
Este proyeto comprende la realizacion de varias tareas programadas en Mplab con Harmony ademas usa el Chipckit uc32 y el ChipKit Basic I/O Shield para visualizar las diferentes actividades codificadas, a continuacion se listan algunas de ellas.

    Parpadeo intermitente de dos leds con la utilizacion de Timers 1 y 2.
    Lectura del adc y codificacion de leds para su encedndido en funcion de la lectura del ADC.
    Visualizacion de la lectura del adc atravez del puesto UART1 en consola y en la pantalla del I/O Shield
    Finalmente uso del protocolo I2C para el visualizacion de temperatura del sensor digital TCN75A.
