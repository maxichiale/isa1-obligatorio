# Marco de trabajo y adaptaciones al contexto del proyecto

## Definiciones y Políticas de trabajo del equipo

Se decidió utilizar SCRUM como marco de trabajo ágil para este proyecto sobre la aplicación de pencas deportivas. Esto implica buscar aplicar los principios del manifiesto ágil para cada decisión que se tenga que tomar. En particular se trabajará en iteraciones y entregas incrementales, promoviendo la colaboración la flexibilidad frente al cambio y las situaciones que puedan surgir, buscando la mejora continua, con un equipo que se autoorganiza para lograrlo.

Se utilizarán los roles, eventos, y artefactos que el marco SCRUM define, con adaptaciones a la realidad del equipo y contexto del proyecto, a saber:

- **Roles**: Product Owner, Scrum Master, Development team.
- **Eventos**: Daily Scrum, Sprint Planning, Sprint Review, Sprint Retrospective.
- **Artefactos**: Product Backlog, Sprint Backlog, Increment.

Se incluye mas detalles sobre esto en la sección de [roles y responsabilidades](RolesYResponsabilidades.md)



## Proceso de Ingeniería de Requerimientos Ágil

Como input para esta parte del proceso se toman los resultados del trabajo de [relevamiento de aplicaciones, y feedback de usuarios de pencas](AnalisisInicial.md).

Se utilizará la práctica **Card - Conversation - Confirmation** para poder construir las UserStories en reuniones de Grooming que se realizarán con el Product Owner, y con el input mencionado anteriormente.

En la etapa **Card** se busca crear tarjetas con la historia de usuario. Esta tarjeta contiene una breve descripción de la historia escrita en un lenguaje sencillo y accesible. La tarjeta no necesita tener todos los detalles, sino que debe proporcionar suficiente información para iniciar una conversación.
En el proyecto, en esta etapa se crea la tarjeta asignandole un título, y una narrativa basica escrita en el formato **Como Quiero Para**. En esta estapa se trabaja sobre la independencia de la tarjeta, y se discute sobre el valor que representa.

La **Conversation** es la discusión que se lleva a cabo entre el Product Owner, los desarrolladores y otros interesados para profundizar en los detalles de la historia de usuario. Esta conversación es esencial para aclarar requisitos, discutir posibles soluciones y abordar cualquier pregunta o duda que el equipo pueda tener. Durante la conversación, se exploran los criterios de aceptación, se identifican posibles impedimentos y se define cómo se implementará la historia. La conversación asegura que todos los involucrados tengan un entendimiento común de lo que se necesita.
En el proyecto se identifican los escenarios, y se empiezan a escribir bocetos de especificación de los criterios de aceptación. En esta etapa se trata de acotar el tamaño y determinar las condiciones que deba cumplir para ser verificable.

La **Confirmation** se refiere a que luego de la Conversation se escriben los criterios de aceptación que definen cuándo una historia de usuario se considera completada y satisfactoria. Estos criterios son especificaciones claras y medibles que permiten al equipo verificar que la historia ha sido implementada correctamente y cumple con los requisitos del Product Owner. Los criterios de aceptación proporcionan una base para las pruebas de aceptación y ayudan a asegurar la calidad del producto.
En el proyecto se escriben los criterios de aceptación, escritos en BDD con **Dado Cuando Y Entonces**. Al realizar esto la UserStory queda lista para poder ser estimada.

### User stories

### Definition of Ready

Las User Story deben cumplir con lo siguiente, antes de ser seleccionados para su inclusión en el Sprint:
- Ser claras y completas siguiendo los criterios INVEST, a saber:
    - **Independent (Independiente)**:  Las historias de usuario deben ser independientes unas de otras para evitar dependencias. Esto permite que puedan ser movidas, priorizadas y desarrolladas sin estar atadas a otras historias. La independencia también facilita una mejor flexibilidad y mejora la planificación.
    - **Negotiable (Negociable)**: Las historias de usuario no deben ser vistas como un contrato detallado, sino más bien como un punto de partida para una conversación. Deben proporcionar suficiente detalle para que el equipo entienda la intención, pero dejar espacio para la discusión y negociación sobre cómo implementarlas.
    - **Valuable (Valiosa)**: Cada historia de usuario debe entregar valor al cliente o usuario. Esto asegura que el equipo siempre esté trabajando en tareas que contribuyen directamente al objetivo general del producto y a la satisfacción del usuario.
    - **Estimable (Estimable)**: Una historia de usuario debe ser lo suficientemente clara para que el equipo de desarrollo pueda estimar el esfuerzo requerido para completarla. Esto generalmente implica entender el alcance y la complejidad de la historia. Si una historia es demasiado vaga, puede necesitar dividirse en partes más pequeñas y comprensibles.
    - **Small (Pequeña)**: Las historias de usuario deben ser lo suficientemente pequeñas para ser completadas dentro de un solo sprint. Las historias más pequeñas son más fáciles de estimar, gestionar y probar. También proporcionan retroalimentación más frecuente y permiten iteraciones más rápidas.
    - **Testable (Verificable)**: Una historia de usuario debe tener criterios de aceptación claros que hagan posible probar si la historia ha sido implementada con éxito. Si una historia no es verificable, probablemente sea demasiado vaga o amplia y necesite ser refinada.
- Tener criterios de aceptación definidos, especificados como escenarios y escritos en BDD (lenguaje Gherkin) y verificables
- Estar priorizadas. Dicha priorización se realizará en general según el valor que aporte dicha UserStory (según lo manifieste el Product Owner), pero también teniendo en cuenta los criterios técnicos (como por ejemplo la factibilidad de poder ser incluidas dentro de los releases que se planifiquen) dados por el Equipo de Desarrollo. 

En el marco del proyecto las UserStory estarán especificadas bajo estos lineamientos en la herramienta [Azure DevOps](https://dev.azure.com/) con criterios de aceptación escritos en BDD. Las mismas se agruparán en Epicas indicando las funcionalidades de alto nivel que tendrá la aplicación.

### Definition of Done

Los elementos del Backlog completados durante el Sprint deben cumplir con los criterios de aceptación especificados, con las pruebas realizadas en forma exitosa (es decir llegando al resultado esperado segñun lo especificado). También debe estar en condición de ser liberado a los usuarios finales (listo para instalar o hacer deploy).

## Repositorio

Utilizaremos Github como repositorio donde centralizaremos el código.

El mismo fué creado como un repositorio público y pertenece a la organización [ORT-IngSoft-ISA1-2023-2](https://github.com/IngSoft-ISA1-2023-2).

Puede acceder al mismo en este [link](https://github.com/IngSoft-ISA1-2023-2/isa1-n6a-id-mini-proyecto-agil-isa-n6a-id-mini-proyecto-agil-equipo2).


### Estrategia de ramas

Ya que el desarrollo se realizará sobre la herramienta OnLine [Framer](https://www.framer.com/) para generar prototipos, no podemos seguir una estrategia de tipo **Feature branching**, pero se resolvió generar una rama para cada Iteración, que al final de cada iteración se integrarán en **develop**, y en **main**.

Tendremos a **main** como rama principal con el código productivo.

La rama **develop** sera la rama que consolida todos los cambios, pervio a pasarlos a main.

Como excepción a lo anterior, se permitirá realizar tareas de documentación directamente en la rama develop, si el desarrollador lo prefiere.

Se incluye la siguiente imagen para ilustrar la metodología de trabajo descrita anteriormente:

![gitflow simplified](img/proceso/gitflow-branching-model-adapted.png)



### Comandos Git a utilizar:

1. `git --version`
    Muestra la version de Git que estamos corriendo localmente.

2. `git config –global user.name <name>`
    Permite setear el nombre de usuario de Git a utilizar globalmente en el equipo cliente.

3. `git config –global user.email <email>`
    Permite setear el email de usuario Git a utilizar globalmente en el equipo cliente.

4. `git init`
	Permite crear un nuevo repositorio en la ubicacion local actual.

5. `git remote add <remote_name> <url>`
    Enlaza el nombre como un alias a la url del repositorio remoto.

6. `git branch {-v, -a, -d, -r, -m} <branch_name>`
	Es utilizado para administrar ramas. 
    * Si no se incluyen parametros, lista ramas locales, e indica cual es la rama actual.
    * Si solo se da un nombre de rama, crea una nueva rama local con el nombre indicado.
    * `-d` elimina la rama con el nombre indicado (debe ser distinta a la actual).
    * `-m <old_name> <new_name>` para renombrar ramas.
    * `-r` abarca las ramas remotas al operar (ej. al listar o borrar).
    * `-a` abarca todas las ramas remotas o locales (ej. al listar o borrar).
    * `-v` muestra no solo el nombre sino parte del hash del ultimo commit y el mensaje del mismo

7. `git push {-u} <remote_name> <branch_name>`
    Envia al repositorio remoto indicado por el nombre, los cambios que estan en el repositorio local. Si no se indica un repositorio remoto se envia al que este seteado por defecto, pero se puede indicar un repositorio remoto diferente indicando el nombre. Tambien se puede indicar la rama desde la que se quieren enviar los cambios, si no son los de la rama actual.
    * `-u` establece el enlace entre un repositorio remoto y la rama local para que luego no sea necesario incluir dicho parametro y se puedan subir los cambios con un simple git push.

8. `git fetch <remote_name>`
    Se descarga informacion actualizada de las ramas remotas. No aplica cambios a las ramas locales.

9. `git status`
    Como primer dato nos indica con que rama esta enlazado nuestro directorio de trabajo. Nos indica cual es la situacion actual del arbol del directorio de trabajo, incluyendo archivos nuevos sin trackear, archivos borrados, modificados, cambios en el arbol de staging. Toda la informacion apunta a indicarnos los cambios que no tenemos commiteados en el repositorio local.

10. `git clone {-b <branch_name>} <url>`
	Es utilizado para crear una copia de un repositorio remoto previamente creado en la ubicacion actual de la máquina en la que se está trabajando. 
    * `-b <branch_name>` Para clonar una rama especifica, antes de la dirección del repositorio.

11. `git checkout {-b} <branch_name>`
	Se cambia el arbol de trabajo local al correspondiente de la rama que se indica. 
    * `-b` Se crea la rama indicada por el nombre proporcionado y luego se cambia el directorio de trabajo al arbol de la misma. Lo que se haga en adelante afectara a esa rama.

12. `git add {-A, <path>}`
	Pasa las modificaciones realzadas en el arbol de trabajo al arbol de staging.
    * `<path>` Se puede incluir el directorio local ".", directorios o archivos.
    * `-A` Actualiza todo el arbol de staging para que refleje los cambios en el arbol del directorio de trabajo (archivos y directorios).

13. `git commit {-m "<message>"}`
	Guarda en el repositorio los cambios que estan en el area de staging.
    * `-m "<message>"` Incluye el mensaje indicado para que quede asociado al commit, junto con los datos que guarda por defecto, relacionado a la fecha-hora y contenido de los cambios y el usuario que los realizo.
    * `-a` Add and commit all together.
    * `--amend --no-edit` Ammend. Permite agregar cambios al ultimo commit ya realizado sin modificar el mensaje.

14. `git pull`
	Baja los cambios hechos en el repositorio remoto y actualiza los arboles de staging y del directorio de trabajo local.

15. `git push`
	Sube los cambios realizados en el repositorio local que no se hayan subido al repositorio remoto.

16. `git merge <branch_name>`
	Se crea un commit que incorpora los cambios de la rama mencionada, en la rama actual. Si se modificaron los mismos elementos desde que se dividieron las ramas ocurriran conflictos que deberan ser resueltos.

17. `git log`
    Muestra el registro interno de los cambios realizados (commits), ordenados del mas reciente al mas antiguo. Se incluye por defecto informacion del usuario que realizo cada commit, la fecha-hora, y el mensaje asociado.
    * `--oneline` Shows the commit in one line (commitid, 1st line of message, branch name).
    * `--graph` It shows the branch graph.

18. `git diff {<commit1> <commit2>, <branch1> <branch2>, <tag1> <tag2>}`
    Permite comparar conjunto de cambios.
    - `<commit1> <commit2>` Entre dos commits
    - `<branch1> <branch2>` Entre dos ramas
    - `<tag1> <tag2>` Entre dos tags

19. `git stash {push, -u, -m "name" | pop | apply, {stash@<id>}}`
	Guarda temporalmente los cambios realizados en el arbol del directorio de trabajo local (y opcionalemnte tambien los que estan en staging) como una entrada en una estructura de pila, colocando ese registro encima de la pila. Esto vuelve el directorio de trabajo (y opcionalemente el area de staging) a estar sincronizado con el de staging, y opcionalmente tambien con el repositorio, para realizar otras actividades. Luego se pueden volver a aplicar los cambios guardados restaurando el arbol del directorio de trabajo local (y opcionalmente el area de staging tambien) con dichos cambios.
    * `push` Con este parametro permite agregar una entrada en la pila del stash con cambios.
        - `-u` Se incluyen los archivos nuevos que aun no estan traqueados por la herramienta.
        - `-m "message"` Se le incluye opcionalmente un mensaje asociado para facilitar recordar que cambios incluye.
    * `pop` Con este parametro se quita del tope de la pila el ultimo conjunto de cambios y se aplican al directorio de trabajo local y el area de staging si se guardo de esa forma.
    * `apply {stash@<id>}` Se aplican los cambios del registro en el tope de la pila de la misma manera que con el pop, pero no se quita de la pila.
        - `stash@<id>` Se puede incluir un nombre con el identificador dentro de los registros en la pila para seleccionar un registro especifico dentro de la pila.
    * `list` Muestra los stashes guardados

20. `git rebase <branch_name>`
    Se mueve el punto de division de la rama, hacia al final de la rama de la que se da el nombre, y se cuelgan a partir de alli los commits de la rama particular que no son parte de la rama origen. Si se modificaron los mismos elementos desde el punto de division inicial en ambas ramas ocurriran conflictos, que deberan resolverse.

21. `git restore {--staged} <filename or .>` 
    Restaura el arbol del directorio de trabajo actual.
    * `--staged` Restaura el arbol de staging, quitando el cambio que se agrego a staging con git add, por lo que el cambio queda nuevamente solo en el arbol de trabajo local.

22. `git reset {--soft, --hard} <hashid>`
    Cuando se ejecuta sin parametros opcionales, vuelve el repositorio a la situacion de ese commit, y los cambios del mismo quedan en el directorio de trabajo local, pero no en el arbol de staging.
    - `--soft` ademas, los cambios quedan tambien en el arbol de staging y no solo en el directorio de trabajo local.
    - `--hard` los cambios de ese commit se vuelven atras en los 3 arboles (repositorio, staging, y en el directorio de trabajo local).

22. `git revert <commit>`
    Revierte los cambios realizados en un commit específico.

23. `git tag {-a, -e, -m, -f, -l, -d} <tagName>`
    Permite agregar una etiqueta a un conjunto de cambios para que el mismo quede asociado a una "foto" del estado de todos los archivos, de forma de volver todos los archivos a ese estado en el futuro.
    - `-a` Hace un tag anotado.
    - `-m` Permite incluir un mensaje asociado.
    - `-e` Permite editar el mensaje.
    - `-f` Reemplaza un tag con el nombre que se indica.
    - `-l` Lista los tags.
    - `-d` Elimina el tag con el nombre indicado.
    

### Versionado

En general se pretende seguir las recomendaciones principales indicadas por [Semantic Versioning](https://semver.org/)

Pero para el proyecto particular para el que se trabajará sobre prototipos no se manejará una numeración de versiones ya que simplemente se hará merge a **main** al final de cada iteración
