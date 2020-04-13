# **Índice**
 
1. [Aclaraciones previas](#id1)
   1. [Sobre las entregas](#id2)
   2. [Con caracter general](#id3)
2. [Proyecto](#id4)
   1. [Título](#id5)
   2. [Objetivos](#id6)
      1. [Objetivos específicos](#id7)
 
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
 