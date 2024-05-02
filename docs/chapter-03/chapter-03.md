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
        <td align="justify">
            No corresponde
        </td>
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
        <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
Quiero obtener la información de un incidente mediante una API
Para mostrarla en la aplicación cuando se solicite.
</td>
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
        <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
Quiero registrar a un nuevo usuario mediante una API
Para visualizar a los usuarios afiliados a nuestra app.</td>
        <td align="justify">
	        Escenario 1:<br>
Dado que tengo acceso a al API de registro de usuarios <br>
Cuando envío una solicitud con datos válidos de un nuevo usuario<br>
Entonces el usuario se registro exitosamente en la base de datos y recibo una confirmación<br>
Escenario 2:<br>
Dado que tengo acceso a al API de registro de usuarios <br>
Cuando envío una solicitud con datos no válidos de un nuevo usuario<br>
Entonces la solicitud es rechazada y recibo un mensaje de error adecuado.
		</td>
        <td align="center">-</td>
	</tr>
	<tr>
		<td align="center">TS04</td>
        <td align="justify">GET User</td>
        <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
Quiero obtener la información de un usuario mediante una API
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
        <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
Quiero registrar la información de pago de las empresas o entidades mediante una API
Para contar con la información para pagos seguros.</td>
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
        <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
Quiero obtener la información de pago de las empresas o entidades mediante una API
Para recibir los pagos en la aplicación cuando lo solicite.</td>
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
        <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
Quiero obtener la información de que usuarios realizan los reportes mediante una API
Para mostrarla en la aplicación cuando se solicite.</td>
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
        <td align="justify">Como desarrollador que trabaja en la aplicación de PeaceApp
Quiero obtener la información de en que zonas se registraron los incidentes mediante una API
Para mostrarla en la aplicación cuando se solicite la cantidad de incidentes en una zona.</td>
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
        <td align="justify">Como desarrollador que trabaja en la aplicación PeaceApp
Quiero registrar la información de la dirección a la que se va a movilizar el ciudadano mediante una API
Para contar con la información que necesitará el API de Google Maps.</td>
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
        <td align="justify">Como desarrollador que trabaja en la aplicación PeaceApp
Quiero obtener la información de los usuarios por el tipo de usuario mediante una API
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
<img src="../../assets/Impact_mapping.png" alt="Impact map">

## 3.4. Product Backlog
|#Orden| ID |                                  User Story                                    |  Story Points  |
|:-----|:--:|:-------------------------------------------------------------------------------|:--------------:|
|  01  |US01|Contactar con la startup                      				     |        3       |
|  02  |US02|Navegar en el landing page                      				     |        1       |
|  03  |US03|Seleccion de tipo de usuario                      				     |        2       |
|  04  |US04|Registro como ciudadano                      				     |        2       |
|  05  |US05|Registro como entidad gubernamental                      			     |        3       |
|  06  |US06|Alertas de Zonas de Riesgo                      				     |        5       |
|  07  |US07|Recibir notificaciones sobre reportes recientes                      	     |        3       |
|  08  |US08|Añadir foto de perfil                      				     |        1       |
|  09  |US09|Editar información de perfil                      				     |        1       |
|  10  |US10|Personalización de rutas                      				     |        3       |
|  11  |US11|Visualización de Rutas Seguras                     			     |        2       |
|  12  |US12|Reporte de incidentes                    					     |        5       |
|  13  |US13|Visualización de reportes                     				     |        2       |
|  14  |US14|Acceso a reportes                     					     |        1       |
|  15  |US15|Priorización de reportes               					     |        2       |
|  16  |US16|Análisis de datos    							     |        3       |
|  17  |US17|Estrategias usando el mapa de calor        				     |        5       |
|  18  |US18|Mapa de calor        							     |        3       |
|  19  |US19|Compartir ubicación      							     |        2       |
|  20  |TS01|POST Inicident                      			    		     |        1       |
|  21  |TS02|GET Incident                      						     |        3       |
|  22  |TS03|POST User                     						     |        3       |
|  23  |TS04|GET User                    						     |        3       |
|  24  |TS05|POST Payment Card                     					     |        3       |
|  25  |TS06|GET Payment Card                      					     |        3       |
|  26  |TS07|GET Reports by user                      					     |        1       |
|  27  |TS08|GET zones by Quantity Incidents					   	     |        1       |
|  28  |TS09|POST address To Go                    					     |        1       |
|  29  |TS10|GET users by kind								     |	      1       |
