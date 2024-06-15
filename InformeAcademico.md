# Informe académico

**Resultados y Lecciones Aprendidas en la Aplicación de Prácticas de Ingeniería de Software Ágil en el Prototipado de una Aplicación de Pencas Deportivas**

### Resumen

Este informe detalla los resultados y lecciones aprendidas a lo largo de la implementación de prácticas de ingeniería de software ágil, específicamente utilizando el marco de trabajo SCRUM, en el desarrollo de un prototipo de MVP para una aplicación de pencas deportivas. Se destacan las adaptaciones al marco de trabajo SCRUM debido a las particularidades del proyecto, las acciones de mejora aplicadas y sus impactos en el rendimiento y satisfacción del equipo.

## Resultados del proyecto

### 1. Introducción
Dado el contexto particular de nuestro proyecto y la disponibilidad de dedicación al mismo que tenía cada integrante, a lo largo del proceso, se realizaron diversas adaptaciones de roles, eventos y artefactos, y también acciones de mejora para optimizar el rendimiento y la satisfacción del equipo. 
Sin duda, aprendimos cómo debería funcionar SCRUM a través de un proceso que se asemeja mucho a la realidad. Aunque hicimos adaptaciones propias para el contexto de este proyecto, que no se alineaban al 100% con la guía de SCRUM, entendemos que es algo común en la práctica. Esto se basa en la experiencia de algunos de nosotros que trabajamos con SCRUM en el ámbito laboral, donde siempre se realizan ajustes, ya sea en la forma de realizar las reuniones, en las prioridades, en las métricas, etc.

### 2. Contexto del Proyecto
- Objetivo del Proyecto: descubrir, idear y prototipar un de MVP para una aplicación de pencas deportivas.
- Equipo: un Product Owner, un Scrum Master y un equipo de desarrollo.
- Duración y Esfuerzo: el proyecto se ejecutó en 4 iteraciones de dos semanas cada una, con un esfuerzo mínimo de 5 horas-persona por semana.
- Público Objetivo del MVP: Personas de entre 14 y 70 años interesadas en participar en pencas deportivas.

### 3. Inspección y Adaptación del Proceso
Cada iteración incluyó los siguientes mecanismos de inspección y adaptación:
- **Retrospectivas**: Al final de cada iteración, realizamos retrospectivas para identificar lo que funcionó, lo que debía mejorarse y lo que debíamos seguir haciendo. Esto nos permitió obtener feedback directo del equipo y ajustar nuestras prácticas de inmediato.
- **Feedback Continuo**: Por parte de los miembros del equipo durante las ceremonias, o en cualquier otra comunicación informal.

  Los resultados se discutieron y se tomaron acciones a partir de ellos, ya sea para la mejora del proceso ágil como para la mejora del producto.

### 4. Adaptaciones al Marco de Trabajo SCRUM
Dado el contexto particular de nuestro proyecto, donde el objetivo era aprender prácticas de gestión ágil y dado que el equipo tenía con fuerte limitante de horas libres para participar activamente, y que la duración total del proyecto debeía ajustarse al calednario del semestre, realizamos las siguientes adaptaciones al marco SCRUM:

#### Marco SCRUM

Este proyecto entonces cubre solamente lo que sería el Ciclo de Discovery en lo que seria **Dual Track SCRUM** de un proyecto completo produciendo como resultado un prototipo con User Stories validadas por usuarios. Por lo que aplicamos SCRUM a este ciclo, simulando que el Ciclo de Discovery es el Ciclo de Delivery, y esto implica que tenemos que traducir los elementos de uno a otro. Por ejemplo:
  - Cuando hablamos de producto e incrementos, en vez de estar entregando un producto funcional listo para ser usado por los usuarios, los incrementos son prototipos de funcionalidades que son una aproximación a lo que seria el producto final.
  - El backlog de ideas propias y surgidas del relevamiento con usuarios, será nuestro Product backlog
  - Los incrementos serán validados por el Prodct Owner y algunos usuarios que propusieron ideas, en lugar de que usuarios reales utilicen un produco real.
  - El equipo de desarrollo en lugar de estar codificando estará diseñando los prototipos como si fueran diseñadores.

Para mayor referencia se incluye el siguiente diagrama

![dual track scrum](img/dual-track-scrum.png)

#### Sprints

Se redujo de 4 a 2 semanas la duración de los Sprints debido al calendario propuesto por letra (requerimiento), y también para poder tener mayor cantidad de Sprints, y por ende, más feedback para hacer ajustes. También utilizamos un sprint "0" o inicial dedicado a realizar tareas de Discovery de ideas, relevamiento, y arquitectura del producto a desarrollar. Esto se hizo asi porque no teniamos claro un alcance concreto dado, sino que debiamos determinarlo en base a posibles usuarios del producto.

#### Planificación y Release

Si bien en cada Sprint posterior al inicial se hicieron avances en el producto, solo se relaizó un release al final, por lo que dado que había funcionalidades bastante fijas dadas por letra, y una fecha final fija por calendario ORT, la planificación realizada fué mas bien **Date Driven**, priorizando las épicas solicitadas por letra para cumplir el mínimo requerido y luego las que aportaran mayor valor a los usuarios, dejando otras por el camino que no se llegaron a implementar.

#### Roles multifunción

En nuestro caso, los roles de Product Owner y Scrum Master, también participan del desarrollo, aunque en menor medida. Por esto también se da la particularidad de que el Product Owner esta presente en todas las ceremonias, inclusive en las Daily Scrum lo que permite un feedback mas temprano, y si es necesario tomar decisiones de priorización poder hacerlo en ese mismo momento.

#### Distribución de la carga de trabajo

Se estableció una carga de trabajo, no constante a lo largo del proyecto, porque al hacer la planificación inicial el equipo identificó que no se iba a poder contar con una capacidad constante en el tiempo dado que hay entregas y otros eventos externos que afectan la disponibilidad de tiempo de los integrantes del equipo. En base a eso se definió planificar una capacidad mayor en las etapas iniciales, para luego ir descendiendo la misma en las etapas finales, de forma de poder mantener un promedio que nos permita cumplir los objetivos. El mismo principio se utilizó al planificar los Sprints, en base a los objetivos del mismo, establecimos prioridades semanales claras para asegurar la finalización de tareas críticas, de manera que no nos quede mucha carga de trabajo acumulada para el final del Sprint.

#### Virtualizacion de eventos

Dada la dispersión de los integrantes del equipo, y la dificultad de coincidir en un mismo lugar se decidió que todas las ceremonias de SCRUM se realizarán en forma virtual, salvo algunas revisiones con stakeholders puntuales.

#### Virtualizacion de artefactos de comunicación

Dado la misma imposibilidad de tener reunido el equipo físicamente en un lugar como para tener espacios colaborativos e irradiadores de información físicos, utilizamos Azure DevOps para la gestión visual de algunos artefactos como ser el Product Backlog, Sprint Backlog, Burndown y Velocity charts, y Taskboards. De esta manera mejoramos la comunicación y colaboración del equipo, priorizando y gestionando mejor las tareas asignadas. 

  También utilizamos Framer para la gestión del entregable, lo que facilita el acceso simultaneo para poder trabajar en la elaboración del mismo.

  Otras herramientas como MetroRetro, Planning Poker entre otras, se utilizaron como irradiadores de información que facilitan la comunicación con el equipo.

  Además se incorporó un grupo de Whatsapp para poder agilizar la comunicación y estar en permanente contacto y por ejemplo resolver dudas, plantear dificulades, ajustar prioridades, reportar avances, etc.

#### Frecuencia de Daily Scrums

Debido a la disponibilidad horaria de los integrantes del grupo, las Daily Scrums no son realizadas todos los días, en vez de ello, se hacen 3 veces a la semana, y se acepta que puedan tener hasta 30 minutos de duracion.


#### Duracion de Citas para ceremonias Scrum

Las citas fueron considerablemente mas larga que lo propuesto por SCRUM ya que por ejemplo se anexó tiempo para trabajo en conjunto luego de los 15 minutos aprox de duracion de la daily, algo similar con las demas. Esto para facilitar tareas de coordinacion entre las tareas que vienen realizando distintos integrantes que tienen cierta relación, solucionar bloqueos o dudas que algun miembro del equipo haya manifestado en la daily o la ceremonia que se haya realizao, o hacer cualquier ajuste que ayude a lograr el objetivo del Sprint.

#### Definición de User Stories

Se utilizó la técnica de **Card-Conversation-Confirmation** para la definición de las mismas, y BDD utilizando la sintaxis **Dado-Cuando-Entonces** para escribir los diferentes escenarios de los criterios de aceptación. Ser requirió que todas las User Stories cumplieran el criterio de **Definition of Ready** antes de su implementación, y cumplir con cada uno de los escenarios en **BDD** de los criterios de aceptación para alcanzar el **Definition of Done** para poder darla por finalizada.

#### "Pair Programming"

Se hizo bastante uso de esta técnica dado que no teníamos mucho tiempo para hacer verificaciones, y ciclos de prueba y correcciones, precisábamos que lo que se entregara tuviera la mejor calidad posible y fuera correcto. Cuando un integrante del equipo tenía una tarea compleja, solicitaba al Scrum Master apoyo y este buscaba quien podría ayudar o el mismo lo hacía, para resolver el tema de manera conjunta. Esto es algo que no propone SCRUM pero que al equipo la resultó bueno agregar a las tareas que el Scrum Master y equipo de desarrollo normalmente si hace comom parte de SCRUM de ayudar a desbloquear las tareas que no logran avanzar.

#### Reviews

Dado que no se tenía un producto utilizable en forma autónoma por los usuarios, se hicieron sesiones de demostración con usuarios, sobre las que se pidió feedback mediante cuestionarios.
También se hicieron videos demostrativos de cada funcionalidad entregada, para utilizar cuando no se podía agendar un encuentro.
Además en las Sprint Reviews se analizo todo este material junto con la revisión del propio Product Owner.

### 5. Algunos resultado obtenidos

1.	Aumento de la Velocidad del Equipo: Se observó un incremento significativo en la velocidad del equipo.

2.	Mejora en la Colaboración: Cuando un integrante del equipo tenía una tarea compleja, solicitaba al Scrum Master o un compañero de desarrollo, apoyo para resolver la misma de manera conjunta y así mejorar la calidad (visual) y unificación de los Frames. Esto resultó en una mayor colaboración y conocimiento compartido entre los miembros del equipo. A través de un grupo de Whatsapp estuvimos en permanente contacto por dudas, sobre lo que se debía hacer y los avances realizados y establecimos prioridades semanales claras para asegurar la finalización de tareas críticas, de manera que no nos quede mucha carga de trabajo acumulada para el final del Sprint.

3.	Satisfacción de los clientes: Se registró un aumento en la satisfacción del equipo, evidenciado en encuestas de feedback positivo.

Para la velocidad del equipo estos resultados no fueron inmediatos debido a que primero se tuvo que identificar los problemas, esto ocurre en las reuniones retrospectivas y luego generar un plan de acción, para luego poder determinar la mejor manera de tomar medidas frente al problema que fue detectado. Luego de resolver estos problemas pudimos optimizar nuestra velocidad. Además, al usar las herramientas más seguido, genero mayor facilidad a la hora de aplicar cambios o generar nuevas historias siendo más eficientes a la hora de implementarlas.
El punto de mejorar en la colaboración a su vez incide en la mejoría de la velocidad, debido a que, en caso de dudas o incluso trancarse en algún momento, resolverlo de manera conjunta era más rápido, que estancarse una persona sola intentando solucionar un problema. 
Además, mejorar la colaboración nos brindó una mejor organización, evitando posponer mucho trabajo para los días finales de las iteraciones, y distribuir mejor la carga de tareas para cada integrante.
Finalmente, en la satisfacción del equipo es el caso más claro, debido a que al comienzo de las iteraciones se plantea una forma de trabajo, y luego se va ajustando la metodología para la mayor comodidad de los integrantes, por lo que este aspecto con los ajustes correspondientes mejora rápidamente la satisfacción.

También logramos la correcta identificación y priorización de las funcionalidades que generaban valor para 
la aplicación, algunas de ellas no llegaron a implementarse o fueron descartadas desde el inicio.

### 6. Principales artefactos obtenidos

#### 6.1. Product Backlog. 
Definición y prototipos navegables que demuestran la funcionalidad de las User Stories implementadas.

Traer casos de uso para aca   ######### COMPLETAR ##################

#### 6.2. User stories SI implementadas a raiz de sugerencias de usuarios

- [Agregar chat](https://fi365-my.sharepoint.com/:v:/g/personal/sa276280_fi365_ort_edu_uy/EUuPPutG551KjWmyH2_IplEB0TAgqybAXMpo1obHR6SPug?e=gnpEwy)
- [Agregar idiomas](https://fi365-my.sharepoint.com/:v:/g/personal/sa276280_fi365_ort_edu_uy/EbLuHSbLbZVJoycxypKwJ40Bno_YCdSw7oko7et-P6UcWw?e=AMl5HO)
- [Agregar modo nocturno](https://fi365-my.sharepoint.com/:v:/g/personal/sa276280_fi365_ort_edu_uy/ETYmn5f4hINFt182nNF_T-MBdQ63fFOSqTnpZ8asvPyxLw?e=li4PSa)
- [Cambio de logo](https://fi365-my.sharepoint.com/:v:/g/personal/sa276280_fi365_ort_edu_uy/ETYmn5f4hINFt182nNF_T-MBdQ63fFOSqTnpZ8asvPyxLw?e=li4PSa)
- [Mejoras de los favoritos](https://fi365-my.sharepoint.com/:v:/g/personal/sa276280_fi365_ort_edu_uy/EY4W7lw-_Q1JjmlYhQeyQBoBr0Ni19ZvJAPFob9D2v56Cw?e=37RgwX)

#### 6.3. User stories NO implementadas

A continuación, mostraremos en detalle las principales funcionalidades que fueron descartadas, junto con su historia de usuario asociada y una breve justificación de por qué no se implementaron.

- Agregar estados: 

![AgregarEstados](img/funcionalidades-no-implementadas/Agregar-estados.png)

En cierto momento se consideró la idea de añadir funcionalidades parecidas a las de las redes sociales como permitir a los usuarios subir historias y fotos en la 
aplicación, pero decidimos no implementarlas. Nuestra aplicación está centrada en pronósticos deportivos, y agregar estas funciones podría desviar el enfoque 
principal y sobrecargar la experiencia del usuario. Estos requerimientos fueron solicitados por el público juvenil, que tiene una inclinación natural hacia el uso 
de este tipo de funcionalidades, sin ser demandantes. 

Además, la implementación de estas características podría complicar el desarrollo y mantenimiento de la app, desviando recursos y atención de nuestro objetivo 
principal. La inclusión de funciones de redes sociales también podría diluir la propuesta de valor única de la aplicación y hacerla menos atractiva para los 
usuarios que buscan una plataforma dedicada exclusivamente a los pronósticos deportivos. Por estas razones, optamos por mantenernos enfocados en mejorar y optimizar 
las funciones centrales relacionadas con los pronósticos, asegurando así una experiencia de usuario más coherente y efectiva. 

- Automatización de modo oscuro:

![AutomModoOscuro](img/funcionalidades-no-implementadas/Automatizacion-modo-oscuro.png)

Un usuario también solicito el modo oscuro automático, pero al ya tener implementado el modo oscuro manual funcionando adecuadamente y satisfaciendo las necesidades de los usuarios, implementar un modo oscuro automático no nos pareció relevante o prioritario en términos de beneficio adicional. 

- Creación de un muro: 

![CreacionMuro](img/funcionalidades-no-implementadas/Creacion-muro.png)

También consideramos la idea de permitir a los usuarios publicar e interactuar en muros dentro de la aplicación. Sin embargo, debido a las limitaciones de tiempo y la priorización de otras funcionalidades que aportaban mayor valor, decidimos no implementar esta característica. Aunque probablemente habría sido interesante y beneficioso para fomentar la interacción entre los usuarios y enriquecer la experiencia de la comunidad. 

- Pencas de pago:
 
![PencasPagas](img/funcionalidades-no-implementadas/Pencas-pagas.png)

Otra funcionalidad no agregada fue la de tener pencas pagas, en las que se debería pagar antes para acceder a ella. Decidimos mantener las pencas gratuitas ya que de esta forma nos alineamos con una estrategia de crecimiento y validación del producto antes de introducir cualquier componente de pago, lo cual es una decisión estratégica para establecer una base sólida y preparar el terreno para futuras expansiones y monetización. 

#### 6.3. Otros Artefactos del Proyecto   COMPLETAR -------------------------
1.	Minuta de Sprint Planning con su agenda, actividades y resultados.
2.	Objetivos del proyecto.
3.	Review final de usuarios (###### COMPLETAR Juntar todas las reviews de todas las US #########)

Durante el desarrollo del proyecto de aplicación de pencas deportivas utilizando prácticas de ingeniería de software ágil, se obtuvieron importantes lecciones que impactaron positivamente en el rendimiento del equipo y en la calidad del producto final. Estas lecciones aprendidas no solo fueron aplicables al contexto específico del proyecto, sino que también son transferibles a futuros proyectos de ingeniería de software ágil. 

## Reflecciones y Lecciones Aprendidas

### 1. Problemas Encontrados y Acciones de Mejora Implementadas

En el correr de las iteraciones, hubieron varios puntos que se tuvieron que ir puliendo para mejorar tanto la calidad del desarrollo y en consecuencia el producto que se estaba diseñando, como a su vez mejorar nuestras prácticas para tener una mejor organización en el trabajo.
Los puntos a mejorar fueron:
- **Desafíos en la comunicacion**: Durante el desarrollo del proyecto, uno de los principales desafíos que enfrentamos fue mantener una comunicación clara y constante entre los miembros del equipo. Con horarios diferentes, coordinar reuniones sincrónicas resultaba complicado, y los malentendidos sobre las tareas y prioridades comenzaron a afectar el progreso del proyecto.
- **Desincronización en los horarios**: Los miembros del equipo tenían diferentes disponibilidades, lo que dificultaba la programación de reuniones conjuntas.
  Falta de claridad en las tareas: A veces, los objetivos y las responsabilidades no estaban suficientemente claros, llevando a confusiones y duplicaciones de esfuerzos.
- **Limitaciones de tiempo**: Otro desafío significativo fue la limitación de horas disponibles para trabajar en el proyecto. Cada miembro del equipo disponía de tiempos diferentes, lo que restringía nuestra capacidad de avanzar rápidamente y requería una gestión del tiempo muy eficiente.
- **Acumulación de trabajo**: En algunas iteraciones, el trabajo no se completaba a tiempo, acumulándose para las siguientes y creando una carga adicional. El uso de Framer al principio también resultó complicado para los desarrolladores, ya que se presentaban comportamientos inesperados en los canvas y en los distintos elementos que colocábamos sobre ellos lo que genero demoras, y que ciertas historias quedaran fuera de la iteración correspondiente.
- **Problemas de adaptación**: La adopción de SCRUM y las prácticas ágiles presentó sus propios desafíos, especialmente porque algunos miembros del equipo no tenían experiencia previa con estas metodologías. La resistencia inicial y la curva de aprendizaje afectaron la implementación efectiva de SCRUM.
- **Falta de experiencia**: La inexperiencia en SCRUM llevó a una implementación inicial ineficaz de las ceremonias y artefactos.
- **Confusión en roles y responsabilidades**: Hubo incertidumbre sobre las responsabilidades específicas de cada rol dentro del equipo SCRUM.

#### Las acciones de mejora principales fueron:
- **Pair Programming**:  Implementamos sesiones de programación en pareja para abordar tareas complejas de manera más eficiente y mejorar la calidad de los resultados.
- **Herramientas de Comunicación Instantánea**: Utilizamos WhatsApp para mantener un canal abierto y constante de comunicación. Esto permitió resolver dudas rápidas y mantener a todos informados sobre el progreso y los problemas en tiempo real.
- **Tablero Virtual de Tareas (Azure Boards)**: Azure Boards nos ayudo mucho en este punto para la gestión visual de tareas, facilitando que todos los miembros del equipo vieran el estado actual de las tareas y los avances en tiempo real.
- **Priorización Semanal**: Establecimos prioridades semanales claras para asegurar la finalización de tareas críticas y evitar la acumulación de trabajo al final del sprint.
- **Agregar más días de reuniones y trabajo colaborativo**: Inicialmente, solo teníamos reuniones diarias los viernes y los sábados (día de la entrega), lo que aumentaba la carga de trabajo en esos dos días y reducía los resultados obtenidos. Esto ocurría porque, antes del viernes, había tareas que no se habían identificado o realizado correctamente, lo que provocaba un retraso continuo en el planificado para esos dos días.
  Por esta razón, decidimos agregar una reunión diaria los martes (de corta duración) para coordinar y mejorar la comunicación antes del tiempo límite de la iteración.

- **Mentoría Continua**: Los miembros con experiencia en SCRUM proporcionaron mentoría y apoyo continuo, ayudando a resolver dudas y guiar en la correcta aplicación de las prácticas.
  Algunos desarrolladores se adaptaron rápidamente al uso de Framer, destacándose por su habilidad para dominar la herramienta. Estos miembros no solo trabajaron con mayor eficacia, sino que también proporcionaron un valioso apoyo al resto del equipo, facilitando el uso de Framer y compartiendo sus conocimientos para mejorar la productividad general.

- **Feedback y Mejora Continua**: Utilizamos las retrospectivas al final de cada sprint para identificar áreas de mejora y ajustar nuestras prácticas de manera iterativa, lo que ayudó a superar la resistencia inicial y mejorar gradualmente la implementación de SCRUM.

### 2. Principales Lecciones Aprendidas

A continuación, se amplía la discusión sobre las principales lecciones aprendidas:
1.	**Importancia de la Colaboración y Comunicación Efectiva**: Una de las lecciones clave fue la relevancia de fomentar la colaboración entre los miembros del equipo y mantener una comunicación efectiva. La apertura para compartir ideas, resolver problemas de manera conjunta y mantener una comunicación clara y constante contribuyó significativamente al éxito del proyecto. La colaboración permitió acelerar el desarrollo del producto y garantizar que todas las partes involucradas estuvieran alineadas en cuanto a los objetivos y las tareas a realizar.
2.	**Flexibilidad y Adaptación ante los Cambios**: Otra lección importante fue la necesidad de ser flexibles y estar preparados para adaptarse a los cambios que surgieran durante el proyecto. En un entorno ágil, donde los requisitos y las circunstancias pueden evolucionar rápidamente, la capacidad de adaptación se vuelve fundamental para mantener la eficiencia y la efectividad en el desarrollo del producto. La flexibilidad permitió al equipo ajustar su enfoque, prioridades y estrategias según las necesidades del proyecto.
3.	**Inspección y Mejora Continua**: La práctica de realizar retrospectivas al final de cada iteración fue fundamental para identificar áreas de mejora, analizar lo que funcionó bien y lo que se podría mejorar en el proceso de desarrollo. La inspección constante del trabajo realizado y la implementación de acciones de mejora permitieron al equipo optimizar sus prácticas, corregir posibles errores y avanzar de manera más eficiente en cada iteración del proyecto.
4.	**Implementación Efectiva de Acciones de Mejora**: Una lección clave fue la importancia de implementar acciones de mejora de manera efectiva y sistemática. Asignar responsabilidades claras, hacer un seguimiento regular de las mejoras propuestas, evaluar su efectividad y documentar todo el proceso fueron pasos fundamentales para garantizar que las acciones de mejora tuvieran un impacto positivo en el proyecto. La implementación efectiva de acciones de mejora contribuyó a la optimización del rendimiento del equipo y al logro de los objetivos del proyecto.

Las lecciones aprendidas durante el proyecto fueron fundamentales para el éxito del mismo. La colaboración, la flexibilidad, la inspección y mejora continua, así como la implementación efectiva de acciones de mejora, son aspectos clave que el equipo pudo aplicar y que serán valiosos para futuros proyectos de ingeniería de software ágil. Estas lecciones no solo impactaron en el desarrollo del producto, sino que también en el crecimiento y la mejora del equipo en su conjunto, fortaleciendo su capacidad para enfrentar desafíos y alcanzar objetivos de manera eficiente y efectiva en entornos ágiles de desarrollo de software.

Además, este proyecto nos permitió comprender las responsabilidades de cada rol y la importancia de cada artefacto, lo que nos facilita llevar estos conocimientos a nuestro trabajo y aplicarlos para mejorar nuestras prácticas. 



## Conclusión
La aplicación de prácticas ágiles mediante SCRUM en el desarrollo de un MVP para una aplicación de pencas deportivas nos permitió alcanzar nuestros objetivos y aprender valiosas lecciones sobre la gestión ágil de proyectos.

Se pudo ver en la práctica la aplicación de lo que indica el marco de trabajo SCRUM y también como se convive con el proceso de mejora continua a partir del feedback, tanto a nivel de las User Stories como a nivel del proceso de desarrollo en si.

Las adaptaciones realizadas fueron efectivas en mejorar la eficiencia y la calidad del trabajo, y las acciones de mejora implementadas resultaron en beneficios tangibles para el equipo y el proyecto. 

Estos aprendizajes serán fundamentales para futuros proyectos de ingeniería de software ágil.

## Referencias

Scrum Guide: Ken Schwaber and Jeff Sutherland, "The Scrum Guide."
Agile Principles: Manifesto for Agile Software Development, agilemanifesto.org.
