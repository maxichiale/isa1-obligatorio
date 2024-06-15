# Marco de trabajo y adaptaciones al contexto del proyecto

## Definiciones y Políticas de trabajo del equipo

Se decidió utilizar SCRUM como marco de trabajo ágil para este proyecto sobre la aplicación de pencas deportivas. Esto implica buscar aplicar los principios del manifiesto ágil para cada decisión que se tenga que tomar. En particular se trabajará en iteraciones y entregas incrementales, promoviendo la colaboración la flexibilidad frente al cambio y las situaciones que puedan surgir, buscando la mejora continua, con un equipo que se autoorganiza para lograrlo.

Se utilizarán los roles, eventos, y artefactos que el marco SCRUM define, con adaptaciones a la realidad del equipo y contexto del proyecto, a saber:

- **Roles**: Product Owner, Scrum Master, Development team.
- **Eventos**: Daily Scrum, Sprint Planning, Sprint Review, Sprint Retrospective.
- **Artefactos**: Product Backlog, Sprint Backlog, Increment.

Se incluye mas detalles sobre esto en la sección de [roles y responsabilidades](RolesYResponsabilidades.md)


Este proyecto entonces cubre solamente lo que sería el Ciclo de Discovery en lo que seria **Dual Track SCRUM** de un proyecto completo produciendo como resultado un prototipo con User Stories validadas por usuarios. Por lo que aplicamos SCRUM a este ciclo, simulando que el Ciclo de Discovery es el Ciclo de Delivery, y esto implica que tenemos que traducir los elementos de uno a otro. Por ejemplo:
  - Cuando hablamos de producto e incrementos, en vez de estar entregando un producto funcional listo para ser usado por los usuarios, los incrementos son prototipos de funcionalidades que son una aproximación a lo que seria el producto final.
  - El backlog de ideas propias y surgidas del relevamiento con usuarios, será nuestro Product backlog
  - Los incrementos serán validados por el Prodct Owner y algunos usuarios que propusieron ideas, en lugar de que usuarios reales utilicen un produco real.
  - El equipo de desarrollo en lugar de estar codificando estará diseñando los prototipos como si fueran diseñadores.

Para mayor referencia se incluye el siguiente diagrama

![dual track scrum](img/dual-track-scrum.png)

### Sprints

Se redujo de 4 a 2 semanas la duración de los Sprints debido al calendario propuesto por letra (requerimiento), y también para poder tener mayor cantidad de Sprints, y por ende, más feedback para hacer ajustes. También utilizamos un sprint "0" o inicial dedicado a realizar tareas de Discovery de ideas, relevamiento, y arquitectura del producto a desarrollar. Esto se hizo asi porque no teniamos claro un alcance concreto dado, sino que debiamos determinarlo en base a posibles usuarios del producto.

### Planificación y Release

Si bien en cada Sprint posterior al inicial se hicieron avances en el producto, solo se relaizó un release al final, por lo que dado que había funcionalidades bastante fijas dadas por letra, y una fecha final fija por calendario ORT, la planificación realizada fué mas bien **Date Driven**, priorizando las épicas solicitadas por letra para cumplir el mínimo requerido y luego las que aportaran mayor valor a los usuarios, dejando otras por el camino que no se llegaron a implementar.

### Roles multifunción

En nuestro caso, los roles de Product Owner y Scrum Master, también participan del desarrollo, aunque en menor medida. Por esto también se da la particularidad de que el Product Owner esta presente en todas las ceremonias, inclusive en las Daily Scrum lo que permite un feedback mas temprano, y si es necesario tomar decisiones de priorización poder hacerlo en ese mismo momento.

### Distribución de la carga de trabajo

Se estableció una carga de trabajo, no constante a lo largo del proyecto, porque al hacer la planificación inicial el equipo identificó que no se iba a poder contar con una capacidad constante en el tiempo dado que hay entregas y otros eventos externos que afectan la disponibilidad de tiempo de los integrantes del equipo. En base a eso se definió planificar una capacidad mayor en las etapas iniciales, para luego ir descendiendo la misma en las etapas finales, de forma de poder mantener un promedio que nos permita cumplir los objetivos. El mismo principio se utilizó al planificar los Sprints, en base a los objetivos del mismo, establecimos prioridades semanales claras para asegurar la finalización de tareas críticas, de manera que no nos quede mucha carga de trabajo acumulada para el final del Sprint.

### Virtualizacion de eventos

Dada la dispersión de los integrantes del equipo, y la dificultad de coincidir en un mismo lugar se decidió que todas las ceremonias de SCRUM se realizarán en forma virtual, salvo algunas revisiones con stakeholders puntuales.

### Virtualizacion de artefactos de comunicación

Dado la misma imposibilidad de tener reunido el equipo físicamente en un lugar como para tener espacios colaborativos e irradiadores de información físicos, utilizamos Azure DevOps para la gestión visual de algunos artefactos como ser el Product Backlog, Sprint Backlog, Burndown y Velocity charts, y Taskboards. De esta manera mejoramos la comunicación y colaboración del equipo, priorizando y gestionando mejor las tareas asignadas. 

  También utilizamos Framer para la gestión del entregable, lo que facilita el acceso simultaneo para poder trabajar en la elaboración del mismo.

  Otras herramientas como MetroRetro, Planning Poker entre otras, se utilizaron como irradiadores de información que facilitan la comunicación con el equipo.

  Además se incorporó un grupo de Whatsapp para poder agilizar la comunicación y estar en permanente contacto y por ejemplo resolver dudas, plantear dificulades, ajustar prioridades, reportar avances, etc.

### Frecuencia de Daily Scrums

Debido a la disponibilidad horaria de los integrantes del grupo, las Daily Scrums no son realizadas todos los días, en vez de ello, se hacen 3 veces a la semana, y se acepta que puedan tener hasta 30 minutos de duracion.


### Duracion de Citas para ceremonias Scrum

Las citas fueron considerablemente mas larga que lo propuesto por SCRUM ya que por ejemplo se anexó tiempo para trabajo en conjunto luego de los 15 minutos aprox de duracion de la daily, algo similar con las demas. Esto para facilitar tareas de coordinacion entre las tareas que vienen realizando distintos integrantes que tienen cierta relación, solucionar bloqueos o dudas que algun miembro del equipo haya manifestado en la daily o la ceremonia que se haya realizao, o hacer cualquier ajuste que ayude a lograr el objetivo del Sprint.

### "Pair Programming"

Se hizo bastante uso de esta técnica dado que no teníamos mucho tiempo para hacer verificaciones, y ciclos de prueba y correcciones, precisábamos que lo que se entregara tuviera la mejor calidad posible y fuera correcto. Cuando un integrante del equipo tenía una tarea compleja, solicitaba al Scrum Master apoyo y este buscaba quien podría ayudar o el mismo lo hacía, para resolver el tema de manera conjunta. Esto es algo que no propone SCRUM pero que al equipo la resultó bueno agregar a las tareas que el Scrum Master y equipo de desarrollo normalmente si hace comom parte de SCRUM de ayudar a desbloquear las tareas que no logran avanzar.

### Reviews

Dado que no se tenía un producto utilizable en forma autónoma por los usuarios, se hicieron sesiones de demostración con usuarios, sobre las que se pidió feedback mediante cuestionarios.
También se hicieron videos demostrativos de cada funcionalidad entregada, para utilizar cuando no se podía agendar un encuentro.
Además en las Sprint Reviews se analizo todo este material junto con la revisión del propio Product Owner.


### Proceso de Ingeniería de Requerimientos Ágil

Como input para esta parte del proceso se toman los resultados del trabajo de [relevamiento de aplicaciones, y feedback de usuarios de pencas](AnalisisInicial.md).

Se utilizará la práctica **Card - Conversation - Confirmation** para poder construir las UserStories en reuniones de Grooming que se realizarán con el Product Owner, y con el input mencionado anteriormente.

En la etapa **Card** se busca crear tarjetas con la historia de usuario. Esta tarjeta contiene una breve descripción de la historia escrita en un lenguaje sencillo y accesible. La tarjeta no necesita tener todos los detalles, sino que debe proporcionar suficiente información para iniciar una conversación.
En el proyecto, en esta etapa se crea la tarjeta asignandole un título, y una narrativa basica escrita en el formato **Como Quiero Para**. En esta estapa se trabaja sobre la independencia de la tarjeta, y se discute sobre el valor que representa.

La **Conversation** es la discusión que se lleva a cabo entre el Product Owner, los desarrolladores y otros interesados para profundizar en los detalles de la historia de usuario. Esta conversación es esencial para aclarar requisitos, discutir posibles soluciones y abordar cualquier pregunta o duda que el equipo pueda tener. Durante la conversación, se exploran los criterios de aceptación, se identifican posibles impedimentos y se define cómo se implementará la historia. La conversación asegura que todos los involucrados tengan un entendimiento común de lo que se necesita.
En el proyecto se identifican los escenarios, y se empiezan a escribir bocetos de especificación de los criterios de aceptación. En esta etapa se trata de acotar el tamaño y determinar las condiciones que deba cumplir para ser verificable.

La **Confirmation** se refiere a que luego de la Conversation se escriben los criterios de aceptación que definen cuándo una historia de usuario se considera completada y satisfactoria. Estos criterios son especificaciones claras y medibles que permiten al equipo verificar que la historia ha sido implementada correctamente y cumple con los requisitos del Product Owner. Los criterios de aceptación proporcionan una base para las pruebas de aceptación y ayudan a asegurar la calidad del producto.
En el proyecto se escriben los criterios de aceptación, escritos en BDD con **Dado Cuando Y Entonces**. Al realizar esto la UserStory queda lista para poder ser estimada.

### User stories

#### Definition of Ready

Las User Story deben cumplir con lo siguiente, antes de ser seleccionados para su inclusión en el Sprint:
- Ser claras y completas siguiendo los criterios INVEST, a saber:
    - **Independent (Independiente)**:  Las historias de usuario deben ser independientes unas de otras para evitar dependencias. Esto permite que puedan ser movidas, priorizadas y desarrolladas sin estar atadas a otras historias. La independencia también facilita una mejor flexibilidad y mejora la planificación.
    - **Negotiable (Negociable)**: Las historias de usuario no deben ser vistas como un contrato detallado, sino más bien como un punto de partida para una conversación. Deben proporcionar suficiente detalle para que el equipo entienda la intención, pero dejar espacio para la discusión y negociación sobre cómo implementarlas.
    - **Valuable (Valiosa)**: Cada historia de usuario debe entregar valor al cliente o usuario. Esto asegura que el equipo siempre esté trabajando en tareas que contribuyen directamente al objetivo general del producto y a la satisfacción del usuario.
    - **Estimable (Estimable)**: Una historia de usuario debe ser lo suficientemente clara para que el equipo de desarrollo pueda estimar el esfuerzo requerido para completarla. Esto generalmente implica entender el alcance y la complejidad de la historia. Si una historia es demasiado vaga, puede necesitar dividirse en partes más pequeñas y comprensibles.
    - **Small (Pequeña)**: Las historias de usuario deben ser lo suficientemente pequeñas para ser completadas dentro de un solo sprint. Las historias más pequeñas son más fáciles de estimar, gestionar y probar. También proporcionan retroalimentación más frecuente y permiten iteraciones más rápidas.
    - **Testable (Verificable)**: Una historia de usuario debe tener criterios de aceptación claros que hagan posible probar si la historia ha sido implementada con éxito. Si una historia no es verificable, probablemente sea demasiado vaga o amplia y necesite ser refinada.
- Tener criterios de aceptación bien definidos y verificables
- Estar priorizadas. Dicha priorización se realizará en general según el valor que aporte dicha UserStory (según lo manifieste el Product Owner), pero también teniendo en cuenta los criterios técnicos (como por ejemplo la factibilidad de poder ser incluidas dentro de los releases que se planifiquen) dados por el Equipo de Desarrollo. 

En el marco del proyecto las UserStory estarán especificadas bajo estos lineamientos en la herramienta [Azure DevOps](https://dev.azure.com/GC109606/ISA1-Equipo2-Pencas) con criterios de aceptación escritos en **BDD**, especificados como escenarios en lenguaje Gherkin. Las mismas se agruparán en Epicas indicando las funcionalidades de alto nivel que tendrá la aplicación.

#### Definition of Done

Establece las condiciones que deben cumplirse para determinar si un elemento de trabajo (historia de usuario, tarea, funcionalidad, entre otros) está completamente terminado y listo para ser entregado.
Los elementos del Backlog completados durante el Sprint deben cumplir con los criterios de aceptación especificados, con las pruebas realizadas en forma exitosa (es decir llegando al resultado esperado según lo especificado). También debe estar en condición de ser liberado a los usuarios finales (listo para instalar o hacer deploy).

## Repositorio

Utilizaremos Github como repositorio donde centralizaremos el código.

El mismo fué creado como un repositorio público y pertenece a la organización [ORT-IngSoft-ISA1-2023-2](https://github.com/IngSoft-ISA1-2023-2).

Puede acceder al mismo en este [link](https://github.com/IngSoft-ISA1-2023-2/isa1-n6a-id-mini-proyecto-agil-isa-n6a-id-mini-proyecto-agil-equipo2).


### Estrategia de ramas

Ya que el desarrollo se realizará sobre la herramienta OnLine [Framer](https://www.framer.com/) para generar prototipos, no podemos seguir una estrategia de tipo **Feature branching**, pero se resolvió generar una rama para cada Iteración, que al final de cada iteración se integrarán en **develop**, y en **main**.

Tendremos a **main** como rama principal con el código productivo.

La rama **develop** sera la rama que consolida todos los cambios, pervio a pasarlos a main.

Como excepción a lo anterior, se permitirá realizar tareas de documentación directamente en la rama develop, si el desarrollador lo prefiere.

Cada vez que se vaya a realizar merge de una rama de Iteracion a Develop y de Develop a Main se realizara mediante la cración de un **Pull Request**, de forma de poder visualizar los cambios y evitar que se integren cambios no deseados. Al confirmar el Pull Request y confirmar la integración a la branch original, se deben eliminar la branch en la que se estuvo trabajando.

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
