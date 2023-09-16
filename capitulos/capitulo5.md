## CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT

### 5.1. Software Configuration Management.

#### 5.1.1. Software Development Environment Configuration.

**Repositorios en Github del proyecto:**

- Documentación: https://github.com/TechNest2023/Informe-de-Trabajo.git
- Landing Page: https://github.com/TechNest2023/Landing-Page.github.io.git

La configuración del ambiente de desarrollo usará las siguientes herramientas de software:

**Requirement Management**
Para ver todo el tema de el manejo de los requisitos capturados por nuestras historias de usuario e ingresados al product backlog se usará Trello.

-  **Trello:** https://trello.com

**Product UX/UI Design:**
Se utilizará esta herramienta de diseño de prototipos y  mock-ups para nuestra Landing Page y Web Application, esto nos permite tener una mejor visión de como debería ser el resultado final que necesitamos.

- Figma: https://www.figma.com

**Software Development:**

• Herramientas permitidas:

Landing Page: 
Para el desarrollo de la Landing Page se hará uso de 3 tecnología más usadas en el mundo del desarrollo web que son el lenguaje de programación JavaScript, el lenguaje de etiquetas HTML y el lenguaje de estilos CSS.  De manera opcional se tratará de implementar con la estructura del framework Angular.
-  JavaScript: https://developer.mozilla.org/es/docs/Web/JavaScript 
- HTML: https://developer.mozilla.org/es/docs/Web/HTML
- CSS: https://developer.mozilla.org/es/docs/Web/CSS 

**Software Documentation:**
Para poder tener un API RESTFull o un servicio web de nuestro proyecto, usaremos Swagger para tener un mejor visualización y captura de los servicios que se realizaran internamente en el proyecto.

-  Swagger https://swagger.io/docs/


#### 5.1.2. Source Code Management.

Para una mejor organización del proyecto de software de TechNest se usará lo siguiente:

**Repositorios:**

EduFocus Landing Page: https://github.com/TechNest2023/Landing-Page.git

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

- CSS:  Este es un lenguaje de diseño, el cual nos ayudará a dejar el Landing Page más presentable y atractivo para los usuarios.

De igual manera, el despliegue del Landing Page se utilizarán las siguientes herramientas:
- Git: Es un sistema de control de versiones el cual registrará los cambios que se realizan en el proyecto mediante un historial para luego subirlo al repositorio en el GitHub.

[![git.png](https://i.postimg.cc/7PW71jv6/git.png)](https://postimg.cc/bd1spCwc)

- GitHub:  Esta es una plataforma que nos permitirá alojar el código de nuestro proyecto para que cualquier integrante del equipo pueda acceder a este y se pueda trabajar de forma colaborativa.

[![github.png](https://i.postimg.cc/yxtZV3h9/github.png)](https://postimg.cc/BP56p6VQ)

- GitFlow: Es el flujo de trabajo que se utilizará en Git para agregar nuevas funcionalidades, corregir errores y preparar el código Fuente para producción de nuestro Landing Page.

[![gitflow.png](https://i.postimg.cc/wTRNwFHk/gitflow.png)](https://postimg.cc/ZCZ0R8W9)

- GitHub Pages: Es un servicio que nos brinda GitHub para publicar nuestro Landing Page a partir del Repositorio creado.

[![githubpages.jpg](https://i.postimg.cc/QCH7GJ7h/githubpages.jpg)](https://postimg.cc/vxwT59XN)

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

[![coding.png](https://i.postimg.cc/4xZkBTjy/coding.png)](https://postimg.cc/Wh9H1xNc)

<br>

| **Repository** | **Branch** | **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
|----------------|------------|---------------|--------------------|-------------------------|-------------------------|
| | | | | |

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

##### ~~5.2.1.6. Services Documentation Evidence for Sprint Review.~~

<br><br>

##### 5.2.1.7. Software Deployment Evidence for Sprint Review.

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

