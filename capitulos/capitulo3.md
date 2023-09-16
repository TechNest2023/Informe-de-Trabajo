## CAPÍTULO III: REQUIREMENTS SPECIFICATION

### 3.1. To-Be Scenario Mapping.

**Usuario Estudiante:**

[![To-Be-Estudiante.jpg](https://i.postimg.cc/MHN1V8hw/To-Be-Estudiante.jpg)](https://postimg.cc/QKgBZv8Y)

  **Usuario especialista:** 
  
[![To-Be-Especialista.jpg](https://i.postimg.cc/HxSwWMzV/To-Be-Especialista.jpg)](https://postimg.cc/G8y8qHZC)

<br><br><br><br><br><br><br><br><br><br><br><br>

### 3.2. User Stories.

|EPIC ID| Descripción de la épica |
|--|--|
|EP01 |Gestión de especialistas  |
|EP02 |Gestión de estudiantes  |
|EP03 |Gestión de seguimiento de actividades|
|EP04 |Gestión de cuenta|
|EP05 |Gestión de chat en línea|
|EP06 |Gestión de sesiones sincrónicas|
|EP07 |Diseño de Landing Page  |

<br><br><br><br>

|**Epic / Story ID**|**Título**| **Título**|**Criterios de Aceptación** |**Relacionado con (Epic ID)**|
|--|--|--|--|--|
|US-01|Registro de nuevos especialistas   | Como especialista quiero registrarme en la plataforma de EduFocus, para poder brindar mis servicios a los alumnos.  | **Escenario:** El especialista quiere formar parte del equipo de EduFocus. <br><br>**Dado que** el especialista se encuentra en la web de EduFocus<br>**Cuando** el especialista presiona en la opción “Únete al equipo de especialistas”<br>**Entonces** la plataforma le enviará a un formulario para completar sus datos como nombre completo, correo y contraseña.  |EP01|
|US-02|Modificar datos de los especialistas   |Como especialista quiero modificar mis datos de usuario, para tener mi perfil más personalizado. |**Escenario:** El especialista quiere formar modificar sus datos.<br><br> **Dado que** el especialista se encuentra en el módulo de “perfil” de la web <br>**Cuando** presiona en la opción “Editar Perfil”<br> **Entonces** el especialista podrá modificar sus datos como su nombre público, foto, correo, contraseña, biografía, entre otros. | EP01 |
|US-03 |Buscar especialistas por filtro |Como estudiante quiero buscar a los especialistas por área de expertís, para poder agendar una sesión. |**Escenario:** El estudiante quiere encontrar un especialista según su tipo de problema<br><br>**Dado que** el estudiante se encuentra en la página principal de la web de EduFocus<br>**Cuando** presiona en la opción “Filtros”<br>**Entonces** se expandirá una lista de filtros como país, idioma, carrera y área de especialización. |EP01 |
|US-04 |Borrar especialista |Como estudiante quiero realizar un una queja o reclamo, para hacer saber que el especialista no cumple las expectativas necesarias |**Escenario:** El especialista no ha cumplido con las normas éticas con el alumno o ha tenido un problema con el alumno.<br><br>**Dado que** el estudiante se encuentra en el perfil del especialista<br>**Cuando** presiona en la opción “Reportar”<br>**Entonces** se le enviará a un formulario donde completará la información de los hechos y sucesos.<br>**Y** se corroborará la información para tomar medidas contra el especialista. |EP01 |
|US-05 |Registro de nuevo estudiante |Como estudiante quiero registrarme en la plataforma de EduFocus, para acceder al amplio catálogo de especialistas. |**Escenario:** El estudiante quiere acceder a todos los beneficios de EduFocus<br><br>**Dado que** el estudiante se encuentra en la web principal<br>**Cuando** presiona en la opción “Registrarse”<br>**Entonces** el sistema le mostrará un formulario para completar su nombre, correo y contraseña. |EP02 |
|US-06 |Modificar datos del estudiante |Como estudiante quiero modificar mis datos, para tener mi información actualizada. |**Escenario:** El estudiante quiere modificar alguna información de su perfil como biografía, correo, contraseña o imagen.<br><br>**Dado que** el estudiante se encuentra en la sección de perfil<br>**Cuando** presiona en la opción “Editar perfil”<br>**Entonces** el estudiante podrá modificar sus datos principales y secundarios. |EP02 |
|US-07 |Deshabilitar estudiante |Como especialista quiero reportar sucesos de disciplina, para no afectar el ambiente de ayuda a alumnos. |**Escenario:** El estudiante presenta un mal comportamiento, incumple con las normas de Edufocus  o tiene faltas éticas.<br><br>**Dado que** el especialista se encuentra en la sección del perfil del estudiante<br>**Cuando** presiona en la opción “Reportar”<br>**Entonces** se le enviará a un formulario donde completará la información de los hechos y sucesos.**Y** se corroborará la información para tomar medidas contra el estudiante. |EP02 |
|US-08 |Buscar estudiantes por filtro |Como especialista quiero buscar a los estudiantes que han reservado cita conmigo, para tener mejor organizado mis horarios y sesiones. |**Escenario**: El especialista quiere llevar un control de sus estudiantes asignados<br><br>**Dado que** el especialista se encuentra en el apartado de “Mis estudiantes”<br>**Cuando** presiona en la opción “Buscar estudiante”<br>**Entonces** la web mostrará un listado de filtros de buscar a estudiantes por horarios de sesiones, buscar por fechas, buscar por temática a tratar y buscar por edad. |EP02 |
|US-09 |Registro de nuevo seguimiento |Como estudiante quiero tener un seguimiento de mis actividades encargadas por el especialista, para tener una mejor comprensión y adaptación de lo tratado en las sesiones. |**Escenario:** El estudiante decide hacer seguimiento a su progreso de implementación y aprendizaje de lo tratado en las sesiones con el especialista.<br>**Dado que** el estudiante se encuentra en la sección “Mis asesorías”<br>**Cuando** presiona en la opción “Realizar seguimiento”<br>**Entonces** se creará un nuevo módulo donde el especialista podrá subir las actividades que realizará el estudiante en un tiempo específico y con instrucciones detalladas<br>**Y** el especialista podrá revisar y dar retroalimentación de su avance**Y** se mostrará un dashboard del progreso del estudiante en la página principal |EP03 |
|US-10 |Modificación de seguimiento |Como especialista quiero modificar el progreso de los estudiantes, para que puedan visualizar sus avances de las actividades |**Escenario:** El especialista ha revisado las actividades y quiere dar a conocer las puntuaciones o porcentajes obtenidos en las actividades.<br><br>**Dado que** el especialista se encuentra en el perfil del estudiante<br>**Cuando** presiona en la opción “Modificar progreso”<br>**Entonces** la web le mostrará una serie de casilleros por actividades para que pueda completar con una nota específica<br>**Y** en el dashboard del estudiante se mostrará el avance que ha tenido en sus actividades. |EP03 |
|US-11 |Eliminar seguimiento |Como estudiante quiero cancelar el seguimiento de actividades, ya que la sesiones con el especialista fueron suficientes, para mi aprendizaje. |**Escenario:** El estudiante prefiere solo tener las sesiones con el especialista<br><br>**Dado que** el estudiante se encuentra en la sección “Mis asesorías”<br>**Cuando** presiona en la opción “Cancelar seguimiento”<br>**Entonces** las actividades y progresos desaparecerán de la plataforma. |EP03 |
|US-12 |Visualizar progreso de seguimiento |Como estudiante quiero visualizar mi progreso de las actividades de seguimiento, para tener un mejor entendimiento de mis avances. |**Escenario:** El estudiante quiere visualizar sus avances de las actividades de las asesorías<br>**Dado que** el estudiante se encuentra en la sección “Mis asesorías”<br>**Cuando** presiona en la opción “Ver mi progreso”<br>**Entonces** la plataforma le muestra un dashboard con la información porcentual de cómo está el estudiante con respecto a las actividades de las sesiones. |EP03 |
|US-13 |Recuperar datos de la cuenta |Como estudiante o especialista quiero recuperar los datos como correo y contraseña de mi cuenta, para poder ingresar a la plataforma |**Escenario:** El estudiante o especialista se olvidó sus credenciales de acceso o sus cuentas fueron vulneradas.<br><br>**Dado que** el estudiante o especialista se encuentra en la página principal de la web<br>**Cuando** presiona en la opción “Recuperar cuenta”<br>**Entonces** se le mostrará un formulario para verificar que el usuario sea el dueño original de la cuenta. |EP04 |
|US-14 |Eliminar cuenta |Como estudiante o especialista quiero eliminar mi cuenta para dejar de usar los servicios de EduFocus |**Escenario:** El estudiante o especialista quiere eliminar su cuenta.<br><br>**Dado que** el estudiante o especialista se encuentra en la sección “perfil”<br>**Cuando** presiona en la opción “Borrar cuenta”<br>**Entonces** la web le mostrará las opciones de borrar temporal o definitivamente la cuenta. |EP04|
|US-15 |Crear nueva conversación |Como estudiante quiero conversar fuera de las sesiones sincrónicas con mi especialista, para consultarle algunas dudas. |**Escenario:** El estudiante quiere conversar por chat en línea con el especialista<br><br>**Dado que** el estudiante se encuentra en el módulo de “Mis asesorías”<br>**Cuando** presiona en la opción “Crear chat de conversación”<br>**Entonces** se crear un chat en línea para que el estudiante pueda conversar de cualquier inquietud con su especialista. |EP05 |
|US-16 |Visualizar conversación |Como estudiante quiero revisar mis conversaciones con mi especialista, para revisar lo que se ha conversado. |**Escenario:** El estudiante quiere revisar el chat con el especialista<br><br>**Dado que** el estudiante quiere ver sus conversaciones con su especialista<br>**Cuando** presiona en la opción “Mis asesorías”<br>**Entonces** se le muestra todos los mensajes de conversación con el especialista |EP05 |
|US-17 |Eliminar conversación |Como estudiante quiero eliminar mis conversaciones con mi especialista, porque ya no veo la necesidad de tenerlo. |**Escenario:** El estudiante quiere eliminar el chat en línea de sus especialistas.<br><br>**Dado que** el estudiante se encuentra en el módulo “Mis asesorías”<br>**Cuando** presiona en la opción “Chat de conversación”<br>**Y** presiona en la opción “Eliminar chat”<br>**Entonces** se eliminará de manera correcta el chat en línea. |EP05 |
|US-18 |Buscar conversación por filtro |Buscar conversación por filtro |**Escenario:** El estudiante quiere buscar una parte específica de la conversación con el especialista.<br><br>**Dado que** el estudiante se encuentra en el apartado de  “Mis asesorías”<br>**Cuando** presiona en la opción “Chat de conversación”<br>**Y** presiona en la opción “Filtrar conversación”<br>**Entonces** se le mostrará una serie de filtros como buscar por fecha, hora y palabra. |EP05 |
|US-19 |Crear nueva sesión |Como estudiante quiero crear una nueva sesión, para empezar con las asesorías entre pares |**Escenario :** El estudiante quiere reservar sesiones con un especialista específico.<br><br>**Dado que** es estudiante se encuentra en el apartado “Reservar sesiones”<br>**Y** verifica la disponibilidad de tiempo del especialista<br>**Y** elige la fecha y hora para la sesión<br>**Cuando** presiona en la opción “Agendar sesión”<br>**Entonces** se creará una nueva sesión con el especialista.|EP06 |
|US-20 |Modificar sesión |Como estudiante quiero modificar una sesión agendada, para cambiar la fecha y hora de acuerdo con mi disponibilidad y la del especialista. |**Escenario:** El estudiante quiere cambiar la fecha de una sesión agendada.<br><br>**Dado que** el estudiante quiere modificar la fecha y hora de una sesión<br>**Y** se encuentra en la sección “Reservar sesiones”<br>**Cuando** presiona en la opción “Modificar reserva”<br>**Entonces** la plataforma le mostrará de nuevo el calendario y las horas en las que puede realizar una nueva reserva de sesión. |EP06 |
|US-21|Eliminar sesión | Como estudiante quiero eliminar una sesión agendada, porque decidí elegir a otro especialista de mi preferencia. |**Escenario:** El estudiante quiere cancelar una sesión agendada<br><br>**Dado que** el estudiante se encuentra en la sección “Reservar sesiones”<br>**Cuando** presiona en la opción “Cancelar reserva”<br>**Entonces** el sistema automáticamente borrará la sesión agendada.|EP06 |
|US-22 |Buscar sesiones por filtro |Como estudiante quiero buscar mis sesiones agendadas, para tener un panorama general de mis asesorías. |**Escenario:** El estudiante quiere revisar de manera general sus sesiones agendadas con varios o con un mismo especialista.<br><br>**Dado que** es estudiante se encuentra en la sección “Mis asesorías”<br>**Y** visualiza de manera general un calendario con todas las sesiones agendadas<br>**Cuando** presiona en la opción “Filtrar asesorías”<br>**Entonces** el sistema le muestra para buscar asesorías por fecha, hora y especialista. |EP06 |
|US-23 |Idioma de la web |Como visitante del segmento estudiante o especialista quiero poder cambiar el idioma de la web, para ajustar la web a mis preferencias de idioma. |**Escenario:** visitante quiere cambiar el idioma de la página de español a inglés.<br><br>**Dado que** el visitante se encuentra en la pantalla principal<br>**Cuando** presione en el botón “español”<br>**Y** selecciona la opción “inglés”<br>**Entonces** el sistema cambia el idioma de la página a “inglés”. |EP07 |
|US-24 |Visualización de la llamada a la acción|Como visitante del segmento estudiante o especialista quiero visualizar un botón de contacto, para poder conectarme con el equipo de EduFocus.  |**Escenario**: El visitante accede al formulario de contacto para contactar con EduFocus<br><br>**Dado que** el usuario se encuentra en la pantalla de inicio<br> **Cuando** haga clic en el botón “Contáctanos” <br>**Entonces** será enviada a la sección del formulario de contacto. |EP07  | 
|US-25 |Beneficios de EduFocus |Como visitante del segmento estudiante o especialista quiero acceder a una descripción de los beneficios de la aplicación, para tener un panorama de los aportes que puede dejar EduFocus en mí. |**Escenario**: El visitante lee sobre los beneficios de EduFocus<br><br> **Dado que** el usuario se encuentra en la pantalla de inicio<br> **Cuando** se desplace hacia la sección de “beneficios” <br>**Entonces** visualiza los beneficios de EduFocus. |EP07  | 
|US-26 |Precios o planes de suscripción |Como visitante del segmento estudiante o especialista quiero visualizar los planes de suscripción, para poder ver si se ajusta a mi economía. |**Escenario**: Usuario visualiza los tipos de planes que tiene EduFocus<br><br> **Dado que** el usuario se encuentra en la pantalla de inicio <br>**Cuando** se desplace hacia la sección “Planes”<br> **Entonces** visualizará los planes disponibles que tiene EduFocus |EP07  | 
|US-27 |Página reponsive |Como visitante del segmento estudiante o especialista, quiero que la página web se adapte a diferentes dispositivos para poder visualizar a la información desde mi celular o computadora. |**Escenario 1:** El visitante visualiza la Landing Page de EduFocus desde una computadora.<br><br> **Dado que** el usuario se ingresa a la página web de EduFocus<br> **Cuando** navegue por la página <br>**Entonces** visualizará todos los contenidos adaptados a su tamaño de pantalla.<br><br><br>**Escenario 2:** El visitante visualiza la Landing Page de EduFocus desde un celular.<br><br> **Dado que** el usuario se ingresa a la página web de EduFocus<br> **Cuando** navegue por la página<br> **Entonces** visualizará todos los contenidos adaptados a su tamaño de pantalla. |EP07  | 
   
   <br><br><br><br><br>
   
### 3.3. Impact Mapping.

**Primer Mapa de impacto:**

[![Impact-Map-1.png](https://i.postimg.cc/Hk590VYh/Impact-Map-1.png)](https://postimg.cc/G4LDd3sF)

<br>

**Segundo Mapa de Impacto:**

[![Impact-Map-2.png](https://i.postimg.cc/QxvqWp37/Impact-Map-2.png)](https://postimg.cc/8jBv2fsk)
  
<br>

### 3.4. Product Backlog.

|Orden|User Storie Id |Título|Descripción|Story Points |
|--|--|---|--|-- |
|1  |US-09  |Registro de nuevo seguimiento   |Como estudiante quiero tener un seguimiento de mis actividades encargadas por el especialista, para tener una mejor comprensión y adaptación de lo tratado en las sesiones.  |8    |
|2 |US-12 |Visualizar progreso de seguimiento |Como estudiante quiero visualizar mi progreso de las actividades de seguimiento, para tener un mejor entendimiento de mis avances. |8 |
|3 |US-10 |Modificación de seguimiento |Como especialista quiero modificar el progreso de los estudiantes, para que puedan visualizar sus avances de las actividades. |5 |
|4 |US-11 |Eliminar seguimiento |Como estudiante quiero cancelar el seguimiento de actividades, ya que la sesiones con el especialista fueron suficientes, para mi aprendizaje. |5 |
|5 |US-03 |Buscar especialistas por filtro |Como estudiante quiero buscar a los especialistas por área de expertís, para poder agendar una sesión. |5 |
|6 |US-23 |Idioma de la web |Como visitante del segmento estudiante o especialista quiero poder cambiar el idioma de la web, para ajustar la web a mis preferencias de idioma. |5 |
|7 |US-24|Visualización de la llamada a la acción |Como visitante del segmento estudiante o especialista quiero visualizar un botón de contacto, para poder conectarme con el equipo de EduFocus. |5 |
|8 |US-25 |Beneficios de EduFocus |Como visitante del segmento estudiante o especialista quiero acceder a una descripción de los beneficios de la aplicación, para tener un panorama de los aportes que puede dejar EduFocus en mí. |5 |
|9 |US-26 |Precios o planes de suscripción |Como visitante del segmento estudiante o especialista quiero visualizar los planes de suscripción, para poder ver si se ajusta a mi economía. |5 |
|10 |US-27 |Página reponsive |Como visitante del segmento estudiante o especialista, quiero que la página web se adapte a diferentes dispositivos para poder visualizar a la información desde mi celular o computadora. |5 |
|11 |US-08 |Buscar estudiantes por filtro |Como especialista quiero buscar a los estudiantes que han reservado cita conmigo, para tener mejor organizado mis horarios y sesiones. |3 |
|12 |US-15 |Crear nueva conversación |Como estudiante quiero conversar fuera de las sesiones sincrónicas con mi especialista, para consultarle algunas dudas. |3 |
|13 |US-16 |Visualizar conversación |Como estudiante quiero revisar mis conversaciones con mi especialista, para revisar lo que se ha conversado. |3 |
|14 |US-17 |Eliminar conversación |Como estudiante quiero eliminar mis conversaciones con mi especialista, porque ya no veo la necesidad de tenerlo. |3 |
|15 |US-18 |Buscar conversación por filtro |Buscar conversación por filtro |3 |
|16 |US-01 |Registro de nuevos especialistas |Como especialista quiero registrarme en la plataforma de EduFocus, para poder brindar mis servicios a los alumnos. |2 |
|17 |US-02 |Modificar datos de los especialistas |Como especialista quiero modificar mis datos de usuario, para tener mi perfil más personalizado. |2 |
|18 |US-04 |Borrar especialista |Como estudiante quiero realizar un una queja o reclamo, para hacer saber que el especialista no cumple las expectativas necesarias. |2 |
|19 |US-05 |Registro de nuevo estudiante |Como estudiante quiero registrarme en la plataforma de EduFocus, para acceder al amplio catálogo de especialistas. |2 |
|20 |US-06 |Modificar datos del estudiante |Como estudiante quiero modificar mis datos, para tener mi información actualizada. |2 |
|21 |US-07 |Deshabilitar estudiante |Como especialista quiero reportar sucesos de disciplina, para no afectar el ambiente de ayuda a alumnos. |2|
|22 |US-13 |Recuperar datos de la cuenta |Como estudiante o especialista quiero recuperar los datos como correo y contraseña de mi cuenta, para poder ingresar a la plataforma |2 |
|23 |US-14 |Eliminar cuenta |Como estudiante o especialista quiero eliminar mi cuenta para dejar de usar los servicios de EduFocus |2 |
|24 |US-19 |Crear nueva sesión |Como estudiante quiero crear una nueva sesión, para empezar con las asesorías entre pares |2 |
|25 |US-20 |Modificar sesión |Como estudiante quiero modificar una sesión agendada, para cambiar la fecha y hora de acuerdo con mi disponibilidad y la del especialista. |2 |
|26 |US-21 |Eliminar sesión |Como estudiante quiero eliminar una sesión agendada, porque decidí elegir a otro especialista de mi preferencia. |2|
|27 |US-22 |Buscar sesiones por filtro |Como estudiante quiero buscar mis sesiones agendadas, para tener un panorama general de mis asesorías. |2 |

<br>
Tablero Trello para seguimiento del Sprint 1:

[![trello.png](https://i.postimg.cc/xjPNcz2T/trello.png)](https://postimg.cc/4nmx0nyr)

***Nota:*** Se usó la herramienta de Trello para el seguimiento del Product Backlog

URL: https://trello.com/invite/b/jvy2pIMW/ATTI3b9f29c9e2d80e68eb7fe4271312289dA1712056/technest-edufocus-app