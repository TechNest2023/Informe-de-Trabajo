## Tabla de contenido

- [**Capítulo V: Product Implementation, Validation & Deployment**](#capítulo-v-product-implementation-validation--deployment)
	- [5.1. Software Configuration Management.](#51-software-configuration-management)
		- [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
		- [5.1.2. Source Code Management.](#512-source-code-management)
		- [5.1.3. Source Code Style Guide & Conventions.](#513-source-code-style-guide--conventions)
		- [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
	- [5.2. Landing Page, Services & Applications Implementation.](#52-landing-page-services--applications-implementation)
		- [5.2.1. Sprint 1](#521-sprint-1)
			- [5.2.1.1 Sprint Planning 1](#5211-sprint-planning-1)
			- [5.2.1.2. Sprint Backlog 1.](#5212-sprint-backlog-1)
			- [5.2.1.3. Development Evidence for Sprint Review.](#5213-development-evidence-for-sprint-review)
			- [5.2.1.4. Testing Suite Evidence for Sprint Review.](#5214-testing-suite-evidence-for-sprint-review)
			- [5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
			- [5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
			- [5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
			- [5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)
		- [5.2.2. Sprint 2](#522-sprint-2)
			- [5.2.2.1 Sprint Planning 1](#5221-sprint-planning-2)
			- [5.2.2.2. Sprint Backlog 1.](#5222-sprint-backlog-2)
			- [5.2.2.3. Development Evidence for Sprint Review.](#5223-development-evidence-for-sprint-review)
			- [5.2.2.4. Testing Suite Evidence for Sprint Review.](#5224-testing-suite-evidence-for-sprint-review)
			- [5.2.2.5. Execution Evidence for Sprint Review.](#5225-execution-evidence-for-sprint-review)
			- [5.2.2.6. Services Documentation Evidence for Sprint Review.](#5226-services-documentation-evidence-for-sprint-review)
			- [5.2.2.7. Software Deployment Evidence for Sprint Review.](#5227-software-deployment-evidence-for-sprint-review)
			- [5.2.2.8. Team Collaboration Insights during Sprint.](#5228-team-collaboration-insights-during-sprint)
	- [Conclusiones](#conclusiones)
		- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
	- [Bibliografía](#bibliografía)
	- [Anexos](#anexos)

<br>

## CAPITULO IV: PRODUCT DESIGN

### 4.1. Style Guidelines.

En esta sección, delineamos los principios de estilo que guiarán la creación de nuestro producto desde cero. Estas directrices establecerán un estándar para la elección de fuentes, tamaños y la paleta de colores necesarios en el proceso inicial de prototipado del diseño de **EduFocus**. Estas indicaciones serán una valiosa referencia para los integrantes del equipo, ofreciéndoles una comprensión clara sobre cómo implementar los diferentes elementos de diseño en todas las áreas y secciones de la plataforma. Esto conducirá a un considerable ahorro de tiempo y a una mayor uniformidad en el aspecto visual de **EduFocus**.

#### 4.1.1. General Style Guidelines.

En esta sección, se presentará la gama completa de colores que hemos establecido, así como los íconos, el logotipo y la fuente de texto elegidos. Estos elementos son fundamentales en la construcción de los estilos visuales que definirán la estética de nuestra plataforma web. Cada tono y diseño ha sido meticulosamente escogido para comunicar una identidad uniforme y distintiva en toda la aplicación, garantizando una experiencia visual atractiva para quienes la utilicen.

[![general.jpg](https://i.postimg.cc/fRQSMMLD/general.jpg)](https://postimg.cc/0bZyfRDB)

#### 4.1.2. Web Style Guidelines.

En esta sección, se presentará la gama completa de colores que hemos establecido, así como los íconos, el logotipo y la fuente de texto elegidos. Estos elementos son fundamentales en la construcción de los estilos visuales que definirán la estética de nuestra plataforma web. Cada tono y diseño ha sido meticulosamente escogido para comunicar una identidad uniforme y distintiva en toda la aplicación, garantizando una experiencia visual atractiva para quienes la utilicen. Se eligió la fuente Poppins de Google debido a que tiene un estilo moderno, también elegimos lo botones con borde redondeado y sin contorno para que hagan juego con la fuente. En cuanto a los íconos, los elegimos básandonos en la iconografía básica de muchas web applications.

[![web.jpg](https://i.postimg.cc/Pfc8FWnL/web.jpg)](https://postimg.cc/jCH5DJ5K)

### 4.2. Information Architecture.

La finalidad principal de diseñar la arquitectura de la información es establecer una organización coherente y accesible para los usuarios, facilitando así que puedan descubrir, comprender y moverse con eficacia por el contenido.

#### 4.2.1. Organization Systems.

Como equipo, hemos acordado adoptar un formato jerárquico convencional, que se asemeja al enfoque de organización comúnmente utilizado en la mayoría de las páginas. Podríamos describir este enfoque de formato de la siguiente manera:

<div align="center" style="{}" >
  <strong>Landing page</strong>
</div>

* **Inicio**

   En esta sección será la pantalla de nuestro landing page, ya que permitirá a los usuarios registrarse e iniciar sesión en nuestra web application

* **Habilidades de estudio a desarrollar**

   En esta sección se indican algunas habilidades que el usuario logrará desarrollar gracias al uso de nuestro sistema

* **Estrategias para bienestar emocional**

   En esta sección se colocarán algunas estrategias que los estudiantes aprenderán para su bienestar emocional

* **Seguimiento académico**

   En esta sección se detalla sobre esa funcionalidad que tiene la web application

* **Call-to-action**

   Los usamos para poder lograr que nuestro usuario se interese en visitar nuesta web application

* **Footer**

   Está sección contendrá la información de contacto y referencias otras páginas 

#### 4.2.2. Labeling Systems.

Los "Sistemas de Etiquetado" son un conjunto de métodos y tácticas empleados para asignar nombres, etiquetas o títulos explicativos a elementos y secciones en una interfaz digital, como un sitio web, una aplicación móvil o una plataforma en línea.

 <div align="center" style="{}" >
  <strong>Landing page</strong>
</div>

Es crucial que las etiquetas utilizadas en la landing page coincidan con las que hemos detallado en la estructura previamente mencionada. Esta decisión se fundamenta en la navegación sencilla que nuestra página de inicio proporciona gracias a su diseño sin complicaciones. Asimismo, no tenemos la intención de incorporar múltiples alternativas que pudieran necesitar, por ejemplo, un motor de búsqueda.



#### 4.2.3. SEO Tags and Meta Tags

Las "etiquetas SEO" y las "etiquetas meta" son componentes del código HTML que se emplean en una página web para ofrecer datos suplementarios acerca del contenido de la página a los motores de búsqueda y a los visitantes.

 <div align="center" style="{}" >
  <strong>Landing page</strong>
</div>

**SEO Tags:**

- Title Tag:

```
<title>EduFocus</title>
```

- Meta Description Tag:

```
<meta name="description" content=""EduFocus te ofrece recomendaciones de estudio personalizadas, estrategias para mejorar tu bienestar emocional y seguimiento de tu progreso académico y emocional. Con acceso a expertos en educación y psicología, nuestra plataforma facilita la interacción entre estudiantes y especialistas, proporcionando un entorno enriquecedor para tu desarrollo académico y emocional">
```

**Meta Tags:**

- Charset Meta Tag:

```
<meta charset="UTF-8">
```

- Viewport Meta Tag:

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

- Author Meta Tag:

```
<meta name="author" content="TechNest">
```

- Keywords Meta Tag (opcional):

```
<meta name="keywords" content="Educación personalizada,
Técnicas de estudios,
Salud emocional,
Bienestar mental,
Recomendaciones de estudio,
Seguimiento académico,
Plataforma educativa">
```

#### 4.2.4. Searching Systems.

Estos sistemas se han desarrollado con el propósito de agilizar la búsqueda de información, productos, servicios o cualquier tipo de contenido que responda a las necesidades y consultas de los usuarios de forma rápida

 <div align="center" style="{}" >
  <strong>Landing page</strong>
</div>

No aplicamos sistemas de búsqueda ya que no le consideramos conveniente, ya que la landing page no cuenta con servicios complejos ni tampoco una gran cantidad de información como para implementar algún sistema de búsqueda.


#### 4.2.5. Navigation Systems.

Los "Navigation Systems" (Sistemas de Navegación) se refieren a las estrategias y elementos utilizados en un diseño web o interfaz para guiar a los usuarios a través de la estructura y el contenido de un sitio web, aplicación u otra plataforma digital. Estos sistemas están diseñados para hacer que la navegación sea más intuitiva, eficiente y agradable para los usuarios, permitiéndoles encontrar la información que buscan y moverse entre diferentes secciones con facilidad.

 <div align="center" style="{}" >
  <strong>Landing page</strong>
</div>

1. **Navegación a través de Botones:**

   En la sección hero, un botón "Iniciar prueba" te llevará directamente a la web application. Esto garantiza una navegación rápida hacia la acción principal que deseamos que los usuarios tomen. Adicional a esto tenemos el botón de "Acceder" y "Registrarse", los cuales también nos llevarán al inicio de sesión de la web application.

2. **Footer - Navegación Rápida:**

   En la parte inferior de la página, el footer incluye una sección de navegación rápida. Aquí encontrarás botones que te llevarán a las secciones clave, como \*\*"Nosotros", "Otros servicios".

3. **Scroll Suave:**

   Implementa un scroll suave para que, al desplazarnos por la landing page el contenido aparezca lentamente con una animación

<br>

### 4.3. Landing Page UI Design.

#### 4.3.1. Landing Page Wireframe.

**Vista desde escritorio:**

<div align="center"><a  href = "https://postimg.cc/WqTXsJ9S"><img  src="https://i.postimg.cc/qqCYXs2f/landing-wireframe-desktop.jpg"  alt="Landing Page Wireframe Desktop"  width="250"  height="590" /></a></div>

<br><br>

**Vista desde móvil:**

<div align="center"><a  href = "https://postimg.cc/WqTXsJ9S"><img  src="https://i.postimg.cc/ydx2W4d8/landing-wireframe-movilejpg.jpg"  alt="Landing Page Wireframe Mobile"/></a></div>

<br><br><br><br>

#### 4.3.2. Landing Page Mock-up.

**Vista desde escritorio:**

<div align="center"><a  href = "https://postimg.cc/3dSdJP8m"><img  src="https://i.postimg.cc/dVvdnYgH/landing-mockup-desktop.jpg"  alt="Landing Page Mock-Up Desktop"/></a></div>

<br><br>

**Vista desde móvil:**

<div align="center"><a  href = "https://postimg.cc/Wt7dxdx9"><img  src="https://i.postimg.cc/T2znLm0X/landing-mockup-movil.jpg"  alt="Landing Page Mock-Up Mobile"/></a></div>

<br><br>

### 4.4. Web Applications UX/UI Design.
#### 4.4.1. Web Applications Wireframes.

**Estudiantes:**

**Inicio**

<div align="center"><a  href = "https://postimg.cc/w1n53tqX"><img  src="https://i.postimg.cc/FKHTWcwB/inicio.jpg"  alt="Wireframe Inicio" width="700"  height="350"/></a></div>

<br>

**Actividades**

<div align="center"><a  href = "https://postimg.cc/zVXFQZ2g"><img  src="https://i.postimg.cc/jdy3LRzZ/actividades.jpg"  alt="Wireframe Actividades del estudiante" width="700"  height="350"/></a></div>

<br>

**Registro**

<div align="center"><a  href = "https://postimg.cc/DJP1CBq6"><img  src="https://i.postimg.cc/Jn9KzF0f/registro.jpg"  alt="Wireframe Registro" width="700"  height="350"/></a></div>

<br>

**Agendar Sesion**

<div align="center"><a  href = "https://postimg.cc/XpHkSHtD"><img  src="https://i.postimg.cc/cLZ93PhZ/agendar-sesion.jpg"  alt="Wireframe Agendar Sesion del estudiante" width="700"  height="350"/></a></div>

<br>

**Chat de mensajería**

<div align="center"><a  href = "https://postimg.cc/Z0mcryrj"><img  src="https://i.postimg.cc/gcXTbVr9/chat-mensajes.jpg"  alt="Wireframe Chat de mensajería del estudiante" width="700"  height="350"/></a></div>

<br>

**Chats**

<div align="center"><a  href = "https://postimg.cc/dZJjvzqg"><img  src="https://i.postimg.cc/prFGQH3V/chats.jpg"  alt="Wireframe Chats del estudiante" width="700"  height="350"/></a></div>

<br>

**Visitar Perfil**

<div align="center"><a  href = "https://postimg.cc/MM7mCW8y"><img  src="https://i.postimg.cc/xC7pbCxF/esitar-perfil.jpg"  alt="Wireframe Visitar perfil del estudiante" width="700"  height="350"/></a></div>

<br>

**Inicio de Sesion**

<div align="center"><a  href = "https://postimg.cc/vDvvXHhy"><img  src="https://i.postimg.cc/2jsXk1B1/inicio-sesion.jpg"  alt="Wireframe Inicio de Sesion " width="700"  height="350"/></a></div>

<br>

**Listado de sesiones**

<div align="center"><a  href = "https://postimg.cc/QFFkXg3N"><img  src="https://i.postimg.cc/fRKHf5qd/listado-sesiones.jpg"  alt="Wireframe Listado de Sesiones del estudiante" width="700"  height="350"/></a></div>

<br>

**Perfil Especialista**

<div align="center"><a  href = "https://postimg.cc/bSPfXJTM"><img  src="https://i.postimg.cc/BbLSKP1q/netlify.jpg"  alt="Netlify"  width="600"  height="300" /></a></div>


**Despliegue de la Web App: Firebase**

Para la implementación de nuestra Web App, hemos optado por Firebase, quees una plataforma ampliamente utilizada para el despliegue de aplicaciones web y móviles. Ofrece una solución integral que simplifica el proceso de implementación de aplicaciones en línea. Con Firebase, los desarrolladores pueden aprovechar servicios de alojamiento web confiables y escalables. Permite cargar y alojar fácilmente aplicaciones web, proporcionando una infraestructura de alojamiento segura y de alto rendimiento. 

<div align="center"><a  href = "https://postimg.cc/m1SfTspr"><img  src="https://i.postimg.cc/T1zRq2rn/firebase.png"  alt="Firebase"  width="600"  height="300" /></a></div>

**GitFlow: Método de Desarrollo**

Para gestionar nuestro flujo de trabajo de desarrollo, seguiremos la metodología GitFlow. Este enfoque establece reglas claras para agregar nuevas características, solucionar problemas y preparar el código fuente para su lanzamiento. Nos ayuda a mantener una estructura organizada del repositorio y garantiza que todos los cambios se gestionen de manera coherente antes de implementarlos.

<div align="center"><a  href = "https://postimg.cc/vgfwS9Wf"><img  src="https://i.postimg.cc/cH51CBC9/gitflow3.png"  alt="Gitflow"  width="600"  height="300" /></a></div>

<br><br>

### 5.2. Landing Page, Services & Applications Implementation.
#### 5.2.1. Sprint 1
##### 5.2.1.1. Sprint Planning 1.

| **Sprint #** | Sprint 1 |
| --- | --- |
| **Sprint Planning Background** |
| Date | 2023-08-26 |
| Time | 3:00 PM |
| Location | Google Meet |
| Prepared By | Claudio Jesús Moreno Rosales|
| Attendees (to planning meeting) | Gray Hidalgo, Alejandro Eduardo/Herrera del Pino, Josehp Piero/Portales Ortiz, Diego Alejandro |
| Sprint 1 Review Summary | **Equipo de desarrollo:** El equipo realizó las tareas asignadas exitosamente para la realización del UX Research, UX Design y todo lo referentes a la implementación de la Landing Page. **Landing Page:** Se realizaron los diseños wireframe, mockup y prototype para posterior a ello, establecer el código de la página web estática en HTML, CSS y JavaScript. | |
| Sprint 1 Retrospective Summary | **Oportunidades de mejora:** Se vio que hay que mejorar un poco en la comunicación del equipo para ir de manera más ágil cuando van haciendo cambios en el repositorio de github o van subiendo avances de tareas. |
| **Sprint Goal & User Stories** ||
| Sprint 1 Goal | **Objetivos:**** Investigación:** Realizar el UX Research Métrica: Realización y demostración de los hallazgos. <br><br>**Diseño:** Realizar diseños wireframe, mockup y prototype de la Landing Page. Métrica: Creación exitosa de mockups interactivos. <br><br>**Programación:** Codificar Landing Page en los lenguajes de HTML, CSS y JavaScript. Métrica: Corrección exitosa del 100% del código a nivel de legibilidad.<br><br>**Despliegue:** Desplegar la solución estática Métrica: Verificación de que la Landing Page se ha desplegado correctamente en el entorno de producción. |
| Sprint 1 Velocity | 30 |
| Sum of Story Points | 25 |

<br><br>

##### 5.2.1.2. Sprint Backlog 1.

| **Sprint #** | Sprint 1 |
| --- | --- |
| User Story | Work-Item/ Task |

| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (hours)** | **Assigned To** | **Status**|
|--|--|--|--|--|--|--|--|
| US-23 | Idioma de la web | LD01 |Cambiar de idioma español a inglés | Como visitante del segmento estudiante o especialista quiero poder cambiar el idioma de la web, para ajustar la web a mis preferencias de idioma. | 3 h|Gray Hidalgo, Alejandro Eduardo | In-Process|
| US-24 | Visualización de la llamada a la acción | LD02 |Visualizar la opción de contacto con los desarrolladores |Como visitante del segmento estudiante o especialista quiero visualizar un botón de contacto, para poder conectarme con el equipo de EduFocus. | 3 h|Gray Hidalgo, Alejandro Eduardo | Done|
| US-25 | Beneficios de EduFocus | LD03 |Verificar los beneficios de EduFocus |Como visitante del segmento estudiante o especialista quiero acceder a una descripción de los beneficios de la aplicación, para tener un panorama de los aportes que puede dejar EduFocus en mí. | 3 h|Moreno Rosales, Claudio Jesús | Done|
| US-26 | Precios o planes de suscripción | LD04 |Visualizar los planes de suscripción y precios de cada uno  |Como visitante del segmento estudiante o especialista quiero visualizar los planes de suscripción, para poder ver si se ajusta a mi economía. | 3 h|Herrera Del Pino, Josehp Piero | Done|
| US-27 | Página reponsive | LD05 |Verificar adaptabilidad de la web en diferentes tamaños de pantalla  |Como visitante del segmento estudiante o especialista, quiero que la página web se adapte a diferentes dispositivos para poder visualizar a la información desde mi celular o computadora. | 3 h|Portales Ortiz, Diego Alejandro | Done|

<br><br>

#### 4.4.3. Web Applications Mock-ups.

<div align="center"> En esta ventana los usuarios iniciarán sesión para poder ingresar a nuestra web application. <a  href = "https://postimg.cc/8jxBzymK">
<img  src="https://i.postimg.cc/wjjWFZyp/inicio-sesion.jpg"  alt="Inicio de sesion"  width="700"  height="400"/></a></div>

<br>

<div align="center"> Esta ventana es la del formulario de registro, nuestros usuarios podrán registrarse como especialistas o estudiantes. <a  href = "https://postimg.cc/PNxmzG6V">
<img  src="https://i.postimg.cc/44vBGspG/registro.jpg"  alt="Registro"  width="700"  height="400"/></a></div>


<br>

<div align="center"> Esta es la ventana de inicio para los que se registraron como estudiantes, se muestra la diversidad de especialistas que tiene la plataforma. <a  href = "https://postimg.cc/vxcfQ9gw">
<img  src="https://i.postimg.cc/3NZBFF3N/inicio-estudiante.jpg"  alt="Ventana de inicio"  width="700"  height="400"/></a></div>

<br>

<div align="center">  Esta es la ventana para crear una sesión con alguno de los especialistas según la disponibilidad de los mismos. <a  href = "https://postimg.cc/mcsYQtq7">
<img  src="https://i.postimg.cc/q7t1HKxD/Agendar-sesion.jpg"  alt="Agendar Sesion"  width="700"  height="400"/></a></div>


<br>

<div align="center">  Esta es la ventana en la que se muestran todas las sesiones pendientes con los diversos especialistas. <a  href = "https://postimg.cc/cKBQTdy2">
<img  src="https://i.postimg.cc/tgL2qgrq/lista-sesiones-agendadas.jpg"  alt="Lista de Sesiones Agendadas"  width="700"  height="400"/></a></div>

  
<br>

<div align="center">  Esta es la ventana en la que se muestran todas las sesiones pendientes con los diversos especialistas. <a  href = "https://postimg.cc/Z07x1YBh">
<img  src="https://i.postimg.cc/SNq1YJmj/chat-estudiante.jpg"  alt="Chat del estudiante"  width="700"  height="400"/></a></div>
   
<br>

<div align="center">  Esta es la ventana en la que se muestran todas las sesiones pendientes con los diversos especialistas. <a  href = "https://postimg.cc/gxRyXvMY">
<img  src="https://i.postimg.cc/sgHTLm7Z/encio-mensajes-estudiante.jpg"  alt="Envío de mensajes al estudiante"  width="700"  height="400"/></a></div>
    
<br>

<div align="center"> Esta es la ventana en la que el estudiante subirá las actividades asignadas por los diferentes especialistas con los que tiene una sesión programada. <a  href = "https://postimg.cc/JGs5mwZH">
<img  src="https://i.postimg.cc/8PHKRNC4/actividades-estudiante.jpg"  alt="Actividades del estudiante"  width="700"  height="400"/></a></div>


<br>

<div align="center"> En esta ventana se muestra el perfil del especialista y las actividades encargadas para mí. <a  href = "https://postimg.cc/TL2n4BTw">
<img  src="https://i.postimg.cc/9MZ1rjSG/perfil-especialista-desde-Alumno.jpg"  alt="Perfil del especialista, vista desde el perfil del alumno"  width="700"  height="400"/></a></div>


<br>

<div align="center"> En esta ventana  se muestra las calificaciones otorgadas por los especialistas respecto a las actividades asignadas.<a  href = "https://postimg.cc/1nWDhMzK">
<img  src="https://i.postimg.cc/902b9n5s/progreso.jpg"  alt="Progreso"  width="700"  height="400"/></a></div>


<br>

<div align="center"> En esta ventana se muestra el chat personal abierto desde la perspectiva del especialistas. <a  href = "https://postimg.cc/vxDy37Tj">
<img  src="https://i.postimg.cc/mkyrZ8sb/chat-mensajes.jpg"  alt="Chat de mensajería" width="700"  height="400"/></a></div>


<br>

<div align="center"> En esta ventana se muestran todos los chats con los diferentes alumnos que tienen programada una sesión con el especialista desde la perspectiva del mismo..<a  href = "https://postimg.cc/TyXRfWNL">
<img  src="https://i.postimg.cc/8C7sdRhH/chat.jpg"  alt="Chats" width="700"  height="400"/></a></div>

<br>

<div align="center"> 
En esta ventana se muestra como los especialistas pueden definir su horario disponible para los estudiantes.<a  href = "https://postimg.cc/VrfmbP8z">
<img  src="https://i.postimg.cc/26v6MC9L/estableces-horarios.jpg"  alt="Horarios" width="700"  height="400"/></a></div>


<br>

<div align="center"> 
En esta sección se muestra el perfil del estudiante desde la perspectiva del especialista, el cual puede dejarle actividades personalizadas.<a  href ="https://postimg.cc/K4sx4Wsy"><img src="https://i.postimg.cc/FshRC5y1/peril-estudiante.jpg"  alt="Perfil del estudiante, desde la vista del especialista." width="700"  height="400"/></a></div>


<br><br>

##### 5.2.1.8. Team Collaboration Insights during Sprint.

**Ramas:**
[![branches.png](https://i.postimg.cc/DwdWMnZM/branches.png)](https://postimg.cc/mPk2cx7Y)

**Insights:**
[![insight1.png](https://i.postimg.cc/YqMQHZ7L/insight1.png)](https://postimg.cc/JtYs3TGR)

**GitFlow**
[![insight2.png](https://i.postimg.cc/SNdCNdQT/insight2.png)](https://postimg.cc/fJ3J8x9m)

<br><br><br>


### 5.2.2. Sprint 2 

En el marco del segundo Sprint de nuestro proyecto, estamos enfocados en la corrección y mejora de las actividades relacionadas con el proceso de Needfinding, centrándonos en aspectos clave como los User Persona, Mapas As-Is, Mapas To-Be, Impact Map y User Journey Map. Reconociendo la importancia de estos elementos en la comprensión de las necesidades y expectativas de nuestros usuarios, hemos decidido realizar ajustes significativos para garantizar su precisión y utilidad. Además, durante este Sprint, nos embarcaremos en la mejora continua de nuestro Landing Page, con el objetivo de perfeccionar su apariencia y funcionalidad. Esta acción nos acercará aún más a su despliegue exitoso. 

Paralelamente, avanzaremos en la creación de la primera versión de nuestra Frontend Web Application. A medida que avanzamos, también nos aseguraremos de mantener todos nuestros documentos y productos de software actualizados, garantizando así que reflejen con precisión el estado actual de nuestro proyecto y cumplan con los estándares de calidad esperados. 

[![sprins.png](https://i.postimg.cc/hGzYFt0N/sprins.png)](https://postimg.cc/QBDm1swq)

<br><br>

### 5.2.2.1 Sprint Planning 2

| **Sprint #** | Sprint 2 |
| --- | --- |
| **Sprint Planning Background** |
| Date | 2023-09-21 |
| Time | 5:00 PM |
| Location | Google Meet |
| Prepared By | Claudio Jesús Moreno Rosales|
| Attendees (to planning meeting) | Gray Hidalgo, Alejandro Eduardo/Herrera del Pino, Josehp Piero/Portales Ortiz, Diego Alejandro |
| Sprint 2 Review Summary | **Equipo de desarrollo:** El equipo asignó las nuevas tareas a realizar para corregir correctamente las observaciones del sprint 1. <br>**Landing Page:** Se estableció los aspectos del Landing Page que se van a Mejorar para este segundo sprint | |
| Sprint 2 Retrospective Summary | **Oportunidades de mejora:** Se vio que hay que mejorar un poco en la comunicación del equipo para ir de manera más ágil cuando van haciendo cambios en el repositorio de github o van subiendo avances de tareas y si hay contratiempos avisar con anticipación para evitar errores después. |
| **Sprint Goal & User Stories** ||
| Sprint 2 Goal | **Objetivos:** <br><br> **Programación:** Mejorar el aspecto y la legibilidad del código para la Landing Page. Además, realizar el primer avance del Frontend Web Application. <br> Métrica: Corrección exitosa del 100% del código.<br><br>**Despliegue:** Desplegar la solución estática del Landing Page en el Hosting de Netlify y desplegar el Frontend Web Application en Firebase.  |
| Sprint 2 Velocity | 15 |
| Sum of Story Points | 11  |

<br><br>

### 5.2.2.2. Sprint Backlog 2

| **Sprint #** | Sprint 2 |
| --- | --- |
| User Story | Work-Item/ Task |

| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (hours)** | **Assigned To** | **Status**|
|--|--|--|--|--|--|--|--|
| US-01 | Registro de nuevos especialistas | WA01 |Registrar especialistas | Como especialista quiero registrarme en la plataforma de EduFocus, para poder brindar mis servicios a los alumnos. | 4 h | Gray Hidalgo, Alejandro Eduardo | Done|
| US-05 | Registro de nuevo estudiante | WA05 |Registrar estudiantes |Como estudiante quiero registrarme en la plataforma de EduFocus, para acceder al amplio catálogo de especialistas. | 4 h| Moreno Rosales, Claudio Jesús | Done|
| US-19 | Crear nueva sesión | WA19 |Crear una nueva sesión con un especialista (realizar reserva) |Como estudiante quiero crear una nueva sesión, para empezar con las asesorías entre pares| 5 h| Herrera Del Pino, Josehp Piero| Done|
| US-23 | Idioma de la web | WA23 | Mejorar la accesibilidad en cuanto a los idiomas.  |Como visitante del segmento estudiante o especialista quiero poder cambiar el idioma de la web, para ajustar la web a mis preferencias de idioma. | 3 h| Portales Ortiz, Diego Alejandro | Done|


<br><br>

### 5.2.2.3. Development Evidence for Sprint Review

Para realizar las correcciones de la Landing Page se repartieron diversas actividades a  cada integrante pueda colaborar de manera satisfactoria y desplegar  el primer producto. 

Repositorio Landing Page:  https://github.com/TechNest2023/Landing-Page.git
Despliegue de Landing Page: https://edufocus-landingpage.netlify.app 

Para la primera versión del desarrollo de la Web APP se establecieron tareas específicas, la cual se reflejan mediante los siguientes commits realizados en el siguiente repositorio: https://github.com/TechNest2023/Frontend-Web-Application.git

<br>

| **Repository** | **Branch** | **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
|----------------|------------|---------------|--------------------|-------------------------|-------------------------|
|Landing-Page |Main |56b7ab53ee59ef948a979fa354d32e18a144c1a5 |Feat |Landing Page Update | Sep 7
|Landing-Page |Main |1b342a79d5cc4be3128efc420f4a48cd5537934a |Feat |Update to deploy | Sep 18

<br><br>

### 5.2.2.4. Testing Suite Evidence for Sprint Review

Los archivos .feature en Gherkin en esta occasion abarcan las User Stories 1, 5, 19 y 23. En este caso, sirve para verificar que las funcionalidades estén en la Web Application.

**Link del repositorio de los Acceptance Test:** https://github.com/TechNest2023/Acceptance-Test.git

A continuación, se presenta las pruebas de funcionalidad que presenta la Landing Page y la Web Application, respecto a los archivos .feature realizados en el lenguaje Gherkin para los criterios de aceptación que se deben cumplir.

<br>

[![Gherkin1.png](https://i.postimg.cc/dVBDgsxJ/Gherkin1.png)](https://postimg.cc/w116mpzr)

<br>

| **Repository** | **Branch** | **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
|----------------|------------|---------------|--------------------|-------------------------|-------------------------|
|[Acceptance-Test](https://github.com/TechNest2023/Acceptance-Test) |Main |05a55f508ad38d1be442de6f3afccb9429ae4434 |feat |The functionalities of the first version of the web application |Sep 23

<br><br>

### 5.2.2.5. Execution Evidence for Sprint Review

En este Sprint se ha logrado cumplir con las correcciones y mejoras a la Landing Page y brindar un primer avance del Web Application despegados en Netlify y Firebase.

-   Video Presentación de la Web App desplegada:

<br><br>

### 5.2.2.6. Services Documentation Evidence for Sprint Review

Se realizó la creación de los archivos Gherkin con extension .feature. Este se abarca las User Stories que descritas en el Sprint Backlog 2 que es el alcance definido por el equipo.

Repositorio de los Gherkin Features: https://github.com/TechNest2023/Acceptance-Test.git

<br>

 [![gherkin2.png](https://i.postimg.cc/HLkjgqqX/gherkin2.png)](https://postimg.cc/pm3PQ6XL)

<br>

**Features de las User Stories del Sprint 2:**

[![gherkin3.png](https://i.postimg.cc/W1jh9FS9/gherkin3.png)](https://postimg.cc/Tp7d1Pzm)

<br>

**Gherkin del Frontend Web Application:**

[![gherkin4.png](https://i.postimg.cc/SNtywg6t/gherkin4.png)](https://postimg.cc/8jMQvBnh)

<br><br>

### 5.2.2.7. Software Deployment Evidence for Sprint Review

FIREBASE

<br><br>

### 5.2.2.8. Team Collaboration Insights during Sprint


<br><br>

## Conclusiones

**TB1:**

- Las entrevistas con Alexandra, Nancy y Nadir ofrecen diferentes perspectivas sobre la importancia de EduFocus, una plataforma que une estudiantes con especialistas en educación y psicología. 

- Para este análisis, recopilamos datos cualitativos a través de entrevistas estructuradas, categorizándolas por roles profesionales y segmentos de mercado. Esta metodología proporciona una base sólida para comprender las diversas necesidades y desafíos de los clientes.

- Es esencial destacar que la metodología Lean UX, respaldada por herramientas como el Lean UX Canvas, Lean UX Hypothesis Statement y Lean UX Assumptions, ha sido crucial para abordar la problemática que EduFocus busca resolver. Estas herramientas han facilitado la identificación de desafíos clave, la definición de hipótesis y la generación de soluciones orientadas al usuario. Su incorporación en la estrategia de EduFocus garantiza que la plataforma sea ágil y competitiva en un mercado en constante cambio..

- Se logro implementar a un 70% la Landing Page, pero ese espera que para los siguientes Sprints este  este apartado funcionando al 100%.

**TP:**

- En este segundo Sprint, nuestra atención se ha centrado en la mejora de actividades cruciales relacionadas con el proceso de Needfinding. Hemos trabajado en la revisión y ajuste de elementos esenciales como User Persona, Mapas As-Is, Mapas To-Be, Impact Map y User Journey Map, reconociendo su valor en la comprensión de las necesidades de los usuarios.

- hemos dedicado esfuerzos para optimizar nuestro Landing Page, acercándonos cada vez más a su despliegue exitoso. Paralelamente, avanzamos en la creación de la primera versión de nuestra Frontend Web Application, asegurándonos de mantener nuestros documentos y productos actualizados para cumplir con los estándares de calidad esperados. Este Sprint representa un paso importante hacia nuestro objetivo final.

## Bibliografía

Andrade, I., Facio, S., Quiroz, A., Alemán, L., Flores, M., & Rosales, M.. (2018). Actitud, hábitos de estudio y rendimiento académico: Abordaje desde la teoría de la acción razonada.  _Enfermería universitaria_,  _15_(4), 342-351.  [https://doi.org/10.22201/eneo.23958421e.2018.4.533](https://doi.org/10.22201/eneo.23958421e.2018.4.533)

González, R. (2019). Relación entre hábitos de estudio y rendimiento académico. Revista Guatemalteca de Educación Superior, 2(1), 22-27. DOI: https://doi.org/10.46954/revistages.v2i1.22

Sinchigalo, R., Guzmán, B., & Bonilla, D. (2022). Bienestar emocional y rendimiento académico en estudiantes universitarios: relación bidimensional y su impacto en las estrategias de apoyo. Journal of Science and Research. 1-25. (ISSN: 2528-8083). https://doi.org/10.5281/zenodo.8008096

## Anexos

- ### Anexo A: Video presentaciones de entregables

<div align="center"> Video presentación del primer entregable: </div>

<div align="center"><a  href = "https://postimg.cc/3WgQ4Fq2"><img  src="https://i.postimg.cc/QNz8z6kY/portada.jpg"  alt="TB1"  width="600"  height="350" /></a></div>

<div align="center">  URL:  <a  href="https://youtu.be/YBDS9CG0y3c"> https://youtu.be/YBDS9CG0y3c </a></div> 

<div align="center"> Duración: 21:26 minutos </div>

---

- ### Anexo B: Diseños Mock-up

<div align="center"> Diseño de Landing Page: </div>

<div align="center"><a  href = "https://postimg.cc/NLz483rX"><img  src="https://i.postimg.cc/xT04QYf6/Mock-Up-Landing.png"  alt="MockUp"  width="600"  height="350" /></a></div>

<div align="center">  URL:  <a  href="https://www.figma.com/proto/1wuLrsXCa0nid5h7kKGR0v/Dise%C3%B1os-de-Open-Source?page-id=1%3A2&type=design&node-id=27-938&viewport=358%2C602%2C0.14&t=kWuba402O20Pr4hB-1&scaling=scale-down-width"> https://bitly.ws/VvN3 </a></div> 

---
- ### Anexo C:  Deploy de los productos software de EduFocus

<div align="center"> Landing Page Desplegada: </div>

<div align="center"><a  href = "https://postimg.cc/TyNCWqPG"><img  src="https://i.postimg.cc/TwfSFtMy/landing-page-deploy.png"  alt="Deploy Landing Page"  width="600"  height="350" /></a></div>

<div align="center">  URL:  <a  href="https://edufocus-landingpage.netlify.app "> Edufocus Landing Page</a></div> 

<br><br>

---
### Anexo D: Indicaciones para secciones que incluyen Videos

|Sección  |Características del video  |Sobre el contenido |Integración y entrega |
|--|--|--|--|
|Needfinding Interviews  |Cantidad de videos: 1<br>Nomenclatura: upc-pre-202302-si729-SW54-TechNest-needfinding-sprint-1<br>Formato: .mp4 <br>Duración:  |En las entrevistas se refleja la importancia de tener plataformas de ayuda que permitan al estudiante y al tutor tener un ambiente seguro, en el cual el estudiante supere sus dificultades en relación al aspecto académico, con herramientas que le ofrecen los especialistas y los especialistas imparten su conocimiento y ayuda a sus estudiantes de manera fácil. |https://rb.gy/lqew0 |

---
