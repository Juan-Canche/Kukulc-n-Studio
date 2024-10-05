<h1 align="center">
Kukulc-n-Studio
</h1>
<div align="center">
Proyect FIS.

</div>

<a name="top"></a>

# Integrantes

- Josemaría Conde Chabarría
- José Luis Basulto Cámara
- Mauricio Antonio De lázaro Lara
- Christopher May Paat
- Juan Angel Canché Góngora
- Joel Humberto Basto Chavarria
- Oswaldo Castillo Machado

# Introducción

**Propósito**

Su propósito es ser un servicio de entretenimiento para sus jugadores. El sistema de transporte Va y Ven en la ciudad de Mérida Yucatán es muy conocido y querido por la ciudadanía, hoy en día existen muchos videojuegos que tienen el concepto del Va y Ven como principal atractivo. Hasta el momento los juegos que se han lanzado son principalmente del género "simulador" donde el usuario simula ser conductor del vehículo y recorre las calles de Mérida. Este proyecto ofrece un estilo diferente de jugabilidad, que busca satisfacer a otro tipo de jugadores los cuales se inclinan por el género de administración y estrategia.

**Convenciones del documento** 
Convención | Descripción 
---------- | :--------- | 
Las palabras grandes en blanco | Son títulos. | 
Las palabras de tamaño normal con sombreado  | Son subtítulos.  | 
RF-000   | Hace referencia a un requerimiento funcional y en qué orden está.   | 
RNF-000    | Hace referencia a un requerimiento no funcional y en qué orden está.    |
NPC| Personaje no jugable. | 
UML | Lenguaje Unificado de Modelado. | 

**Audiencia objetivo y sugerencias de lectura**

Este documento está dirigido a desarrolladores involucrados en la creación del videojuego de administración y estrategia basado en el sistema de transporte metropolitano Va y Ven, así como a desarrolladores externos que deseen conocer más sobre el proyecto. Además, también está destinado al público en general que busque una comprensión más profunda de las características y objetivos del juego. Para los desarrolladores se sugiere leer la parte de requerimientos y diagramas UML y C4, para saber sobre la arquitectura y funcionamiento del videojuego. Para el público en general, leer este apartado de introducción y requerimientos.

**Objetivos**
- Mostrar una interfaz de usario intuitiva.
- Registrarse e iniciar sesión.
- Tener las funciones base de toda aplicación como: Botones de reanudar, pausar, quitar sonido, configuración, perfil, etc.
- Crear, eliminar y actualizar perfiles de usuario.
- Mostrar los mapas.
- Mostrar las rutas.
- Reproducir de ambientación.
- Mostrar y usar los diferentes tipos de transporte (camiones).
- Mostrar los NPCs y que puedan subir y bajar del camión.

**Alcance del proyecto**

**Tareas(elementos dentro del alcance)**

- Gestión de rutas: Los jugadores podrán tomar decisiones sobre la asignación y optimización de las rutas del sistema Va y Ven, asegurando que las unidades de transporte funcionen de manera eficiente y satisfagan las necesidades de los personajes no jugables (NPCs) durante cada nivel.
- Gestión de camiones: El juego incluirá diferentes tipos de camiones los cuales se irán desbloqueando mientras se sube de nivel, cada unidad tendrá una velocidad específica, una capacidad de personas y cierta energía para funcionar.
- Interacción de pasajeros: Los pasajeros que serán NPCs servirán como método de validación para la efectividad de las rutas y las unidades que se estén usando, habrá diferentes tipos de pasajeros y cada uno tendrá una ruta específica. Además, contarán con las acciones de subir y bajar del camión.
- Progresión por niveles: Los jugadores comenzarán en el nivel 1 del juego, mientras vayan avanzando iran subiendo de nivel y desbloquenado diferentes mapas, camiones, rutas y la dificultad irá incrementando, por ejemplo, en la cantidad de rutas que administrar y desafíos relacionados con la satisfacción de los pasajeros. 
- Interfaz de usuario: El juego contará con una interfaz de usario intuitiva para que al jugador le sea fácil de interactuar con la aplicación y pueda realizar las actividades de manera satisfactoria. Los jugadores podrán visualizar y gestionar las rutas, mapas, camiones, los niveles de satisfacción de los NPCs a través de paneles interactivos y gráficos y usar las funciones por defecto de un videojuego tales como pausar, reanudar, configurar la aplicación, quitar el sonido, registrarse, iniciar sesión, crear perfil, entre otras.

**Limitaciones**
- En esta primera versión el juego no contará con modo multijugador en línea.
- El diseño del mapa del juego debe estar inspirado unicamente en la ciudad de Mérida Yucatán.
- En esta fase inicial el juego solo será compatible con el sistema operativo android.
- La interacción del jugador con los NPCs será solo para saber sobre su satisfacción, no tendrán dialogos.
- El juego esta pensado para que sea en una perspectiva 2D.

**Referencias** 
- Lifeparticle. (s. f.). GitHub - lifeparticle/Markdown-Cheatsheet: 🔖  The Ultimate Markdown Cheatsheet. GitHub. Recuperado el 4 de octubre de 2024, de https://github.com/lifeparticle/Markdown-Cheatsheet?tab=readme-ov-file#tables
-  StackEdit. (s/f). Stackedit.io. Recuperado el 4 de octubre de 2024, de https://stackedit.io/app
- Flowchart maker & online diagram software. (s/f). Diagrams.net. Recuperado el 4 de octubre de 2024, de https://app.diagrams.net/
- O365devx. (2023). Convenciones de documento (VBA). Microsoft Learn. https://learn.microsoft.com/es-es/office/vba/language/concepts/getting-started/document-conventions-visual-basic-for-applications
- Atlassian. (s/f). Alcance del proyecto: cómo puede ahorrar tiempo la gestión del alcance del proyecto. Atlassian. Recuperado el 4 de octubre de 2024, de https://www.atlassian.com/es/work-management/project-management/project-

# Descripción del proyecto

**Descripción general** 

El videojuego pertenece al género de administración y estrategia, en el que se gestionan las rutas del sistema de transporte metropolitano "Va y Ven". El jugador toma decisiones sobre el funcionamiento de las rutas y las unidades de transporte con el objetivo de mantener la mayor satisfacción posible de los personajes no jugables (NPCs) durante los niveles o fases del juego. Este sistema se centra en la toma de decisiones estratégicas, permitiendo al jugador utilizar la divisa de satisfacción generada por los NPCs para mejorar su estrategia. Las decisiones del jugador impactarán directamente en el funcionamiento de las rutas, la eficiencia del transporte y la experiencia general de los pasajeros virtuales. El proyecto busca ofrecer una experiencia de juego que combine la complejidad de la gestión de un sistema de transporte con una jugabilidad accesible y entretenida.

**Perspectiva del producto**

**Características del producto**

**Clases y características del usuario**

**Ambiente de operación**

**Restricciones de diseño e implementación**

**Documentación del usario**

**Suposiciones y dependencias**


# Requerimientos

# Funcionales

- RF-001: Para poder acceder completamente a las funciones, se debe iniciar sesión con un usuario y contraseña. De esta manera podremos ayudar a la creación y personalización de perfiles y a la seguridad de la cuenta.

- RF-002: El juego no contendrá sonidos o imágenes capaces de asustar a los más pequeños. Tampoco contendrá lenguaje inapropiado, es decir, lo que se mostrará dentro de la aplicación deberá contener un lenguaje sano para todas las edades, esto involucra: texto en la interfaz, texto de los personajes no jugables (NPCs), etc.

- RF-003: El programa debe de permitir a los usuarios crear un perfil local, en donde, se guarde el progreso, tanto como logros y puntuaciones  previamente obtenidas al jugar.

- RF-004: Contará con un algoritmo que modifique la complejidad y diseño del nivel, para que este sea más inmersivo y menos repetitivo.  Funcionando en base a como se desempeñe el usuario en el transcurso del programa.

- RF-005: El juego debe permitir al usuario pausar y reanudar la partida en cualquier momento con solo presionar un botón en la pantalla.

- RF-006: El programa debe incluir un sistema de recompensas que permita a los usuarios obtener monedas o puntos por completar rutas. Estos puntos podrán ser usados para desbloquear nuevas zonas o vehículos.

- RF-007: El usuario podrá seleccionar entre distintas zonas del mapa para completar rutas, obteniendo recompensas o puntos de experiencia al finalizar con éxito.  

- RF-008: El juego debe permitir a los jugadores comparar sus puntuaciones y tiempos con los de otros usuarios, mostrando un ranking global, por región o amigos.

- RF-009: El programa contara con un sistema de horario interno de 24 horas para los niveles, siendo 1 hora en el juego equivalente a 30 segundos en la vida real, es decir que un dia en el juego consta de 12 minutos en la vida real

- RF-010: El programa mostrara un apartado llamado Tienda en el cual se podra comprar las diferentes zonas o vehiculos, usando las monedas recolectadas en los niveles

- RF-011: El juego tendrá una interfaz gráfica que permitirá al usuario navegar entre el perfil, la tienda o la selección de niveles.

- RF-012: El juego contará con un apartado de configuraciones donde podrá modificar el volumen de la música y efectos de sonido.

- RF-013: El juego contará con música y efectos de sonido que se reproduciran durante su partida.  
 
- RF-014: El usuario podrá agregar como amigos a otros usuarios que tengan creado un perfil dentro del juego.

- RF-015: El programa permitira cambiar el color del fondo entre blanco, gris y negro.

- RF-016: El juego contara con un apartado donde se puedan consultar las estadisticas del jugador (partidas totale, partidas jugadas, horas de juego, monedas totales recolectadas)

- RF-017: El juego debe permitir al usuario reiniciar un nivel en cualquier momento desde el menú de pausa, para que pueda intentarlo de nuevo sin necesidad de salir al menú principal.

- RF-018: El juego debe incluir una opción para restablecer la configuración predeterminada en el menú de ajustes, permitiendo al usuario volver a los valores originales de sonido y brillo fácilmente.

# No funcionales

- RNF-001: La clasificación del juego debe ser para todas las edades "E".

- RNF-002: El programa debe de ser capaz de soportar elementos del juego mostrados simultáneamente, en este caso, 26 objetos (camiones) sin que el rendimiento sea por debajo de 60 FPS.

- RNF-003: El programa únicamente se ejecutara en sistemas operativos Android.

- RNF-004: El programa debe de desempeñarse correctamente con los requerimientos mínimos, es decir, en sistemas (smartphone) con un procesador Qualcomm Snapdragon 765, 2 GB de RAM y que cuenten con 350 MB de almacenamiento.

- RNF-005: El tiempo de carga inicial del juego no debe exceder los 5 segundos en dispositivos que cumplan con los requisitos mínimos

- RNF-006: El programa debe ser capaz de ejecutarse en varios idiomas, siendo los principales español e inglés, pero con opción de agregar otros idiomas en el futuro.

- RNF-007: La información del usuario, como credenciales y progreso en el juego, debe estar protegida mediante encriptación, garantizando la seguridad y privacidad.

- RNF-008: El programa debe adaptarse a diferentes tamaños de pantalla y resoluciones, garantizando una experiencia optima tanto en smarphones de gama baja como en tablets de mayor capacidad.

- RNF-009: El programa contara con actualizaciones en un plazo de tiempo medio, siendo aproximadamente de 1 a 3 meses, variando en la cantidad cambios que se hagan, como la solucion a futuros errores que se puedan presentar como nuevo contenido para el juego.

- RNF-010: La interfaz gráfica de usuario deberá estar adaptada para uso táctil. 

- RNF-011: El juego permitirá agregar como amigos a un máximo de 25 perfiles. 

- RNF-012: El juego no contará con microtransacciones a través de la aplicación.

- RNF-013: El juego será compatible con versiones de Sistema Operativo Android 6.0 y posteriores.

- RNF-014: El juego sera capa de escalar copn la pantalla del sipositivo para evitar franjas negras en los bordes.

- Rnf-015: El juego no debera de necesitar internet para inicalizar.

- RNF-016: El juego debe poder activar o desactivar la música y efectos de sonido desde el menú de configuración.

- RNF-017: El juego debe permitir al usuario ajustar el brillo de la pantalla dentro de la aplicación para mejorar la visibilidad en diferentes condiciones de luz. 
</div>
