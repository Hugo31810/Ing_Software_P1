# Requisitos del Sistema

A continuación se detallan los requisitos no funcionales y de dominio identificados para el caso de estudio.
## Requisitos de Dominio (RD)

| Número | Nombre                          | Descripción                                                                                  |
| :----- | :------------------------------ | :------------------------------------------------------------------------------------------- |
| RD1    | Unidad de medida                | Los dispositivos de las vías envían señales eléctricas medidas en voltios.                   |
| RD2    | Formato de hora                 | El fichero de entrada debe contener la hora en formato (HH:MM:SS:MS).                        |
| RD3    | Indicador de estado             | El fichero de entrada debe usar un valor binario (0/1) para indicar el estado.               |
| RD4    | Múltiples dispositivos          | Pueden existir múltiples dispositivos por cada vía de tren.                                  |
| RD5    | Identificador de dispositivo    | Cada dispositivo debe tener un identificador.                                                |
| RD6    | Semántica de vía libre          | Un valor binario de '1' significa que la vía está libre.                                     |
| RD7    | Semántica de tren en vía        | Un valor binario de '0' significa que hay un tren en la vía.                                 |
| RD8    | Incidencia: Ausencia de datos   | Una ausencia de datos se define como un dispositivo que no emite datos por más de 2 minutos. |
| RD9    | Incidencia: Salto de frecuencia | Un salto de frecuencia se define como una variación de al menos 0.5 voltios.                 |