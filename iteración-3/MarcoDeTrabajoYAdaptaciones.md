# Marco de trabajo y adaptaciones al contexto del proyecto

Se decidió utilizar SCRUM como marco de trabajo ágil para este proyecto sobre la aplicación de pencas deportivas. Esto implica buscar aplicar los principios del manifiesto ágil para cada decisión que se tenga que tomar. En particular se trabajará en iteraciones y entregas incrementales, promoviendo la colaboración la flexibilidad frente al cambio y las situaciones que puedan surgir, buscando la mejora continua, con un equipo que se autoorganiza para lograrlo.

Se utilizarán los roles, eventos, y artefactos que el marco SCRUM define, con adaptaciones a la realidad del equipo y contexto del proyecto, a saber:

- **Roles**: Product Owner, Scrum Master, Development team.
- **Eventos**: Daily Scrum, Sprint Planning, Sprint Review, Sprint Retrospective.
- **Artefactos**: Product Backlog, Sprint Backlog, Increment.

## Definiciones y Políticas de trabajo del equipo

### Proceso de Ingeniería de Requerimientos Ágil

Se utilizará la práctica **Card - Conversation - Confirmation** para poder construir las UserStories en reuniones de Grooming que se realizarán con el Product Owner, y con el input del relevamiento de aplicaciones y feedback de usuarios de pencas.

[Feedback inicial de usuarios de pencas](AnalisisInicial.md)

En la etapa **Card** se busca crear tarjetas con la historia de usuario. Esta tarjeta contiene una breve descripción de la historia escrita en un lenguaje sencillo y accesible. La tarjeta no necesita tener todos los detalles, sino que debe proporcionar suficiente información para iniciar una conversación.

La **Conversation** es la discusión que se lleva a cabo entre el Product Owner, los desarrolladores y otros interesados para profundizar en los detalles de la historia de usuario. Esta conversación es esencial para aclarar requisitos, discutir posibles soluciones y abordar cualquier pregunta o duda que el equipo pueda tener. Durante la conversación, se exploran los criterios de aceptación, se identifican posibles impedimentos y se define cómo se implementará la historia. La conversación asegura que todos los involucrados tengan un entendimiento común de lo que se necesita.

La **Confirmation** se refiere a que luego de la Conversation se escriben los criterios de aceptación que definen cuándo una historia de usuario se considera completada y satisfactoria. Estos criterios son especificaciones claras y medibles que permiten al equipo verificar que la historia ha sido implementada correctamente y cumple con los requisitos del Product Owner. Los criterios de aceptación proporcionan una base para las pruebas de aceptación y ayudan a asegurar la calidad del producto.

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
- Tener criterios de aceptación definidos y verificables
- Estar priorizadas. Dicha priorización se realizará en general según el valor que aporte dicha UserStory (según lo manifieste el Product Owner), pero también teniendo en cuenta los criterios técnicos (como por ejemplo la factibilidad de poder ser incluidas dentro de los releases que se planifiquen) dados por el Equipo de Desarrollo. 

### Definition of Done

los elementos del Backlog completados durante el Sprint deben cumplir con los criterios de aceptación definidos, estar probados y listos para su entrega.