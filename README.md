# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br>
    <img src="./assets/logo-upc.png" alt="UPC Logo"><br>
    <br>
    <strong>Ingeniería de Software - 2024-01</strong><br>
    <br>
    <strong>Aplicaciones Web - WX54</strong><br>  
    <br>
    <strong>Profesor: Alex Humberto Sánchez Ponce</strong><br>
    <br> <strong>INFORME DE TRABAJO FINAL - TF </strong> 
</p>
<p align="center">
    <strong>Startup: PeaceApp </strong><br>
    <strong>Producto:  PeaceApp </strong>
</p>

<h3 align="center" >Team Members:</h3>
<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Escalante Baygorrea, Janiel Franz</td>
            <td>U201912668</td>
        </tr>
        <tr>
            <td>Noriega Suschenko, Anatoly Andrey</td>
            <td>U202211813</td>
        </tr>
        <tr>
            <td>Príncipe Godoy, Johan</td>
            <td>U202014511</td>
        </tr>
        <tr>
            <td>Rodriguez Zuluoeta, Andres Fernando</td>
            <td>U202124213</td>
        </tr>
        <tr>
            <td>Zarate Caceres, Victor Ernesto</td>
            <td>U202112907</td>
        </tr>
    </table>
</div>
<br>

# Registro de Versiones del Informe

| Versión |   Fecha    | Autor | Descripción de modificación | 
|:-------:|:----------:|:-----:|:----------------------------| 
|TB1| 14/04/2024 |Todos los integrantes del equipo| Capitulo I, Capitulo II, Capitulo III, Capitulo IV y Capitulo V.<br>Creación de Landing Page | 
|TP | 01/05/2024 |Todos los integrantes del equipo| Correción del presentable anterior<br>Mejora de Landing Page<br>Creación de App Web|
|TB2| 08/06/2024 |Todos los integrantes del equipo| Correcion del presentable anterior<br>Versión definitiva de Landing Page<br>Mejora de App Web<br>Primera versión de Web Services<br>Primera versión de Video About-The-Product.<br>Primera versión de Video About-The-Team|
|TF | 28/06/2024 |Todos los integrantes del equipo|Correcion del presentable anterior<br>Versión definitiva de App Web<br>Versión mejorada de Web Services<br>Versión final de Video About-The-Product.<br>Versión final de Video About-The-Team||

# Project Report Collaboration Insights

Para el desarrollo del informe se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:

| Integrantes                         | Tareas designadas                                                                                                                                                                      |
| :---------------------------------- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Escalante Baygorrea, Janiel Franz   | Lean UX Process, Software Object-Oriented Design, Diagrama de base de datos, Diagrama UML, parte del Landing Page, Responsive landing page, Web Application reports bounded context.   |
| Noriega Suschenko, Anatoly Andrey   | Segmentos objetivo, Competidores, Analisis Competitivo, Entrevista, Landing Page UI Design, Web Application UX/UI Design, Web Application Prototyping y parte del Landing Page         |
| Príncipe Godoy, Johan               | Needfinding, Ubiquitous Language, To-Be Scenario Mapping, Domain-Driven Software Architecture y parte del Landing Page                                                                 |
| Rodriguez Zuluoeta, Andres Fernando | Diseño de entrevistas, Analisis de entrevistas, Needfinding, User Personas, User Stories, Impact Mapping, Product Backlog, Software Configuration Managemente y parte del Landing Page |
| Zarate Caceres, Victor Ernesto      | Startup Profile, Solution Profile, Registor de entrevista, Style Guidelines, Information Arquitecture y parte del Landing Page                                                         |

Informe: https://github.com/G2WebApplication-WX54/Final-Report-Project-Web-Development/tree/develop

# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capc3adtulo-i-introduccic3b3n-1)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#23-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capc3adtulo-iv-product-design-1)
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capc3adtulo-v-product-implementation-validation--deployment-1)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
    - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
    - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.2.2. Sprint 2](#522-sprint-2)
    - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
    - [5.2.2.2. Sprint Backlog 1](#5222-sprint-backlog-2)
    - [5.2.2.3. Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
    - [5.2.2.4. Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
    - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
    - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
    - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
    - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
  - [5.2.3. Sprint 3](#523-sprint-3)
    - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
    - [5.2.3.2. Sprint Backlog 3](#5232-sprint-backlog-3)
    - [5.2.3.3. Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)
    - [5.2.3.4. Testing Suite Evidence for Sprint Review](#5234-testing-suite-evidence-for-sprint-review)
    - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
    - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
    - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
    - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
  - [5.2.4. Sprint 4](#524-sprint-4)
    - [5.2.4.1. Sprint Planning 3](#5241-sprint-planning-4)
    - [5.2.4.2. Sprint Backlog 3](#5242-sprint-backlog-4)
    - [5.2.4.3. Development Evidence for Sprint Review](#5243-development-evidence-for-sprint-review)
    - [5.2.4.4. Testing Suite Evidence for Sprint Review](#5244-testing-suite-evidence-for-sprint-review)
    - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
    - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
    - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
    - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
- [5.3.Validation Interviews](#53-validation-interviews)
  - [Diseño de Entrevistas](#diseño-de-entrevistas)
  - [Registro de Entrevistas](#registro-de-entrevistas)
  - [Evaluaciones según heurísticas](#evaluaciones-segun-heuristicas)
- [5.4.Video About-the-Product](#54-video-about-the-product)

### [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Product](#video-about-the-product)

### [Bibliografía](#bibliografia)
### [Anexos](#anexos)

# Student Outcome
<div align="justify">
	Criterio: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos.<br>    
	En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.
	<br><br>
	<table>
		<tr>
			<td><b>Criterio específico</b></td>
			<td><b>Acciones realizadas</b></td>
			<td><b>Conclusiones</b></td>
		</tr>
		<tr>
			<td>
				<b>Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.</b>
			</td>
			<td>
				TB1:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
					  He realizado la seccion del UX LEAN Process, Software Object-Oriented Design, Diagrama de base de datos, Diagrama UML y parte del Landing Page. Mi participación en el equipo fue fundamental para el desarrollo del proyecto, cumpliendo con todas las tareas asignadas y aportando ideas para el desarrollo de la plataforma.<br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            He realizado la sección de Segmentos objetivos para identificar cuales serán nuestros principales usuarios para la plataforma, también el analisis de competidores junto con las estrategias para evaluar quienes son nuestros rivales potenciales dentro del mercado y evaluar estrategias para poder aprovechar nuestras oportunidades y fortalezas para afrontar las debilidades y amenazas. También realice la entrevista del segmento usuario para poder evaluar lo que requieren nuestros usuarios potenciales y realice los diseños tanto de los Wireframes y Mock-Ups de la Landing Page como de la Web Application y realizar un prototipo de como sera nuestra plataforma <br><br>          
			    <b>Príncipe Godoy, Johan:</b><br>
					  Para el desarrollo del proyecto, participé eficazmente en la creación de los User Task Matrix, Journey Mapping, Empathy Mapping, As-Is y To-be Scenario Mapping<br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            He realizado el diseño y posterior analisis de entrevistas,user personas de cada segmento obejtivo, user stories con sus respectivos criterios de aceptacion, impact mapping, product backlog y el software configuration management.<br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Se participo activamente en identificar el problema a enfrentar y la solución que se utilizara. Para cumplir el trabajo, se realizaron todas las tareas encomendadas, como lo son la introducción, el perfil de la Startup, el perfil de la solución y el diseño de producto con todas las guidelines e información de arquitectura necesaria.<br><br>
        TP:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
            He participado junto con mis compañeros en la modificación del repositorio del reporte del proyecto. Por otro lado, también participe en la creación de la App Web y su posterior dedspliegue<br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            He realizado la corrección de algunos puntos del proyecto como lo serían el Ubiquitous Language, el Domain-Driven Software Architecture, junto con el Sprint 1 que en el envío pasado no estaba presente. Así mismo participe en la realización de la Web Application y poner como predeterminado el idioma inglés en la Landing Page.<br><br>          
          <b>Príncipe Godoy, Johan:</b><br>
            Para el sprint 2, se realizó la corrección de algunos puntos de la entrega anterior como los user stories, product backlog. De la misma manera, implementé las vistas asignadas para el web application.<br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            Se trabajó en conjunto para mejorar aspectos previos, como las user stories y task stories. También se hizo la correccion del as-is mapping y to-be mapping. Este esfuerzo conjunto nos permitió avanzar en nuestro 
            proyecto de manera efectiva.<br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Se participo con la correción de puntos anteriores, como en el resumen y análisis de entrevistas, el Journey Mapping en su versión As-Is, las User Stories y su Product Backlog. Además, se realizo la recopliación de evidencias para la creación del Sprint 2, correspondiente a esta entrega.<br><br>
        TB2:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
            Elaboración de versión preliminar de los web services y diseño de la base de datos a implementar.<br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            Desarrollo BackEnd orientado a la funcionalidad de la aplicación, correción de entregables anteriores y sprint 3<br><br>          
          <b>Príncipe Godoy, Johan:</b><br>
            Elaboración del sprint planning 3, sprint planning 3, colaboracion con Fronted y Backend del proyecto<br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            Sprint 3, documentación, heurísticas y colaboración en el desarrollo Frontend<br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Se participo en la siguiente mejora de la Web App, así como con las entrevistas, videos About-The-Team y About-The-Product; y la documentación correspondiente al desarrollo del Sprint 3, correspondiente a esta entrega.<br><br>
        TF:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
            <br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            <br><br>          
          <b>Príncipe Godoy, Johan:</b><br>
            <br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            <br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Se participo en la corrección de los últimos detalles que se presentaron en el apartado Frontend. A su vez, se procuro adaptar los datos necesarios para una conexión exitosa a los Web Services.
      </td>
      <td>
        TB1:<br>
          Se llevó a cabo un análisis completo que ayudo a identificar a nuestros potenciales clientes, evaluando a la competencia y como enfrentarla. El desarrollo del proyecto incluyó la elaboración de diversos mapas para entender todo de mejor manera. En general, se aseguro el cumplimiento de todas las tareas encomendadas y para dar un enfoque sólido y bien fundamentado al proyecto.<br><br>
        TP:<br>
          Se ha trabajado de forma colaborativa para la mejora del proyecto, tanto en la modificación del repositorio del reporte como en la creación y despliegue de la aplicación web. Durante el sprint se han corregido puntos previos, lo que ha permitido avanzar de manera efectiva en nuestro proyecto. Nuestro esfuerzo conjunto y colaborativo ha sido fundamental para alcanzar los objetivos establecidos en cada fase del desarrollo.<br><br>
        TB2:<br>
          Se revisaron los errores previos para desplegar la versión definitiva del frontend y se ideo el desarrollo y futura implementación del backend. Nuestro esfuerzo conjunto y colaborativo ha sido fundamental para alcanzar las metas que se plantearon para esta entrega y acercarnos más a la versión definitva de la futura entrega.<br><br>
        TF:<br>
      </td>
    </tr>
    <tr>
      <td>
        <b>Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.</b>
      </td>
      <td>
        TB1:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
            Para llevar acabo el desarrollo del LEAN UX y el diagrama UML estudie como funciona el sector de la seguridad ciudadana y como se puede aplicar la tecnología para mejorar la seguridad de los ciudadanos.<br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            Hice uso de lo aprendido dentro del curso de Aplicaciones Web y trabajos anteriores para identificar los problemas a resolver sobre nuestro trabajo. Asimismo, en base a lo aplicado como analizar nuestro público objetivo, las estrategias frente a nuestros competidores, las entrevistas realizadas, y el diseño de los Wireframes y Mock-Ups junto con los UserFlows, Wireflows y el prototipo de la plataforma web, nos sirvio para tener una idea más clara de como avanzar con el trabajo en cuestión.<br><br>     
          <b>Príncipe Godoy, Johan:</b><br>
            Para el cumplimiento de este trabajo usé lo aprendido dentro del curso y proyectos antereriores. De esta manera pude cumplir con los puntos que me fueron asignado como Diagrama de Contexto, Contenedor y Componentes.<br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            Use el conocimiento previamente adquirido en trabajos anteriores para asi poder realizar el proyecto de este curso. Pude realizar con exito el diseño y posterior analisis de entrevistas,user personas, user stories, impact mapping, product backlog y el software configuration management.<br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Se hizo uso del conocimiento previo adquirido en el desarrollo de aplicaciones web, aplicaciones de escritorio y trabajos anteriores. Este conocimiento se vio reflejado en identificar los problemas que deben ser resueltos mediante la recopilación de testimonios a través de entrevistas. Además, sirvio para identificar los colores más adecuados para que la plataforma se vea funcional y sea atractiva al usuario.<br><br>
        TP:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
            Trabaje con el BC del reporte de incidentes. Hice uso del framework VueJs para el desarrollo de la App web,utilizando el UI PrimeVue y Primeblocks<br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            Hice uso de los nuevos conocimientos que aprendí en el curso junto con la retroalimentación dada por el profesor para corregir los errores del envío pasado. Esto me sirvió para seguir mejorando en el proyecto además que con lo aprendido en clase me sirvió para avanzar la Web Application.<br><br>
          <b>Príncipe Godoy, Johan:</b><br>
            Se realizó la implementación del Sprint 2, para la cual se realizó reunionen con el grupo para definir el alcance y los objetivos que tendríamos con esta entrega. Asimismo, hubo frecuente comunicación para conocer los constantes avances durante la entrega.<br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            Se hizo uso de los aprendizajes obtenidos durante el curso y de experiencias previas para rectificar las inconsistencias en nuestro informe y aplicaciones. Este saber se manifestó en la mejora del diseño de las plataformas y en la elaboración de un informe actualizado que cumple de manera más precisa con los requisitos del curso.<br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Se utilzo lo aprendido durante el curso y de manera previa para corregir los errores existentes en nuestro informe y aplicaciones. Este conocimiento se vio reflejado dar un mejor diseño a las plataformas y en presentar un nuevo informe mejorado, más apegado a lo que se espera en el curso.<br><br>
        TB2:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
            Se incorporaron los conocimientos adquiridos para depurar el informe previo y optimizar el rendimiento de las aplicaciones. Este proceso de aprendizaje permitió perfeccionar el diseño de ambas plataformas, dando como resultado un nuevo informe que se ajusta a los criterios establecidos en el curso.<br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            Se utilizo la información disponible para diseñar un backend que se adapte alas necesidades de la aplicación.<br><br>          
          <b>Príncipe Godoy, Johan:</b><br>
            Se corrigieron los errores presentes en nuestro informe y se optimizo el funcionamiento de las aplicaciones. Esta experiencia permitió mejorar el diseño de ambas plataformas y presentar un nuevo informe más alineado con las expectativas del curso.<br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            Se analizao toda la información recopilda hasta el momento para orientar el diseño de una nueva versión de la plicación web.<br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Se aplicaron los conocimientos adquiridos para corregir los errores existentes en nuestro informe y mejorar el funcionamiento de las aplicaciones. Este conocimiento permitio mejorar el dieños de ambas plataformas y presentar un nuevo informe más apegado a lo que se espera en el curso.<br><br>
        TF:<br><br>
          <b>Escalante Baygorrea, Janiel Franz:</b><br>
            <br><br>
          <b>Noriega Suschenko, Anatoly Andrey:</b><br>
            <br><br>          
          <b>Príncipe Godoy, Johan:</b><br>
            <br><br>
          <b>Rodriguez Zuluoeta, Andres Fernando:</b><br>
            <br><br>
          <b>Zarate Caceres, Victor Ernesto:</b><br>
            Los distintos métodos y temas aprendidos durante el curso sirvieron para concatenar las istintas piezas que se fueron creando a lo largo del camino para culminar en esta entrega final.
      </td>
      <td>
        TB1:<br><br>
          Se aplicó toda la experiencia y conocimientos previos para abordar el trabajo de manera efectiva. Esto incluyó el análisis de problema, la identificación del público objetivo, y el diseño de la plataforma.<br><br>
        TP:<br>
          La efectividad en la comunicación fue de gran utilidad para corregir los errores previos y mejorar el proyecto. Esto no solo ayudó a mantener al equipo alineado con las metas del proyecto, sino que también aseguró que todos los intereses sean tomados en cuenta para tomar mejores decisiones. Esto resultó en una mayor integración del equipo y en la optimización de los recursos y tiempos del proyecto.<br><br>
        TB2:<br>
          Nuestra aplicación web siempre ha sido diseñada teniendo en cuenta la usabilidad y la accesibilidad, haciéndola sencilla y fácil de usar. Al hacer que la tecnología sea más accesible, este enfoque ayuda a las personas a sentirse mejor y a estar más conectadas. Nuestros Servicios web están construidos con medidas de seguridad de primer nivel para garantizar la privacidad de nuestros usuarios.<br><br>
        TF:<br>
			</td>
		</tr>
	</table>
</div>

# Capítulo I: Introducción
## 1.1. StartUp Profile
### 1.1.1. Description de la StartUp

<div align="justify">
  La idea de crear PeaceApp nace ante la creciente ola de inseguridad ciudadana en Lima, y en todo el país. Según el INEI, el 45,6% de ciudadanos de Lima se siente inseguros de vivir en dicha ciudad, con un registro de mas de 75 mil denuncias por hurtos y/o asaltos. Para enfrentar esta situación, la aplicación brindara un mapa con información de las calles, resaltando el nivel de peligro en las distintas zonas de la ciudad. Ante esto, el usuario podrá hacer denuncias ante los crímenes a través de fotos, audios y/o videos, en tiempo real, pudiendo brindar sus datos o hacerlo de manera anónima. Además, el ciudadano podrá compartir su ubicación con sus contactos cercanos para que monitoreen su trayecto y enviar mensajes de emergencia a la policía nacional, bomberos o ambulancia, usando un sistema de marcación rápida.
  <ul>
    <li><b>Misión:</b></li>
    Nuestra misión es garantizar la seguridad de nuestros usuarios, para que puedan transitar sin miedo alguno por las distintas calles del Perú.
    <li><b>Visión:</b></li>
    Vemos el mundo en constante cambio y buscamos ser parte de ello. Creemos que todas las personas deben poder sentirse seguras de vivir y transitar en su propio país y que los gobiernos deben encargarse de ello. Por ello, buscamos ser conocidos como líderes en el mercado de seguridad por nuestra labor para todos nuestros usuarios.
  </ul>
</div>

### 1.1.2. Perfiles de Integrantes del equipo

|    Nombre Completo del integrante   | Descripcion de Carrera | Fotografía | Conocimientos y Habilidades a apuntar|
| ------------------------------------| ---------------------- | ---------- | ------------------------------------ |
| Escalante Baygorrea, Janiel Franz   | Ingenieria de Software <br>Universiad Peruana de Ciencias Aplicadas | ![Franz Escalante](./assets/Franz.jpeg)  | Conocimientos en lenguajes de Programación como C++, Java, HTML, CSS.<br>Me considero que soy una persona muy trabajadora. |
| Noriega Suschenko, Anatoly Andrey   | Ingeniería de Software<br> 5to Ciclo<br>2024-1<br>Universidad Peruana de Ciencias Aplicadas | ![Anatoly Noriega](./assets/Anatoly.png) | - Conocimientos en lenguajes de Programación como C++, Python, HTML, CSS.<br>-Considero que soy una persona muy perseverante y que sabe trabajar en equipo. |
| Príncipe Godoy, Johan               | Ingenieria de Software <br>Universiad Peruana de Ciencias Aplicadas | ![Johan Príncipe](./assets/Johan.jpg) | - Conocimiento en lenguajes de programación como C++, Python, HTML, CSS, JS, SQL, MongoDB. <br> - Me considero una persona comprometida y perseverante para lograr lo mejor con el equipo. |
| Rodriguez Zuluoeta, Andres Fernando | Ingenieria de Software <br>Universiad Peruana de Ciencias Aplicadas | ![Andres Rodriguez](./assets/Andres.jpg) | Tengo conocimiento de lenguaje de programación como C ++ y Python. Me considero una persona centrada y responsable al momento de realizar trabajos en grupo. |
| Zarate Caceres, Victor Ernesto      | Ingeniería de Software<br>Universidad Peruana de Ciencias Aplicadas | ![Ernesto Zarate](./assets/ernesto.png)  | - Conocimiento de Programación en C++, Python, HTML, CSS, MAtLab y SQL.<br>-Me considero una persona responsable, capaz de aportar ideas para el proyecto.<br>-Tengo el compromiso de trabajar de manera eficiente y cumplir con los plazos de entrega. |

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

<div align="justify">
  <ul>
    <li>
      <b>What (Qué): </b>PeaceApp esta enfocada en ayudar a los usuarios en su día a día, teniendo como objetivo crear una comunidad entre usuarios y autoridades para mantener información
      detallada y confiable de las calles en todo el Perú. Tambien, nos encargaremos de mantener el sistema actualizado para que funcione de manera óptima. 
    </li>
    <li>
      <b>When (Cuándo): </b>PeaceApp estara lista para funcionar las 24 horas del día, cada día de la semana. Con esto se busca que la base de datos tenga información verificada y actualizada en todo momento. 
    </li>
    <li>
      <b>Where (Dónde): </b>PeaceApp esta hecha para ser utilizada en cualquier momento y lugar, pues funcionara en base a la ubicación del usuario. Además de que las distintas autoridades deben estar al tanto de la situación actual de su jurisdicción.
    </li>
    <li>
      <b>Who (Quién): </b>Los personas más afectadas por la delincuencia veran mejoras en la situación de sus distritos. Estos, a su vez, tendrán la capacidad de colaborar con mantener la información actualizada, por medio de una herramienta integrada, que les permitirá publicar sobre los distintos sucesos que observan y ponerse en contacto rápidamente con las 
      autoridades con las cuales se relaciona PeaceAppp (comisarías, bomberos, hospitales, municipalidades, etc.).
    </li>
    <li>
      <b>Why (Por qué): </b>PeaceApp fue creada para enfrentar la creciente delincuencia en la ciudad de Lima y en todo el país. Esta tiene el objetivo de informar sobre los sucesos más recientes del entorno del usuario y ayudar a otros usuarios y a las municipalidades a prevenir estas situaciones en el futuro.
    </li>
    <li>
      <b>How (Cómo): </b>PeaceApp tiene un personal altamente capacitado para mantener actualizada y funcional la base de datos de los distritos y ciudades en todo el Perú, para mantener a nuestros usuarios con la información actualizada sobre las calles que transitará. Además, se podrá compartir información con otros usuarios y autoridades para tomar las medidas correspondientes y que verifiquen la veracidad de todo lo que se publique. 
    </li>
    <li>
      <b>How Much (Cuánto):</b>PeaceApp estara disponible de forma gratuita para todas las personas naturales. Además, tendrá disponible una licencia de uso para las entidades, como municipalidades. Así, estas tendrán un acceso preferencial a los datos recopilados y puedan utilzarlos para tomar acción directa en contra de la delincuencia. 
    </li>
  </ul>
</div>

### 1.2.2 Lean UX
#### 1.2.2.1. Problem Statements
<div align="justify">
  El propósito de nuestro servicio es ofrecer rutas seguras, diseñadas en base a la ubicación de partida y la de llegada del usuario. A través de nuestro servicio, los usuarios tienen acceso a un mapa de calor de la peligrosidad de las zonas de lima. Las actualizaciones de las zonas de peligrosidad se haran en base a reportes de los usuarios de
  la aplicación. Por otro lado, las entidades que trabajen con nosotros podrán tener acceso a esta información y sus respectivos datos estadísticos. Estos datos pueden ser
  usados para plantear una estrategía contra la delincuencia.

  Hemos observado la insatisfacción de los clientes con respecto a la seguridad. Actualmente, los hurtos en la calle son comunes en la ciudad de Lima. Según Osiptel, la mayor
  cantidad de robos de celulares por hora se reportan los lunes, esto sería aproximadamente 366 equipos móviles en promedio. Por otro lado, Según el último resultado
  de la ENAPRES para el semestre móvil Ene-Jun 2023 publicado por el INEI, el 26.9% de la población de 15 años de edad, a más, a nivel nacional, ha sido victima de algún
  hecho delictivo.

  ¿De qué forma podemos evitar los hurtos en la calle cuando se encuentran recorriendo una ruta?
</div>

#### 1.2.2.2. UX Assumptions
<div align="justify">
  Ahora que hemos analizado la problematica y tenemos un panorama de cómo solucionar el problema, debemos saber que empresas tienen características similares a las nuestras y cómo estas se han ido desarrollando a través del tiempo.
  La aplicación UrSafe es similar a la nuestra, esta aplicación permite ver un mapa con lugares seguros y te permite comunicarte con familiares, amigos y el 911 en caso de peligro.<br>
  <b>Assumptions:</b>
  <ul>
    <li>Los ciudadanos de Lima necesitan una app que les muestre rutas seguras para movilizarse a través de la ciudad de Lima.</li>
    <li>Los ciudadanos necesitan sentirse parte de una comunidad en la que se puedan reportar incidentes y verlo reflejado en un mapa que les permite visualizar las zonas más seguras de su ciudad.</li>
    <li>Mis clientes serán ciudadanos y entidades preocupadas por la seguridad de su distrito o trabajadores.</li>
    <li>Generaré ingresos vendiendo nuestra aplicación web a municipalidades, instituciones del estado e interesados en el tema de la seguridad.</li>
    <li>No tengo ningún competidor en el mercado actualmente.</li>
    <li>Las entidades que trabajen con nuestra aplicación podrán obtener datos de vital importancia para combatir la criminalidad.</li>
    <li>Los ciudadanos de a pie estarán interesados en esta aplicación.</li>
    <li>Las entidades públicas de este país necesitan este tipo de aplicaciones para combatir la criminalidad con más eficacia.</li>
  </ul>

  <b>Business outcomes:</b>
  <ul>
    <li>Generar ingresos con la aplicación</li>
    <li>Mejorar la calidad de la vida de los ciudadanos del Perú</li>
    <li>Reducir la cantidad de robos que ocurren en el país</li>
  </ul>

  <b>User outcomes:</b>
  <ul>
    <li>¿Quién es el usuario?</li>  
    Cualquier ciudadano que se encuentre en una zona en la que una entidad este asociada con nosotros. Por otro lado, las entidades públicas como municipalidades, PNP, etc. También empresas privadas interesadas en contar con esta aplicación para sus trabajadores, de preferencia extranjeros que no conocen bien las calles de la ciudad.
    <li>¿Dónde encaja nuestro producto en su trabajo o vida?</li>  
    Encaja en su vida diaria, ya que con nuestra aplicación podrá movilizarse por la ciudad evitando riesgos
    <li>¿Qué problemas tiene nuestro producto?</li>  
    Un problema que tiene nuestro producto es que para geenera ingresos, dependemos exclusivamente de las entidades que se van a asociar con nosotros
    <li>¿Cuándo y cómo es usado nuestro producto?</li>  
    Nuestros usuarios utilizarían la aplicación cuando tengan que pasar por lugares que no conocen o deseen reportar un incidente para que otros ciudadanos tengan cuidado.
    Por otro lado, las entidades podrán recopilar información de los ciudadanos y esto les facilitará tomar acciones para combatir la criminalidad en ciertas areas.
    <li>¿Qué características son importantes?</li> 
    Sera una aplicación sencilla de usar para los usuarios y que las información se accesible de una manera sencilla.
    <li>¿Cómo debe verse nuestro producto y comportarse?  
    Nuestra app debe tener una buena selección de colores para que sea agradable a la vista. Además el registro debe ser fácil para todos los usuarios.</li>
  </ul>
  <b>User benefits:</b>
  <ul>
    <li>Evitar robos y cualquier tipo de incidentes que ponga en peligro al usuario al movilizarse por la ciudad.</li>
    <li>Información en tiempo real de zonas peligrosas mediante el uso del mapa de calor.</li>
    <li>Información de rutas seguras para movilizarse mediante el mapa.</li>
    <li>Acceso a datos estadísticos para comprender mejor el problema.</li>
  </ul>
</div>

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hypothesis Statement 01**  
  **Creemos que** las entidades publicas y privadas estarán interesadas en nuestro producto  
  **Sabremos que** hemos tenido éxito  
  **Cuando** podamos trabajar con un mapa de calor de toda la ciudad de Lima
- **Hypothesis Statement 02**  
  **Creemos que** la aplicación logrará formar una comunidad interesada en la seguridad  
  **Sabremos que** hemos tenido exito  
  **Cuando** tengamos se perciba un aumento en la cantidad de usuarios registrados diariamente.
- **Hypothesis Statement 03**  
  **Creemos que** la disponibilidad de datos de vital importancia permitarán a distintas entidades planificar una estrategia contra la delincuencia  
  **Sabremos que** se está cumpliendo ese objetivo  
  **Cuando** se perciba una disminución en los reportes de criminalidad sin que se reduzca la cantidad de usuarios
- **Hypothesis Statement 04**  
  **Creemos que** nuestra aplicación será usada a nivel nacional  
  **Sabremos que** hemos tenido exito  
  **Cuando** la aplicación sea adquirida por la mayoria de las entidades de distintas ciudades del Perú

#### 1.2.2.4. Lean UX Canvas

A continuación se puede ver el Lean UX Canvas trabajado por el equipo:
![Imagen de Lean-UX Canvas](https://i.postimg.cc/QdBzp4FY/Lean-UX-Canvas-Template.jpg)
Enlace para acceder a Miro: https://miro.com/app/board/uXjVKZpPpnQ=/?share_link_id=692620192853

## 1.3. Segmentos objetivo
### Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos
<div align="justify">
  En muchos centros urbanos, la seguridad pública sigue siendo una preocupación mayor para los ciudadanos que buscan maneras efectivas de protegerse en su día a día. Aplicaciones como PeaceApp podrían ofrecer soluciones prácticas para estos desafíos. Según un estudio del Banco Mundial sobre seguridad urbana, la implementación de tecnologías que aumentan la percepción y la realidad de la seguridad puede tener impactos significativos en la reducción del crimen y la mejora de la calidad de vida urbana (Banco Mundial, 2017).
</div>

### Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana
<div align="justify">
  Las entidades gubernamentales, desde la policía local hasta los planificadores urbanos, enfrentan retos constantes para mejorar la eficiencia de sus respuestas y estrategias de prevención del crimen. Según la Organización de las Naciones Unidas, el acceso a datos precisos y actualizados es crucial para la planificación efectiva de la seguridad y el desarrollo urbano (Naciones Unidas, 2019). Herramientas como PeaceApp, que proporcionan datos en tiempo real y facilitan la comunicación entre ciudadanos y autoridades, son esenciales para desarrollar respuestas más rápidas y fundadas a los problemas de seguridad pública.
</div>

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
<div align="justify">
  <table>
    <tr>
      <td colspan="3">Citizen<br>Link: https://citizen.com/</td>
      <td colspan="4">Citizen es una aplicación de seguridad pública que alerta a los usuarios sobre incidentes cercanos en tiempo real, como crímenes o emergencias. Fomenta la participación comunitaria al permitir a los usuarios transmitir videos en vivo y compartir alertas, ayudando a mantener informada a la comunidad sobre situaciones de seguridad cercanas.</td>
    </tr>
    <tr>
      <td colspan="3">Safetipin<br>Link: https://safetipin.com/</td>
      <td colspan="4">Safetipin es una herramienta de seguridad personal que permite a los usuarios calificar la seguridad de diferentes áreas basándose en criterios como iluminación y presencia de personas. Proporciona un mapa de seguridad para ayudar a otros a tomar decisiones informadas sobre dónde ir y cómo moverse de manera segura.</td>
    </tr>
    <tr>
      <td colspan="3">SafeMapp<br>Link: https://www.linkedin.com/company/safemapp/</td>
      <td colspan="4">SafeMapp ofrece una plataforma para informar y consultar sobre áreas seguras e inseguras, creando un mapa interactivo de alertas de seguridad. Permite a los usuarios enviar alertas SOS a contactos de emergencia y navegar por rutas seguras, mejorando la seguridad personal y comunitaria.</td>
    </tr>
    <tr>
      <td colspan="3">URSafe<br>Link: https://ursafe.com/</td>
      <td colspan="4">URSafe es una aplicación de seguridad personal avanzada que utiliza reconocimiento de voz y geolocalización para activar alertas de emergencia. Los usuarios 
      pueden configurar frases clave que, al ser pronunciadas, envían notificaciones a contactos seleccionados, facilitando una rápida respuesta en situaciones de peligro.</td>
    </tr>
  </table>
</div>

### 2.1.1. Análisis competitivo.
<div align="justify">
  <table>
    <tr>
      <th colspan="22">Competitive Analysis Landscape</th>
    </tr>
    <tr>
      <td colspan="1">¿Por qué llevar a cabo el análisis?</td>
      <td colspan="17">Este análisis nos ayuda a entender las particularidades de cada sitio web o aplicación, identificar la competencia en el mercado y planificar cómo abordar las oportunidades. También nos permite trabajar en la mejora continua de nuestras áreas de desarrollo.</td>
    </tr>
    <tr>
      <td colspan="2"></td>
      <td>Citizen<br><img src="./assets/Citizen.png" alt="Citizen"></td>
      <td>Safetipin<br><img src="./assets/Safetipin.png" alt="Safetipin"></td>
      <td>SafeMapp<br><img src="./assets/SafeMapp.png" alt="SafeMapp"></td>
      <td>URSafe<br><img src="./assets/URSafe.png" alt="URSafe"></td>
    </tr>
    <tr>
      <td rowspan="2">Perfil</td>
      <td>Overview</td>
      <td>Aplicación que proporciona a los usuarios información en tiempo real sobre incidentes de seguridad como crímenes, accidentes y emergencias en un área local.</td>
      <td>Aplicación que evalúa la seguridad de una ubicación específica mediante la recopilación de datos sobre iluminación, visibilidad, presencia policial, transporte público y otros factores relevantes para la seguridad.</td>
      <td>Aplicación que proporciona mapas de calor de seguridad y herramientas de navegación para ayudar a los usuarios a moverse de manera segura por la ciudad.</td>
      <td>Aplicación de seguridad personal que ofrece funciones de seguimiento en tiempo real, alertas de seguridad y asistencia en casos de emergencia.</td>
    </tr>
    <tr>
      <td>Ventaja Competitiva</td>
      <td>Proporciona datos actualizados y colaborativos para mejorar la conciencia de seguridad en la comunidad.</td>
      <td>Ofrece información precisa y práctica para ayudar a los usuarios a tomar decisiones informadas sobre su seguridad personal.</td>
      <td>Proporciona consejos de seguridad personalizados y alertas adaptadas a las necesidades individuales de los usuarios.</td>
      <td>Ofrece herramientas prácticas y útiles para ayudar a los usuarios a mantenerse seguros en diversas situaciones y entornos.</td>
    </tr>
    <tr>
      <td rowspan="2">Perfil de Marketing</td>
      <td>Mercado Objetivo</td>
      <td>Ciudadanos urbanos interesados en la seguridad en tiempo real y la colaboración comunitaria.</td>
      <td>Residentes y viajeros buscando evaluar la seguridad de áreas específicas.</td>
      <td>Usuarios urbanos preocupados por la seguridad, buscando información y consejos personalizados.</td>
      <td>Personas que buscan herramientas prácticas para mejorar su seguridad personal.</td>
    </tr>
    <tr>
      <td>Estrategias de Marketing</td>
      <td>Publicidad en línea.</td>
      <td>Publicidad en línea.</td>
      <td>Publicidad en línea.</td>
      <td>Publicidad en línea.</td>
      </tr>
    <tr>
      <td rowspan="3">Perfil de Producto</td>
      <td>Productos y Servicios</td>
      <td>- Ofrece alertas en tiempo real sobre incidentes de seguridad o delitos.<br>- Permite a los usuarios informar sobre incidentes y compartir información con otros residentes.<br>- Proporciona datos actualizados para mejorar la conciencia de seguridad en la comunidad mediante su plataforma.</td>
      <td>- Proporciona mapas detallados de seguridad.<br>- Ofrece evaluaciones de seguridad basada en la iluminación, visibilidad, etc.<br>- Aconseja a los usuarios a tomar decisiones informadas sobre su seguridad personal.</td>
      <td>- Ofrece mapas de seguridad detallados y evaluaciones de riesgo en diversas áreas.<br>- Proporciona consejos de seguridad personalizados y alertas adaptadas a las necesidades de usuario.<br>- Ofrece información específica sobre el entorno del usuario.</td>
      <td>- Proporciona herramientas para la seguridad personal: alertas de emergencia y seguimiento en tiempo real.<br>- Permite establecer contactos de emergencia y enviar notificaciones automáticas en situaciones desfavorables.<br>- Ofrece un enfoque práctico y útil para ayudar a los usuarios a mantenerse seguros en diversas situaciones y entornos.</td>
    </tr>
    <tr>
      <td>Precios y Costos</td>
      <td>Gratuito</td>
      <td>Gratuito/Servicios premium</td>
      <td>Gratuito/Servicios premium</td>
      <td>Gratuito/Servicios premium</td>
    </tr>
    <tr>
      <td>Canales de distribución (Web y/o Móvil)</td>
      <td>Aplicación móvil de iOS y Android</td>
      <td>Aplicación móvil de iOS y Android</td>
      <td>Aplicación móvil de iOS y Android</td>
      <td>Aplicación móvil de iOS y Android</td>
    </tr>
    <tr>
      <td rowspan="4">Análisis SWOT</td>
      <td>Fortalezas</td>
      <td>- Interfaz intuitiva y fácil de usar para reportar incidentes y alertas.<br>- Gran base de usuarios en areas urbanas densamente pobladas.<br>- Actualizaciones en tiempo real sobre incidentes de seguridad.</td>
      <td>- Ofrece evaluaciones de seguridad detalladas basadas en multiples factores<br>- Interfaz amigable y fácil de usar.<br>- Colaboraciones con organismos gubernamentales y organizaciones de seguridad.</td>
      <td>- Enfoque en proporcionar consejos de seguridad personalizados y alertas adaptadas a las necesidades de los usuarios.<br>- Interfaz intuitiva y fácil de usar.<br>- Potencial para crear una comprometida y activa a través de funciones de participación y colaboraciones</td>
      <td>- Proporciona herramientas prácticas para mejorar la seguridad personal.<br>- Interfaz intuitiva y facil de usar.<br>- Potencial para desarrollar asociaciones estratégicas con empresas de seguridad y proveedores de servicios de emergencia para mejorar la eficacia y la cobertura de la aplicación.</td>
    </tr>
    <tr>
      <td>Debilidades</td>
      <td>- Dependencia de la participación activa de la comunidad para reportar incidentes.<br>- Posible vulnerabilidad a la propagación de información errónea o falsa.<br>- Competencia creciente de otras aplicaciones de seguridad ciudadana.</td>
      <td>- Dependencia de la retroalimentación de los usuarios para recopilar datos de seguridad.<br>- Posible falta de precisión en evaluaciones de seguridad.<br>- Competencia creciente de otras aplicaciones y servicios que ofrecen información similar sobre seguridad urbana.</td>
      <td>- Dependencia activa de los usuarios para mantener actualizada la información sobre seguridad.<br>- Posible falta de fiabilidad en la información proporcionada por usuarios individuales.<br>- Competencia de otras aplicaciones y servicios que ofrecen consejos de seguridad y alertas personalizadas.</td>
      <td>- Dependencia de la participación activa de los usuarios para reportar incidentes.<br>- Posible falta de confiabilidad en la precisión de las alertas de seguridad.<br>- Competencia de otras aplicaciones y dispositivos de seguridad personal que ofrecen características similares.</td>
    </tr>
    <tr>
      <td>Oportunidades</td>
      <td>- Expansión de nuevas ciudades y regiones.<br>- Colaboraciones con agencias gubernamentales y organismos de seguridad.<br>- Incorporación de nuevas funciones como servicios de seguridad personalizada para usuarios premium.</td>
      <td>- Expansión a nuevas ciudades y países.<br>- Desarrollo de asociaciones estratégicas con empresas de transporte y servicios publicos.<br>- Incorporación de nuevas funciones como alertas de seguridad en tiempo real para usuarios premium.</td>
      <td>-  Expansión a nuevas ciudades y regiones.<br>- Desarrollo de asociaciones con empresas de seguridad privada o proveedores de servicios de emergencia.<br>- Incorporación de nuevas funciones como asistencia en tiempo real o acompañamiento para usuarios premium.</td>
      <td>- Expansión a nuevas regiones y mercados.<br>- Desarrollo de características innovadoras como integración con dispositivos wearables o servicios de asistencia personalizada.<br>- Incorporaciones de planes premium con funciones avanzadas como monitoreo de seguridad las 24 horas o servicios de asesoramiento de seguridad personal.</td>
    </tr> 
    <tr>
      <td>Amenazas</td>
      <td>- Cambios en la legislación de privacidad de datos que pueda afectar a la recopilación de la información del usuario.<br>- Riesgo de incidentes de seguridad cibernética que comprometan
      con la integridad y la confianza.<br>- Posible perdida de confianza de los usuarios debido a la incapacidad de la aplicación para prevenir o responder de manera inmediata.</td>
      <td>- Riesgo de perdida de confianza de los usuarios debido a la inclusión de datos incorrectos o sesgados.<br>- Posible resistencia por parte de las autoridades locales o empresas afectadas
        por las evaluaciones de seguridad negativas.<br>- Vulnerabilidad a la manipulación por parte de usuarios malintencionados que intentan distorsionar la percepción de la seguridad</td>
      <td>- Riesgo de perdida de confianza de los usuarios debido a la incapacidad de la aplicacion.<br>- Posible exposición a riesgos legales relacionados con la privacidad de datos y la 
        responsabilidad por la seguridad de los usuarios.<br>- Vulnerabilidad a la manipulación por parte de usuarios malintencionados que intentan difundir información falsa o engañosa.</td>
      <td>- Riesgo de perdida de confianza de los usuarios debido a la incapacidad de la aplicación para responder eficazmente a emergencias.<br>- Posible exposición a riesgos legales relacionados
      con la privacidad de los datos.<br>- Vulnerabilidad a la competencia agresiva de otras empresas que ofrecen soluciones de seguridad personal más establecidas o con mayores recursos financieros.</td>
    </tr>
  </table>
</div>


### 2.1.2. Estrategias y tácticas frente a competidores.

<div align="justify">
  Para asegurar una posición líder en el mercado de aplicaciones de seguridad ciudadana, PeaceApp se enfocará en una estrategia de diferenciación basada en la hiperlocalización y la participación
  comunitaria. Esta estrategia se complementará con el desarrollo de tecnología de mapeo avanzada que proporcione datos precisos y actualizados sobre la seguridad en áreas específicas, aprovechando
  informes en tiempo real de los usuarios. Este enfoque no solo resalta nuestras fortalezas, como la capacidad de proporcionar información detallada y relevante, sino que también nos permite explorar
  nuevas oportunidades al expandirnos a nuevas regiones y colaborar con agencias gubernamentales y de seguridad.<br>
  En respuesta a las debilidades del sector, como la dependencia de la retroalimentación activa de los usuarios y la vulnerabilidad a la información incorrecta, PeaceApp implementará mecanismos robustos
  de verificación de datos para asegurar la confiabilidad de la información compartida. Esto ayudará a mitigar las amenazas como la pérdida de confianza del usuario y los posibles riesgos legales 
  relacionados con la privacidad de los datos. Al mismo tiempo, estas alianzas y mejoras tecnológicas reforzarán nuestra posición frente a competidores establecidos y emergentes, permitiendo a PeaceApp 
  ofrecer un servicio indispensable para la seguridad personal y comunitaria, y responder de manera efectiva a las emergencias.
</div>

## 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.
<div align="justify">
  <b>Introducción antes de la entrevista:</b><br>
  Buenos días/ tardes/ noches. Le agradezco de antemano que haya aceptado la entrevista. Nuestro objetivo es recopilar información de nuestros potenciales usuarios, para el desarrollo de un proyecto que
  consiste en un servicio que ofrece rutas seguras, diseñadas en base a la ubicación de partida y la de llegada del usuario. Además de que los usuarios tienen acceso a un mapa de calor de la peligrosidad
  de las zonas de lima que serán actualizadas en base a reportes de los usuarios de la aplicación.<br><br>
</div>

<b>Preguntas Personales:</b>

1.  ¿Cuál es su nombre?
2.  ¿Cuántos años tiene?
3.  ¿Qué destinos frecuenta y cómo se transporta a estos?
4.  ¿Cómo se siente con respecto a la delincuencia al paso?
5.  ¿Qué tan familiarizado está con las aplicaciones de mapas virtuales?

#### Segmento objetivo (Ciudadanos):

**Preguntas principales:**

1. ¿Cómo te desplazas habitualmente por la ciudad?<br>
2. ¿Conoces que zonas de Lima son las más peligrosas?<br>
3. ¿Has tenido alguna vez preocupaciones sobre la seguridad en ciertas zonas de la ciudad?<br>
4. ¿Utilizas alguna aplicación o servicio para planificar tus rutas? Si es así, ¿cuál?<br>
5. ¿Qué características valoras más en un servicio de planificación de rutas?<br>
6. ¿Estarías dispuesto a compartir tus experiencias de seguridad para ayudar a actualizar un mapa de calor de peligrosidad?<br>
7. ¿Cómo te gustaría recibir actualizaciones sobre las zonas de peligrosidad?<br>
8. ¿Qué tipo de datos estarías dispuesto a compartir para mejorar la seguridad de las rutas?<br>
9. ¿Estarías interesado en recibir recomendaciones de rutas seguras basadas en tu ubicación?<br>
10. ¿Cuánto valoras la seguridad en comparación con la eficiencia (por ejemplo, el tiempo de viaje) al elegir una ruta?<br>
11. ¿Qué navegadores web utilizas con más frecuencia?<br>
12. ¿Cuánto tiempo estás dispuesto a esperar que una página web se cargue antes de considerarla demasiado lenta?<br>
13. ¿Qué dispositivos móviles utilizas para acceder a aplicaciones web (marca)?<br>

#### Segmento objetivo (Gerentes de entidades publicas o empresas):

- **Preguntas generales:**
  - ¿Cuál es tu nombre?
  - ¿Qué edad tienes?
  - ¿Dónde vives actualmente?
  - ¿A qué te dedicas?
- **Preguntas objetivas:**

  - ¿Cuál es tu cargo o función en el área de seguridad de la entidad?
  - ¿Con qué frecuencia utilizas aplicaciones o herramientas basadas en mapas para tu trabajo?
  - ¿Qué sistema operativo utilizas principalmente en tu computadora de trabajo?
  - ¿Qué navegador web prefieres utilizar en tu computadora?
  - ¿Qué dispositivo móvil sueles utilizar para acceder a aplicaciones relacionadas con tu trabajo?
  - ¿Qué navegador móvil prefieres para acceder a herramientas o aplicaciones relacionadas con la seguridad?

- **Preguntas subjetivas:**
  - ¿Cómo describirías la importancia del monitoreo de la delincuencia en tu área de responsabilidad?
  - ¿Cuál es tu mayor desafío al utilizar herramientas tecnológicas para mejorar la seguridad en tu entorno?
  - ¿Cuál es tu opinión sobre la integración de la tecnología en el campo de la seguridad ciudadana?

### 2.2.2. Registro de entrevistas.

#### Enlace de las entrevistas: [Enlace](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912668_upc_edu_pe/Ee-KEPn8lOdNmwOa9bFyd4EBSI_z7olPvkuzJgcn3r2WQQ?e=VBFk2G&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

#### Segmento 1:

<div align="justify">
<table>
  <tr>
    <td>Entrevista 1: </td>
    <td>Mauricio Abraham Rivo Rojas Sánchez</td>
  </tr>
  <tr>
    <td colspan="2">
      En la entrevista realizada a Mauricio Abraham Rivo Rojas Sánchez, un joven de 18 años residente de Lima, se destaca su preocupación significativa por la delincuencia en la ciudad. Mauricio
      utiliza principalmente el auto para sus desplazamientos diarios, aunque ocasionalmente utiliza el bus o camina, especialmente cuando se dirige a su lugar de estudio en San Isidro. Reconoce
      áreas como San Juan de Lurigancho y Comas entre las más peligrosas, aunque nota un incremento de la delincuencia en zonas tradicionalmente consideradas seguras como Miraflores y San Isidro.
      Utiliza aplicaciones como Waze para planificar sus rutas, valorando especialmente aquellas que le ofrecen seguridad y eficiencia. Está dispuesto a compartir sus experiencias y recibir 
      actualizaciones en tiempo real para mejorar la seguridad en sus rutas, demostrando un alto grado de compromiso con la mejora de la situación de seguridad en su comunidad.
    </td>
  </tr>
  <tr>
    <td colspan="2"><img src="./assets/Entrevista1.png"></td>
  </tr>
  <tr>
    <td colspan="2">Tiempo en el video: 00:00</td>
  </tr>
</table>
<table>
  <tr>
    <td>Entrevista 2: </td>
    <td>Carlos Leon</td>
  </tr>
  <tr>
    <td colspan="2">
      Carlos prefiere desplazarse en bicicleta o a pie, y evita el transporte público. Aunque conoce de la peligrosidad de algunas zonas de Lima, como el Callao o San Juan de Lurigancho, se siente
      seguro en las rutas que recorre gracias a la presencia de patrulleros o serenos. Carlos usa Google Maps para planificar rutas y valora la exactitud en el tiempo estimado de llegada. A la hora
      de elegir una ruta, valora más la eficiencia en términos de tiempo de viaje, aunque también le importa la seguridad. Menciona estar dispuesto a compartir experiencias de seguridad para mejorar
      un mapa de calor de peligrosidad y le gustaría recibir actualizaciones sobre zonas peligrosas a través de notificaciones móviles. Carlos está dispuesto a compartir información sobre las zonas
      más transitadas o peligrosas de la ciudad y se muestra interesado en recibir recomendaciones de rutas seguras basadas en su ubicación.
    </td>
  </tr>
  <tr>
    <td colspan="2"><img src="./assets/Entrevista2.png"></td>
  </tr>
  <tr>
    <td colspan="2">Tiempo en el video: 07:32</td>
  </tr>
</table>
<table>
  <tr>
    <td>Entrevista 3:</td>
    <td>Fatima Urbina</td>
  </tr>
  <tr>
    <td colspan="2">
      La entrevistada es Fatima Urbina, una joven de 22 años que vive en Lima. Se desplaza a su trabajo en Jesús María utilizando transporte público y a veces taxi por aplicativo o el metropolitano.
      Fatima está familiarizada con las aplicaciones de mapas virtuales y utiliza Moovit para planificar sus rutas.<br> Fatima está consciente de la delincuencia en la ciudad y no se siente completamente
      segura al caminar, especialmente en zonas que considera peligrosas como Comas, San Juan de Lurigancho y San Martín de Porres. Está dispuesta a compartir sus experiencias de seguridad para ayudar a
      actualizar un mapa de calor de peligrosidad y le gustaría recibir actualizaciones sobre las zonas de peligrosidad a través de notificaciones.<br> En cuanto a la elección de rutas, Fatima valora más 
      la seguridad que la eficiencia, incluso si eso significa que su viaje tome más tiempo. Estaría interesada en recibir recomendaciones de rutas seguras basadas en su ubicación.<br> Fatima utiliza
      los navegadores web Safari y Google Chrome y considera que una página web que tarda más de 30 segundos en cargarse es demasiado lenta. Accede a las aplicaciones web a través de su iPhone.<br></td>
  </tr>
  <tr>
    <td colspan="2"><img src="./assets/Entrevista_3.png" alt="Entrevista 3"></td>
  </tr>
  <tr>
    <td colspan="2">Tiempo en el video: 12:53</td>
  </tr>
</table>
</div>

#### Segmento 2:

<div align="justify">
  <table>
    <tr>
      <td>Entrevista 1:</td>
      <td>Silvana Salazar</td>
    </tr>
    <tr>
      <td colspan="2">
        La entrevistada es la jefa de seguridad de una empresa privada en Lima. Utiliza herramientas de mapeo casi a diario para analizar patrones de delincuencia en su zona de operación. Prefiere Windows
        10 como sistema operativo en su computadora de trabajo y Google Chrome como navegador web. Para acceder a aplicaciones relacionadas con su trabajo de seguridad, utiliza un smartphone Android y 
        prefiere Google Chrome como navegador móvil. Considera crucial el monitoreo de la delincuencia para proteger al personal, clientes y activos, y facilitar medidas preventivas y respuestas efectivas 
        ante situaciones de riesgo. Su mayor desafío en el uso de herramientas tecnológicas es asegurar la actualización y compatibilidad de las mismas con las necesidades específicas de seguridad, además 
        de garantizar la integridad y privacidad de los datos. Opina que la integración de la tecnología es esencial para mejorar la seguridad ciudadana, permitiendo la recopilación y análisis eficiente de 
        datos para prevenir delitos y responder rápida y efectivamente ante emergencias.
      </td>
    </tr>
    <tr>
      <td colspan="2"><img src="./assets/interview-4.JPG" alt="Entrevista 4"></td>
    </tr>
    <tr>
      <td colspan="2">Tiempo en el video: 17:07</td>
    </tr>
  </table>
  <table>
    <tr>
      <td>Entrevista 2:</td>
      <td>Jorge Coras</td>
    </tr>
    <tr>
      <td colspan="2">El entrevistado es el coordinador de seguridad ciudadana en la Municipalidad de Lima. Utiliza herramientas de mapeo diariamente para monitorear incidentes, identificar áreas de 
        riesgo y planificar estrategias de seguridad. Prefiere Windows 10 como sistema operativo en su computadora de trabajo y Google Chrome como navegador web debido a su velocidad y compatibilidad 
        con diversas herramientas en línea. Utiliza un smartphone Android para acceder a aplicaciones relacionadas con su trabajo y prefiere Google Chrome en su dispositivo móvil por su funcionalidad 
        y sincronización con su cuenta. Considera que el monitoreo de la delincuencia es vital para garantizar la seguridad de los ciudadanos de Lima, permitiendo identificar tendencias delictivas, 
        implementar medidas preventivas y responder eficazmente a emergencias. Uno de sus mayores desafíos</td>
    </tr>
    <tr>
      <td colspan="2"><img src="./assets/interview-5.JPG" alt="Entrevista 5"></td>
    </tr>
    <tr>
      <td colspan="2">Tiempo en el video: 19:46</td>
    </tr>
  </table>
</div>

### 2.2.3. Análisis de entrevistas.

#### Segmento 1:

<div align="justify">
  Para este segmento objetivo se realizaron entrevistas a Fatima Urbina, Mauricio Abraham Rivo Rojas Sánchez y Carlos Leon, con el 100% de ellos siendo residentes de la ciudad de Lima. En cuanto a las
  características subjetivas, un 66% de los entrevistados mantiene una preocupación común por su seguridad personal en la ciudad. En general se obtuvo que el 100% de los entrevistados está dispuestos a 
  compartir sus experiencias de seguridad para mejorar el mapa de calor de peligrosidad y recibir recomendaciones de rutas seguras en tiempo real. Esto punto nos revelo que el 66% de entrevistados valoran
  la seguridad por encima de la velocidad en la planificación de rutas.<br>
  Por otro lado, en términos objetivos se observo que el 100% de los entrevistados menciona un uso frecuente de la tecnología para la movilidad diaria. Esta disposición sugiere una base de usuarios 
  comprometidos y una potencial comunidad de soporte para el desarrollo y adopción de una aplicación propuesta que integre mapas de calor de seguridad y recomendaciones de rutas personalizadas basadas
  en informes de usuarios y actualizaciones en tiempo real. El 100% de las distintas entrevistas ofrecieron una perspectiva para resaltar la necesidad de una solución tecnológica que proporcione rutas 
  eficientes y seguras, revelando una gran oportunidad en el mercado para nuestra aplicación web.
</div>

#### Segmento 2:

<div align="justify">
  Para este segmento objetivo se realizaron entrevistas a Silvana Salazar y Jorge Coras, siendo ambos residentes de la ciudad de Lima. En las entrevistas se evidencian características comunes, fundamentales
  para comprender el perfil de estos profesionales en el campo de la seguridad.En términos objetivos, el 100% de los entrevistados ha demostrado una tendencia hacia la especialización en la gestión de la
  seguridad, ya sea en el ámbito público o privado. Además, se obtuvo un 100% de confianza de los entrevistados en las herramientas de mapeo en su trabajo diario, lo que resalta la importancia de la tecnología
  para la gestión de la seguridad. En cuanto a preferencias tecnológicas, ambos prefieren Windows 10 como sistema operativo de escritorio y Android, en el apartado móvil. En ambos medios, se confirmo una 
  preferencia del 100% por Google Chrome como navegador web, lo que sugiere una preferencia por la consistencia y la sincronización entre dispositivos en el entorno laboral.<br> En cuanto a las características
  subjetivas, el 100% de los entrevistados resalta la importancia del monitoreo de la delincuencia para garantizar la seguridad de los ciudadanos. Esta preocupación compartida refleja un enfoque común en 
  la prevención y respuesta ante situaciones de riesgo. Además, destacan la necesidad de asegurar la interoperabilidad entre las diferentes herramientas tecnológicas utilizadas y la protección de datos y 
  privacidad de los ciudadanos como desafíos importantes en su trabajo diario.

</div>

## 2.3. Needfinding.

### 2.3.1. User Personas.

Con el objetivo de asegurar un entendimiento detallado y completo de los segmentos que hemos identificado como fundamentales para nuestro proyecto, hemos implementado un proceso meticuloso y riguroso de creación de User Personas. Este proceso nos ha permitido desarrollar un User Persona específico y único para cada uno de estos segmentos objetivos, lo que nos facilita una visión más clara y precisa de nuestros usuarios objetivo. De esta manera, podemos diseñar y ofrecer soluciones que se alineen de manera óptima con sus necesidades y expectativas.

- **UserPersona 1**
  <br>
  <img src="./assets/UserPersona_1.png" alt="UserPersona_1">
  <br>

- **UserPersona 2**
  <br>
  <img src="./assets/UserPersona_2.png" alt="UserPersona_2">
  <br>

### 2.3.2. User Task Matrix.

<div style='text-align: justify;'>
El User Task Matrix es una herramienta que ayuda a identificar y priorizar las tareas que los diferentes segmentos de usuarios realizan para alcanzar sus objetivos. 
En este caso, el User Task Matrix se centra en dos segmentos: Ciudadanos preocupados por su seguridad personal en espacios públicos y Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana. 
La matriz presenta 15 tareas que son importantes para ambos segmentos, con una clasificación de frecuencia y importancia para cada uno. La matriz ayuda a comprender las necesidades y prioridades de cada segmento y a identificar cualquier similitud o diferencia en sus tareas. 
</div>

|                                                                        | Segmento 1             | Segmento 2             |
| ---------------------------------------------------------------------- | ---------------------- | ---------------------- |
| Task                                                                   | Frecuencia - Severidad | Frecuencia - Severidad |
| Identificar zonas inseguras                                            | Alta - Alta            | Alta - Alta            |
| Denunciar delitos                                                      | Alta - Alta            | Alta - Alta            |
| Buscar información sobre delitos                                       | Alta - Alta            | Alta - Alta            |
| Recibir alertas de emergencia                                          | Alta - Alta            | Alta - Alta            |
| Planificar rutas seguras                                               | Alta - Alta            | Alta - Alta            |
| Acceder a recursos de seguridad                                        | Alta - Alta            | Alta - Alta            |
| Analizar datos de delitos                                              | Alta - Alta            | Alta - Alta            |
| Desarrollar políticas de seguridad                                     | Baja - Alta            | Alta - Alta            |
| Implementar medidas de seguridad                                       | Baja - Alta            | Alta - Alta            |
| Monitorear zonas de riesgo                                             | Baja - Alta            | Alta - Alta            |
| Asistir a capacitaciones de seguridad                                  | Media - Alta           | Alta - Alta            |
| Participar en programas de prevención de delitos                       | Media - Alta           | Alta - Alta            |
| Colaborar con la comunidad en temas de seguridad                       | Media - Alta           | Alta - Alta            |
| Evaluar la eficacia de las medidas de seguridad                        | Baja - Alta            | Alta - Alta            |
| Mejorar continuamente la planificación urbana en términos de seguridad | Baja - Alta            | Alta - Alta            |

<div align="justify">
  En el User Task Matrix, se identifican 15 tareas que los usuarios realizan con diferentes frecuencias e importancias, independientemente de la solución de software. Las tareas más frecuentes e importantes para
  ambos segmentos son identificar zonas inseguras, denunciar delitos, buscar información sobre delitos, recibir alertas de emergencia y planificar rutas seguras. El segmento de Ciudadanos preocupados por su 
  seguridad personal en espacios públicos también da importancia a compartir su ubicación con contactos cercanos y enviar mensajes de emergencia, mientras que el segmento de Entidades Gubernamentales responsables
  de la seguridad pública y la planificación urbana destaca la importancia de analizar datos de delitos, desarrollar políticas de seguridad, implementar medidas de seguridad, monitorear zonas de riesgo y mejorar
  continuamente la planificación urbana en términos de seguridad. Ambos segmentos coinciden en la importancia de recibir alertas de emergencia y planificar rutas seguras.
</div>

### 2.3.3. User Journey Mapping.

<div align="justify">
  La siguiente sección ilustra el end-to-end journey de PeaceApp para los segmentos objetivos de Ciudanos preocupados y Entidades Gubernamentales. El User Journey Mapping empieza desde el momento en el que los 
  usuarios conocen a la aplicación, pasando por un proceso de decisión y adaptación a su uso. En este punto, se hace el registro en la aplicación, se registra el uso continuo y la posibilidad de dejar de usalo 
  ante un descontento o haber logrado su objetivo inicial.<br>
</div>

#### Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos

##### As-Is

<img src="./assets/UserJourneyMap_UP1_AsIs1.png" alt="User Journey Map As-Is: User Persona 1" width="80%">

##### To-Be

<img src="./assets/UserJourneyMap_UP1.png" alt="User Journey Map User Persona 1" width="80%">

#### Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana

##### As-Is

<img src="./assets/UserJourneyMap_UP2_AsIs2.png" alt="User Journey Map As-Is: User Persona 2" width="80%">

##### To-Be

<img src="./assets/UserJourneyMap_UP2.png" alt="User Journey Map User Persona 2" width="80%">

### 2.3.4. Empathy Mapping.

**Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos**
<img src="./assets/Empathy_map_UP1.png" alt="Empathy Map User Persona 1" width="80%">

**Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana**
<img src="./assets/Empathy_map_UP2.png" alt="Empathy Map User Persona 2" width="80%"><br>

<div align="justify">
  Para crear un Empathy Map, primero recopilamos información hablando con personas que representan a nuestros usuarios. Les hacemos preguntas sobre sus experiencias y sentimientos, y anotamos todo lo que nos 
  dicen. Luego, organizamos esa información en un gráfico que muestra lo que los usuarios ven, escuchan, dicen, hacen, piensan y sienten. Por ejemplo, podríamos descubrir que muchos usuarios ven situaciones
  estresantes en su entorno, escuchan conversaciones sobre desafíos similares, dicen que están bien cuando se les pregunta pero en realidad están preocupados, hacen ejercicio para aliviar el estrés, piensan 
  en formas de mejorar su bienestar emocional y sienten ansiedad por el futuro. Esto nos da una comprensión más profunda de las necesidades y deseos de nuestros usuarios, lo que nos permite diseñar soluciones
  que realmente los ayuden.
</div>

### 2.3.5. As-is Scenario Mapping.

**Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos**
<img src="./assets/As-Is_Segmento1.jpg" alt="As-Is Map User Persona 1" width="80%">

**Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana**
<img src="./assets/As-Is_Segmento2.jpg" alt="As-Is Map User Persona 2" width="80%">

## 2.4. Ubiquitous Language.
<div align="justify">
  <ul>
    <li><b>Geolocation (Geolocalización):</b> Tecnología que utiliza datos de GPS o internet para determinar la ubicación exacta de un dispositivo.</li>
    <li><b>Heat Map (Mapa de Calor):</b> Es una representación gráfica de datos donde los valores se representan mediante colores.</li>
    <li><b>Hyperlocalization (Hiperlocalización):</b> Técnica avanzada de localización que ofrece información extremadamente precisa y detallada de un área geográfica muy reducida.</li>
    <li><b>Market (Mercado):</b> Es el conjunto de transacciones de bienes y servicios entre compradores y vendedores.</li>
    <li><b>Quick Dial System (Sistema de Marcación Rápida):</b> Funcionalidad que permite a los usuarios contactar servicios de emergencia con sólo pulsar un botón.</li>
    <li><b>Route Monitoring (Monitoreo de Trayecto):</b> Supervisión continua del recorrido de una persona mediante una aplicación para garantizar su seguridad.</li>
    <li><b>Starting Location (Ubicación de Partida):</b> Punto inicial desde donde comienza el recorrido o viaje de un usuario.</li>
    <li><b>Tracking Features (Funciones de Seguimiento):</b> Herramientas que permiten observar y registrar la ubicación o actividad de una persona o objeto en tiempo real.</li>
  </ul>
</div>

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

<div style="text-align: justify">
  El "To-be Scenario Map" representa la visión de la experiencia del usuario una vez que se han implementado las soluciones o mejoras planificadas. 
  Este mapa proporciona una representación visual de cómo queremos que sea la experiencia del usuario en el futuro, destacando las actividades que realizarán, 
  los pensamientos que tendrán y los sentimientos que experimentarán en cada fase del proceso. Al visualizar el futuro deseado, el "To-be Scenario Map" nos ayuda a 
  alinear al equipo en torno a una visión compartida y a identificar las áreas en las que necesitamos enfocarnos para lograr esa experiencia mejorada para el usuario.
</div>

**Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos**

<img src="./assets/To-Be_Segmento1.jpg" alt="To-Be Scenario Map User Persona 1" width="80%">

**Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana**

<img src="./assets/To-Be_Segmento2.jpg" alt="To-Be Scenario Map User Persona 2" width="80%">

## 3.2. User Stories

<table>
  <tr>
    <td align="center">User Story ID</td>
    <td align="center">Título</td>
    <td align="center">Descripción</td>
    <td align="center">Criterios de Aceptación</td>
    <td align="center">Relacionado con (Epic ID)</td>
  </tr>
  <tr>
    <td align="center">EP01</td>
    <td align="justify">Diseño y Desarrollo de la Landing Page</td>
    <td align="justify">Como visitante de la Landing Page, quiero encontrar una landing page bien diseñada y fácil de usar que me proporcione información clara y concisa sobre la aplicación, para poder entender el propósito de la aplicación.</td>
    <td align="justify">No corresponde</td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP02</td>
    <td align="justify">Contacto</td>
    <td align="justify">Como visitante de la Landing Page, quiero contactarme con las personas encargadas en el desarrollo de la aplicación, para poder presentarles mis dudas sobre la aplicación.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP03</td>
    <td align="justify">Información sobre los servicios de la aplicación</td>
    <td align="justify">Como visitante de la Landing Page, quiero encontrar los servicios y beneficios que ofrece la aplicación, para poder conocerlos y aprovecharlos al máximo.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP04</td>
    <td align="justify">Registro de usuarios</td>
    <td align="justify">Como usuario de la aplicación, quiero poder dar mis datos personales, para poder registrarme y usar la aplicación.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP05</td>
    <td align="justify">Sistema de notificaciones</td>
    <td align="justify">Como usuario de la aplicación, quiero recibir notificaciones en tiempo real sobre incidentes de seguridad en mi área, para estar siempre informado y tomar precauciones.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP06</td>
    <td align="justify">Perfiles de usuario</td>
    <td align="justify">Como usuario de PeaceApp, quiero poder crear y personalizar mi perfil de usuario, para tener una identidad dentro de la comunidad de la aplicación.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP07</td>
    <td align="justify">Ruta Segura</td>
    <td align="justify">Como ciudadano quiero que me recomieden la ruta mas segura para asi poder tener un viaje sin preocupaciones.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP08</td>
    <td align="justify">Registro de reportes</td>
    <td align="justify">Como ciudadano quiero que poder generar reportes para que el mapa de calor sea más preciso.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP09</td>
    <td align="justify">Mapa de Calor</td>
    <td align="justify">Como entidad gubernamental quiero poder contar con un mapa de calor de mi zona para poder administrar mejor la seguridad.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">EP10</td>
    <td align="justify">Visualización de reportes</td>
    <td align="justify">Como entidad gubernamental quiero poder ver los reportes de los ciudadanos para tener una mejor gestión de la seguridad.</td>
    <td align="justify">
      No corresponde
    </td>
    <td align="center">No corresponde</td>
  </tr>
  <tr>
    <td align="center">US01</td>
    <td align="justify">Contactar con la startup</td>
    <td align="justify">Como visitante de la Landing Page, quiero encontrar un formulario de contacto funcional y accesible para poder comunicarme con la startup.</td>
    <td align="justify">
      Escenario 1: Enviar mensaje a los desarrolladores <br>
      Given que el visitante tenga una consulta o comentario relacionado con la aplicación. <br> 
      When redacte un mensaje y adjunte una dirección de correo electrónico para contactar a los desarrolladores <br>
      Then el sistema enviará el mensaje a la dirección de correo electrónico de la startup. <br>
    </td>
    <td align="center">EP02</td>
  </tr>
  <tr>
    <td align="center">US02</td>
    <td align="justify"> Navegar en el landing page</td>
    <td align="justify"> Como visitante de la landing page, quiero encotrar las secciones bien definidas para comprender fácilmente la información mostrada. </td>
    <td align="justify">
      Escenario 1: Visualizar información.<br>
      Given el visitante está recorriendo la landing.<br>
      When acceda a alguna sección de la landing<br>
      Then podrá comprender la información pues las secciones estarán bien organizadas. <br>
    </td>
    <td align="center">EP01</td>
  </tr>
  <tr>
    <td align="center">US03</td>
    <td align="justify"> Seleccion de tipo de usuario</td>
    <td align="justify"> Como usuario de la aplicacion, quiero poder elegir el tipo de usuario que soy para poder tener mis beneficios según el tipo de usuario</td>
    <td align="justify">
      Escenario 1: El usuario ingresa a la aplicacion<br>
      Given el usuario desee comenzar a usar la aplicacion<br>
      When se registre tiene que seleccionar el tipo de usuario<br>
      Then pasará al formulario para completar sus datos<br>
      And podrá entrar a la aplicacion con las funcionalidades para su tipo de usuario<br>
    </td>
    <td align="center">EP04</td>
  </tr>
  <tr>
    <td align="center">US04</td>
    <td align="justify"> Registro como ciudadano</td>
    <td align="justify"> Como ciudadano, quiero poder rellenar un formulario con mis datos personales para poder hacer uso mis funcionalidades como ciudadano</td>
    <td align="justify">
      Escenario 1: Usuario registra información.<br>
      Given que un ciudadano llena el formulario<br>
      When presione el boton "crear cuenta"<br>
      Then el sistema guardará la informacion personal del usuario en la base de datos<br>
      Escenario 2: Usuario registra información incompleta. <br>
      Given que un ciudadano no llena en la totalidad el formulario<br>
      When presione el boton "crear cuenta"<br>
      Then el sistema le mostrara una alerta en la parte del formlario que le falta llenar<br>
    </td>
    <td align="center">EP04</td>
  </tr>
  <tr>
    <td align="center">US05</td>
    <td align="justify"> Registro como entidad gubernamental</td>
    <td align="justify"> Como entidad gubernamental, quiero poder rellenar un formulario con mis datos necesarios para poder hacer uso mis funcionalidades como entidad gubernamental</td>
    <td align="justify">
      Escenario 1: Entidad gubernamental completa registro<br>
      Given que la entidad gubernamental completó el formulario exitosamente<br>
      When presione el boton "siguiente"<br>
      Then el sistema redireccionará a pantalla de pago de la suscripcion<br>
      Escenario 2: Sistema rechaza credenciales<br>
      Given que la entidad gubernamenta haya intentado registrarse en la aplicacion<br>
      When el sistema verifique que las credenciales no son validas<br>
      Then la entidad gubernamental recibira una notificacion para reintentar subir sus credenciales<br>
    </td>
    <td align="center">EP04</td>
  </tr>
  <tr>
    <td align="center">US06</td>
    <td align="justify">Alertas de Zonas de Riesgo</td>
    <td align="justify">Como ciudadano, quiero recibir alertas si me acerco y/o estoy en una zona de alto riesgo, para estar atento y tomar las precauciones pertinentes</td>
    <td align="justify">
      Escenario 1: Ciudadano recibe una alerta anticipada.<br>
      Given el ciudadano se esta desplazando usando sus dispositivo movil<br>
      When el sistema la aplicación detecta que el ciudadano se está acercando a una zona de alto riesgo.<br>
      Then la aplicación envía una alerta visual y auditiva al ciudadano.
      Escenario 2 Ciudadano recibe alerta:
      Given el ciudadano se esta caminando en una zona de peligro segun la aplicacion<br>
      And empieza a usar su dispositivo movil<br>
      When el sistema detecta que esta usando sus dispositivo movil y en una zona de peligro<br>
      Then la aplicacion envia una alerta visual y auditiva al ciudadano<br>	
    </td>
    <td align="center">EP05</td>
  </tr>
  <tr>
    <td align="center">US07</td>
    <td align="justify">Recibir notificaciones sobre reportes recientes</td>
    <td align="justify">Como ciudadano, quiero recibir notificaciones sobre los reportes recientes para poder estar mejor informado del lugar donde me encuentro</td>
    <td align="justify">
      Escenario 1: Actualizacion sobre reportes recientes<br>
      Given que el ciudadano tiene la opcion de recibir notificaciones sobre los reportes reciente activada<br>
      When la aplicacion reciba nuevas reportes de otros ciudadanos en la zona donde el se encuentra<br>
      Then el ciudadano será notificado sobre nuevos reportes por la aplicacion<br>
    </td>
    <td align="center">EP05</td>
  </tr>
  <tr>
    <td align="center">US08</td>
    <td align="justify">Añadir foto de perfil</td>
    <td align="justify">Como usuario, quiero tener la opción de añadir una foto de perfil, para personalizar mis perfil</td>
    <td align="justify">
      Escenario 1: Subida exitosa de una foto de perfil<br>
      Given el usuario accede a la configuración de su cuenta,<br>
      When el usuario encuentra la opción de "Foto de Perfil"<br>
      Then se debe abrir un cuadro de diálogo que permita al usuario seleccionar una foto de su dispositivo,<br>
      And cuando el usuario selecciona una foto y confirma la acción, <br>
      Then la foto de perfil del usuario debe actualizarse con la foto seleccionada. <br>
      Escenario 2: Fallo al subir una foto de perfil <br>
      Given la imagen seleccionada por el usuario no cumple con los requisitos de formato especificados <br>
      When el usuario confirme la acción de cambiar su foto de perfil <br>
      Then el sistema muestra un mensaje de error indicando que el formato de la imagen no es válido. <br>
    </td>
    <td align="center">EP06</td>
  </tr>
  <tr>
    <td align="center">US09</td>
    <td align="justify">Editar información de perfil</td>
    <td align="justify">Como usuario, quiero poder editar mi información de perfil, para arreglar algunos errores de registro</td>
    <td align="justify">
      Escenario 1: Edición exitosa de información de perfil <br>
      Given el usuario se registró en la aplicación <br>
      And alguna parte de sus datos están incorrectos<br>
      When el usuario accede a la configuración de su cuenta <br>
      And selecciona la opción de "Editar Información",<br>
      Then se debe abrir una página o un cuadro de diálogo que permita al usuario editar su información de perfil,<br>
      And cuando el usuario realiza los cambios y confirma la acción <br>
      Then la información de perfil del usuario debe actualizarse con la nueva información. <br>
    </td>
    <td align="center">EP06</td>
  </tr>
  <tr>
    <td align="center">US10</td>
    <td align="justify">Personalización de rutas</td>
    <td align="justify">Como ciudadano, quiero poder personalizar preferencias de seguridad, para que mis rutas se ajusten a ellas.</td>
    <td align="justify">
      Escenario 1:  Personalización de preferencias de seguridad antes de seleccionar una ruta<br>
      Given el ciudadano ha accedido a las opciones de personalización.<br>
      When el ciudadano ajusta sus preferencias de seguridad.<br>
      Then la aplicación personaliza la ruta del ciudadano en función de sus preferencias.
      Escenario 2: Cambio de preferencias de seguridad durante la navegación <br>
      Given Un ciudadano está utilizando la ruta que le sugirió la aplicación. <br>
      When durante el viaje, el ciudadano se da cuenta de que prefiere ajustar sus preferencias de seguridad. <br>
      Then el ciudadano puede cambiar sus preferencias de seguridad en cualquier momento <br>
      And la aplicación ajustará la ruta en consecuencia. <br>
    </td>
    <td align="center">EP07</td>
  </tr>
  <tr>
    <td align="center">US11</td>
    <td align="justify">Visualización de Rutas Seguras</td>
    <td align="justify">Como ciudadano, quiero poder ingresar mi destino en la aplicación, para poder elegir la ruta más segura para mi viaje</td>
    <td align="justify">
      Escenario 1: Selección de una ruta segura.<br>
      Given el ciudadano desea desplazar hacia su destino usando la aplicación.<br>
      When ingreso su destino en la aplicación y solicite las rutas posibles.<br>
      And la aplicación  muestre varias rutas posibles hacia su destino. <br>
      Then el usuario selecciona una ruta de acuerdo a sus preferencias y necesidades.
    </td>
    <td align="center">EP07</td>
  </tr>
  <tr>
    <td align="center">US12</td>
    <td align="justify">Reporte de incidentes</td>
    <td align="justify">Como ciudadano, quiero poder reportar incidentes de seguridad que ocurran en mi ubicación a través de la aplicación, para alertar a otros usuarios que se encuentren en la zona y contribuir a la seguridad de la comunidad.</td>
    <td align="justify">
      Escenario 1: Reporte de un incidente de seguridad<br>
      Given el usuario ha presenciado un incidente de seguridad.<br>
      And decida usar la opción de "nuevo reporte" en la aplicación <br>
      When el usuario ingresa los detalles del incidente en la aplicación.<br>
      Then la aplicación registra el incidente y actualiza la información de peligrosidad de la zona correspondiente. <br>
      Escenario 2: Adjuntar Evidencia Visual al Reporte de Incidentes  <br>
      Given el usuario quiere darle credibilidad a un reporte <br>
      When llena los detalles del reporte <br>
      Then tendrá la opción de "subir evidencia" <br> 
      And podrá compartir una foto del incidente <br>
    </td>
    <td align="center">EP08</td>
  </tr>
  <tr>
    <td align="center">US13</td>
    <td align="justify">Visualización de reportes</td>
    <td align="justify">Como ciuddano, quiero poder ver los reportes de otros usuarios sobre incidentes ocurridos en la zona, para estar al tanto de los eventos de seguridad y tomar medidas apropiadas si es necesario.</td>
    <td align="justify">
      Escenario 1: Visualización de reportes recientes<br>
      Given el ciudadano está navegando por la aplicación.<br>
      When acceda a la opción de "ver reportes"<br>
      And la aplicación reciba nuevos reportes de usarios <br>
      Then la aplicación mostrará los reportes más recientes en la zona del ciudadano. <br>
      And para cada reporte, se proporciona información detallada, como la ubicación, la descripción, tipo, la fecha, hora del incidente en que ocurrió. <br>
      Escenario 2: Filtrado de reportes por tipo de incidente <br>
      Given el ciudadano está interesado en un tipo específico de incidente. <br>
      When seleccione un tipo de incidente en la aplicación <br>
      Then la aplicación mostrará solo los reportes de ese tipo de incidente. <br>
    </td>
    <td align="center">EP10</td>
  </tr>
  <tr>
    <td align="center">US14</td>
    <td align="justify">Acceso a reportes</td>
    <td align="justify">Como entidad gubernamental, quiero tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.</td>
    <td align="justify">
      Escenario 1: Análisis de reportes por parte de la entidad gubernamental<br>
      Given la entidad gubernamental accede al sistema de gestión de reportes de la aplicación<br>
      When la app permita a la entidad acceder a una interfaz que muestra todos los reportes de incidentes realizados por los usuarios.<br>
      Then la entidad usarará los reportes para identificar tendencias o patrones en la incidencia de ciertos tipos de incidentes en áreas específicas. <br>
      Escenario 2: Colaboración con la comunidad basada en datos de reportes <br>
      Given la entidad gubernamental ha identificado un patrón de incidentes en una zona específica. <br>
      When la entidad comparte esta información con la comunidad a través de la aplicación <br>
      Then la entidadad organiza reuniones comunitarias para discutir los problemas de seguridad identificados y las posibles soluciones. <br>  
    </td>
    <td align="center">EP10</td>
  </tr>
  <tr>
    <td align="center">US15</td>
    <td align="justify">Priorización de reportes</td>
    <td align="justify">Como entidad, quiero poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.</td>
    <td align="justify">
      Escenario 1: Priorización de un reporte de emergencia
      Given que la entidad gubernamental recibe un reporte de un tiroteo en una zona <br>
      When prioriza este reporte sobre otros menos urgentes en la cola de trabajo. <br>
      Then la entidad asignará rápidamente recursos y unidades policiales para responder al incidente. <br>
      Escenario 2: Manejo de un reporte menos urgente
      Given que la entidad gubernamental recibe un reporte de un robo en una zona <br>
      When la entidad decide que el robo no es una amenaza inmediata para la seguridad pública <br>
      Then la entidad asignará recursos para investigar el incidente en un plazo de 24 horas. <br>
    </td>
    <td align="center">EP10</td>
  </tr>
  <tr>
    <td align="center">US16</td>
    <td align="justify">Análisis de datos</td>
    <td align="justify">Como entidad gubernamental, quiero poder analizar los datos recopilados en el mapa de calor de mi zona para identificar áreas con alta densidad de incidentes de inseguridad</td>
    <td align="justify">
      Escenario 1: entidad analiza los datos recopilados<br>
      Given la entidad accede al mapa de calor<br>
      When la entidad selecciona una región más destacada<br>
      Then podrá veer los detalles de reportes de incidentes en esa área <br>
      And usarlos para su análisis. <br>
    </td>
    <td align="center">EP09</td>
  </tr>
  <tr>
    <td align="center">US17</td>
    <td align="justify">Estrategias usando el mapa de calor</td>
    <td align="justify">Como comisario, quiero utilizar la información recopilada para planificar estrategias contra la delincuencia.</td>
    <td align="justify">
      Escenario 1: Entidad gubernamental planea estrategias con los datos del mapa de calor<br>
      Given la entidad gubernamental busca la zona que le corresponde<br>
      And empieza a recopilar los datos necesarios<br>
      When la entidad gubernamental realice el análisis<br>
      Then se planean estrategias para poder combatir la delincuencia en esas zonas.
    </td>
    <td align="center">EP09</td>
  </tr>
  <tr>
    <td align="center">US18</td>
    <td align="justify">Mapa de calor</td>
    <td align="justify">Como usuario, quiero poder ver un mapa de calor sobre los niveles de peligro en mi zona para tomar las medidas necesarias</td>
    <td align="justify">
      Escenario 1: Acceso al mapa de calor<br>
      Given que el usuario está en la página principal de la aplicación,<br>
      When el usuario selecciona el mapa de calor,<br>
      Then se debe mostrar el mapa de calor señalando las zonas peligrosas y/o seguras de acuerdo a su ubicación
    </td>
    <td align="center">EP09</td>
  </tr>
  <tr>
    <td align="center">US19</td>
    <td align="justify">Compartir ubicación</td>
    <td align="justify">Como usuario, quiero poder compartir mi ubicación con mis contactos cercanos, para que conozcan el nivel de peligrosidad de la zona</td>
    <td align="justify"> 
      Escenario 1: usuario comparte su ubicación<br>
      Given un usuario que comparte su ubicación con sus contactos cercanos<br>
      When se desplaza por las distintas zonas de la ciudad<br>
      Then podrán monitorear su trayecto y saber si esta seguro. <br>
      Escenario 2: error al compartir ubicación<br>
      Given un usuario que intenta compartir su ubicación con sus contactos cercanos<br>
      When la aplicación no puede acceder a la ubicación del usuario<br>
      Then se mostrará un mensaje de error indicando que no se puede compartir la ubicación. <br>
    </td>
    <td align="center">EP09</td>
  </tr>
  <tr>
    <td align="center">TS01</td>
    <td align="justify">POST Inicident</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
    Quiero registrar los incidentes reportados mediante una API
    Para visualizar los reportes que realizan los ciudadanos.</td>
    <td align="justify">
      Escenario 1:<br>
      Dado que tengo acceso al API de registro de inicidentes<br>
      Cuando envio una solicitud con datos válidos de un nuevo incidente<br>
      Entonces el incidente se registra exitosamente en la base de datos<br>
      Escenario 2:<br>
      Dado que tengo acceso al API de registro de inicidentes<br>
      Cuando envio una solicitud con datos válidos de un nuevo incidente<br>
      Entonces el incidente se registra exitosamente en la base de datos
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS02</td>
    <td align="justify">GET Incident</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de un incidente mediante una API Para mostrarla en la aplicación cuando se solicite.</td>
    <td align="justify">
      Escenario 1:<br>
      Dado que tengo acceso al API de obtención de información de incidentes<br>
      Cuando solicito la información de un incidente existente <br>
      Entonces recibo la información en el formato esperado.<br>
      Escenario 2:<br>
      Dado que tengo acceso al API de obtención de información de incidentes<br>
      Cuando solicito la información de un incidente no existente <br>
      Entonces recibo un mensaje de error adecuado.
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS03</td>
    <td align="justify">POST User</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp Quiero registrar a un nuevo usuario mediante una API
    Para visualizar a los usuarios afiliados a nuestra app.</td>
    <td align="justify">
      Escenario 1:<br>
      Dado que tengo acceso a al API de registro de usuarios <br>
      Cuando envío una solicitud con datos válidos de un nuevo usuario<br>
      Entonces el usuario se registro exitosamente en la base de datos y recibo una confirmación<br>
      Escenario 2:<br>
      Dado que tengo acceso a al API de registro de usuarios <br>
      Cuando envío una solicitud con datos no válidos de un nuevo usuario<br>
      Entonces la solicitud es rechazada y recibo un mensaje de error adecuado.</td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS04</td>
    <td align="justify">GET User</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de un usuario mediante una API
    Para mostrarla en la aplicación cuando se solicite.</td>
    <td align="justify">
      Escenario 1:<br>
      Dado que tengo acceso al API de obtención de información de usuarios <br>
      Cuando solicito la información de un usuario existente<br>
      Entonces recibo la información del usuario en el formato esperado.<br>
      Escenario 2:<br>
      Dado que tengo acceso a al API de obtención de información de usuarios <br>
      Cuando solicito la información de un usuario que no existe<br>
      Entonces recibo un mensaje de error adecuado
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS05</td>
    <td align="justify">POST Payment Card</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp Quiero registrar la información de pago de las empresas o entidades mediante una API Para contar con la información para pagos seguros.</td>
    <td align="justify">
      Escenario 01:<br>
      Dado que tengo acceso al API de registro de la información de pago<br>
      Cuando envio la solicitud con datos válidos de una tarjeta <br>
      Entonces la tarjeta de pago se registra correctamente en la base de datos y recibo una notificación<br>
      Escenario 02:<br>
      Dado que tengo acceso al API de registro de la información de pago<br>
      Cuando envio la solicitud con datos invalidos de una tarjeta<br>
      Entonces recibo un mensaje de error adecuado.
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS06</td>
    <td align="justify">GET Payment Card</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de pago de las empresas o entidades mediante una API Para recibir los pagos en la aplicación cuando lo solicite.</td>
    <td align="justify">
      Escenario 01:<br>
      Dado que tengo acceso al API de registro de la información de pago<br>
      Cuando solicito la información de tarjetas de pago de una organización <br>
      Entonces recibo la información la tarjeta de pago en el formato esperado<br>
      Escenario 02:<br>
      Dado que tengo acceso al API de registro de la información de pago<br>
      Cuando solicito la información de tarjetas de pago de una organización que no tiene tarjetas registradas <br>
      Entonces recibo un mensaje indicando que no hay tarjetas registradas
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS07</td>
    <td align="justify">GET Reports by user</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de que usuarios realizan los reportes mediante una API Para mostrarla en la aplicación cuando se solicite.</td>
    <td align="justify">
      Escenario 01:<br>
      Dado que tengo acceso al API de obtención de reportes por usuario<br>
      Cuando solicito la información de reportes por usuario existente<br>
      Entonces recibo la información de los reportes en el formato esperado<br>
      Escenario 02:<br>
      Dado que tengo acceso al API de obtención de reportes por usuario<br>
      Cuando solicito la información de reportes por un usuario que no existente<br>
      Entonces recibo un mensaje de error adecuado.
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS08</td>
    <td align="justify">GET zones by Quantity Incidents</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de en que zonas se registraron los incidentes mediante una API para mostrarla en la aplicación cuando se solicite la cantidad de incidentes en una zona.</td>
    <td align="justify">
      Escenario 01:<br>
      Dado que tengo acceso al API de obtención de zonas por cantidad de incidentes <br>
      Cuando solicito la información de zonas existentes por cantidad de incidentes<br>
      Entonces recibo la información de las zonas por la cantidad de incidentes en el formato esperado<br>
      Escenario 02:<br>
      Dado que tengo acceso al API de obtención de zonas por cantidad de incidentes <br>
      Cuando solicito la información de zonas inexistentes por cantidad de incidentes<br>
      Entonces recibo un mensaje de error adecuado.
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS09</td>
    <td align="justify">POST address To Go</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación PeaceApp Quiero registrar la información de la dirección a la que se va a movilizar el ciudadano mediante una API Para contar con la información que necesitará el API de Google Maps.</td>
    <td align="justify">
      Escenario 01:<br>
      Dado que tengo acceso al API de registro de la dirección a la que el usuario irá<br>
      Cuando envio la solicitud con la información de una dirección existente<br>
      Entonces la dirección se registra exitosamente en la base de datos y recibo una confirmación<br>
      Escenario 02:<br>
      Dado que tengo acceso al API de obtención de la dirección a la que el usuario irá<br>
      Cuando envio una solicitud con la información de una dirección no existente<br>
      Entonces la solicitud es rechazada y recibo un mensaje de error adecuado.
    </td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td align="center">TS10</td>
    <td align="justify">GET users by kind</td>
    <td align="justify">Como desarrollador que trabaja en la aplicación PeaceApp Quiero obtener la información de los usuarios por el tipo de usuario mediante una API
    Para brindar la diferentes funcionalidades en la aplicación de acuerdo a la membresia.</td>
    <td align="justify">
      Escenario 01:<br>
      Dado que tengo acceso al API de obtención de usuarios por el tipo<br>
      Cuando solicito la información de usuarios existentes por el tipo <br>
      Entonces recibo la información de los usuarios por el tipo<br>
      Escenario 02:<br>
      Dado que tengo acceso al API de obtención de usuarios por el tipo<br>
      Cuando solicito la información de usuarios inexistentes por el tipo <br>
      Entonces recibo un mensaje de error adecuado.
    </td>
    <td align="center">-</td>
	</tr>
</table>

## 3.3. Impact Mapping
<img src="./assets/Impact_map.png" alt="Impact map">

## 3.4. Product Backlog
| #Orden |  ID  |                      Título                     |Descripción                             | Story Points |
| :----: | :--: | :---------------------------------------------- |--------------------------------------- | :----------: |
|   01   | US02 | Navegar en el landing page                      | Como visitante de la landing page, quiero encotrar las secciones bien definidas para comprender fácilmente la información mostrada.                                                                                                                |      1       |
|   02   | US18 | Mapa de calor                                   | Como usuario, quiero poder ver un mapa de calor sobre los niveles de peligro en mi zona para tomar las medidas necesarias                                                                                                                          |      3       |
|   03   | US17 | Estrategias usando el mapa de calor             | Como comisario, quiero utilizar la información recopilada para planificar estrategias contra la delincuencia.                                                                                                                                      |      5       |
|   04   | US19 | Compartir ubicación                             | Como usuario, quiero poder compartir mi ubicación con mis contactos cercanos, para que conozcan el nivel de peligrosidad de la zona                                                                                                                |      2       |
|   05   | US06 | Alertas de Zonas de Riesgo                      | Como ciudadano, quiero recibir alertas si me acerco y/o estoy en una zona de alto riesgo, para estar atento y tomar las precauciones pertinentes                                                                                                   |      5       |
|   06   | TS08 | GET zones by Quantity Incidents                 | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de en que zonas se registraron los incidentes mediante una API Para mostrarla en la aplicación cuando se solicite la cantidad de incidentes en una zona. |      1       |
|   07   | US11 | Visualización de Rutas Seguras                  | Como ciudadano, quiero poder ingresar mi destino en la aplicación, para poder elegir la ruta más segura para mi viaje                                                                                                                              |      2       |
|   08   | US10 | Personalización de rutas                        | Como ciudadano, quiero poder personalizar preferencias de seguridad, para que mis rutas se ajusten a ellas.                                                                                                                                        |      3       |
|   09   | TS09 | POST address To Go                              | Como desarrollador que trabaja en la aplicación PeaceApp Quiero registrar la información de la dirección a la que se va a movilizar el ciudadano mediante una API Para contar con la información que necesitará el API de Google Maps.             |      1       |
|   10   | US12 | Reporte de incidentes                           | Como ciudadano, quiero poder reportar incidentes de seguridad que ocurran en mi ubicación a través de la aplicación, para alertar a otros usuarios que se encuentren en la zona y contribuir a la seguridad de la comunidad.                       |      5       |
|   11   | TS07 | GET Reports by user                             | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de que usuarios realizan los reportes mediante una API Para mostrarla en la aplicación cuando se solicite.                                               |      1       |
|   12   | US13 | Visualización de reportes                       | Como ciuddano, quiero poder ver los reportes de otros usuarios sobre incidentes ocurridos en la zona, para estar al tanto de los eventos de seguridad y tomar medidas apropiadas si es necesario.                                                  |      2       |
|   13   | US14 | Acceso a reportes                               | Como entidad gubernamental, quiero tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.                                                                                                                      |      1       |
|   14   | US15 | Priorización de reportes                        | Como entidad, quiero poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.                                                                                                                     |      2       |
|   15   | US16 | Análisis de datos                               | Como entidad gubernamental, quiero poder analizar los datos recopilados en el mapa de calor de mi zona para identificar áreas con alta densidad de incidentes de inseguridad                                                                       |      3       |
|   16   | TS01 | POST Inicident                                  | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero registrar los incidentes reportados mediante una API Para visualizar los reportes que realizan los ciudadanos.                                                                  |      1       |
|   17   | TS02 | GET Incident                                    | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de un incidente mediante una API Para mostrarla en la aplicación cuando se solicite.                                                                     |      3       |
|   18   | US07 | Recibir notificaciones sobre reportes recientes | Como ciudadano, quiero recibir notificaciones sobre los reportes recientes para poder estar mejor informado del lugar donde me encuentro                                                                                                           |      3       |
|   19   | TS05 | POST Payment Card                               | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero registrar la información de pago de las empresas o entidades mediante una API Para contar con la información para pagos seguros.                                                |      3       |
|   20   | TS06 | GET Payment Card                                | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de pago de las empresas o entidades mediante una API Para recibir los pagos en la aplicación cuando lo solicite.                                         |      3       |
|   21   | US03 | Seleccion de tipo de usuario                    | Como usuario de la aplicacion, quiero poder elegir el tipo de usuario que soy para poder tener mis beneficios según el tipo de usuario                                                                                                             |      2       |
|   22   | TS03 | POST User                                       | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero registrar a un nuevo usuario mediante una API Para visualizar a los usuarios afiliados a nuestra app.                                                                           |      3       |
|   23   | US04 | Registro como ciudadano                         | Como ciudadano, quiero poder rellenar un formulario con mis datos personales para poder hacer uso mis funcionalidades como ciudadano                                                                                                               |      2       |
|   24   | US05 | Registro como entidad gubernamental             | Como entidad gubernamental, quiero poder rellenar un formulario con mis datos necesarios para poder hacer uso mis funcionalidades como entidad gubernamental                                                                                       |      3       |
|   25   | TS04 | GET User                                        | Como desarrollador que trabaja en la aplicación de PeaceApp Quiero obtener la información de un usuario mediante una API Para mostrarla en la aplicación cuando se solicite.                                                                       |      3       |
|   26   | TS10 | GET users by kind                               | Como desarrollador que trabaja en la aplicación PeaceApp Quiero obtener la información de los usuarios por el tipo de usuario mediante una API Para brindar la diferentes funcionalidades en la aplicación de acuerdo a la membresia.              |      1       |
|   27   | US08 | Añadir foto de perfil                           | Como usuario, quiero tener la opción de añadir una foto de perfil, para personalizar mis perfil                                                                                                                                                    |      1       |
|   28   | US09 | Editar información de perfil                    | Como usuario, quiero poder editar mi información de perfil, para arreglar algunos errores de registro                                                                                                                                              |      1       |
|   29   | US01 | Contactar con la startup                        | Como visitante de la Landing Page, quiero encontrar un formulario de contacto funcional y accesible para poder comunicarme con la startup.                                                                                                         |      3       |

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.

<div align="justify">
  <b>Branding:</b><br><br>
  <b>Brand Overview:</b><br>
  PeaceApp, se enfoca en ofrecer una solución tecnológica para la problemática que es la inseguridad ciudadana. Por ello, predisponemos que atraiga la atención del usuario desde el principio
  mediante la creación y el diseño agradable e identificable. Para ello, implementa una plataforma encargada de diseñar un mapa de calor que permita a las personas mantener actualizada la
  información de seguridad disponible. A su vez, permite un contacto directo con las autoridades para recibir ayuda ante actividades delictivas.
<br><br>
  <b>Brand Name:</b><br>
  PeaceApp recibe su nombre de la unión de las palabras Peace y App. Peace significa paz en español y App corresponde a la abreviación de application, que significa aplicación. Con ello,
  el nombre se entiende, literalmente, como Aplicación de la paz. Este nombre busca reflejar un tono formal y sereno, que se adecue a nuestros objetivos y permita a los usuarios recordarnos
  con facilidad y reflejar los ideales de búsqueda tranquilidad.<br>
</div>
<div align="center">
  <img src="./assets/logo.png" alt="Logo Peace App" width="40%" height="40%"><br>
</div>
<div align="justify">
  <b>Colores:</b><br>
  Los colores toman protagonismo de la primera percepción visual de los usuarios. Para diseñar el logo, se hizo uso del color azul de manera predominante, pues es un color relacionado a la seguridad. 
  Además, para complementarlo de manera estética, se complementara con el color amarilo y se utilizaran tonalidades frías para complementar en la Landing Page..<br>
  <img src="./assets/colores.png" alt="Colores - Peace App" width="75%" height="75%"><br>

<b>Tipografía:</b><br>
La distribución de la tipografía establece la jerarquía entre los diversos grupos de contenido de la página. Asimismo, cumple un rol importante al momento de guiar al usuario a través de la
interfaz. Para ello, se decidio utilizar las tipografía Monteserrat, una tipografía sobria y elegnate que refleja profesionalidad. Por último, para una correcta diferenciación entre
jerárquias se considerara: .<br>

  <ul>
    <li>Heading 01: Presenta un tamaño de 52px.</li>
    <li>Heading 02: Presenta un tamaño de 36px.</li>
    <li>Heading 03: Presenta un tamaño de 24px.</li>
    <li>Heading 04: Presenta un tamaño de 18px.</li>
  </ul>
  <img src="./assets/tipografia.png" alt="Tipografia - Peace App" width="75%" height="75%"><br>

<b>Spacing:</b><br>
Para que la información se identifique con claridad, se estarán utilizando espacio desde los 8 hasta los 96px para un diseño equilibrado y una experiencia visual agradable.<br>
<img src="./assets/espaciado.png" alt="Espaciado - Peace App" width="75%" height="75%"><br>

</div>

### 4.1.2. Web Style Guidelines.

<div align="justify">
  <ul>
    <li>Imágenes:</li>
    Se incluirán imágenes descriptivas y de utilidad puntual. En primer lugar, la imagen de perfil del usuario y se encontrarán en todo momento en la parte superior derecha, sirvidno como el boton de
    acceso al perfil del usuario. Adicionalmente, se contará con imágenes representativas para cada una de las secciones que representan el núcleo de la aplicación. Por la alta resolución de pantalla 
    resulta importante que el usuario cuente con guías visuales fácilmente identificables. Por esta misma razón, el fondo de las interfaces se verán limitadas a un color único.
    <li>Botones:</li>
    Estarán presentes en la parte superior de la aplicación y los lugares como al inico de sesión o para ingresar al mapa de calor. Estos botones permiten al usuario realizar acciones como ingresar a 
    una ventana, aceptar el ingreso de información o eliminar algún registro. Por otro lado, se deben mostrar botones de confirmación para las acciones que sean de suma importancia para el funcionamiento
    del mapa de calor. Cada botón contará con un estilo distintivo y un alto contraste con los colores del resto de la aplicación. Por ejemplo, se utiliza el color verde y rojo para remarcar el inicio y
    fin de un proceso, respectivamente.
    <li>Pantallas Emergentes:</li>
    Las pantallas emergentes tienen el objetivo de confirmar acciones clave para el funcionamiento de la plataforma. Los pop-ups cuentan con colores con un valor de matiz mayor que sus contrapartes del
    resto de la aplicación web. Además, su aparición oscurecerá el resto de la pantalla para contrastar y darse a conocer, resaltando la importancia del asunto en pantalla antes de que el usuario continúe
    con la navegación.
    <li>Diseño: </li>
    Se implementará un diseño adaptable (Web Responsive Design) que permita mostrar la información de manera óptima en cualquier dispositivo, garantizando que el contenido se vea siempre optimizado para 
    todos los usuarios. Por ello, se opto por emplear el patrón de diseño en forma de "Z" en el sitio web, dirigiendo la atención hacia los elementos clave y potencia la eficacia del contenido. Por ejemplo,
    se verá primero el logotipo en la esquina superior izquierda, seguida hacia la derecha con el menú de navegación, terminando con la imagen de perfil del usuario. Acto seguido, se podrá acceder a toda la
    información en pantalla y las opciones que puedan verse en la parte inferior.<br>
    <img src="./assets/design.png" alt="Web Design - Peace App" width="100%">
  </ul>
</div>

## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
<div align="justify">
  Para organizar la página, hemos decidido estructurar el contenido con un encabezado donde las secciones se declaren de manera clara.
  <ul>
    <li>
      Organización jerárquica (Visual Hierarchy): La información será mostrada de forma jerárquica, para resaltar la información más relevante y ayudar a los usuarios a navegar de manera eficiente. Se utilizó
      este orden para las pantallas de log-in y los perfiles. Los títulos de los datos destacan más en comparación al resto. 
    </li>
    <li>
      Organización Secuencial (Step-by-Step to Accomplish): Se guiará a los usuarios de manera progresiva, empezando por lo más simple y básico para avanzar a lo más detallado. Esto garantiza que los usuarios
      puedan completar tareas de manera intuitiva. El uso del mapa de calor utiliza esta organización. Al ingresar al mapa se ve primero una vista general de la ciudad. Luego, el usuario podrá acercarse hacia
      su propia ubicación o a una que sea de su interés. Acto seguido tendrá el acceso a la información por cada color del mapa en la zona y dará la opción de crear un nuevo reporte. Finalmente, las autoridades
      tendrán acceso a dichos reportes que utilizaran para tomar acción. 
    </li>
    <li>
      Esquemas de categorización:
      <ul>
        <li>Alfabético:</li>
        Las listas desplegables tendrán la información de manera alfabética. Por ejemplo: Características de personalización, distritos o delitos a reportar.  
        <li>Cronológico: </li>
        La lista de reportes que veran las autoridades estará ordenada de forma cronológica. Además, será de gran valor para definir los colores del mapa de calor.
        <li>Por tópicos:</li>
        Distintas opciones de la plataforma estarán representadas con tarjetas e hipervínculos para ser una ayuda visual adecuada. Por ejemplo, el perfil de usuario, las opciones de contacto y la opción de
        reporte de delitos observados.
        <li>Según audiencia:</li>
        Se identifica el uso diferenciado que le darán los dos segmentos objetivos al usar la plataforma. Las autoridades verán como pantalla principal el reporte de delitos reportados por los usuario, quiene 
        tendrán acceso directo al mapa de calor.
      </ul>
    </li>
  </ul>
</div>

### 4.2.2. Labeling Systems.
<div align="justify">
  En PeaceApp, las etiquetas seguiran las implicaciones de SEO, lo que significa que deben cumplir con los siguientes objetivos:
  <ul>
    <li>
      Nivel de Experiencia de Usuario (UX): Las etiquetas ofrecerán información clara para los usuarios puedan navegar de forma intuitiva.
    </li>
    <li>
      Nivel SEO: Utilizaremos el etiquetado interno para enlazar las páginas complementarias y optimizar el motor de búsqueda.
    </li>
    <li>
      Palabras Clave y Etiquetado Adecuado: Cada subpágina contendrá palabras clave relevantes y un etiquetado apropiado para distribuir los términos de manera efectiva y evitar la competencia 
      interna entre páginas.
    </li>
    <li>
      Impacto de las Etiquetas en Menús y Bloques Estáticos: Reconocemos que las palabras clave contenidas en los menús y en los bloques estáticos tienen un mayor impacto en la navegación y 
      visibilidad de la página.
    </li>
  </ul>
  Tipos de Etiquetas:
  <ul>
    <li>
      Etiquetas Contextuales: Describen los enlaces internos de la página y son cruciales para conectar diferentes funciones. Deberán tener contenido claro, sin ambiguedades.
    </li>
    <li>
      Etiquetas de Encabezado: Indicaran la temática y jerarquía del contenido.
    </li>
    <li>
      Etiquetas con Parámetro ALT: Seran de utilidad para proveer información alterna a las imágenes en nuestra plataforma. Estas descripciones facilitarán la accesibilidad web, permitiendo mejor 
      acceso a mayor cantidad de usuarios, como el uso de lectores de pantalla o fallos en la conexión.
    </li>
  </ul>
</div>

### 4.2.3. SEO Tags and Meta Tags

<div align="justify">
  Estas etiquetas nos ayudan a indicar información codificada y especificar los metadatos. No se ven directamente en las interfaces, pero facilitan el análisis de archivos HTML y del archivo. Además, 
  ayudan en el posicionamiento de nuestra página web en los buscadores.
  <ul>
    <li>
      Title (Título): El título de una página es lo más importante. Utilizaremos títulos descriptivos y atractivos para cada página, que reflejen claramente su contenido y propósito.
    </li>
    <img src="./assets/titulo.png" alt="Etiqueta Título" width="85%">
    <li>
      Descripción (Meta Description): Breves resúmenes que aparecen en los resultados de búsqueda. Se utilizaran para traer usuarios al sitio. La meta descripción es "Sientete seguro de visitar la 
      ciudad. Ayuda en a la lucha con la delncuencia."
    </li>
    <img src="./assets/descripcion.png" alt="Etiqueta Descripción" width="85%">
    <li>
      Codificación de carácteres: Esta etiqueta ayudará a que muestre correctamente los caracteres especiales en la página.
    </li>
    <img src="./assets/codificacion.png" alt="Etiqueta codificación" width="85%">
  </ul>
</div>

### 4.2.4. Searching Systems.

<div align="justify">
  PeaceApp sabe lo importante que es representar de forma adecuada, fácil y rápida la gran cantidad de información que se verá en la plataforma. PeaceApp tiene un sistema de búsqueda simple e intuitivo 
  para ser fácil de usar por todos los usuarios. Primero, podrán elegir un destino o buscar un lugar en específico. Estos datos se verán de manera listada, incluyendo el tiempo de viaje y los valores
  correspondientes al mapa de calor. Tambien se tendrá la opción de buscar con filtros por distrito, delito o intensidad en el mapa. Con ello, se podrán observar lso resultaods de manera listada, matricial
  o representada en el mapa, respectivamente. Por último, se tendrá un apartado buscar el contacto con las autoridades competentes. Estos resultados se verán como una imagen en conjunto a los datos de
  contacto.
</div>

### 4.2.5. Navigation Systems.

<div align="justify">
  Los sistemas de navegación principales serán los menús superiores, inferiores, el sistema de búsqueda y el mapa de calor. El sistema de labeling desplazara a los usuarios a las secciones que desean visualizar
  dentro de la página. En caso no se utilicen, el usuario verá la página a medida que desciende. La plataforma permitirá a los usuarios navegar libremente por el mapa usando su puntero o visitar las distintas 
  interfaces de manera secuencial. Tambien se tienen los botones que, de igual manera, representan la apertura, confirmación o finalización de los registros.<br>
  Por último, cabe mencionar que nuestro sistema de navegación se ha diseñado para la comodidad del usuario, pues Queremos que los usuarios puedan cumplir sus objetivos de manera satisfactoria, ya sea recorrer la 
  ciudad de forma segura, realizar una denuncia o realizar su seguimiento.
</div>

## 4.3. Landing Page UI Design.

### 4.3.1. Landing Page Wireframe.

La landing page de PeaceApp, diseñada para ser intuitiva y accesible, inicia con una sección de bienvenida que destaca las principales funciones y beneficios de la aplicación. Se continúa con "Nosotros", donde se detalla la misión y visión, reforzando el compromiso de la empresa con la seguridad personal y comunitaria. La sección "App" ofrece una vista previa interactiva de sus características, mientras que "Servicios" explica los distintos servicios como notificaciones de alerta y análisis de seguridad. "Planes" presenta las opciones de suscripción adaptadas a diferentes necesidades de los usuarios. Finalmente, "Contacto" facilita un formulario para comunicaciones directas con el equipo de PeaceApp, asegurando un soporte eficaz y personalizado.

#### Lading Page Wireframe - Inicio

<img src="./assets/WireFrames - Inicio.png" alt="WireFrameLandingInicio">

#### Lading Page Wireframe - Nosotros

<img src="./assets/WireFrames - Nosotros.png" alt="WireFrameLandingNosotros">

#### Lading Page Wireframe - App

<img src="./assets/WireFrames - App.png" alt="WireFrameLandingApp">

#### Lading Page Wireframe - Servicios

<img src="./assets/WireFrames - Servicios.png" alt="WireFrameLandingServicios">

#### Lading Page Wireframe - Planes

<img src="./assets/WireFrames - Planes.png" alt="WireFrameLandingPlanes">

#### Lading Page Wireframe - Contáctanos

<img src="./assets/WireFrames - Contactanos.png" alt="WireFrameLandingContactanos">

### 4.3.2. Landing Page Mock-up.

El wireframe de la landing page para la vista de escritorio ha sido esencial para estructurar la disposición de los elementos visualmente. Siguiendo este diseño inicial, se desarrolló el mock-up de la landing page, manteniendo la coherencia con el contenido previamente descrito. En la imagen siguiente, se puede observar la implementación efectiva de la paleta de colores primarios y secundarios, así como la tipografía seleccionada, demostrando la atención al detalle y la consistencia del estilo visual a lo largo del diseño.

#### Lading Page Mock-up - Inicio

<img src="./assets/Mock-up - Inicio.png" alt="Mock-upLandingInicio">

#### Lading Page Mock-up - Nosotros

<img src="./assets/Mock-up - Nosotros.png" alt="Mock-upLandingNosotros">

#### Lading Page Mock-up - App

<img src="./assets/Mock-up - App.png" alt="Mock-upLandingApp">

#### Lading Page Mock-up - Servicios

<img src="./assets/Mock-up - Servicios.png" alt="Mock-upLandingServicios">

#### Lading Page Mock-up - Planes

<img src="./assets/Mock-up - Planes.png" alt="Mock-upLandingPlanes">

#### Lading Page Mock-up - Contáctanos

<img src="./assets/Mock-up - Contactanos.png" alt="Mock-upLandingContactanos">

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.

#### Web Applications Wireframes - Página Principal

Pantalla de bienvenida que invita al nuevo usuario a registrarse o iniciar sesión para acceder a la plataforma.
<img src="./assets/Registro.png" alt="Wireframe Registro">

#### Web Applications Wireframes - Recuperacion Contraseña

Interfaz segura de inicio de sesión con recuperación de contraseña para asegurar la cuenta del usuario.
<img src="./assets/Contraseña.png" alt="Wireframe Contraseña">

#### Web Applications Wireframes - Correo de Cambio de Contraseña

Mensaje de confirmación que informa al usuario que el enlace para recuperar su contraseña ha sido enviado a su correo electrónico.
<img src="./assets/Recuperado.png" alt="Wireframe Recuperado">

#### Web Applications Wireframes - Registro de Usuarios

Pantalla de selección de tipo de usuario que ofrece opciones para "Ciudadano" o "Municipalidad", seguida de la opción para iniciar sesión.
<img src="./assets/Tipo de Usuario.png" alt="Wireframe Tipo de Usuario">

#### Web Applications Wireframes - Formulario de Ciudadanos

Formulario de creación de cuenta nueva para ciudadanos con selección segura de correo electrónico y distrito.
<img src="./assets/Formulario Ciudadano.png" alt="WireFrame Formulario Ciudadano">

#### Web Applications Wireframes - Formulario de Municipalidades

Formulario de registro para entidades gubernamentales, enfocado en la contribución a la seguridad comunitaria.
<img src="./assets/Formulario Municipalidad.png" alt="WireFrame Formulario Municipalidad">

#### Web Applications Wireframes - Suscripción de Municipalidades

Detalles de la suscripción gubernamental con consideraciones de renovación, y un formulario de pago con tarjeta para confirmar la transacción.
<img src="./assets/Suscripción Gubernamental.png" alt="WireFrame Suscripción Gubernamental">

#### Web Applications Wireframes - Buscar una Ruta

Interfaz de mapa para buscar rutas seguras basadas en la ubicación actual del usuario.
<img src="./assets/Mapa Ciudadano.png" alt="WireFrame Mapa Ciudadano">

#### Web Applications Wireframes - Ruta Encontrada con Mapa de Calor

Visualización de mapa de calor centrada en el usuario para resaltar los niveles de seguridad de diferentes zonas de la ciudad.
<img src="./assets/Mapa de Calor Ciudadano.png" alt="WireFrame Mapa de Calor Ciudadano">

#### Web Applications Wireframes - Mapa de la Municipalidad

Función interactiva de mapa de calor que muestra áreas de alto riesgo para la Municipalidad en cuestión.
<img src="./assets/Mapa de Calor Entidad.png" alt="WireFrame Mapa de Calor Entidad">

#### Web Applications Wireframes - Sección de Reportes

Sección que lista los reportes enviados por los ciudadanos, con detalles para cada reporte y la opción de enviar un nuevo reporte.
<img src="./assets/Reportes Ciudadano.png" alt="WireFrame Reportes Ciudadano">

#### Web Applications Wireframes - Envio de Reporte

Formulario para reportar incidentes con opción de subir evidencia para una documentación precisa.
<img src="./assets/Formulario Reporte.png" alt="Wireframe Formulario Reporte">

#### Web Applications Wireframes - Detalles del Reporte

Interfaz para visualizar la información del reporte realizado de usuario, con campos como el tipo de reporte, fecha y hora, descripción, ubicación y evidencia.
<img src="./assets/Reporte.png" alt="Wireframe Reporte">

#### Web Applications Wireframes - Lista de Reportes Municipalidad

Lista resumida de informes para que las autoridades revisen y tomen las acciones necesarias.
<img src="./assets/Lista de Reportes Entidad.png" alt="Wireframe Lista de Reportes Entidad">

#### Web Applications Wireframes - Notificaciones y Alertas de Ciudadanos

Interfaz de la aplicación que muestra una lista de notificaciones y alertas para el usuario, permitiendo mantenerse informado sobre las actualizaciones de seguridad.
<img src="./assets/Notificaciones.png" alt="Wireframe Notificaciones">

#### Web Applications Wireframes - Notificaciones y Alertas de Municipalidades

Ajustes de notificaciones personalizables que permiten compartir informes con otras municipalidades.
<img src="./assets/Alertas Entidad.png" alt="WireFrame Alertas Entidad">

#### Web Applications Wireframes - Perfil de Ciudadanos

Pantalla de perfil del usuario puede actualizar su información personal, cerrar sesión o borrar su cuenta.
<img src="./assets/Perfil Usuario.png" alt="WireFrame Perfil Usuario">

#### Web Applications Wireframes - Perfil de Municipalidades

Vista del perfil de una entidad en la aplicación con opciones para cancelar suscripción, cerrar sesión o borrar la cuenta.
<img src="./assets/Perfil Entidad.png" alt="WireFrame Perfil Entidad">

#### Web Applications Wireframes - Editar Perfil

Opciones de edición de perfil de usuario, incluyendo tipos de ruta preferidos y frecuencia de alertas.
<img src="./assets/Editar Perfil.png" alt="WireFrame Editar Perfil">

### 4.4.2. Web Applications Wireflow Diagrams.

#### User Flow User Goal 1 (Como transeúnte, quiero que la aplicación me sugiera la ruta más segura.)

User Task: El usuario se registra como ciudadano, busca un destino y recibe sugerencias de la ruta más segura a través del mapa de calor.

<img src="./assets/WireFlow1.png" alt="WireFlow1">

#### User Flow User Goal 2 (Como transeúnte, quiero poder personalizar mis rutas en función de mis preferencias.)

User Task: El usuario ajusta sus preferencias de seguridad en su perfil para obtener rutas personalizadas que se ajusten a sus necesidades.

<img src="./assets/WireFlow2.png" alt="WireFlow2">

#### User Flow User Goal 3 (Como transeúnte, quiero poder reportar incidentes.)

User Task: El usuario accede a la sección de reportes, completa un formulario con los detalles del incidente y visualiza el nuevo reporte en su lista.

<img src="./assets/WireFlow3.png" alt="WireFlow3">

#### User Flow User Goal 4 (Como comisario, quiero tener acceso a los reportes de los usuarios.)

User Task: El comisario registra información de su municipalidad, revisa reportes de incidentes y planifica estrategias contra la delincuencia.

<img src="./assets/WireFlow4.png" alt="WireFlow4">

#### User Flow User Goal 5 (Como comisario, quiero poder priorizar los reportes en función de su gravedad y urgencia.)

User Task: El comisario establece la prioridad de los reportes basándose en su gravedad y urgencia para gestionar las respuestas de forma eficaz.

<img src="./assets/WireFlow5.png" alt="WireFlow5">

### 4.4.3. Web Applications Mock-ups.

### Web Applications Mock-Ups - Página Principal

Interfaz de bienvenida finalizada, que muestra un diseño interactivo donde los nuevos usuarios son alentados a registrarse o iniciar sesión para utilizar la plataforma.
<img src="./assets/RegistroM.png" alt="Mock-Up Página Principal">

### Web Applications Mock-Ups - Recuperación Contraseña

Interfaz de usuario final para inicio de sesión con funcionalidad de recuperación de contraseña, proporcionando seguridad y accesibilidad.
<img src="./assets/ContraseñaM.png" alt="Mock-Up Recuperación Contraseña">

### Web Applications Mock-Ups - Correo de Cambio de Contraseña

Mensaje de confirmación detallado y diseñado que notifica a los usuarios el envío del enlace para restablecer su contraseña.
<img src="./assets/RecuperadoM.png" alt="Mock-Up Correo de Cambio de Contraseña">

### Web Applications Mock-Ups - Registro de Usuarios

Selección visual de tipo de usuario con un diseño claro y opciones para "Ciudadano" o "Municipalidad", con acceso directo para iniciar sesión.
<img src="./assets/Tipo de UsuarioM.png" alt="Mock-Up Registro de Usuarios">

### Web Applications Mock-Ups - Formulario de Ciudadanos

Diseño definitivo del formulario de registro para ciudadanos, con campos de entrada y selecciones seguras.
<img src="./assets/Formulario CiudadanoM.png" alt="Mock-Up Formulario de Ciudadanos">

### Web Applications Mock-Ups - Formulario de Municipalidades

Formulario interactivo de registro para entidades gubernamentales, diseñado para fomentar la contribución a la seguridad comunitaria.
<img src="./assets/Formulario MunicipalidadM.png" alt="Mock-Up Formulario de Municipalidades">

### Web Applications Mock-Ups - Suscripción de Municipalidades

Vista completa de la suscripción gubernamental con detalles sobre la renovación y formulario de pago seguro.
<img src="./assets/Suscripción GubernamentalM.png" alt="Mock-Up Suscripción de Municipalidades">

### Web Applications Mock-Ups - Buscar una Ruta

Interfaz de usuario para la búsqueda de rutas seguras, mostrando un mapa interactivo y opciones de filtrado.
<img src="./assets/Mapa CiudadanoM.png" alt="Mock-Up Buscar una Ruta">

### Web Applications Mock-Ups - Ruta Encontrada con Mapa de Calor

Representación visual de un mapa de calor en el contexto de la aplicación, destacando las áreas de interés de seguridad.
<img src="./assets/Mapa de Calor CiudadanoM.png" alt="Mock-Up Ruta Encontrada con Mapa de Calor">

### Web Applications Mock-Ups - Mapa de la Municipalidad

Funcionalidad de mapa de calor personalizado para municipalidades, con información detallada sobre áreas de alto riesgo.
<img src="./assets/Mapa de Calor EntidadM.png" alt="Mock-Up Mapa de la Municipalidad">

### Web Applications Mock-Ups - Sección de Reportes

Sección de reportes con una lista detallada y diseño interactivo para visualizar y enviar nuevos reportes.
<img src="./assets/Reportes CiudadanoM.png" alt="Mock-Up Sección de Reportes">

### Web Applications Mock-Ups - Envío de Reporte

Interfaz detallada para el envío de reportes, incluyendo la opción de adjuntar evidencia para verificar los incidentes.
<img src="./assets/Formulario ReporteM.png" alt="Mock-Up Envío de Reporte">

### Web Applications Mock-Ups - Detalles del Reporte

Pantalla que muestra en detalle la información de los reportes enviados por los usuarios, con todas las opciones relevantes.
<img src="./assets/ReporteM.png" alt="Mock-Up Detalles del Reporte">

### Web Applications Mock-Ups - Lista de Reportes Municipalidad

Lista resumida de informes para revisión de las autoridades, con diseño enfocado en la accesibilidad y toma de decisiones.
<img src="./assets/Lista de Reportes EntidadM.png" alt="Mock-Up Lista de Reportes Municipalidad">

### Web Applications Mock-Ups - Notificaciones y Alertas de Ciudadanos

Diseño de la interfaz para mostrar notificaciones y alertas a los ciudadanos, manteniendo al usuario informado sobre la seguridad.
<img src="./assets/NotificacionesM.png" alt="Mock-Up Notificaciones y Alertas de Ciudadanos">

### Web Applications Mock-Ups - Notificaciones y Alertas de Municipalidades

Sistema de alertas para municipalidades que permite la personalización y el intercambio de información entre entidades.
<img src="./assets/Alertas EntidadM.png" alt="Mock-Up Notificaciones y Alertas de Municipalidades">

### Web Applications Mock-Ups - Perfil de Ciudadanos

Diseño completo de la página de perfil de usuario, ofreciendo control total sobre la información personal y la cuenta.
<img src="./assets/Perfil UsuarioM.png" alt="Mock-Up Perfil de Ciudadanos">

### Web Applications Mock-Ups - Perfil de Municipalidades

Interfaz del perfil de la municipalidad con opciones claras para la gestión de la cuenta y suscripción.
<img src="./assets/Perfil EntidadM.png" alt="Mock-Up Perfil de Municipalidades">

### Web Applications Mock-Ups - Editar Perfil

Página de edición de perfil de usuario con un diseño intuitivo y fácil de usar para la personalización del perfil.
<img src="./assets/Editar PerfilM.png" alt="Mock-Up Editar Perfil">

### 4.4.4. Web Applications User Flow Diagrams.

#### User Flow User Goal 1 (Como transeúnte, quiero que la aplicación me sugiera la ruta más segura.)

User Task: El usuario se registra como ciudadano, busca un destino y recibe sugerencias de la ruta más segura a través del mapa de calor.

<img src="./assets/UserFlow1.png" alt="UserFlow1">

#### User Flow User Goal 2 (Como transeúnte, quiero poder personalizar mis rutas en función de mis preferencias.)

User Task: El usuario ajusta sus preferencias de seguridad en su perfil para obtener rutas personalizadas que se ajusten a sus necesidades.

<img src="./assets/UserFlow2.png" alt="UserFlow2">

#### User Flow User Goal 3 (Como transeúnte, quiero poder reportar incidentes.)

User Task: El usuario accede a la sección de reportes, completa un formulario con los detalles del incidente y visualiza el nuevo reporte en su lista.

<img src="./assets/UserFlow3.png" alt="UserFlow3">

#### User Flow User Goal 4 (Como comisario, quiero tener acceso a los reportes de los usuarios.)

User Task: El comisario registra información de su municipalidad, revisa reportes de incidentes y planifica estrategias contra la delincuencia.

<img src="./assets/UserFlow4.png" alt="UserFlow4">

#### User Flow User Goal 5 (Como comisario, quiero poder priorizar los reportes en función de su gravedad y urgencia.)

User Task: El comisario establece la prioridad de los reportes basándose en su gravedad y urgencia para gestionar las respuestas de forma eficaz.

<img src="./assets/UserFlow5.png" alt="UserFlow5">

## 4.5. Web Applications Prototyping.

En esta parte del documento, se incluye el enlace al prototipo de la Aplicación Web, el cual fue creado utilizando la herramienta de prototipado Figma.<br>
https://www.figma.com/proto/g2UjaaatgDwqOfmLg1rFFW/PeaceApp-Prototype?type=design&node-id=201-31&t=NWFD8ug873xPiMio-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=2%3A2&mode=design

## 4.6. Domain-Driven Software Architecture.

### 4.6.1. Software Architecture Context Diagram.

  <img src="./assets/ContextDiagram.png" alt="ContextDiagram" width="80%">

### 4.6.2. Software Architecture Container Diagrams.

  <img src="./assets/ContainerDiagram.png" alt="ContainerDiagram" width="80%">

### 4.6.3. Software Architecture Components Diagrams.

#### Bounded Context Access Diagram <br>

  <img src="./assets/ComponentDiagramAccess.png" alt="ComponentDiagramAccess" width="80%">

#### Bounded Context Payment Diagram <br>

  <img src="./assets/ComponentDiagramPayment.png" alt="ComponentDiagramPayment" width="80%">

#### Bounded Context Location Diagram <br>

  <img src="./assets/ComponentDiagramLocation.png" alt="ComponentDiagramLocation" width="80%">

#### Bounded Context Report Diagram <br>

  <img src="./assets/ComponentDiagramReport.png" alt="ComponentDiagramReport" width="80%">

#### Bounded Context Notification Diagram <br>

  <img src="./assets/ComponentDiagramNotification.png" alt="ComponentDiagramNotification" width="80%">

#### Bounded Context Notification Priorization Diagram <br>

  <img src="./assets/ComponentDiagramNotificationPriorization.png" alt="ComponentDiagramNotificationPriorization" width="80%">

## 4.7. Software Object-Oriented Design.

### 4.7.1. Class Diagrams.

  <img src="./assets/UML DIAGRAM.jpeg" alt="Log In Context" width="80%">

### 4.7.2. Class Dictionary.

  <img src="./assets/class_dictionay1.JPG" alt="Log In Context" width="80%">
  <img src="./assets/class_dictionary2.JPG" alt="Log In Context" width="80%">

## 4.8. Database Design.

### 4.8.1. Database Diagram.

  <img src="./assets/Database Diagram.png" alt="Log In Context" width="80%">

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
<img src="assets/Repositorio_1.png"><br>
Nuestras ramas:<br>
<img src="assets/Repositorio_2.png"><br>
Para poder trabajar cada capitulo de este proyecto, vamos a entrar a la rama correspondiente, por ejemplo si queremos editar el capitulo 1 debemos entrar a la rama feature/chapter-01<br>
<img src="assets/Repositorio3.png"><br>
Dentro de la rama feature/chapter-01 tenemos la carpeta docs donde se encuentran los archivos de cada capitulo, si queremos editar el capitulo 1 debemos editar el archivo chapter-01.md
<img src="assets/Repositorio_4.png"><br>

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
<img src="assets/sprintBack1.png">
Link del Trello: https://trello.com/invite/b/QxWAqzlj/ATTId381d27718ad1075484b3d9d90208edcE87B6F07/sprint-1
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
        <td><strong>Sprint 2</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>02/05/2024</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>08:00 PM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Discord</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Anatoly Andrey Noriega Suschenko, </td>
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
        <td>Sprint 2 Review Summary</td>
        <td align="justify">
		Se corrigieron varios errores respecto al envío pasado y a la retroalimentación brindada por el profesor.
	</td>
    </tr>
    <tr align="center">
        <td>Sprint 2 Retrospective Summary</td>
        <td align="justify">
		El equipo acordó en implementar los componentes escenciales de la Web Application de nuestra aplicación completando por el momento con la parte Front End de nuestro proyecto.
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
        <td>48</td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td>48</td>
    </tr>
</table>

#### 5.2.2.2.Sprint Backlog 2.
<img src="assets/sprintBack2.png">
Link del Trello: https://trello.com/invite/b/LqxwRTaP/ATTI044b3950952fa839a147f7b7c2805119905D8341/sprint-2
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
        <td>US01</td>
        <td>Acceso al Web Application desde la Landing Page</td>
        <td>W-01</td>
        <td>Acceder al Web Application desde la Landing Page</td>
        <td>Permitir al usuario que pueda acceder a la aplicación Web desde la Landing Page</td>
        <td>2</td>
        <td>Victor</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US11</td>
        <td>Vista de Buscar un Distrito de Ciudadano</td>
        <td>W-02</td>
        <td>Buscar un distrito de Ciudadano</td>
        <td>Permitir al usuario que pueda navegar en el mapa de un distrito para encontrar una ruta</td>
        <td>8</td>
        <td>Johan</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US16</td>
        <td>Vista de Visualizar el Distrito de la Entidad Gubernamental</td>
        <td>W-03</td>
        <td>Visualizar el distrito de la Entidad Gubernamental</td>
        <td>Permitir a la Entidad Gubernamental que pueda visualizar el mapa de su distrito</td>
        <td>4</td>
        <td>Johan</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US12</td>
        <td>Formulario de Reportes</td>
        <td>W-04</td>
        <td>Enviar un reporte</td>
        <td>Permitir al usuario hacer un envío de un reporte</td>
        <td>4</td>
        <td>Anatoly</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US13</td>
        <td>Vista de Reportes de los ciudadanos</td>
        <td>W-05</td>
        <td>Crear los reportes del Ciudadano</td>
        <td>Permitir al usuario poder visualizar los reportes que ha hecho dentro de la aplicación</td>
        <td>4</td>
        <td>Janiel</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US13</td>
        <td>Vista de un reporte hecho por el ciudadano</td>
        <td>W-06</td>
        <td>Visualizar un reporte hecho por el Ciudadano</td>
        <td>Permitir al usuario visualizar un reporte único</td>
        <td>2</td>
        <td>Janiel</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US14</td>
        <td>Vista de la lista de Reportes que posee la Entidad Gubernamental</td>
        <td>W-07</td>
        <td>Crear la lista de los reportes hacia la Entidad Gubernamental</td>
        <td>Permitir a la Entidad Gubernamental visualizar los reportes realizados por los ciudadanos en su distrito</td>
        <td>4</td>
        <td>Janiel</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US07</td>
        <td>Vista de Notificaciones de los Ciudadanos</td>
        <td>W-08</td>
        <td>Crear la lista de notificaciones del Ciudadano</td>
        <td>Permitir al usuario visualizar las notificaciones que recibe</td>
        <td>4</td>
        <td>Andres</td>
        <td>To-Do</td>
    </tr>
    <tr align="center">
        <td>US06</td>
        <td>Vista de Notificaciones de la Entidad Gubernamental</td>
        <td>W-09</td>
        <td>Crear lista de notificaciones de la Entidad Gubernamental</td>
        <td>Permitir a la Entidad Gubernamental visualizar las notificaciones que recibe</td>
        <td>4</td>
        <td>Andres</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US04</td>
        <td>Vista de Perfil de Ciudadano</td>
        <td>W-10</td>
        <td>Crear la vista del perfil del ciudadano</td>
        <td>Permitir al ciudadano visualizar su perfil junto con sus datos</td>
        <td>4</td>
        <td>Victor</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US05</td>
        <td>Vista de Perfil de la Entidad Gubernamental</td>
        <td>W-11</td>
        <td>Crear la vista del perfil de la Entidad Gubernamental</td>
        <td>Permitir a la Entidad Gubernamental visualizar su perfil junto con sus datos</td>
        <td>4</td>
        <td>Victor</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US09</td>
        <td>Formulario de edición de Perfil</td>
        <td>W-12</td>
        <td>Editar perfil del ciudadano</td>
        <td>Permitir al usuario que pueda editar su perfil</td>
        <td>4</td>
        <td>Anatoly</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US10</td>
        <td>Personalización del tipo de ruta</td>
        <td>W-13</td>
        <td>Cambiar las preferencias de la ruta</td>
        <td>Permitir al usuario cambiar sus preferencias de ruta de acuerdo a sus necesidades</td>
        <td>2</td>
        <td>Anatoly</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US19</td>
        <td>Ubicación del Ciudadano</td>
        <td>W-14</td>
        <td>Compartir la ubicación del ciudadano</td>
        <td>Permitir al usuario compartir su ubicación en caso lo requiera</td>
        <td>2</td>
        <td>Anatoly</td>
        <td>Done</td>
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
        <td>feature/edit-profile</td>
        <td>f9d12ac1a5f660d30ab1c978d4ca07c456bd84f3</td>
        <td>feat(edit-profile): add the full view of edit profile with the form</td>
        <td>-</td>
        <td>03/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/map-view-citizen</td>
        <td>279df7db406e5d5bde68b65fc68000fe03280344</td>
        <td>feat: mapcitizenview added</td>
        <td>-</td>
        <td>03/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/map-view-goverment</td>
        <td>9f740dd0c65ebb8cb9fd27f84c8cd90c19c7e5e9</td>
        <td>feat: mapgovernmentview added</td>
        <td>-</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/profile-view</td>
        <td>a2457a549b3af8f0d4d4f2e17ad746125a5a07d0</td>
        <td>Update userProfile.page.vue</td>
        <td>-</td>
        <td>03/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/report</td>
        <td>1c5cbee6041c0939319c23be8497e5192be166ab</td>
        <td>feat: municipality component added</td>
        <td>-</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/report-form-view</td>
        <td>fa03cb8268f474c9fde56ff88b44463675d06790</td>
        <td>feat(report-form): add the updated view of the report form</td>
        <td>-</td>
        <td>03/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>feature/map-view-citizen</td>
        <td>279df7db406e5d5bde68b65fc68000fe03280344</td>
        <td>chore: view-notifications.vue</td>
        <td>-</td>
        <td>04/05/2024</td>
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
        <td>develop</td>
        <td>a2457a549b3af8f0d4d4f2e17ad746125a5a07d0</td>
        <td>Update userProfile.page.vue</td>
        <td>Added the User Profile Page</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>develop</td>
        <td>a2457a549b3af8f0d4d4f2e17ad746125a5a07d0</td>
        <td>feat(report-form): add responsive for report-form</td>
        <td>Added the responsive style of the report form with the edit profile view</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>develop</td>
        <td>9f740dd0c65ebb8cb9fd27f84c8cd90c19c7e5e9</td>
        <td>feat: mapgovernmentview added</td>
        <td>Added the map for the goverment entity with the map for the citizens</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>develop</td>
        <td>1c5cbee6041c0939319c23be8497e5192be166ab</td>
        <td>feat: municipality component added</td>
        <td>Added the reports for the municipalities with the other views of reports</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>develop</td>
        <td>124737d58d640261a2e69923e51155ea49d92924</td>
        <td>chore: view-notifications.vue</td>
        <td>Added the view for the notifications of the municipalities</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>develop</td>
        <td>0325d0c8382cb44a016bd8d2de3b7b3a9a037a82</td>
        <td>chore: SendAlert</td>
        <td>Added the functionality of sending an alert</td>
        <td>04/05/2024</td>
    </tr>
    <tr>
        <td>landing-page-web-app</td>
        <td>develop</td>
        <td>3a5ae4a786cef907302db5756cf42d44a5244e42</td>
        <td>Update principal.page.vue</td>
        <td>Added the view for the main page</td>
        <td>04/05/2024</td>
    </tr>
</table>
</div>

#### 5.2.2.5.Execution Evidence for Sprint Review.
En el sprint 2 se diseñó de manera preliminar el primer modelo de la Web App. Además, se realizo la mejora de la landing page. Algunas evidencias son:
    
##### Sección Página Principal
<img src="assets/Evidence-MainPage.jpeg" alt="Evidence-MainPage.jpeg - Sprint 2">

##### Sección Mapa de Ciudadano
<img src="assets/Evidence-MainPage.jpeg" alt="Evidence-MainPage.jpeg - Sprint 2">
    
##### Sección Reportes
<img src="assets/Evidence-Reports.jpeg" alt="Evidence-Reports.jpeg - Sprint 2">

##### Sección Formulario de Reportes
<img src="assets/Evidence-ReportForm.jpeg" alt="Evidence-ReportForm.jpeg - Sprint 2">

##### Sección Notificaciones
<img src="assets/Evidence-Notifications.jpeg" alt="Evidence-Notifications.jpeg - Sprint 2">

##### Sección Perfil de Ciudadano
<img src="assets/Evidence-CitizenProfile.jpeg" alt="Evidence-CitizenProfile.jpeg - Sprint 2">
    
##### Sección Editar Perfil
<img src="assets/Evidence-EditProfile.jpeg" alt="Evidence-EditProfile.jpeg - Sprint 2">

##### Sección Perfil de Entidad Gubernamental
<img src="assets/Evidence-Municipality.jpeg" alt="Evidence-Municipality.jpeg - Sprint 2">

#### 5.2.2.6.Services Documentation Evidence for Sprint Review.
En el segundo sprint, se decidió enfocarse exclusivamente en desarrollar el front-end de nuestra aplicación. Para evitar limitaciones en las pruebas debido a la falta de un back-end, se optó por utilizar un fake-api que implementa una funcionalidad de mapa en nuestra aplicación.

#### 5.2.2.7.Software Deployment Evidence for Sprint Review.
<div align="justify">
	Para el presente sprint, se desplego el landing page completamente funcional, cumpliendo los user stories correspondientes. De la misma forma se desplego una
	primer versión de la web application, con mejoras a realizar para el siguiente sprint:
<img src="assets/Evidence-WebApp.png" alt="Evidence-WebApp.png - Sprint 2">
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

##### Commits:
<img src="/assets/CommitsAnalysisS2.png" alt="CommitsAnalysis - Sprint 2">

##### Analíticas de Colaboración:
<img src="/assets/ColaborationAnalysisS2.png" alt="ColaborationAnalysis - Sprint 2">

### 5.2.3. Sprint 3
#### 5.2.3.1.Spring Planning 3.
<table>
    <tr align="center">
        <td><strong>Sprint #</strong></td>
        <td><strong>Sprint 3</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>27/05/2024</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>11:00 AM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Presencial</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Team</td>
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
        <td>Sprint 2 Review Summary</td>
        <td align="justify">
		Se recibieron las recomendaciones del profesor con respecto al envío pasado.
	</td>
    </tr>
    <tr align="center">
        <td>Sprint 2 Retrospective Summary</td>
        <td align="justify">
		El equipo acordó en perfeccionar la Web Application y trabajar en la versión 
		inicial de los Web Services, para la futura conexión y despliegue.
	</td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr align="center">
        <td>Sprint 3 Goal</td>
        <td align="justify">
		Versión Final de Web Application y Landing Page.<br>
		Versión Inicial de Web Services
	</td>
    </tr>
    <tr align="center">
        <td>Sprint 3 Velocity</td>
        <td>46</td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td>46</td>
    </tr>
</table>

#### 5.2.3.2.Sprint Backlog 3.
<img src="assets/sprintBack3.png">
Link del Trello: https://trello.com/invite/b/HYuJ0Wvx/ATTI8b70bbfde093fcc301a1af4ea372c38aB6FF99AD/sprint-3
<table>
    <tr align="center">
        <td colspan="2"><strong>Sprint #</strong></td>
        <td colspan="6"><strong>Sprint 3</strong></td>
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
        <td>TS01</td>
        <td>POST Inicident</td>
        <td>W-01</td>
        <td>Crear endpoint para registro de incidentes</td>
        <td>Crear endpoint que permita la comunicación para registrar nuevos incidentes en la base de datos.</td>
        <td>4</td>
        <td>Anatoly</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS01</td>
        <td>POST Inicident</td>
        <td>W-02</td>
        <td>Validar datos de entrada</td>
        <td>Implementar validaciones para asegurar que los datos del incidente sean válidos.</td>
        <td>4</td>
        <td>Johan</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS01</td>
        <td>POST Inicident</td>
        <td>W-03</td>
        <td>Guardar incidente en la base de datos</td>
        <td>Desarrollar lógica para almacenar el incidente en la base de datos.</td>
        <td>5</td>
        <td>Johan</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS01</td>
        <td>POST Inicident</td>
        <td>W-04</td>
        <td>Manejar errores de entrada</td>
        <td>Implementar manejo de errores para datos inválidos o solicitudes incorrectas.</td>
        <td>4</td>
        <td>Andres</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS01</td>
        <td>POST Inicident</td>
        <td>W-05</td>
        <td>Escribir pruebas unitarias</td>
        <td>Escribir pruebas unitarias para asegurar que el registro de incidentes funcione correctamente.</td>
        <td>6</td>
        <td>Ernesto</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS02</td>
        <td>GET Incident</td>
        <td>W-06</td>
        <td>Crear endpoint para obtener información de incidentes</td>
        <td>Crear endpoint que permita la comunicación para obtener información de incidentes existentes.</td>
        <td>4</td>
        <td>Franz</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS02</td>
        <td>GET Incident</td>
        <td>W-07</td>
        <td>Validar ID del incidente</td>
        <td>Implementar validaciones para asegurar que el ID del incidente es válido.</td>
        <td>4</td>
        <td>Fran</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS02</td>
        <td>GET Incident</td>
        <td>W-08</td>
        <td>Recuperar datos de la base de datos</td>
        <td>Desarrollar lógica para recuperar la información del incidente desde la base de datos.</td>
        <td>5</td>
        <td>Ernesto</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS02</td>
        <td>GET Incident</td>
        <td>W-09</td>
        <td>Manejar errores de incidentes no existentes</td>
        <td>Implementar manejo de errores para incidentes que no existen en la base de datos.</td>
        <td>4</td>
        <td>Anatoly</td>
        <td>To Do</td>
    </tr>
    <tr align="center">
        <td>TS02</td>
        <td>GET Incident</td>
        <td>W-10</td>
        <td>Escribir pruebas unitarias</td>
        <td>Escribir pruebas unitarias para asegurar que la obtención de incidentes funcione correctamente.</td>
        <td>6</td>
        <td>Andres</td>
        <td>To Do</td>
    </tr>
</table>

#### 5.2.3.3.Development Evidence for Sprint Review.
<div align="justify">
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
		        <td>web-app-project-develop-clean-version</td>
		        <td>feature/password-recover</td>
		        <td>e5cacd6ea838a0b2d35017dfeb6d648cf925f7e9</td>
		        <td>Reordered</td>
		        <td>Files have been reordered.</td>
		        <td>31/05/24</td>
		</tr>
	 	<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>feature/password-recover</td>
		        <td>0989dfc5fdd8d976ea5b06b3b3f9d005488cc26b</td>
		        <td>feat Dialog</td>
		        <td>Dialog for startin Sign Up was created</td>
		        <td>02/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>feature/password-recover</td>
		        <td>caa0b299381f985170b9b913d07ba4dae9812859</td>
		        <td>feature Sign In Pages</td>
		        <td>Sign In pages and their routing has been created. Design and implementation is pendient</td>
		        <td>02/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>feature/password-recover</td>
		        <td>52c23ab67ac1548f545284ea8c53f9a0d76c6faf</td>
		        <td>feature Sign Up</td>
		        <td>New Version of Sign Up has been created</td>
		        <td>02/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>feature/password-recover</td>
		        <td>02fe4b77454d9dc34a24c01872cdbb00f42d91c9</td>
		        <td>feature Sign Up Forms</td>
		        <td>-</td>
		        <td>02/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>feature/password-recover</td>
		        <td>d44f054f2baf9096edd40bfcd57cc1c07fa78275</td>
		        <td>feat Passwor Recovery</td>
		        <td>Password recovery pages have been added</td>
		        <td>02/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>e3651d850bbe0153bf425661aa537a7af74db27b</td>
		        <td>fix Main</td>
		        <td>A new version of Main styles has been released</td>
		        <td>04/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>46db6c27fe0e051d67ae8393b73b49e7b09f5977</td>
		        <td>fix User and Authority Sign Up</td>
		        <td>-</td>
		        <td>04/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>2e4e1a6f76fdf5e48a0c045959e7a693c84d0c9b</td>
		        <td>fix User and Authority Profile</td>
		        <td>Styles in these pages have been improved</td>
		        <td>04/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>809466d1118055f0645a443d772f536c01c8de17</td>
		        <td>fix Profile Editot</td>
		        <td>Styles in editing windows have been improved.</td>
		        <td>04/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>0299647f7cdb8622d35e22e72f1f68246ce5d892</td>
		        <td>fix Styles</td>
		        <td>-</td>
		        <td>04/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>00b7036c41aaf94b7e5877a68a0b14470664b041</td>
		        <td>Fix Styles</td>
		        <td>More style have been improved. Some size and padding have been changed.</td>
		        <td>04/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>bdef99599f0ada824a7a9cbd59609e16188b69b7</td>
		        <td>fix Styles</td>
		        <td>Styles in profiles and toolbar have been improved. Web App is more friendly with movile devices now.</td>
		        <td>06/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>879daeec54458582f64cab50d212ea2df73907d3</td>
		        <td>fix Profile Picture</td>
		        <td>Display on wide screens has been fixed.</td>
		        <td>07/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/css-styles</td>
		        <td>9760935e7ebc891dca84f0400d04d700104d304f</td>
		        <td>fix Logo</td>
		        <td>New Logo file has been uploades and its displays have been fixed.</td>
		        <td>07/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>a1e0bc716e4c4d011dea34f702c8c7426cdddf12</td>
		        <td>fix: some components fixed and services added with db</td>
		        <td>-</td>
		        <td>07/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>c3cf90342b7fc8dab66b204d159a2c79efa71ec2</td>
		        <td>fix Form Styles</td>
		        <td>-</td>
		        <td>08/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>051a0c5eef01047574f1fcccbbed8feba3e21055</td>
		        <td>fix Report Form</td>
		        <td>Report Form has been fixed</td>
		        <td>08/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>27762eed12adf7c0f6c1e9f6b44d234af4c2ad06</td>
		        <td>feature Redirect</td>
		        <td>New redirection after creating report has been created.</td>
		        <td>08/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>407f37687dc9290c628e998b91fb3cd8e7725573</td>
		        <td>fix Reports</td>
		        <td>-</td>
		        <td>08/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>346186f5bc6bf14ca6c925ffb894c54257f11724</td>
		        <td>feat Notifications</td>
		        <td>Notifications window has been updated. It includes a new pop-up</td>
		        <td>08/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>28296c3cf3af412a909f3978982ca9b947b80476</td>
		        <td>fix Profile Edit</td>
		        <td>-</td>
		        <td>08/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>3270043bdf7335caac0950ac0c81c8e4bb2d9ee6</td>
		        <td>feature Server</td>
		        <td>-</td>
		        <td>09/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>93212f1430770f083ab5c7d31b55ad0631d5cb57</td>
		        <td>feature API link</td>
		        <td>API link has been uploaded, so it works online now.</td>
		        <td>09/06/24</td>
		</tr>
		<tr>
		        <td>web-app-project-develop-clean-version</td>
		        <td>fix/components</td>
		        <td>26740f0d3dfeceb0f8aca365640075999052bbbc</td>
		        <td>update Reports</td>
		        <td>Displayed Reports have been updated. They include now a link to a Random Image</td>
		        <td>09/06/24</td>
		</tr>
		<tr>
		        <td>landing-page-web-app</td>
		        <td>main</td>
		        <td>9b47aa5ea9a38318fa1b779e3dd0007f66012850</td>
		        <td>feature Link Web App</td>
		        <td>-</td>
		        <td>09/06/24</td>
		</tr>
	</table>
</div>

#### 5.2.3.4.Testing Suite Evidence for Sprint Review.
<div align="justify">
    Para la entrega del Sprint 3 se busco la mejora de diseño y funcionalidad de la Web Application y Landing Page. También se diseño y desplego la primera versión de los Web Services.
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
	        <td>peace-app-backend</td>
	        <td>develop</td>
	        <td>c441ed07791aed2f52321e4afdf8f2644fd9130a</td>
	        <td>feat: all merge working</td>
	        <td>-</td>
	        <td>10/06/24</td>
	    </tr>
	</table>
</div>

#### 5.2.3.5.Execution Evidence for Sprint Review.
<div align="justify">
	En base a todas la mejoras propuestas a la Web Application y Landing Page, se trabajo para realizarlas en conjunto a la primera versión de los Web Services. Algunas evidencias son:
</div>

##### Sección Página Principal
<img src="/assets/MainPage-Sprint3.jpg" alt="MainPage" width="100%">

##### Sección Mapa de Ciudadano
<img src="/assets/FindRoute-Sprint3.jpg" alt="FindRoute" width="100%">
    
##### Sección Reportes
<img src="/assets/ReportList-Sprint3.jpg" alt="ReportList-Sprint3" width="100%">

##### Sección Recuperar contraseña
<img src="/assets/RecoveryPassword-Sprint3.jpg" alt="RecoveryPassword" width="100%">

##### Sección Perfil de Ciudadano
<img src="/assets/CitizenProfile-Sprint3.jpg" alt="CitizenProfile" width="100%">

##### Sección Perfil de Entidad Gubernamental
<img src="/assets/AuthorityProfile-Sprint3.jpg" alt="AuthorityProfile" width="100%">

#### 5.2.3.6.Services Documentation Evidence for Sprint Review.
<div align="justify">
	Para el sprint 3 se planificó que el sprint abarcaría el front-end y se avanzaria con el back-end. Inicialmente se trabajó con una json server de forma local y luego se pasó a 
	realizar la implementación para la Front End Web Application desplegada. Hasta el momento, el back-end solo fue creado y no tiene vinculo con el front-end. Enlace para acceder 
	al <a href="https://6664a80f932baf9032abbc8e.mockapi.io/api/reports">MockAPI</a>. Enlace para acceder a <a href="https://github.com/G2WebApplication-WX54/peace-app-backend/tree/develop">Web Service</a><br>
	MockAPI:
	<table>
		<tr>
			<td>Endpoint</td>
			<td>Details</td>
		</tr>
		<tr>
			<td>/reports</td>
			<td>Se implementaron las operaciones CRUD para lograr el registro de nuevos reportes y su llamado para la ventana correspondiente.</td>
		</tr>
	</table>
	Web Service:
  <table>
		<tr>
			<td>Endpoint</td>
			<td>Details</td>
		</tr>
		<tr>
			<td>/Citizens</td>
			<td rowspan="2">Se implementaron las operaciones CRUD para lograr el registro de nuevos usuarios.</td>
		</tr>
    <tr>
			<td>/OrganizationsAccount</td>
		</tr>
  <tr>
			<td>/Notification</td>
			<td>Se implementaron las operaciones CRUD para lograr el registro de reportes y su notificación correspondiente.</td>
		</tr>
  <tr>
			<td>/ReportsManagement</td>
			<td>Se implementaron las operaciones CRUD para lograr el manejo de los reportes que se han registrado.</td>
		</tr>
	</table>
	<table>
		<tr>
			<td>Endpoint</td>
			<td>Operaciones</td>
			<td>Parametros</td>
			<td>URL</td>
		</tr>
		<tr>
			<td rowspan="5">Citizens</td>
			<td>Post</td>
			<td>No tiene</td>
			<td>/api/v1/citizens</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>No tiene</td>
			<td>/api/v1/citizens</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>{citizenId}</td>
			<td>/api/v1/citizens/{citizenId}</td>
		</tr>
		<tr>
			<td>Put</td>
			<td>{citizenId}</td>
			<td>/api/v1/citizens/{citizenId}</td>
		</tr>
		<tr>
			<td>Delete</td>
			<td>{citizenId}</td>
			<td>/api/v1/citizens/{citizenId}</td>
		</tr>
		<tr>
			<td rowspan="4">Notification</td>
			<td>Post</td>
			<td>No tiene</td>
			<td>/api/v1/notification</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>No tiene</td>
			<td>/api/v1/notification</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>{id}</td>
			<td>/api/v1/notification/{id}</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>{priority}</td>
			<td>/api/v1/notification/priority/{priority}</td>
		</tr>
		<tr>
			<td rowspan="2">OrganizationsAccount</td>
			<td>Post</td>
			<td>No tiene</td>
			<td>/api/v1/organizations-account</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>{organizationName}</td>
			<td>/api/v1/organizations-account/{organizationName}</td>
		</tr>
		<tr>
			<td rowspan="5">ReportsManagement</td>
			<td>Post</td>
			<td>No tiene</td>
			<td>/api/v1/reports-management</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>No tiene</td>
			<td>/api/v1/reports-management</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>{id}</td>
			<td>/api/v1/reports-management/{id}</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>{date}</td>
			<td>/api/v1/reports-management/date/{date}</td>
		</tr>
		<tr>
			<td>Get</td>
			<td>{district}</td>
			<td>/api/v1/reports-management/district/{district}</td>
		</tr>		
	</table>
	Link del repositorio: https://github.com/G2WebApplication-WX54/peace-app-backend<br>
	Web service commit details:
	<table aling="justify">
	    <tr>
	        <td>Repository</td>
	        <td>Branch</td>
	        <td>Commit Id</td>
	        <td>Commit Message</td>
	        <td>Commit Message Body</td>
	        <td>Commited on (Date)</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>4785feed1e35cb175a0e580df9d8ec57daf76d90</td>
	        <td>chore: initial configuration</td>
	        <td>-</td>
	        <td>03/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>b09202d91be84c7b23962eb58f2f401aa7df1da1</td>
	        <td>feat(communication): create Notification aggregate and Message value object</td>
	        <td>-</td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>514aa17a29e1821df7a2210c428795e74c342853</td>
	        <td>feat(communication): create CreateNotificationCommand</td>
	        <td>-</td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>4785feed1e35cb175a0e580df9d8ec57daf76d90</td>
	        <td></td>
	        <td></td>
	        <td></td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>59b03860a274fc0eaa51dafcf9df89fdde2ee843</td>
	        <td>feat(communication): add queries for getting all notifications and getting notification by id</td>
	        <td>-</td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>149ae5665d332208dabb9bb71d742d1c176745d8</td>
	        <td>feat(communication): add command and query service interfaces for notifications</td>
	        <td>-</td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>86a6d7f8bec364c9a9fe571988b08ab0257148a5</td>
	        <td>feat(communication): add Notification repository interface and implementation</td>
	        <td>-</td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>8bcda6d49aec5a9f66d19693ec5c697de64d1fe1</td>
	        <td>feat(communication): add Notification query service and command service</td>
	        <td>-</td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>4a27f9d0e7e06823cb43186f35efd16f29e6c42f</td>
	        <td>feat(communication): add Notification and CreateNotification resources</td>
	        <td>-</td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>beca97c50ff0cb423871eb74c8e82b166b7a79dc</td>
	        <td>feat(communication): add transform assemblers for Notification and CreateNotification</td>
	        <td></td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>f2e45129b8d89787fc25921fe2b301b268dd4c27</td>
	        <td>feat(communication): add Notifications controller with endpoints for creating and retrieving notifications</td>
	        <td></td>
	        <td>06/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>feature/communication</td>
	        <td>ef9ba5d50a63fd9dbd346a19a206e6b51a8fb44b</td>
	        <td>feat(Communication): Add Priority attribute to Notification</td>
	        <td></td>
	        <td>07/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>589ff2eff456a6e511e24aea813ae32e9c53b071</td>
	        <td>feat: all good I think</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>35c194cb27964ebcba0eaed8c8602267c102bfcc</td>
	        <td>feat(Report-Management): queries and query service</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>afe38654e38e07c66cd03b928984a2ff40f85833</td>
	        <td>feat(Report-Management): all query service</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>f20a05650ed72b41d6c9b5fb8672e8851b876800</td>
	        <td>feat(Report-Management): reports management controller</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>9359a93ee5e3192d22121466677ccc531911890f</td>
	        <td>feat: last thing added in report management controller</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>594d0528de49021228ea09c97f9268417ba86e74</td>
	        <td>feat(Report-Management): working, but with some errors</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
	    <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>1d918462d6fc27b61b685a74a9deb8be6793a74a</td>
	        <td>feat(Report-Management): just 1 problem in controller :)</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
	 <tr>
	        <td>peace-app-backend-DEMO</td>
	        <td>/master</td>
	        <td>862d35026170dde6813ea3270798baed7ec0476d</td>
	        <td>chore: deleting obj folder</td>
	        <td>-</td>
	        <td>07/06/2024</td>
	    </tr>
     			    <tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>737f4f412827e789f32ddd124f526c7dd12d480c</td>
	        <td>feat(communication): "add aggregate of notification."</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>773f7bc8dcc3b04e6ffedbb4ed03760d687b8b25</td>
	        <td>"feat(communication): add CreateNotificationCommand"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>438d10ec31d04d246658d070af64c53f0bcf429a</td>
	        <td>"feat(communication): add queries for getting all notifications, getting notification by id and getting all notifications by priority"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>a11378929e924ccb520b07c09d7bbb695423bc80</td>
	        <td>"feat(communication): add Notification repository interface and implementation"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>d7496540cc4efc7d84db965afd477b564c8e0708</td>
	        <td>"feat(communication): add command and query service interfaces for notifications"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>87d54e125c8fb4f423b8b9f1a8c77072903a9b75</td>
	        <td>"feat(communication): add Notification repository and implementation"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>d86b6721885bd82fac1b94cdea184be37d189625</td>
	        <td>"feat(communication): add Notification query service and command service"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>16f123ce2e97841171db868424d0aa33578d5374</td>
	        <td>"feat(communication): add Notification and CreateNotification resources"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>6c5d8a824fda686b18485dd1a4594c8009f5e117</td>
	        <td>"feat(communication): add transform assemblers for Notification and CreateNotification"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>16cb5ff5caf33e761df1477657ec6f470d398b9f</td>
	        <td>"feat(communication): add controller and update AppDbContext and Program.cs for Notification entity"</td>
	        <td>-</td>
	        <td>08/06/2024</td>
	    </tr>
     <tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>d1a00e4315692483a9ba63dccae8cbfd52f02bf2</td>
	        <td>feat(Organization): working in swagger with an error in POST</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>05ec01fe6881f8c8502435d204835944b96c4b79</td>
	        <td>"feat(citizen): add value objects for citizen account along with aggregates for citizen profile and its audit"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>767ff69d470b71836b970b35ed3ff94c347a4aa3</td>
	        <td>"feat(citizen): added CreateCitizenAccountCommand"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>f2e5239756e04b900f3588faa2d845ef47cba29a</td>
	        <td>"feat(citizen): add queries for getting all accounts by email and by ID"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>9b24d8e56f2d18b8fd5a26c73473d8fb96d2ccae</td>
	        <td>"feat(citizen): add CitizenRepository"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>612111f209bf680c6a335904147bf3fe3481e590</td>
	        <td>"feat(citizen): add interfaces of command and query services"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>b186bcd35407a355f3c29ba2a65630c86038e9b2</td>
	        <td>"feat(citizen): add CitizenRepository in InfrastructureLayer"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>1ff90297dc3780b2399e3c22686bce65687e3431</td>
	        <td>"feat(citizen): add command and query service in application layer"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>a25da27d3f590ac8599ff3f81a487c1d9621ebbc</td>
	        <td>"feat(citizen): add the CitizensContextFacade interface and class in interface layer"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>057ecf5a81d5946768edaca328bffa3fff197c58</td>
	        <td>"feat(citizen): add CitizenResource and CreateCitizenResource"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>dc26e9fe1a9f9edcccfb7283dcee821ba08b6ec6</td>
	        <td>"feat(citizen): add the resources assembler of CitizenResource and CreateCitizenResource"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>92a31786444f92baba3f5daa8568de3ac868e9b6</td>
	        <td>"feat(citizen): add CitizensController and tables to AppDbContext and Program.cs"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>75ddd4d2b1fc72b9c819b7cde0906374a6db48b8</td>
	        <td>"feat(citizen): add the update and delete citizen command"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
		<tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>1001810c415c1b5b2714678a9759ac7e6432770f</td>
	        <td>"feat(citizen): Add CRUD operations for Citizens"</td>
	        <td>-</td>
	        <td>09/06/2024</td>
	    </tr>
     <tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>7b57ebc5b92699390baea9fcee165904644259fd</td>
	        <td>Merge branch 'feature/communication' into merging-test</td>
	        <td>-</td>
	        <td>10/06/2024</td>
	    </tr>
     <tr>
	        <td>peace-app-backend</td>
	        <td>/develop</td>
	        <td>c441ed07791aed2f52321e4afdf8f2644fd9130a</td>
	        <td>feat: all merge working</td>
	        <td>-</td>
	        <td>10/06/2024</td>
	    </tr>
	</table>
	Web services images: 
	<img src="/assets/WebServices1.png" alt="WebServices1" width="100%">
  			<img src="/assets/WebServices2.png" alt="WebServices2" width="100%">
 			<img src="/assets/WebServices3.png" alt="WebServices3" width="100%">
  			<img src="/assets/WebServices4.png" alt="WebServices4" width="100%">
  			<img src="/assets/WebServices5.png" alt="WebServices5" width="100%">
			<img src="/assets/WebServices6.png" alt="WebServices6" width="100%">
  			<img src="/assets/WebServices7.png" alt="WebServices7" width="100%">
  			<img src="/assets/WebServices8.png" alt="WebServices8" width="100%">
  			<img src="/assets/WebServices9.png" alt="WebServices9" width="100%">
  			<img src="/assets/WebServices10.png" alt="WebServices10" width="100%">
  			<img src="/assets/WebServices11.png" alt="WebServices11" width="100%">
  			<img src="/assets/WebServices12.png" alt="WebServices12" width="100%">
  			<img src="/assets/WebServices13.png" alt="WebServices13" width="100%">
  			<img src="/assets/WebServices14.png" alt="WebServices14" width="100%">
  			<img src="/assets/WebServices15.png" alt="WebServices15" width="100%">
  			<img src="/assets/WebServices16.png" alt="WebServices16" width="100%">	
</div>

#### 5.2.3.7.Software Deployment Evidence for Sprint Review.
<div align="justify">
	Para el presente sprint, se desplego el landing page completamente funcional, cumpliendo los user stories correspondientes. De la misma forma se desplego una
	nueva versión de la web application, con un back-end parcial. Estos últimos recibiran mejoras en el siguiente sprint.
	<ul>
		<li>Landing page:</li>
			<img src="/assets/LandingPage-Sprint3.jpg" alt="LandingPage" width="100%">
		<li>Web Application front-end:</li>
			<img src="/assets/Netlify-Deploy-Sprint3.png" alt="Deploy" width="100%">
			<img src="/assets/MainPage-Sprint3.jpg" alt="MainPage" width="100%">
			<img src="/assets/CreateUser-Sprint3.jpg" alt="CreateUser" width="100%">
			<img src="/assets/CreateCitizen-Sprint3.jpg" alt="CreateCitizen" width="100%">
			<img src="/assets/CreateAuthority-Sprint3.jpg" alt="CreateAuthority" width="100%">
			<img src="/assets/RecoveryPassword-Sprint3.jpg" alt="RecoveryPassword" width="100%">
			<img src="/assets/ReportList-Sprint3.jpg" alt="ReportList-Sprint3" width="100%">
			<img src="/assets/NewReport-Sprint3.jpg" alt="NewReport" width="100%">
			<img src="/assets/Subscription-Sprint3.jpg" alt="Subscription" width="100%">
			<img src="/assets/FindRoute-Sprint3.jpg" alt="FindRoute" width="100%">
			<img src="/assets/CitizenProfile-Sprint3.jpg" alt="CitizenProfile" width="100%">
			<img src="/assets/AuthorityProfile-Sprint3.jpg" alt="AuthorityProfile" width="100%">
		<li>Web Services back-end: </li>
			<img src="/assets/WebServices1.png" alt="WebServices1" width="100%">
  			<img src="/assets/WebServices2.png" alt="WebServices2" width="100%">
 			<img src="/assets/WebServices3.png" alt="WebServices3" width="100%">
  			<img src="/assets/WebServices4.png" alt="WebServices4" width="100%">
  			<img src="/assets/WebServices5.png" alt="WebServices5" width="100%">
			<img src="/assets/WebServices6.png" alt="WebServices6" width="100%">
  			<img src="/assets/WebServices7.png" alt="WebServices7" width="100%">
  			<img src="/assets/WebServices8.png" alt="WebServices8" width="100%">
  			<img src="/assets/WebServices9.png" alt="WebServices9" width="100%">
  			<img src="/assets/WebServices10.png" alt="WebServices10" width="100%">
  			<img src="/assets/WebServices11.png" alt="WebServices11" width="100%">
  			<img src="/assets/WebServices12.png" alt="WebServices12" width="100%">
  			<img src="/assets/WebServices13.png" alt="WebServices13" width="100%">
  			<img src="/assets/WebServices14.png" alt="WebServices14" width="100%">
  			<img src="/assets/WebServices15.png" alt="WebServices15" width="100%">
  			<img src="/assets/WebServices16.png" alt="WebServices16" width="100%">		
	</ul>
</div>

#### 5.2.3.8.Team Collaboration Insights during Sprint.
<div align="justify">
	Para este Sprint nos dispusimos a seguir mejorano nuestros productos. Primero, se llevo a cabo las mejoras necesarias al dieño front-end de la Web App. Con esto, se dio inicio a la
	creación de los Web Services que soportaran el apartado back-end.<br>
	Para que el trabajo sea efectivo, se dividieron las tareas por realizar, y cada uno se encargo de corregir los errores prensentes en sus partes previamente presentada. Este trabajo 
	puede corroborarse en los commits presentes en el repositorio de trabajo.<br>
</div>

Tabla para poder identificarnos:

|  UserName (Github)   	|    Nombre      |
| -------------------- 	| -------------|
|Anatoly69420		| Anatoly Andrey  Noriega Suschenko|
|Andres-0304		| Andres Fernando Rodriguez Zuluoeta  |
|JanielFranz           	| Janiel Franz Escalante Baygorrea |
|JP19-03               	| Johan Príncipe Godoy|
|ern23zc               	| Victor Ernesto Zarate Caceres |

##### Commits:
<img src="/assets/CommitsAnalysisS31.png" alt="CommitsAnalysis - Sprint 3">
<img src="/assets/CommitsAnalysisS32.png" alt="CommitsAnalysis - Sprint 3">

##### Analíticas de Colaboración:
<img src="/assets/ColaborationAnalysisS31.png" alt="ColaborationAnalysis - Sprint 3">

### 5.2.4. Sprint 4
#### 5.2.4.1.Spring Planning 4.
<table>
  <tr align="center">
    <td><strong>Sprint</strong></td>
    <td><strong>Sprint 4</strong></td>
  </tr>
  <tr align="center">
    <td>Date</td>
    <td>17/06/2024</td>
  </tr>
  <tr align="center">
    <td>Time</td>
    <td>11:00 AM</td>
  </tr>
  <tr align="center">
    <td>Location</td>
    <td>Presencial</td>
  </tr>
  <tr align="center">
    <td>Prepared by</td>
    <td>Group</td>
  </tr>
  <tr align="center">
    <td>Attendess (to planning meeting)</td>
    <td align="justify">
      Anatoly Andrey Noriega Suschenko - U202211813<br>
      Andres Fernando Rodriguez Zuluoeta - U202124213<br>
      Janiel Franz Escalante Baygorrea - U201912668<br>
      Johan Príncipe Godoy - U202014511<br>
      Victor Ernesto Zarate Caceres - U202112907</td>
  </tr>
  <tr align="center">
    <td>Sprint 3 Review Summary</td>
    <td align="justify">Se diseño una versión preliminar y funcional de los Web Services a ser implementados.</td>
  </tr>
  <tr align="center">
    <td>Sprint 3 Retrospective Summary</td>
    <td align="justify">El tiempo jugo en contra para llevar a la entrega. En esta ocasión, buscará realizarse con antelación.</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
  </tr>
  <tr align="center">
    <td>Sprint 4 Goal</td>
    <td align="justify">
    Versión Final de Web Application y Web Services<br>Conexión y deploy de ambas partes</td>
  </tr>
  <tr align="center">
    <td>Sprint 4 Velocity</td>
    <td>21</td>
  </tr>
  <tr align="center">
    <td>Sum of Story Point</td>
    <td>21</td>
  </tr>
</table>

#### 5.2.4.2.Sprint Backlog 4.
<img src="assets/sprintBack4.png">
Link del Trello: https://trello.com/invite/b/dFWCbvv5/ATTIe59f601ed779323810509cf1ed913c2fBC574E55/sprint-4
<div align="justify">
  <table>
    <tr align="center">
      <td colspan="2"><strong>Sprint</strong></td>
      <td colspan="6"><strong>Sprint 4</strong></td>
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
    <tr>
      <td>EP08</td>
      <td>Registro de reportes</td>
      <td>W-01</td>
      <td>Formulario de registro</td>
      <td>Configurar el formulario de registro para recibir toda la información requerida.</td>
      <td>3</td>
      <td>Johan Principe</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>EP08</td>
      <td>Registro de reportes</td>
      <td>W-02</td>
      <td>Tabla en BD</td>
      <td>Configurar la tabla en la que se almacenara la información</td>
      <td>3</td>
      <td>Franz Escalante</td>
      <td>In Process</td>
    </tr>
    <tr>
      <td>EP10</td>
      <td>Visualización de reportes</td>
      <td>W-03</td>
      <td>Ver reportes</td>
      <td>Observar los reportes correspondientes a la jurisdicción de la entidad gubernamental.</td>
      <td>3</td>
      <td>Johan Principe</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Seleccion de tipo de usuario</td>
      <td>W-04</td>
      <td>Registro como ciudadano</td>
      <td>Registrar un perfil ciudadano, con la información requerida.</td>
      <td>1</td>
      <td>Andres Rodriguez</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Seleccion de tipo de usuario</td>
      <td>W-05</td>
      <td>Registro como entidad gubernamental</td>
      <td>Registrar un perfil de entidad gubernamental, con la información requerida.</td>
      <td>1</td>
      <td>Andres Rodriguez</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>POST User</td>
      <td>W-06</td>
      <td>Almacenar ciudadano</td>
      <td>Almacenar la información en la base de datos tras el registro del usuarios</td>
      <td>2</td>
      <td>Anatoly Noriega</td>
      <td>In Process</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>POST User</td>
      <td>W-07</td>
      <td>Almacenar entidad gubernamental</td>
      <td>Almacenar la información en la base de datos tras el registro de la entidad gubernamental</td>
      <td>2</td>
      <td>Anatoly Noriega</td>
      <td>In Process</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>GET User</td>
      <td>W-09</td>
      <td>Iniciar Sesión - Usuario</td>
      <td>Usar el método GET para validar el inicio de sesión del ciudadano.</td>
      <td>3</td>
      <td>Ernesto Zarate</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>GET User</td>
      <td>W-09</td>
      <td>Iniciar Sesión - Entidad gubernamental</td>
      <td>Usar el método GET para validar el inicio de sesión del la Entidad Gubernamental.</td>
      <td>3</td>
      <td>Ernesto Zarate</td>
      <td>Done</td>
    </tr>
  </table>
</div>

#### 5.2.4.3.Development Evidence for Sprint Review.
<div align="justify">
	<table aling="justify">
<tr>
<td>Repository</td>
<td>Branch</td>
<td>Commit Id</td>
<td>Commit Message</td>
<td>Commit Message Body</td>
<td>Commited on (Date)</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>006fe5671d2075ece71b9d307091283615a2452f</td>
<td>chore: comments to improve in report</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>5fd8fc3a392b02782b6281656261b65b31883afa</td>
<td>fix: date deleted and created date added to the response.</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>bbe25d75e9acd9f5a811c14cab4dcc0fe174a180</td>
<td>fix: get by date repository fixed without error handling</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>bd7eba754f587da0cb72e0c4d9ee7d7c61d53411</td>
<td>feat(BaseRepository): id doesnt exist message added.</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>42051e23172c3cdc7f5edf9931e278edcf55ecf9</td>
<td>feat: Join Reports and Citizen</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>573af0c2356143ee4e60ee14a7774479ac5a4893</td>
<td>Merge remote-tracking branch 'origin/fix/reports' into temporal-merging</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>e195e3f1397e4e3bd930b137f4d3e8bee018f043</td>
<td>update</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>eedf26370faeba4919763fca94c976031ef01a66</td>
<td>fix: GET by District and Date</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>31c6ccabf5243090202dc606dfd08894ad063a83</td>
<td>chore: new packages</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>0dba83f6572948a78148cd8ed1f80428c410e8b1</td>
<td>feat(iam): added user aggregate</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>314c8c58bd03cfca4084b1b4ee5d9ac203464013</td>
<td>feat: commands and queries added</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>c2df13853714f8aca059df3b2019201f1349f819</td>
<td>feat(iam): domain services created</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>f581ab40bfdb17a6a547b83e04f1edd4ab8b81a6</td>
<td>feat(iam): added repository</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>c239d5abdcb2559b12c7e97dc699413c63142086</td>
<td>feat(iam): infrastructure layer added and appdbcontext new builders</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>8ac1adbdba06eea4ea1f4933617d88f71fc8eeb8</td>
<td>feat(iam): user repository</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>1f3f392812bfbe1282112a204b496b73eb2b9f98</td>
<td>feat(iam): added hashing and tokken in application layer</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>d8766cdb1f66bfb4866d8b67ea151a8282bdee0d</td>
<td>feat: GetAllReports</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>0109bc9f91a60c4561fed74f8bb2ab0ee47d582a</td>
<td>feat(iam): user command service application layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>73f834c330ae5c2e087714c216fc852746eb75d4</td>
<td>feat(iam): user query service in application layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>483fc069eb12753c22fcce98bd4cc9fe3773a444</td>
<td>feat(iam): hashing service in infrastructure layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>3903be863be21892230475ddb1f606126c928954</td>
<td>feat(reports): add new Endpoint of get all Reports by IdCitizen and get report by IdCitizen and ReportId</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>3668877c79c340cbeba5bb44e2c4e2fe04fe8019</td>
<td>Merge remote-tracking branch 'origin/feature/reports-v2' into feature/reports-v2</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>475e56e209f8fc629c7d607b3b111fc51ecd445d</td>
<td>fix(reports): fix the methods while the previous merge</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>2d914c6a2266681451f413988854e95bedb4c0b1</td>
<td>feat(iam): token in infrastructure layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>33b31ea5a772936bf87bf8302be3f37962aae43f</td>
<td>feat(iam): implemented token service</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>f6ec530f69f81a4958310a3cb5ca2511b72250ae</td>
<td>fix(iam): authorizations in infrastructure layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>92f0c68c3b00f98c6223ad103af1f4c01217aa69</td>
<td>feat(iam): pipeline finished</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>2cc890ea1d4b14e821979462dc9aaa5613ed909e</td>
<td>feat(iam): interfaces layer with rest</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>37257910afcef690d97f36b0479b0f4a9fd273af</td>
<td>feat(iam): implemented authentication controller</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>4799f4caac66f858b4aaf5eb96900abd1b19bd3b</td>
<td>feat(iam): iam controllers</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>ad5cb55ca1dd60da0773fed18d0ae6c8ed18ac7f</td>
<td>feat(iam): iam controller ready</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>406ca5005d0d2ce4faae0cbfc58699ce3bc9d586</td>
<td>feat(iam): facade added</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>3aab254e96c1ffbbe1d1d5a7375b9004e6f0f0d0</td>
<td>chore: readme added</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>e2c8b0e03d3cc0367d23fadf9d05d34581a96a0f</td>
<td>Merge remote-tracking branch 'origin/feature/reports-v2' into merging-v2</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>1ad644bb03254c6c2e41106b79515fea7ddb54da</td>
<td>feat: login and signup, services, models added and working</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>806771e9088197a6711b52c6e10036077fdf1f16</td>
<td>fix: Main Page styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>17ae71a0a7bf98b9ab28ff799ea89aae6d1ea580</td>
<td>fix: User Sign Up Form Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>e8dfaafd37e16314a64e7696367bed3912e2e8df</td>
<td>fix: Authority Sign Up Form Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>fd4289634cd185505bc6dadbe9c3198916925d63</td>
<td>feat: log out added and toolbars modificated</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>56eae4e8036af2d30811350ac7c6cb565b8aec82</td>
<td>fix: Authority Verification Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>eae6e32994901d67cbbc34de2cccbb3a66cfc1b5</td>
<td>Merge branch 'feature/version1' into fix/css-styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>d78879fb26589e324de64ec5f0534f5b1143fcea</td>
<td>fix: Reports Form Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>ecfc2ef050573e8d49ad59e5fcb373f56885c6a5</td>
<td>fix: Reports Form Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>88871ebf4f91144a91147ca66700b56a49d79060</td>
<td>fix: Authority Profile Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>48e8166665e5474b38b5c5e571f8a36c8009f48d</td>
<td>delete: Profile pages</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>e5ef542f6ebfae6783e56539bf81aaf94afc3ee3</td>
<td>fix: Authority Profile Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>94bcdf29121bf9aa1e028605a24f29b91799c5da</td>
<td>feat: maps added</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>88dadbe97ad2468e953e58eeda38558c70d8e017</td>
<td>fix: Authority Profile Edit Styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>e63c5f779ea5af4a14d771cd7cd416bea8b6dad9</td>
<td>Merge branch 'feature/version1' into fix/css-styles</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>e9b9c0667adf585ac625f8e06032f0a1527db2f5</td>
<td>delete: Routes</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>f07cbbe15d5c3ab9f626d2aec9d292a6030630f4</td>
<td>fix: User Profile Styles</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>07e83594a097f515a79fc1d25a242f78882842ac</td>
<td>fix: Edit Profile Styles</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>34afaea91894184760ed1b7aa4ce3d8711cca59a</td>
<td>fix: Method PUT</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>57a420a01603694b06a9944eeb9883e38c051486</td>
<td>fix: Authority Edit Styles</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>6c56e54915659d3a78988f9a3e045a956e5318a0</td>
<td>fix: Buttons Map Styles</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>646cb47f14ae4228dde8b6bae1e5723d3baa5d38</td>
<td>feat: Map Translation</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>02d902fed1ab6c14fdf42195e8a2e27d47483e22</td>
<td>feat: add support for German and French translations</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
<tr>
<td>web-app-project-develop-clean-version</td>
<td>/fix/css-styles/</td>
<td>d50d3086f76d5d42af58a13249277f793c369f38</td>
<td>feat: try to use azure</td>
<td>-</td>
<td>28/06/2024</td>
</tr>
</table>

</div>

#### 5.2.4.4.Testing Suite Evidence for Sprint Review.
<div align="justify">
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
	        <td></td>
	        <td></td>
	        <td></td>
	        <td></td>
	        <td></td>
	        <td></td>
	    </tr>
	</table>
</div>

#### 5.2.4.5.Execution Evidence for Sprint Review.
<div align="justify">
	Para la entrega del Sprint 4 se busco perfeccionar el diseño de la Web Application y conectarla con los Web Services para ponerla en total funcionamiento. Realizado esto, presentamos como evidencias:
</div>

##### Sección Main Page
<img src="/assets/MainPage.png" alt="MainPage" width="100%">

##### Sección Role Create Account
<img src="/assets/Role-CreateAccount.png" alt="Role-CreateAccount" width="100%">

##### Sección Form Citizen
<img src="/assets/Form-Citizen.png" alt="Form-Citizen" width="100%">

##### Sección Form Authority
<img src="/assets/Form-Authority.png" alt="Form-Authority" width="100%">

##### Sección Recovery Password
<img src="/assets/Recovery-Password.png" alt="Recovery-Password" width="100%">

##### Sección Find Route
<img src="/assets/Find-Route.png" alt="Find-Route" width="100%">

##### Sección Report List
<img src="/assets/Report-List.png" alt="Report-List" width="100%">

##### Sección Create Report
<img src="/assets/Create-Report.png" alt="Create-Report" width="100%">

##### Sección Profile Citizen
<img src="/assets/Profile-Citizen.png" alt="Profile-Citizen" width="100%">

##### Sección Profile Authority
<img src="/assets/Profile-Authority.png" alt="Profile-Authority" width="100%">

##### Sección Edit Profile
<img src="/assets/Edit-Profile.png" alt="Edit-Profile" width="100%">



#### 5.2.4.6.Services Documentation Evidence for Sprint Review.
<div align="justify">
	Para este sprint final se planificó terminar definitivamente el front-end de la aplicación, y conectarla al backend desplegado. Enlace para acceder 
	al <a href="https://6664a80f932baf9032abbc8e.mockapi.io/api/reports">MockAPI</a><br> 
	MockAPI:
	<table>
		<tr>
			<td>Endpoint</td>
			<td>Details</td>
		</tr>
		<tr>
			<td>/reports</td>
			<td>Se implementaron las operaciones CRUD para lograr el registro de nuevos reportes y su llamado para la ventana correspondiente.</td>
		</tr>
	</table>
	Web Service:
	<table>
        <tr>
            <td>Endpoint</td>
            <td>Details</td>
        </tr>
        <tr>
            <td>/Authentications</td>
            <td>Se implementaron las operaciones CRUD para lograr el registro de nuevos usuarios y su autenticación.</td>
        </tr>
        <tr>
            <td>/Citizens</td>
            <td>Se implementaron las operaciones CRUD para lograr el registro de nuevos ciudadanos.</td>
        </tr>
        <tr>
            <td>/Notification</td>
            <td>Se implementaron las operaciones CRUD para lograr el registro de notificaciones y su llamado para la ventana correspondiente.</td>
        </tr>
        <tr>
            <td>/OrganizationsAccount</td>
            <td>Se implementaron las operaciones CRUD para lograr el registro de nuevas organizaciones.</td>
        </tr>
        <tr>
            <td>/ReportsManagement</td>
            <td>Se implementaron las operaciones CRUD para lograr el manejo de los reportes que se han registrado.</td>
        </tr>
        <tr>
            <td>/Users</td>
            <td>Se implementaron las operaciones CRUD para lograr el manejo de los usuarios que se han registrado.</td>
        </tr>
</table>
	<table>
<tr>
    <td>Endpoint</td>
    <td>Operaciones</td>
    <td>Parametros</td>
    <td>URL</td>
</tr>
<tr>
    <td rowspan="2">Authentication</td>
    <td>POST</td>
    <td>No tiene</td>
    <td>api/v1/authentication/sign-up</td>
</tr>
<tr>
    <td>POST</td>
    <td>No tiene</td>
    <td>api/v1/authentication/sign-in</td>
</tr>
<tr>
    <td rowspan="5">Citizens</td>
    <td>POST</td>
    <td>No tiene</td>
    <td>api/v1/citizens</td>
</tr>
<tr>
    <td>GET</td>
    <td>No tiene</td>
    <td>api/v1/citizens</td>
</tr>
<tr>
    <td>GET</td>
    <td>{citizenId}</td>
    <td>api/v1/citizens/{citizenId}</td>
</tr>
<tr>
    <td>PUT</td>
    <td>{citizenId}</td>
    <td>api/v1/citizens/{citizenId}</td>
</tr>
<tr>
    <td>DELETE</td>
    <td>{citizenId}</td>
    <td>api/v1/citizens/{citizenId}</td>
</tr>
<tr>
    <td rowspan="4">Notification</td>
    <td>POST</td>
    <td>No tiene</td>
    <td>api/v1/notification</td>
</tr>
<tr>
    <td>GET</td>
    <td>No tiene</td>
    <td>api/v1/notification</td>
</tr>
<tr>
    <td>GET</td>
    <td>{id}</td>
    <td>api/v1/notification/{id}</td>
</tr>
<tr>
    <td>GET</td>
    <td>{priority}</td>
    <td>api/v1/notification/priority/{priority}</td>
</tr>
<tr>
    <td rowspan="2">OrganizationsAccount</td>
    <td>POST</td>
    <td>No tiene</td>
    <td>api/v1/organizations-account</td>
</tr>
<tr>
    <td>GET</td>
    <td>{organizationName}</td>
    <td>api/v1/organizations-account/{organizationName}</td>
</tr>
<tr>
    <td rowspan="5">ReportsManagement</td>
    <td>POST</td>
    <td>No tiene</td>
    <td>api/v1/reports</td>
</tr>
<tr>
    <td>GET</td>
    <td>No tiene</td>
    <td>api/v1/reports</td>
</tr>
<tr>
    <td>GET</td>
    <td>{id}</td>
    <td>api/v1/reports/{id}</td>
</tr>
<tr>
    <td>GET</td>
    <td>{citizenId}</td>
    <td>api/v1/reports/citizen/{citizenId}</td>
</tr>
<tr>
    <td>GET</td>
    <td>{citizenId},{id}</td>
    <td>api/v1/reports/{citizenId},{id}</td>
</tr>
<tr>
    <td rowspan="2">Users</td>
    <td>GET</td>
    <td>{id}</td>
    <td>api/v1/users/{id}</td>
</tr>
<tr>
    <td>GET</td>
    <td>No tiene</td>
    <td>api/v1/users</td>
</tr>
</table>
	<br>
	Web service images
	<br>
			<img src="/assets/WebServices1-sprint4.png" alt="WebServices1-sprint4" width="100%">
  			<img src="/assets/WebServices2-sprint4.png" alt="WebServices2-sprint4" width="100%">
 			<img src="/assets/WebServices3-sprint4.png" alt="WebServices3-sprint4" width="100%">
  			<img src="/assets/WebServices4-sprint4.png" alt="WebServices4-sprint4" width="100%">
  			<img src="/assets/WebServices5-sprint4.png" alt="WebServices5-sprint4" width="100%">
			<img src="/assets/WebServices6-sprint4.png" alt="WebServices6-sprint4" width="100%">
  			<img src="/assets/WebServices7-sprint4.png" alt="WebServices7-sprint4" width="100%">
  			<img src="/assets/WebServices8-sprint4.png" alt="WebServices8-sprint4" width="100%">
  			<img src="/assets/WebServices9-sprint4.png" alt="WebServices9-sprint4" width="100%">
  			<img src="/assets/WebServices10-sprint4.png" alt="WebServices10-sprint4" width="100%">
  			<img src="/assets/WebServices11-sprint4.png" alt="WebServices11-sprint4" width="100%">
  			<img src="/assets/WebServices12-sprint4.png" alt="WebServices12-sprint4" width="100%">
  			<img src="/assets/WebServices13-sprint4.png" alt="WebServices13-sprint4" width="100%">
  			<img src="/assets/WebServices14-sprint4.png" alt="WebServices14-sprint4" width="100%">
  			<img src="/assets/WebServices15-sprint4.png" alt="WebServices15-sprint4" width="100%">
  			<img src="/assets/WebServices16-sprint4.png" alt="WebServices16-sprint4" width="100%">	
			<img src="/assets/WebServices17-sprint4.png" alt="WebServices17-sprint4" width="100%">	
			<img src="/assets/WebServices18-sprint4.png" alt="WebServices18-sprint4" width="100%">	
			<img src="/assets/WebServices19-sprint4.png" alt="WebServices19-sprint4" width="100%">	
			<img src="/assets/WebServices20-sprint4.png" alt="WebServices20-sprint4" width="100%">	
	Link del repositorio: https://github.com/G2WebApplication-WX54/peace-app-backend<br>
	Web service commit details:
<table aling="justify">
<tr>
<td>Repository</td>
<td>Branch</td>
<td>Commit Id</td>
<td>Commit Message</td>
<td>Commit Message Body</td>
<td>Commited on (Date)</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>006fe5671d2075ece71b9d307091283615a2452f</td>
<td>chore: comments to improve in report</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>5fd8fc3a392b02782b6281656261b65b31883afa</td>
<td>fix: date deleted and created date added to the response.</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>bbe25d75e9acd9f5a811c14cab4dcc0fe174a180</td>
<td>fix: get by date repository fixed without error handling</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>bd7eba754f587da0cb72e0c4d9ee7d7c61d53411</td>
<td>feat(BaseRepository): id doesnt exist message added.</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>42051e23172c3cdc7f5edf9931e278edcf55ecf9</td>
<td>feat: Join Reports and Citizen</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>573af0c2356143ee4e60ee14a7774479ac5a4893</td>
<td>Merge remote-tracking branch 'origin/fix/reports' into temporal-merging</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>e195e3f1397e4e3bd930b137f4d3e8bee018f043</td>
<td>update</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>eedf26370faeba4919763fca94c976031ef01a66</td>
<td>fix: GET by District and Date</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>31c6ccabf5243090202dc606dfd08894ad063a83</td>
<td>chore: new packages</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>0dba83f6572948a78148cd8ed1f80428c410e8b1</td>
<td>feat(iam): added user aggregate</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>314c8c58bd03cfca4084b1b4ee5d9ac203464013</td>
<td>feat: commands and queries added</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>c2df13853714f8aca059df3b2019201f1349f819</td>
<td>feat(iam): domain services created</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>f581ab40bfdb17a6a547b83e04f1edd4ab8b81a6</td>
<td>feat(iam): added repository</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>c239d5abdcb2559b12c7e97dc699413c63142086</td>
<td>feat(iam): infrastructure layer added and appdbcontext new builders</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>8ac1adbdba06eea4ea1f4933617d88f71fc8eeb8</td>
<td>feat(iam): user repository</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>1f3f392812bfbe1282112a204b496b73eb2b9f98</td>
<td>feat(iam): added hashing and tokken in application layer</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>d8766cdb1f66bfb4866d8b67ea151a8282bdee0d</td>
<td>feat: GetAllReports</td>
<td>-</td>
<td>26/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>0109bc9f91a60c4561fed74f8bb2ab0ee47d582a</td>
<td>feat(iam): user command service application layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>73f834c330ae5c2e087714c216fc852746eb75d4</td>
<td>feat(iam): user query service in application layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>483fc069eb12753c22fcce98bd4cc9fe3773a444</td>
<td>feat(iam): hashing service in infrastructure layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>3903be863be21892230475ddb1f606126c928954</td>
<td>feat(reports): add new Endpoint of get all Reports by IdCitizen and get report by IdCitizen and ReportId</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>3668877c79c340cbeba5bb44e2c4e2fe04fe8019</td>
<td>Merge remote-tracking branch 'origin/feature/reports-v2' into feature/reports-v2</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>475e56e209f8fc629c7d607b3b111fc51ecd445d</td>
<td>fix(reports): fix the methods while the previous merge</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>2d914c6a2266681451f413988854e95bedb4c0b1</td>
<td>feat(iam): token in infrastructure layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>33b31ea5a772936bf87bf8302be3f37962aae43f</td>
<td>feat(iam): implemented token service</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>f6ec530f69f81a4958310a3cb5ca2511b72250ae</td>
<td>fix(iam): authorizations in infrastructure layer</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>92f0c68c3b00f98c6223ad103af1f4c01217aa69</td>
<td>feat(iam): pipeline finished</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>2cc890ea1d4b14e821979462dc9aaa5613ed909e</td>
<td>feat(iam): interfaces layer with rest</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>37257910afcef690d97f36b0479b0f4a9fd273af</td>
<td>feat(iam): implemented authentication controller</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>4799f4caac66f858b4aaf5eb96900abd1b19bd3b</td>
<td>feat(iam): iam controllers</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>ad5cb55ca1dd60da0773fed18d0ae6c8ed18ac7f</td>
<td>feat(iam): iam controller ready</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>406ca5005d0d2ce4faae0cbfc58699ce3bc9d586</td>
<td>feat(iam): facade added</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>3aab254e96c1ffbbe1d1d5a7375b9004e6f0f0d0</td>
<td>chore: readme added</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
<tr>
<td>peace-app-backend</td>
<td>/master</td>
<td>e2c8b0e03d3cc0367d23fadf9d05d34581a96a0f</td>
<td>Merge remote-tracking branch 'origin/feature/reports-v2' into merging-v2</td>
<td>-</td>
<td>27/06/2024</td>
</tr>
</table>

</div>

#### 5.2.4.7.Software Deployment Evidence for Sprint Review.
<div align="justify">
	Para el presente sprint, se conectaron los Web Services con la Web Application completamente funcional, cumpliendo los user stories correspondientes. A su vez, se cumplio internacionalizar la plataforma, haciendola más accesible a las personas.
	<ul>
		<li>Landing Page:</li>
			<img src="/assets/LandingPage-Sprint4.png" alt="LandingPage-Sprint4" width="100%">
		<li>Web Application (Front-End):</li>
			<img src="/assets/MainPage.png" alt="MainPage" width="100%">
			<img src="/assets/Role-CreateAccount.png" alt="Role-CreateAccount" width="100%">
			<img src="/assets/Form-Citizen.png" alt="Form-Citizen" width="100%">
			<img src="/assets/Form-Authority.png" alt="Form-Authority" width="100%">
			<img src="/assets/Recovery-Password.png" alt="Recovery-Password" width="100%">
			<img src="/assets/Find-Route.png" alt="Find-Route" width="100%">
			<img src="/assets/Report-List.png" alt="Report-List" width="100%">
			<img src="/assets/Create-Report.png" alt="Create-Report" width="100%">
			<img src="/assets/Profile-Citizen.png" alt="Profile-Citizen" width="100%">
			<img src="/assets/Profile-Authority.png" alt="Profile-Authority" width="100%">
			<img src="/assets/Edit-Profile.png" alt="Edit-Profile" width="100%">
		<li>Web Services (Back-End): </li>	
			<img src="/assets/WebServices1-sprint4.png" alt="WebServices1-sprint4" width="100%">
  			<img src="/assets/WebServices2-sprint4.png" alt="WebServices2-sprint4" width="100%">
 			<img src="/assets/WebServices3-sprint4.png" alt="WebServices3-sprint4" width="100%">
  			<img src="/assets/WebServices4-sprint4.png" alt="WebServices4-sprint4" width="100%">
  			<img src="/assets/WebServices5-sprint4.png" alt="WebServices5-sprint4" width="100%">
			<img src="/assets/WebServices6-sprint4.png" alt="WebServices6-sprint4" width="100%">
  			<img src="/assets/WebServices7-sprint4.png" alt="WebServices7-sprint4" width="100%">
  			<img src="/assets/WebServices8-sprint4.png" alt="WebServices8-sprint4" width="100%">
  			<img src="/assets/WebServices9-sprint4.png" alt="WebServices9-sprint4" width="100%">
  			<img src="/assets/WebServices10-sprint4.png" alt="WebServices10-sprint4" width="100%">
  			<img src="/assets/WebServices11-sprint4.png" alt="WebServices11-sprint4" width="100%">
  			<img src="/assets/WebServices12-sprint4.png" alt="WebServices12-sprint4" width="100%">
  			<img src="/assets/WebServices13-sprint4.png" alt="WebServices13-sprint4" width="100%">
  			<img src="/assets/WebServices14-sprint4.png" alt="WebServices14-sprint4" width="100%">
  			<img src="/assets/WebServices15-sprint4.png" alt="WebServices15-sprint4" width="100%">
  			<img src="/assets/WebServices16-sprint4.png" alt="WebServices16-sprint4" width="100%">	
			<img src="/assets/WebServices17-sprint4.png" alt="WebServices17-sprint4" width="100%">	
			<img src="/assets/WebServices18-sprint4.png" alt="WebServices18-sprint4" width="100%">	
			<img src="/assets/WebServices19-sprint4.png" alt="WebServices19-sprint4" width="100%">	
			<img src="/assets/WebServices20-sprint4.png" alt="WebServices20-sprint4" width="100%">	
	</ul>
</div>

#### 5.2.4.8.Team Collaboration Insights during Sprint.
<div align="justify">
	Para este Sprint nos dispusimos a perfeccionar nuestros productos. Primero, se llevo a cabo las mejoras finales a los diseño Front-End y Back-End de la Web App. Con esto, se pudo dar inicio, al despliegue de este último y a unir ambos para cumplir con la entrega final de este trabajo.
	Para terminar de manera efectiva, se dividio el trabajo. Dicho trabajo puede corroborarse en los commits presentes en el repositorio de trabajo.<br>
</div>

Tabla para poder identificarnos:

|  UserName (Github)   	|    Nombre      |
| -------------------- 	| -------------|
|Anatoly69420		| Anatoly Andrey  Noriega Suschenko|
|Andres-0304		| Andres Fernando Rodriguez Zuluoeta  |
|JanielFranz           	| Janiel Franz Escalante Baygorrea |
|JP19-03               	| Johan Príncipe Godoy|
|ern23zc               	| Victor Ernesto Zarate Caceres |

##### Commits:
<img src="/assets/CommitsAnalysisS41.png" alt="CommitsAnalysis (Web App) - Sprint 4">
<img src="/assets/CommitsAnalysisS42.png" alt="CommitsAnalysis (Web Services) - Sprint 4">

##### Analíticas de Colaboración:
<img src="/assets/ColaborationAnalysisS41.png" alt="ColaborationAnalysis (Web App)- Sprint 4">
<img src="/assets/ColaborationAnalysisS42.png" alt="ColaborationAnalysis (Web Services) - Sprint 4">
	
## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
<div align="justify">
	En este segmento, se esbozan las metas específicas de los usuarios que guían nuestras entrevistas. Estos "User Goals" son fundamentales para garantizar que la aplicación web cumpla con las necesidades auténticas de los usuarios en el ámbito de la seguridad y la prevención del crimen. A continuación, se presentan los objetivos del usuario mencionados:
	<ul>
		<li><b>User Goal: Iniciar Sesión</b></li>
		<b>User Persona: Entidad Gubernamental y Ciudadanos.</b><br>
		<b>Explicación del Flujo:</b> Inicialmente, el usuario deberá ingresar a la aplicación
		implementada. Posteriormente, verá en su pantalla un formulario que solicitará sus datos de acceso, específicamente, su correo electrónico y contraseña. Si estos son validados, el sistema redirigirá al usuario a "Find Route". De lo contrario, permanecerá en la pantalla de inicio de sesión y se le solicitará que reintroduzca sus credenciales.
		<li><b>User Goal: Crear un Nuevo Usuario</b></li>
		<b>User Persona: Entidad Gubernamental y Ciudadano.</b><br>
		<b>Explicación del Flujo:</b> En primer lugar, el usuario deberá acceder a la sección "Sign Up", dentro de la cual podrá seleccionar el tipo de cuenta que desea crear: "Citizen" o "Authority". Una vez seleccionado el tipo de cuenta, se desplegará un diálogo con casillas de texto, dentro de las cuales los usuarios podrán registrar la información necesaria.
		<li><b>User Goal: Registrar Reportes</b></li>
		<b>User Persona: Ciudadanos.</b><br>
		<b>Explicación del Flujo:</b> En primer lugar, el usuario debe acceder a la sección "Report List". A continuación, deberá presionar el botón situado en la parte inferior que indica "New Report". Una vez presionado, se le redirigirá a un formulario donde deberá llenar con los datos que se le solicitan. Una vez que los datos estén completos, deberá presionar el botón que indica "Send".
		<li><b>User Goal: Ver Perfil</b></li>
		<b>User Persona: Entidad Gubernamental y Ciudadano.</b><br>
		<b>Explicación del Flujo:</b> En todo momento, el usuario visualizará en la parte superior de la aplicación una barra de navegación. Cuando presione el símbolo de un engranaje, que se encuentra situado en el extremo derecho de la barra de navegación, podrá acceder a su perfil de usuario. En este podrá realizar actividades de relevancia, tales como ver su rol dentro de la organización y actualizar sus datos personales.
		<li><b>User Goal: Mostrar Ruta</b></li>
		<b>User Persona: Ciudadano.</b><br>
		<b>Explicación del Flujo:</b> En primer lugar, el usuario debe acceder a la sección "Find Route". A continuación, deberá ingresar el lugar al que se quiere dirigir y después se le mostrará el recorrido que debe realizar.
	</ul>
</div>

### 5.3.2. Registro de Entrevistas.
##### Enlace de las entrevistas:
#### Segmento 1:  
<div align="justify">
	<table>
		<tr>
			<td>Entrevista 1: </td>
			<td>Fatima Urbina</td>
		</tr>
		<tr>
			<td colspan="2" ><img src="/assets/Entrevista-Andres-Fatima.jpg" alt="Entrevista-Andres-Fatima"></td>
		</tr>
		<tr>
		<td colspan="2">Mientras navegaba por la aplicación web, Fátima destacó la facilidad de entendimiento y la dinámica de la interfaz. No obstante, mencionó que, habiéndose ya creado una cuenta como usuario y después de iniciar sesión, no debería tener 		que indicar si es usuario o autoridad; la página debería reconocer si ella es usuario o autoridad. También señaló que las notificaciones deberían actualizarse de manera automática y no manualmente. Por último, indicó que cuando se dirige a la 			visualización de perfil, debería aparecerle su perfil directamente sin tener que seleccionar su tipo de usuario.</td>
		</tr>
		<tr>
			<td colspan="2">Tiempo en el video: 06:54 Link: https://drive.google.com/file/d/12LXgBU5WvKAfV2lRNnldmr8W4ukhf8No/view?usp=sharing</td>
		</tr>
	</table>
	<table>
		<tr>
			<td>Entrevista 2: </td>
			<td>Mauricio Rojas</td>
		</tr>
		<tr>
			<td colspan="2" ><img src="/assets/Entrevista-Anatoly-Mauricio.png" alt="Entrevista-Anatoly-Mauricio"></td>
		</tr>
		<tr>
		<td colspan="2">Mientras el ciudadano Mauricio accedia a la aplicación web, mencionó que le parecio interesante el apartado del mapa junto con las rutas y la funcionalidad de reportes. Comenta que en general la aplicación supero sus expectativas generales. Sin embargo, algo a destacar que menciono el usuario es que en si no hay una validación de los datos al momento de crear una nueva cuenta. Al momento de crear la cuenta y darle al botón de submit directamente lo redirige a la seccion de perfil de ciudadano junto con datos ya preestablecidos de la página y no con los datos reales.</td>
		</tr>
		<tr>
			<td colspan="2">Tiempo en el video: 00:00</td>
		</tr>
	</table>
</div>

#### Segmento 2:
<div align="justify">
	<table>
		<tr>
			<td>Entrevista 1: </td>
			<td></td>
		</tr>
		<tr>
			<td colspan="2" ></td>
		</tr>
		<tr>
		<td colspan="2"></td>
		</tr>
		<tr>
			<td colspan="2">Tiempo en el video: 00:00</td>
		</tr>
	</table>
	<table>
		<tr>
			<td>Entrevista 2: </td>
			<td></td>
		</tr>
		<tr>
			<td colspan="2" ></td>
		</tr>
		<tr>
		<td colspan="2"></td>
		</tr>
		<tr>
			<td colspan="2">Tiempo en el video: 00:00</td>
		</tr>
	</table>
</div>

### 5.3.3. Evaluaciones según heurísticas.

**ESCALA DE SEVERIDAD:** <br>

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:
<br>
| Nivel |Descripción                                                                                                  |
|-------|-------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.                   |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta                                 |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                              |

**Tabla de resumen:** <br>

**Web Application:** <br>

| # | Problema | Escala de severida | Heurística/Principio violado(a) |
|---|----------|--------------------|---------------------------------|
| 1 |No se valida la información al crear una cuenta para el ciudadano.|4|Usability: Prevención de errores|
| 2 |Visualización Directa del Perfil|2|Consistency and Standards|
|   |          |                    |                                 |
|   |          |                    |                                 |

<br>

**PROBLEMA #1: No se valida la información al crear una cuenta para el ciudadano**
- Severidad: 4
Heurística violada: Usabilidad - Prevención de errores

- Problema:
La aplicación permite a los usuarios crear cuentas sin validar la información ingresada, permitiendo que los usuarios accedan sin llenar ningún campo y mostrando datos preestablecidos.

- Recomendación:
Implementar validaciones de campos obligatorios al crear una cuenta para asegurar que se ingresen datos completos y correctos.
<img src="/assets/EvidenciaProblema1.png" alt="Evidencia Problema 1">

**PROBLEMA #2:**
- Severidad: 2
Heurística violada: Consistency and Standards

- Problema:Al dirigirse a la visualización de perfil, el usuario debe seleccionar su tipo de usuario en lugar de mostrar directamente su perfil.

- Recomendación: Ajustar la navegación de la aplicación para que, al acceder a la visualización del perfil, se muestre automáticamente el perfil correspondiente sin pasos adicionales.
<img src="/assets/EvidenciaProblema2.png" alt="Evidencia Problema 2">

**PROBLEMA #3:**
- Severidad: 

- Problema:

- Recomendación:
<img src="/assets/EvidenciaProblema3.png" alt="Evidencia Problema 3">

**PROBLEMA #4:**
- Severidad: 

- Problema:

- Recomendación:
<img src="/assets/EvidenciaProblema4.png" alt="Evidencia Problema 4">

## 5.4. Video About-the-Product.
### Versión 1:
<img src="/assets/About-the-Product.png" alt="About-the-Product(v1)">
Enlace: https://youtu.be/sA65PrsZbco

### Versión 2:
<img src="/assets/About-the-Product2.png" alt="About-the-Product(v2)">
Enlace: 

# Conclusiones
## Conclusiones y Recomendaciones
<div align="justify">
	<ul>
    <li>Conclusiones:</li>
    <ul>
      <li>Se comprendio la problemática que enfrenta Perú y su impacto en la población. El análisis competitivo nos ayudó a identificar a nuestros competidores y desarrollar estrategias para superarlos.</li>
      <li>El needfinding nos permitió entender mejor a nuestros usuarios y sus necesidades, lo que nos ayudó a idear una solución que satisfaga sus expectativas.</li>
      <li>Utilizando el Product Backlog y el Impact Map, priorizamos las necesidades de nuestros usuarios. El diseño UX/UI resultó en interfaces innovadoras y atractivas para nuestra aplicación.</li>
      <li>Las validaciones y auditorías nos permitieron refinar y mejorar nuestros productos continuamente. Al finalizar la TB2 y con la implementación de la web applications, empezamos a recibir retroalimentación de los usuarios para resolver de mejor manera el problema y desarrollar un amejor solución.</li>
    <li>La presentación de evidencia de despliegue de software durante la revisión del sprint muestra que las funcionalidades están siendo probadas y puestas en producción de manera efectiva.</li>
<li>Durante el sprint actual, se han conectado servicios web, lo que indica progreso en la integración y comunicación entre diferentes partes del sistema. Esto es crucial para el funcionamiento cohesivo de la aplicación.</li>
</ul>
    <li>Recomendaciones:</li>
    <ul>
      <li>Continuar adoptando y mejorando las prácticas ágiles, asegurando que todos los sprints terminen con una revisión y retrospectiva para identificar áreas de mejora en el proceso de desarrollo.</li>
<li>Implementar revisiones de código regulares y obligatorias para asegurar la calidad y consistencia del código entre todos los miembros del equipo</li>    
</ul>
  </ul>
</div>

## Video About-The-Team
<div align="justify">
El video ofrece un resumen del trabajo del equipo, en el cual los integrantes detallan las tareas que realizaron para alcanzar los objetivos del curso. Los miembros del equipo resaltan la importancia de la comunicación oral y escrita como un método eficiente para compartir ideas y comunicar el avance del proyecto.
El video tiene una duracion de 15:04 minutos. Desde el minuto 0:00 al 0:56 el integrante Johan Príncipe explica su aporte al proyecto. Del 0:57 al 2:49, Ernesto Zarate habla de su participación en el proyecto junto con sus aportes en el mismo. Del minuto 2:50 al 4:17 continúa Andres Rodriguez, seguidamente de Franz Escalantes desde el minuto 4:19 al 5:45. El video concluye con Anatoly Noriega dando explicación de sus aportes para el trabajo y las metas que logró.
<img src="/assets/About-the-Team.png" alt="About-the-Team(v1)">
Enlace: https://youtu.be/NIMv12_64jI 
</div>

# Bibliografía
<div align="justify">
  <ul>
    <li>Quispe García, E. (2020). <em>Seguridad Ciudadana: Una mirada al servicio efectuado por las municipalidades.</em> Recuperado de http://repositorio.contraloria.gob.pe/handle/ENC/21</li>
    <li>Gómez, P. J. M. (2020). <em>Las juntas vecinales de seguridad ciudadana y su relación con la lucha contra la delincuencia común: estudio de caso de la Municipalidad de San Martín de Porres. Revista de Ciencia e Investigación en Defensa, 1(4), 49-62. </em>Recuperado de https://www.recide.caen.edu.pe/index.php/recide/article/download/37/33</li>    
    <li>INEI. <em>Instituto Nacional de Estadistica e Informatica. </em>Recuperado de https://m.inei.gob.pe/biblioteca-virtual/boletines/estadisticas-de-seguridad-ciudadana/1/#lista </li>
    <li>Rivero Ruiz, C. S. (2023). <em>Ejecución presupuestal de la Policía Nacional del Perú y su incidencia en la seguridad ciudadana, periodo 2017-2020.</em> Recuperado de https://hdl.handle.net/20.500.13084/6851</li>
    <li>Banco Mundial. (2017). <em>c.</em> Recuperado de https://www.bancomundial.org</li>
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
		<td>
			Cantidad de videos: 4<br>
			Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-expo-tb1<br>
			Formato: .mp4<br>
			Duración:<br>
			Enlace:<br><br>
			Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-expo-tp1<br>
			Formato: .mp4<br>
			Duración: 14:10<br>
			Enlace: https://shorturl.at/msvzQ<br><br>
			Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-expo-tb2<br>
			Formato: .mp4<br>
			Duración:<br>
			Enlace:<br><br>
      Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-expo-tf<br>
			Formato: .mp4<br>
			Duración:<br>
			Enlace:<br><br>
		</td>
	</tr>
	<tr>
		<td>Entrevistas</td>
		<td>
			Cantidad de videos: 2<br>
			Nomenclatura: Interview Web Development<br>
			Formato: .mp4<br>
			Duración: 24:10<br>
			Enlace: https://shorturl.at/clwGR<br><br>
			Nomenclatura: Validation interviews<br>
			Formato: .mp4<br>
			Duración: <br>
			Enlace: <br><br>
		</td>
	  </tr>
	<tr>
		<td>Video About-the-Product</td>
		<td>
			Cantidad de videos: 2<br>
			Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-About-the-Product<br>
			Formato: .mp4<br>
			Duración: 5:13<br>
			Enlace: https://youtu.be/sA65PrsZbco<br><br>
      Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-About-the-Product-v2<br>
			Formato: .mp4<br>
			Duración: <br>
			Enlace: 
		</td>
	</tr>
	<tr>
		<td>Video About-the-Team</td>
		<td>
			Cantidad de videos: 1<br>
			Nomenclatura: upc-pre202401-si730-WX54-PeaceApp-About-the-Team<br>
			Formato: .mp4<br>
			Duración: 15:04<br>
			Enlace: https://youtu.be/NIMv12_64jI
		</td>
	</tr>
</table>
