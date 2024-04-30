# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

<div style="text-align: justify">
El "To-be Scenario Map" representa la visión de la experiencia del usuario una vez que se han implementado las soluciones o mejoras planificadas. 
Este mapa proporciona una representación visual de cómo queremos que sea la experiencia del usuario en el futuro, destacando las actividades que realizarán, 
los pensamientos que tendrán y los sentimientos que experimentarán en cada fase del proceso. Al visualizar el futuro deseado, el "To-be Scenario Map" nos ayuda a 
alinear al equipo en torno a una visión compartida y a identificar las áreas en las que necesitamos enfocarnos para lograr esa experiencia mejorada para el usuario.
</div>

**Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos**

<img src="/assets/To-Be_Segmento1.jpg" alt="To-Be Scenario Map User Persona 1" width="80%">

**Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana**

<img src="/assets/To-Be_Segmento2.jpg" alt="To-Be Scenario Map User Persona 2" width="80%">

## 3.2. User Stories
| Epic Story ID | Título| Descripción | Criterios de aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| EP01| Diseño y Desarrollo de la Landing Page| Como visitante de la Landing Page, quiero encontrar una landing page bien diseñada y fácil de usar que me proporcione información clara y concisa sobre la aplicación, para poder entender el propósito de la aplicación.| No corresponde| No corresponde|
| EP02| Seguridad en el desplazamiento| Como visitante de la landing page quiero que me recomieden la ruta mas segura para asi poder tener un viaje sin preocupaciones.| No corresponde| No corresponde|
| EP03| Gestion de seguridad | Como usuario de la municipalidad quiero poder ver todos los reportes hechos por los ciudadanos para asi poder tener mayor informacion sobre los lugares con mayor delincuencia.| No corresponde          | No corresponde |
| EP04| Servicios de la Aplicación| Como visitante de la Landing Page, quiero encontrar los servicios que ofrece la aplicación, para poder comprender como PeaceApp puede satisfacer mis necesiades de seguridad y bienestar. | No corresponde| No corresponde|
| EP05| Sistema de notificaciones| Como usuario de PeaceApp, quiero recibir notificaciones en tiempo real sobre incidentes de seguridad en mi área, para estar siempre informado y tomar precauciones.| No corresponde|No corresponde|
| EP06| Perfiles de usuario| Como usuario de PeaceApp, quiero poder crear y personalizar mi perfil de usuario, para tener una identidad dentro de la comunidad de la aplicación.| No corresponde| No corresponde |

<table>
    <tr>
        <td align="center">User Story ID</td>
        <td align="center">Título</td>
        <td align="center">Descripción</td>
        <td align="center">Criterios de Aceptación</td>
        <td align="center">Relacionado con (Epic ID)</td>
    </tr>
    <tr>
        <td align="center">US01</td>
        <td align="justify">Planificación de rutas seguras</td>
        <td align="justify">Como transeúnte, quiero recibir actualizaciones en tiempo real sobre las zonas de peligrosidad en mi ruta.</td>
        <td align="justify">
            Escenario: Un transeúnte está planeando su ruta y quiere recibir actualizaciones en tiempo real sobre las zonas peligrosas.<br>
            Given el transeúnte ha iniciado la aplicación<br>
            And ha ingresado su ruta.<br>
            When la aplicación detecta cambios en la peligrosidad de las zonas en la ruta del transeúnte.<br>
            Then la aplicación actualiza la información de peligrosidad en tiempo real y la muestra al transeúnte.
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US02</td>
        <td align="justify">Actualizaciones en tiempo real</td>
        <td align="justify">Como transeúnte, quiero que la aplicación me sugiera la ruta más segura para llegar a mi destino.</td>
        <td align="justify">
            Escenario: Un transeúnte quiere que la aplicación le sugiera la ruta más segura para llegar a su destino.<br>
            Given el transeúnte ha ingresado su destino en la aplicación.<br>
            When la aplicación ha calculado todas las rutas posibles.<br>
            Then la aplicación sugiere la ruta más segura basada en la información de peligrosidad actual.
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US03</td>
        <td align="justify">Personalización de rutas</td>
        <td align="justify">Como transeúnte, quiero poder personalizar mis rutas en función de mis preferencias de seguridad.</td>
        <td align="justify">
            Escenario: Un transeúnte quiere personalizar su ruta en función de sus preferencias de seguridad.<br>
            Given el transeúnte ha ingresado su ruta y ha accedido a las opciones de personalización.<br>
            When el transeúnte ajusta sus preferencias de seguridad.<br>
            Then la aplicación personaliza la ruta del transeúnte en función de sus preferencias.
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US04</td>
        <td align="justify">Reporte de incidentes</td>
        <td align="justify">Como transeúnte, quiero poder reportar incidentes de seguridad a través de la aplicación.</td>
        <td align="justify">
            Escenario: Un transeúnte quiere reportar un incidente de seguridad a través de la aplicación.<br>
            Given el transeúnte ha presenciado un incidente de seguridad.<br>
            When el transeúnte ingresa los detalles del incidente en la aplicación.<br>
            Then la aplicación registra el incidente y actualiza la información de peligrosidad de la zona correspondiente.
        </td>
        <td align="center">EP05</td>
    </tr>
    <tr>
        <td align="center">US05</td>
        <td align="justify">Alertas de Zonas de Riesgo</td>
        <td align="justify">Como usuario, quiero recibir alertas si me acerco a una zona de alto riesgo.</td>
        <td align="justify">
            Escenario: Un usuario recibe una alerta cuando se acerca a una zona de alto riesgo.<br>
            Given el usuario está utilizando la aplicación mientras se desplaza.<br>
            When la aplicación detecta que el usuario se está acercando a una zona de alto riesgo.<br>
            Then la aplicación envía una alerta al usuario.
        </td>
        <td align="center">EP05</td>
    </tr>
    <tr>
        <td align="center">US06</td>
        <td align="justify">Visualización de reportes</td>
        <td align="justify">Como transeúnte, quiero poder ver los reportes de otros usuarios en el mapa de calor de peligrosidad.</td>
        <td align="justify">
            Escenario: Un transeúnte quiere ver los reportes de otros usuarios en el mapa de calor de peligrosidad.<br>
            Given el transeúnte ha abierto el mapa de calor de peligrosidad en la aplicación.<br>
            When hay reportes de otros usuarios disponibles para la zona que está viendo el transeúnte.<br>
            Then la aplicación muestra los reportes de otros usuarios en el mapa de calor.
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US07</td>
        <td align="justify">Acceso a reportes</td>
        <td align="justify">Como comisario, quiero tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.</td>
        <td align="justify">
            Escenario: Un comisario quiere tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.<br>
            Given el comisario ha iniciado sesión en la aplicación con su cuenta de comisario.<br>
            When el comisario accede a la sección de reportes de la aplicación.<br>
            Then la aplicación muestra al comisario los reportes de los usuarios.
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US08</td>
        <td align="justify">Análisis de datos</td>
        <td align="justify">Como comisario, quiero poder analizar los datos recopilados para identificar patrones y tendencias.</td>
        <td align="justify">
            Escenario: Un comisario quiere analizar los datos recopilados para identificar patrones y tendencias.<br>
            Given el comisario tiene acceso a los datos recopilados por la aplicación.<br>
            When el comisario utiliza las herramientas de análisis de datos de la aplicación.<br>
            Then la aplicación proporciona al comisario los resultados del análisis de datos.
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US09</td>
        <td align="justify">Planificación de estrategias</td>
        <td align="justify">Como comisario, quiero utilizar la información recopilada para planificar estrategias contra la delincuencia.</td>
        <td align="justify">
            Escenario: Un comisario quiere utilizar la información recopilada para planificar estrategias contra la delincuencia.<br>
            Given el comisario ha analizado los datos recopilados y ha identificado áreas problemáticas.<br>
            When el comisario utiliza la información recopilada para planificar estrategias.<br>
            Then la aplicación registra las estrategias del comisario y las asocia con las áreas problemáticas correspondientes.
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US10</td>
        <td align="justify">Priorización de reportes</td>
        <td align="justify">Como comisario, quiero poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.</td>
        <td align="justify">
            Escenario: Un comisario quiere poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.<br>
            Given el comisario tiene acceso a los reportes de los usuarios.<br>
            When el comisario clasifica los reportes en función de su gravedad y urgencia.<br>
            Then la aplicación prioriza los reportes según la clasificación del comisario.
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US11</td>
        <td align="justify">Comunicación con entidades asociadas</td>
        <td align="justify">Como comisario, quiero poder compartir información relevante con otras entidades de seguridad para coordinar esfuerzos.</td>
        <td align="justify">
            Escenario: Un comisario quiere compartir información relevante con otras entidades de seguridad para coordinar esfuerzos.<br>
            Given el comisario ha identificado información relevante que desea compartir.<br>
            When el comisario utiliza la función de compartir de la aplicación.<br>
            Then la aplicación comparte la información seleccionada con las entidades de seguridad seleccionadas por el comisario.
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US12</td>
        <td align="justify">Visualización de Rutas Seguras</td>
        <td align="justify">Como comisario, quiero poder ver las rutas seguras más utilizadas por los usuarios para entender mejor sus patrones de desplazamiento.</td>
        <td align="justify">
            Escenario: Un comisario quiere ver las rutas seguras más utilizadas por los usuarios para entender mejor sus patrones de desplazamiento.<br>
            Given el comisario ha accedido a la sección de rutas seguras de la aplicación.<br>
            When hay datos disponibles sobre las rutas seguras más utilizadas por los usuarios.<br>
            Then la aplicación muestra al comisario las rutas seguras más utilizadas.
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US13</td>
        <td align="justify">Añadir foto de perfil</td>
        <td align="justify">Como usuario, quiero poder añadir una foto de perfil.</td>
        <td align="justify">
            Escenario:<br>
            Given que el usuario está en su perfil,<br>
            When el usuario selecciona la opción para añadir una foto de perfil,<br>
            Then se debe abrir un cuadro de diálogo que permita al usuario seleccionar una foto de su dispositivo,<br>
            And cuando el usuario selecciona una foto y confirma la acción, la foto de perfil del usuario debe actualizarse con la foto seleccionada.
        </td>
        <td align="center">EP06</td>
    </tr>
    <tr>
        <td align="center">US14</td>
        <td align="justify">Recibir notificaciones sobre zona peligrosa</td>
        <td align="justify">Como usuario, quiero recibir notificaciones cuando me este acercando a una zona peligrosa</td>
        <td align="justify">
            Escenario:<br>
            Given que el usuario ha activado las notificaciones de zonas peligrosas en la configuración de la aplicación,<br>
            When el usuario se acerca a una zona marcada como peligrosa,<br>
            Then el usuario debe recibir una notificación alertándole de la proximidad a la zona peligrosa.
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US15</td>
        <td align="justify">Ver reportes</td>
        <td align="justify">Como usuario, quiero poder ver los reportes de otros usuarios en las denuncias.</td>
        <td align="justify">
            Escenario:<br>
            Given que el usuario está viendo una denuncia,<br>
            When el usuario selecciona la opción para ver los reportes de otros usuarios,<br>
            Then se debe mostrar una lista de reportes con las calificaciones y comentarios de otros usuarios.
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US16</td>
        <td align="justify">Editar información de perfil</td>
        <td align="justify">Como usuario, quiero poder editar mi información de perfil.</td>
        <td align="justify">
            Escenario:<br>
            Given que el usuario está en su perfil,<br>
            When el usuario selecciona la opción para editar su información de perfil,<br>
            Then se debe abrir una página o un cuadro de diálogo que permita al usuario editar su información de perfil,<br>
            And cuando el usuario realiza los cambios y confirma la acción, la información de perfil del usuario debe actualizarse con la nueva información.
        </td>
        <td align="center">EP06</td>
    </tr>
    <tr>
        <td align="center">US17</td>
        <td align="justify">Ver denuncias más recientes</td>
        <td align="justify">Como usuario, quiero poder ver las denuncias más recientes en mi área.</td>
        <td align="justify">
            Escenario:<br>
            Given que el usuario está en la página principal de la aplicación,<br>
            When el usuario selecciona la opción para ver las denuncias más recientes,<br>
            Then se debe mostrar una lista de las denuncias más recientes en su área.
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US18</td>
        <td align="justify">Mapa de calor</td>
        <td align="justify">Como usuario, quiero poder ver un mapa de calor sobre los niveles de peligro</td>
        <td align="justify">
            Escenario:<br>
            Given que el usuario está en la página principal de la aplicación,<br>
            When el usuario selecciona el mapa de calor,<br>
            Then se debe mostrar el mapa de calor señalando las zonas peligrosas y/o seguras
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US19</td>
        <td align="justify">Optimización de la Experiencia del Usuario</td>
        <td align="justify">Como visitante de la Landing Page, quiero encontrar una landing page responsive</td>
        <td align="justify">
            Escenario:<br>
            Given que el usuario ingresa a la landing page,<br>
            When desee, donde desee y desde cualquier dispositivo,<br>
            Then disfruta una experiencia fluida desde.
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US20</td>
        <td align="justify">Desarrollo de Secciones Clave de la Landing Page</td>
        <td align="justify">Como visitante de la Landing Page, quiero encontrar información clara y atractiva.</td>
        <td align="justify">
            Escenario:<br>
            Given que la Landing Page funciona<br>
            When esta recibe un visitante<br>
            Then cada sección de la landing page de la aplicación, permite ser comprendida con facilidad y motiva su uso.
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US21</td>
        <td align="justify">Implementación de Formularios de Contacto</td>
        <td align="justify">Como visitante de la Landing Page, deseo encontrar formularios de contacto funcionales y accesibles</td>
        <td align="justify">
            Escenario:<br>
            Given un usuario que visita la landing Page<br>
            When tiene preguntas o preocupaciones<br>
            Then la landing page de la aplicación ofrece un medio de comunicación efectiva con el equipo de desarrollo de PeaceApp.
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US22</td>
        <td align="justify">Compartir ubicación</td>
        <td align="justify">Como usuario de PeaceApp, quiero poder compartir mi ubicación con mis contactos cercanos.</td>
        <td align="justify"> 
            Escenario:<br>
            Given un usuario que comparte su ubicación con sus contactos cercanos<br>
            When se desplaza por las distintas zonas de la ciudad<br>
            Then podrán monitorear su trayecto y saber si estoy seguro.
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US23</td>
        <td align="justify">Testimonios de Usuarios</td>
        <td align="justify">Como visitante de la Landing Page, quiero encontrar las opiniones de los diferentes usuarios que han probado la aplicación. </td>
        <td align="justify">
            Escenario:<br>
            Given un usuario que visita la Landing Page<br>
            When tiene curiosidad por la eficiencia de la aplicación<br>
            Then podrá ver opiniones de otros usuarios<br>
            And tener una idea clara de su experiencia y satisfacción con PeaceApp
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
		<td align="center">TS01</td>
        <td align="justify">Integración del mapa interactivo</td>
        <td align="justify">Como desarrollador quiero implementar un mapa interactivo para ser el eje de funcionamiento.</td>
        <td align="justify">
	        Escenario:
	        Given que se desea desplegar un mapa de calor<br>
	        When el usuario cargue la página<br>
	        Then debería usar una API de mapas para hacerlo posible. 
	    </td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS02</td>
        <td align="justify">GET and POST de reportes de seguridad</td>
        <td align="justify">Como desarrollador quiero habilitar la creación y retorno de reportes de incidentes de seguridad para la seguridad de los usuarios.</td>
        <td align="justify">
            Escenario 1: Crear un nuevo reporte de seguridad<br>
            Given que el usuario está en la página de reportes<br>
            When el usuario completa el formulario con los detalles del incidente<br>
            And el usuario envía el reporte<br>
            Then debería ver un mensaje de confirmación y el reporte debería almacenarse en la API y aparecer en la lista de reportes<br><br>
            Escenario 2: Ver detalles de un reporte existente
            Given que el usuario está en la página de reportes<br>
            When el usuario selecciona un reporte de la lista<br>
            Then la aplicación hace el GET con la API<br>
            And debería ver los detalles completos del reporte
        </td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS03</td>
        <td align="justify">GET and POST User</td>
        <td align="justify">Como desarrollador quiero registrar los datos de nuevos usuario mediantes una API para obtener a los que se encuentran afiliados.</td>
        <td align="justify">
	        Escenario 1: Usuario se registra en la página web<br>
	        Given que tengo acceso a la API de registro de usuarios<br>
	        When se envía una solicitud con datos válidos de un nuevo usuario<br>
	        Then el usuario se registra exitosamente y se envía una confirmación. <br><br>
	        Escenario 2: Usuario ingresa a la página web<br>
	        Given que el usuario accede a la página de inicio de sesión<br>
	        When hace clic en el botón de iniciar sesión<br>
	        Then los datos ingresados se comparan con los de la API<br>
	        And se autoriza el ingreso de ser al caso.
		</td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS04</td>
        <td align="justify">Implementación de medidas de seguridad</td>
        <td align="justify">Como desarrollador quiero incorporar medidas de seguridad robustas para proteger la información sensible de los usuarios y garantizar la integridad del sistema.</td>
        <td align="justify">
	        Escenario: Encriptación de datos de usuario<br>
	        Given que un usuario se registra en la plataforma<br>
	        When se ingresan los datos personales<br>
	        Then los datos de usuario se almacenan en la base de datos de forma encriptada<br>
	        And el usuario puede iniciar sesión utilizando su contraseña encriptada
        </td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS05</td>
        <td align="justify">Pruebas y depuración</td>
        <td align="justify">Como desarrollador quiero realizar pruebas exhaustivas para identificar y corregir los errores o fallos de todas las funcionalidades implementadas.</td>
        <td align="justify">
	        Escenario 1: Pruebas de funcionamiento de todas las funcionalidades<br>
	        Given la implementación de todas las funcionalidades de la página web<br>
	        When se realizan pruebas exhaustivas para verificar el correcto funcionamiento<br>
	        Then se verifican los datos almacenados en la API<br>
	        And que las medidas de seguridad funcionen correctamente.<br><br>
	        Escenario 2: Corrección de errores identificados en las pruebas<br>
	        Given errores o fallos de funcionamiento en la página web<br>
	        When se identifica la causa de los errores<br>
	        Then se implementan las correcciones necesarias<br>
	        And se realizan más pruebas para verificar que se corrigieron los errores.
	    </td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS06</td>
        <td align="justify">Mantenimiento y actualizaciones</td>
        <td align="justify">Como desarrollador quiero establecer un plan de mantenimiento continuo para realizar actualizaciones periódicas y agregar nuevas funcionalidades según sea necesario.</td>
        <td align="justify">
	        Escenario: Actualización del sistema<br>
	        Given que se han creado nuevas funcionalidadas<br>
	        When los administradores inician sesión en el panel de administración<br>
	        Then la actualización del sistema se despliega correctamente<br>
	        And está disponible para los usuarios.
	    </td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS07</td>
        <td align="justify">GET and POST comentarios y valoraciones</td>
        <td align="justify">Como desarrollador quiero Implementar un sistema de comentarios y valoraciones para que los usuarios puedan compartir sus experiencias</td>
        <td align="justify">
	        Escenario 1: Un usuario puede agregar un comentario<br>
	        Given el usuario está en la página del mapa<br>
	        When el usuario selecciona un área específica en el mapa<br>
	        Then escribe un comentario sobre el área<br>
	        And se almacena el comentario en la sección de comentarios de la API<br><br>
	        Escenario 2: Un usuario puede ver un comentario
	        Given el usuario está en la página del mapa<br>
	        When el usuario selecciona un área específica en el mapa<br>
	        Then se hace el llamdo a la sección de comentarios de la API<br>
	        And el usuario pueder ver los comentarios.
	     </td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS08</td>
        <td align="justify">Establecer un canal de comunicación directa entre los usuarios y las autoridades </td>
        <td align="justify">Como desarrollador quiero establecer un canal de comunicación directa entre los usuarios y las autoridades para que se envíen alertas o se solicite asistencia en tiempo real.</td>
        <td align="justify">
	        Escenario 1: Un usuario puede enviar una alerta a las autoridades<br>
	        Given el usuario experimenta una mala experiencia<br>
	        When se selecciona la opción de enviar una alerta a las autoridades<br>
	        And proporciona detalles sobre la situación y ubicación<br>
	        And presiona el botón de enviar alerta<br>
	        Then se envía una alerta a las autoridades de seguridad<br><br>
	        Escenario 2: Un usuario puede solicitar asistencia en tiempo real<br>
	        Given se requiere asistencia inmediata<br>
	        When el usuario selecciona la opción adecuada<br>
	        And especifica el tipo de ayuda que necesita<br>
	        Then se obtiene la ubicación en tiempo real<br>
	        And se envía la solicitud
        </td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS09</td>
        <td align="justify">Optimización del rendimiento</td>
        <td align="justify">Como desarrollador quiero mejorar el rendimiento de la página web para garantizar una experiencia fluida para los usuarios.</td>
        <td align="justify">
	        Escenario 1: Carga rápida de la página principal<br>
	        Given que el usuario accede a la página principal<br>
	        When la página se carga completamente<br>
	        Then la página se muestra en menos de 3 segundos<br>
	        And todos los elementos son visibles y funcionales<br><br>
	        Escenario 2: Optimización de recursos estáticos<br>
	        Given el tamaño total de los recursos descargados es mínimo<br>
	        When el usuario ingresa a la página<br>
	        Then los recursos estáticos se cargan de manera eficiente y rápida<br>
	        And la página carga con rapidez y fluidez.
        </td>
        <td align="center">-</td>
	</tr>
</table>

## 3.3. Impact Mapping
<img src="../../assets/Impact_mapping.png" alt="Impact map">

## 3.4. Product Backlog
|#Orden| ID | User Story | Story Points |
|:-----|:---|:----------|:--------------|
|  01  |US20|Desarrollo de Secciones Clave de la Landing Page|3|
|  02  |US19|Optimización de la Experiencia del Usuario|5|
|  03  |US22|Compartir ubicación|8|
|  04  |US02|Actualizaciones en tiempo real|8|
|  05  |US18|Mapa de calor|8|
|  06  |US01|Planificación de rutas seguras|8|
|  07|US03|Personalización de rutas|3|
|  08|US12|Visualización de Rutas Seguras|3|
|  09|US04|Reporte de incidentes|8|
|  10|US05|Alertas de Zonas de Riesgo|5|
|  11|US06|Visualización de reportes|8|
|  12|US07|Acceso a reportes|8|
|  13|US08|Análisis de datos|8|
|  14|US09|Planificación de estrategias|5|
|  15|US10|Priorización de reportes|3|
|  16|US11|Comunicación con entidades asociadas|5|
|  17|US13|Añadir foto de perfil|2|
|  18|US14|Recibir notificaciones sobre zona peligrosa|5|
|  19|US15|Ver reportes|3|
|  20|US16|Editar información de perfil|3|
|  21|US17|Ver denuncias más recientes|5|
|  22|US21|Implementación de Formularios de Contacto|4|
|  23|US23|Testimonios de Usuarios|3|
