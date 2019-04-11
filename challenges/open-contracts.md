# Contratos Abiertos

## Problema

Las Contrataciones Abiertas son aquellos datos generados por el gobierno al pasar por procesos de contratación o adquisición de bienes, servicios u obras.

Actualmente existen algunas APIs de contrataciones abiertas publicadas por algunos gobiernos para transparentar el gasto público. Sin embargo, para ser mostrados al ciudadano común, estos datos necesitan ser consumidos por otra aplicación que además les de formato para hacerla legible a la vista humana.

## Solución

Por tal motivo, se solicita el desarrollo de una aplicación Web que permita tener una interfaz amigable y legible de los datos abiertos de contrataciones públicas generados por algunas instancias de gobierno y que sea accesible mediante cualquier dispositivo conectado a Internet. 

## Limitantes

Deberá ser una aplicación Web. Sin embargo, deberá ser responsiva y adaptable al dispositivo desde el que se visualice. Se solicita, además, en el caso de utilizar alguna librería de terceros, que ésta sea de código abierto o cuyo uso no implique costo alguno. 

## Criterios de aceptación

- La aplicación deberá consultar  las APIs publicadas en cualquiera de estos dos portales: 

 - https://contratacionesabiertas.jalisco.gob.mx. 

 - http://www.contratosabiertos.cdmx.gob.mx. 

- La aplicación deberá permitir filtra la información sobre contratos de un año en específico. 

- Para ese año específico, deberá poder mostrar, en un listado con paginación, el conjunto de contratos realizados. Cada contrato deberá tener un enlace a su información en específico. 

- Dentro de cada contrato, deberá existir un enlace para consultar la información del proveedor de ese enlace. 

- Deberá existir un buscador para que el usuario busque un proceso de contratación por palabra clave. 

- Los formularios respectivos deberán contar con las validaciones necesarias para garantizar la correcta experiencia de usuario: 

 - Los campos obligatorios no deberán estar vacíos. 

 - Se deberán mostrar mensajes de error, remarcando los campos de formulario que presenten algún problema. 

 

## Recomendaciones

#### Stack de tecnologías sugeridas. 

##### Frontend para consulta de las APIs: 
Angular.
React.

##### Diseño de interfaz: 

HTML5. 
CSS. 
SASS. 
Bootstrap 4. 
