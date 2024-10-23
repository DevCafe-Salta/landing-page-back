### Trabajando con la rama develop
Este proyecto sigue un flujo de trabajo basado en ramas para mantener un desarrollo organizado y controlado. Asegúrate de seguir estas pautas al colaborar en el proyecto:

Clona el Repositorio: Comienza clonando el repositorio a tu máquina local:
  
bash
git clone <url del repo>


Checkout a develop: Cambia a la rama develop con el siguiente comando:

bash
git checkout develop
git pull origin develop


Crea una rama: Crea una rama local con un nombre descriptivo de la funcionalidad que vas a desarrollar. Utiliza el siguiente comando para crear una nueva rama y cambiar a ella:

bash
git checkout -b <nombre de la rama>


Realiza los cambios: Realiza los cambios necesarios en el código para implementar la funcionalidad que estás desarrollando. Y luego hacer el push a la rama creada. (tu rama creada)

bash
git add .
git commit -m "mensaje descriptivo de los cambios realizados"
git push origin <nombre de la rama>


En caso de que otros colaboradores hayan realizado cambios en la rama develop mientras trabajabas en tu rama, deberás actualizar tu rama con los últimos cambios antes de hacer el push. Para ello, cambia a la rama develop y ejecuta el siguiente comando:

bash
git pull origin develop


Crea un Pull Request: Cuando hayas terminado de implementar la funcionalidad, crea un Pull Request (PR) a la rama develop para que tus cambios sean revisados y aprobados por los colaboradores del proyecto. Asegúrate de seguir las siguientes pautas al crear un PR:

- El título del PR debe ser descriptivo y conciso.
- El cuerpo del PR debe describir los cambios realizados y explicar cómo se implementó la funcionalidad.
- El PR debe ser revisado por al menos dos colaboradores antes de ser aprobado. 


