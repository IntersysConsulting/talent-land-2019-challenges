# Bot Food

##Descripcion
Una empresa de servicio de comida proporciona a sus clientes un Google Sheets como este 

 [Google Sheet](https://docs.google.com/spreadsheets/d/1AACXoQ45jFIOm53mN57ge65mmXzGahgTivHW-j_xIWs/edit?usp=sharing  "Google Sheet")
 
 Donde cada semana las personas tienen que entrar y rellenar las filas con sus pedidos cada viernes

## Problema
Algunas personas olvidan llenar el Google Sheet en el tiempo adecuado y con el pasar de los días se olvidan de lo que pidieron para determinado día

## Solución
Hacer un Slack bot que permita hacer los pedidos de comida y que nos recuerde cuando deberíamos hacerlos, así como también nos permita consultar nuestro pedido.

## Informacio util

Contenido del Google Sheet:
<img src="https://raw.githubusercontent.com/IntersysConsulting/talent-land-2019-challenges/master/assets/BotFood-img1.png?sanitize=true" width="25%" height="25%">

La parte A: son los platillos disponibles por día de la semana, son las opciones que el bot debe sugerir para que realizes tu pedido.

La parte B: es la que debe llenar el bot
Columnas:
- A: número de orden “1,2,3,4”
- B: email del usuario
- C: total de días que pidió comida “1,2,3,4,5”
- E,F,G,H,I: platillo seleccionado por día

## Stack de tecnologías
usa las tecnologías con las que te sientas mas cómodo.

## Criterio de aceptación:
- hacer el pedido rellenando el  Google Sheets
- recordatorio los viernes para hacer el pedido
- el bot debe responder a la pregunta “¿que pedi el día X?



