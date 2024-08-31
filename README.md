# Universidad Peruana de Ciencias Aplicadas



  <img src="https://hackmd.io/_uploads/ryJoz7YcR.png" alt="Logo" />



  **SI729 Desarrollo de Aplicaciones Open Source** <br>
    **Sección: WS53**<br>
    **Carrera: Ingeniería de Software**<br>
    **Ciclo: 5-6**<br>
    **Profesor:**<br>
    **Juan Antonio Flores Moroco**<br>
    **"Informe de Trabajo Final"**<br>
    **Tema: SphereHub**<br>
    **Producto: BookSphere**<br>
    **Agosto 2024**<br>

**Integrantes:**


- Gómez Vallejos Sergio André - U20221D401
- Salon Puerta Merly - U20201B772
- Romero Qwistgaard, Russell Stephen - U20211043
- Nanfuñay Liza, Pedro Jesús - U202215462
- Fabian Puente, Ronaldo Macedonio - U20201B193


<p style="text-align: center;">
  <strong>Registro de versiones de informe:</strong><br>
</p>



| Entregables  | Fecha | Autor | Descripción de modificación |
|-----------|-----------|-----------|-----------|
| TB1| 03/08/2024 | Sergio André Gómez Vallejos | Implementación de contenido en el Student Outcome <br> Registrar las entrevistas<br> Desarrollo del Contenido II<br> Competidores<br> User Journey Mapping <br> Perfil de integrante <br> Desarrollar el Capitulo IV <br> Implementar en el Capitulo V|
| TP | Fila 2, Columna 2 | Fila 2, Columna 3 | Fila 2, Columna 4 |
| TB2 | Fila 3, Columna 2 | Fila 3, Columna 3 | Fila 3, Columna 4 |
| TF | Fila 4, Columna 2 | Fila 4, Columna 3 | Fila 4, Columna 4 |


**Project Report Collaboration Insights**

### URL del Repositorio 
https://github.com/orgs/BookSphere-SH/repositories




<p style="text-align: center; font-weight: bold;">
 #Tabla de contenido
  
</p>

1. [CAPÍTULO I: Introducción](#CAPÍTULO-I-Introducción)<br>
      1.1. [Startup Profile](#Startup-Profile)<br>
      1.1.1. [Descripción de la Startup](#Descripción-de-la-Startup)<br>
      1.1.2. [Perfiles de integrantes del equipo](#Perfiles-de-integrantes-del-equipo)<br>
   1.2. [Solution Profile](#Solution-Profile)<br>
      1.2.1. [Antecedentes y problemática](#Antecedentes-y-problemática)<br>
      1.2.2. [Lean UX Process](#Lean-UX-Process)<br>
             1.2.2.1 [Lean UX Problem Statements](#Lean-UX-Problem-Statements)<br>
             1.2.2.2 [Lean UX Assumptions](#Lean-US-Assumptions)<br>
             1.2.2.3 [Lean UX Hypothesis Statements](#Lean-UX-Hypothesis-Statements)<br>
             1.2.2.4 [Lean UX Canvas](#Lean-UX-Canvas) <br>
1.3. [Segmentos objetivo](#Segmentos-objetivo) <br>
2. [CAPÍTULO II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation--Analysis) <br>
   2.1. [Competidores](#Competidores) <br>
      2.1.1. [Análisis competitivo](#Análisis-competitivo) <br>
      2.1.2. [Estrategias y tácticas frente a competidores](#Estrategias-y-tácticas-frente-a-competidores) <br>
   2.2. [Entrevistas](#Entrevistas) <br>
      2.2.1. [Diseño de entrevistas](#Diseño-de-entrevistas) <br>
      2.2.2. [Registro de entrevistas](#Registro-de-entrevistas)<br> 
      2.2.3. [Análisis de entrevistas](#Análisis-de-entrevistas)<br> 
   2.3. [Needfinding](#Needfinding) <br>
      2.3.1. [User Personas](#User-Personas) <br>
      2.3.2. [User Task Matrix](#User-Task-Matrix) <br>
      2.3.3. [User Journey Mapping](#User-Journey-Mapping) <br>
      2.3.4. [Empathy Mapping](#Empathy-Mapping) <br>
      2.3.5. [As-is Scenario Mapping](#As-is-Scenario-Mapping) <br>
   2.4. [Ubiquitous Language](#Ubiquitous-Language) <br>
3. [CAPÍTULO III: Requirements Specification](#Capítulo-III-Requirements-Specification) <br>
   3.1. [To-Be Scenario Mapping](#To-Be-Scenario-Mapping) <br>
   3.2. [User Stories](#User-Stories) <br>
   3.3. [Impact Mapping](#Impact-Mapping) <br>
   3.4. [Product Backlog](#Product-Backlog) <br>
4. [CAPÍTULO IV: Product Design](#Capítulo-IV-Product-Design) <br>
   4.1. [Style Guidelines](#Style-Guidelines) <br>
      4.1.1. [General Style Guidelines](#General-Style-Guidelines) <br>
      4.1.2. [Web Style Guidelines](#Web-Style-Guidelines) <br>
   4.2. [Information Architecture](#Information-Architecture) <br>
      4.2.1. [Organization Systems](#Organization-Systems) <br>
      4.2.2. [Labeling Systems](#Labeling-Systems) <br>
      4.2.3. [SEO Tags and Meta Tags](#SEO-Tags-and-Meta-Tags) <br>
      4.2.4. [Searching Systems](#Searching-Systems) <br>
      4.2.5. [Navigation Systems](#Navigation-Systems) <br>
   4.3. [Landing Page UI Design](#Landing-Page-UI-Design) <br>
      4.3.1. [Landing Page Wireframe](#Landing-Page-Wireframe) <br>
      4.3.2. [Landing Page Mock-up](#Landing-Page-Mock-up) <br>
   4.4. [Web Applications UX/UI Design](#Web-Applications-UX-UI-Design) <br>
      4.4.1. [Web Applications Wireframes](#Web-Applications-Wireframes) <br>
      4.4.2. [Web Applications Wireflow Diagrams](#Web-Applications-Wireflow-Diagrams) <br>
      4.4.3. [Web Applications Mock-ups](#Web-Applications-Mock-ups) <br>
      4.4.4. [Web Applications User Flow Diagrams](#Web-Applications-User-Flow-Diagrams) <br>
   4.5. [Web Applications Prototyping](#Web-Applications-Prototyping) <br>
   4.6. [Domain-Driven Software Architecture](#Domain-Driven-Software-Architecture) <br>
      4.6.1. [Software Architecture Context Diagram](#Software-Architecture-Context-Diagram) <br>
      4.6.2. [Software Architecture Container Diagrams](#Software-Architecture-Container-Diagrams) <br>
      4.6.3. [Software Architecture Components Diagrams](#Software-Architecture-Components-Diagrams) <br>
   4.7. [Software Object-Oriented Design](#Software-Object-Oriented-Design) <br>
      4.7.1. [Class Diagrams](#Class-Diagrams) <br>
      4.7.2. [Class Dictionary](#Class-Dictionary) <br>
   4.8. [Database Design](#Database-Design) <br>
      4.8.1. [Database Diagram](#Database-Diagram) <br>
5. [CAPÍTULO V: Product Implementation, Validation & Deployment](#Capítulo-V-Product-Implementation--Validation--Deployment) <br>
   5.1. [Software Configuration Management](#Software-Configuration-Management) <br>
      5.1.1. [Software Development Environment Configuration](#Software-Development-Environment-Configuration) <br>
      5.1.2. [Source Code Management](#Source-Code-Management) <br>
      5.1.3. [Source Code Style Guide & Conventions](#Source-Code-Style-Guide--Conventions) <br>
      5.1.4. [Software Deployment Configuration](#Software-Deployment-Configuration) <br>
   5.2. [Landing Page, Services & Applications Implementation](#Landing-Page--Services--Applications-Implementation) <br>
      5.2.1. [Sprint 1](#Sprint-1) <br>
         5.2.1.1. [Sprint Planning 1](#Sprint-Planning-1) <br>
         5.2.1.2. [Sprint Backlog 1](#Sprint-Backlog-1) <br>
         5.2.1.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review) <br>
         5.2.1.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review) <br>
         5.2.1.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review) <br>
         5.2.1.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review) <br>
         5.2.1.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review) <br>
         5.2.1.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint) <br>
      5.2.2. [Sprint 2](#Sprint-2) <br>
         5.2.2.1. [Sprint Planning 2](#Sprint-Planning-2) <br>
         5.2.2.2. [Sprint Backlog 2](#Sprint-Backlog-2) <br>
         5.2.2.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-2)<br> 
         5.2.2.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-2) <br>
         5.2.2.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-2) <br>
         5.2.2.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-2) <br>
         5.2.2.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-2) <br>
         5.2.2.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-2) <br>
      5.2.3. [Sprint 3](#Sprint-3) <br>
         5.2.3.1. [Sprint Planning 3](#Sprint-Planning-3) <br>
         5.2.3.2. [Sprint Backlog 3](#Sprint-Backlog-3) <br>
         5.2.3.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-3) <br>
         5.2.3.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-3) <br>
         5.2.3.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-3) <br>
         5.2.3.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-3) <br>
         5.2.3.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-3) <br>
         5.2.3.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-3) <br>
   5.3. [Validation Interviews](#Validation-Interviews) <br>
     5.3.1. [Diseño de Entrevistas](#Diseño-de-Entrevistas) <br>
     5.3.2. [Registro de Entrevistas](#Registro-de-Entrevistas) <br>
     5.3.3. [Evaluaciones según heurísticas](#Evaluaciones-según-heurísticas) <br>
   5.4. [Video About-the-Product](#Video-About-the-Product) <br>
[Conclusiones](#Conclusiones) <br>
[Conclusiones y recomendaciones](#Conclusiones-y-recomendaciones) <br>
[Video About-the-Team](#Video-About-the-Team) <br>
[Bibliografía](#Bibliografía) <br>
[Anexos](#Anexos) <br>

  
 
   # STUDENT OUTCOME
El curso contribuye al cumplimiento del Student Outcome ABET: 
##### ABET – EAC - Student Outcome 3 
Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3. 

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|-------------------------|------------------------|------------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. |                        |                  |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. |                        |                  |
# CAPÍTULO I: Introducción
## Startup Profile
### Descripción de la Startup
#### Descripción General:
<div style="text-align: justify">
SphereHub es nuestra empresa innovadora que une la pasión por la lectura y la tecnología con el objetivo de transformar la manera en que las personas acceden a los libros y materiales educativos. Al igual que Steam revolucionó la distribución de videojuegos, BookSphere nuestro producto, busca convertirse en la plataforma de referencia para el acceso y la exploración de libros, audiolibros, y recursos de estudio en formato digital.
<div/>

Nuestra plataforma principal, BookSphere, permite a los usuarios explorar una vasta colección de libros y audiolibros, acceder a reseñas, y visualizar información detallada antes de decidir qué leer. BookSphere no solo es un lugar para descubrir nuevos títulos, sino también para sumergirse en el contenido de una manera interactiva y personalizada.

#### Colaboraciones Estratégicas:
En BookSphere, estamos comprometidos a establecer sólidas alianzas con editoriales, autores independientes, e instituciones educativas. Trabajamos en estrecha colaboración con ellos para garantizar que nuestros usuarios tengan acceso a una biblioteca digital en constante expansión, donde se destacan tanto las obras clásicas como las contemporáneas. Invitamos a los autores y las editoriales a cargar versiones digitales de sus libros y otros materiales educativos, enriqueciendo nuestra plataforma y ampliando las opciones disponibles para los lectores.

#### Innovación y Tecnología:
Nuestra plataforma utiliza tecnologías avanzadas para ofrecer una experiencia inmersiva a los usuarios. Desde la capacidad de visualizar adelantos y reseñas en formato interactivo hasta la personalización del contenido basado en los intereses del usuario, BookSphere busca redefinir la forma en que las personas interactúan con los libros y el conocimiento. Queremos que cada usuario se sienta como un explorador en un vasto universo literario, con acceso inmediato a los recursos que necesita para aprender, crecer y disfrutar.

#### Comunidad y Funciones Sociales:
BookSphere no es solo una plataforma para leer y aprender; es también un espacio social donde los usuarios pueden conectarse con otros lectores, compartir opiniones, y descubrir nuevas perspectivas. La plataforma incluye funciones de red social que permiten a los usuarios dejar comentarios y reseñas, participar en discusiones sobre libros, y seguir a otros miembros de la comunidad con intereses similares. Esta característica fomenta la creación de una comunidad vibrante y comprometida, donde los lectores pueden intercambiar ideas y recomendaciones, creando un ambiente enriquecedor y colaborativo.

#### Visión:
Visualizamos un mundo donde la tecnología y la lectura se fusionan para crear experiencias enriquecedoras y accesibles para todos. Nuestro objetivo es que BookSphere sea sinónimo de innovación en el mundo de la literatura y la educación, un lugar donde los usuarios puedan descubrir y disfrutar de libros y materiales educativos de manera más intuitiva y conectada. Aspiramos a crear una sociedad donde el conocimiento esté al alcance de todos, y donde el acceso a los recursos educativos sea tan sencillo y emocionante como explorar una biblioteca infinita.

#### Misión:
Nos esforzamos por proporcionar una plataforma que conecte a los lectores y estudiantes con una vasta colección de recursos educativos a través de una experiencia digital avanzada. Estamos decididos a utilizar la tecnología para generar un impacto positivo en el acceso al conocimiento y la educación. BookSphere será símbolo de pasión por la lectura, innovación en la distribución de libros, y compromiso con el aprendizaje continuo, mientras fomentamos una comunidad activa y participativa en torno a la literatura y el conocimiento.


### Perfiles de integrantes del equipo
| Integrante | Descripción |
| ---- | --- |
| ![Sergio](https://hackmd.io/_uploads/SkU_5d9cR.png) | Sergio André Gómez Vallejos – Ingeniería de Software – u20221d401 <br> Soy una persona resiliente que, sin importar cuántas veces caiga, siempre encuentra la manera de levantarse. Tengo habilidades sociales sólidas y una amplia experiencia en la resolución de problemas de código. Suelo ser el miembro más activo de mi equipo de trabajo. Me apasionan los lenguajes de programación y la tecnología, y constantemente me esfuerzo por alcanzar mis objetivos y contribuir al desarrollo del startup. |
| ![fotoperfilMerly](https://hackmd.io/_uploads/H1jAVj9cA.jpg) | Merly Salon Puerta – Ingeniería de Software – U20201b772 <br>A lo largo de mi vida he adquirido diversos valores éticos los cuales son la base en todas las áreas de mi vida. Estoy comprometida a aportar de diversas formas para el desarrollo del proyecto con mucho optimismo y entusiasmo. Participaré activamente en las actividades grupales para culminar el proyecto de manera satisfactoria. |
| ![FotoPerfil4](https://hackmd.io/_uploads/rJGKndc5A.jpg) | Pedro Jesús Nanfuñay Liza - Ingeniería de Software - U202215462<br>Me considero una persona responsable y perseverante, siempre dispuesto a participar y colaborar con mi equipo. Cuento con conocimientos en varios lenguajes de programación y una fuerte pasión por investigar y conocer el desarrollo de las nuevas tecnologías. Mi objetivo es culminar este proyecto de manera satisfacoria.|
| ![Captura de pantalla 2024-08-15 121605](https://hackmd.io/_uploads/ByWzO2icC.png)| Russell Stephen Romero Qwistgaard - Ingeniería de Software - U202211043 <br> Tengo 19 y estudió la carrera de ingeniería de software, actualmente en el 5 ciclo de esta. Me apasiona crear programas en entornos distintos para poder ampliar mi conocimiento en las muchas áreas que dependen de mi formación. Estoy dispuesto a cooperar y ser puntual en mis trabajos individuales y grupales. |
|![Ronaldo](https://hackmd.io/_uploads/BJXwMC1sR.jpg)|Ronaldo Macedonio Fabian Puente - Ingeniería de Software - U20201b193<br>Me comprometo a desarrollar el trabajo en equipo hasta completar los objetivos planteados.|
## Solution Profile
### Antecedentes y problemática
#### Antecedentes
###### **WHO?**
SphereHub es una empresa que está posicionada para revolucionar la manera en que las personas acceden a los libros y materiales educativos en formato digital. Está dirigida tanto a lectores apasionados como a estudiantes, autores independientes, editoriales y a instituciones educativas.

###### **WHAT?**
BookSphere busca convertirse en la plataforma de referencia para la exploración y acceso a libros, audiolibros, y recursos educativos digitales. A través de su innovadora plataforma, los usuarios pueden explorar una amplia variedad de contenidos literarios y educativos, acceder a reseñas detalladas, y sumergirse en una experiencia de lectura personalizada e interactiva.

###### **WHERE?**
La plataforma de BookSphere opera principalmente en el entorno digital, lo que le permite llegar a usuarios globalmente. Aunque se enfoca en mercados donde el acceso a recursos educativos y libros digitales está creciendo, su visión es convertirse en una plataforma globalmente reconocida y utilizada.

###### **WHEN?**
La necesidad de una plataforma como BookSphere surge en un contexto donde la digitalización de contenidos ha transformado muchas industrias, incluyendo la literaria y educativa. Con el aumento del uso de dispositivos digitales para el consumo de medios y la creciente demanda de acceso flexible a recursos educativos, el momento actual es ideal para la implementación de una solución como BookSphere.

###### **WHY?**
La misión de BookSphere es democratizar el acceso al conocimiento y la educación, haciendo que sea tan sencillo y emocionante como explorar una biblioteca infinita. En un mundo donde la educación es clave para el desarrollo personal y profesional, BookSphere busca eliminar las barreras al acceso a los libros y materiales educativos, brindando a los usuarios una experiencia inmersiva y personalizada.

###### **HOW?**
BookSphere utiliza tecnología avanzada para ofrecer una plataforma que no solo permite la descarga y lectura de libros, sino que también incluye funciones interactivas como adelantos de contenido, personalización de recomendaciones, y un espacio social donde los usuarios pueden compartir opiniones y participar en discusiones sobre literatura y educación.

###### **HOW MUCH?**
El costo de implementación y desarrollo de la plataforma es significativo debido a la necesidad de integrar tecnología avanzada y establecer alianzas estratégicas con autores, editoriales, y otras entidades. Sin embargo, los beneficios potenciales en términos de expansión del acceso al conocimiento y la creación de una comunidad lectora activa justifican esta inversión.

#### Problemática
###### **WHO?**
Los principales afectados por la falta de una plataforma como BookSphere son los lectores y estudiantes que buscan acceso a una amplia gama de recursos literarios y educativos, pero enfrentan barreras debido a la disponibilidad limitada, los altos costos de los libros físicos, o la falta de interactividad en las plataformas actuales.

###### **WHAT?**
La problemática radica en la falta de una plataforma digital centralizada y accesible que combine una extensa biblioteca de recursos educativos y literarios con tecnologías interactivas que mejoren la experiencia del usuario. A pesar de la digitalización, muchas plataformas existentes carecen de un enfoque integral que ofrezca una experiencia personalizada y socialmente conectada.

###### **WHERE?**
La necesidad se siente a nivel global, pero es más acentuada en regiones donde el acceso a libros y recursos educativos es limitado, ya sea por restricciones económicas, geográficas o tecnológicas.

###### **WHEN?**
El problema es especialmente relevante en la era actual, donde el aprendizaje continuo y el acceso a la información son cruciales para el éxito personal y profesional. Sin una plataforma como BookSphere, el acceso al conocimiento se mantiene fragmentado y desigual.

###### **WHY?**
La falta de acceso adecuado a recursos educativos y literarios limita las oportunidades de aprendizaje y crecimiento personal. Además, la ausencia de una plataforma que combine funcionalidad, accesibilidad y una experiencia de usuario envolvente perpetúa la desconexión entre el contenido educativo disponible y los usuarios que más lo necesitan.

###### **HOW?**
Actualmente, la mayoría de las plataformas digitales están fragmentadas en términos de funcionalidad y acceso, con muchas enfocadas únicamente en la venta de libros sin considerar la experiencia integral del usuario o la creación de comunidades de lectores. Esto crea una brecha en la cual los usuarios no pueden disfrutar plenamente de los beneficios de la digitalización.

###### **HOW MUCH?**
La falta de acceso a una plataforma como BookSphere puede resultar en un costo significativo para los usuarios en términos de oportunidades educativas perdidas, el tiempo invertido en buscar recursos dispersos, y la falta de una comunidad de apoyo para compartir y discutir conocimientos.
### Lean UX Process
#### Lean UX Problem Statements
1. El mercado de libros en línea no ha logrado una adecuada centralización ni expansión en los últimos años, lo que ha limitado la efectividad de las plataformas actuales para construir una comunidad activa. Esto ha provocado una desconexión tanto entre los consumidores, que muestran poco interés en utilizar estas plataformas de manera seguida, como entre los autores, que se sienten desincentivados para publicar sus obras en este entorno.
2. Autores sin recursos que intentan publicar sus trabajos no la tienen fácil, pues requieren de contratar a un publisher para poder anunciar sus obras en masa y esto no es del todo accesible para ellos.
3. Las plataformas existentes a menudo carecen de herramientas efectivas para la promoción y visibilidad de nuevas obras, lo que limita la capacidad de los autores para llegar a su audiencia objetivo y obtener reconocimiento.
4. Los lectores a menudo enfrentan dificultades para descubrir nuevos títulos que se alineen con sus intereses específicos debido a la falta de recomendaciones personalizadas y sistemas de filtrado efectivos en las plataformas actuales.
5. La gestión de derechos de autor y licencias es un proceso complejo y opaco para muchos autores, lo que dificulta la protección de sus obras y la maximización de sus ingresos.
6. Las plataformas de libros digitales actuales no siempre ofrecen una experiencia de usuario coherente y fluida, lo que puede resultar en una navegación confusa y una baja retención de usuarios.
7. La interacción entre autores y lectores es limitada en las plataformas existentes, lo que impide la creación de una comunidad comprometida y la retroalimentación valiosa para la mejora continua de las obras.
8. Los autores independientes tienen dificultades para acceder a datos analíticos detallados sobre el rendimiento de sus publicaciones, lo que les impide tomar decisiones informadas sobre estrategias de marketing y ajustes de contenido.
9. Muchas plataformas de libros digitales no proporcionan suficientes recursos y soporte para ayudar a los autores a mejorar sus habilidades de auto-publicación y marketing, dejándolos en desventaja frente a los autores establecidos que cuentan con apoyo editorial.
#### Lean UX Assumptions
1. Si una solución se llevara a cabo, debe ser bien modelada para los gustos del público objetivo y requerir un buen mantenimiento para garantizar una experiencia de usuario positiva.
2. Los componentes incluidos deben centrarse en el objetivo principal sin desviarse en ningún momento durante su uso.
3. La plataforma debe ofrecer una interfaz intuitiva y fácil de usar para autores y lectores por igual, facilitando la integración de nuevas funcionalidades.
4. La solución debe permitir la colaboración efectiva entre autores y lectores, fomentando la creación de una comunidad activa.

#### Lean UX Hypothesis Statements
1. Creemos que, para lograr nuestro objetivo, es necesario desarrollar una aplicación que combine todas las funcionalidades de los actuales sitios de venta de libros, incorporando además nuevas características que los usuarios aprovecharán para mejorar su experiencia, como la personalización de contenido y funciones sociales interactivas.
2. También consideramos que es necesario desarrollar una herramienta que comunique y respalde las necesidades de los usuarios, proporcionando soporte y recursos para la auto-publicación y promoción, así como una plataforma que permita a los autores gestionar sus derechos y licencias de manera eficiente.
3. Suponemos que al ofrecer una plataforma que simplifique la publicación y distribución de obras para autores independientes, y que al mismo tiempo permita una interacción significativa con los lectores, se podrá aumentar el interés y la participación en el mercado de libros digitales.
4. Asumimos que la integración de funcionalidades que promuevan la colaboración entre autores y lectores, así como la inclusión de herramientas analíticas para medir el impacto y el rendimiento de las publicaciones, contribuirá al éxito y sostenibilidad de la plataforma.

#### Lean UX Canvas
![Captura de pantalla 2024-08-19 054506](https://hackmd.io/_uploads/r1RqfoeoR.png) 
### Segmentos objetivo
#### 1. Lectores Ávidos Particulares o Estudiantes:

Este segmento objetivo abarca a lectores apasionados y estudiantes que buscan acceder a una amplia variedad de libros y audiolibros, ya sea por interés personal o para cumplir con sus obligaciones académicas. Estos usuarios valoran la accesibilidad, la diversidad de títulos, y la posibilidad de personalizar su experiencia de lectura. Además, están interesados en interactuar con otros lectores a través de reseñas y comunidades en línea que enriquecen su experiencia literaria.


#### 2. Autores:
El segundo segmento objetivo incluye a autores independientes que desean distribuir sus obras o recursos educativos de manera más eficiente y llegar a un público más amplio. Estos autores valoran una plataforma que les permita gestionar sus contenidos de forma digital y mantener un control sobre su distribución, con la posibilidad de obtener ingresos a través de suscripciones o ventas directas. Además, les interesa participar en una comunidad donde puedan interactuar con lectores, recibir feedback, y promover sus obras.



####  Variable geográfica:

País: Perú
Ciudad: Zonas urbanas y suburbanas

#### Variable demográfica:

Género: Femenino / Masculino
Ocupación: Estudiantes, lectores, editores, autores independientes
Estado civil: Todos los estados
Edad y etapa del ciclo de vida: Ciudadanos mayores de 15 años

#### Variable psicográfica:

Nivel Socioeconómico (NSE): Todos los niveles socioeconomicos
Características de personalidad: Curiosidad, deseo de aprendizaje continuo, aprecio por la lectura, compromiso con la educación y el desarrollo personal.

# Capítulo II: Requirements Elicitation & Analysis
## Competidores
BookSphere enfrenta competencia de plataformas como Google Play Books, Audible y Scribd. Google Play Books proporciona una amplia gama de libros electrónicos y audiolibros, pero carece de una componente social. Audible, especializado en audiolibros, ofrece una gran biblioteca y buena integración con dispositivos Amazon, aunque no cuenta con funciones comunitarias. Scribd ofrece acceso ilimitado a diversos contenidos digitales bajo suscripción, pero su interacción social es limitada. A diferencia de estos competidores, BookSphere destaca por integrar una comunidad literaria activa, permitiendo a los usuarios compartir reseñas y participar en discusiones, lo que enriquece la experiencia del usuario.
## Análisis Competitivo
<table>
   <tr>
      <td align="center" colspan="6">Competitive Analysis Landscaspe</td>
   </tr>
   <tr>
      <td colspan="2">¿Porqué llevar a cabo este análisis?</td><td colspan="4">¿Cómo podemos proporcionar un buen servicio entre los restaurantes y los consumidores de manera que la comunicación entre ambos sea efectiva y agradable?</td>
   </tr>
   <tr align="center">
      <td colspan="2"><td>SphereHub<br><img src="https://hackmd.io/_uploads/S15TtAi90.jpg" alt="Google Play Books" style="max-width: 80px;"/></td><td>Google Play Books<br><img src="https://hackmd.io/_uploads/SkbrwAo5A.jpg" alt="Google Play Books" style="max-width: 80px;"/></td><td>Audible<br><img src="https://hackmd.io/_uploads/S191dAo5C.png" alt="Audible" style="max-width: 80px;"/></td><td>Scribd<br><img src="https://hackmd.io/_uploads/SJ4_u0i9R.png" alt="Audible" style="max-width: 90px;"/></td>
   </tr>




   <tr>
      <td rowspan="2">Perfil</td><td>Overview</td><td> SphereHub es una empresa emergente que, a través de BookSphere, busca revolucionar el acceso a libros y recursos educativos digitales. Integrando una experiencia inmersiva y social, BookSphere se posiciona como una plataforma integral para estudiantes y lectores que desean descubrir, interactuar y compartir conocimientos.	 </td><td>Google Play Books ofrece un extenso catálogo de libros digitales y audiolibros, con opciones de compra y alquiler directamente en la plataforma de Google.</td><td> Audible, una subsidiaria de Amazon, se especializa en audiolibros y contenido de audio, ofreciendo una vasta colección de títulos y suscripciones.</td><td> Scribd es un servicio de suscripción que ofrece acceso a una vasta biblioteca digital de libros, audiolibros, documentos y más. Su modelo de suscripción todo en uno lo convierte en una opción popular para consumidores de contenido digital. </td>
   </tr>
   <tr>
      <td>Ventaja competitiva. ¿Qué valor ofrece a los clientes?</td><td> BookSphere se diferencia por combinar el acceso a libros con una comunidad interactiva, similar a la experiencia de Steam, donde los usuarios pueden dejar reseñas, comentarios y participar en foros relacionados con la literatura.</td><td> Google Play Books ofrece una integración nativa con Android, y su modelo permite a los usuarios comprar títulos específicos sin necesidad de suscripción.</td><td> Audible cuenta con una extensa selección de audiolibros exclusivos y la integración con dispositivos Amazon, como Alexa, lo que mejora la experiencia del usuario.	 </td><td> Scribd ofrece un acceso ilimitado a su biblioteca por una suscripción mensual, cubriendo una amplia gama de géneros y formatos.	 </td>
   </tr>
   <tr>
      <td rowspan="2">Perfil de Marketing</td><td>Mercado Objetivo</td><td>  Nos enfocamos en lectores apasionados y estudiantes que buscan una plataforma digital intuitiva para acceder a libros, audiolibros y recursos educativos. Además, nuestro objetivo es colaborar con editoriales, autores independientes e instituciones educativas que desean distribuir sus obras de manera innovadora y llegar a un público más amplio. </td><td> Usuarios de dispositivos Android que buscan conveniencia en la adquisición de contenido digital.
 </td><td> Consumidores que prefieren la experiencia auditiva para leer, incluyendo profesionales y entusiastas de la literatura.	 </td><td> Lectores generales que consumen una variedad de contenido digital, desde libros hasta revistas y documentos.	 </td>
   </tr>
   <tr>
      <td>Estrategias de Marketing</td><td> SphereHub planea enfocarse en campañas digitales dirigidas a instituciones educativas y crear alianzas estratégicas con editoriales y universidades. Además, promoverá la plataforma en redes sociales y a través de influencers literarios.	 </td><td> Google Play Books se apoya en la preinstalación en dispositivos Android y en su visibilidad dentro del ecosistema Google para llegar a un público amplio.
 </td><td> Audible invierte en campañas de marketing masivas, especialmente a través de Amazon y dispositivos Alexa, destacando su oferta de prueba gratuita y su contenido exclusivo.	 </td><td> Scribd apuesta por publicidad online y alianzas con creadores de contenido. También se enfoca en la retención mediante recomendaciones personalizadas y una experiencia sin interrupciones.	 </td>
   </tr>
   <tr>
      <td rowspan="3">Perfil de Producto</td><td>Productos & Servicios</td><td> Acceso a una amplia variedad de libros, audiolibros, y recursos educativos, junto con funcionalidades sociales para mejorar la interacción y el descubrimiento de contenido.	 </td><td> Libros digitales, audiolibros, revistas.
 </td><td> Audiolibros, podcasts, contenido exclusivo.	 </td><td> Libros, audiolibros, documentos, artículos, revistas.	 </td>
   </tr>
   <tr>
      <td>Precios & Costos</td><td> Ofreceremos un modelo flexible similar al de Steam, pero centrado en libros y audiolibros, con opciones de compra individual y suscripciones que permiten a los usuarios acceder a una vasta colección de contenido digital. </td><td> Compra individual de títulos.
 </td><td> Suscripción mensual para un crédito mensual, con opciones de compra adicional.	 </td><td> Suscripción mensual con acceso ilimitado.	 </td>
   </tr>
   <tr>
      <td>Canales de distribución (Web y/o Móvil)</td><td> Disponible en la web y como app móvil, con sincronización de progreso en múltiples dispositivos.	 </td><td> Web, iOS, Android. </td><td> Web, iOS, Android, dispositivos Alexa.	 </td><td> Web, iOS, Android, Kindle.	
 </td>
   </tr>

   <tr>
      <td rowspan="5">Análisis SWOT</td><td>Fortalezas</td><td> Comunidad interactiva, integración de funcionalidades sociales, enfoque en estudiantes y lectores serios.	 </td><td> Gran alcance y facilidad de acceso a través de dispositivos Android y Google.
 </td><td> Gran selección de contenido exclusivo y alto enfoque en la experiencia auditiva.	 </td><td> Acceso ilimitado a una biblioteca extensa por una tarifa plana.	 </td>
   </tr>
   <tr>
      <td>Debilidades</td><td> Dependencia inicial de alianzas estratégicas para construir una biblioteca robusta.	 </td><td> Competencia con otras plataformas de Google en el mismo ecosistema. </td><td> Alto costo si el usuario desea más de un libro al mes.	 </td><td> Puede saturarse el contenido debido a la amplitud de la biblioteca.	 </td>
   </tr>
   <tr>
      <td>Oportunidades</td><td> Crecimiento en el sector educativo, expansión a mercados internacionales, adopción de tecnologías emergentes.	 </td><td> Expansión en mercados donde Android es dominante. </td><td> Creciente popularidad de los audiolibros y podcasts.	 </td><td> Expansión a otros mercados verticales, como educación.	 </td>
   </tr>
   <tr>
      <td>Amenazas</td><td> Competencia fuerte en el mercado de libros digitales, barreras tecnológicas para la expansión en comunidades sin acceso a internet de alta calidad.	 </td><td> Competencia dentro del propio ecosistema de Google y otras apps con modelos más atractivos. </td><td> Nuevos jugadores en el mercado de audiolibros o cambios en las preferencias de consumo.	 </td><td> Competencia con plataformas de distribución más grandes, como Amazon.	 </td>
   </tr>

</table> 

<br/>


## Estrategias y tácticas frente a competidores
BookSphere VS Audible, Scribd, Google Play Books

### Estrategias:

Diferenciación: BookSphere se diferencia al ofrecer una plataforma interactiva que combina el acceso a libros, audiolibros y recursos educativos con características sociales, como la posibilidad de compartir reseñas, comentarios, y participar en comunidades de lectores. Esta integración de contenido y red social crea una experiencia de usuario única que no se encuentra en los competidores tradicionales.

Enfoque en el usuario: BookSphere se enfoca en entender las preferencias y comportamientos de sus usuarios, personalizando la experiencia de navegación y recomendación de libros y recursos. A través de algoritmos avanzados, la plataforma adaptará su contenido para ofrecer recomendaciones relevantes, manteniendo a los usuarios comprometidos y leales a la plataforma.

Alianzas estratégicas: BookSphere buscará establecer colaboraciones con editoriales, autores independientes y entidades educativas para expandir su catálogo digital. Además, creará alianzas con influencers y comunidades de lectores online para promover la plataforma y atraer a nuevos usuarios, generando un efecto de red que fortalezca su posición en el mercado.

### Tácticas:

Mejora tecnológica constante: BookSphere implementará mejoras continuas en su plataforma utilizando tecnologías avanzadas, como inteligencia artificial para recomendaciones personalizadas, análisis de comportamiento del usuario, y características de gamificación para fomentar la interacción dentro de la comunidad. También se actualizarán las opciones de lectura y escucha, como modos offline y sincronización entre dispositivos.

Análisis de la competencia: BookSphere realizará un análisis constante de los movimientos y estrategias de competidores como Audible, Scribd, y Google Play Books. Este análisis permitirá ajustar las tácticas de marketing y producto, asegurando que BookSphere se mantenga a la vanguardia en términos de innovación y satisfacción del usuario.

Integración de la comunidad: BookSphere se centrará en fortalecer su componente de red social, incentivando la participación de los usuarios a través de desafíos de lectura, clubes de lectura virtuales, y eventos en línea. La plataforma también ofrecerá incentivos, como acceso anticipado a nuevos títulos o descuentos en membresías, para usuarios activos y comprometidos en la comunidad.
## Entrevistas
### 1. Segmento Objetivo: Estudiantes
Nuestra plataforma, BookSphere, ha desarrollado una serie de preguntas orientadas a comprender las necesidades, experiencias y expectativas de los lectores particulares y estudiantes en relación con el acceso a libros y materiales educativos en formato digital. Sabemos que, para este segmento, la disponibilidad, el precio y la experiencia de usuario son factores clave para elegir una plataforma de lectura. Nuestro objetivo es identificar cómo BookSphere puede satisfacer estas necesidades ofreciendo una biblioteca digital completa, accesible y con funcionalidades avanzadas. Además, buscamos explorar qué características interactivas podrían enriquecer la experiencia del usuario y fomentar un entorno de aprendizaje dinámico. Con estas entrevistas, buscamos no solo validar nuestras hipótesis, sino también adaptar nuestra oferta para garantizar que los lectores encuentren en BookSphere un recurso valioso y conveniente.
    
### Preguntas Principales:
1. ¿Qué dispositivo usas principalmente para leer libros o audiolibros en formato digital?
2. ¿Qué sistema operativo prefieres para acceder a plataformas de libros digitales?
3. ¿Qué características buscas en una plataforma de libros digitales?
4. ¿Cómo sueles descubrir nuevos libros para leer?
5. ¿Qué tipo de contenidos prefieres: libros, audiolibros, o ambos?
6. ¿Qué valoras más al seleccionar un libro para leer (reseñas, recomendaciones, adelantos, etc.)?
7. ¿Cómo te gustaría que una plataforma te ayudara a organizar y gestionar tu lectura?
8. ¿Utilizas alguna plataforma actual para discutir libros con otros lectores? ¿Qué te gusta o disgusta de esa experiencia?
9. ¿Qué tan importante es para ti la personalización de las recomendaciones de libros?
10. ¿Cómo te sentirías si pudieras interactuar directamente con autores a través de una plataforma?
11. ¿Qué mejorarías en las plataformas de libros digitales que ya usas?

### 2. Segmento Objetivo: Autores
BookSphere se enfoca en facilitar la distribución y acceso a materiales educativos y libros de todo tipo a través de una plataforma digital. En este segmento, las entrevistas estarán dirigidas a comprender las expectativas y necesidades de autores independientes que desean llegar a un público más amplio mediante la digitalización y distribución de sus contenidos. Preguntaremos sobre los desafíos actuales que enfrentan en la publicación de sus libros, la facilidad para integrarse a plataformas digitales, y qué funcionalidades consideran importantes para maximizar la exposición y las ventas. Además, indagaremos sobre la disposición para colaborar con una plataforma como BookSphere, que busca ofrecer una solución centralizada y eficiente para la distribución de contenidos digitales. Con estas entrevistas, pretendemos ajustar nuestra estrategia para convertirnos en un aliado clave para los autores.
### Preguntas principales:
1. ¿Cuántas horas a la semana dedicas a escribir o leer?
2. ¿Cuántos libros has escrito o leído en el último año?
3. ¿Prefieres libros en formato digital o físico? ¿Por qué?
4. ¿Tienes alguno de tus libros en formato digital?
5. ¿Qué sistema operativo prefieres para tus tareas de escritura (Windows, macOS, Linux, Android, iOS, etc.)?
6. ¿Qué software o aplicaciones utilizas para crear o editar libros digitales?
7. ¿Qué características valoras más en una plataforma de publicación digital?
8. ¿Cómo evalúas la visibilidad y el alcance de tus libros?
8. ¿Qué funcionalidades te gustaría que una plataforma digital ofreciera para mejorar tu experiencia como escritor?
10. ¿Como escritor/a, qué importancia tiene el feedback de los lectores y la interacción con otros usuarios en la plataforma?

## Registro de entrevistas
### Segmento: Estudiantes

### Análisis de entrevistas
    
#### Entrevista 1
| **Datos del entrevistado** | 
|--------------------------|
| **Nombre:**  Maycol Jhordan Rojas Velásquez |
| **Edad:**  19 años |
| **Procedencia:**  Lima, Ate |
| ![Entrevista](/assets/Entrevista_MKL.png)|
| **Resumen:** Maicol Jhordan es un estudiante que usa libros y audiolibros digitales regularmente. Valora una amplia variedad de títulos y una interfaz intuitiva en las plataformas. Prefiere leer libros electrónicos para estudio y audiolibros para actividades mientras se desplaza. Descubre nuevos libros mediante recomendaciones personalizadas y reseñas en línea, y busca funciones como listas de lectura personalizadas y recordatorios. La personalización de recomendaciones es muy importante para él, y le gustaría poder interactuar directamente con autores. Aunque aprecia la interacción en las plataformas actuales, encuentra que la organización y la interactividad podrían mejorar. |



#### Entrevista 2
| **Datos del entrevistado** | 
|--------------------------|
| **Nombre:**  Christopher Del Carpio Arenas |
| **Edad:**  19 años |
| **Procedencia:**  Lima, Lima |
| ![Entrevista](/assets/Entrevista_Cris.png)|
| **Resumen:** Christopher prefiere usar su laptop y smartphone para leer libros digitales y audiolibros, eligiendo Windows y Android por su comodidad y variedad de aplicaciones. Valora plataformas con interfaces intuitivas, buenas recomendaciones personalizadas y una amplia biblioteca. Descubre libros a través de recomendaciones, redes sociales y reseñas, y disfruta tanto de libros digitales como de audiolibros para adaptarse a diferentes situaciones. La personalización de recomendaciones es crucial para él, y considera que interactuar con autores directamente sería enriquecedor. Mejora en accesibilidad y personalización en las plataformas existentes sería ideal. |

#### Entrevista 3
| **Datos del entrevistado** | 
|--------------------------|
| **Nombre:**  Sebastián Cosquillo |
| **Edad:**  19 años |
| **Procedencia:**  Lima, Comas |
| ![Captura Entrevista - Segmento 1](https://hackmd.io/_uploads/SJsLMuHoA.png)|
| **Resumen:** Sebastián prefiere leer libros y escuchar audiolibros en su celular con Android. Busca plataformas con una amplia variedad de títulos en español e inglés y con una interfaz fácil de usar. Descubre libros a través de recomendaciones y redes sociales, y le gusta combinar libros y audiolibros según la situación. Valora una plataforma que permita organizar su lectura, con listas personalizadas y seguimiento del progreso. También considera importante la personalización de recomendaciones y le gustaría interactuar con autores en una plataforma digital.|
 
### Segmento: Autores
#### Entrevista 1
| **Datos del entrevistado** | 
|--------------------------|
| **Nombre:**  Apaestegui Edquen Diego Sebastian |
| **Edad:**  23 años |
| **Procedencia:**  Lima, Lima |
| ![entrevista_autor_1](https://acortar.link/GlGagu)|
| **Resumen:** Sebastián Edquén destaca la importancia de la accesibilidad y la comodidad en la publicación digital, prefiriendo libros digitales por su facilidad de uso en diferentes dispositivos. Su experiencia resalta la necesidad de herramientas avanzadas de marketing y análisis en las plataformas de publicación, así como la valiosa interacción con lectores. Las funciones que faciliten la promoción y la gestión efectiva de contenidos son clave para mejorar su experiencia como autor en el entorno digital. |
#### Entrevista 2
| **Datos del entrevistado** | 
|--------------------------|
| **Nombre:**  José Manuel Qwistgaard Suárez |
| **Edad:**  63 años |
| **Procedencia:**  Lima, Lima |
| ![Captura de pantalla 2024-08-25 134512](https://hackmd.io/_uploads/ry3J3lYo0.png)|
| **Resumen:** José Manuel Qwistgaard Suárez es un excoronel de la fuerza armada del Perú, secretario técnico del consejo de minitros y un escritor. Habiendo publicdo 2 libros tanto de manera física como digital, José Qwistgaard nos relata su experiencia con el proceso de publicación así también como el proceso de marketing. También explica el cómo la conexción que tienen los autores con sus leyentes es importate para el medio. Aunque no halla tenido ningún problema con el proceso de publicación que utiliza para sus libros, si a notado un percanse al momento de anunciarlos en redes sociales, pues hay algunos como los blogs que cobran por permitir publicitar sus libros. Normalmente utiliza documentos de Word para escribir el texto y luego utilizar otros programas para la edición final, siendo la laptop su medio preferido para editar y leer libros.|

#### Entrevista 3
| **Datos del entrevistado** | 
|--------------------------|
| **Nombre:**  Milosch Perez Mendoza |
| **Edad:**  25 años |
| **Procedencia:**  Lima, San Miguel |
| ![Entrevista]( https://github.com/RonaldoFabian01/Publicrepos/blob/main/Entrevista.png?raw=true)|
| **Resumen:** Milosch Perez es un joven escritor, que tiene ciertas predilecciones por los libros en formatos digital, tanto en su lectura como su distribución, él tiene estas preferencias por qué cree que sus obras tiene más protección  debido a las leyes de derechos de autor y administra sus obras en iPad y PC. En cuanto a la redacción de sus libros, él prefiere usar Microsoft Word 365, ya que le permite redactar en simultaneo con otros autores. Le gusta leer libros digitales, y la facilidad de acceder a los libros digitales, ya que puede hacerlo desde múltiples dispositivos. El descubre nuevas obras literarias por recomendaciones y por la publicación de los autores que sigue en redes sociales. A él le gustaría que su editor de texto tuviera la funcionalidad de grabar y convertir a su voz a texto. Milosch tambien cree que el feedback y la crítica de sus lectores es muy importante, ya que le permiten conocer más a sus lectores, y considerar estas críticas en sus futuras obras.|

#### Entrevista 4
| **Datos del entrevistado** | 
|--------------------------|
| **Nombre:**  Silvia Elizabet Rojas |
| **Edad:**  38 años |
| **Procedencia:**  Lima, Callao |
|![Entrevista4](https://hackmd.io/_uploads/B1k5gRqs0.png)|
| **Resumen:** Silvia es licenciada en psicología y disfruta escribir con frecuencia. Su libro favorito es Viva la diferencia. Utiliza el sistema operativo Windows, y prefiere Microsoft Word y Google Docs para redactar sus textos. Silvia valora especialmente que una plataforma le facilite llegar a su público lector. Actualmente, publica sus escritos en redes sociales y le gusta recibir retroalimentación de sus lectores, ya que esto le ayuda a mejorar. Además, aprecia ver los comentarios e interacciones que sus publicaciones generan, pues le permiten evaluar si su contenido capta la atención del público.|

## Needfinding
### User Personas
#### Segmento 1: Estudiantes
![User Persona - Segmento 1](https://hackmd.io/_uploads/rkpUVuBo0.png)
#### Segmento 2: Autores
![User Persona - Segmento 2](https://hackmd.io/_uploads/HJAhOGusR.png)

Enlace de las entrevistas: https://acortar.link/Q5pT1u
### User Task Matrix


| User Task                                       | Estudiantes (Frecuencia) | Estudiantes (Importancia) | Autores (Frecuencia) | Autores (Importancia) |
|-------------------------------------------------|---------------------------|---------------------------|----------------------|-----------------------|
| Explorar Colección de Libros                   | Always                    | High                      | Sometimes            | Medium                |
| Buscar y Filtrar Libros                        | Always                    | High                      | Never                | Low                   |
| Leer Reseñas y Calificaciones                  | Sometimes                 | Medium                    | Always               | High                  |
| Leer Muestras de Libros                        | Always                    | High                      | Never                | Low                   |
| Comprar o Descargar Libros                     | Always                    | High                      | Never                | Low                   |
| Dejar Comentarios y Reseñas                    | Always                    | High                      | Never                | Low                   |
| Participar en Discusiones sobre Libros         | Always                    | High                      | Never                | Low                   |
| Seguir a Otros Usuarios                        | Sometimes                 | Medium                    | Sometimes            | Medium                |
| Cargar Libros Digitales                        | Never                     | Low                       | Always               | High                  |
| Actualizar Información del Libro               | Never                     | Low                       | Always               | High                  |
| Gestionar Perfil y Obras Publicadas            | Sometimes                 | Low                       | Always               | High                  |
| Acceder a Estadísticas de Lectura              | Sometimes                 | Low                       | Always               | High                  |
| Colaborar en Proyectos Educativos              | Never                     | Low                       | Always               | High                  |
| Gestionar Derechos y Licencias                 | Never                     | Low                       | Always               | High                  |
| Verificación y Aprobación de Contenidos        | Never                     | Low                       | Always               | High                  |






### User Journey Mapping
**Estudiantes**
![User journey map](https://hackmd.io/_uploads/SJ-6VBgiR.png)
**Autores**
![Empathy Map - Segmento 2](/assets/Customer-journey-map-1.png)
### Empathy Mapping
#### Segmento 1: Estudiantes
![Empathy Map - Segmento 1](https://hackmd.io/_uploads/HyjrSOSjA.png)
#### Segmento 2: Autores
![Empathy Map - Segmento 2](https://hackmd.io/_uploads/B1KfKzOoC.png)

### As-is Scenario Mapping

### Estudiantes


![As-Is Scenario Mapping Lectores](https://hackmd.io/_uploads/H12ulhPi0.jpg)

### Autores
    
![As-Is Scenario Mapping Autores](https://hackmd.io/_uploads/B12_lhvjR.jpg)

    


## Ubiquitous Language
**1. Avid Reader (Lector Ávido)**
Un individuo apasionado por la lectura que busca constantemente nuevos libros y contenido literario. Suelen estar muy comprometidos con comunidades y discusiones relacionadas con libros.
    
**2. Digital Library (Biblioteca Digital)**
Una colección de libros, audiolibros y otros materiales educativos disponibles en formato digital y accesibles a través de una plataforma en línea.
    
**3. Interactive Content (Contenido Interactivo)**
Contenido digital que permite a los usuarios interactuar de diversas maneras, como mediante vistas previas interactivas, elementos multimedia o características personalizadas.
    
**4. Personalized Recommendations (Recomendaciones Personalizadas)**
Sugerencias de libros o materiales educativos adaptadas a los intereses, historial de lectura o metas de aprendizaje de un individuo, a menudo generadas mediante algoritmos o preferencias del usuario.
    
**5. Content Management (Gestión de Contenidos)**
El proceso de organizar, actualizar y mantener el contenido digital en una plataforma, incluyendo la carga de nuevos materiales y la gestión de los existentes.
    
**6. User Engagement (Participación del Usuario)**
 El nivel de interacción e involucramiento que un usuario tiene con la plataforma, incluyendo actividades como la lectura, reseñas y participación en discusiones comunitarias.
    
**7. Author Interaction (Interacción con el Autor)**
La capacidad para que los usuarios se relacionen directamente con los autores a través de funciones como sesiones de preguntas y respuestas, chats en vivo o blogs de autores.
    
**8. Feedback Loop (Ciclo de Retroalimentación)**
El proceso mediante el cual se recopila la retroalimentación de los usuarios y se utiliza para mejorar la plataforma o el contenido, incluyendo reseñas y calificaciones.
    
**9. Educational Resources (Recursos Educativos)**
Materiales diseñados para apoyar el aprendizaje y la educación, como libros de texto, guías de estudio y contenido instructivo.
    
**10. Content Visibility (Visibilidad del Contenido)**
El grado en que el contenido digital es accesible y descubrible para los usuarios, influenciado por factores como la funcionalidad de búsqueda y las herramientas de promoción.
    
**11. Publisher Partnership**
Asociación con Acuerdos colaborativos entre la plataforma y las editoriales para distribuir y promover libros y materiales educativos.
    
**12. Digital Rights Management (DRM) (Gestión de Derechos Digitales)**
Tecnología y políticas utilizadas para proteger el contenido digital contra la distribución no autorizada y la piratería, asegurando que los autores y editores mantengan el control sobre su trabajo.
    
**13. Community Features (Funciones Comunitarias)**
Herramientas y funcionalidades que facilitan la interacción y el compromiso de los usuarios dentro de la plataforma, como foros de discusión, reseñas de usuarios y opciones de compartir en redes sociales.
    
**14. Platform Usability (Usabilidad de la Plataforma)**
 La facilidad con la que los usuarios pueden navegar y utilizar la plataforma, incluyendo aspectos como el diseño intuitivo, la accesibilidad y el soporte al usuario.
    
**15. Content Updates (Actualizaciones de Contenido)**
El proceso de modificar o agregar nuevas versiones de materiales digitales, incluyendo revisiones, nuevas ediciones o correcciones de contenido existente.

# Capítulo III: Requirements Specification
## To-Be Scenario Mapping
#### Leyentes
![Captura de pantalla 2024-08-27 181907](https://hackmd.io/_uploads/rkk-yJ2sA.png)
![Captura de pantalla 2024-08-27 181932](https://hackmd.io/_uploads/HkYzJy2jR.png)


#### Autores
![Captura de pantalla 2024-08-27 181647](https://hackmd.io/_uploads/By7qR0ojA.png)
![Captura de pantalla 2024-08-27 181838](https://hackmd.io/_uploads/S10C0Roo0.png)

## User Stories

| **Epic/Story ID**   | **Título**                            | **Descripción**                                                                                                                                                                         | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                                                                                                                    | **Relacionado con (Epic ID)** |
|----------|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
| Epic 1   | Registro y Acceso de Usuario          | **Como** usuario, **quiero** registrarme y acceder a mi cuenta **para** gestionar mis libros y configuraciones personales.                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                  |          |
| Story 001 | Registro de Usuario                   | **Como** nuevo usuario, **quiero** registrarme en la plataforma **para** poder acceder a mis libros y configuraciones personales.                                                   | **Scenario 1:** *Registro exitoso* <br> **Given** estoy en la página de registro <br> **When** ingreso mi información válida y envío el formulario <br> **Then** mi cuenta se crea y recibo un mensaje de confirmación. <br><br> **Scenario 2:** *Error en el registro* <br> **Given** estoy en la página de registro <br> **When** ingreso información incorrecta <br> **Then** se muestra un mensaje de error y mi cuenta no se crea. | Epic 1  |
| Story 002 | Inicio de Sesión                      | **Como** usuario registrado, **quiero** iniciar sesión **para** acceder a mi cuenta y gestionar mis libros.                                                                          | **Scenario 1:** *Inicio de sesión exitoso* <br> **Given** tengo una cuenta registrada <br> **When** ingreso mis credenciales correctas <br> **Then** accedo a mi cuenta y soy redirigido a mi panel de usuario. <br><br> **Scenario 2:** *Error en el inicio de sesión* <br> **Given** tengo una cuenta registrada <br> **When** ingreso credenciales incorrectas <br> **Then** se muestra un mensaje de error y no accedo a mi cuenta. | Epic 1  |
| Story 003 | Recuperar Contraseña                  | **Como** usuario, **quiero** recuperar mi contraseña **para** poder acceder a mi cuenta en caso de olvido.                                                                           | **Scenario 1:** *Recuperación exitosa* <br> **Given** he olvidado mi contraseña <br> **When** sigo el proceso de recuperación y creo una nueva contraseña <br> **Then** recibo una confirmación de que mi contraseña ha sido cambiada exitosamente. <br><br> **Scenario 2:** *Error en la recuperación* <br> **Given** he olvidado mi contraseña <br> **When** el proceso de recuperación falla <br> **Then** se muestra un mensaje de error. | Epic 1  |
| Epic 2   | Gestión de Biblioteca                  | **Como** usuario, **quiero** gestionar mi biblioteca **para** organizar mis libros y materiales de lectura.                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                  |          |
| Story 004 | Añadir Libros a la Biblioteca          | **Como** usuario, **quiero** añadir libros a mi biblioteca **para** tener acceso a ellos desde mi cuenta.                                                                            | **Scenario 1:** *Añadir libro exitosamente* <br> **Given** estoy en la sección de biblioteca <br> **When** selecciono un libro y lo añado a mi biblioteca <br> **Then** el libro aparece en mi biblioteca y recibo una confirmación. <br><br> **Scenario 2:** *Error al añadir libro* <br> **Given** estoy en la sección de biblioteca <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y el libro no se añade a mi biblioteca. | Epic 2  |
| Story 005 | Eliminar Libros de la Biblioteca       | **Como** usuario, **quiero** eliminar libros de mi biblioteca **para** mantenerla organizada y actualizada.                                                                           | **Scenario 1:** *Eliminar libro exitosamente* <br> **Given** tengo un libro en mi biblioteca <br> **When** selecciono el libro y elijo eliminarlo <br> **Then** el libro se elimina de mi biblioteca y recibo una confirmación. <br><br> **Scenario 2:** *Error al eliminar libro* <br> **Given** tengo un libro en mi biblioteca <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y el libro no se elimina. | Epic 2  |
| Story 006 | Buscar Libros                         | **Como** usuario, **quiero** buscar libros en mi biblioteca **para** encontrar rápidamente el material que necesito.                                                                 | **Scenario 1:** *Búsqueda exitosa* <br> **Given** estoy en la sección de búsqueda <br> **When** ingreso el título del libro y realizo la búsqueda <br> **Then** se muestran los resultados relevantes y puedo acceder al libro. <br><br> **Scenario 2:** *No se encuentra el libro* <br> **Given** estoy en la sección de búsqueda <br> **When** ingreso un título que no está en la biblioteca <br> **Then** se muestra un mensaje indicando que no se encontraron resultados. | Epic 2  |
| Epic 3   | Interacción Social y Comunidad         | **Como** usuario, **quiero** interactuar con otros usuarios **para** compartir recomendaciones y reseñas sobre libros.                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                  |          |
| Story 007 | Recomendar Libros a Otros Usuarios     | **Como** usuario, **quiero** recomendar libros a otros usuarios **para** compartir mis lecturas favoritas.                                                                          | **Scenario 1:** *Recomendación enviada exitosamente* <br> **Given** estoy en la página de un libro <br> **When** selecciono recomendar a un amigo y envío la recomendación <br> **Then** mi recomendación es enviada y el destinatario recibe una notificación. <br><br> **Scenario 2:** *Error al enviar recomendación* <br> **Given** estoy en la página de un libro <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y la recomendación no se envía. | Epic 3  |
| Story 008 | Escribir Reseñas de Libros             | **Como** usuario, **quiero** escribir reseñas de libros **para** compartir mi opinión sobre los libros que he leído.                                                                | **Scenario 1:** *Reseña enviada exitosamente* <br> **Given** he leído un libro <br> **When** escribo una reseña y la envío <br> **Then** la reseña se publica en la página del libro y otros usuarios pueden verla. <br><br> **Scenario 2:** *Error al enviar reseña* <br> **Given** he leído un libro <br> **When** ocurre un problema técnico al enviar la reseña <br> **Then** se muestra un mensaje de error y la reseña no se publica. | Epic 3  |
| Epic 4   | Funcionalidades de Adquisición        | **Como** usuario, **quiero** adquirir libros y contenidos **para** ampliar mi biblioteca personal. 
| Story 009      | Enviar Mensajes a Otros Usuarios        | **Como** usuario, **quiero** enviar mensajes a otros usuarios **para** interactuar y discutir sobre libros y temas relacionados.                                                                                           | **Scenario 1:** *Mensaje enviado exitosamente* <br> **Given** estoy en la página de mensajes <br> **When** escribo un mensaje y lo envío <br> **Then** el mensaje se envía y el destinatario recibe una notificación. <br><br> **Scenario 2:** *Error al enviar mensaje* <br> **Given** estoy en la página de mensajes <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y el mensaje no se envía. | Epic 4  |
| Story 010      | Recibir Notificaciones de Mensajes      | **Como** usuario, **quiero** recibir notificaciones cuando recibo nuevos mensajes **para** estar al tanto de las interacciones.                                                                                           | **Scenario 1:** *Notificación recibida exitosamente* <br> **Given** recibo un nuevo mensaje <br> **When** el sistema detecta el nuevo mensaje <br> **Then** recibo una notificación en mi cuenta. <br><br> **Scenario 2:** *Error en la notificación* <br> **Given** recibo un nuevo mensaje <br> **When** ocurre un problema técnico en el sistema de notificaciones <br> **Then** no recibo una notificación y el problema se informa al usuario. | Epic 4  |
 | Story 011 | Añadir Libros al Carrito              | **Como** estudiante, **quiero** añadir libros al carrito **para** revisar mi selección antes de proceder a la compra.                                                                 | **Scenario 1:** *Añadir al carrito exitosamente* <br> **Given** estoy en la página del libro <br> **When** hago clic en "Añadir al carrito" <br> **Then** el libro se añade a mi carrito de compras y recibo una confirmación. <br><br> **Scenario 2:** *Error al añadir al carrito* <br> **Given** estoy en la página del libro <br> **When** hay un problema técnico <br> **Then** se muestra un mensaje de error y el libro no se añade al carrito. | Epic 4  |
| Story 012 | Procesar Pago                        | **Como** usuario, **quiero** procesar el pago de los libros en mi carrito **para** completar la compra y obtener acceso al contenido.                                                 | **Scenario 1:** *Pago exitoso* <br> **Given** tengo libros en mi carrito <br> **When** realizo el pago con una tarjeta válida <br> **Then** la transacción se completa y recibo una confirmación del pago y acceso a los libros adquiridos. <br><br> **Scenario 2:** *Error en el pago* <br> **Given** tengo libros en mi carrito <br> **When** ocurre un problema con el pago <br> **Then** se muestra un mensaje de error y el pago no se procesa. | Epic 4  |
| Epic 5   | Personalización de Perfil              | **Como** usuario, **quiero** personalizar mi perfil **para** que mi cuenta refleje mis preferencias y estilo personal.                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                  |          |
| Story 013 | Editar Información del Perfil          | **Como** usuario, **quiero** editar mi información personal en mi perfil **para** actualizar mis datos y preferencias.                                                               | **Scenario 1:** *Edición exitosa* <br> **Given** estoy en la página de perfil <br> **When** edito mi información y guardo los cambios <br> **Then** mi perfil se actualiza con la nueva información y recibo una confirmación. <br><br> **Scenario 2:** *Error al editar perfil* <br> **Given** estoy en la página de perfil <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y mi información no se actualiza. | Epic 5  |
| Story 014 | Subir Imagen de Perfil                 | **Como** usuario, **quiero** subir una imagen de perfil **para** personalizar mi cuenta y hacerla más reconocible.                                                                    | **Scenario 1:** *Imagen subida exitosamente* <br> **Given** estoy en la página de perfil <br> **When** subo una imagen y guardo los cambios <br> **Then** la imagen se actualiza en mi perfil y recibo una confirmación. <br><br> **Scenario 2:** *Error al subir imagen* <br> **Given** estoy en la página de perfil <br> **When** ocurre un problema técnico al subir la imagen <br> **Then** se muestra un mensaje de error y la imagen no se sube. | Epic 5  |
| Story 015 | Configurar Preferencias de Notificaciones | **Como** usuario, **quiero** configurar mis preferencias de notificaciones **para** recibir solo la información que me interesa.                                                     | **Scenario 1:** *Preferencias configuradas exitosamente* <br> **Given** estoy en la página de configuraciones de notificaciones <br> **When** configuro mis preferencias y guardo los cambios <br> **Then** mis preferencias se actualizan y recibo una confirmación. <br><br> **Scenario 2:** *Error al configurar preferencias* <br> **Given** estoy en la página de configuraciones <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y las preferencias no se actualizan. | Epic 5  |
| Epic 6   | Soporte y Contacto                    | **Como** usuario, **quiero** tener acceso al soporte y contacto **para** resolver cualquier problema o pregunta que pueda tener.                                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                  |          |
| Story 016 | Enviar Consulta al Soporte             | **Como** usuario, **quiero** enviar una consulta al soporte **para** obtener ayuda con cualquier problema que enfrente.                                                              | **Scenario 1:** *Consulta enviada exitosamente* <br> **Given** estoy en la página de soporte <br> **When** envío mi consulta y recibo una confirmación <br> **Then** mi consulta es recibida y recibo una notificación de que el soporte está trabajando en ella. <br><br> **Scenario 2:** *Error al enviar consulta* <br> **Given** estoy en la página de soporte <br> **When** ocurre un problema técnico al enviar la consulta <br> **Then** se muestra un mensaje de error y la consulta no se envía. | Epic 6  |
| Story 017 | Acceder a Preguntas Frecuentes         | **Como** usuario, **quiero** acceder a una sección de preguntas frecuentes **para** encontrar respuestas a dudas comunes sin necesidad de contactar al soporte.                       | **Scenario 1:** *Acceso a preguntas frecuentes exitoso* <br> **Given** estoy en la página de preguntas frecuentes <br> **When** navego por las preguntas y respuestas <br> **Then** encuentro la información que necesito y puedo resolver mis dudas. <br><br> **Scenario 2:** *Error en la sección de preguntas frecuentes* <br> **Given** estoy en la página de preguntas frecuentes <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo acceder a la información. | Epic 6  |
| Story 018 | Enviar Comentarios sobre la Plataforma | **Como** usuario, **quiero** enviar comentarios sobre la plataforma **para** contribuir a su mejora.                                                                                | **Scenario 1:** *Comentario enviado exitosamente* <br> **Given** estoy en la página de comentarios <br> **When** envío mi comentario y recibo una confirmación <br> **Then** mi comentario es recibido y el equipo de desarrollo toma nota de mis sugerencias. <br><br> **Scenario 2:** *Error al enviar comentario* <br> **Given** estoy en la página de comentarios <br> **When** ocurre un problema técnico al enviar el comentario <br> **Then** se muestra un mensaje de error y el comentario no se envía. | Epic 6  |
| Epic 7   | Funcionalidades para Estudiantes      | **Como** estudiante, **quiero** acceder a funcionalidades específicas **para** facilitar mi experiencia académica en la plataforma BookSphere.                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                  |          |
| Story 019 | Explorar Catálogo de Libros            | **Como** estudiante, **quiero** explorar el catálogo de libros y audiolibros **para** descubrir recursos educativos relevantes.                                                        | **Scenario 1:** *Catálogo visible correctamente* <br> **Given** estoy en la página de catálogo <br> **When** navego por los títulos <br> **Then** puedo ver y explorar la colección de libros y audiolibros. <br><br> **Scenario 2:** *Error en el catálogo* <br> **Given** estoy en la página de catálogo <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo ver el catálogo. | Epic 7  |
| Story 020 | Acceder a Reseñas y Detalles           | **Como** estudiante, **quiero** acceder a reseñas y detalles de libros **para** tomar decisiones informadas sobre qué leer o estudiar.                                                 | **Scenario 1:** *Reseñas y detalles visibles* <br> **Given** estoy en la página de un libro <br> **When** consulto la sección de reseñas y detalles <br> **Then** puedo leer las reseñas y ver la información detallada del libro. <br><br> **Scenario 2:** *Error en reseñas y detalles* <br> **Given** estoy en la página de un libro <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo ver la información. | Epic 7  |
| Story 021 | Añadir Libros a Favoritos              | **Como** estudiante, **quiero** añadir libros a mis favoritos **para** tener fácil acceso a mis títulos preferidos y recomendaciones.                                                  | **Scenario 1:** *Libros añadidos a favoritos* <br> **Given** estoy en la página de un libro <br> **When** añado el libro a mis favoritos <br> **Then** el libro se guarda en mi lista de favoritos. <br><br> **Scenario 2:** *Error al añadir a favoritos* <br> **Given** estoy en la página de un libro <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y el libro no se añade a favoritos. | Epic 7  |
| Story 022 | Leer y Escuchar Adelantos              | **Como** estudiante, **quiero** leer o escuchar adelantos de libros **para** evaluar si un libro es relevante antes de decidirme a adquirirlo.                                           | **Scenario 1:** *Adelantos accesibles* <br> **Given** estoy en la página de un libro <br> **When** selecciono el adelanto <br> **Then** puedo leer o escuchar una muestra del contenido. <br><br> **Scenario 2:** *Error al acceder a adelantos* <br> **Given** estoy en la página de un libro <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo acceder al adelanto. | Epic 7  |
| Story 023 | Personalizar Recomendaciones          | **Como** estudiante, **quiero** personalizar mis recomendaciones de libros **para** recibir sugerencias basadas en mis intereses y actividades.                                          | **Scenario 1:** *Recomendaciones personalizadas* <br> **Given** estoy en la sección de recomendaciones <br> **When** personalizo mis intereses <br> **Then** recibo sugerencias basadas en mis preferencias. <br><br> **Scenario 2:** *Error en recomendaciones* <br> **Given** estoy en la sección de recomendaciones <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y las recomendaciones no se personalizan. | Epic 7  |
| Story 024 | Participar en Discusiones de Libros     | **Como** estudiante, **quiero** participar en discusiones sobre libros **para** intercambiar ideas y opiniones con otros usuarios.                                                      | **Scenario 1:** *Discusión publicada* <br> **Given** estoy en la sección de discusiones <br> **When** publico un comentario <br> **Then** mi comentario aparece en la discusión. <br><br> **Scenario 2:** *Error en discusiones* <br> **Given** estoy en la sección de discusiones <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y mi comentario no se publica. | Epic 7  |
| Story 025 | Gestionar Lista de Lectura              | **Como** estudiante, **quiero** gestionar mi lista de lectura **para** organizar mis objetivos de lectura y seguimiento.                                                                 | **Scenario 1:** *Lista de lectura gestionada* <br> **Given** estoy en mi lista de lectura <br> **When** añado o elimino un libro <br> **Then** la lista se actualiza según los cambios realizados. <br><br> **Scenario 2:** *Error al gestionar lista* <br> **Given** estoy en mi lista de lectura <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y la lista no se actualiza. | Epic 7  |
| Story 026 | Recibir Recomendaciones de Lectura     | **Como** estudiante, **quiero** recibir recomendaciones de lectura basadas en mi historial y preferencias **para** descubrir nuevos títulos que se alineen con mis intereses.        | **Scenario 1:** *Recomendaciones recibidas* <br> **Given** estoy en la sección de recomendaciones <br> **When** reviso las sugerencias <br> **Then** recibo recomendaciones que coinciden con mis intereses. <br><br> **Scenario 2:** *Error en recomendaciones* <br> **Given** estoy en la sección de recomendaciones <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no recibo recomendaciones. | Epic 7  |
| Story 027 | Acceder a Materiales de Estudio         | **Como** estudiante, **quiero** acceder a materiales de estudio adicionales **para** apoyar mi aprendizaje y profundizar en los temas.                                                   | **Scenario 1:** *Materiales accesibles* <br> **Given** estoy en la sección de materiales de estudio <br> **When** consulto los recursos <br> **Then** puedo ver y descargar los materiales disponibles. <br><br> **Scenario 2:** *Error al acceder a materiales* <br> **Given** estoy en la sección de materiales de estudio <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo acceder a los materiales. | Epic 7  |
| Story 028 | Ver Historial de Lectura                | **Como** estudiante, **quiero** ver mi historial de lectura **para** seguir mi progreso y revisar los libros que he leído anteriormente.                                                | **Scenario 1:** *Historial de lectura visible* <br> **Given** estoy en la sección de historial de lectura <br> **When** reviso mi historial <br> **Then** puedo ver todos los libros que he leído y su información. <br><br> **Scenario 2:** *Error en historial de lectura* <br> **Given** estoy en la sección de historial de lectura <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo ver el historial. | Epic 7  |
| Story 029 | Programar Recordatorios de Lectura      | **Como** estudiante, **quiero** programar recordatorios para mis lecturas **para** no olvidar los plazos y mantenerme al día con mis objetivos.                                          | **Scenario 1:** *Recordatorios programados* <br> **Given** estoy en la sección de recordatorios <br> **When** configuro un recordatorio <br> **Then** el recordatorio se guarda y recibo una notificación en la fecha establecida. <br><br> **Scenario 2:** *Error al programar recordatorio* <br> **Given** estoy en la sección de recordatorios <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y el recordatorio no se programa. | Epic 7  |
| Story 030 | Revisar Feedback de Lectores           | **Como** estudiante, **quiero** revisar el feedback de otros lectores sobre los libros **para** hacer una elección informada antes de leer o adquirir un título.                       | **Scenario 1:** *Feedback visible* <br> **Given** estoy en la página de un libro <br> **When** consulto las reseñas y comentarios <br> **Then** puedo ver el feedback de ellos.
| Epic 8   | Funcionalidades para Autores           | **Como** autor, **quiero** acceder a funcionalidades específicas **para** gestionar mis libros y conectar con la comunidad en la plataforma BookSphere.                                |                                                                                                                                                                                                                                                                                                                                                                                                                                  |          |
| Story 031 | Publicar Libros Digitales              | **Como** autor, **quiero** publicar mis libros digitales en BookSphere **para** llegar a un público más amplio y compartir mi trabajo.                                                 | **Scenario 1:** *Libro publicado correctamente* <br> **Given** estoy en la sección de publicación <br> **When** subo y configuro un libro digital <br> **Then** el libro se publica y está disponible en la plataforma. <br><br> **Scenario 2:** *Error en publicación* <br> **Given** estoy en la sección de publicación <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y el libro no se publica. | Epic 8  |
| Story 032 | Actualizar Información del Libro       | **Como** autor, **quiero** actualizar la información de mis libros **para** asegurarme de que los detalles y el contenido estén siempre actualizados.                                  | **Scenario 1:** *Información actualizada* <br> **Given** estoy en la página de gestión de libros <br> **When** actualizo la información de un libro <br> **Then** los cambios se reflejan en la plataforma. <br><br> **Scenario 2:** *Error en actualización* <br> **Given** estoy en la página de gestión de libros <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y la información no se actualiza. | Epic 8  |
| Story 033 | Gestionar Comentarios y Reseñas        | **Como** autor, **quiero** gestionar los comentarios y reseñas de mis libros **para** responder a los lectores y mejorar mi trabajo basado en sus opiniones.                           | **Scenario 1:** *Comentarios gestionados* <br> **Given** estoy en la sección de comentarios <br> **When** reviso y respondo a los comentarios <br> **Then** puedo interactuar con los lectores y gestionar las reseñas. <br><br> **Scenario 2:** *Error en gestión de comentarios* <br> **Given** estoy en la sección de comentarios <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo gestionar los comentarios. | Epic 8  |
| Story 034 | Acceder a Estadísticas de Lectura      | **Como** autor, **quiero** acceder a estadísticas sobre la lectura de mis libros **para** analizar el rendimiento y entender mejor a mi audiencia.                                      | **Scenario 1:** *Estadísticas accesibles* <br> **Given** estoy en la sección de estadísticas <br> **When** consulto los datos <br> **Then** puedo ver estadísticas sobre la lectura de mis libros. <br><br> **Scenario 2:** *Error en estadísticas* <br> **Given** estoy en la sección de estadísticas <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo acceder a las estadísticas. | Epic 8  |
| Story 035 | Promocionar Libros en la Plataforma    | **Como** autor, **quiero** promocionar mis libros en la plataforma **para** aumentar su visibilidad y atraer a más lectores.                                                           | **Scenario 1:** *Promoción visible* <br> **Given** estoy en la sección de promociones <br> **When** configuro una campaña de promoción <br> **Then** mi libro aparece en las áreas destacadas de la plataforma. <br><br> **Scenario 2:** *Error en promoción* <br> **Given** estoy en la sección de promociones <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y la promoción no se configura. | Epic 8  |
| Story 036 | Recibir Feedback de Lectores           | **Como** autor, **quiero** recibir feedback sobre mis libros **para** mejorar mis escritos y entender mejor las necesidades de mis lectores.                                          | **Scenario 1:** *Feedback recibido* <br> **Given** estoy en la sección de feedback <br> **When** consulto los comentarios y opiniones de los lectores <br> **Then** puedo leer y analizar el feedback recibido. <br><br> **Scenario 2:** *Error en feedback* <br> **Given** estoy en la sección de feedback <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo acceder al feedback. | Epic 8  |
| Story 037 | Interactuar con la Comunidad de Lectores| **Como** autor, **quiero** interactuar con la comunidad de lectores **para** participar en discusiones y eventos relacionados con mis libros.                                           | **Scenario 1:** *Interacción exitosa* <br> **Given** estoy en la sección de eventos <br> **When** participo en un evento o discusión <br> **Then** puedo interactuar con los lectores y participar activamente. <br><br> **Scenario 2:** *Error en interacción* <br> **Given** estoy en la sección de eventos <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo participar en el evento. | Epic 8  |
| Story 038 | Crear Contenido Exclusivo              | **Como** autor, **quiero** crear contenido exclusivo para mis seguidores **para** ofrecerles material adicional y fomentar su interés en mis libros.                                 | **Scenario 1:** *Contenido exclusivo disponible* <br> **Given** estoy en la sección de contenido exclusivo <br> **When** subo material adicional <br> **Then** el contenido está disponible para los seguidores. <br><br> **Scenario 2:** *Error en contenido exclusivo* <br> **Given** estoy en la sección de contenido exclusivo <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y el contenido no se publica. | Epic 8  |
| Story 039 | Gestionar Derechos de Autor            | **Como** autor, **quiero** gestionar los derechos de autor de mis libros **para** proteger mi trabajo y asegurar que se respete mi propiedad intelectual.                              | **Scenario 1:** *Derechos gestionados correctamente* <br> **Given** estoy en la sección de derechos de autor <br> **When** configuro los derechos de mi libro <br> **Then** los derechos están correctamente gestionados y protegidos. <br><br> **Scenario 2:** *Error en gestión de derechos* <br> **Given** estoy en la sección de derechos de autor <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y los derechos no se gestionan correctamente. | Epic 8  |
| Story 040 | Acceder a Información sobre Tendencias | **Como** autor, **quiero** acceder a información sobre las tendencias de lectura **para** adaptar mis escritos a los intereses actuales del público.                                   | **Scenario 1:** *Tendencias accesibles* <br> **Given** estoy en la sección de tendencias <br> **When** consulto la información sobre tendencias de lectura <br> **Then** puedo ver las tendencias actuales y adaptar mi trabajo en consecuencia. <br><br> **Scenario 2:** *Error en tendencias* <br> **Given** estoy en la sección de tendencias <br> **When** ocurre un problema técnico <br> **Then** se muestra un mensaje de error y no puedo acceder a la información sobre tendencias. | Epic 8  |



## Historias Técnicas

| **Historias técnicas ID** | **Título**                             | **Descripción**                                                                                                                                                                                                                       | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                                                       |
|--------|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| TS001  | Crear Cuenta de Usuario                | Como desarrollador, quiero que los usuarios puedan crear una cuenta en BookSphere para acceder a la plataforma y sus recursos.                                                | **Scenario 1: Registro exitoso** <br> **Given** que el endpoint "/register" está disponible <br> **When** se envía una solicitud POST con datos válidos para el registro <br> **Then** se recibe una respuesta con estado 201 Created <br> **And** el usuario tiene una cuenta activa. <br><br> **Scenario 2: Error en registro** <br> **Given** que el endpoint "/register" está disponible <br> **When** se envía una solicitud POST con datos inválidos <br> **Then** se recibe una respuesta con estado 400 Bad Request <br> **And** un mensaje de error "Email ya registrado". |
| TS002  | Iniciar Sesión                         | Como desarrollador, quiero que los usuarios puedan iniciar sesión en BookSphere usando sus credenciales para acceder a sus cuentas.                                           | **Scenario 1: Inicio de sesión exitoso** <br> **Given** que el endpoint "/login" está disponible <br> **When** se envía una solicitud POST con credenciales válidas <br> **Then** se recibe una respuesta con estado 200 OK <br> **And** un token de autenticación válido. <br><br> **Scenario 2: Error en inicio de sesión** <br> **Given** que el endpoint "/login" está disponible <br> **When** se envía una solicitud POST con credenciales inválidas <br> **Then** se recibe una respuesta con estado 401 Unauthorized <br> **And** un mensaje de error "Credenciales inválidas". |
| TS003  | Buscar Libros                         | Como desarrollador, quiero implementar una funcionalidad de búsqueda para que los usuarios puedan encontrar libros en BookSphere por título, autor o género.                   | **Scenario 1: Búsqueda exitosa** <br> **Given** que el endpoint "/search" está disponible <br> **When** se envía una solicitud GET con un criterio de búsqueda válido <br> **Then** se recibe una respuesta con estado 200 OK <br> **And** una lista de libros que coinciden con el criterio. <br><br> **Scenario 2: Búsqueda sin resultados** <br> **Given** que el endpoint "/search" está disponible <br> **When** se envía una solicitud GET con un criterio de búsqueda que no coincide con ningún libro <br> **Then** se recibe una respuesta con estado 404 Not Found <br> **And** un mensaje de error "No se encontraron libros". |
| TS004  | Agregar Libro a la Biblioteca          | Como desarrollador, quiero permitir que los administradores agreguen nuevos libros a la biblioteca de BookSphere a través de un formulario en la interfaz de usuario.         | **Scenario 1: Libro agregado exitosamente** <br> **Given** que el formulario para agregar libros está disponible <br> **When** se completa el formulario con datos válidos <br> **Then** el libro se guarda en la base de datos y es visible en la biblioteca. <br><br> **Scenario 2: Error al agregar libro** <br> **Given** que el formulario para agregar libros está disponible <br> **When** se completa el formulario con datos inválidos <br> **Then** se muestra un mensaje de error "Datos inválidos para el libro". |
| TS005  | Actualizar Información del Libro       | Como desarrollador, quiero permitir que los administradores actualicen la información de un libro existente en la biblioteca de BookSphere a través de la interfaz de usuario.                                     | **Scenario 1: Actualización exitosa** <br> **Given** que el formulario para actualizar libros está disponible <br> **When** se actualizan los datos del libro con información válida <br> **Then** la información del libro se actualiza correctamente en la base de datos. <br><br> **Scenario 2: Error en la actualización** <br> **Given** que el formulario para actualizar libros está disponible <br> **When** se actualizan los datos del libro con información inválida <br> **Then** se muestra un mensaje de error "Datos inválidos para el libro". |
| TS006  | Eliminar Libro de la Biblioteca        | Como desarrollador, quiero permitir que los administradores eliminen libros de la biblioteca de BookSphere a través de un botón en la interfaz de usuario.                                                 | **Scenario 1: Eliminación exitosa** <br> **Given** que el botón de eliminación está disponible <br> **When** se elimina un libro existente <br> **Then** el libro se borra de la base de datos y ya no está visible en la biblioteca. <br><br> **Scenario 2: Error al eliminar libro** <br> **Given** que el botón de eliminación está disponible <br> **When** se intenta eliminar un libro que no existe <br> **Then** se muestra un mensaje de error "Libro no encontrado". |
| TS007  | Gestionar Reseñas de Libros             | Como desarrollador, quiero permitir que los usuarios agreguen y gestionen reseñas de libros en BookSphere a través de la interfaz de usuario.                                                               | **Scenario 1: Reseña agregada exitosamente** <br> **Given** que el formulario para agregar reseñas está disponible <br> **When** se envía una reseña válida <br> **Then** la reseña se guarda en la base de datos y es visible en la página del libro. <br><br> **Scenario 2: Error al agregar reseña** <br> **Given** que el formulario para agregar reseñas está disponible <br> **When** se envía una reseña inválida <br> **Then** se muestra un mensaje de error "Datos inválidos para la reseña". |
| TS008  | Implementar Funcionalidad de Favoritos  | Como desarrollador, quiero que los usuarios puedan marcar libros como favoritos en BookSphere a través de la interfaz de usuario.                                                | **Scenario 1: Libro marcado como favorito** <br> **Given** que la opción para marcar favoritos está disponible <br> **When** se marca un libro como favorito <br> **Then** el libro aparece en la lista de favoritos del usuario. <br><br> **Scenario 2: Error al marcar libro como favorito** <br> **Given** que la opción para marcar favoritos está disponible <br> **When** se intenta marcar un libro como favorito pero hay un problema <br> **Then** se muestra un mensaje de error "No se pudo marcar el libro como favorito". |
| TS009  | Implementar Recomendaciones Personalizadas | Como desarrollador, quiero que BookSphere ofrezca recomendaciones personalizadas a los usuarios basadas en su historial de lectura.                                          | **Scenario 1: Recomendaciones generadas exitosamente** <br> **Given** que el sistema de recomendaciones está integrado <br> **When** un usuario accede a la sección de recomendaciones <br> **Then** se muestran recomendaciones basadas en el historial de lectura del usuario. <br><br> **Scenario 2: Error en recomendaciones** <br> **Given** que el sistema de recomendaciones está integrado <br> **When** hay un problema técnico al generar recomendaciones <br> **Then** se muestra un mensaje de error indicando que no se pueden generar recomendaciones. |
| TS010  | Implementar Funcionalidad de Filtros en Búsqueda | Como desarrollador, quiero añadir filtros a la funcionalidad de búsqueda para que los usuarios puedan refinar sus resultados de búsqueda según diferentes criterios.            | **Scenario 1: Filtros aplicados exitosamente** <br> **Given** que los filtros están implementados <br> **When** un usuario aplica filtros en la búsqueda <br> **Then** los resultados se actualizan para mostrar solo los elementos que cumplen con los criterios. <br><br> **Scenario 2: Error en aplicación de filtros** <br> **Given** que los filtros están implementados <br> **When** hay un problema técnico al aplicar los filtros <br> **Then** se muestra un mensaje de error indicando que los filtros no se pueden aplicar. |
| TS011  | Implementar Funcionalidad de Exportación de Datos | Como desarrollador, quiero permitir a los usuarios exportar datos en formatos comunes como CSV o Excel para facilitar el análisis externo.                                  | **Scenario 1: Exportación exitosa** <br> **Given** que la funcionalidad de exportación está implementada <br> **When** un usuario solicita exportar datos <br> **Then** se genera un archivo en el formato solicitado y se proporciona al usuario para descargar. <br><br> **Scenario 2: Error en exportación** <br> **Given** que la funcionalidad de exportación está implementada <br> **When** hay un problema técnico al generar el archivo <br> **Then** se muestra un mensaje de error indicando que la exportación no se pudo completar. |
| TS012  | Implementar Funcionalidad de Seguimiento de Lectura | Como desarrollador, quiero que los usuarios puedan rastrear su progreso de lectura en BookSphere para llevar un registro de los libros que están leyendo.                        | **Scenario 1: Progreso de lectura registrado exitosamente** <br> **Given** que la funcionalidad de seguimiento de lectura está implementada <br> **When** un usuario actualiza su progreso de lectura <br> **Then** el progreso se guarda en la base de datos y se muestra correctamente en la interfaz de usuario. <br><br> **Scenario 2: Error al registrar progreso de lectura** <br> **Given** que la funcionalidad de seguimiento de lectura está implementada <br> **When** hay un problema técnico al registrar el progreso <br> **Then** se muestra un mensaje de error indicando que no se pudo actualizar el progreso de lectura. |



## Impact Mapping
El impact mapping es una técnica de planificación estratégica que visualiza cómo las actividades y proyectos contribuyen a objetivos de negocio específicos. Utiliza un mapa para mostrar los impactos deseados, los actores involucrados, los objetivos a alcanzar y las entregas necesarias para lograr esos objetivos. Facilita la alineación de esfuerzos con metas estratégicas y mejora la toma de decisiones al clarificar el valor y los resultados esperados.

### Business Goal: 
 Que el 50% de los estudiantes que usen  nuestra aplicación interactúen con otros usuarios
 
 ![Impact map estudiantes](https://hackmd.io/_uploads/Bk-iNoqoA.png)
### Business Goal:
 Captar la atención de los lectores para incentivarlos a comprar los libros
 
![Impact Map to sell books (1)](https://hackmd.io/_uploads/Hy6YY6cjC.png)

## Product Backlog

| **Orden** | **User Story**                       | **Título**                         | **Descripción**                                                                 | **Story Points** |
|-----------|-------------------------------------|------------------------------------|---------------------------------------------------------------------------------|------------------|
| 1         | Story 001                            | Registro de Usuario                | Como usuario, quiero registrarme para crear una cuenta y acceder a los recursos disponibles. | 1                |
| 2         | Story 002                            | Inicio de Sesión	      | Como usuario registrado, quiero iniciar sesión para acceder a mi cuenta y gestionar mis libros. | 2                |
| 3         | Story 003                            | Recuperación de Contraseña         | Como usuario, quiero recuperar mi contraseña para poder acceder a mi cuenta en caso de olvido. | 2                |
| 4         | Story 004                            | Añadir Libros a la Biblioteca                      | Como usuario, quiero añadir libros a mi biblioteca para tener acceso a ellos desde mi cuenta. | 3                |
| 5         | Story 005                            | Eliminar Libros de la Biblioteca     | Como usuario, quiero eliminar libros de mi biblioteca para mantenerla organizada y actualizada. | 2                |
| 6         | Story 006                            | Buscar Libros             | Como usuario, quiero buscar libros en mi biblioteca para encontrar rápidamente el material que necesito. | 2                |
| 7         | Story 007                            | 	Recomendar Libros a Otros Usuarios            | Como usuario, quiero recomendar libros a otros usuarios para compartir mis lecturas favoritas. | 2                |
| 8         | Story 008                            | Escribir Reseñas de Libros      | Como usuario, quiero escribir reseñas de libros para compartir mi opinión sobre los libros que he leído. | 3                |
| 9         | Story 009                            | Enviar Mensajes a Otros Usuarios    | Como usuario, quiero enviar mensajes a otros usuarios para discutir sobre libros y temas relacionados. | 3                |
| 10        | Story 010                            | Recibir Notificaciones de Mensajes | Como usuario, quiero recibir notificaciones cuando recibo nuevos mensajes para estar al tanto de las interacciones. | 2                |
| 11        | Story 011                            | Añadir Libros al Carrito                    | Como estudiante, quiero añadir libros al carrito para revisar mi selección antes de proceder a la compra. | 3                |
| 12        | Story 012                            | Procesar Pago	                     | Como usuario, quiero procesar el pago de los libros en mi carrito para completar la compra y obtener acceso al contenido. | 2                |
| 13        | Story 013                            | Editar Información del Perfil            | Como usuario, quiero editar mi información personal en mi perfil para actualizar mis datos y preferencias. | 2                |
| 14        | Story 014                            | Subir Imagen de Perfil | Como usuario, quiero subir una imagen de perfil para personalizar mi cuenta y hacerla más reconocible. | 2                |
| 15        | Story 015                            | Configurar Preferencias de Notificaciones           |Como usuario, quiero configurar mis preferencias de notificaciones para recibir solo la información que me interesa.| 1                |
| 16        | Story 016                            | Enviar Consulta al Soporte | Como usuario, quiero enviar una consulta al soporte para obtener ayuda con cualquier problema que enfrente. | 3                |
| 17        | Story 017                            | Acceder a Preguntas Frecuentes            | Como usuario, quiero acceder a una sección de preguntas frecuentes para encontrar respuestas a dudas comunes sin necesidad de contactar al soporte. | 2                |
| 18        | Story 018                            | Enviar Comentarios sobre la Plataforma |Como usuario, quiero enviar comentarios sobre la plataforma para contribuir a su mejora. | 2                |
| 19        | Story 019                            | Explorar Catálogo de Libros          | Como estudiante, quiero explorar el catálogo de libros y audiolibros para descubrir recursos educativos relevantes. | 2                |
| 20        | Story 020                            | Acceder a Reseñas y Detalles      | Como estudiante, quiero acceder a reseñas y detalles de libros para tomar decisiones informadas sobre qué leer o estudiar. | 3                |
| 21        | Story 021                            | 	Añadir Libros a Favoritos    | Como estudiante, quiero añadir libros a mis favoritos para tener fácil acceso a mis títulos preferidos y recomendaciones.| 3                |
| 22        | Story 022                            | Leer y Escuchar Adelantos         | Como estudiante, quiero leer o escuchar adelantos de libros para evaluar si un libro es relevante antes de decidirme a adquirirlo. | 2                |
| 23        | Story 023                            | Personalizar Recomendaciones       | Como estudiante, quiero personalizar mis recomendaciones de libros para recibir sugerencias basadas en mis intereses y actividades. | 2                |
| 24        | Story 024                            | Participar en Discusiones de Libros| Como estudiante, quiero participar en discusiones sobre libros para intercambiar ideas y opiniones con otros usuarios. | 3                |
| 25        | Story 025                            | Gestionar Lista de Lectura          | Como estudiante, quiero gestionar mi lista de lectura para organizar mis objetivos de lectura y seguimiento. | 2                |
| 26        | Story 026                            | Recibir Recomendaciones de Lectura              | Como estudiante, quiero recibir recomendaciones de lectura basadas en mi historial y preferencias para descubrir nuevos títulos que se alineen con mis intereses. | 3                |
| 27        | Story 027                            | Acceder a Materiales de Estudio        |Como estudiante, quiero acceder a materiales de estudio adicionales para apoyar mi aprendizaje y profundizar en los temas. | 2                |
| 28        | Story 028                            | 	Ver Historial de Lectura | Como estudiante, quiero ver mi historial de lectura para seguir mi progreso y revisar los libros que he leído anteriormente. | 2                |
| 29        | Story 029                            | Programar Recordatorios de Lectura   | Como estudiante, quiero programar recordatorios para mis lecturas para no olvidar los plazos y mantenerme al día con mis objetivos. | 3                |
| 30        | Story 030                            | Revisar Feedback de Lectores | Como estudiante, quiero revisar el feedback de otros lectores sobre los libros para hacer una elección informada antes de leer o adquirir un título. | 2                |
| 31        | Story 031                            | Publicar Libros Digitales      | Como autor, quiero publicar mis libros digitales en BookSphere para llegar a un público más amplio y compartir mi trabajo. | 3                |
| 32        | Story 032                            | Actualizar Información del Libro   | Como autor, quiero actualizar la información de mis libros para asegurarme de que los detalles y el contenido estén siempre actualizados. | 2                |
| 33        | Story 033                            | Gestionar Comentarios y Reseñas   | Como autor, quiero gestionar los comentarios y reseñas de mis libros para responder a los lectores y mejorar mi trabajo basado en sus opiniones. | 3                |
| 34        | Story 034                            | Acceder a Estadísticas de Lectura           | Como autor, quiero acceder a estadísticas sobre la lectura de mis libros para analizar el rendimiento y entender mejor a mi audiencia. | 3                |
| 35        | Story 035                            | Promocionar Libros en la Plataforma           |Como autor, quiero promocionar mis libros en la plataforma para aumentar su visibilidad y atraer a más lectores. | 2                |
| 36        | Story 036                            | Recibir Feedback de Lectores     |Como autor, quiero recibir feedback sobre mis libros para mejorar mis escritos y entender mejor las necesidades de mis lectores. | 3                |
| 37        | Story 037                            | Interactuar con la Comunidad de Lectores        | Como autor, quiero interactuar con la comunidad de lectores para participar en discusiones y eventos relacionados con mis libros. | 3                |
| 38        | Story 038                            |Crear Contenido Exclusivo      | Como autor, quiero crear contenido exclusivo para mis seguidores para ofrecerles material adicional y fomentar su interés en mis libros. | 3                |
| 39        | Story 039                            | Gestionar Derechos de Autor | Como autor, quiero gestionar los derechos de autor de mis libros para proteger mi trabajo y asegurar que se respete mi propiedad intelectual. | 2                |
| 40        | Story 040                            | Acceder a Información sobre Tendencias | Como autor, quiero acceder a información sobre las tendencias de lectura para adaptar mis escritos a los intereses actuales del público.| 3                |


| **Orden** | **Technical Story**                             | **Título**                               | **Descripción**                                                                                          | **Story Points (1 / 2 / 3)** |
|-----------|--------------------------------------------|------------------------------------------|----------------------------------------------------------------------------------------------------------|------------------|
| 1         | TS001                                      | Crear Cuenta de Usuario                 | Permitir a los usuarios crear una cuenta para acceder a la plataforma.                                   | 1                |
| 2         | TS002                                      | Iniciar Sesión                           | Permitir a los usuarios iniciar sesión con sus credenciales para acceder a sus cuentas.                  | 2                |
| 3         | TS003                                      | Buscar Libros                           | Implementar una funcionalidad de búsqueda de libros por título, autor o género.                           | 3                |
| 4         | TS004                                      | Agregar Libro a la Biblioteca            | Permitir a los administradores agregar nuevos libros a la biblioteca.                                     | 2                |
| 5         | TS005                                      | Actualizar Información del Libro         | Permitir a los administradores actualizar la información de un libro existente.                          | 1                |
| 6         | TS006                                      | Eliminar Libro de la Biblioteca          | Permitir a los administradores eliminar libros de la biblioteca.                                           | 3                |
| 7         | TS007                                      | Gestionar Reseñas de Libros              | Permitir a los usuarios agregar y gestionar reseñas de libros.                                             | 2                |
| 8         | TS008                                      | Implementar Sistema de Valoración         | Implementar un sistema de valoración para que los usuarios puedan calificar libros.                      | 3                |
| 9         | TS009                                      | Implementar Funcionalidad de Favoritos    | Permitir a los usuarios marcar libros como favoritos.                                                     | 2                |
| 10        | TS010                                      | Implementar Recomendaciones Personalizadas | Ofrecer recomendaciones personalizadas a los usuarios basadas en su historial de lectura.               | 1                |
| 11        | TS011                                      | Configurar Notificaciones de Nuevas Publicaciones | Notificar a los usuarios sobre nuevas publicaciones de libros.                                         | 2                |
| 12        | TS012                                      |


# Capítulo IV: Product Design
## Style Guidelines
Las Style Guidelines son fundamentales para mantener una comunicación cohesiva y profesional en todos los aspectos de la marca o proyecto, ya sea en publicaciones impresas, en línea o en cualquier otro medio de difusión. En esta sección estableceremos el conjunto de directrices que usará nuestro equipo para diseñar el proyecto BookSphere. Estas pautas definirán aspectos como la elección de colores, tipografía, estructura del documento, entre otros elementos. Para el diseño de BookSphere, utilizaremos la plataforma Figma para la creación de la aplicación web y la página de inicio. Ambas incluirán una paleta de colores con tonalidades de marrón y gris, que evocan calidez, sofisticación y modernidad, reflejando la conexión entre la tradición de la lectura y la innovación digital. A continuación, se presenta un detalle más amplio de cada aspecto mencionado.
### General Style Guidelines
El logotipo de BookSphere no es solo una imagen, es la representación visual de nuestra identidad. En el centro, el símbolo que nos representa es una esfera estilizada, que simboliza un universo de conocimiento accesible para todos. Este logotipo fusiona la idea de tecnología y literatura, dos pilares clave de nuestra misión. Es versátil y se adapta a diversas plataformas y aplicaciones, asegurando que nuestra marca se mantenga coherente y distintiva en cualquier contexto. Este logo transmite la innovación, accesibilidad y conexión que buscamos ofrecer a nuestros usuarios, tanto estudiantes como autores, en su búsqueda de libros y materiales educativos.
Logotipo del producto:  <br>
<img src="/assets/logo.jpeg" alt="Logo" width="200" />
 <br>
 Horizontal layout
  <br>
<img src="assets/Logo-inverted.jpeg" alt="Logo" width="200" />
 <br>
Inverted Colors
 <br>
**Typography**
**Font Families:**
- **Rushen Shadow: Usada para el logotipo del proyecto. Su estilo distintivo y decorativo ayuda a destacar la identidad de BookSphere.**   <br>
 ![Rushen](/assets/Rushen.png)

- **Poppins: Empleada para los encabezados y títulos. Ofrece una lectura clara y moderna, ideal para captar la atención en la plataforma.**   <br>
![Poppins](/assets/Poppins.png)

- **Noto Sans: Aplicada al cuerpo del texto. Su diseño versátil facilita la lectura y la comprensión de la información.**   <br>
![noto](/assets/noto.png)

- **Roboto: Utilizada para botones y llamados a la acción. Su aspecto limpio y moderno ayuda a mejorar la interacción del usuario.**   <br>
![Roboto](/assets/Roboto.png)

- **Raleway: Reservada para detalles y elementos destacados. Añade un toque de sofisticación a la interfaz.**   <br>
![raleway](/assets/raleway.png)

- **Arial: Seleccionada para el texto legal y el pie de página. Garantiza legibilidad y profesionalismo.**   <br>
![Arial](/assets/Arial.png)

 <br>
 
**Colores**

**La selección de colores en BookSphere ha sido cuidadosamente diseñada para reflejar la modernidad y la conexión entre la tecnología y la lectura. La paleta de colores está compuesta por:**

- **Rojo anaranjado (#e04e0b):** Representa energía y dinamismo, aportando un toque vibrante a la página. <br>
  ![#e04e0b](./assets/E04E0B.png)

- **Naranja claro (#e4864f):** Evoca calidez y accesibilidad, creando una atmósfera acogedora. <br>
  ![#e4864f](/assets/e4864f.png)

- **Gris claro (#e9ebeb):** Aporta claridad y modernidad, manteniendo la elegancia del diseño. <br>
  ![#e9ebeb](/assets/E9EBEB.png)

- **Blanco  (#ffffff):** Simboliza pureza y simplicidad, dando un aspecto limpio a la página. <br>
  ![#ffffff](/assets/ffffff.png)
- **Gris muy claro (#F5F5F5):**   Añade una ligera variación de gris, manteniendo la sobriedad en el diseño. <br>
  ![#F5F5F5](/assets/F5F5F5.png)
  
- **Marrón oscuro (#3E2723):** Transmite seriedad y sofisticación, ideal para resaltar elementos importantes. <br>
  ![#3E2723](/assets/3E2723.png)
  
 <br>
Estos colores no solo crean una armonía visual en la plataforma, sino que también refuerzan la identidad de BookSphere como una solución innovadora para el acceso a libros y materiales educativos. La combinación de estos tonos contribuye a una experiencia de usuario enriquecedora, que combina la tradición de la lectura con la modernidad de la tecnología, y refleja nuestro compromiso con la excelencia en el diseño y la funcionalidad.

### Espaciado en la Plataforma Web de BookSphere

La plataforma web de **BookSphere** está diseñada para ofrecer una experiencia de lectura y navegación cómoda y clara. A continuación, se detallan las especificaciones de espaciado recomendadas para garantizar la legibilidad y la organización visual de la plataforma:

#### Espaciado entre líneas (line-height)
- **Texto de cuerpo:** El espaciado entre líneas debe ser de 1.4 a 1.6 veces el tamaño de la fuente. Esto asegura que el texto sea fácil de leer y que haya suficiente separación para evitar una sensación de aglomeración.

#### Espaciado entre párrafos
- **Margen inferior:** Debe ser al menos el 120% del tamaño de la fuente entre párrafos. Este margen proporciona un espacio adecuado para la separación de ideas y facilita la lectura continua sin interrupciones visuales incómodas.

#### Margen y espaciado alrededor de elementos de la interfaz
- **Espacio entre elementos de la interfaz:** Al menos 20 píxeles de espacio debe mantenerse entre los elementos de la interfaz para asegurar que cada componente tenga suficiente separación y sea fácilmente accesible.

#### Espaciado entre secciones o módulos
- **Margen superior e inferior:** Debe ser de al menos 45 píxeles. Esto asegura que las secciones de la página estén claramente delimitadas y que haya suficiente espacio entre diferentes bloques de contenido.

#### Espaciado entre elementos de menú y navegación
- **Espacio entre elementos de navegación:** Al menos 15 píxeles de espacio debe mantenerse entre los elementos de navegación para evitar una apariencia desordenada y mejorar la accesibilidad.

#### Espaciado alrededor de imágenes y gráficos
- **Margen alrededor de imágenes:** Debe haber al menos 20 píxeles de margen alrededor de las imágenes y gráficos. Esto asegura que los elementos visuales no se sientan aglomerados y que el contenido relacionado esté claramente separado.

#### Espaciado en el pie de página
- **Margen superior e inferior:** Debe ser de alrededor de 40 a 60 píxeles. Este espaciado proporciona un equilibrio visual y asegura que el pie de página esté claramente diferenciado del contenido principal.

### Web Style Guidelines
texto
## Information Architecture
### Organization Systems

A continuación, explicaremos en qué grupos de información se aplicaron los distintos tipos de organización visual para ambos segmentos objetivo, así como en cuáles se utiliza algún tipo de categorización.

**Lista de libros y recursos digitales:** Los usuarios podrán ver una lista completa de todos los libros, audiolibros y materiales educativos disponibles en BookSphere. Si un libro les interesa, podrán agregarlo a su biblioteca personal o comenzar a leerlo inmediatamente. Además, podrán visualizar reseñas, puntuaciones y recomendaciones personalizadas antes de tomar su decisión.

**Historial de publicaciones:** Cada autor o editor tendrá acceso a un historial completo de sus publicaciones en la plataforma. En este historial, podrán editar la información de cualquier obra previamente subida, actualizar versiones, o incluso eliminar contenido si lo consideran necesario, otorgándoles un control total sobre su material.

**Historial de lectura:** Cada usuario contará con un historial detallado de los libros y recursos que ha leído o explorado en BookSphere. Este historial también incluirá información sobre el progreso en sus lecturas actuales, lo que facilita retomar la lectura desde donde la dejaron.

**Mensajes y Comunicación:** Los usuarios podrán comunicarse directamente entre ellos o con los autores a través de la plataforma. Esta función facilitará la interacción entre lectores y creadores, permitiendo que los usuarios compartan sus opiniones, hagan preguntas, o coordinen actividades relacionadas con el contenido.

### Labeling Systems

| Ícono  | Descripción |
|------------|------------|
|  ![user](https://hackmd.io/_uploads/rJfKxfgn0.png)   | **Perfil:** En BookSphere, el ícono de perfil permitirá a los usuarios acceder a su información personal, modificar sus datos, ver su historial de lectura o publicación y gestionar sus preferencias.  |
|  ![messages](https://hackmd.io/_uploads/B1GKxMlnC.png)   |**Mensajes:** Los usuarios lo usarán para comunicarse entre sí, tanto Autores como Lectores, o recibir notificaciones de novedades, recomendaciones personalizadas, o mensajes de la comunidad.  |
|   ![book-alt](https://hackmd.io/_uploads/B1GYgMg3R.png)  | **Biblioteca:** Un ícono que permite a los usuarios acceder a su biblioteca personal donde pueden ver todos los libros y audiolibros que han adquirido o guardado.  |
|  ![search](https://hackmd.io/_uploads/H1lMYgzghA.png)     | **Buscar:** Un ícono para buscar libros, autores, o recursos específicos dentro de la plataforma. |
|  ![feedback-alt](https://hackmd.io/_uploads/rkgfYxGeh0.png)    | **Reseñas:** Un ícono para acceder a las reseñas que el usuario ha dejado o para ver las reseñas de otros usuarios sobre un libro específico.  |
| ![download](https://hackmd.io/_uploads/BJzYgfeh0.png)     | **Descargas:** Un ícono que permita a los usuarios acceder a los libros o recursos descargados para su lectura o escucha offline. |
|   ![process](https://hackmd.io/_uploads/SkWzKxGl2A.png)    | **Configuración:** Un ícono de engranaje que permita a los usuarios acceder a las opciones de configuración de su cuenta, como la gestión de preferencias de notificación o personalización del perfil. |
|   ![star](https://hackmd.io/_uploads/r1zFxGl3A.png)   | **Favoritos:** Un ícono de corazón o estrella para que los usuarios puedan marcar libros o recursos como favoritos, permitiéndoles acceder a ellos fácilmente más tarde.  |
|   ![home](https://hackmd.io/_uploads/B1eMYlGenC.png)   | **Home:** Un ícono para llevar a los usuarios de vuelta a la pantalla de inicio o la página principal de la plataforma. Generalmente se representa con una casa o un edificio. |
|  ![bell](https://hackmd.io/_uploads/SJGFgfenC.png)
![book-alt]    | **Notificaciones:** Un ícono de campana que notifique a los usuarios sobre eventos importantes, actualizaciones, o interacciones dentro de la plataforma.|



### SEO Tags and Meta Tags
texto
### Searching Systems
texto
### Navigation Systems
texto
## Landing Page UI Design
### Landing Page Wireframe
texto
### Landing Page Mock-up
texto
## Web Applications UX/UI Design
### Web Applications Wireframes
texto
### Web Applications Wireflow Diagrams
texto
### Web Applications Mock-ups
texto
### Web Applications User Flow Diagrams
texto
## Web Applications Prototyping
texto
## Domain-Driven Software Architecture
### Software Architecture Context Diagram
texto
### Software Architecture Container Diagrams
texto
### Software Architecture Components Diagrams
texto
## Software Object-Oriented Design
### Class Diagrams
texto
### Class Dictionary
texto
## Database Design
### Database Diagram
texto
# Capítulo V: Product Implementation, Validation & Deployment
## Software Configuration Management
### Software Development Environment Configuration
texto
### Source Code Management
texto
### Source Code Style Guide & Conventions
texto
### Software Deployment Configuration
texto
## Landing Page, Services & Applications Implementation
### Sprint 1
#### Sprint Planning 1
texto
#### Sprint Backlog 1
texto
#### Development Evidence for Sprint Review
texto
#### Testing Suite Evidence for Sprint Review
texto
#### Execution Evidence for Sprint Review
texto
#### Services Documentation Evidence for Sprint Review
texto
#### Software Deployment Evidence for Sprint Review
texto
#### Team Collaboration Insights during Sprint
texto

## Validation Interviews

### Diseño de Entrevistas

### Registro de Entrevistas

### Evaluaciones según heurísticas

## Video About-the-Product

## Conclusiones

### Conclusiones y recomendaciones

## Video About-the-Team

## Bibliografía

## Anexos
sss
