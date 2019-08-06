# Sistemas empresariales
## ¿Que es un sistema empresarial?
Es sistema que tiene un impacto muy importante en el funcionamiento de 
la organización o negocio y cuya falla traería graves consecuencias.
Normalmente que ofrece alta calidad de servicio, gestiona con grandes 
volúmenes de datos, disponible de forma continua y es capaz de soportar 
cualquier organización grande.
* En el desarrollo de aplicaciones de misión crítica se consideran
 * Plataforma tecnológica
 * Alta disponibilidad
 * Escalabilidad
 * Seguridad
 * Mantenimiento

## Caracteristicas mas importantes de una aplicación empresarial
* Acceso a bases de datos, usualmente a bases de datos relacionales.
* Operaciones transaccionales, cumple con las propiedades ACID
* Escalables, permiten escalabilidad vertical y horizontal
* Disponibles, idealmente prestan servicios de forma continua
* Seguras, no todos los usuarios acceden con la misma, funcionalidad
* Permiten integración con otras tecnologías
* Arquitectura multicapa

## Instituciones que requerirían aplicaciones de misión crítica. 

## Diferencias entre la escalabilidad horizontal y escalabilidad vertical
# Servidor
Un servidor es una computadora que formando parte de una red provee servicios 
a otras computadoras denominadas clientes.

# Que es un servidor Web y que es un servidor de aplicaciones
Un servidor web dispositivo de software que proporcionan servicios de paginas web 
a las  computadoras cliente.
Un servidor de aplicaciones es un dispositivo de software que proporcionan servicios 
de aplicación a las computadoras cliente.
 Un servidor de aplicaciones generalmente gestiona la mayor
parte (o la totalidad) de las funciones de la lógica de negocio y acceso a los datos de 
la aplicación.
 Los beneficios de la aplicación de la tecnología de servidores
de aplicación son la centralización y al disminución de la
complejidad en el desarrollo de aplicaciones

#Protocolo HTTP
HTTP, de sus siglas en inglés: "Hypertext Transfer Protocol", es el nombre de un protocolo el cual nos permite realizar una petición de datos y recursos, como pueden ser documentos HTML. Es la base de cualquier intercambio de datos en la Web, y un protocolo de estructura cliente-servidor, esto quiere decir que una petición de datos es iniciada por el elemento que recibirá los datos (el cliente), normalmente un navegador Web. Así, una página web completa resulta de la unión de distintos sub-documentos recibidos, como, por ejemplo: un documento que especifique el estilo de maquetación de la página web (CSS), el texto, las imágenes, vídeos, scripts, etc... 


Clientes y servidores se comunican intercambiando mensajes individuales (en contraposición a las comunicaciones que utilizan flujos continuos de datos). Los mensajes que envía el cliente, normalmente un navegador Web, se llaman peticiones, y los mensajes enviados por el servidor se llaman respuestas.

Diseñado a principios de la década de 1990, HTTP es un protocolo ampliable, que ha ido evolucionando con el tiempo. Es lo que se conoce como un protocolo de la capa de aplicación, y se transmite sobre el protocolo TCP, o el protocolo encriptado TLS, aunque teóricamente podría usarse cualquier otro protocolo fiable. Gracias a que es un protocolo capaz de ampliarse, se usa no solo para transmitir documentos de hipertexto (HTML), si no que además, se usa para transmitir imágenes o vídeos, o enviar datos o contenido a los servidores, como en el caso de los formularios de datos. HTTP puede incluso ser utilizado para transmitir partes de documentos, y actualizar páginas Web en el acto.

## Elementos REQUEST en HTTP

## Elementos RESPONSE en HTTP

## Describa con un gráfico la arquitectura Java EE
Es una plataforma de programación para
desarrollar y ejecutar software de aplicaciones en Lenguaje de programación Java con
arquitectura de n-niveles distribuida, basándose ampliamente en componentes de
software modulares ejecutándose sobre un servidor de aplicaciones.
Java EE incluye varias especificaciones de API, tales como JDBC, RMI, e-mail, JMS,
Servicios Web, XML, etc., y define como coordinarlos. Java EE también establece algunas
especificaciones únicas para Java EE de algunos componentes. Estas incluyen Enterprise
JavaBeans, Servlets, JavaServer Pages y varias tecnologías de servicios web. Esto
permite al desarrollador crear una aplicación de Empresa que sea portable entre
plataformas y escalable. Otros beneficios añadidos son, por ejemplo, que el servidor de
aplicaciones puede manejar las transacciones, seguridad, escalabilidad, concurrencia y
gestión de los componentes que son desplegados, significando que los desarrolladores
pueden concentrarse más en la lógica de negocio de los componentes en lugar de las
tareas de mantenimiento de bajo nivel. 


## Contenedores, componentes y servicios de Java EE

Un contenedor es un entorno de ejecución que provee al componente una serie de servicios.

Java EE Server: La porción de tiempo de ejecución de un producto
Java EE. provee los contenedores web y de ejb.
Contenedor EJB: Maneja la ejecución de los enterprise beans.
Contenedor Web: Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE. Contenedor de aplicación cliente: Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.
Contenedor Applet: Maneja la ejecución de applets, no necesita servidor de aplicaciones,consiste en un browser y el plugin web de java.

Un componente es una unidad de software que forma parte de una aplicación

Java EE define los siguientes tipos de componentes:
* Componente cliente: Cliente AWT, Swing, Applet y navegador Web
* Componente web: Servlet, JSP y JSF
* Componente de negocio: EJB
* Cada tipo cubre necesidades concretas y se basan en APIs especificas 

Java EE define los siguientes servicios:

De directorio: para la indexación y búsqueda de
componentes y recursos
De despliegue: para poder personalizar los componentes y
recursos

De transaccionalidad: para poder ejecutar distintas acciones en una misma unidad transaccional

De seguridad: para poder autenticar y autorizar a los
usuarios de la aplicación

De acceso a datos: para facilitar el acceso a Bases de Datos
Servicios Java EE

De conectividad: para poder acceder fácilmente a distintos EIS

De mensajería: para poder comunicarse con otros componentes, aplicaciones o EIS

Para que un entorno de ejecución pueda decir que es Java EE debe implementar y soportar:
   Todos los tipos de componentes
   Todos los tipos de contenedores
   Todos los servicios


## Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse
Un servlet es una clase Javaque hereda de la clase HttpServlet. Los cinco métodos más
comunes de un servlet son:
public void init()throws ServletException{}
public void service(HttpServletRequest request,
 HttpServletResponse response)
 throws ServletException, IOException {
public void doPost (HttpServletRequest request,
 HttpServletResponse response)
 throws ServletException, IOException {
public void doGet (HttpServletRequest request,
 HttpServletResponse response)
 throws ServletException, IOException {
public void destroy(){};

