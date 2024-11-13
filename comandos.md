## Ejercicio 3

### Paso 1

Crear un repositorio nuevo con el nombre libro y mostrar su contenido. Comprueba el estado del respositorio.

Primero al no tener vinculado el repositorio con GitHub
(Dentro de la carpeta ""libro")

    git config user.name "sergiofr13"
    git config user.email "sergio.ferreiro.ramos@gmail.com"

(Dentro de la carpeta creada "libro")

    git init

Para mostrar contenido:

    ls

Comprobar estado

    git status


### Paso 2

Crear un fichero indice.txt con el siguiente contenido:

    touch indice.txt
    nano indice.txt

(Agregamos el contenido)


### Paso 3

Realizar un commit con el mensaje “Añadido índice del libro”.

    git status

    git add comandos.md
    git add indice.txt

    git commit -m "Añadido indice del libro"



### Paso 4

Comprueba y explica el estado del repositorio.


    git status

Ahora al haber hecho el commit, no hay cambios nuevos.