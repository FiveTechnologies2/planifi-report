# Capítulo IV: Product Design

## 4.1. Style Guidelines
Para optimizar la experiencia de los usuarios en la gestión de planillas, se propone un diseño de interfaz atractivo y responsivo tanto en la web como en la aplicación móvil. La interfaz tendrá colores coherentes, imágenes de alta calidad y una navegación intuitiva para facilitar el uso. La experiencia de usuario se simplificará con flujos de trabajo eficientes para la carga de datos, gestión de empleados y cálculos automáticos de nómina. Esto permitirá a los usuarios ahorrar tiempo y esfuerzo en la gestión de sus planillas. Se incorporarán recursos visuales e infografías para facilitar la comprensión y análisis de la información. Las infografías proporcionarán una representación visual de los datos de la nómina, lo que permitirá a los usuarios tomar decisiones más informadas. En definitiva, estas estrategias buscan proporcionar una experiencia práctica y amigable para la gestión de planillas, simplificando el proceso y permitiéndote enfocarte en lo que realmente importa.

### 4.1.1. General Style Guidelines

**BRANDING**

 Nuestro logo representa nuestra formalidad y compromiso con los usuarios, consiste en la inicial del nombre de nuestro producto acompañado del nombre y una de nuestro eslogan del producto

 <img src="static/img/Chapter 4/img-Planifi.png" alt=" " style="width: 45;"></img>
 

 **TYPOGRAPHY**

 Para la tipografía, se seleccionó la fuente Open Sans. Esta elección se basa en su capacidad para captar la atención del usuario, a la vez que mantiene una alta legibilidad y un aspecto estético agradable.

 <img src="static/img/Chapter 4/img-opensans.png" alt=" " style="width: 65;"></img>


 **PALETA DE COLORES**

 En cuanto a la elección de nuestra paleta de colores, decidimos usar los siguientes colores:

\#57C600

<img src="static/img/Chapter 4/img-57C600.png" alt=" " style="width: 65;"></img>

\#8EF988

<img src="static/img/Chapter 4/img-8EF988.png" alt=" " style="width: 65;"></img>

\#A2D5F2

<img src="static/img/Chapter 4/img-A2D5F2.png" alt=" " style="width: 65;"></img>

\#D4A5A5

<img src="static/img/Chapter 4/img-D4A5A5.png" alt=" " style="width: 65;"></img>

\#F7CAC9

<img src="static/img/Chapter 4/img-F7CAC9.png" alt=" " style="width: 65;"></img>

\#FFE4B5

<img src="static/img/Chapter 4/img-FFE4B5.png" alt=" " style="width: 65;"></img>
 
 **COLORES NEUTROS**
Nuestros colores neutros son los siguientes:

\#000000

<img src="static/img/Chapter 4/img-000000.png" alt=" " style="width: 65;"></img>

\#FFFFFF

<img src="static/img/Chapter 4/img-FFFFFF.png" alt=" " style="width: 65;"></img>

\#E5E5E5

<img src="static/img/Chapter 4/img-E5E5E5.png" alt=" " style="width: 65;"></img>

### 4.1.2. Web Style Guidelines 

En Planifi, hemos elegido cuidadosamente nuestros elementos de estilo web para crear una experiencia que refleje la escencia de nuestra plataforma y atienda a las necesidades de nuestra audiencia en la industria comercial.

**COLORES BASE**

La elección de estos colores son las siguientes: 
- El verde representa frescura, crecimiento y renovación de energía
- El salmón representa inocencia y bondad
- El celeste representa serenidad y confianza
- El amarillo claro representa energía y creatividad
- El rosado boragoña tiende a alejar las preocupaciones y es acompañado con suavidad

**COLORES NEUTROS**

La elección de colores neutros fue la siguiente:
- Negro que representa elegancia y el poder
- Blanco que representa creatividad, imparcialidad y paz

**ESTILO DE LETRAS**

Optamos por una tipografía formal y legible. Nuestra elección se basa en la necesidad de una comunicación clara y efectiv en la plataforma. Valoramos la legibilidad y accesibillidad, ya que queremos que todos los usuarios puedan interactuar sin problemas.

## 4.2. Information Architecture

### 4.2.1. Organization Systems 
El principal propósito de este punto es darnos una guía y apoyo para poder clasificar la información de nuestra página web de forma que cuando vaya a hacer la implementación, el sistema sea accesible y de fácil uso para los usuarios. En nuestro caso, utilizaremos un tipo de organización es de manera jerárquica, es decir, se ordena desde lo más importante a lo más básico. Al momento de ingresar en parte de "Compra", lo primero que se encontrará con los planes que tenemos, contamos con tres planes, los cuales son desde el más básico hasta el premium. Para ello usamos el tipo de organización secuencial, dado a que primero se ingresa al botón de compra. Posteriormente, se elije el plan y recién se puede llegar al producto. Mientras que nnuestro tipo de categorización para algunos puntos va a ser por tópicos.

### 4.2.2. Labeling Systems 

En nuestro caso las etiquetas de información se representarán como palabras en el idioma español, usando siempre la palabra más adecuada para el completo entendimieneto del usuario. Las etiquetas más importantes de nuestra aplicación son:

- COMPRAR: Aqui se encontrarán nuestros planes, el básico, estandar y el premium
- ¿Quiénes somos?: Donde se encontrará información sobre nuestra startup y comentarios importantes
- Beneficios: Se muestra nuestros puntos fuertes
- Ubicación: Para saber de donde se conectarán los usuarios para un mejor manejo del mantenimiento
- Contacto: En caso de necesitar ayuda o soporte.


### 4.2.3. SEO Tags and Meta Tags 

**Landing Page**

Nuestra página de inicio contará con los siguientes Tags:

~~~
<header>
    <a href="#" class="logo">Planifi</a>
        <ul class="navbar">
            <li><a href="#quienes-somos">¿Quiénes somos?</a></li>
            <li><a href="#beneficios">Beneficios</a></li>
            <li><a href="#ubicacion">Ubicación</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
</header>
~~~

### 4.2.4. Searching Systems 
Nuestro sistema de busqueda va a ser de una manera eficiente e intuitiva de realizar para nuestros usuarios. Como nuestro producto cuenta con tres planes de los cuales en el plan básico, tendra que buscar en la comunidad. En el plan estandar, de un soporte. Y por último, el plan premium, contará tanto del soporte como de un tutorial guiado paso a paso para poder realizar dichas acciones.

### 4.2.5. Navigation Systems 
El sistema que permitirá a los usuarios ir entre las distintas secciones de nuestra página será una barra superior en nuestro landing page, la cual estará conformada por los títulos de cada sección.

## 4.3. Landing Page UI Design
Nuestra decisión del diseño y la arquitectura es usar una forma más minimalista y tratar de llamar la atención al cliente por el producto.

### 4.3.1. Landing Page Wireframe 
Wireframe 1
<img src="static/img/Chapter 4/img-wireframe1.png" alt=" " style="width: 65;"></img>

Wireframe 2
<img src="static/img/Chapter 4/img-wireframe2.png" alt=" " style="width: 65;"></img>

Wireframe 3
<img src="static/img/Chapter 4/img-wireframe3.png" alt=" " style="width: 65;"></img>

Wireframe 4
<img src="static/img/Chapter 4/img-wireframe4.png" alt=" " style="width: 65;"></img>

Wireframe 5
<img src="static/img/Chapter 4/img-wireframe5.png" alt=" " style="width: 65;"></img>

Para poder ver el wireframe completo, este es el link de Figma -> [Figma](https://www.figma.com/file/YxrOLUAqkGsL86OvtCETzt/Planifi-Wireframe?type=design&node-id=0%3A1&mode=design&t=0KnNllAIDZqRZnLP-1) 

### 4.3.2. Landing Page Mock-up 
Mock-up 1
<img src="static/img/Chapter 4/img-mockup1.png" alt=" " style="width: 65;"></img>

Mock-up 2
<img src="static/img/Chapter 4/img-mockup2.png" alt=" " style="width: 65;"></img>

Mock-up 3
<img src="static/img/Chapter 4/img-mockup3.png" alt=" " style="width: 65;"></img>

Mock-up 4
<img src="static/img/Chapter 4/img-mockup4.png" alt=" " style="width: 65;"></img>

Mock-up 5
<img src="static/img/Chapter 4/img-mockup5.png" alt=" " style="width: 65;"></img>

Para poder ver el Mock-up completo, este es el link de Figma -> [Figma](https://www.figma.com/file/V8WMiF3a2LgTBpJKDA6flY/Mockup?type=design&mode=design&t=0KnNllAIDZqRZnLP-1) 

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes 

<img src="static/img/Chapter 4/img-webaplicationwireframe.png" alt=" " style="width: 65;"></img>

Para poder ver el web application wireframe completo, este es el link de Figma -> [Figma](https://www.figma.com/file/YxrOLUAqkGsL86OvtCETzt/Planifi-Wireframe?type=design&node-id=0%3A1&mode=design&t=0KnNllAIDZqRZnLP-1) 

### 4.4.2. Web Applications Wireflow Diagrams

<img src="static/img/Chapter 4/img-wireflow.png" alt=" " style="width: 65;"></img>

Para poder ver mejor el Wireflow, este es el link del lucidchart -> [Lucidchart](https://lucid.app/lucidchart/1d7753bc-2ef3-4485-8b8c-cfd7e119defb/edit?view_items=7crsvUt5MiZ_&invitationId=inv_738c0520-b232-4d6d-bbca-a1c0eba60e98)

### 4.4.2. Web Applications Mock-ups

<img src="static/img/Chapter 4/img-webaplicationmockup.png" alt=" " style="width: 65;"></img>

Para poder ver el Mock-up completo, este es el link de Figma -> [Figma](https://www.figma.com/file/V8WMiF3a2LgTBpJKDA6flY/Mockup?type=design&mode=design&t=0KnNllAIDZqRZnLP-1) 

### 4.4.3. Web Applications User Flow Diagrams

<img src="static/img/Chapter 4/img-userflow.png" alt=" " style="width: 65;"></img>

Para poder ver el Mock-up completo, este es el link de Figma -> [Figma](https://lucid.app/lucidchart/5de1ec5e-e8cf-4908-bb2c-128ac71bb507/edit?viewport_loc=-3774%2C-1589%2C6470%2C2610%2C0_0&invitationId=inv_912178d8-2592-4cee-bb1e-576a04f2c013) 

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
