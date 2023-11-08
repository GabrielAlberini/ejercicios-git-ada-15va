# Ejercicios git

## Ejercicio 1:

1. Crea un nuevo repositorio en tu cuenta de GitHub.
2. Clona el repositorio recién creado en tu computadora.
3. Crea un archivo llamado index.js y escribe dentro de él algunas líneas de texto.
4. Añade el archivo al área de preparación (staging area).
5. Realiza un commit con un mensaje descriptivo.
6. Crea una rama (branch) nueva llamada nueva-funcionalidad.
7. Cambia a esa nueva rama.
8. Agrega una nueva línea de texto al archivo ejercicio.txt.
9. Confirma tus cambios en la rama nueva-funcionalidad.
10. Cambia de nuevo a la rama principal (main/master).
11. Fusiona la rama nueva-funcionalidad con la rama principal.
12. Elimina la rama nueva-funcionalidad.
13. Agrega otra al archivo index.js.
14. Añade este cambio al área de preparación.
15. Realiza otro commit con un mensaje descriptivo.
16. Finalmente, envía los cambios al repositorio remoto en GitHub.

## Ejercicio 2:

1. Crea un repositorio local vacío en tu máquina.
2. Inicializa el repositorio local con `git init`.
3. Crea un archivo de texto llamado `index.js` y escribe dentro de él un pequeño programa.
4. Añade el archivo al área de preparación.
5. Realiza un commit con un mensaje descriptivo.
6. Crea un repositorio vacío en GitHub.
7. Conecta tu repositorio local con el repositorio vacío en GitHub utilizando el comando `git remote add origin <URL_del_r epositorio>`.
8. Sube tu código al repositorio remoto en GitHub utilizando el comando `git push -u origin main` o `git push -u origin master` según la configuración de tu repositorio.
9. Haz algunos cambios en el archivo `index.js`.
10. Añade estos cambios al área de preparación.
11. Realiza otro commit con un mensaje descriptivo.
12. Sube los cambios al repositorio remoto en GitHub.
13. Crea una nueva rama llamada `actualizaciones`.
14. Realiza algunos cambios en el archivo `index.js` en esta nueva rama.
15. Añade estos cambios al área de preparación.
16. Realiza un commit con un mensaje descriptivo.
17. Sube la nueva rama al repositorio remoto en GitHub.
18. Fusiona la rama `actualizaciones` con la rama principal (main o master).
19. Sube los cambios fusionados al repositorio remoto en GitHub.
20. Verifica que todas las operaciones se hayan realizado correctamente en el repositorio remoto.

## Ejercicio 3:

1. Crea un nuevo repositorio local vacío en tu máquina.
2. Inicializa el repositorio local con `git init`.
3. Crea un archivo de texto llamado `ejercicio.js` y escribe dentro de él un pequeño programa en JavaScript.
4. Añade el archivo al área de preparación con `git add ejercicio.js`.
5. Realiza un commit con un mensaje descriptivo con `git commit -m "Agregando archivo de ejercicio en JavaScript"`.
6. Crea un repositorio vacío en tu cuenta de GitHub.
7. Conecta tu repositorio local con el repositorio remoto en GitHub con `git remote add origin <URL_del_repositorio>`.
8. Sube tu código al repositorio remoto en GitHub con `git push -u origin master`.
9. Haz algunos cambios en el archivo `ejercicio.js`.
10. Añade estos cambios al área de preparación con `git add ejercicio.js`.
11. Realiza otro commit con un mensaje descriptivo con `git commit -m "Realizando cambios en el ejercicio en JavaScript"`.
12. Sube los cambios al repositorio remoto en GitHub con `git push origin main`.
13. Crea una nueva rama llamada `actualizaciones` con `git branch actualizaciones`.
14. Cambia a la nueva rama con `git checkout actualizaciones`.
15. Realiza algunos cambios en el archivo `ejercicio.js` en esta nueva rama.
16. Añade estos cambios al área de preparación con `git add ejercicio.js`.
17. Realiza un commit con un mensaje descriptivo con `git commit -m "Agregando nuevas funcionalidades al ejercicio en JavaScript"`.
18. Sube la nueva rama al repositorio remoto en GitHub con `git push origin actualizaciones`.
19. Cambia de nuevo a la rama principal con `git checkout master`.
20. Fusiona la rama `actualizaciones` con la rama principal con `git merge actualizaciones`.
21. Sube los cambios fusionados al repositorio remoto en GitHub con `git push origin master`.

## Ejercicio 4:

1. Inicia sesión en tu cuenta de GitHub.
2. Busca un repositorio público que te interese.
3. Haz clic en el botón "Fork" en la esquina superior derecha de la página del repositorio para hacer una copia del repositorio en tu cuenta.
4. Clona tu repositorio recién bifurcado en tu máquina local con el comando `git clone <URL_del_repositorio_fork>`.
5. Realiza algunos cambios en el código o agrega archivos nuevos en tu repositorio local en una nueva rama.
6. Añade los cambios al área de preparación con `git add .` para agregar todos los cambios, o usa `git add <nombre_del_archivo>` para agregar cambios específicos.
7. Realiza un commit con un mensaje descriptivo con `git commit -m "Realizando cambios en el repositorio bifurcado"`.
8. Sube los cambios a tu repositorio bifurcado en GitHub con `git push origin <nombre_de_tu_rama>`.
9. Desde la página de tu repositorio bifurcado en GitHub, haz clic en el botón "Pull Request" para iniciar una nueva solicitud de extracción.
10. Completa los detalles de la solicitud de extracción y envía la solicitud para que el propietario original del repositorio la revise.
