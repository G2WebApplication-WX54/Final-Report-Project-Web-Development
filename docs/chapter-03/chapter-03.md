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
        <td align="justify">Escenario: Un transeúnte está planeando su ruta y quiere recibir actualizaciones en tiempo real sobre las zonas peligrosas.<br>
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
        <td align="justify">Escenario: Un transeúnte quiere que la aplicación le sugiera la ruta más segura para llegar a su destino.<br>
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
        <td align="justify">Escenario: Un transeúnte quiere personalizar su ruta en función de sus preferencias de seguridad.<br>
            Given el transeúnte ha ingresado su ruta y ha accedido a las opciones de personalización.<br>
            When el transeúnte ajusta sus preferencias de seguridad.<br>
            Then la aplicación personaliza la ruta del transeúnte en función de sus preferencias.<br>
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US04</td>
        <td align="justify">Reporte de incidentes</td>
        <td align="justify">Como transeúnte, quiero poder reportar incidentes de seguridad a través de la aplicación.</td>
        <td align="justify">Escenario: Un transeúnte quiere reportar un incidente de seguridad a través de la aplicación.<br>
            Given el transeúnte ha presenciado un incidente de seguridad.<br>
            When el transeúnte ingresa los detalles del incidente en la aplicación.<br>
            Then la aplicación registra el incidente y actualiza la información de peligrosidad de la zona correspondiente.<br>
        </td>
        <td align="center">EP05</td>
    </tr>
    <tr>
        <td align="center">US05</td>
        <td align="justify">Alertas de Zonas de Riesgo</td>
        <td align="justify">Como usuario, quiero recibir alertas si me acerco a una zona de alto riesgo.</td>
        <td align="justify">Escenario: Un usuario recibe una alerta cuando se acerca a una zona de alto riesgo.<br>
            Given el usuario está utilizando la aplicación mientras se desplaza.<br>
            When la aplicación detecta que el usuario se está acercando a una zona de alto riesgo.<br>
            Then la aplicación envía una alerta al usuario.<br>
        </td>
        <td align="center">EP05</td>
    </tr>
    <tr>
        <td align="center">US06</td>
        <td align="justify">Visualización de reportes</td>
        <td align="justify">Como transeúnte, quiero poder ver los reportes de otros usuarios en el mapa de calor de peligrosidad.</td>
        <td align="justify">Escenario: Un transeúnte quiere ver los reportes de otros usuarios en el mapa de calor de peligrosidad.<br>
            Given el transeúnte ha abierto el mapa de calor de peligrosidad en la aplicación.<br>
            When hay reportes de otros usuarios disponibles para la zona que está viendo el transeúnte.<br>
            Then la aplicación muestra los reportes de otros usuarios en el mapa de calor.<br>
        </td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US07</td>
        <td align="justify">Acceso a reportes</td>
        <td align="justify">Como comisario, quiero tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.</td>
        <td align="justify">Escenario: Un comisario quiere tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.<br>
            Given el comisario ha iniciado sesión en la aplicación con su cuenta de comisario.<br>
            When el comisario accede a la sección de reportes de la aplicación.<br>
            Then la aplicación muestra al comisario los reportes de los usuarios.<br>
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US08</td>
        <td align="justify">Análisis de datos</td>
        <td align="justify">Como comisario, quiero poder analizar los datos recopilados para identificar patrones y tendencias.</td>
        <td align="justify">Escenario: Un comisario quiere analizar los datos recopilados para identificar patrones y tendencias.<br>
            Given el comisario tiene acceso a los datos recopilados por la aplicación.<br>
            When el comisario utiliza las herramientas de análisis de datos de la aplicación.<br>
            Then la aplicación proporciona al comisario los resultados del análisis de datos.<br>
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US09</td>
        <td align="justify">Planificación de estrategias</td>
        <td align="justify">Como comisario, quiero utilizar la información recopilada para planificar estrategias contra la delincuencia.</td>
        <td align="justify">Escenario: Un comisario quiere utilizar la información recopilada para planificar estrategias contra la delincuencia.<br>
            Given el comisario ha analizado los datos recopilados y ha identificado áreas problemáticas.<br>
            When el comisario utiliza la información recopilada para planificar estrategias.<br>
            Then la aplicación registra las estrategias del comisario y las asocia con las áreas problemáticas correspondientes.<br>
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US10</td>
        <td align="justify">Priorización de reportes</td>
        <td align="justify">Como comisario, quiero poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.</td>
        <td align="justify">Escenario: Un comisario quiere poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.<br>
            Given el comisario tiene acceso a los reportes de los usuarios.<br>
            When el comisario clasifica los reportes en función de su gravedad y urgencia.<br>
            Then la aplicación prioriza los reportes según la clasificación del comisario.<br>
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US11</td>
        <td align="justify">Comunicación con entidades asociadas</td>
        <td align="justify">Como comisario, quiero poder compartir información relevante con otras entidades de seguridad para coordinar esfuerzos.</td>
        <td align="justify">Escenario: Un comisario quiere compartir información relevante con otras entidades de seguridad para coordinar esfuerzos.<br>
            Given el comisario ha identificado información relevante que desea compartir.<br>
            When el comisario utiliza la función de compartir de la aplicación.<br>
            Then la aplicación comparte la información seleccionada con las entidades de seguridad seleccionadas por el comisario.<br>
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US12</td>
        <td align="justify">Visualización de Rutas Seguras</td>
        <td align="justify">Como comisario, quiero poder ver las rutas seguras más utilizadas por los usuarios para entender mejor sus patrones de desplazamiento.</td>
        <td align="justify">Escenario: Un comisario quiere ver las rutas seguras más utilizadas por los usuarios para entender mejor sus patrones de desplazamiento.<br>
            Given el comisario ha accedido a la sección de rutas seguras de la aplicación.<br>
            When hay datos disponibles sobre las rutas seguras más utilizadas por los usuarios.<br>
            Then la aplicación muestra al comisario las rutas seguras más utilizadas.<br>
        </td>
        <td align="center">EP03</td>
    </tr>
    <tr>
        <td align="center">US13</td>
        <td align="justify">Añadir foto de perfil</td>
        <td align="justify">Como usuario, quiero poder añadir una foto de perfil.</td>
        <td align="justify">Escenario 1:<br>
            Given que el usuario está en su perfil,<br>
            When el usuario selecciona la opción para añadir una foto de perfil,<br>
            Then se debe abrir un cuadro de diálogo que permita al usuario seleccionar una foto de su dispositivo,<br>
        And cuando el usuario selecciona una foto y confirma la acción, la foto de perfil del usuario debe actualizarse con la foto seleccionada.</td>
        <td align="center">EP06</td>
    </tr>
    <tr>
        <td align="center">US14</td>
        <td align="justify">Recibir notificaciones sobre zona peligrosa</td>
        <td align="justify">Como usuario, quiero recibir notificaciones cuando me este acercando a una zona peligrosa</td>
        <td align="justify">Escenario 1:<br>
            Given que el usuario ha activado las notificaciones de zonas peligrosas en la configuración de la aplicación,<br>
            When el usuario se acerca a una zona marcada como peligrosa,<br>
        Then el usuario debe recibir una notificación alertándole de la proximidad a la zona peligrosa.</td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US15</td>
        <td align="justify">Ver reportes</td>
        <td align="justify">Como usuario, quiero poder ver los reportes de otros usuarios en las denuncias.</td>
        <td align="justify">Escenario 1:<br>
            Given que el usuario está viendo una denuncia,<br>
            When el usuario selecciona la opción para ver los reportes de otros usuarios,<br>
        Then se debe mostrar una lista de reportes con las calificaciones y comentarios de otros usuarios.</td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US16</td>
        <td align="justify">Editar información de perfil</td>
        <td align="justify">Como usuario, quiero poder editar mi información de perfil.</td>
        <td align="justify">Escenario 1:<br>
            Given que el usuario está en su perfil,<br>
            When el usuario selecciona la opción para editar su información de perfil,<br>
            Then se debe abrir una página o un cuadro de diálogo que permita al usuario editar su información de perfil,<br>
        And cuando el usuario realiza los cambios y confirma la acción, la información de perfil del usuario debe actualizarse con la nueva información.</td>
        <td align="center">EP06</td>
    </tr>
    <tr>
        <td align="center">US17</td>
        <td align="justify">Ver denuncias más recientes</td>
        <td align="justify">Como usuario, quiero poder ver las denuncias más recientes en mi área.</td>
        <td align="justify">Escenario 1:<br>
            Given que el usuario está en la página principal de la aplicación,<br>
            When el usuario selecciona la opción para ver las denuncias más recientes,<br>
        Then se debe mostrar una lista de las denuncias más recientes en su área.</td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US18</td>
        <td align="justify">Mapa de calor</td>
        <td align="justify">Como usuario, quiero poder ver un mapa de calor sobre los niveles de peligro</td>
        <td align="justify">Escenario 1:<br>
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
        <td align="justify">para poder disfrutar una experiencia fluida desde cualquier dispositivo móvil.</td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US20</td>
        <td align="justify">Desarrollo de Secciones Clave de la Landing Page</td>
        <td align="justify">Como visitante de la Landing Page, quiero encontrar información clara y atractiva.</td>
        <td align="justify">en cada sección de la landing page de la aplicación, para comprender fácilmente cómo la app puede mejorar mi seguridad personal y sentirme motivado a usarla</td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US21</td>
        <td align="justify">Implementación de Formularios de Contacto</td>
        <td align="justify">Como visitante de la Landing Page, deseo encontrar formularios de contacto funcionales y accesibles</td>
        <td align="justify">en la landing page de la aplicación, para poder comunicarme fácilmente con el equipo de desarrollo de PeaceApp y obtener respuestas a mis preguntas o preocupaciones relacionadas con la aplicación.</td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US22</td>
        <td align="justify">Compartir ubicación</td>
        <td align="justify">Como usuario de PeaceApp, quiero poder compartir mi ubicación con mis contactos cercanos.</td>
        <td align="justify"> para que puedan monitorear mi trayecto y asegurarse de que estoy seguro</td>
        <td align="center">EP04</td>
    </tr>
    <tr>
        <td align="center">US23</td>
        <td align="justify">Testimonios de Usuarios</td>
        <td align="justify">Como visitante de la Landing Page, quiero encontrar las opiniones de los diferentes usuarios </td>
        <td align="justify">que han probado la aplicación, para poder tener una idea clara de la experiencia y satisfacción de otros usuarios con PeaceApp</td>
        <td align="center">EP04</td>
    </tr>
</table>

## 3.3. Impact Mapping
<img src="../../assets/Impact_mapping.png" alt="Impact map">

## 3.4. Product Backlog
<table align="center" border="1">
    <tr align="center">
        <td>User Story ID</td>
        <td>Titulo</td>
        <td>Descripcion</td>
        <td>Priority (1/2/3/5/8)</td>
    </tr>
    <tr>
        <td align="center">US01</td>
        <td>Planificación de rutas seguras</td>
        <td>Como transeúnte, quiero recibir actualizaciones en tiempo real sobre las zonas de peligrosidad en mi ruta.</td>
        <td align="center">8</td>
    </tr>
    <tr>
        <td align="center">US02</td>
        <td>Actualizaciones en tiempo real</td>
        <td>Como transeúnte, quiero que la aplicación me sugiera la ruta más segura para llegar a mi destino.</td>
        <td align="center">8</td>
    </tr>
    <tr>
        <td align="center">US03</td>
        <td>Personalización de rutas</td>
        <td>Como transeúnte, quiero poder personalizar mis rutas en función de mis preferencias de seguridad.</td>
        <td align="center">3</td>
    </tr>
    <tr>
        <td align="center">US04</td>
        <td>Reporte de incidentes</td>
        <td>Como transeúnte, quiero poder reportar incidentes de seguridad a través de la aplicación.</td>
        <td align="center">8</td>
    </tr>
    <tr>
        <td align="center">US05</td>
        <td>Alertas de Zonas de Riesgo</td>
        <td>Como usuario, quiero recibir alertas si estoy a una zona de alto riesgo.</td>
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">US06</td>
        <td>Visualización de reportes</td>
        <td>Como transeúnte, quiero poder ver los reportes de otros usuarios en el mapa de calor de peligrosidad.</td>
        <td align="center">8</td>
    </tr>
    <tr>
        <td align="center">US07</td>
        <td>Acceso a reportes</td>
        <td>Como comisario, quiero tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.</td>
        <td align="center">8</td>
    </tr>
    <tr>
        <td align="center">US08</td>
        <td>Análisis de datos</td>
        <td>Como comisario, quiero poder analizar los datos recopilados para identificar patrones y tendencias.</td>
        <td align="center">8</td>
    </tr>
    <tr>
        <td align="center">US09</td>
        <td>Planificación de estrategias</td>
        <td>Como comisario, quiero utilizar la información recopilada para planificar estrategias contra la delincuencia.</td>
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">US10</td>
        <td>Priorización de reportes</td>
        <td>Como comisario, quiero poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.</td>
        <td align="center">3</td>
    </tr>
    <tr>
        <td align="center">US11</td>
        <td>Comunicación con entidades asociadas</td>
        <td>Como comisario, quiero poder compartir información relevante con otras entidades de seguridad para coordinar esfuerzos.</td>
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">US12</td>
        <td>Visualización de Rutas Seguras</td>
        <td>Como comisario, quiero poder ver las rutas seguras más utilizadas por los usuarios para entender mejor sus patrones de desplazamiento.</td>
        <td align="center">3</td>
    </tr>
</tr>
<tr>
    <td align="center">US13</td>
    <td>Añadir foto de perfil</td>
    <td>Como usuario, quiero poder añadir una foto de perfil.</td>
    <td align="center">2</td>
</tr>
</tr>
<tr>
    <td align="center">US14</td>
    <td>Recibir notificaciones sobre zona peligrosa</td>
    <td>Como usuario, quiero recibir notificaciones cuando me este acercando a una zona peligrosa.</td>
    <td align="center">5</td>
</tr>
</tr>
<tr>
    <td align="center">US15</td>
    <td>Ver reportes</td>
    <td>Como usuario, quiero poder ver los reportes de otros usuarios en las denuncias.</td>
    <td align="center">3</td>
</tr>
</tr>
<tr>
    <td align="center">US16</td>
    <td>Editar información de perfil</td>
    <td>Como usuario, quiero poder editar mi información de perfil.</td>
    <td align="center">3</td>
</tr>
</tr>
<tr>
    <td align="center">US17</td>
    <td>Ver denuncias más recientes</td>
    <td>Como usuario, quiero poder ver las denuncias más recientes en mi área.</td>
    <td align="center">5</td>
</tr>
</tr>
<tr>
    <td align="center">US18</td>
    <td>Mapa de calor</td>
    <td>Como usuario, quiero poder ver un mapa de calor sobre los niveles de peligro</td>
    <td align="center">8</td>
</tr>
</table>
