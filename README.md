# DIU26
Prácticas Diseño Interfaces de Usuario (Tema: Restaurante Sushi Temática Anime ) 

* [Guiones de prácticas](GuionesPracticas/)

**Grupo:** DIU1_SushiJAMA.  **Curso:** 2025/26 

**Actualizado:** 19/03/2026

**Proyecto:** SushiJAMA

**Descripción:** SushiJAMA es un restaurante japonés de temática anime que combina la gastronomía japonesa con un innovador sistema de recompensas físicas mediante Gashapones. A través de nuestra plataforma web, los usuarios acceden a "Pakupaku-Go", un sistema de fidelización donde cada plato consumido otorga 1, 2 o 3 puntos según su categoría. Al acumular 5 puntos, el cliente consigue un premio aleatorio de la colección temática de esa temporada. Aquellos usuarios que logran reunir todos los premios de una colección obtienen una recompensa final exclusiva. Todo el progreso se gestiona desde su perfil, donde además pueden interactuar con la comunidad y votar las temáticas de las futuras temporadas.

**Logotipo:**
<p align="center">
  <img src="./img/Logo.png" width="400">
</p>

Miembros y nombre del equipo:
 * :bust_in_silhouette:  Juan Antonio Jara     :octocat:     
 * :bust_in_silhouette:  Manuel Jesús Izquierdo     :octocat:

----- 

<br>

# Proceso de Diseño 

<br>

## Paso 1. UX User & Desk Research & Analisis 


### 1.a User Research Plan
-----


Para comenzar a hacer el User Research Plan de nuestro proyecto SushiJAMA hemos visitado y degustado otros restaurantes japoneses con una temática parecida a la que tenemos ideada con la finalidad de abstraernos de lo convencional.

La investigación que hemos realizado se ha basado en identificar los posibles puntos débiles de otros restaurantes para conseguir adaptar la comida japonesa tradicional a las nuevas tendencias, para ello nos hemos basado en patrones de consumo y opiniones/reseñas de distintos usuarios en redes sociales buscando siempre la novedad.

SushiJAMA se diferencia del resto de locales con una nueva mecánica que consiste en una recompensa ambientada en la temática que haya en ese momento. Esta, consiste en un gashapon de pequeños premios aleatorios, que variarán por temporada cada 5 puntos adquiridos. Estos dependen del tipo de plato pedido, habiendo platos de 1,2 y 3 puntos. Con esta propuesta, queremos incentivar a que los usuarios quieran coleccionar todos los premios de esa temporada. Además habrá una recompensa adicional para quienes tengan toda la colección.

Para hacer esto posible, nos centraremos en que el público usuario sea participe del progreso del restaurante aportando sus propuestas de mejora e ideas para futuras temporadas.

<p align="center">
  <img src="../img/Logo.png" width="500">
</p>


### 1.b Competitive Analysis
-----


Para nuestro análisis competitivo, hemos seleccionado dos modelos de negocio parecidos al nuestro que nos permiten evaluar cómo se gestiona la experiencia de usuario frente al sistema de recompensas:

* **[Amazing Mota](https://www.amazingmota.com/welcome) (Valencia):** Un restaurante buffet local muy popular por incluir una cinta giratoria y máquinas de Gashapon físicas.
* **[Kura Sushi](https://kurasushi.com/) (Internacional):** Es una cadena global pionera en la integración de recompensas mediante su sistema *Bikkura Pon*.

Hemos elegido estas dos plataformas porque representan los dos extremos del mercado al que nos dirigimos. Por un lado, Amazing Mota tiene un gran atractivo físico, pero su carencia total de reservas online y de un seguimiento digital de los premios genera algo de fricción al usuario. Por otro lado, Kura Sushi ofrece un ecosistema digital robusto, pero su interacción es puramente unidireccional (el usuario consume y recibe, sin formar parte de una comunidad). 

Realizar esta comparativa nos aporta información vital para **SushiJAMA**, mostrando que existe un nicho desatendido para una plataforma que combine un portal de *delivery* con un perfil de usuario gamificado (*Pakupaku-Go*) donde el progreso se guarde digitalmente y la comunidad participe en las decisiones del restaurante.

A continuación, mostramos la matriz de análisis donde hemos evaluado aspectos de modelo de negocio, funcionalidad, usabilidad y accesibilidad:

![Competitor Analysis](../img/Competitor_Analysis.png)



### 1.c Personas 
-----
Presentamos dos perfiles diferentes, donde cada uno aporta su visión y expectativas desde perspectivas distintas, pero con el objetivo común de disfrutar de una experiencia gastronómica única y sin complicaciones. David es un chico más reflexivo e introvertido, un coleccionista apasionado por el anime y los juegos de rol que valora la eficiencia y busca asegurar la mesa para sus amigos sin tener que hacer colas. Yelena, por otro lado, es una líder extrovertida y creativa, experta en marketing digital, que siempre busca locales innovadores e "instagrameables" para compartir contenido e interactuar con la comunidad de sus marcas favoritas.
<br>
![David](./3.Personas/David.png)
![Yelena](./3.Personas/Yelena.png)


### 1.d User Journey Map
----


David y Yelena se enfrentan a la experiencia de visitar un restaurante de la competencia (Amazing Mota) desde perspectivas muy diferentes. Para David, la salida representa una oportunidad para disfrutar con sus amigos de rol y ampliar su colección de figuras, pero la imposibilidad de reservar online y las largas esperas en la calle dificultan enormemente su experiencia. A pesar de disfrutar de la comida y el premio físico, la falta de un perfil digital para guardar su progreso le resulta frustrante. Por su parte, Yelena busca un local estético para crear contenido e interactuar con la marca. Aunque el ambiente visual le resulta muy atractivo, la pobre digitalización del menú y la ausencia total de una comunidad online donde participar o dejar sugerencias acaban frustrando por completo su experiencia.
<br>
![Journey David](./4.JourneyMaps/David-Journey.jpg) 
![Journey Yelena](./4.JourneyMaps/Yelena-Journey.jpg) 


### 1.e Usability Review
----


La página de **SushiJAMA** ha obtenido una puntuación de **79 sobre 100** (Buena).
<br>
![Usability Review](./5.UsabilityReview/usabilityReview_nota.png) 
<br>

En nuestra revisión, SushiJAMA demuestra ser una plataforma sólida y bien planteada. Destaca especialmente en la claridad de su contenido, la arquitectura de la información y la facilidad para que los usuarios comprendan el innovador sistema de recompensas gamificado. La identidad visual es atractiva y está muy bien alineada con nuestro público objetivo.

Sin embargo, para alcanzar la excelencia y superar a competidores físicos como Amazing Mota o Kura Sushi, hemos detectado áreas de mejora clave. Existen ciertas fricciones en el flujo de la reserva online que podrían simplificarse para reducir el número de clics, y las opciones de filtrado en el menú digital pueden resultar algo confusas en dispositivos móviles. Optimizar la navegación en estos puntos es crucial para redondear la experiencia del usuario.

Enlace: [Aquí](./5.UsabilityReview/UsabilityReview_SushiJAMA.xlsx).


### 1.f Briefing Final
----

Como se indicó inicialmente en el [User Research](#1a-user-research-plan), el objetivo de nuestro proyecto SushiJAMA es revolucionar la experiencia en la restauración japonesa, uniendo la reserva online con un sistema de fidelización (Pakupaku-Go).

Para asentar las bases, iniciamos haciendo un [Análisis de competidores](#1b-competitive-analysis), destacando el caso de [Amazing Mota](https://www.amazingmota.com/welcome). Concluimos que, aunque su modelo físico con gashapones y cinta giratoria es muy atractivo para el público, presenta una gran carencia: no admiten reservas online y su menú es un simple PDF estático, lo que genera fricción en la experiencia del usuario incluso antes de visitar el local.

Después, valoramos esta [experiencia](#1d-user-journey-map) a través de dos [perfiles](#1c-Personas) con intereses distintos. Por un lado, David, un usuario coleccionista que buscaba organizar una cena con amigos, se encontró con el estrés de hacer cola en la calle y la frustración de no poder registrar digitalmente sus premios físicos. Por otro lado, Yelena, una creadora de contenido que buscaba interactuar con la marca, se topó con un sistema sin opciones para dejar feedback o participar en una comunidad.

Finalizamos con una revisión de [usabilidad](#1e-usability-review) del sitio, obteniendo una puntuación de 79/100. Valoramos positivamente aspectos como la estructura visual y la claridad del menú principal, pero detectamos algunos fallos como una barra de búsqueda mejorable, posibles errores en la navegación y las citas del apartado de reservas así como la falta de opciones de filtrado.

En conclusión, el estudio confirma que existe un nicho claro para SushiJAMA. Para triunfar, es necesario diseñar una plataforma *web responsive* que elimine las colas mediante reservas online, ofrezca una carta interactiva y fidelice al usuario permitiéndole gestionar sus puntos de gashapon y votar en las decisiones futuras del restaurante.
<br>
<br>



## Paso 2. UX Design  

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento

### 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
![Método UX](img/feedback-capture-grid.png) 
----

>>> Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior. De qué carece la competencia?? Tu diagrama puede ser una figura subida a la carpeta P2/


 Interesante | Críticas     
| ------------- | -------
  Preguntas | Nuevas ideas
  
    
>>> Explica el Problema y plantea una hipótesis. Es decir, explica aquí qué 
>>> se plantea como "propuesta de valor" para un nuevo diseño de aplicación propio


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

>>> Propuesta de valor, pero ahora en vez de un texto es un ScopeCanvas que has subido a P2/ y enlazado desde aqui. Tambien vale una imagen miniatura del recurso.
>>> No olvides que tu propuesta ya tiene un nombre corto y puedes actualizar la cabecera de este archivo



### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

>>> Definir "User Map" y "Task Flow" ... enlazar desde P2/ y describir brevemente


### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

>>> Identificar términos para diálogo con usuario (evita el spanglish) y la arquitectura de la información. Es muy apropiado un diagrama tipo sitemap y una tabla que se ampliaría para llevar asociado la columna iconos (tanto para la web como para una app). 

Término | Significado     
| ------------- | -------
  Login  | acceder a plataforma


### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

>>> Plantear el diseño del layout para Web/movil (organización y simulación). Describa la herramienta usada 

<br>

## Paso 3. Mi UX-Case Study (diseño)

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

>>> Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo. Todos los recursos estarán subidos a la carpeta P3/
>>> Explique aqui la/s herramienta/s utilizada/s y el por qué de la resolución empleada. Reflexione ¿Se puede usar esta imagen como cabecera de Instagram, por ejemplo, o se necesitan otras?


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

>>> Plantear el Landing Page del producto. Aplica estilos definidos en el moodboard


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

>>> Estudio de Guidelines y explicación de los Patrones IU a usar 
>>> Es decir, tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 


### 3.d Mockup
![Método UX](img/mockup.png) 
----

>>> Consiste en tener un Layout en acción. Un Mockup es un prototipo HTML que permite simular tareas con estilo de IU seleccionado. Muy útil para compartir con stakeholders


<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea



<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




