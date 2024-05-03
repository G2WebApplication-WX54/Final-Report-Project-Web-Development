# Capítulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

- **Product UX/UI Design**<br>
**Figma** es una plataforma de creación de prototipos y edición gráfica, que se utiliza principalmente para el diseño digital. En el contexto de este proyecto, se utilizará para la creación e Wireframes, Mock-ups y Prototypes de la aplicación. Puedes encontrar más información en la siguiente dirección: https://www.figma.com/login<br>
**Lucidchart** es una herramienta para la creación de diagramas de flujo. Se utilizará para el diseño de As-Is y To-Be Scenario Maps. Puedes encontrar más información en la siguiente dirección: https://www.lucidchart.com/<br>
**UXPressia** es una plataforma en línea que sirve para visualizar y gestionar la experiencia del cliente. Para este proyecto lo usaremos para la creacion de User Personas, Empathy Maps, Journey Maps e Impact Maps. Puedes encontrar más información en la siguiente dirección: https://uxpressia.com/

- **Software Development**<br>
**Visual Studio Code:** Este entorno de desarrollo integrado ha sido seleccionado para la creación y compilación del código debido a su familiaridad entre los miembros del equipo. Su uso es valioso para el proyecto ya que permite añadir extensiones útiles, soporta la edición de texto en varios lenguajes de programación y está disponible en varios sistemas operativos, entre otras ventajas.<br>
**HTML5:** Conocido como HyperText Markup Language, es un lenguaje de marcado utilizado para las páginas web. Se utilizará en el proyecto para mostrar el contenido en la aplicación.<br>
**CSS:** Las Hojas de Estilo en Cascada son un lenguaje que controla el diseño y la presentación de las páginas web, trabajando en conjunto con HTML.<br>
**JavaScript:** Es un lenguaje de programación interpretado y orientado a objetos. Se empleará para desarrollar la interfaz de usuario dentro de la aplicación.
- **Software Deployment**<br>
**Git** es una herramienta de control de versiones que facilita el seguimiento y la gestión de las distintas versiones del software. Se empleará para conservar un registro de modificaciones y facilitar la resolución de problemas. Los integrantes del equipo la utilizarán a través de la línea de comandos en sus sistemas locales. Puedes encontrar más información en la siguiente dirección: https://git-scm.com/
- **Software Documentation**<br>
**Github** es una plataforma en la nube que servirá como el hogar de los repositorios de código de nuestro proyecto. Esta herramienta permitirá una colaboración efectiva en tiempo real y facilitará la revisión de las aportaciones de cada integrante del equipo. Los miembros del equipo podrán acceder a ella mediante sus navegadores web. Puedes encontrarla en la siguiente dirección: https://github.com/


### 5.1.2. Source Code Management.

El proyecto adoptará las convenciones de flujo de trabajo del modelo GitFlow para la gestión de versiones, utilizando GitHub como la plataforma y el sistema de control de versiones.<br>

**Estructura de las ramas (branches)**:

- **Master (Rama Master)**: Esta rama se considerará la principal para la aplicación y contendrá las versiones finales y estables del desarrollo. Solo se permitirán cambios que hayan sido probados y verificados previamente en otras ramas de prueba.<br>
- **Develop (Rama de Desarrollo)**: El objetivo de esta rama es llevar a cabo los avances del proyecto en equipo y mantener los archivos centrales del desarrollo continuo.<br>
- **Feature (Ramas de Funcionalidad)**: Cada funcionalidad desarrollada por el equipo o separada del enfoque actual del desarrollo tendrá su propia rama. Una vez que una funcionalidad esté completamente desarrollada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, “feature/nombre-de-la-funcionalidad”.<br>

Convenciones de los Commits: Para los mensajes de los commits realizados, se utilizará la especificación de los Commits Convencionales

### 5.1.3. Source Code Style Guide & Conventions.

HTML: Aquí hay algunas prácticas recomendadas para lograr un código HTML coherente, mantenible y bien organizado:<br>

Nos aseguramos de cerrar todos los elementos HTML. Por ejemplo, \<p>Esto es un párrafo.\</p>.
Es recomendable especificar el texto alternativo y las dimensiones (ancho y alto) de las imágenes. Esto mejora la accesibilidad del contenido. Por ejemplo: \<img src="abc.img" alt="nombre de la imagen" style="width:128px;height:128px"> <br>

Gherkin: Es un lenguaje específico de dominio diseñado para resolver un problema específico: mejorar la comunicación entre los equipos de negocio y técnicos cuando se trabaja con Desarrollo Guiado por Comportamiento (BBD, por sus siglas en inglés). Para promover buenas prácticas, se utilizan saltos de línea para organizar mejor los diferentes tipos de escenarios y distinguirlos de manera más efectiva. Además, se utilizan las palabras clave “Given”, “When”, “Then” y “And” para estructurar los escenarios.

### 5.1.4. Software Deployment Configuration.

Nuestro repositorio en Github<br>
<img src="../../assets/Repositorio_1.png"><br>
Nuestras ramas:<br>
<img src="../../assets/Repositorio_2.png"><br>
Para poder trabajar cada capitulo de este proyecto, vamos a entrar a la rama correspondiente, por ejemplo si queremos editar el capitulo 1 debemos entrar a la rama feature/chapter-01<br>
<img src="../../assets/Repositorio3.png"><br>
Dentro de la rama feature/chapter-01 tenemos la carpeta docs donde se encuentran los archivos de cada capitulo, si queremos editar el capitulo 1 debemos editar el archivo chapter-01.md
<img src="../../assets/Repositorio_4.png"><br>

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
En el Sprint Planning 1, nos centraremos en los tasks relacionados con la creación de la Landing Page. Distribuiremos entre nosotros todas las tareas identificadas para este sprint.
<table>
    <tr align="center">
        <td><strong>Sprint #</strong></td>
        <td><strong>Sprint 1</strong></td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>26/03/2024</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>10:00 PM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Discord</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Janiel Franz Escalante Baygorrea, </td>
    </tr>
    <tr align="center">
        <td>Attendess (to planning meeting)</td>
        <td>
	        Anatoly Andrey Noriega Suschenko - U202211813<br>
	        Andres Fernando Rodriguez Zuluoeta - U202124213<br>
	        Janiel Franz Escalante Baygorrea - U201912668<br>
	        Johan Príncipe Godoy - U202014511<br>
	        Victor Ernesto Zarate Caceres - U202112907
    </tr>
    <tr align="center">
        <td>Sprint 1 Review Summary</td>
        <td>En el Sprint Planning 1, nos centraremos en los tasks relacionados con la creación de la Landing Page. Distribuiremos entre nosotros todas las tareas identificadas para este sprint.</td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Retrospective Summary</td>
        <td>En esta sección, todos los miembros expresaron que algunas partes del código fueron exitosas, mientras que en otras áreas sienten que podrían mejorar sus habilidades al desarrollar páginas de inicio.</td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Goal</td>
        <td>Desarrollar y planificar despliegue de Landing Page</td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Velocity</td>
        <td>5</td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td>5</td>
    </tr>
</table>

#### 5.2.1.2. Sprint Backlog 1
<table>
    <tr align="center">
        <td colspan="2"><strong>Sprint #</strong></td>
        <td colspan="6"><strong>Sprint 1</strong></td>
    </tr>
    <tr align="center">
        <td colspan="2"><strong>User Story</strong></td>
        <td colspan="6"><strong>Work-Item / Task</strong></td>
    </tr>
    <tr align="center">
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Description</strong></td>
        <td><strong>Estimation (Hours)</strong></td>
        <td><strong>Assigned to</strong></td>
        <td><strong>Status (To do / In process / To review / Done)</strong></td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Estructura del Landing Page</td>
        <td>W-01</td>
        <td>Estructura del Landing Page</td>
        <td>Crear la estructura de la Landing page para visualizar la información de la aplicación</td>
        <td>2</td>
        <td>Janiel</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Sección Inicio</td>
        <td>W-02</td>
        <td>Estilos a la sección inicio</td>
        <td>Añadir estilos a la sección de inicio</td>
        <td>1</td>
        <td>Victor</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Sección Nosotros</td>
        <td>W-03</td>
        <td>Estilos a la sección nosotros</td>
        <td>Añadir estilos a la sección de nosotros</td>
        <td>1</td>
        <td>Andres</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Sección Aplicación</td>
        <td>W-04</td>
        <td>Estilos a la sección aplicación</td>
        <td>Añadir estilos a la sección de aplicación</td>
        <td>1</td>
        <td>Andres</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Sección Servicios</td>
        <td>W-05</td>
        <td>Estilos a la sección servicios</td>
        <td>Añadir estilos a la sección de servicios</td>
        <td>1</td>
        <td>Andres</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Sección Planes</td>
        <td>W-06</td>
        <td>Estilos a la sección planes</td>
        <td>Añadir estilos a la sección de planes</td>
        <td>1</td>
        <td>Victor</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US01</td>
        <td>Sección Contacto</td>
        <td>W-07</td>
        <td>Estilos a la sección contacto</td>
        <td>Añadir estilos a la sección de contacto</td>
        <td>1</td>
        <td>Victor</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Header de Navegación</td>
        <td>W-08</td>
        <td>Funcionalidad de navegación de la página</td>
        <td>Añadir un Header de Navegación para agilizar la búsqueda de información en la Landing Page</td>
        <td>1</td>
        <td>Anatoly</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US02</td>
        <td>Header de Navegación</td>
        <td>W-09</td>
        <td>Estilos al Header de Navegación</td>
        <td>Añadir estilos al Header de Navegación
        /td>
        <td>1</td>
        <td>Johan</td>
        <td>Done</td>
    </tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review
<table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id</td>
        <td>Commit Message</td>
        <td>Commit Message Body</td>
        <td>Commited on (Date)</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>develop</td>
        <td>66f48121b2b9ccbe6e4eb7c3c920e698e686c4c4</td>
        <td>feat: index html and images</td>
        <td>-</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/adding-some-css</td>
        <td>b20caabc8714404c89799fd0863e46131389744e</td>
        <td>Create style.css</td>
        <td>-</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/css-footer</td>
        <td>b9ca48965254c9750cba2e9f64d46aa007667e2a</td>
        <td>chore: styles.css</td>
        <td>-</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/css-header-and-body</td>
        <td>ddae7c7f723dab8e2ad9cb16ab28416e37ae2be6</td>
        <td>docs: styles header and body added</td>
        <td>-</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/javascript-movements</td>
        <td>cc5104b442d99058db318446b93730dc4c2a8c27</td>
        <td>feat: add JavaScript for landing page functionality</td>
        <td>-</td>
        <td>14/04/2024</td>
    </tr>
</table>

#### 5.2.1.4. Testing Suite Evidence for Sprint Review
<div align="justify">
    Para la entrega del Sprint 1 se busco el desarrollo completo e implementación de la Landing Page. Por ello, esta sección se centro en la implementación de los archivos feature, basados en User Stories, que contiene nuestro landing page. 
    <table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id</td>
        <td>Commit Message</td>
        <td>Commit Message Body</td>
        <td>Commited on (Date)</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>10baacc3ba06a9fd36e6cb3a00dbff4401550ece</td>
        <td>initial commit</td>
        <td>- Created the initial commit</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>66f48121b2b9ccbe6e4eb7c3c920e698e686c4c4</td>
        <td>index html and images</td>
        <td>- Added index HTML file</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>cc5104b442d99058db318446b93730dc4c2a8c27</td>
        <td>add JavaScript for landing page functionality</td>
        <td>- Added JavaScript file</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>b20caabc8714404c89799fd0863e46131389744e</td>
        <td>Create style.css</td>
        <td>- Added style CSS file</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>ddae7c7f723dab8e2ad9cb16ab28416e37ae2be6</td>
        <td>styles header and body added</td>
        <td>- Added styles for header and body</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>b9ca48965254c9750cba2e9f64d46aa007667e2a</td>
        <td>styles.css</td>
        <td>- Added some styles for the sections</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>0fa09ebe512404169eab1d25cf73bffa40ea9657</td>
        <td>moving css from style to styles</td>
        <td>- Moved css from style to styles</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>9cac788d73dcb4a83e13aa5b3200fa6c37ae577d</td>
        <td>deleting some space in the code</td>
        <td>- Deleted unnecesary spaces</td>
        <td>14/04/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>main</td>
        <td>311c9d575bdee6c3f674cb47382db1b174a1d4ba</td>
        <td>translate content to English</td>
        <td>- Added English as the default language</td>
        <td>01/05/2024</td>
    </tr>
</table>
</div>

#### 5.2.1.5. Execution Evidence for Sprint Review
<div align="justify">
    En el sprint 1 se diseñó de manera preliminar el primer modelo de la landing page. Esta cuenta con diferentes secciones para acceso de los usuarios. Algunas evidencias son:
    
##### Sección de Inicio:
Se implementó el Header de nuestra Landing Page junto con la sección de inicio del Landing Page.

<img src="/assets/Evidence Header and Start.png" alt="Evidence Header and Start" width="80%">

##### Sección de Nosotros:
Se implementó la sección de nosotros para describir sobre quienes somos.

<img src="/assets/Evidence About Us.png" alt="Evidence About Us" width="80%">

##### Sección de Aplicación:
Se implementó la sección de la aplicación donde se muestra una pequeña descripción de la app.

<img src="/assets/Evidence App.png" alt="Evidence App" width="80%">

##### Sección de Servicios:
Se implementó la sección de los servicios que ofreceremos a los usuarios.

<img src="/assets/Evidence Services.png" alt="Evidence Services" width="80%">

##### Sección de Planes:
Se añadió la sección de planes donde podrán adquirir nuestro plan estándar (para los ciudadanos) o nuestro plan gubernamental (para las municipalidades).

<img src="/assets/Evidence Plans.png" alt="Evidence Plans" width="80%">

##### Sección de Contacto:
Se añadió la sección de contactos donde podrán contactarse con los desarrolladores de la plataforma junto con el footer.

<img src="/assets/Evidence Contact and Footer.png" alt="Evidence Contact and Footer" width="80%">

</div>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
<div align="justify">
    En este primer sprint se incluyo únicamente una Landing Page creada con html estático, en varios archivos conjuntos subidos simultáneamente. Por ello, al no contar con un back-end, no fue contemplada la evidencia de documentación de los servicios.
</div>

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
<div align="justify">
Nos enfocamos plenamente en asegurar un proceso de Deployment eficiente y efectivo. Este enfoque no solo buscó mejorar la experiencia de usuario final, sino también optimizar nuestro flujo de trabajo de desarrollo y despliegue continuo. Por ello, se presentan las siguientes evidencias:<br><br>
<img src="/assets/Evidence Application.png" alt="Evidence Application" width="80%">
</div>
Enlace para acceder a la landing page: https://g2webapplication-wx54.github.io/landing-page-web-app/

#### 5.2.1.8. Team Collaboration Insights during Sprint
<div align="justify">
Se abordo el trabajo de manera colaborativa y organizada. Para ello, se dividieron las tareas según las secciones acordadas durante las reuniones de planificación. Esto nos ayudo a trabajar de manera eficiente, al centrarnos en áreas específicas para optimizar el tiempo y los recursos. Dicha participación de los miembros del equipo se ve reflejado en los commits realizados en el repositorio de trabajo.
</div>

Tabla para poder identificarnos:

|  UserName (Github)   | Nombre         |
| -------------------- |-------------|
|Anatoly69420          | Anatoly Andrey  Noriega Suschenko|
|Andres-0304   		   | Andres Fernando Rodriguez Zuluoeta  |
|JanielFranz           |Janiel Franz Escalante Baygorrea |
|JP19-03               |Johan Príncipe Godoy|
|ern23zc               |Victor Ernesto Zarate Caceres |

##### Commits:

<img src="/assets/CommitsAnalysis.png" alt="CommitsAnalysis">

##### Analíticas de Colaboración:

<img src="/assets/ColaborationAnalysis.png" alt="ColaborationAnalysis">

### 5.2.2. Sprint 2
#### 5.2.2.1.Sprint Planning 2.
<table>
    <tr align="center">
        <td><strong>Sprint #</strong></td>
        <td><strong>Sprint 1</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>20/04/2024</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>10:00 PM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Discord</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Janiel Franz Escalante Baygorrea, </td>
    </tr>
    <tr align="center">
        <td>Attendess (to planning meeting)</td>
        <td align="justify">
	        Anatoly Andrey Noriega Suschenko - U202211813<br>
	        Andres Fernando Rodriguez Zuluoeta - U202124213<br>
	        Janiel Franz Escalante Baygorrea - U201912668<br>
	        Johan Príncipe Godoy - U202014511<br>
	        Victor Ernesto Zarate Caceres - U202112907
    </tr>
    <tr align="center">
        <td>Sprint 1 Review Summary</td>
        <td align="justify">
		Se completaron las User Stories establecidos en el sprint anterior y mejoramos la experiencia de usuario en la landing page.
	</td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Retrospective Summary</td>
        <td align="justify">
		El equipo acordó enmendar los errores de la presentación anterior y colaborar más estrechamente con el equipo. Además se acordó la landing page de la aplicación.
	</td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr align="center">
        <td>Sprint 2 Goal</td>
        <td align="justify">
		El objetivo primordial para este sprint es implementar funcionalidades esenciales para la Web Application, buscando enriquecer la experiencia del usuario y mejorar sustancialmente la gestión de contenido. 
		</td>
    </tr>
    <tr align="center">
        <td>Sprint 2 Velocity</td>
        <td></td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td></td>
    </tr>
</table>

#### 5.2.2.2.Sprint Backlog 2.
<table>
    <tr align="center">
        <td colspan="2"><strong>Sprint #</strong></td>
        <td colspan="6"><strong>Sprint 2</strong></td>
    </tr>
    <tr align="center">
        <td colspan="2"><strong>User Story</strong></td>
        <td colspan="6"><strong>Work-Item / Task</strong></td>
    </tr>
    <tr align="center">
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Description</strong></td>
        <td><strong>Estimation (Hours)</strong></td>
        <td><strong>Assigned to</strong></td>
        <td><strong>Status (To do / In process / To review / Done)</strong></td>
    </tr>
    <tr align="center">
        <td>US</td>
        <td></td>
        <td>W-01</td>
        <td></td>
        <td></td>
        <td> hours</td>
        <td></td>
        <td></td>
    </tr>
    <tr align="center">
        <td>US</td>
        <td></td>
        <td>W-02</td>
        <td></td>
        <td></td>
        <td> hours</td>
        <td></td>
        <td></td>
    </tr>
    <tr align="center">
        <td>US</td>
        <td></td>
        <td>W-03</td>
        <td></td>
        <td></td>
        <td> hours</td>
        <td></td>
        <td></td>
    </tr>
    <tr align="center">
        <td>US</td>
        <td></td>
        <td>W-04</td>
        <td></td>
        <td></td>
        <td> hours</td>
        <td></td>
        <td></td>
    </tr>
    <tr align="center">
        <td>US</td>
        <td></td>
        <td>W-05</td>
        <td></td>
        <td></td>
        <td> hours</td>
        <td></td>
        <td></td>
    </tr>
    <tr align="center">
        <td>US</td>
        <td></td>
        <td>W-06</td>
        <td></td>
        <td></td>
        <td> hours</td>
        <td></td>
        <td></td>
    </tr>
</table>

#### 5.2.2.3.Development Evidence for Sprint Review.
<table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id</td>
        <td>Commit Message</td>
        <td>Commit Message Body</td>
        <td>Commited on (Date)</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>/0/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>/0/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>/0/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>/0/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>/0/2024</td>
    </tr>
</table>

#### 5.2.2.4.Testing Suite Evidence for Sprint Review.
<div align="justify">
    Para la entrega del Sprint 2 se busco el desarrollo inicial de la Web Application y una mejora de la Landing Page. Por ello, esta sección se centro en trabajar en los User Stories relacionados. 
    <table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id</td>
        <td>Commit Message</td>
        <td>Commit Message Body</td>
        <td>Commited on (Date)</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>/0/2024</td>
    </tr>
</table>
</div>

#### 5.2.2.5.Execution Evidence for Sprint Review.
<div align="justify">
    En el sprint 2 se diseñó de manera preliminar el primer modelo de la Web App. Además, se realizo la mejora de la landing page. Algunas evidencias son:
    <ul>
        <li></li>
    </ul>
</div>

#### 5.2.2.6.Services Documentation Evidence for Sprint Review.
<div align="justify">
	Para el Sprint 2 únicamente se planificó para abarcar las mejoras de la landing page y la creación del front-end.
	<table>
		<tr>
			<td>Endpoint: </td>
			<td>Details: </td>
		</tr>
		<tr>
			<td>/</td>
			<td>Se implemento</td>
		</tr>
		<tr>
			<td>/</td>
			<td>Se implemento</td>
		</tr>
	</table>
	<table>
		<tr>
			<td>Repository</td>
			<td>Branch</td>
			<td>Commit ID</td>
			<td>Commit message</td>
			<td>Commit message body</td>
			<td>Commited on (Date)</td>
		</tr>
		<tr>
			<td>landing-page-web-app</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>landing-page-web-app</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</table>
</div>

#### 5.2.2.7.Software Deployment Evidence for Sprint Review.
<div align="justify">
	Para el presente sprint, se desplego el landing page completamente funcional, cumpliendo los user stories correspondientes. De la misma forma se desplego una
	primer versión de la web application, con mejoras a realizar para el siguiente sprint:
	<ul>
		<li>Landing Page:</li>
		<img src="imgs/EvidenceSprintLanding1" alt="Evidencia 1 Landing Page - Sprint 2">
		<img src="imgs/EvidenceSprintLanding2" alt="Evidencia 2 Landing Page - Sprint 2">
		<img src="imgs/EvidenceSprintLanding3" alt="Evidencia 3 Landing Page - Sprint 2">
		<img src="imgs/EvidenceSprintLanding4" alt="Evidencia 4 Landing Page - Sprint 2">
		<li>Web Application</li>
		<img src="imgs/EvidenceSprintWebApp1" alt="Evidencia 1 Web ApplicationLanding Page - Sprint 2">
		<img src="imgs/EvidenceSprintWebApp2" alt="Evidencia 2 Web ApplicationLanding Page - Sprint 2">
		<img src="imgs/EvidenceSprintWebApp3" alt="Evidencia 3 Web ApplicationLanding Page - Sprint 2">
		<img src="imgs/EvidenceSprintWebApp4" alt="Evidencia 4 Web ApplicationLanding Page - Sprint 2">
	</ul>
</div>

#### 5.2.2.8.Team Collaboration Insights during Sprint.
<div align="justify">
	Durante el Sprint actual, nos dispusimos a abordar las distintas mejoras para la Landing Page de PeaceApp, avanzar en llevarla a su versión definitiva, donde será completamente responsive.<br>
	A su vez se dio inicio a la creación de la plataforma principal. Para ello, dividimos las tareas para trabajar de manera eficiente y centrarnos en áreas específicas, con el fin  
	de optimizar el tiempo y los recursos. Finalmente, la participación de los miembros del equipo se ve reflejado en los xxx commits realizados en el repositorio de trabajo.<br>
</div>

Tabla para poder identificarnos:

|  UserName (Github)   | Nombre         |
| -------------------- |-------------|
|Anatoly69420          | Anatoly Andrey  Noriega Suschenko|
|Andres-0304   		   | Andres Fernando Rodriguez Zuluoeta  |
|JanielFranz           |Janiel Franz Escalante Baygorrea |
|JP19-03               |Johan Príncipe Godoy|
|ern23zc               |Victor Ernesto Zarate Caceres |

# Conclusiones
# Bibliografía
<div align="justify">
  <ul>
    <li>Banco Mundial. (2017). <em>Enhancing Urban Safety and Security: Global Report on Human Settlements 2007.</em> Recuperado de https://www.bancomundial.org</li>
    <li>Naciones Unidas. (2019). <em>UN System-Wide Guidelines on Safer Cities and Human Settlements.</em> Recuperado de https://www.un.org</li>
  </ul>
</div>

# Anexos.
<table>
  <tr>
    <td>Sección</td>
    <td>Características del video</td>
  </tr>
  <tr>
    <td>Exposición</td>
    <td>Cantidad de videos: 1<br>
      Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-expo-tb1<br>
      Formato: .mp4<br>
      Duración:<br>
      Enlace:</td>
  </tr>
  <tr>
    <td>Entrevistas</td>
    <td>Cantidad de videos: 1<br>
      Nomenclatura: Interview Web Development<br>
      Formato: .mp4<br>
      Duración: 24:10<br>
      Enlace: https://shorturl.at/clwGR</td>
  </tr>
</table>
