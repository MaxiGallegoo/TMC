 
# Taller de Matemática Computacional

Este repositorio corresponde al curso Taller de Matemática Computacional que se dicta en el primer año de la carrera Tecnicatura Universitaria en Desarrollo de Aplicaciones Informáticas (TUDAI).

**Tabla de contenidos:**
1. [Cómo clonar el repositorio](#cómo-clonar-el-repositorio)
2. [Trabajo Práctico Nº 1 - Lógica](#trabajo-práctico-nº-1---lógica)
    1. [Antes de empezar...](#antes-de-empezar)
    2. [Observar un objeto espacial](#observar-un-objeto-espacial)
    3. [Actuar sobre un objeto](#actuar-sobre-un-objeto)

3. [Actualizar el repositorio](#actualizar-el-repositorio)
    1. [En un equipo del laboratorio](#en-un-equipo-del-laboratorio)
    2. [En nuestra computadora](#en-nuestra-computadora)
4. [Trabajo Práctico Nº 2 - Conjuntos](#trabajo-práctico-nº-2---conjuntos)

5. [Trabajo Práctico Nº 3 - Funciones](#trabajo-práctico-nº-3---funciones)

6. [Trabajo Práctico Nº 4 - Conteo](#trabajo-práctico-nº-4---conteo)

6. [Trabajo Práctico Nº 4 - Probabilidad](#trabajo-práctico-nº-5---probabilidad)

## Cómo clonar el repositorio

Clonar un repositorio (o repo, como se le dice en la jerga) es algo que cualquier programador que se precie de tal debe saber hacer. Acá te vamos a enseñar cómo hacer para clonar este repositorio en particular, pero deberías poder hacer esto en cualquier otra materia que trabaje con Github.

1. Descargar e instalar [git](https://www.git-scm.com/downloads)
2. Abrir una linea de comandos e ir a la ubicación donde queremos guardar el repo: ``cd ~/Documents``
3. Clonar el repositorio: ``git clone https://github.com/Unicen/TMC.git``

## Trabajo Práctico Nº 1 - Lógica

El [enunciado](https://github.com/Unicen/TMC/blob/master/tp1-logica/enunciado.pdf) está [acá](https://github.com/Unicen/TMC/blob/master/tp1-logica/enunciado.pdf).

### Antes de empezar...

Para empezar hay que tener instalado [Python](https://www.python.org/downloads/). Asumiendo que ya está instalado y que ya tenemos clonado el repo de la materia:

1. Moverse hasta la ruta en la que está el repo clonado.
2. Entrar en la carpeta tp1-logica.
3. Ejecutar el comando ``python3 -i main.py`` escribiendo directamente en la consola. Si todo anduvo bien deberían ver algo así.

![alt text](https://raw.githubusercontent.com/Unicen/TMC/master/resources/tp1-init.png "python3 -i main.py")

### Observar un objeto espacial
1. Escribir ``objetoObservado = observar()`` en la consola y presionar Enter.
2. Como resultado una variable llamada ``objetoObservado`` tendrá el nombre de lo que hayamos visto en el espacio.

### Actuar sobre un objeto
1. **Importante!** Editar la función ``actuar`` antes de usarla para que haga lo que queremos :-)
2. Escribimos ``actuar(objetoObservado)`` en la consola. 

## Actualizar el repositorio

La actualización se realiza desde la linea de comandos (git cmd en Windows o terminal en Linux/OSX).

### En un equipo del laboratorio

1. Borrar la carpeta
``rd /s /q TMC`` 
2. Volver a [clonar](#cómo-clonar-el-repositorio)

### En nuestra computadora

1. Entrar a la carpeta TMC 
``cd TMC`` 
2. Decirle a git que traiga los cambios del servidor de origen
``git pull origin master``

## Trabajo Práctico Nº 2 - Conjuntos

El [enunciado](https://github.com/Unicen/TMC/blob/master/tp2-conjuntos/enunciado.pdf) está [acá](https://github.com/Unicen/TMC/blob/master/tp2-conjuntos/enunciado.pdf).

1. Abrir Git CMD.
2. Moverse hasta la ruta en la que está el repo clonado.
3. Actualizar el [repo](#actualizar-el-repositorio)
4. Entrar en la carpeta tp2-conjuntos.
5. Ejecutar el comando ``python3 -i main.py`` escribiendo directamente en la consola.


## Trabajo Práctico Nº 3 - Funciones

Realizar el [practico 3](https://github.com/Unicen/TMC/blob/master/tp3-funciones/enunciado.pdf) utilizando el sitio [desmos](https://www.desmos.com/calculator). 

## Trabajo Práctico Nº 4 - Conteo

Realizar el [practico 4](https://github.com/Unicen/TMC/blob/master/tp4-conteo/enunciado.pdf). 

## Trabajo Práctico Nº 5 - Probabilidad

Realizar el [practico 5](https://github.com/Unicen/TMC/blob/master/tp5-probabilidad/enunciado.pdf).