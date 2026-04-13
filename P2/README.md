## DIU - Practica2, entregables

### Ideación 
En esta fase, hemos convergido las ideas iniciales recopiladas para estructurar las necesidades reales de nuestros usuarios frente a la propuesta del restaurante interactivo.

* Malla receptora de información

Se ha utilizado una matriz de 4 cuadrantes (Cosas positivas, Críticas constructivas, Preguntas e Ideas) para evaluar el concepto inicial. Destacan como puntos fuertes el diseño minimalista y el sistema de reservas, pero se han detectado dudas clave sobre la vinculación de cuentas con la máquina física de Gashapon y el gasto imprevisto para conseguir puntos. Como ideas de mejora, se proponen mercados de intercambio de figuras y notificaciones push.

  <img width="3291" height="2600" alt="FeedbackCaptureGrid" src="https://github.com/user-attachments/assets/30882cf9-5517-42ea-a31e-271f7eb62367" />

* Mapa de empatía

Hemos mapeado los dolores (Pains) y ganancias (Gains) de nuestro público objetivo. Se evidencia una clara frustración generalizada por las colas y los tiempos de espera (Pain), frente a un alto nivel de motivación (Gain) impulsado por la gamificación de la experiencia (coleccionismo de premios con 5 puntos) y el entorno temático.

<img width="5024" height="3945" alt="empathyMap" src="https://github.com/user-attachments/assets/c5db2fe8-063a-4e4c-a119-fa616ae937d1" />

* Point of View

Se han definido tres perfiles de usuario y sus insights críticos que dirigen las funcionalidades del sistema:

El Estudiante Coleccionista: Frustrado por no poder trackear sus recompensas físicas. Insight: Necesita el módulo digital "Pakupaku-Go" para visualizar su progreso y asegurar su colección.

La Ejecutiva Ocupada: Odia perder tiempo. Insight: Evita el local por las colas; su adopción de la app depende de un sistema de reservas online infalible y rápido.

La Joven Participativa: Aburrida de restaurantes unidireccionales. Insight: Necesita el módulo de votaciones para sentirse parte de la comunidad y decidir las futuras temáticas del local.

![povdiu](https://github.com/user-attachments/assets/133c16a6-2991-4642-ae82-65832d3e5601)


### PROPUESTA DE VALOR
* ScopeCanvas

El lienzo de alcance define a SushiJAMA no solo como un restaurante, sino como una experiencia gastronómica innovadora y cambiante basada en animes de la infancia. Se establecen objetivos a corto plazo (rediseño web accesible y corrección de flujos de reserva) y a largo plazo (colaboración con el sector primario y fomento de la cultura japonesa). Las métricas clave de éxito se basarán en el aumento de reservas, valoraciones y volumen de interacciones en el módulo de comunidad.

![ScopeCanvas (1)](https://github.com/user-attachments/assets/87f0263c-10ff-45c9-8079-4fc33966b268)



### TASK ANALYSIS

* User Task Matrix
 
Mediante una matriz de tareas, cruzamos los distintos perfiles de usuario (registrado, no registrado, administrador) con las acciones principales (reservar, ver carta, escanear código QR, votar temáticas). Esto nos permitió priorizar el desarrollo de flujos críticos frente a acciones secundarias.

* User/Task flow

Se han modelado los diagramas de flujo lógicos para las dos tareas más críticas (Happy Paths) que resuelven los insights de nuestro POV:

Flujo de Reserva: Implementa una validación lógica de sesión (Autenticación) y un control de disponibilidad de fechas antes de confirmar.

Registro de Recompensa (Pakupaku-Go): Detalla la interacción Phygital (Físico-Digital). El usuario inicia sesión, accede al inventario, concede permisos de cámara, escanea el QR de su premio y el sistema valida si es único antes de sumarlo a su colección digital.

![UserFlow](https://github.com/user-attachments/assets/2e0d3f6f-2358-48ce-95be-a1e74a63da9d)


### ARQUITECTURA DE INFORMACIÓN

* Sitemap

El mapa del sitio revela una arquitectura jerárquica plana y accesible. Desde el Home nacen 6 nodos principales: Reservas, Carta (Menú), Pakupaku-Go (Recompensas y mecánicas), Quiénes Somos, Inicio Sesión / Perfil y Comunidad (Sugerencias y votaciones). Esta estructura asegura que ningún flujo crítico esté a más de 3 clics de profundidad.

<img width="2528" height="1488" alt="SiteMap" src="https://github.com/user-attachments/assets/10d32ddb-0f9c-4a79-bbde-41a4f02d5789" />

* Labelling

Se ha diseñado un vocabulario orientado a la inmersión del usuario. Por ejemplo, en lugar de utilizar términos genéricos como "Mis puntos" o "Recompensas", se ha acuñado el término "Pakupaku-Go" para darle identidad al sistema de gamificación. Asimismo, la sección social se engloba bajo "Comunidad", reforzando el sentimiento de pertenencia identificado en la fase de ideación.

### Prototipo Lo-FI Wireframe 

Se ha realizado la maquetación estructural de baja fidelidad en Figma. El enfoque técnico ha sido el diseño modular y responsivo (Mobile-First adaptado a Desktop), utilizando intensivamente propiedades CSS equivalentes en Figma:

Auto Layout y Flexbox: Para sistemas de tarjetas adaptables (Wrap).

Sistemas de Cuadrícula: Vistas de Carta/Menú y Comunidad que reorganizan su contenido dinámicamente de múltiples columnas en escritorio a una sola columna en pantallas de 390px.

Componentes reutilizables: Creación de master components para los menús de navegación, footers, y tarjetas de platos (Item_Plato).

* [WIREFRAME-PC](https://github.com/Manuizquierdoizq/DIU1.SushiJAMA/tree/master/P2/Wireframe_PC)

* [WIREFRAME-MOVIL](https://github.com/Manuizquierdoizq/DIU1.SushiJAMA/tree/master/P2/Wireframe_Movil)

### Conclusiones  
En esta segunda fase, hemos transformado la investigación inicial de SushiJAMA en una estructura digital sólida. Nuestro objetivo: resolver la fricción de las colas físicas y digitalizar la experiencia de gamificación (Gashapon).

Definición: Tras analizar a los usuarios (Malla Receptora, Mapa de Empatía y POV), confirmamos que la clave del éxito reside en un sistema de reservas infalible y en el módulo Pakupaku-Go, que permite escanear y coleccionar digitalmente los premios físicos.

Estructura: Trazamos los diagramas lógicos (User Flows) para estas tareas críticas y organizamos la plataforma mediante un Sitemap plano y de fácil navegación.

Prototipado: Materializamos esta arquitectura creando Wireframes Lo-Fi en Figma. Implementamos un diseño 100% responsivo (Mobile-First a Desktop) utilizando Auto Layout y cuadrículas elásticas.

Conclusión: Hemos resuelto los retos estructurales y de usabilidad. La arquitectura del proyecto está validada y el terreno queda perfectamente preparado para iniciar el diseño visual de Alta Fidelidad (UI).

>>>> Este fichero se debe editar para que cada evidencia quede enlazada con el recurso subido a la carpeta de la practica. Se pide más detalle técnico en las descripciones de lo que sería el README principal del repositorio y que corresponde a la descripcion del Case Study.
>>>> Termine con la seccion de Conclusiones para aportar una valoración final del equipo sobre la propia realización de la práctica
