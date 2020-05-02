# Diferencias entre git merge y git merge --no--ff

> **Git-merge:** sirve para unir dos o más historias de desarrollo juntas. Es decir, que sirve para incorporar cambios de los commits nombrados en la rama actual. Este comando lo usa git pull para incorporar cambios desde otro repositorio y puede usarse a mano para combinar cambios de una rama a otra.

> En cambio **git merge --no-ff** ,que es una extensión de git merge, puede crear una confirmación de fusión en todos los casos, incluso cuando la fusión podría resolverse como un avance rápido.

* Aca podemos ver algunas imagenes de ejemplo:

!["Imagen"](https://i.stack.imgur.com/83JeN.png)


!["Imagen"](https://res.cloudinary.com/practicaldev/image/fetch/s--4wcz_y0b--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/nqo6mgud5dzbmfpxzqkd.png)