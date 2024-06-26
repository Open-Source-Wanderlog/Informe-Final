# Capítulo IV: Product Design

## 4.1. Style Guidelines

Las guías de estilo serán la base para dar forma a nuestro producto, utilizando patrones que consideren los aspectos de arquitectura de la información y accesibilidad necesarios para la implementación exitosa de WanderLog tanto en una Landing Page como en una Aplicación Web.

### 4.1.1. General Style Guidelines

- **Branding**: Con el propósito de dar estilo y reconocimiento a nuestra aplicación web que posee una variedad de ajustes en los temas de colores, fuentes tipográficas y en el aspecto de diseño estructural, para el desarrollo correcto de nuestro banding hemos tomado en cuenta cada una de las características de nuestra solución .

- **Typography**: El tipo de tipografía escogida, sucesor de Raleway, resalta elegancia y modernidad. Ofreciendo así, una visión amigable y fácil de leer para nuestra plataforma.

- **Logo**: El logo de WanderLog es una combinación de un globo terráqueo y una brújula, que simboliza la idea de viajar y explorar nuevos lugares.

![El logo de WanderLog](https://github.com/Open-Source-Wanderlog/images-front/blob/main/imgs/img01-logo.png?raw=true)

- **Colors**: La paleta de colores de WanderLog está compuesta por tonos azules y blancos. El azul representa la confianza, la seguridad y la eficiencia, mientras que el blanco simboliza la pureza y la simplicidad.
![La paleta de colores de WanderLog](https://github.com/Open-Source-Wanderlog/images-front/blob/main/imgs/img02-colors.png?raw=true)
- **Spacing**:
El espaciado de la aplicación es un factor importante, ya que nuestra aplicación tiene como objetivo dar un aspecto de control y sencillez. Por lo tanto, el espaciado de las secciones y funcionalidades tienen un orden determinado, el cual el usuario podrá ver cada una de ellas de forma clara y detallada.

- **Dimension**:
La dimensión para adoptar en cuanto al diseño es un tono formal y entusiasta, aplicando colores profesionales como el azul presentado y un tono entusiasta con colores naranjas. Asimismo, para el diseño de los íconos y formas adoptaremos diseños amigables al usuario utilizando bordes curvos en su mayoría.

### 4.1.2. Web Style Guidelines

- **Estudio de marca**: Para entender a nuestra marca, tuvimos que familiarizarnos con nuestro público objetivo, aquí vemos nuestro valores, misión y visión para transportarlos a la parte visual. 

- **Reglas del Logotipo**: Se definirán un tamaño mínimo y uno normal y se variará con un estilo de logos de día y noche para diferenciar las estadías en que se encuentre el usuario.

- **Paleta de colores**: De manera similar se implementará una paleta de colores de día y de noche para que vaya acorde a el modo que el usuario elija por predeterminado en su aparato móvil.

- **Tipografía**: Se define los tipos de letra para los encabezados dependiendo de la importancia de estos y otros para el texto del cuerpo dependiendo de los subtemas a los que se esté ingresando en la aplicación.

- **Diseño y espaciado**: Se diseñará una ventana que tenga administrada los íconos y subtemas con un espaciado que no sienta al usuario en un ambiente demasiado frustrante y deje un toque más liberal y fresco. Íconos: Se crean íconos principales que guiarán al usuario en la búsqueda de su objetivo que tenga puesto en la mira en ese momento; tales como: Búsqueda, cerrar, ubicación, llave de casa.

- **Ilustraciones e imágenes**: Para el uso de imágenes y/o ilustraciones se utilizará un margen redondo, además que será fotosensible para la vista del usuario. Estos se utilizarán para ver el interior de la casa.

- **Configuraciones Estilísticas**: Son las consideraciones que se tomarán en cuenta desde que se definen para darle un estilo único y personalizado dependiendo del usuario modelo.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

Se aplicará los siguientes organizadores visuales:

- **Forma jerárquica**: Se usará para mostrar las opciones de filtrado de paquetes, según el plan del usuario y sus preferencias.

- **Forma matricial**: Se usará para que el usuario navegue a través de un mapa para que pueda conocer la ubicación exacta de los hoteles, restaurantes, lugares turísticos.

- **Organización secuencial**: Al momento de comenzar el registro de usuario o el proceso de formar un paquete, se mostrará en un orden establecido para imponer orden.

- **Alfabético**: Este esquema se usará en el orden en el que salen los destinos disponibles, o los lugares turísticos con paquetes disponibles.

- **Cronológico**: El esquema cronológico es importante para determinar desde qué fechas están disponibles los paquetes de viaje.

- **Por tópicos**: El siguiente esquema es crucial para ordenar los tipos de destino que el usuario desea, en base a sus preferencias.

- **Según audiencia**: La información se adecua al tipo de audiencia que el usuario está usando al momento de ingresar a la aplicación o web.


### 4.2.2. Labeling Systems

Asegurando que, en WanderLog, los usuarios puedan utilizar el aplicativo de forma clara y concisa, se ha empleado un sistema de etiquetado.

**Menú Principal**
- **Sobre Nosotros:** Información sobre la misión, visión y equipo de WanderLog. 
- **Planes:** Diferentes tipos de planes de viaje disponibles (turísticos y escolares).	
- **Noticias:** Últimas noticias y actualizaciones relacionadas con viajes.	
- **Contáctanos:** Información de contacto para asistencia y consultas.	
- **Registrarme:** Formulario para nuevos usuarios.	
- **Iniciar Sesión:** Acceso para usuarios registrados.

**Secciones del Contenido**
- **Frase Principal:** "Descubre el mundo sin preocupaciones de manera eficiente, evitando el estrés de planificar un viaje."	
- **Tour de la Página:** "¿Desea recibir un tour por nuestra página?"
  - **Claro**
  - **No gracias**
- **Sobre Nosotros:** "WanderLog surge para ayudar a aquellas personas que necesitan simplificar la planificación de sus viajes de principio a fin..."	
- **Planes:**	
  - **Turístico:** "Para personas que desean explorar las distintas partes del mundo y aprender sobre sus culturas."
  - **Escolar:** "Para viajes de promoción para colegios que desean disfrutar de un viaje inolvidable."
- **Noticias:** "¿Desea recibir las noticias más relevantes sobre vuelos y descuentos exclusivos a su correo electrónico?"
- **Contáctanos:**
  - **Correos** 
  - **Teléfonos** 
  - **Dirección**
- **Testimoniales:** "Increíble! Nunca había tenido un viaje tan bien organizado..."	
- **Redes Sociales:** "Síguenos en nuestras redes sociales"

### 4.2.3. SEO Tags and Meta

WanderLog implementará SEO Tags y Meta Tags para aumentar el rendimiento y visibilidad en las principales páginas del Landing Page y aplicativo web.

**Title**
```html
<title>WanderLog - Planifica Tu Viaje de Manera Fácil y Eficiente</title>
```

**Meta Tags Description**
```html
<meta name="description" content="Descubre el mundo sin preocupaciones con WanderLog. Planifica tus viajes de principio a fin de manera fácil y eficiente, y disfruta de tus vacaciones al máximo.">
```
**Author**
```html
<meta name="author" content="WanderLog Team">
```
- **Title:** El título de la página, claro, conciso y conteniendo palabras clave relevantes. 
- **Meta Description:** La descripción ayuda a los usuarios y a los motores de búsqueda a entender de qué trata la página. 
- **Author:** Atribuye el contenido a los creadores, proporcionando transparencia y credibilidad.



### 4.2.4. Searching Systems

WanderLog emplea un sistema de búsqueda que proporciona una experiencia intuitiva en su Landing Page, necesario para encontrar la información importante de manera rápida.

**Planes Turísticos**
- **Selección de Destino:** El usuario selecciona su destino turístico establecido. A partir de esta selección, se despliega una interfaz que muestra vuelos, hoteles y atracciones disponibles en el destino seleccionado. 
- **Interfaz Intuitiva:** La interfaz está diseñada para presentar los resultados de manera clara y organizada, permitiendo al usuario explorar fácilmente las opciones disponibles.

**Viajes Escolares**
- **Selección de Paquete:** El usuario selecciona directamente un paquete escolar ya establecido. Estos paquetes incluyen destinos y actividades predefinidas, eliminando la necesidad de aplicar filtros adicionales.	
- **Presentación Clara:** Los paquetes escolares se muestran con descripciones detalladas y precios, facilitando la selección directa del paquete deseado.

**Resultados de la Búsqueda**
- **Presentación de Resultados:** Los resultados de búsqueda se presentan en una lista organizada, con cada categoría (vuelos, hoteles, atracciones) mostrada por separado en el caso de los planes turísticos.	
- **Tarjetas de Resultados:** Cada resultado se presenta en una tarjeta individual que incluye una imagen representativa, el nombre del servicio (vuelo, hotel, atracción), una breve descripción, precio y un botón de acción para ver más detalles.

### 4.2.5. Navigation Systems

WanderLog emplea un sistema de navegación en la Landing page de WanderLog para brindar una experiencia de usuario fluida, permitiendo a los usuarios encontrar fácilmente la información que buscan.

**Estructura del Menú**
- **Sobre Nosotros:** Enlace a una sección que describe la misión y visión de WanderLog, proporcionando contexto sobre los servicios ofrecidos.
- **Planes:** Acceso a una sección donde se detallan los diferentes tipos de paquetes de viaje disponibles (Turístico, Escolar, etc.).
- **Noticias:** Enlace a una sección para suscribirse a las últimas noticias y actualizaciones de WanderLog.
- **Contactarnos:** Información de contacto para soporte y consultas.
- **Registrarme:** Enlace para que nuevos usuarios creen una cuenta en WanderLog.
- **Iniciar Sesión:** Acceso directo para usuarios registrados.

**Diseño del Menú**
- **Fijo en la Parte Superior:** El menú principal se encuentra fijo en la parte superior de la página para garantizar un acceso constante y fácil navegación sin importar en qué parte de la página se encuentren los usuarios.	
- **Claridad Visual:** Los enlaces del menú están claramente delineados y son fáciles de identificar gracias a un diseño limpio y un espaciado adecuado.

**Hero Section**
- **Mensaje Principal:** "Descubre el mundo sin preocupaciones de manera y eficiente, evitando el estrés de planificar un viaje."

**Sobre Nosotros**
- **Descripción:** Breve explicación sobre la misión de WanderLog y cómo ayuda a simplificar la planificación de viajes.	
- **Icono Representativo:** Uso de un icono de avión para reforzar el tema de viajes.

**Planes**
- **Categorías de Paquetes:** Dos opciones principales se presentan con imágenes y descripciones:	
- **Turístico:** Para personas interesadas en explorar diferentes culturas y destinos.	
- **Escolar:** Para viajes de promoción y experiencias educativas.	
- **Enlaces Visuales:** Las imágenes actúan como enlaces visuales que llevan a los usuarios a más detalles sobre cada tipo de paquete.

**Noticias**
- **Suscripción al Boletín:** Formulario sencillo para que los usuarios ingresen su correo electrónico y reciban noticias y descuentos exclusivos. 
- **Call to Action:** Botón "Enviar" claramente identificado.

**Contactarnos**
- **Información de Contacto:** Detalles de correos electrónicos, números de teléfono y dirección física para facilitar la comunicación con los usuarios.	
- **Sección Bien Delineada:** Separada claramente del resto del contenido para facilitar su localización.

**Footer**
- **Testimonios:** Comentarios de usuarios anteriores que destacan la eficacia de WanderLog, proporcionando pruebas sociales y generando confianza. 
- **Redes Sociales:** Enlaces a las cuentas de redes sociales de WanderLog (Twitter, Facebook, Instagram), facilitando la conexión con la comunidad y el seguimiento de actualizaciones.

**Elementos de Accesibilidad**
- **Contraste de Color:** Asegurando que todos los elementos de navegación sean fácilmente distinguibles para usuarios con discapacidades visuales.	
- **Texto Alternativo (Alt Text):** Para todas las imágenes e iconos, asegurando la compatibilidad con lectores de pantalla.	
- **Tamaño de Fuente:** Fuentes claras y de tamaño adecuado para asegurar la legibilidad.

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

El toolbar incluye el logo de la startup y distintos botones, como el de sobre nosotros, planes, noticias, contacto, registrarse e iniciar sesión. 

![alt text](<../assets/imgs/img06-wireframe 1.png>)

El Hero Image incluye un texto descriptivo que captura la atención de los usuarios y los invita a explorar la página. Se acompaña de una imagen representativa.

![alt text](<../assets/imgs/img7-wireframe 2.png>)

"Sobre Nosotros" contiene información sobre la misión y visión de WanderLog, así como un icono representativo.

![alt text](<../assets/imgs/img08-wireframe 3.png>)

"Planes" contiene información sobre los servicios que ofrece WanderLog hacia nuestros segmentos objetivos, siendo los Turistas y Escolares.

![alt text](<../assets/imgs/img09-wireframe 4.png>)

"Noticias" ofrece un medio por el cual el usuario puede ofrecer su correo electrónico para que le lleguen noticias actuales en relación con la startup.

![alt text](<../assets/imgs/img10-wireframe 5.png>)

"Contactanos" contiene los distintos medios de contacto, siendo los correos, teléfonos y dirección de la startup.

![alt text](<../assets/imgs/img11-wireframe 6.png>)

El Footer contiene los medios sociales anexados, siendo Twitter, Facebook e Instagram, además de distintos testimonios de usuarios que usaron el aplicativo web.

![alt text](<../assets/imgs/img 12-wireframe 7.png>)


### 4.3.2. Landing Page Mock-up

El toolbar incluye el logo de la startup y distintos botones, como el de sobre nosotros, planes, noticias, contacto, registrarse e iniciar sesión. 

![alt text](<../assets/imgs/img13-mockup 1.png>)


El Hero Image incluye un texto descriptivo que captura la atención de los usuarios y los invita a explorar la página. Se acompaña de una imagen representativa.

![alt text](<../assets/imgs/img14-mockup 2.png>)

"Sobre Nosotros" contiene información sobre la misión y visión de WanderLog, así como un icono representativo.

![alt text](<../assets/imgs/img15-mockup 3.png>)

"Planes" contiene información sobre los servicios que ofrece WanderLog hacia nuestros segmentos objetivos, siendo los Turistas y Escolares. "Noticias" ofrece un medio por el cual el usuario puede ofrecer su correo electrónico para que le lleguen noticias actuales en relación con la startup. "Contactanos" contiene los distintos medios de contacto, siendo los correos, teléfonos y dirección de la startup. Finalmente, el Footer contiene los medios sociales anexados, siendo Twitter, Facebook e Instagram, además de distintos testimonios de usuarios que usaron el aplicativo web.

![alt text](<../assets/imgs/img16-mockup 4.png>)

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

La pantalla de ingreso permite al usuario realizar un login al aplicativo web ingresando sus datos de correo electrónico y contraseña.

![alt text](<../assets/imgs/img17-app wireframe 1.png>)

La pantalla de Registro permite al usuario crear una nueva cuenta de usuario en WanderLog, la cual podrá emplear en la pantalla de ingreso posteriormente. La interfaz de Home es el apartado central del aplicativo, donde inicial los flujos principales para ambos segmentos escolares y turísticos.

![alt text](<../assets/imgs/img18-app wireframe 2.png>)

La pantalla de elección de paquetes Estudiantiles se centra en brindar a modo de paquete una opción de viajes a un destino en particular que cubre todas las necesidades básicas, como vuelos, hospedaje y atracciones turísticas. La interfaz de Vuelo dentro del plan de viaje permite al usuario visualizar el vuelo seleccionado.

![alt text](<../assets/imgs/img19-app wireframe 3.png>)

La interfaz de Hospedaje dentro del plan de viaje permite al usuario visualizar el hospedaje seleccionado. La interfaz de atracciones dentro del plan de viaje permite al usuario visualizar la atracción turística seleccionada.

![alt text](<../assets/imgs/img20-app wireframe 4.png>)

La pantalla de elección de viajes turísticos se centra en permitir seleccionar opciones de vuelos, hospedajes y atracciones turísticas en base a un destino en particular. La pantalla de perfil permite al usuario visualizar su información personal y los planes de suscripción.

![alt text](<../assets/imgs/img21-app wireframe 5.png>)

### 4.4.2. Web Applications Wireflow Diagrams

Se ha empleado de la herramienta en línea "Figma" para diseñar los Wireflow Diagrams, los cuales permiten combinar representaciones visuales simplificadas de las pantallas del aplicativo con diagramas de flujo, ilustrando cómo los usuarios pueden interactuar con el aplicativo por medio de un flujo de pantallas.

**Link del figma**: https://www.figma.com/file/rP99xLB3zucajdvaxBP7Ax/Untitled?type=design&node-id=0%3A1&mode=design&t=qnaHxqkizVdElFjC-1 

![alt text](<../assets/imgs/img22-wireflow diagram.png>)

### 4.4.3. Web Applications Mock-Ups

La pantalla de ingreso permite al usuario realizar un login al aplicativo web ingresando sus datos de correo electrónico y contraseña. La pantalla de Registro permite al usuario crear una nueva cuenta de usuario en WanderLog, la cual podrá emplear en la pantalla de ingreso posteriormente. 

![alt text](<../assets/imgs/img23-app mockup 1.png>)


La interfaz de Home es el apartado central del aplicativo, donde inicial los flujos principales para ambos segmentos escolares y turísticos. La pantalla de elección de paquetes Estudiantiles se centra en brindar a modo de paquete una opción de viajes a un destino en particular que cubre todas las necesidades básicas, como vuelos, hospedaje y atracciones turísticas. 

![alt text](<../assets/imgs/img24-app mockup 2.png>)

La interfaz de Vuelo dentro del plan de viaje permite al usuario visualizar el vuelo seleccionado. La interfaz de Hospedaje dentro del plan de viaje permite al usuario visualizar el hospedaje seleccionado. 

![alt text](<../assets/imgs/img25-app mockup 3.png>)

La interfaz de atracciones dentro del plan de viaje permite al usuario visualizar la atracción turística seleccionada. La pantalla de elección de viajes turísticos se centra en permitir seleccionar opciones de vuelos, hospedajes y atracciones turísticas en base a un destino en particular. 

![alt text](<../assets/imgs/img26-app mockup 4.png>)

La pantalla de perfil permite al usuario visualizar su información personal y los planes de suscripción.

![alt text](<../assets/imgs/img27-app mockup 5.png>)

### 4.4.4. Web Applications User Flow Diagrams

Se ha utilizado la herramnienta en línea de "Figma" para mostrar la forma como navvegan los usuarios el aplicativo las rutas esperadas y alternas, usando mock-ups y basándose en los Wireflow Diagrams.

**Link del figma**: https://www.figma.com/file/rP99xLB3zucajdvaxBP7Ax/Untitled?type=design&node-id=9%3A519&mode=design&t=qnaHxqkizVdElFjC-1

![alt text](<../assets/imgs/img28-app mockup 6.png>)

## 4.5. Web Applications Prototyping

En esta sección se compartirán los prototipos relacionados a la aplicación web, donde se presentan el alcance de los user goals en ambos segmentos objetivos. A continuación se adjunta el link al video completo de Web Applications Prototyping.

**Link:** https://drive.google.com/file/d/1BWzI7dVY1skFZ6LU6fZ2nCBPjvyvQiI8/view?usp=sharing 

**Web Applications Prototyping Video:**
![alt text](<../assets/imgs/img29-prototyping.png>)

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Software Architecture Context Diagram

Explica el contexto del usuario, centrándose en la relación de los viajeros turísticos y estudiantiles con el sistema de Wanderlog para generar los planes de viaje. Además, hay conexión con servicios de terceros. 

![alt text](<../assets/imgs/Imagen30-c4 context.png>)

### 4.6.2. Software Architecture Container Diagrams

El aplicativo en sí tiene una estructura de landing page, aplicativo web, API RESTful, contexto específico por servicio y base de datos. Cada componente del aplicativo se centra en la funcionalidad completa del servicio ofrecido, en cuanto al lado frontend y backend.

![alt text](<../assets/imgs/img31-c4 container.png>)

### 4.6.3. Software Architecture Components Diagrams

Para el Bounded Context de Identificación y Acceso, describe la funcionalidad en relación con el API y los servicios de login al aplicativo, los cuales se realizan por medio de un controlador de acceso para llamar a un repositorio y almacenar el resultado en una base de datos relacional.

![alt text](<../assets/imgs/img32-c4 component.jpg>)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

Un diagrama de clases se basa en emplear la información que se va a obtener en el flujo del aplicativo. Cada pantalla del aplicativo, como login, registro, home, perfil, etc tiene su respectiva funcionalidad en el código, el cual, al estructurarlo, se incluye dentro del presente diagrama.

**Link:** https://lucid.app/lucidchart/a97d2deb-ec0e-4532-8974-aa3d18092ee9/edit?viewport_loc=-3398%2C-1105%2C3217%2C1297%2C0_0&invitationId=inv_6a093c88-89ba-4fd9-ab6f-3a8e5397ec82 


![alt text](<../assets/imgs/img33-class diagram.png>)

### 4.7.2. Class Dictionary

- **User**: Es la clase que representa al usuario, sus atributos en su mayoría son sus datos personales, junto con la id. Sus métodos son generados por sus propios datos personales.

- **Register-Login**: Es el registro e inicio de sesión, contiene como único atributo un arreglo de usuarios y sus métodos son los de registrar un usuario nuevo e iniciar sesión con uno existente.

- **Page**: Es la clase principal, sus atributos consisten en la planilla, suscripción y un arreglo con todos los proyectos del usuario. Sus métodos, por otra parte, permiten ver los viajes anteriores, sus datos y ver los detalles de la suscripción.

- **Suscription**: La clase que representa la suscripción del usuario en la página. Su único método es el que contiene los datos del plan de suscripción y mediante sus métodos puede suscribirse, cancelar la suscripción o cambiar de tipo de suscripción.

- **TravelPlan**:

- **Flight**: Es la clase de los vuelos, sus atributos son la duración del viaje, si hace paradas y número de asiento. Mientras sus métodos son, será ver los detalles del vuelo y el servicio turístico.

- **TouristService**: Es la clase que representa los servicios turísticos.

- **Lodging**: Representa los alojamientos.

- **StudentPack**: Los atributos son lo siguiente, descripción del plan, día de inicio del plan y día de fin del plan. Sus métodos son ver los detalles del plan, suscripción, cancelar la suscripción y modificar la suscripción.

- **NumberOfService**: Es una clase auxiliar, no tiene atributos y solo tiene los métodos que muestran el plan de viaje, alojamiento, vuelo y atracciones turísticos.

## 4.8. Database Design

### 4.8.1. Database Diagram

Las bases de datos incluyen información vital para el backend del aplicativo. Especialmente en relación con la información del usuario, del plan de suscripción y los planes de viaje.

**Link:** https://my.vertabelo.com/public-model-view/ZzfPB6kondo8KEVZnBz1sWtoaOAxCT7eHRUA3Iz0GMsB6yIu03HNTusq4u5hssX1?x=3144&y=3222&zoom=0.4568

![alt text](<../assets/imgs/img34-database diagram.png>)
