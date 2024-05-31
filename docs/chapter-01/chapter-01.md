<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br>
    <img src="../../assets/logo-upc.png" alt="UPC Logo"><br>
    <br>
    <strong>Ingeniería de Software - 2024-01</strong><br>
    <br>
    <strong>Aplicaciones Web - WX54</strong><br>  
    <br>
    <strong>Profesor: Alex Humberto Sánchez Ponce</strong><br>
    <br> <strong>INFORME DE TRABAJO FINAL - TB2 </strong> 
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
<br>

# Project Report Collaboration Insights
Para el desarrollo del informe se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:

| Integrantes| Tareas designadas|
| :------------- |:-------------|
|Escalante Baygorrea, Janiel Franz|Lean UX Process, Software Object-Oriented Design, Diagrama de base de datos, Diagrama UML y parte del Landing Page|
|Noriega Suschenko, Anatoly Andrey|Segmentos objetivo, Competidores, Analisis Competitivo, Entrevista, Landing Page UI Design, Web Application UX/UI Design, Web Application Prototyping y parte del Landing Page|
|Príncipe Godoy, Johan|Needfinding, Ubiquitous Language, To-Be Scenario Mapping, Domain-Driven Software Architecture y parte del Landing Page|
|Rodriguez Zuluoeta, Andres Fernando|Diseño de entrevistas, Analisis de entrevistas, Needfinding, User Personas, User Stories, Impact Mapping, Product Backlog, Software Configuration Managemente y parte del Landing Page|
|Zarate Caceres, Victor Ernesto|Startup Profile, Solution Profile, Registor de entrevista, Style Guidelines, Information Arquitecture y parte del Landing Page|

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
- [5.3.Validation Interviews](#53-validation-interviews)
    - [Diseño de Entrevistas](#531-sprint-1)
    - [Registro de Entrevistas](#532-sprint-1)
    - [Evaluaciones según heurísticas](#533-sprint-1)
-  [5.4.Video About-the-Product](#54-video-about-the-product)

### [Conclusiones](#conclusiones-1)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Product](#video-about-the-product)

### [Bibliografía](#bibliografía-1)
### [Anexos](#anexos-1)
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
              TB1<br><br>
              <b>Escalante Baygorrea, Janiel Franz</b><br>
              He realizado la seccion del UX LEAN Process, Software Object-Oriented Design, Diagrama de base de datos, Diagrama UML y parte del Landing Page.
              Mi participación en el equipo fue fundamental para el desarrollo del proyecto, cumpliendo con todas las tareas asignadas y aportando ideas para 
              el desarrollo de la plataforma.
              <br><br>
              <b>Noriega Suschenko, Anatoly Andrey</b><br>
              He realizado la sección de Segmentos objetivos para identificar cuales serán nuestros principales usuarios para la plataforma, también el analisis de competidores junto con las estrategias 
              para evaluar quienes son nuestros rivales potenciales dentro del mercado y evaluar estrategias para poder aprovechar nuestras oportunidades y fortalezas para afrontar las debilidades y amenazas.
              También realice la entrevista del segmento usuario para poder evaluar lo que requieren nuestros usuarios potenciales y realice los diseños tanto de los Wireframes y Mock-Ups de la Landing Page 
              como de la Web Application y realizar un prototipo de como sera nuestra plataforma.
              <br><br>          
              <b>Príncipe Godoy, Johan</b><br>
              Para el desarrollo del proyecto, participé eficazmente en la creación de los User Task Matrix, Journey Mapping, Empathy Mapping, As-Is y To-be Scenario Mapping
              <br><br>
              <b>Rodriguez Zuluoeta, Andres Fernando</b><br>
              He realizado el diseño y posterior analisis de entrevistas,user personas de cada segmento obejtivo, user stories con sus respectivos criterios de aceptacion, impact mapping, product backlog y el 
              software configuration management.
              <br><br>
              <b>Zarate Caceres, Victor Ernesto</b><br>
              Se participo activamente en identificar el problema a enfrentar y la solución que se utilizara. Para cumplir el trabajo, se realizaron todas las tareas encomendadas, como lo son la introducción,
              el perfil de la Startup, el perfil de la solución y el diseño de producto con todas las guidelines e información de arquitectura necesaria.<br><br>
              TP<br><br>
              <b>Escalante Baygorrea, Janiel Franz</b><br>
              <br><br>
              <b>Noriega Suschenko, Anatoly Andrey</b><br>
              He realizado la corrección de algunos puntos del proyecto como lo serían el Ubiquitous Language, el Domain-Driven Software Architecture, junto con el Sprint 1 que en el envío pasado no estaba presente. Así mismo participe en la realización de la Web Application y poner como predeterminado el idioma inglés en la Landing Page.<br><br>          
              <b>Príncipe Godoy, Johan</b><br>
              <br><br>
              <b>Rodriguez Zuluoeta, Andres Fernando</b><br>
              <br><br>
              <b>Zarate Caceres, Victor Ernesto</b><br>
              Se participo con la correción de puntos anteriores, como en el resumen y análisis de entrevistas, el Journey Mapping en su versión As-Is, las User Stories y su Product Backlog. Además, se realizo
              la recopliación de evidencias para la creación del Sprint 2, correspondiente a esta entrega. 
          </td>
          <td>
              TB1<br>
              Se llevó a cabo un análisis completo que ayudo a identificar a nuestros potenciales clientes, evaluando a la competencia y como enfrentarla. El desarrollo del proyecto incluyó la elaboración de 
              diversos mapas para entender todo de mejor manera. En general, se aseguro el cumplimiento de todas las tareas encomendadas y para dar un enfoque sólido y bien fundamentado al proyecto.<br><br>
              TP<br>
              <br><br>
          </td>
      </tr>
      <tr>
        <td>
            <b>Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.</b>
        </td>
        <td>
            TB1<br><br>
            <b>Escalante Baygorrea, Janiel Franz</b><br>
            Para llevar acabo el desarrollo del LEAN UX y el diagrama UML estudie como funciona el sector de la seguridad ciudadana y como se puede aplicar la tecnología para mejorar la seguridad de los ciudadanos.
            <br><br>
            <b>Noriega Suschenko, Anatoly Andrey</b><br>
            Hice uso de lo aprendido dentro del curso de Aplicaciones Web y trabajos anteriores para identificar los problemas a resolver sobre nuestro trabajo. Asimismo, en base a lo aplicado como analizar 
            nuestro público objetivo, las estrategias frente a nuestros competidores, las entrevistas realizadas, y el diseño de los Wireframes y Mock-Ups junto con los UserFlows, Wireflows y el prototipo 
            de la plataforma web, nos sirvio para tener una idea más clara de como avanzar con el trabajo en cuestión.
            <br><br>          
            <b>Príncipe Godoy, Johan</b><br>
            Para el cumplimiento de este trabajo usé lo aprendido dentro del curso y proyectos antereriores. De esta manera pude cumplir con los puntos que me fueron asignado como Diagrama de Contexto, Contenedor y Componentes.
            <br><br>
            <b>Rodriguez Zuluoeta, Andres Fernando</b><br>
            Use el conocimiento previamente adquirido en trabajos anteriores para asi poder realizar el proyecto de este curso. Pude realizar con exito el diseño y posterior analisis de entrevistas,user personas, 
            user stories, impact mapping, product backlog y el software configuration management. 
            <br><br>
            <b>Zarate Caceres, Victor Ernesto</b><br>
            Se hizo uso del conocimiento previo adquirido en el desarrollo de aplicaciones web, aplicaciones de escritorio y trabajos anteriores. Este conocimiento se vio reflejado en identificar los problemas
            que deben ser resueltos mediante la recopilación de testimonios a través de entrevistas. Además, sirvio para identificar los colores más adecuados para que la plataforma se vea funcional y sea 
            atractiva al usuario.<br><br>
            TP<br><br>
            <b>Escalante Baygorrea, Janiel Franz</b><br>
            <br><br>
            <b>Noriega Suschenko, Anatoly Andrey</b><br>
            Hice uso de los nuevos conocimientos que aprendí en el curso junto con la retroalimentación dada por el profesor para corregir los errores del envío pasado. Esto me sirvió para seguir mejorando en el proyecto además que con lo aprendido en clase me sirvió para avanzar la Web Application.<br><br>          
            <b>Príncipe Godoy, Johan</b><br>
            <br><br>
            <b>Rodriguez Zuluoeta, Andres Fernando</b><br>
            <br><br>
            <b>Zarate Caceres, Victor Ernesto</b><br>
            Se utilzo lo aprendido durante el curso y de manera previa para corregir los errores existentes en nuestro informe y aplicaciones. Este conocimiento se vio reflejado dar un mejor diseño a las plataformas
            y en presentar un nuevo informe mejorado, más apegado a lo que se espera en el curso.
        </td>
        <td>
            TB1<br><br>
            Se aplicó toda la experiencia y conocimientos previos para abordar el trabajo de manera efectiva. Esto incluyó el análisis de problema, la identificación del público objetivo, y el diseño de la plataforma.<br><br>
            TP<br>
            <br><br>
        </td>
      </tr>
    </table>
</div>

# Capítulo I: Introducción
## 1.1. StartUp Profile
### 1.1.1. Description de la StartUp
<div align="justify">
    La idea de crear PeaceApp nace ante la creciente ola de inseguridad ciudadana en Lima, y en todo el país. Según el INEI, el 45,6% de ciudadanos de Lima se siente inseguros de vivir en 
    dicha ciudad, con un registro de mas de 75 mil denuncias por hurtos y/o asaltos. Para enfrentar esta situación, la aplicación brindara un mapa con información de las calles, resaltando 
    el nivel de peligro en las distintas zonas de la ciudad. Ante esto, el usuario podrá hacer denuncias ante los crímenes a través de fotos, audios y/o videos, en tiempo real, pudiendo 
    brindar sus datos o hacerlo de manera anónima. Además, el ciudadano podrá compartir su ubicación con sus contactos cercanos para que monitoreen su trayecto y enviar mensajes de emergencia
    a la policía nacional, bomberos o ambulancia, usando un sistema de marcación rápida.
    <ul>
        <li><b>Misión:</b></li>
        Nuestra misión es garantizar la seguridad de nuestros usuarios, para que puedan transitar sin miedo alguno por las distintas calles del Perú.
        <li><b>Visión:</b></li>
        Vemos el mundo en constante cambio y buscamos ser parte de ello. Creemos que todas las personas deben poder sentirse seguras de vivir y transitar en su propio país y que los gobiernos 
        deben engargarse de ello. Por ello, buscamos ser conocidos como líderes en el mercado de seguridad por nuestra labor para todos nuestros usuarios.
    </ul>
</div>

### 1.1.2. Perfiles de Integrantes del equipo
| Nombre Completo del integrante      | Descripcion de Carrera                                                                      | Fotografía                              | Conocimientos y Habilidades a apuntar                                                                                                                                                                                                                   |
|-------------------------------------|---------------------------------------------------------------------------------------------|-----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Escalante Baygorrea, Janiel Franz   | Ingenieria de Software <br>Universiad Peruana de Ciencias Aplicadas                         | ![Franz Escalante](/assets/Franz.jpeg)  | Conocimientos en lenguajes de Programación como C++, Java, HTML, CSS.<br>Me considero que soy una persona muy trabajadora.                                                                                                                              |
| Noriega Suschenko, Anatoly Andrey   | Ingeniería de Software<br> 5to Ciclo<br>2024-1<br>Universidad Peruana de Ciencias Aplicadas | ![Anatoly Noriega](/assets/Anatoly.png) | - Conocimientos en lenguajes de Programación como C++, Python, HTML, CSS.<br>-Considero que soy una persona muy perseverante y que sabe trabajar en equipo.                                                                                             |
| Príncipe Godoy, Johan               | Ingenieria de Software <br>Universiad Peruana de Ciencias Aplicadas                         | ![Johan Príncipe](/assets/Johan.jpg)    | - Conocimiento en lenguajes de programación como C++, Python, HTML, CSS, JS, SQL, MongoDB. <br> - Me considero una persona comprometida y perseverante para lograr lo mejor con el equipo.                                                              |
| Rodriguez Zuluoeta, Andres Fernando | Ingenieria de Software <br>Universiad Peruana de Ciencias Aplicadas                         | ![Andres Rodriguez](/assets/Andres.jpg) | Tengo conocimiento de lenguaje de programación como C ++ y Python. Me considero una persona centrada y responsable al momento de realizar trabajos en grupo.                                                                                            |
| Zarate Caceres, Victor Ernesto      | Ingeniería de Software<br>Universidad Peruana de Ciencias Aplicadas                         | ![Ernesto Zarate](/assets/ernesto.png)  | - Conocimiento de Programación en C++, Python, HTML, CSS, MAtLab y SQL.<br>-Me considero una persona responsable, capaz de aportar ideas para el proyecto.<br>-Tengo el compromiso de trabajar de manera eficiente y cumplir con los plazos de entrega. |

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
            <b>Where (Dónde): </b>PeaceApp esta hecha para ser utilizada en cualquier momento y lugar, pues funcionara en base a la ubicación del usuario. Además de que las distintas autoridades
            deben estar al tanto de la situación actual de su jurisdicción.
        </li>
        <li>
            <b>Who (Quién): </b>Los personas más afectadas por la delincuencia veran mejoras en la situación de sus distritos. Estos, a su vez, tendrán la capacidad de colaborar con mantener la
            información actualizada, por medio de una herramienta integrada, que les permitirá publicar sobre los distintos sucesos que observan y ponerse en contacto rápidamente con las 
            autoridades con las cuales se relaciona PeaceAppp (comisarías, bomberos, hospitales, municipalidades, etc.).
        </li>
        <li>
            <b>Why (Por qué): </b>PeaceApp fue creada para enfrentar la creciente delincuencia en la ciudad de Lima y en todo el país. Esta tiene el objetivo de informar sobre los sucesos más 
            recientes del entorno del usuario y ayudar a otros usuarios y a las municipalidades a prevenir estas situaciones en el futuro.
        </li>
        <li>
            <b>How (Cómo): </b>PeaceApp tiene un personal altamente capacitado para mantener actualizada y funcional la base de datos de los distritos y ciudades en todo el Perú, para mantener
            a nuestros usuarios con la información actualizada sobre las calles que transitará. Además, se podrá compartir información con otros usuarios y autoridades para tomar las medidas
            correspondientes y que verifiquen la veracidad de todo lo que se publique. 
        </li>
        <li>
            <b>How Much (Cuánto):</b>PeaceApp estara disponible de forma gratuita para todas las personas naturales. Además, tendrá disponible una licencia de uso para las entidades, como 
            municipalidades. Así, estas tendrán un acceso preferencial a los datos recopilados y puedan utilzarlos para tomar acción directa en contra de la delincuencia. 
        </li>
    </ul>
</div>  

### 1.2.2	Lean UX   

#### 1.2.2.1. Problem Statements
El propósito de nuestro servicio es ofrecer rutas seguras, diseñadas en base a la ubicación de partida y la de llegada del usuario. A través de nuestro servicio, los usuarios
tienen acceso a un mapa de calor de la peligrosidad de las zonas de lima. Las actualizaciones de las zonas de peligrosidad  se haran en base a reportes de los usuarios de
la aplicación. Por otro lado, las entidades que trabajen con nosotros podrán tener acceso a esta información y sus respectivos datos estadísticos. Estos datos pueden ser
usados para plantear una estrategía contra la delincuencia.

Hemos observado la insatisfacción de los clientes con respecto a la seguridad. Actualmente, los hurtos en la calle son comunes en la ciudad de Lima. Según Osiptel, la mayor
cantidad de robos de celulares por hora se reportan los lunes, esto sería aproximadamente 366 equipos móviles en promedio. Por otro lado, Según el último resultado
de la ENAPRES para el semestre móvil Ene-Jun 2023 publicado por el INEI, el 26.9% de la población de 15 años de edad, a más, a nivel nacional, ha sido victima de algún
hecho delictivo.


¿De qué forma podemos evitar los hurtos en la calle cuando se encuentran recorriendo una ruta?

#### 	 1.2.2.2. UX Assumptions

Ahora que hemos analizado la problematica y tenemos un panorama de cómo solucionar el problema, debemos saber que empresas tienen características similares a las nuestras
y cómo estas se han ido desarrollando a través del tiempo.
La aplicación UrSafe es similar a la nuestra, esta aplicación permite ver un mapa con lugares seguros y te permite comunicarte con familiares, amigos y el 911 en caso de
peligro.


**Assumptions:**
+ Los ciudadanos de Lima necesitan una app que les muestre rutas seguras para movilizarse a tráves de la ciudad de Lima
+ Los ciudadanos necesitan sentirse parte de una comunidad en la que se puedan reportar incidentes y verlo reflejado en un mapa que les permite visualizar las zonas más
  seguras de su ciudad.
+ Mis clientes serán ciudadanos y entidades preocupadas por la seguridad de su distrito o trabajadores
+ Generaré ingresos vendiendo nuestra aplicación web a municipalidades, instituciones del estado e interesedos en el tema de la seguridad
+ No tengo ningún competidor en el mercado actualmente
+ Las entidades que trabajen con nuestra aplicación podrán obtener datos de vital importancia para combatir la criminalidad
+ Los ciudadanos de a pie estarán interesados en esta aplicación
+ Las entidades públicas de este país necesitan este tipo de aplicaciones para combatir la criminalidad con más eficacia.

**Business outcomes:**

+ Generar ingresos con la aplicación
+ Mejorar la calidad de la vida de los ciudadanos del Perú
+ Reducir la cantidad de robos que ocurren en el país

**User outcomes:**
+ ¿Quién es el usuario?   
  Cualquier ciudadano que se encuentre en una zona en la que una entidad este asociada con nosotros. Por otro lado, las entidades públicas
  como municipalidades, PNP, etc. También empresas privadas interesadas en contar con esta aplicación para sus trabajadores, de preferencia
  extranjeros que no conocen bien las calles de la ciudad.
+ ¿Dónde encaja nuestro producto en su trabajo o vida?  
  Encaja en su vida diaria, ya que con nuestra aplicación podrá movilizarse por la ciudad evitando riesgos
+ ¿Qué problemas tiene nuestro producto?  
  Un problema que tiene nuestro producto es que para geenera ingresos, dependemos exclusivamente de las entidades que se van a asociar con nosotros
+ ¿Cuándo y cómo es usado nuestro producto?  
  Nuestros usuarios utilizarían la aplicación cuando tengan que pasar por lugares que no conocen o deseen reportar un incidente para que otros ciudadanos tengan cuidado.
  Por otro lado, las entidades podrán recopilar información de los ciudadanos y esto les facilitará tomar acciones para combatir la criminalidad en ciertas areas.

+ ¿Qué características son importantes?  
  Sera una aplicación sencilla de usar para los usuarios y que las información se accesible de una manera sencilla.

+ ¿Cómo debe verse nuestro producto y comportarse?  
  Nuestra app debe tener una buena selección de colores para que sea agradable a la vista. Además el registro debe ser fácil para todos los usuarios.

**User benefits**
+ Evitar robos y cualquier tipo de incidentes que ponga en peligro al usuario al movilizarse por la ciudad
+ Información en tiempo real de zonas peligrosas mediante el uso del mapa de calor
+ Información de rutas seguras para movilizarse mediante el mapa
+ Acceso a datos estadísticos para comprender mejor el problema


#### 	1.2.2.3. Lean UX Hypothesis Statements
+ **Hypothesis Statement 01**   
  **Creemos que** las entidades publicas y privadas estarán interesadas en nuestro producto  
  **Sabremos que** hemos tenido éxito  
  **Cuando** podamos trabajar con un mapa de calor de toda la ciudad de Lima
+ **Hypothesis Statement 02**    
  **Creemos que** la aplicación logrará formar una comunidad interesada en la seguridad  
  **Sabremos que** hemos tenido exito  
  **Cuando** tengamos se perciba un aumento en la cantidad de usuarios registrados diariamente.
+ **Hypothesis Statement 03**  
  **Creemos que** la disponibilidad de datos de vital importancia permitarán a distintas entidades planificar una estrategia contra la delincuencia  
  **Sabremos que** se está cumpliendo ese objetivo  
  **Cuando** se perciba una disminución en los reportes de criminalidad sin que se reduzca la cantidad de usuarios
+ **Hypothesis Statement 04**  
  **Creemos que** nuestra aplicación será usada a nivel nacional    
  **Sabremos que** hemos tenido exito  
  **Cuando** la aplicación sea adquirida por la mayoria de las entidades de distintas ciudades del Perú
#### 	1.2.2.4. Lean UX Canvas
A continuación se puede ver el Lean UX Canvas trabajado por el equipo:
![Imagen de Lean-UX Canvas](https://i.postimg.cc/QdBzp4FY/Lean-UX-Canvas-Template.jpg)
Enlace para acceder a Miro: https://miro.com/app/board/uXjVKZpPpnQ=/?share_link_id=692620192853
## 1.3. Segmentos objetivo
### Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos
En muchos centros urbanos, la seguridad pública sigue siendo una preocupación mayor para los ciudadanos que buscan maneras efectivas de protegerse en su día a día. Aplicaciones como PeaceApp podrían ofrecer soluciones prácticas para estos desafíos. Según un estudio del Banco Mundial sobre seguridad urbana, la implementación de tecnologías que aumentan la percepción y la realidad de la seguridad puede tener impactos significativos en la reducción del crimen y la mejora de la calidad de vida urbana (Banco Mundial, 2017).

### Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana
Las entidades gubernamentales, desde la policía local hasta los planificadores urbanos, enfrentan retos constantes para mejorar la eficiencia de sus respuestas y estrategias de prevención del crimen. Según la Organización de las Naciones Unidas, el acceso a datos precisos y actualizados es crucial para la planificación efectiva de la seguridad y el desarrollo urbano (Naciones Unidas, 2019). Herramientas como PeaceApp, que proporcionan datos en tiempo real y facilitan la comunicación entre ciudadanos y autoridades, son esenciales para desarrollar respuestas más rápidas y fundadas a los problemas de seguridad pública.
