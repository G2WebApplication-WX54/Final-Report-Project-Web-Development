# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**Segmento 1: Ciudadanos preocupados por su seguridad personal en espacios públicos**

<img src="/assets/To-Be_Map_UP1.png" alt="To-Be Scenario Map User Persona 1" width="80%">

**Segmento 2: Entidades Gubernamentales responsables de la seguridad pública y la planificación urbana**

<img src="/assets/To-Be_Map_UP2.png" alt="To-Be Scenario Map User Persona 2" width="80%">

## 3.2. User Stories

<table align="center" border="1">
    <tr>
        <td align="center">Epic / Story ID</td>
        <td>Título</td>
        <td>Descripción</td>
        <td>Criterios de Aceptación</td>
        <td align="center">Relacionado con (Epic ID)</td>
    </tr>
    <tr>
        <td align="center">EP01</td>
        <td>Seguridad en el desplazamiento</td>
        <td>Este Epic se centra en cómo los usuarios pueden mejorar su seguridad durante el desplazamiento utilizando la aplicación.</td>
        <td>-</td>
        <td align="center">-</td>
    </tr>
    <tr>
        <td align="center">EP02</td>
        <td>Gestion de seguridad</td>
        <td>Este Epic se centra en cómo los comisarios pueden manejar y mejorar la seguridad en su jurisdicción utilizando la aplicación.</td>
        <td>-</td>
        <td align="center">-</td>
    </tr>
    <tr>
        <td align="center">US01</td>
        <td>Planificación de rutas seguras</td>
        <td>Como transeúnte, quiero recibir actualizaciones en tiempo real sobre las zonas de peligrosidad en mi ruta.</td>
        <td>Escenario: Un transeúnte está planeando su ruta y quiere recibir actualizaciones en tiempo real sobre las zonas peligrosas.<br>
            Given el transeúnte ha iniciado la aplicación<br>
            And ha ingresado su ruta.<br>
            When la aplicación detecta cambios en la peligrosidad de las zonas en la ruta del transeúnte.<br>
            Then la aplicación actualiza la información de peligrosidad en tiempo real y la muestra al transeúnte.
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US02</td>
        <td>Actualizaciones en tiempo real</td>
        <td>Como transeúnte, quiero que la aplicación me sugiera la ruta más segura para llegar a mi destino.</td>
        <td>Escenario: Un transeúnte quiere que la aplicación le sugiera la ruta más segura para llegar a su destino.<br>
            Given el transeúnte ha ingresado su destino en la aplicación.<br>
            When la aplicación ha calculado todas las rutas posibles.<br>
            Then la aplicación sugiere la ruta más segura basada en la información de peligrosidad actual.
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US03</td>
        <td>Personalización de rutas</td>
        <td>Como transeúnte, quiero poder personalizar mis rutas en función de mis preferencias de seguridad.</td>
        <td>Escenario: Un transeúnte quiere personalizar su ruta en función de sus preferencias de seguridad.<br>
            Given el transeúnte ha ingresado su ruta y ha accedido a las opciones de personalización.<br>
            When el transeúnte ajusta sus preferencias de seguridad.<br>
            Then la aplicación personaliza la ruta del transeúnte en función de sus preferencias.<br>
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US04</td>
        <td>Reporte de incidentes</td>
        <td>Como transeúnte, quiero poder reportar incidentes de seguridad a través de la aplicación.</td>
        <td>Escenario: Un transeúnte quiere reportar un incidente de seguridad a través de la aplicación.<br>
            Given el transeúnte ha presenciado un incidente de seguridad.<br>
            When el transeúnte ingresa los detalles del incidente en la aplicación.<br>
            Then la aplicación registra el incidente y actualiza la información de peligrosidad de la zona correspondiente.<br>
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US05</td>
        <td>Alertas de Zonas de Riesgo</td>
        <td>Como usuario, quiero recibir alertas si me acerco a una zona de alto riesgo.</td>
        <td>Escenario: Un usuario recibe una alerta cuando se acerca a una zona de alto riesgo.<br>
            Given el usuario está utilizando la aplicación mientras se desplaza.<br>
            When la aplicación detecta que el usuario se está acercando a una zona de alto riesgo.<br>
            Then la aplicación envía una alerta al usuario.<br>
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US06</td>
        <td>Visualización de reportes</td>
        <td>Como transeúnte, quiero poder ver los reportes de otros usuarios en el mapa de calor de peligrosidad.</td>
        <td>Escenario: Un transeúnte quiere ver los reportes de otros usuarios en el mapa de calor de peligrosidad.<br>
            Given el transeúnte ha abierto el mapa de calor de peligrosidad en la aplicación.<br>
            When hay reportes de otros usuarios disponibles para la zona que está viendo el transeúnte.<br>
            Then la aplicación muestra los reportes de otros usuarios en el mapa de calor.<br>
        </td>
        <td align="center">EP01</td>
    </tr>
    <tr>
        <td align="center">US07</td>
        <td>Acceso a reportes</td>
        <td>Como comisario, quiero tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.</td>
        <td>Escenario: Un comisario quiere tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.<br>
            Given el comisario ha iniciado sesión en la aplicación con su cuenta de comisario.<br>
            When el comisario accede a la sección de reportes de la aplicación.<br>
            Then la aplicación muestra al comisario los reportes de los usuarios.<br>
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US08</td>
        <td>Análisis de datos</td>
        <td>Como comisario, quiero poder analizar los datos recopilados para identificar patrones y tendencias.</td>
        <td>Escenario: Un comisario quiere analizar los datos recopilados para identificar patrones y tendencias.<br>
            Given el comisario tiene acceso a los datos recopilados por la aplicación.<br>
            When el comisario utiliza las herramientas de análisis de datos de la aplicación.<br>
            Then la aplicación proporciona al comisario los resultados del análisis de datos.<br>
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US09</td>
        <td>Planificación de estrategias</td>
        <td>Como comisario, quiero utilizar la información recopilada para planificar estrategias contra la delincuencia.</td>
        <td>Escenario: Un comisario quiere utilizar la información recopilada para planificar estrategias contra la delincuencia.<br>
            Given el comisario ha analizado los datos recopilados y ha identificado áreas problemáticas.<br>
            When el comisario utiliza la información recopilada para planificar estrategias.<br>
            Then la aplicación registra las estrategias del comisario y las asocia con las áreas problemáticas correspondientes.<br>
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US10</td>
        <td>Priorización de reportes</td>
        <td>Como comisario, quiero poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.</td>
        <td>Escenario: Un comisario quiere poder priorizar los reportes en función de su gravedad y urgencia para responder de manera más eficiente.<br>
            Given el comisario tiene acceso a los reportes de los usuarios.<br>
            When el comisario clasifica los reportes en función de su gravedad y urgencia.<br>
            Then la aplicación prioriza los reportes según la clasificación del comisario.<br>
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US11</td>
        <td>Comunicación con entidades asociadas</td>
        <td>Como comisario, quiero poder compartir información relevante con otras entidades de seguridad para coordinar esfuerzos.</td>
        <td>Escenario: Un comisario quiere compartir información relevante con otras entidades de seguridad para coordinar esfuerzos.<br>
            Given el comisario ha identificado información relevante que desea compartir.<br>
            When el comisario utiliza la función de compartir de la aplicación.<br>
            Then la aplicación comparte la información seleccionada con las entidades de seguridad seleccionadas por el comisario.<br>
        </td>
        <td align="center">EP02</td>
    </tr>
    <tr>
        <td align="center">US12</td>
        <td>Visualización de Rutas Seguras</td>
        <td>Como comisario, quiero poder ver las rutas seguras más utilizadas por los usuarios para entender mejor sus patrones de desplazamiento.</td>
        <td>Escenario: Un comisario quiere ver las rutas seguras más utilizadas por los usuarios para entender mejor sus patrones de desplazamiento.<br>
            Given el comisario ha accedido a la sección de rutas seguras de la aplicación.<br>
            When hay datos disponibles sobre las rutas seguras más utilizadas por los usuarios.<br>
            Then la aplicación muestra al comisario las rutas seguras más utilizadas.<br>
        </td>
        <td align="center">EP02</td>
    </tr>
</table>

## 3.3. Impact Mapping

<img src="../../assets/Impact_map.png" alt="Impact map">

## 3.4. Product Backlog

<table align="center" border="1">
    <tr align="center">
        <td>User Story ID</td>
        <td>Titulo</td>
        <td>Descripcion</td>
        <td>Priority</td>
    </tr>
    <tr>
        <td align="center">US01</td>
        <td>Planificación de rutas seguras</td>
        <td>Como transeúnte, quiero recibir actualizaciones en tiempo real sobre las zonas de peligrosidad en mi ruta.</td>
        <td align="center">3</td>
    </tr>
        <tr>
        <td align="center">US02</td>
        <td>Actualizaciones en tiempo real</td>
        <td>Como transeúnte, quiero que la aplicación me sugiera la ruta más segura para llegar a mi destino.</td>
        <td align="center">5</td>
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
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">US05</td>
        <td>Alertas de Zonas de Riesgo</td>
        <td>Como usuario, quiero recibir alertas si me acerco a una zona de alto riesgo.</td>
        <td align="center">3</td>
    </tr>
        <tr>
        <td align="center">US06</td>
        <td>Visualización de reportes</td>
        <td>Como transeúnte, quiero poder ver los reportes de otros usuarios en el mapa de calor de peligrosidad.</td>
        <td align="center">3</td>
    </tr>
        <tr>
        <td align="center">US07</td>
        <td>Acceso a reportes</td>
        <td>Como comisario, quiero tener acceso a los reportes de los usuarios para entender mejor la situación de seguridad.</td>
        <td align="center">5</td>
    </tr>
        <tr>
        <td align="center">US08</td>
        <td>Análisis de datos</td>
        <td>Como comisario, quiero poder analizar los datos recopilados para identificar patrones y tendencias.</td>
        <td align="center">5</td>
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
</table>
