# **Índice**
 
1. [Aclaraciones previas](#id1)
   1. [Sobre las entregas](#id2)
   2. [Con caracter general](#id3)
2. [Proyecto](#id4)
   1. [Título](#id5)
   2. [Objetivos](#id6)
      1. [Objetivos específicos](#id7)
3. [Justificación del proyecto](#id8)
4. [Características, comparación con otras aplicaciones y servicios del mercado](#id9)
5. [Librerías, servicios, protocolos, herramientas, etc, a utilizar](#id10)

 
<div id='id1'/>
 
# Aclaraciones previas
 
<div id='id2'/>
 
## Sobre las entregas
- Las entregas del proyecto serán entregadas, para su ágil consulta, en un formato que dista del formato final de presentación.
- Estas serán servidas a través del enlace al repositorio  hospedado en [GitHub](https://github.com/HaroldTemple/proyecto)
- Este será público y contendrá los puntos requeridos así como toda la documentación y archivos del proyecto.
- Este documento en particular servirá de índice desde el cual se podrá explorar todo el contenido.
- Se incluirán instrucciones para la ejecución de código y despliegue de los oportunos servicios.
 
<div id='id3'/>
 
## Con caracter general
- El proyecto será entregado en su forma final cumpliendo con los requesitos de formato.
- Este podrá sufrir modificaciones a lo larg de su desarroyo y estas serán devidamente regustradas mediante un [arvhivo de control de versiones](https://github.com/HaroldTemple/proyecto/blob/master/semver.md)
- Se creará un documento anexo en la entrga final con la presentación pública.
 
<div id='id4'/>
 
# Proyecto
 
<div id='id5'/>
 
## Título
 
#### **Despligue de aplicaciones mediante kubernetes**
 
<div id='id6'/>
 
## Ojetivos
 
> La idea nace de la necesidades que tienen los desarrolladores de desplegar sus aplicaciones durante el desarrollo y acercarse al punto de la producción sin perderse en los conocimientos puramente competencia del administrador de sistemas. Con este proyecto acercamos un método para atajar este conflicto de competencias y que este pueda volcar todo su desempeño exclusivamente en la aplicación. El objetivo principal de este proyecto, pues, es poner a disposición del desarrollador un espacio para el despliegue de aplicaciones de forma sencilla, ágil y agnóstica al lenguaje ya al entorno de desarrollo. Se pretende, mediante la orquestación automatización de contenedores, el despliegue, ajuste de escala de aplicaciones perfilados en la conjugación de los diversos microservicios que la componen. Todo ello mediante el uso de herramientas opensource.
 
> Un ejemplo de ello sería una aplicación de votos (escrita en Python), con una base de datos (Redis, PostgreSQL) que captura las interacciones de los usuarios y los procesa en un servidor en el que corre el motor de Javascript V8. 
 
<div id='id7'/>
 
### Objetivos específicos (especificaciones)
 
- Auxilio personalizado al desarroyador.
  - Se pretende despojar a este de toda labor adminitrativa de sistemas, redes, infraestructura, etc.
 
- Uso de contenirazción para homogenizar el servicio.
  - Mediante el uso de Docker se elimina la barrera del sistema operativo ya que virtualiza y se hace portable, mediante abstracción, la capa del kernel.
 
- Manejo del orquestador Kubernetes (k8s).
  - Orquestador que opera con los contenedores y los hace interactuar entre si mediante la conforacion de un cluster.
 
- Empleo de KinD como herramienta para la ejecución de un clúster de Kubernetes en local.
  - Su uso simplifica el uso de contenedores de Dockers.
 
- Helm como gestor de paquetes de Kubernetes.
  - Este herramienta nos proporciona paquetes preconfigurados para agilizar la configuración y el despliegue.
 
- Uso de la interfaz de usuario vía terminal k9s.
  - Siendo un apéndice de k8s, se convierte en una herramienta para el manejo, navegación, observación y administración del cluster.

<div id='id8'/>

## Justificación del proyecto

> La justificación del proyecto viene dada por la necesidad que se planteó en el apartado [objetivos](#id6). En la industria que nos concierne, cada vez las profesiones y labores se van especializando más y se produce un fenómeno de meteorización en donde cada uno de los perfiles desconoce, y así debe ser, las competencias del perfil ajeno. Esto favorece la existencia de verdaderos especialistas en disciplinas muy concretas, sin eliminar del panorama nunca a los perfiles fullstack. La idea general y por la que se propone este proyecto es para permitir total libertad al desarrollador sin que se vea supeditado a obtener y manejar conocimientos de administración de sistemas, redes o bases de datos de forma interna, con esto conseguimos que este centre toda su atención en su trabajo. También se favorece un entorno donde el lenguaje de programación o la base de datos no importe para el despliegue ya que mediante el uso de API´s, convertimos a la comunicación entres microservicios agnóstica y que esta no interfiera ni limite. Ponemos así un recurso que acelera el trabajo de otro profesional de la industria o se ayuda a una empresa a desplegar su aplicación o servicio de una forma limpia, transparente y segura y lo que es más importante, portable y migrable con cero dificultades eliminando el cuello de botella que se produce por lo anteriormente descrito.

<div id='id9'/>

## Características, comparación con otras aplicaciones y servicios del mercado

> En el mercado existen empresas que permiten el despliegue de aplicaciones que proporcionan un altísimo rendimiento a un bajo coste y que, mediante una serie de directivas descritas en un manifiesto y procesadas con inteligencia artificial permiten desplegar con suma agilidad el servicio que uno desee. La diferenciación con este mercado es que el servicio que se le proporciona al usuario final se hará mediante unas herramientas customizadas para cada desarrollo. Se puede pensar que ya está todo hecho y que no se necesita a un administrador que haga la gestión, pero ha de saber que el proceso en ambos casos no es para nada trivial y que se necesitas, de nuevo, la mano de un profesional dedicado que haga transparente el proceso para aquel que sólo ha de atender a su cometido. Desarrollar. Dicho en román paladino, existe la posibilidad de que el usuario final se autogestione como siempre o que se adentre en el mundo de la orquestación pero se va a encontrar de que la tarea no es sencilla, en este caso aparece la idea del proyecto y así, el administrador de sistemas entra como actor principal pudiendo incluso hacer coexistir su labor con las herramientas de pago (automatizadas y antes descritas) que existen en el mercado. Algunas de ellas son:

- [AWS](https://aws.amazon.com/es/)
- [AZURE](https://azure.microsoft.com/es-es/)
- [Heroku](https://id.heroku.com/login)

<div id='id10'/>

## Librerías, servicios, protocolos, herramientas, etc, a utilizar

- Docker (Contenerización)
- Kubernetes (Orquestador de contenedores)
- GIT (Para el control de verisnes)
- MarkDown (Lenguaje de marcas simplificado)
- YML (Lenguaje de marcas por identación)
- k9s (Observador de clúster)
- Helm (gestor de paquetes de Kubernetes)
- KinD (FrameWord simplificador de orquestación)
- Pyhon, Redis, PostgreSQL, Node.js (Para la aplicación a depslegar en el ejemplo de uso)