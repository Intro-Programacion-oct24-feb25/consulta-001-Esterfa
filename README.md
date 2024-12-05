## [Consulta]

1. Investigar sobre Entornos de virtualización para pruebas y desarrollo – Docker.
2. Crear una wiki con la información investigada
3. Agregar la bibliografía
   
                                         	DOCKER
Docker es una plataforma de contenedores lanzada en 2013 que ha contribuido enormemente a la democratización de la contenedorización. Facilita la creación de contenedores y aplicaciones basadas en contenedores. Hay otras, pero esta es la más utilizada. También es más fácil de instalar y utilizar que sus competidoras.

Es una solución de código abierto, segura y asequible. Muchas personas y empresas contribuyen al desarrollo de este proyecto. Esta amplia comunidad está desarrollando un gran ecosistema de productos, servicios y recursos.

Inicialmente diseñada para Linux, Docker también admite contenedores en Windows o Mac gracias a una capa de virtualización Linux entre el sistema operativo Windows/macOS y el entorno de ejecución Docker. Por tanto, es posible ejecutar contenedores nativos de Windows en entornos de contenedores de Windows o Linux.

¿Cómo funciona Docker?
Docker se basa en el núcleo de Linux y en funciones del núcleo como cgroups y namespaces. Estas funciones permiten separar los procesos para que puedan ejecutarse de forma independiente.

De hecho, el propósito de los contenedores es ejecutar varios procesos y aplicaciones por separado. Esto optimiza el uso de la infraestructura sin reducir el nivel de seguridad en comparación con los sistemas separados.

Todas las herramientas de contenedores, como Docker, están asociadas a un modelo de despliegue basado en imágenes. Con este modelo es más fácil compartir una aplicación o un conjunto de servicios entre varios entornos.

Además, Docker permite automatizar el desarrollo de aplicaciones en un entorno de contenedores. Gracias a estas distintas herramientas, los usuarios pueden acceder a todas las aplicaciones, acelerar el despliegue, controlar las versiones y asignarlas.


Docker facilita la coordinación del comportamiento entre contenedores y la conexión entre ellos para crear stacks de aplicaciones. Para simplificar el proceso de desarrollo y testeo de aplicaciones multicontenedor, Docker ha creado Docker Compose.

Se trata de una herramienta de línea de comandos, similar al cliente Docker, que utiliza un archivo de descripción con un formato específico para agrupar aplicaciones de varios contenedores y ejecutarlas en un único host.

Cuando una aplicación está lista para instalarse en Docker, es necesario poder abastecer, configurar, ampliar y supervisar los contenedores en la arquitectura de microservicios.

Esto se consigue utilizando sistemas de orquestación de contenedores de código abierto como Kubernetes, Mesos o Docker Swarm. Estos sistemas proporcionan las herramientas necesarias para gestionar clústeres de contenedores.

En concreto, estas soluciones permiten distribuir recursos entre contenedores, añadir o eliminar contenedores, gestionar interacciones entre contenedores, supervisar su estado y equilibrar la carga entre microservicios.



El Docker Desktop es la aplicación nativa para ordenador diseñada por Docker para Windows y Mac. Es la forma más sencilla de ejecutar, construir, depurar y probar aplicaciones dockerizadas.

Incorpora características clave como ciclos de prueba rápidos, notificaciones de cambios en los archivos, compatibilidad con la red de la empresa y flexibilidad total a la hora de elegir proxies y VPN.

La aplicación Docker Desktop incluye herramientas para desarrolladores, Docker App, Kubernetes y sincronización de versiones. Permite crear imágenes y plantillas eligiendo idiomas y herramientas.

Las principales ventajas son la velocidad, la seguridad y la flexibilidad. Existe una edición Community gratuita y una edición Enterprise de pago con funciones adicionales de seguridad, gestión, orquestación y administración.

Existen dos versiones diferentes de Docker Desktop. La versión Stable ha sido probada exhaustivamente y puede utilizarse para desarrollar aplicaciones fiables. Las actualizaciones se publican en paralelo a las del Docker Engine.

Sin embargo, la versión Edge incluye nuevas funciones experimentales del Docker Engine. Por tanto, existe el riesgo de que se produzcan bugs, fallos del sistema y otros problemas técnicos. Sin embargo, esta versión permite probar las nuevas características por adelantado.

BIBLIOGRAFIA

https://datascientest.com/es/docker-todo-que-saber

https://www.ionos.com/es-us/digitalguide/servidores/know-how/que-es-docker/?srsltid=AfmBOorZxSU7_rO-ApNpbNQ43AHfK07UBr6usMwNzfC1sB8dsVywFWjw

