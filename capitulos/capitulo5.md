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
	- [Conclusiones](#conclusiones)
		- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
	- [Bibliografía](#bibliografía)
	- [Anexos](#anexos)

<br>

## CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT

### 5.1. Software Configuration Management.

#### 5.1.1. Software Development Environment Configuration.

**1. Project Management**

- Repositorio en Github: https://github.com/orgs/TechNest2023/repositories 	

**2. Requirements Management**

- Trello: 

	Es una herramienta de gestión de proyectos basada en tableros visuales. Permite organizar tareas en tarjetas y listas, asignar responsabilidades, establecer fechas límite y colaborar en tiempo real. Con funciones como arrastrar y soltar, comentarios y etiquetas, Trello facilita la organización y seguimiento del progreso de los proyectos. Además, se integra con otras herramientas y ofrece una vista clara del estado de las tareas.

	Trello: https://trello.com/es/tour 

**3. Product UX/UI Design**

- UXPressia

	Es una herramienta en línea que permite a los usuarios desarrollar diversas actividades ofreciendo distintos diseños con métodos para investigaciones de clientes. Por ello, se utilizó UXpressia para el desarrollo de User Person, Emphaty Map y Journey Map porque nos facilita los diseños y la obtención de tu trabajo en diferentes tipos de archivos como formato PDF o PNG de alta resolución e imprimirlos sin esfuerzo.
	
   UXPressia: Uxpressia.com


- Figma

	Es una herramienta de diseño de interfaces como colores, imágenes, formas, entre otros que nos permite diseñar y crear nuestra aplicación ofreciendo diversos modelos de celulares Iphone, Android con respecto a distintas generaciones. Además, se utilizará para la elaboración de nuestro prototipo brindándonos la opción de elaborar nuestro proyecto con la simulación para el usuario.

Figma: https://www.figma.com/files/recent?fuid=1229486195528071108

**4. Software Development**

- HTML

	El lenguaje para el desarrollo de plataformas web HTML define la estructura de su contenido. HTML consta de un conjunto de elementos que utiliza para incluir diferentes piezas de contenido para que se vean o se comporten de cierta manera. Las diversas etiquetas incrustadas pueden convertir una palabra o imagen en un hipervínculo a otro sitio web, poner palabras en cursiva, aumentar, reducir fuentes, entre otros. Además, HTML (Hypertext Markup Language) – Lenguajes de Marcas de Hipertextos no es lenguaje de programación.

	HTML: https://developer.mozilla.org/es/docs/Web/HTML

- CSS

	Este lenguaje se utiliza para ordenar las pautas de diseño de páginas web y presentar el contenido de la página de una manera atractiva. Así, HTML se utiliza para estructurar el contenido del sitio web, mientras que CSS se utiliza para estructurar la presentación. Cascading Stylesheets (CSS) – Hojas de filo en cascada
	
	CSS:  https://developer.mozilla.org/es/docs/Web/CSS  
           
- JavaScript

	JavaScript es un lenguaje de programación fundamental en el desarrollo web. Proporciona interactividad y dinamismo a las páginas, permitiendo la creación de experiencias de usuario más atractivas y funcionales. Sus beneficios incluyen la capacidad de validar formularios en tiempo real, cargar contenido de manera asíncrona sin recargar la página completa (Ajax), y crear aplicaciones web interactivas y altamente responsivas. 

	JS: https://developer.mozilla.org/es/docs/Web/JavaScript 

- Github: GitHub es un servicio web y en la nube que ayuda a los desarrolladores a almacenar y administrar su código para llevar el control de cambios de versiones Git. El uso del Github es para almacenar cada uno de los integrantes sus tareas asignadas y así tener mejor control y organización del trabajo

	Github:  https://github.com/

**5. Software Testing**

- Lenguaje Gherkin

	Es un lenguaje interpretado como un código. En este lenguaje, podemos agregar historias de usuario a nuestro programa con sus respectivas partes: función, escenario, dado, cuándo, and (opcionalmente), entonces. Esto se puede hacer en cualquier idioma, pero el idioma más común es el inglés. Este lenguaje se utiliza para implementar nuestras historias de usuario.

	Calatrava, S. G. (2021, octubre 13). Qué es Gherkin: cómo usarlo y cuáles son sus elementos. Profile Software Services. https://profile.es/blog/que-es-gherkin/

**6. Software Documentation**

- **Swagger**

	Swagger es una herramienta de código abierto que simplifica la documentación y prueba de APIs. Proporciona una forma estructurada y fácil de describir APIs, lo que facilita su comprensión y uso por parte de desarrolladores y equipos de trabajo. Swagger también permite la generación automática de documentación interactiva, facilitando la exploración y prueba de endpoints de API. 

	Swagger https://swagger.io/docs/




#### 5.1.2. Source Code Management.

A continuación, presentaremos la gestión del código fuente que planeamos realizar para este proyecto. Está gestión nos permitirá realizar el seguimiento y control de los múltiples cambios y modificaciones que se realice cualquier integrante del equipo, a lo largo de la vida útil del proyecto. Además, cabe destacar que para este proyecto se creará un repositorio en GitHub, donde se realizará el control de versiones.

Repositorio para el Landing Page: https://github.com/TechNest2023/Landing-Page.git

Repositorio para las pruebas de Aceptación: https://github.com/TechNest2023/Acceptance-Test.git

**Implementación de GitFlow**:

En primer lugar, para este proyecto se implementará GitFlow como Workflow de control de versiones.  Este es un modelo alternativo de creación de ramas en Git en el cual se utilizan ramas principales y ramas de apoyo. Es por ello que para nuestro GitFlow usaremos las siguientes ramas:

- **Ramas Principales:**

	- Rama Master: 

		Esta rama se encarga de contener el código fuente que está listo para producción, el cual vendría a ser una nueva versión de nuestro proyecto.

	- Rama Develop:

		Esta rama se encarga de contener el código fuente de los últimos cambios de desarrollo realizados antes de lanzar la próxima versión de nuestro proyecto

[![gitflow.jpg](https://i.postimg.cc/d1KkHzhr/gitflow.jpg)](https://postimg.cc/zL0G32SG)

***Nota:*** Organización de ramas con Git Flow

<br>

**Ramas de apoyo:**

Estas ramas siempre tienen un tiempo de vida limitado, debido a que una vez se termine con esta, pasará a fusionarse en cualquiera de las ramas principales, dependiendo del tipo de rama que se use, y posteriormente será eliminada. Teniendo en cuenta esto, las ramas de apoyo que utilizaremos para este proyecto son los siguientes:

- Rama Feature:

	Este tipo de rama surgen de la rama principal Develop y se utiliza para desarrollar nuevas funciones del proyecto. Una vez culminado la función detallada en esta rama, se deberá fusionar con la rama principal Develop para luego ser eliminada.

- Rama Release:

	Este tipo de rama surge de la rama principal Develop y se utiliza para preparar una nueva versión de producción. Una vez instanciada esta rama, ya no se podrán agregar nuevas funciones, puesto a que en esta rama solo se realizarán tareas orientadas a la publicación, como solución de errores, generación de documentación, etc. Además, una vez culminado con esta rama, deberá fusionarse tanto en la rama Máster, como en la rama Develop.

- Rama Hotfix

	Esta rama surge de la rama principal Máster y se utilizan para corregir rápidamente los problemas y errores que se presentaron en el código fuente publicado en la rama Master. Una vez se haya terminado de trabajar con la rama Hotfix, se deberá fusionar con las ramas Máster y Develop. 

<div align="center"><a  href = "https://postimg.cc/jWbDDkWp"><img  src="https://i.postimg.cc/5tHLkhf2/gitflow2.png"  alt="Gitflow"  width="500"  height="800" /></a></div>

<div align="center"> Nota: Git Workflow Diagram </div>

<br>

Para nombrar las ramas de Feature, Release y Hotfix en nuestro proyecto, seguiremos las convenciones del Semantic Versioning Specification (SemVer). Este sistema de numeración de versiones consta de tres partes: MAJOR.MINOR.PATCH (X.Y.Z), donde cada una representa la versión principal, la versión secundaria y la versión del parche, respectivamente. Comenzaremos con una versión 0.yz en GitFlow hasta que definamos la API pública con la que trabajaremos, momento en el que cambiaremos a la versión 1.0.0. A partir de aquí, seguiremos estas reglas para incrementar las versiones:

- Versión del Parche (Z): Se incrementará si se realizan correcciones de errores compatibles con versiones anteriores.
- Versión secundaria (Y): Se incrementará si se introduce una nueva funcionalidad compatible con versiones anteriores en la API pública o si se realizan cambios en el código privado, como la obsolescencia de funciones.
- Versión Principal (X): Se incrementará si se introducen cambios incompatibles con las versiones anteriores en la API pública.

Siguiendo esta estructura de versiones, nombraremos las ramas de la siguiente manera:

- Rama Feature: feature-vX.Y.Z (donde X.Y.Z representa la versión semántica).
Ejemplo: feature-v1.0.3

- Rama Release: release-vX.Y.Z (donde X.Y.Z representa la versión semántica).
Ejemplo: release-v1.2.1

- Rama Hotfix: hotfix-vX.Y.Z (donde X.Y.Z representa la versión semántica).
Ejemplo: hotfix-v1.1.5

En cuanto a los Conventional Commits, estos son una forma de especificar de manera más explícita los cambios realizados en los commits. Seguiremos la siguiente estructura para escribirlos:

```
<type> [opcional scope]: <description>
[optional body]
[optional footer(s)]
```

Donde:

- `<type>` representa el tipo de commit, como Feat (nueva funcionalidad), Fix (corrección de errores), Test (adición de pruebas), Docs (modificaciones en la documentación) y Perf (mejoras de rendimiento).
- `[opcional scope]` es opcional y se utiliza para proporcionar contexto adicional al commit.
- `<description>` es una breve descripción de los cambios realizados, escrita en minúsculas y en imperativo.
- `[optional body]` es un campo opcional donde se puede agregar información adicional en párrafos separados por saltos de línea.
- `[optional footer(s)]` es un campo opcional para informar sobre cambios importantes.

Este enfoque de Conventional Commits nos ayudará a mantener un historial de commits explícito y comprensible en nuestro proyecto.




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

**Diseño UI/UX:**
-  Figma ([https://www.figma.com/best-practices/guide-to-developerhandoff/components-styles-and-documentation/](https://www.figma.com/best-practices/guide-to-developerhandoff/components-styles-and-documentation/) )

**Herramienta ágil**
- Trello: https://trello.com

#### 5.1.4. Software Deployment Configuration.

Para el despliegue de los componentes de nuestro proyecto, hemos seleccionado herramientas específicas que nos permiten gestionar eficazmente el control de versiones y llevar a cabo el despliegue de manera fluida.

**Control de Versiones: Git y GitHub**

Utilizaremos Git como nuestro sistema de control de versiones principal. Git es una herramienta esencial que nos permitirá rastrear y gestionar todos los cambios realizados en nuestro proyecto, lo que incluye las modificaciones en el código fuente, la documentación y más. Cada cambio será registrado en un historial, lo que facilita la colaboración y el seguimiento de la evolución del proyecto.

GitHub será nuestra plataforma de alojamiento de código, donde almacenaremos y compartiremos nuestro repositorio de código con el equipo. Esto proporciona una colaboración en tiempo real, la capacidad de revisar y aprobar cambios, y una integración perfecta con otras herramientas.

<div align="center"><a  href = "https://postimg.cc/w35dXXxd"><img  src="https://i.postimg.cc/FF8sQp21/Github.jpg"  alt="Github"  width="600"  height="300" /></a></div>


**Despliegue de la Landing Page: Netlify**

Para el despliegue de nuestra Landing Page, hemos elegido Netlify, que se destaca en ofrecer soluciones avanzadas de automatización y alojamiento web, especialmente diseñadas para empresas. Esta plataforma permite a los usuarios configurar sus sitios web de manera instantánea y sencilla. Aquellas empresas que cuentan con una cuenta en Netlify pueden comenzar a alojar sus sitios web en esta plataforma de manera eficaz. Además, Netlify ofrece la posibilidad a los usuarios de alojar sus sitios web de forma intuitiva, ya sea mediante la simple acción de arrastrar y soltar componentes desde sus propias computadoras hacia su aplicación web, o incluso importando sus repositorios directamente desde Git.

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
| US-25 | Beneficios de EduFocus | LD03 |Verificar los beneficios de EduFocus |Como visitante del segmento estudiante o especialista quiero acceder a una descripción de los beneficios de la aplicación, para tener un panorama de los aportes que puede dejar EduFocus en mí. | 3 h|Gray Hidalgo, Alejandro Eduardo | Done|
| US-26 | Precios o planes de suscripción | LD04 |Visualizar los planes de suscripción y precios de cada uno  |Como visitante del segmento estudiante o especialista quiero visualizar los planes de suscripción, para poder ver si se ajusta a mi economía. | 3 h|Gray Hidalgo, Alejandro Eduardo | In-Process|
| US-27 | Página reponsive | LD05 |Verificar adaptabilidad de la web en diferentes tamaños de pantalla  |Como visitante del segmento estudiante o especialista, quiero que la página web se adapte a diferentes dispositivos para poder visualizar a la información desde mi celular o computadora. | 3 h|Gray Hidalgo, Alejandro Eduardo | In-Process|

<br><br>

##### 5.2.1.3. Development Evidence for Sprint Review.

A lo largo del primer sprint, nuestro equipo ha logrado avances significativos en la implementación de los componentes clave de nuestra solución. Durante este período, nos hemos concentrado en llevar a cabo investigaciones de experiencia de usuario (UX Research), elaborar el diseño y los prototipos de la Landing Page, además de abordar la programación de la solución en su forma estática.

Vista general del código:

[![coding.png](https://i.postimg.cc/4xZkBTjy/coding.png)](https://postimg.cc/Wh9H1xNc)



<br>

| **Repository** | **Branch** | **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
|----------------|------------|---------------|--------------------|-------------------------|-------------------------|
|Landing-Page |Main |56b7ab53ee59ef948a979fa354d32e18a144c1a5 |Feat |Landing Page Update | Sep 7
|Landing-Page |Main |1b342a79d5cc4be3128efc420f4a48cd5537934a |Feat |Update to deploy | Sep 18

<br><br>

##### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Los archivos .feature descritos en Gherkin son una parte fundamental de las metodologías de desarrollo de software basadas en el comportamiento, como Behavior-Driven Development (BDD). En este caso, sirve para comunicar y automatizar las especificaciones que se tienen en las historias de usuario. Además, para el Sprint 1 se abordaron las historias de usuario relacionadas a la EPIC-07 de la Landing Page.

**Link del repositorio de los Acceptance Test:** https://github.com/TechNest2023/Acceptance-Test.git

[![gherkin-github.png](https://i.postimg.cc/FzwgPD7V/gherkin-github.png)](https://postimg.cc/JHck033s)

<br>

[![gherkin-github-2.png](https://i.postimg.cc/gjxHqfk0/gherkin-github-2.png)](https://postimg.cc/rRL4qZ46)

A continuación, se presenta las pruebas de funcionalidad que presenta la Landing Page, respecto a los archivos .feature realizados en el lenguaje Gherkin para los criterios de aceptación que se deben cumplir.

<br>

| **Repository** | **Branch** | **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
|----------------|------------|---------------|--------------------|-------------------------|-------------------------|
|[Acceptance-Test](https://github.com/TechNest2023/Acceptance-Test) |Main |2c871f3e6c1d73b42161eb59704ab9620d5e33e0 |feat |added sprint 1 .feature files - Landing Page |Sep 11

<br><br>

- Se muestra las pruebas de la funcionalidad de Beneficios de EduFocus:
[![2.png](https://i.postimg.cc/TwrgfgYT/2.png)](https://postimg.cc/ftRJv39P)

<br>

[![5.png](https://i.postimg.cc/sDnSjVyG/5.png)](https://postimg.cc/zVg3pYyq)

<br><br>

##### 5.2.1.5. Execution Evidence for Sprint Review

En esta fase, nuestro equipo ha elaborado diseños minuciosos para la Landing Page. Hemos creado wireframes que establecen la estructura y la disposición de los elementos esenciales. Posteriormente, hemos desarrollado mockups que visualizan la apariencia y el estilo de la página. Estos mockups se han transformado en prototipos interactivos que permiten a los usuarios explorar la navegación y la funcionalidad prevista.

En cuanto al equipo de desarrollo, ha trabajado de manera efectiva en la programación de la Landing Page. Hemos empleado lenguajes de programación como HTML, CSS y JavaScript para convertir los diseños en una experiencia interactiva, además, se pudo integrar el framework de Angular para su desarrollo. 

[![Vide-presentacion.png](https://i.postimg.cc/pX6DR2Yc/Vide-presentacion.png)](https://postimg.cc/JGjyQCFj)

Video de presentación del Landing Page: https://youtu.be/nbXIblJgpkU 

<br><br>

##### 5.2.1.6. Services Documentation Evidence for Sprint Review.

La documentación de productos de software, como la Landing Page, se basa en archivos Gherkin escritos en lenguaje Cucumber. Estos archivos siguen una estructura clara que describe los criterios de aceptación del software mediante escenarios de prueba legibles. La estructura incluye encabezados que describen características, seguidos de escenarios que detallan el comportamiento esperado del software en situaciones específicas. Estos archivos facilitan la comprensión, colaboración y automatización de pruebas, garantizando que el software cumpla con los estándares requeridos.

Repositorio de la documentación de los Acceptance Test: https://github.com/TechNest2023/Acceptance-Test.git

[![testing.png](https://i.postimg.cc/yN4fRDk7/testing.png)](https://postimg.cc/Snd7FN6P)

<br>

Features de las User Stories del Sprint 1:

[![features.png](https://i.postimg.cc/ncWSHRxj/features.png)](https://postimg.cc/D8qP6c8n)

<br>

Gherkin de la Lading Page:

[![specific-Feature.png](https://i.postimg.cc/3xDSWXrL/specific-Feature.png)](https://postimg.cc/mPBN5FHM)


<br><br>

##### 5.2.1.7. Software Deployment Evidence for Sprint Review.

En el transcurso de este Sprint, se ha realizado un proceso de Deployment con enfoque en la creación de cuentas y configuración de recursos en Netlify, nuestro proveedor de alojamiento web. Este despliegue se centra específicamente en nuestra Landing Page, que es uno de los productos dentro de nuestro proyecto. 

Durante este proceso, se llevaron a cabo actividades clave, como la creación de una cuenta en Netlify y la configuración de recursos necesarios para alojar nuestra Landing Page de manera eficiente. Además, se trabajó en la integración y automatización de las tareas de Deployment para garantizar una ejecución fluida. 

**Asociación del repositorio de Github con Netlify:**

[![netlify1.png](https://i.postimg.cc/gjfxkXKZ/netlify1.png)](https://postimg.cc/WqwN54CN)

<br>

**Proceso de Despliegue del Landing Page:**

[![netlify2.png](https://i.postimg.cc/j5Sw8r5L/netlify2.png)](https://postimg.cc/wtnjvZDp)

<br>

**Proceso de construcción y despliegue:**
[![netlify3.png](https://i.postimg.cc/435Hb3XD/netlify3.png)](https://postimg.cc/kV257q6s)

<br>

[![netlify4.png](https://i.postimg.cc/nzSsgwjT/netlify4.png)](https://postimg.cc/KkLvgf5g)

<br>

**Finalización del despliegue:**

[![netlify5.png](https://i.postimg.cc/Zn99SF6m/netlify5.png)](https://postimg.cc/zHrDwhd2)

<br>

Landing Page Desplegada en : https://edufocus-landingpage.netlify.app 

[![landing-page-deploy.png](https://i.postimg.cc/TwfSFtMy/landing-page-deploy.png)](https://postimg.cc/TyNCWqPG)


<br><br>

##### 5.2.1.8. Team Collaboration Insights during Sprint.

**Ramas:**
[![branches.png](https://i.postimg.cc/DwdWMnZM/branches.png)](https://postimg.cc/mPk2cx7Y)

**Insights:**
[![insight1.png](https://i.postimg.cc/YqMQHZ7L/insight1.png)](https://postimg.cc/JtYs3TGR)

**GitFlow**
[![insight2.png](https://i.postimg.cc/SNdCNdQT/insight2.png)](https://postimg.cc/fJ3J8x9m)

<br><br><br>

## Conclusiones

**TB1:**

- Las entrevistas con Alexandra, Nancy y Nadir ofrecen diferentes perspectivas sobre la importancia de EduFocus, una plataforma que une estudiantes con especialistas en educación y psicología. 

- Para este análisis, recopilamos datos cualitativos a través de entrevistas estructuradas, categorizándolas por roles profesionales y segmentos de mercado. Esta metodología proporciona una base sólida para comprender las diversas necesidades y desafíos de los clientes.

- Es esencial destacar que la metodología Lean UX, respaldada por herramientas como el Lean UX Canvas, Lean UX Hypothesis Statement y Lean UX Assumptions, ha sido crucial para abordar la problemática que EduFocus busca resolver. Estas herramientas han facilitado la identificación de desafíos clave, la definición de hipótesis y la generación de soluciones orientadas al usuario. Su incorporación en la estrategia de EduFocus garantiza que la plataforma sea ágil y competitiva en un mercado en constante cambio..

- Se logro implementar a un 70% la Landing Page, pero ese espera que para los siguientes Sprints este  este apartado funcionando al 100%.

## Bibliografía

Andrade, I., Facio, S., Quiroz, A., Alemán, L., Flores, M., & Rosales, M.. (2018). Actitud, hábitos de estudio y rendimiento académico: Abordaje desde la teoría de la acción razonada.  _Enfermería universitaria_,  _15_(4), 342-351.  [https://doi.org/10.22201/eneo.23958421e.2018.4.533](https://doi.org/10.22201/eneo.23958421e.2018.4.533)

González, R. (2019). Relación entre hábitos de estudio y rendimiento académico. Revista Guatemalteca de Educación Superior, 2(1), 22-27. DOI: https://doi.org/10.46954/revistages.v2i1.22

Sinchigalo, R., Guzmán, B., & Bonilla, D. (2022). Bienestar emocional y rendimiento académico en estudiantes universitarios: relación bidimensional y su impacto en las estrategias de apoyo. Journal of Science and Research. 1-25. (ISSN: 2528-8083). https://doi.org/10.5281/zenodo.8008096

## Anexos

|Sección  |Características del video  |Sobre el contenido |Integración y entrega |
|--|--|--|--|
|Needfinding Interviews  |Cantidad de videos: 1<br>Nomenclatura: upc-pre-202302-si729-SW54-TechNest-needfinding-sprint-1<br>Formato: .mp4 <br>Duración:  |En las entrevistas se refleja la importancia de tener plataformas de ayuda que permitan al estudiante y al tutor tener un ambiente seguro, en el cual el estudiante supere sus dificultades en relación al aspecto académico, con herramientas que le ofrecen los especialistas y los especialistas imparten su conocimiento y ayuda a sus estudiantes de manera fácil. |https://rb.gy/lqew0 |