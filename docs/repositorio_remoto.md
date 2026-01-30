# Cómo hacer un repositorio en línea

Para poder subir un repositorio local a la nube se han de usar los siguiente comandos:

1. Luego de haber guardado los cambios con el commit, se debe hacer una conexión al repositorio remoto de la siguiente manera:

git remote add "conexión remota" "dirección del repositorio remoto"

2. Luego de establecida la conexión remota se debe revisar con:

git remote -v

3. Estando ya seguros de que la conexión remota está establecida y los commits necesarios hechos se deben enviar a la nube con:

git push -u "nombre de conexión remota" "nombre de la rama de trabajo"

4. Si se desea traer algo de la nube al local se puede utilizar:

git pull