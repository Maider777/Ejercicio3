# QUE ES _GIT_?
_Git_, es una pieza de tecnologia diseñada para rastrear y registrar cambios y alteraciones en cualquier tipo de archivos de computadora, especialmente cuando se trata de esos archivos que son utlizados por mas de una o dos personas. _Git_, se utiliza para administrar el flujo de su trabajo y seguir el progreso de varios proyectos. Esta tecnologia se utiliza en ingenieria de software, aunque hay muchas empresas que utlizan Git aunque no tengan nada que ver con el software. _Git_ es bastante popular para desarrolladores y programadores, ademas de ser una herramienta esencial para las empresas que quieran administrar su flujo de trabajo.

![imagen](https://www.syloper.com/wp-content/uploads/git_destacada-1024x426.png)

## __COMANDOS__ QUE SE UTILIZAN EN _GIT_
+ _git_ help: Muestra una lista con los comandos mas utilizados en _git_.
+ _git_ init: Ejecutamos este comando para crear un repositorio con _git_ y asi utilizar todo el funcionamiento que _git_ nos ofrece.
+ _git_ branch: Es el comando que se usa para trabajar con la creacion de ramas, borrado de ramas y demas. Tambien, realizando este comando, _git_ nos dara el listado de ramas que tengamos en un proyecto, aunque hay que advertir que las ramas de un repositorio local pueden ser distintas a las ramas de un repositorio remoto.
+ _git_ merge: Este comando sirve para fusionar las ramas en las que estemos trabajando.
+ _git_ switch: Se utiliza para poder cambiar de rama cuando nosotros queramos hacerlo.
+ _git_ checkout -b nombredebranch: Sirve para moverse entre branches, en este caso vamos al branch que indicamos en el comando.
+ _git_ merge nombredebranch: Realiza un merge entre dos branches, en este caso la direccion del merge seria entre el branch que indiquemos en le comando, y el branch donde estemos ubicados.
+ _git_ status: Indica el estado del repositorio en el que estamos trabajando, es decir, nos muestra cuales estan modificados, cuales no son seguidos por _git_, y muchas otras caracteristicas mas.
+ _git_ clone url/nombreproyecto: clona un repositorio de _git_ en la carpeta nombreproyecto.
+ _git_ push: Despues de añadir, y de hacer commit, si estamos trabajando remotamente, este comando va a subir los archivos al repositorio remoto, tambien indicando la rama que indiquemos.
+ _git_ pull: Este comando se emplea para extraer y descargar contenido desde un repositorio remoto y actualizar al instante el repositorio local para mostrar ese contenido.
+ _git_ tag: Los tags o etiquetas permiten especificar puntos o commits especificos dentro de un repositorio que son considerados importantes. Para crear un tag, en el caso de querer generar un tag para el ultimo commit realizado en la rama, es necesario definir el nombre que tendra la etiqueta. Tambien es posible añadirle una descripcion.
+ _git_ fetch: Este comando se utiliza para descargar contenido y referencias de otro repositorio.
+ _git_ checkout: Con este comando puedes cambiar de rama o restaurar archivos del arbol de trabajo.
+ _git_ ignore: Se utiliza para ignorar uno o mas de archivos, especificando que tipo de archivo es el que queremos ignorar. Este comando se realiza cuando añadimos el comando _git init_, es decir, se añade al mismo nivel que añadimos _git init_.
+ _git_ add: Este comando lo que hace es añadir los archivos modificados o no modificados al repositorio _Git_ en el que estas trabajando. Otro comando para realizar la misma accion pero de manera diferente, seria hacer _git add ._; este comando hace lo mismo que el anterior, pero lo unico que cambia es que añadira todo lo que haya dentro del repositorio en el que estes trabajando.
+ _git_ commit: Este comando realiza un commit. Es decir, se utiliza _git commit -m "mensaje" + nombrearchivo_ para hacer commit a los archivos que indiquemos, y asi quedan guardados nuestras modificaciones. Otra manera de hacer commit utilizando otro comando, podria ser hacer _git commit -am "mensaje"_ para hacer commit de los archivos que han sido modificados y _git_ los esta siguiendo.
+ _git_ diff: Ejecutamos este comando para que _git_ nos muestre los cambios entre las confirmaciones realizadas y el arbol de trabajo. Tambien puede mostrarnos otros tipos de cambios entre dos arboles de trabajo, por ejemplo.
+ _git_ log: Este comando nos muestra todos los commits o todas las confirmaciones que hemos realizado anteriormente.
+ _git_ config: Al realizar este comando, lo que hacemos es poder decirle a _Git_ quien es el que esta realizando cualquier operacion en el repositorio que estamos trabajando. Es decir, despues de insertar este comando, debemos añadir nuestro email y nuestro nombre de usuario para que _Git_ sepa quien es la persona que esta realizando cambios en ese repositorio en el que estamos trabajando.

Esto es un ejemplo del comando _git status_:

![imagen](https://www.toolsqa.com/wp-content/gallery/git/thumbs/thumbs_git_status_new_file-1.png)

## QUE DIFERENCIA HAY ENTRE UN __REPOSITORIO NORMAL__ Y UN __REPOSITORIO DE TRABAJO__ DE GIT?
Un repositorio simple no contiene archivos de trabajo que se usen en _Git_. Sin embargo, un repositorio de trabajo contiene todos los archivos que se puedan utlizar por _Git_. 

## QUE DIFERENCIA HAY ENTRE UNA __BIFURCACION__ Y UNA __RAMA__?
En _Git_, una bifurcacion, es una copia de un repositorio que esta completamente separado del original. Una rama, sin embargo, se utiliza para cambiar algunas partes de un programa. 

Un ejemplo para ver la diferencia entre estas dos, podría ser:
En un automovil, por ejemplo, la bifurcacion seria manipular el exterior del automovil, y la rama seria cambiar los neumaticos.

## CUANDO REALIZO UNA CONFIRMACION, Y EL ARCHIVO YA ESTA EXPUESTO, ME DOY CUENTA DE QUE PODRIA HABER HECHO MAS CAMBIOS. PODRIA HACER ESOS CAMBIOS AUNQUE YA ESTUVIERA CONFIRMADO?
Si, y para realizar esta accion hay un comando llamado __git revert__. Lo que este comando realiza es que éste actua como un parche para la confirmacion que debe cambiarse. Entonces, cuando quieras volver al archivo para poder hacer esos cambios, podrás alterar y arreglar las cosas.

## QUE ES UN __CHERRY PICKING__?
Como termino, __cherry-picking__ es todo lo que se usa comunmente entre los desarrolladores. Este termino, ocurre cuando decides elegir algun tipo de confirmacion de una rama basada en _Git_ y luego aplicar sus caracteristicas a otra rama.

## QUE ES UN __STASH__?
El stash actua como una unidad de almacenamiento, el cual guarda tu proyecto y todas las caracteristicas. Esto, te permite regresar despues de un tiempo y continuar trabajando desde donde lo dejaste. Entonces, todo lo que estas trabajando lo puedes guardar dentro de un stash, sin tener miedo a perder cualquiera de tus trabajos.

## CUANDO APARECE UN __CONFLICTO__ EN _GIT_?
Si estas trabajando en una confirmacion y decides fusionarla, _Git_ verificara si existen cambios duplicados en la confirmacion que se esta llevando a cabo. En el caso de que se encuentren cambios duplicados, _Git_ emitira un conflicto. Esto ocurre cuando _Git_ no puede determinar cuales son los cambios correctos y cuales no. Este tipo de conflicto podria afectar a tu proyecto de manera negativa.

## ERRORES COMETIDOS EN _GIT_(PERSONALIZADO)
Un tipo de error, es el que cometi cuando quise nombrar un commit con un nombre especifico,ya que me equivoque y no lo nombre de la manera que yo queria. Entonces, busque en internet sobre como cambiar el nombre del *commit*, y entonces realize el comando _git commit --amend_, y fue cuando pude cambiar el nombre al commit que realize.

Otro tipo de error que cometi, fue el que no podia editar un archivo desde _Git lab_. Este problema me resulto dificil de comprender, y el problema fue que no podia editarlo ya que en _Git lab_ no estaba trabajando en ninguna rama. Fue por eso que no me dejaba editar el archivo que yo queria.

_Git lab_:

![imagen](https://blog.desafiolatam.com/wp-content/uploads/2017/10/gitlab-cover.png)


