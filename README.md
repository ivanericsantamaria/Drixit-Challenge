Relevar los issues correspondientes y reportarlos en el board de tu repositorio:
https://github.com/ivanericsantamaria/Drixit-Challenge/projects.


Detallar brevemente el proceso para la detección de issues y consideraciones a la hora de reportarlos:
Primeramente leo la documentación y la user story, una vez leído y entendido todo (incluso los comentarios que se van dejando en la US a medida que se desarrolla), comienzo a testear verificando el cumplimiento de los CDA (criterios de aceptación).
Si encuentro un issue, verifico todo lo que sea necesario para comprobar que realmente lo sea y una vez confirmado me encargo de redactar un ticket de BUG (o issue) bien detallado, en el que se explique el problema como debe funcionar o verse realmente y dejo toda la evidencia necesaria para que quien lo tome lo pueda entender correctamente y así realmente se pueda llegar al fix necesario y evitar algun rework de la tarea por falta de entendimiento.


Si encontrases un bug en la plataforma que no podés reproducir de manera consistente, cómo lo reportarías? Explicar con ejemplos:
Para comenzar una vez encontrado un bug lo primero que hago es intentar reproducirlo, si veo que esto no vuelve a ocurrir lo sigo intentando hasta dar con los pasos y combinaciones necesarias para que vuelva a suceder, si todo esto falla, genero un ticket de bug como siempre, detallando los pasos específicos para reproducirlo pero en este caso dejo aclarado que este comportamiento no es siempre el mismo, y las condiciones e información que considere pertinente.
Un ejemplo real que puedo dar de esto es un caso que me sucedió recientemente, en el que un desplegable de “localidades” por momentos aparecía con un desplegable con las opciones correctas a completar y otras aparecía como un casillero a completar. En este último escenario, al completarlo con una localidad que no estaba contemplada en la base de datos generaba un error que impedía al usuario generar cualquier tipo de compra.
Ante estos casos es muy importante conversar con el equipo en las dailys o incluso en los canales de comunicación cotidianos, en mi caso Slack, para que todo el equipo esté al tanto de lo que ocurre y el problema pueda ser solucionado a la brevedad.


Cómo procederías si vieras una traducción/redacción que consideras errónea pero la misma se encuentra implementada tal como indica la documentación?
Como primera instancia lo consultaría con el equipo en una daily y propondría modificar la documentación para asegurar la calidad desde el planeamiento.



BONUS POINTS:

Cuales serían los test cases que harías para una pantalla de login?
https://docs.google.com/spreadsheets/d/1J2qN65OlCwBCdeeu9zS911jiCu7MvZlUdy1HsPaUIgU/edit?usp=sharing

