# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
En el siguiente apartado, se detalla cada uno de los productos de software utilizados en el proyecto. Esta descripción servirá como guía para que tanto los desarrolladores actuales como los futuros puedan participar de manera efectiva en todas las fases del proyecto.<br><br>
**Project Management**
- Notion: https://www.notion.so/es-es
Se empleó Notion para organizar y llevar un registro de las tareas que están por hacer, se están realizando y ya están completadas. De esta manera, podríamos tener un control en cuanto al tiempo de cómo estábamos desarrollando el proyecto y, asimismo, ver las actividades pendientes. Notion es una aplicación que se encuentra disponible en las tiendas de teléfonos móviles, web o aplicación de escritorio.
- Google Meet : https://meet.google.com
La plataforma de Google Meet se empleó para las reuniones virtuales con los integrantes del equipo y así poder comunicarnos entre nosotros sobre la gestión del proyecto. Asimismo, empleamos esta plataforma para poder compartir contenido entre los miembros del equipo, como compartir pantalla, imágenes, texto, entre otros.

 	
**Requirements Management** <br>
- Notion: https://trello.com/
Para el apartado de requirements, consideramos que la mejor opción era Notion, debido a que con la diversidad de plantillas permitía colaborar de manera muy práctica en el product backlog, además de ser muy fácil de usar. Esta aplicación es gratuita y solo necesitamos registrarnos para utilizarla
 	
**Product UX/UI Design**
- UXPressia: https://uxpressia.com/
Se empleó esta herramienta para la creación de los User Personas, el User Journey Map, Empathy Map. Lo usamos por su facilidad para poder llevar a cabo el desarrollo de estos artefactos debido a su variedad de plantillas. Es gratuito y colaborativo solo es necesario un registro para su uso.
 
- Miro (https://miro.com/es/)
Miro ha sido empleado en el desarrollo de los escenarios mapping y escenario mapping para los dos segmentos objetivos.
 
- Figma: https://www.figma.com/
Esta herramienta fue de vital importancia para la creación de los wireframes, mockups y mobile applications prototyping de manera colaborativa. Asimismo, su acceso es gratuito al contar con una cuenta registrada.
 
- Color Mania (https://www.blacksunsoftware.com/colormania.html)
Color Mania fue empleado en la selección de la paleta de colores para el desarrollo del diseño de la web.
 
**Software Development** <br>
- Landing Page
El desarrollo del landing page se realizó con las siguientes herramientas: HTML5, CSS3 y JavaScript.
 
**IDE’s de desarrollo**
 
- Visual Studio Code https://code.visualstudio.com/ 
Este IDE es altamente versátil y está diseñado para proporcionar una experiencia de desarrollo eficiente y personalizable. Cuenta con una amplia variedad de extensiones disponibles.

**Software testing**
- Para las pruebas de testeo software, de  la landing page, se utilizó los distintos navegadores web tales como Google Chrome (https://www.google.com/chrome/), Microsoft Edge (https://www.microsoft.com/en-us/edge) y Mozilla Firefox (https://www.mozilla.org/en-US/firefox/browsers/). Estos navegadores son gratuitos. 
 
**Software Documentation**
- Google Drive (https://www.google.com/intl/es-419_pe/drive/)
Empleamos Google Drive para tener un documento donde registrar los archivos del proyecto. Principalmente, utilizamos la herramienta de Google Docs para desarrollar los informes a entregar.
 
- Lucidchart: https://www.lucidchart.com/
Fue empleada para el desarrollo de diagramas de clases UML. Debido a la facilidad de crear diversos diagramas y la facilidad para colaborar. Asimismo, funciona en el navegador y hace falta tener una cuenta para acceder a esta.
 
- Structurizr: https://structurizr.com/
El uso de esta herramienta fue para la creación de los diagramas C4 debido a su facilidad. Para usar esta aplicación web es necesario tener una cuenta registrada.
 

### 5.1.2. Source Code Management

El manejo y registro de las modificaciones de nuestra landing page y este documento es manjeada mediante una organización en Github

- **Oragnization:** https://github.com/Gianfranco4991/BusinessPRO.git
- **Landing Page Repository:** https://github.com/Salvlormonch1/planifi.github.io
- **Report Repository:** https://github.com/Gianfranco4991/BusinessPRO

Adicionalmente, para mejorar el control de nnuestro proyecto usamos GitFlow para la creación de ramas y cambios en el código fuente. Es por ello que se manejan dos ramas principales: `main`, `develop`.

- **MAIN:** La rama `main` almacena el historial oficial de las publicaciones de nuestro repositorio listas para producción.
- **DEVELOP:** Esta rama sirve para integrar las características *(features)*.

    En nuestro caso hemos decidido implementar la rama `'develop'`.

    Esta rama es la rama principal donde se integra todas las características. Cuando se completa una característica, se fusionan con `'develop'`. Todas las rams de características deben fusionarse con `'develop'`.

    Ejemplo de flujo de trabajo con GitFlow:

    1. Se crea una rama de `"feature"` a partir de la rama develop
    2. Se trabaja en la rama de `'feature'`
    3. Se hace un merge de la rama de `'feature'` a la rama develop

**RAMAS AUXILIARES:**
- **Feature:** Para desarrollar nuevas funcionalidades o mejoras a partir de la rama develop y juntarlas con ellas al terminar. Estas ramas permiten trbajar en el código sin afectar a la estabilidad de la rama principal, en este caso `'develop'`. Y facilitan la revisión y el control de las características antes de integrarlas.
  
  Para la implementación de las ramas `'features'`, nosotros hemos implementado la siguiente nomenclatura: `'feature/feature-name'`.

  Donde:
    - **Feature:** Es el nombre de la rama.
    - **Feature-name:** Es el nombre de la características que se está desarrollando.
  
  Ejemplo Report:
    - `'feature/chapter-1.1'`. Indicando el capitulo a implementar.

  Ejemplo Landing Page:
    - `'feature/html-structure'`. Indicando la sección a implementar.

### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

En esta sección, se describen los pasos para configurar y desplegar la landing page utilizando Visual Studio Code. Estos pasos son cruciales para asegurar que la aplicación web esté disponible y funcione sin problemas para los usuarios finales.

- Configuración del Entorno de Desarrollo:

Instalar y configurar Visual Studio Code según las preferencias y necesidades del proyecto.

Instalar extensiones útiles para el desarrollo web, como "HTML CSS Support" y "Live Server", que faciliten la creación y visualización de la landing page.

<img src="static/img/Chapter 5/img-software-dep-1.png" alt="Software Deployment 1" style="width: 65;"></img>

<img src="static/img/Chapter 5/img-software-dep-2.png" alt="Software Deployment 2" style="width: 65;"></img>

- Desarrollo de la Landing Page:

Crear los archivos HTML y CSS necesarios para la landing page utilizando Visual Studio Code.

<img src="static/img/Chapter 5/img-software-dep-3.png" alt="Software Deployment 3" style="width: 65;"></img>

<img src="static/img/Chapter 5/img-software-dep-4.png" alt="Software Deployment 4" style="width: 65;"></img>

<img src="static/img/Chapter 5/img-software-dep-5.png" alt="Software Deployment 5" style="width: 65;"></img>

- Despliegue del Software:

Implementar la landing page en el servidor de producción utilizando Visual Studio Code y las herramientas de implementación integradas.

<img src="static/img/Chapter 5/img-software-dep-6.png" alt="Software Deployment 6" style="width: 65;"></img>

<img src="static/img/Chapter 5/img-software-dep-7.png" alt="Software Deployment 7" style="width: 65;"></img>

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
  <table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 1</td>
  </tr>
  <tr>
    <th>Sprint Planning Date</th>
    <td>2024-04-10</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>04:00 PM</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>Servidor de Discord del Equipo</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td>Gianfranco Luna</td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>Gianfranco / Rodrigo / Ramón / Ricardo/ Carito </td>
  </tr>
  <tr>
    <th>Sprint Review Summary</th>
    <td>En esta entrega, no hay un Sprint anterior, por lo tanto, no hay resúmen del Sprint.</td>
  </tr>
  <tr>
    <th>Sprint Retrospective Summary</th>
    <td>En esta entrega, no hay un Sprint anterior, por lo tanto, no hay resúmen del Sprint.</td>
  </tr>
  <tr>
    <th>Sprint Goal</th>
    <td>La meta de este Sprint es el funcionamiento de la Landing Page, tanto su visualización, el acceso a las redes sociales, el traslado en la Landing Page y la visualización de los canales de comunicación de la empresa.</td>
  </tr>
  <tr>
    <th>Sprint Velocity</th>
    <td>7 Velocity</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>7 Story points</td>
  </tr>
</table>
- 5.2.1.2. Sprint Backlog 1.
<table border="1">
  <tr>
    <th>Sprint #</th>
    <th>User Story</th>
    <th>Work-item/Task</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status (To-do / In-Process / To-Review / Done)</th>
  </tr>
  <tr>
    <td rowspan="6">Sprint 1</td>
    <td rowspan="6">US08: Informacion presentada en el landing page</td>
    <td>TA01</td>
    <td>#182062223</td>
    <td>Agregar sección de about the team</td>
    <td>Se creará un botón que dirija a la seccion about the team.</td>
    <td>2</td>
    <td>Carito</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>#182062223</td>
    <td>Añadir tarjetas de información</td>
    <td>Para la sección de ‘conócenos’, se añadirá un listado de tarjetas (imágenes con texto) que muestren los beneficios que ofrece la app.</td>
    <td>4</td>
    <td>Carito</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA03</td>
    <td>#182062223</td>
    <td>Añadir tarjetas de servicios para clientes</td>
    <td>Se añadirá un listado de tarjetas (imágenes con texto) que muestren los servicios que ofrece la app.</td>
    <td>4</td>
    <td>Carito</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>TA05</td>
    <td>#182062223</td>
    <td>Añadir datos resaltantes</td>
    <td>Agregar una sección que cuente con los datos numéricos y/o estadísticos de las empresas.</td>
    <td>2</td>
    <td>Ramón</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA06</td>
    <td>#182062223</td>
    <td>Agregar encabezados de secciones</td>
    <td>Colocar un encabezado que indique en qué sección se encuentra el usuario.</td>
    <td>1</td>
    <td>Ramón</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA01</td>
    <td>#182062235</td>
    <td>Añadir sección ‘contáctanos’</td>
    <td>Se creará una sección al final del Landing Page que esté dedicada totalmente al contacto con la empresa.</td>
    <td>2</td>
    <td>Carito</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">Sprint 1</td>
    <td rowspan="2">HU32: Traslación en el Landing Page</td>
    <td>TA01</td>
    <td>#182267507</td>
    <td>Crear encabezado del Landing Page</td>
    <td>Se añadirá un encabezado que contenga el logo de SwiftShip al inicio de la página.</td>
    <td>1</td>
    <td>Ramón</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>#182267507</td>
    <td>Programar botones de secciones en el encabezado</td>
    <td>Se crearán botones en el inicio que te lleven a distintas secciones de la página.</td>
    <td>3</td>
    <td>Carito</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">Sprint 1</td>
    <td rowspan="1">HU33: Acceso a redes sociales</td>
    <td>TA01</td>
    <td>#182267516</td>
    <td>Añadir botones de redes sociales</td>
    <td>Se añadirán botones que te lleven a las distintas redes sociales de la página en el footer.</td>
    <td>3</td>
    <td>Carito</td>
    <td>Done</td>
  </tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review
#### 5.2.1.4. Testing Suite Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review

El Execution Evidence for Sprint Review se enfoca en recopilar y presentar evidencia concreta del progreso realizado durante el sprint, centrándose específicamente en la elaboración de la landing page. Esta evidencia es crucial para demostrar cómo se están cumpliendo los objetivos del sprint, qué elementos han sido completados y cómo se alinean con los requisitos del cliente. 

<img src="static/img/Chapter 5/img-evidence-1-sprint-1.png" alt="Evidence Sprint Review 1" style="width: 65;"></img>v

<img src="static/img/Chapter 5/img-evidence-2-sprint-1.png" alt="Evidence Sprint Review 2" style="width: 65;"></img>

<img src="static/img/Chapter 5/img-evidence-3-sprint-1.png" alt="Evidence Sprint Review 3" style="width: 65;"></img>

<img src="static/img/Chapter 5/img-evidence-4-sprint-1.png" alt="Evidence Sprint Review 4" style="width: 65;"></img>

<img src="static/img/Chapter 5/img-evidence-5-sprint-1.png" alt="Evidence Sprint Review 5" style="width: 65;"></img>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Para esta entrega solo se realizó el Landing Page, por lo que no hubo implementación de APIs.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

El objetivo de este primer sprint fue el desarrollo de la Landing Page. Para esto, utilizamos GitHub y GitHub Pages. El proceso fue el siguiente:

1. Un miembro del equipo creó una organización en GitHub y se le envió una invitación a cada uno de los otros miembros para que se puedan unir.

<img src="static/img/Chapter 5/img-invitation-github.png" alt="GitHub Invitation" style="width: 65;"></img>

2. Luego, se creó un repositorio para el desarrollo del trabajo, tanto del informe como de la Landing Page.

<img src="static/img/Chapter 5/img-repository.png" alt="Repository" style="width: 65;"></img>

3. A continuación, cada uno fue realizando modificaciones en los archivos, a través de los commits.

<img src="static/img/Chapter 5/img-commits.png" alt="Commits" style="width: 65;"></img>

4. Finalmente, desplegamos la Landing Page en GitHub Pages, a la que se puede ingresar mediante el siguiente link: [https://salvlormonch1.github.io/planifi.github.io/](https://salvlormonch1.github.io/planifi.github.io/)

<img src="static/img/Chapter 5/img-landing-page.png" alt="Landing Page" style="width: 65;"></img>

#### 5.2.1.8. Team Collaboration Insights during Sprint

A continuación, se mostrarán capturas de los Insights del GitHub para evidenciar la participación de todos los miembros del grupo:
<img src="static/img/Chapter 5/img-insights.png" alt="Insights" style="width: 65;"></img>
