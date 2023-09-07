Chapter5.md
Chapter5.md
## CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT

### 5.1. Software Configuration Management.

#### 5.1.1. Software Development Environment Configuration.
La configuración del ambiente de desarrollo usará las siguientes herramientas de software:

**Product Management:**
 - Github Issues https://docs.github.com/es 

**Requirement Management:**
- Github Issues https://docs.github.com/es 

**Product UX/UI Design:**
- Figma: https://www.figma.com

**Software Development:**

• Herramientas permitidas:

Landing Page:
-  JavaScript: https://developer.mozilla.org/es/docs/Web/JavaScript 

- HTML: https://developer.mozilla.org/es/docs/Web/HTML

- CSS: https://developer.mozilla.org/es/docs/Web/CSS 

**Software Documentation:**

-  Swagger https://swagger.io/docs/


#### 5.1.2. Source Code Management.

Para una mejor organización del proyecto de software de TechNest se usará lo siguiente:

**Repositorios:**

EduFocus Landing Page: https://github.com/TechNest2023/Landing-Page.git
<br>

EduFocus Report: https://github.com/TechNest2023/Informe-de-Trabajo


**Gitflow:**
- Las ramas que se usarán serán las recomendadas por gitflow como la rama **main** para las funcionalidades en estado para producción.
- Luego, se tiene la rama **develop** donde se encontrará las funcionalidades antes de ser  lanzadas a producción, es decir, en ambiente de testeos.
- La rama **features** tendrá las funcionalidades atómicas que cada integrante aportará en el desarrollo del proyecto.
- Finalmente, se tendrá la rama **realease** para testear las funcionalidades antes de combinarla con la rama principal **main**.

#### 5.1.3. Source Code Style Guide & Conventions.

Utilizaremos la guía de estilos y convenciones de codificación en el lenguaje de Java, JavaScript, HTML, CSS y frameworks como Angular.

Adicionalmente, el equipo de desarrollo utilizará las siguientes herramientas de desarrollo:
<br>
**IDE:**
- IntelliJ Idea Ultimate: https://www.jetbrains.com/idea/
- WebStorm ([https://www.jetbrains.com/eses/webstorm/download/#section=windows](https://www.jetbrains.com/eses/webstorm/download/#section=windows) )
- GitHub ([https://docs.github.com/es](https://docs.github.com/es) )

- Java: https://www.java.com/en/
- JavaScript ([https://developer.mozilla.org/es/docs/Web/JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript) )
- CSS ([https://developer.mozilla.org/es/docs/Web/CSS](https://developer.mozilla.org/es/docs/Web/CSS) )
- HTML ([https://developer.mozilla.org/es/docs/Web/HTML](https://developer.mozilla.org/es/docs/Web/HTML) )
- NodeJS. ([https://nodejs.org/es/download/](https://nodejs.org/es/download/) )
<br>
**Frameworks:**
- Angular: https://angular.io
<br>
**Diseño UI/UX:**

-  Figma ([https://www.figma.com/best-practices/guide-to-developerhandoff/components-styles-and-documentation/](https://www.figma.com/best-practices/guide-to-developerhandoff/components-styles-and-documentation/) )
<br>
**Herramienta ágil**
Trello: https://trello.com

#### 5.1.4. Software Deployment Configuration.

Para el despliegue del Landing Page del Proyecto utilizaremos GitHub Pages, el cual es un servicio que nos brinda GitHub para publicar sitios web estáticos desde un repositorio.

Es por ello que primero hemos creado un repositorio donde se subirán las diversas versiones que realicemos en el proyecto

Además, cabe destacar que para el desarrollo del Landing Page se utilizarán las siguientes herramientas:

- HTML: Este es un lenguaje de etiqueta, el cual nos permitirá estructurar el Landing Page

- CSS:  Este es un lenguaje de diseño, el cual nos ayudará a dejar el Landing Page más presentable y atractivo para los usuarios
<![endif]-->

De igual manera, el despliegue del Landing Page se utilizarán las siguientes herramientas:
- Git: Es un sistema de control de versiones el cual registrará los cambios que se realizan en el proyecto mediante un historial para luego subirlo al repositorio en el GitHub.

[![git.png](https://i.postimg.cc/7PW71jv6/git.png)](https://postimg.cc/bd1spCwc)

- GitHub:  Esta es una plataforma que nos permitirá alojar el código de nuestro proyecto para que cualquier integrante del equipo pueda acceder a este y se pueda trabajar de forma colaborativa.

[![github.png](https://i.postimg.cc/yxtZV3h9/github.png)](https://postimg.cc/BP56p6VQ)

- GitFlow: Es el flujo de trabajo que se utilizará en Git para agregar nuevas funcionalidades, corregir errores y preparar el código Fuente para producción de nuestro Landing Page.

[![gitflow.png](https://i.postimg.cc/wTRNwFHk/gitflow.png)](https://postimg.cc/ZCZ0R8W9)

- GitHub Pages: Es un servicio que nos brinda GitHub para publicar nuestro Landing Page a partir del Repositorio creado.

[![githubpages.jpg](https://i.postimg.cc/QCH7GJ7h/githubpages.jpg)](https://postimg.cc/vxwT59XN)


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
| Sprint 1 Review Summary | **Equipo de desarrollo:** El equipo realizó las tareas asignadas exitosamente para la realización del UX Research, UX Design y todo lo referentes a la implementación de la Landing Page.
**Landing Page:** Se realizaron los diseños wireframe, mockup y prototype para posterior a ello, establecer el código de la página web estática en HTML, CSS y JavaScript. |
| Sprint 1 Retrospective Summary | **Oportunidades de mejora:** Se vio que hay que mejorar un poco en la comunicación del equipo para ir de manera más ágil cuando van haciendo cambios en el repositorio de github o van subiendo avances de tareas. |
| **Sprint Goal & User Stories** |
| Sprint 1 Goal | **Objetivos:**** Investigación:** Realizar el UX Research Métrica: Realización y demostración de los hallazgos.
**Diseño:** Realizar diseños wireframe, mockup y prototype de la Landing Page.Métrica:Creación exitosa de mockups interactivos 
**Programación:** Codificar Landing Page en los lenguajes de HTML, CSS y JavaScript. Métrica: Corrección exitosa del 100% del código a nivel de legibilidad.
**Despliegue:** Desplegar la solución estática Métrica: Verificación de que la Landing Page se ha desplegado correctamente en el entorno de producción. |
| Sprint 1 Velocity | 30 |
| Sum of Story Points | 25 |

##### 5.2.1.2. Sprint Backlog 1.

| **Sprint #** | Sprint 1 |
| --- | --- |
| User Story | Work-Item/ Task |

| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (hours)** | **Assigned To** | **Status**|
|--|--|--|--|--|--|--|--|
| US-23 | Idioma de la web | LD01 |Cambiar de idioma español a inglés | Como visitante del segmento estudiante o especialista quiero poder cambiar el idioma de la web, para ajustar la web a mis preferencias de idioma. | 3 h|Gray Hidalgo, Alejandro Eduardo | In-Process|
| US-24 | Visualización de la llamada a la acción | LD02 |Visualizar la opción de contacto con los desarrolladores |Como visitante del segmento estudiante o especialista quiero visualizar un botón de contacto, para poder conectarme con el equipo de EduFocus. | 3 h|Gray Hidalgo, Alejandro Eduardo | Done|
| US-25 | Beneficios de EduFocus | LD03 |Verificar los beneficios de EduFocus |Como visitante del segmento estudiante o especialista quiero acceder a una descripción de los beneficios de la aplicación, para tener un panorama de los aportes que puede dejar EduFocus en mí. | 3 h|Gray Hidalgo, Alejandro Eduardo | Done|
| US-26 | Precios o planes de suscripción | LD04 |Visualizar los planes de suscripción y precios de cada uno  |Como visitante del segmento estudiante o especialista quiero visualizar los planes de suscripción, para poder ver si se ajusta a mi economía. | 3 h|Gray Hidalgo, Alejandro Eduardo | In-Process|
| US-27 | Página reponsive | LD05 |Verificar adaptabilidad de la web en diferentes tamaños de pantalla  |Como visitante del segmento estudiante o especialista, quiero que la página web se adapte a diferentes dispositivos para poder visualizar a la información desde mi celular o computadora. | 3 h|Gray Hidalgo, Alejandro Eduardo | In-Process|



##### 5.2.1.3. Development Evidence for Sprint Review.

A lo largo del primer sprint, nuestro equipo ha logrado avances significativos en la implementación de los componentes clave de nuestra solución. Durante este período, nos hemos concentrado en llevar a cabo investigaciones de experiencia de usuario (UX Research), elaborar el diseño y los prototipos de la Landing Page, además de abordar la programación de la solución en su forma estática.

En esta fase, nuestro equipo ha elaborado diseños minuciosos para la Landing Page. Hemos creado wireframes que establecen la estructura y la disposición de los elementos esenciales. Posteriormente, hemos desarrollado mockups que visualizan la apariencia y el estilo de la página. Estos mockups se han transformado en prototipos interactivos que permiten a los usuarios explorar la navegación y la funcionalidad prevista.

En cuanto al equipo de desarrollo, ha trabajado de manera efectiva en la programación de la Landing Page. Hemos empleado lenguajes de programación como HTML, CSS y JavaScript para convertir los diseños en una experiencia interactiva. 

 **Repository** | **Branch** | **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
| --- | --- | --- | --- | --- | --- |---|
| |  |  |  |  |  |	|
| |  |  |  |  |  |	|
| |  |  |  |  |  |	|

##### 5.2.1.5. Execution Evidence for Sprint Review.


##### 5.2.1.6. Services Documentation Evidence for Sprint Review.
Los archivos .feature descritos en Gherkin son una parte fundamental de las metodologías de desarrollo de software basadas en el comportamiento, como Behavior-Driven Development (BDD). En este caso, sirve para comunicar y automatizar las especificaciones que se tienen en las historias de usuario. Además, para el Sprint 1 se abordaron las historias de usuario relacionadas a la EPIC-07 de la Landing Page.

[![gherkin.png](https://i.postimg.cc/wThwWDhn/gherkin.png)](https://postimg.cc/kBgNG6Yy)


##### 5.2.1.7. Software Deployment Evidence for Sprint Review.


##### 5.2.1.8. Team Collaboration Insights during Sprint.
CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT
5.1. Software Configuration Management.
5.1.1. Software Development Environment Configuration.
La configuración del ambiente de desarrollo usará las siguientes herramientas de software:

Product Management:

Github Issues https://docs.github.com/es
Requirement Management:

Github Issues https://docs.github.com/es
Product UX/UI Design:

Figma: https://www.figma.com
Software Development:

• Herramientas permitidas:

Landing Page:

JavaScript: https://developer.mozilla.org/es/docs/Web/JavaScript

HTML: https://developer.mozilla.org/es/docs/Web/HTML

CSS: https://developer.mozilla.org/es/docs/Web/CSS

Software Documentation:

Swagger https://swagger.io/docs/
5.1.2. Source Code Management.
Para una mejor organización del proyecto de software de TechNest se usará lo siguiente:

Repositorios:

EduFocus Landing Page: https://github.com/TechNest2023/Landing-Page.git


EduFocus Report: https://github.com/TechNest2023/Informe-de-Trabajo

Gitflow:

Las ramas que se usarán serán las recomendadas por gitflow como la rama main para las funcionalidades en estado para producción.
Luego, se tiene la rama develop donde se encontrará las funcionalidades antes de ser lanzadas a producción, es decir, en ambiente de testeos.
La rama features tendrá las funcionalidades atómicas que cada integrante aportará en el desarrollo del proyecto.
Finalmente, se tendrá la rama realease para testear las funcionalidades antes de combinarla con la rama principal main.
5.1.3. Source Code Style Guide & Conventions.
Utilizaremos la guía de estilos y convenciones de codificación en el lenguaje de Java, JavaScript, HTML, CSS y frameworks como Angular.

Adicionalmente, el equipo de desarrollo utilizará las siguientes herramientas de desarrollo:


IDE:

IntelliJ Idea Ultimate: https://www.jetbrains.com/idea/

WebStorm (https://www.jetbrains.com/eses/webstorm/download/#section=windows )

GitHub (https://docs.github.com/es )

Java: https://www.java.com/en/

JavaScript (https://developer.mozilla.org/es/docs/Web/JavaScript )

CSS (https://developer.mozilla.org/es/docs/Web/CSS )

HTML (https://developer.mozilla.org/es/docs/Web/HTML )

NodeJS. (https://nodejs.org/es/download/ )


Frameworks:

Angular: https://angular.io


Diseño UI/UX:

Figma (https://www.figma.com/best-practices/guide-to-developerhandoff/components-styles-and-documentation/ )


Herramienta ágil
Trello: https://trello.com

5.1.4. Software Deployment Configuration.
Para el despliegue del Landing Page del Proyecto utilizaremos GitHub Pages, el cual es un servicio que nos brinda GitHub para publicar sitios web estáticos desde un repositorio.

Es por ello que primero hemos creado un repositorio donde se subirán las diversas versiones que realicemos en el proyecto

Además, cabe destacar que para el desarrollo del Landing Page se utilizarán las siguientes herramientas:

HTML: Este es un lenguaje de etiqueta, el cual nos permitirá estructurar el Landing Page

CSS: Este es un lenguaje de diseño, el cual nos ayudará a dejar el Landing Page más presentable y atractivo para los usuarios
<![endif]–>

De igual manera, el despliegue del Landing Page se utilizarán las siguientes herramientas:

Git: Es un sistema de control de versiones el cual registrará los cambios que se realizan en el proyecto mediante un historial para luego subirlo al repositorio en el GitHub.
git.png

GitHub: Esta es una plataforma que nos permitirá alojar el código de nuestro proyecto para que cualquier integrante del equipo pueda acceder a este y se pueda trabajar de forma colaborativa.
github.png

GitFlow: Es el flujo de trabajo que se utilizará en Git para agregar nuevas funcionalidades, corregir errores y preparar el código Fuente para producción de nuestro Landing Page.
gitflow.png

GitHub Pages: Es un servicio que nos brinda GitHub para publicar nuestro Landing Page a partir del Repositorio creado.
githubpages.jpg

5.2. Landing Page, Services & Applications Implementation.
5.2.1. Sprint 1
5.2.1.1. Sprint Planning 1.
Sprint #	Sprint 1
Sprint Planning Background	
Date	2023-08-26
Time	3:00 PM
Location	Google Meet
Prepared By	Claudio Jesús Moreno Rosales
Attendees (to planning meeting)	Gray Hidalgo, Alejandro Eduardo/Herrera del Pino, Josehp Piero/Portales Ortiz, Diego Alejandro
Sprint 1 Review Summary	Equipo de desarrollo: El equipo realizó las tareas asignadas exitosamente para la realización del UX Research, UX Design y todo lo referentes a la implementación de la Landing Page.
Landing Page: Se realizaron los diseños wireframe, mockup y prototype para posterior a ello, establecer el código de la página web estática en HTML, CSS y JavaScript.	
Sprint 1 Retrospective Summary	Oportunidades de mejora: Se vio que hay que mejorar un poco en la comunicación del equipo para ir de manera más ágil cuando van haciendo cambios en el repositorio de github o van subiendo avances de tareas.
Sprint Goal & User Stories	
Sprint 1 Goal	Objetivos:** Investigación:** Realizar el UX Research Métrica: Realización y demostración de los hallazgos.
Diseño: Realizar diseños wireframe, mockup y prototype de la Landing Page.Métrica:Creación exitosa de mockups interactivos
Programación: Codificar Landing Page en los lenguajes de HTML, CSS y JavaScript. Métrica: Corrección exitosa del 100% del código a nivel de legibilidad.
Despliegue: Desplegar la solución estática Métrica: Verificación de que la Landing Page se ha desplegado correctamente en el entorno de producción. |
| Sprint 1 Velocity | 30 |
| Sum of Story Points | 25 |

5.2.1.2. Sprint Backlog 1.
Sprint #	Sprint 1
User Story	Work-Item/ Task
Id	Title	Id	Title	Description	Estimation (hours)	Assigned To	Status
US-23	Idioma de la web	LD01	Cambiar de idioma español a inglés	Como visitante del segmento estudiante o especialista quiero poder cambiar el idioma de la web, para ajustar la web a mis preferencias de idioma.	3 h	Gray Hidalgo, Alejandro Eduardo	In-Process
US-24	Visualización de la llamada a la acción	LD02	Visualizar la opción de contacto con los desarrolladores	Como visitante del segmento estudiante o especialista quiero visualizar un botón de contacto, para poder conectarme con el equipo de EduFocus.	3 h	Gray Hidalgo, Alejandro Eduardo	Done
US-25	Beneficios de EduFocus	LD03	Verificar los beneficios de EduFocus	Como visitante del segmento estudiante o especialista quiero acceder a una descripción de los beneficios de la aplicación, para tener un panorama de los aportes que puede dejar EduFocus en mí.	3 h	Gray Hidalgo, Alejandro Eduardo	Done
US-26	Precios o planes de suscripción	LD04	Visualizar los planes de suscripción y precios de cada uno	Como visitante del segmento estudiante o especialista quiero visualizar los planes de suscripción, para poder ver si se ajusta a mi economía.	3 h	Gray Hidalgo, Alejandro Eduardo	In-Process
US-27	Página reponsive	LD05	Verificar adaptabilidad de la web en diferentes tamaños de pantalla	Como visitante del segmento estudiante o especialista, quiero que la página web se adapte a diferentes dispositivos para poder visualizar a la información desde mi celular o computadora.	3 h	Gray Hidalgo, Alejandro Eduardo	In-Process
5.2.1.3. Development Evidence for Sprint Review.
A lo largo del primer sprint, nuestro equipo ha logrado avances significativos en la implementación de los componentes clave de nuestra solución. Durante este período, nos hemos concentrado en llevar a cabo investigaciones de experiencia de usuario (UX Research), elaborar el diseño y los prototipos de la Landing Page, además de abordar la programación de la solución en su forma estática.

En esta fase, nuestro equipo ha elaborado diseños minuciosos para la Landing Page. Hemos creado wireframes que establecen la estructura y la disposición de los elementos esenciales. Posteriormente, hemos desarrollado mockups que visualizan la apariencia y el estilo de la página. Estos mockups se han transformado en prototipos interactivos que permiten a los usuarios explorar la navegación y la funcionalidad prevista.

En cuanto al equipo de desarrollo, ha trabajado de manera efectiva en la programación de la Landing Page. Hemos empleado lenguajes de programación como HTML, CSS y JavaScript para convertir los diseños en una experiencia interactiva.

Repository	Branch	Commit Id	Commit Message	Commit Message Body	Commited on (Date)
5.2.1.5. Execution Evidence for Sprint Review.
5.2.1.6. Services Documentation Evidence for Sprint Review.
Los archivos .feature descritos en Gherkin son una parte fundamental de las metodologías de desarrollo de software basadas en el comportamiento, como Behavior-Driven Development (BDD). En este caso, sirve para comunicar y automatizar las especificaciones que se tienen en las historias de usuario. Además, para el Sprint 1 se abordaron las historias de usuario relacionadas a la EPIC-07 de la Landing Page.

gherkin.png

5.2.1.7. Software Deployment Evidence for Sprint Review.
5.2.1.8. Team Collaboration Insights during Sprint.
MENU
Signed in as Harry Yasper.
Main workspace synced with your Google Drive app data folder.
