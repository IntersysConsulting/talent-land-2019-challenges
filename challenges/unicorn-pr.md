# Unicorneando las PR

## Problema

Los developers por que developers no pueden seguir los guidelines de los PR y no siguen el proceso para una revisión rápida y de calidad.

## Solución

Agregar un bot en Github que pueda escribir mensajes a los developers en sus pull requests de modo que puedan recordar los guidelines necesarios que deben cumplir todas las PR creadas.


## Criterios de aceptación

- El script desarrollado deberá tener mínimo dos reglas que validen algunos de los guidelines
sugeridos a los creadores de las PR.

- Con el fin de promover una cultura de reconocimiento, el script deberá tener mínimo
una regla para imprimir un comentario celebrando un logro del desarrollador, como por ejemplo,
felicitar al autor ya que la PR cumple con los requisitos.

- El repositorio debe ser creado en Github.

## Recomendaciones

Guidelines sugeridos:

- “No hay reviewers agregados. Por favor, sugiere un reviewer.”
- “No veo ninguna ninguna descripción en ésta PR”
- “El título no contiene el ticket (JIRA, Trello Card, Issue, etc). Por favor, agregalo.”

### Stack de tecnologías sugeridas

Danger JS (o Danger también para swift o ruby), CircleCI