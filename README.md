# repo04
Ejemplo de no-fast-forward

Por cambiar, una vez en la rama main, cambiaremos directamente a una nueva rama con:

> git checkout -b <nombre_rama>

Donde haremos modificaciones, las publicaremos, volveremos a la rama main y mergearemos con no fast forward.

> git merge --no-ff -m "Mensaje informativo"
