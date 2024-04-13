# Capítulo IV: Product Design

## 4.1. Style Guidelines
## 4.1.1. General Style Guidelines
## 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
## 4.2.1. Organization Systems
## 4.2.2. Labeling Systems
## 4.2.3. SEO Tags and Meta Tags
## 4.2.4. Searching Systems
## 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
## 4.3.1. Landing Page Wireframe
## 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
## 4.4.1. Web Applications Wireframes
## 4.4.2. Web Applications Wireflow Diagrams
## 4.4.2. Web Applications Mock-ups
## 4.4.3. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
## 4.6.1. Software Architecture Context Diagram

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-system-context.png" alt="System Context Diagram" style="width: 65;"></img>
</div>

## 4.6.2. Software Architecture Container Diagrams

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-component-container.png" alt="Container Diagram" style="width: 65;"></img>
</div>

## 4.6.3. Software Architecture Components Diagrams

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-component-project-follow-up-BC.png" alt="Proyect Follow Up Component Diagram" style="width: 65;"></img>
</div>

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-component-register-BC.png" alt="Register Component Diagram" style="width: 65;"></img>
</div>

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-component-report-BC.png" alt="Report Component Diagram" style="width: 65;"></img>
</div>

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-component-spreadsheet-BC.png" alt="Spreadsheet Component Diagram" style="width: 65;"></img>
</div>

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-component-suscription-BC.png" alt="Subscription Component Diagram" style="width: 65;"></img>
</div>

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-component-worker-follow-up-BC.png" alt="Worker Follow Up Component Diagram" style="width: 65;"></img>
</div>

## 4.7. Software Object-Oriented Design
## 4.7.1. Class Diagrams

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-class-diagram.png" alt="Class Diagram" style="width: 65;"></img>
</div>

## 4.7.2. Class Dictionary

Para la realización del diagrama, se han utilizado las siguientes clases, junto con sus respectivos atributos y métodos:

- app: La clase principal. Sus atributos consisten en la planilla, suscripción y un arreglo con todos los proyectos del usuario. Sus métodos, por otra parte, permiten ver la planilla con los trabajadores y sus datos, la lista de proyectos, ver los detalles de la suscripción y realizar un reporte financiero.
- expense: La clase que representa un gasto de la empresa. Sus atributos almacenan el valor del monto del gasto, la descripción y la fecha. Sus métodos son getters que permiten obtener dicha información.
- financial-report: La clase que representa el reporte financiero que realiza la app. Su único método es un arreglo que contiene todos los gastos de la empresa y sus métodos permiten obtener dicho arreglo de gastos, ver la lista de gastos y ver el reporte financiero detallado.
- normal-plan: La clase que representa el plan de suscripción normal o básico. Contiene atributos que tienen valores predefinidos para dicho plan de suscripción, tales como el precio y cantidad máxima de trabajadores y proyectos. Sus métodos son getters que devuelven el valor de cada atributo.
- plan: Una interfaz que representa el plan de suscripción. Tiene tres métodos que retornan el precio, la cantidad máxima de trabajadores y la cantidad máxima de proyectos que admite cada suscripción.
- premium-plan: La clase que representa el plan de suscripción premium. Contiene atributos que tienen valores predefinidos para dicho plan de suscripción, tales como el precio y cantidad máxima de trabajadores y proyectos. Sus métodos son getters que devuelven el valor de cada atributo.
- project: La clase que representa a un proyecto de la empresa. Sus atributos consisten en los datos del proyecto, como la descripción y el nombre, y un arreglo de trabajadores que guarda a todos los trabajadores de la empresa que han aportado a dicho proyecto. Sus métodos incluyen getters para cada atributo y otros dos para mostrar una lista de los trabajadores de dicho proyecto y para buscar un trabajador en particular.
- projects: La clase que representa el conjunto de todos los proyectos del usuario. Contiene un arreglo de proyectos y métodos para ver todos los proyectos o buscar uno en específico.
- register-login: El registro e inicio de sesión. Contiene como único atributo un arreglo de usuarios y sus métodos son los de registar un usuario nuevo e iniciar sesión con uno existente.
- spreadsheet: La clase que representa a la planilla. Contiene un arreglo de trabajadores como atributo y métodos para acceder a la lista completa de trabajadores o para buscar a uno o algunos en particular.
- subscription: La clase que representa la suscripción del usuario en la app. Su único método es el que contiene los datos del plan de suscripción y mediante sus métodos puede suscribirse, cancelar la suscripción o cambiar de tipo de suscripción.
- user: La clase que representa al usuario. Entre sus atributos se encuentran su id, nombre de usuario, contraseña para ingresar, email y su respectiva planilla, suscripción y proyectos. En cuanto a sus métodos, se encuentran los getters para cada uno de sus atributos.
- worker: La clase que representa al trabajador. Sus atributos son los datos del trabajador, tales como su nombre, email, número telefónico, dirección, puesto, etc. También hay atributos que contienen las horas regulares y horas extra trabajadas y otro que contiene un número que representa el rendimiento, el cual es medido por alguno de sus supervisores y también es un dato importante. Los métodos son los getters por cada atributo y dos métodos extra. Uno para mostrar el detalle de las horas totales trabajadas y otro que muestre el rendimiento en base a dichas horas.


## 4.8. Database Design
## 4.8.1. Database Diagram

<div style="text-align: center; margin-top: 20px;">
        <img src="static/img/Chapter 4/img-database-model.png" alt="Database Diagram" style="width: 65;"></img>
</div>
