## Examen COD

1. En primer lugar hacemos un fork del proyecto y lo clonamos en nuestro pc para trabajar con el.

2. Pasamos todas las ramas a local y creamos una nueva llamada readme donde vamos a escribir este Readme.

3. Juntamos el código de las otras dos ramas en la main con merge delde el propio IDE

4. Eliminamos el último commit de la interfaz ya que da error y no queremos mezclarlo

5. Ahora realizamos correctamente el merge y hacemos un único commit con merge squash

6. A este commit lo etiquetamos con v1.0 con el comando git tag -a v1.0 -m "version 1.0"

7. Despues de esto modificamos el gitignore y lo añadimos a este último commit con git amend.

8. Pot últmio hacemos el push y creamos la release desde el propio github