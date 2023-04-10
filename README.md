# ResumendeDevOps

https://devopsdays.io/
Contenido:




## ¿Que Es?

El término DevOps, que es una combinación de los términos ingleses development (desarrollo) y operations (operaciones), designa la unión de personas, procesos y tecnología para ofrecer valor a los clientes de forma constante.

¿Qué significa DevOps para los equipos? DevOps permite que los roles que antes estaban aislados (desarrollo, operaciones de TI, ingeniería de la calidad y seguridad) se coordinen y colaboren para producir productos mejores y más confiables. Al adoptar una cultura de DevOps junto con prácticas y herramientas de DevOps, los equipos adquieren la capacidad de responder mejor a las necesidades de los clientes, aumentar la confianza en las aplicaciones que crean y alcanzar los objetivos empresariales en menos tiempo.

![](https://orangematter.solarwinds.com/wp-content/uploads/2022/03/DevOps-lifecycle-capabilities-1024x621.png)

## ¿Para Que Sirve?

DevOps sirve para mejorar y acelerar el proceso de desarrollo de software, mediante la automatización, integración y colaboración entre los equipos de desarrollo, operaciones y seguridad.

En lugar de trabajar de forma aislada y secuencial, los equipos de DevOps trabajan de manera colaborativa y simultánea, lo que les permite detectar y solucionar problemas de manera más rápida y eficiente, así como entregar software de manera más frecuente y con mayor calidad.

Además, DevOps fomenta la cultura de la mejora continua, lo que significa que los equipos están constantemente buscando formas de optimizar y mejorar el proceso de desarrollo y entrega de software.


## Beneficios y Contras

# Beneficios de DevOps:
- Mayor velocidad y frecuencia en el lanzamiento de software.
- Mejora en la calidad del software, debido a la automatización de pruebas y procesos de integración continua.
- Reducción en el tiempo de resolución de problemas, gracias a la detección temprana y la resolución rápida de problemas.
- Mayor colaboración y comunicación entre los equipos de desarrollo, operaciones y seguridad.
- Mayor eficiencia y reducción de costos, gracias a la automatización de tareas manuales y repetitivas.
- Promueve la cultura de la mejora continua, lo que significa que los equipos están constantemente buscando formas de optimizar y mejorar el proceso de desarrollo y entrega de software.

# Contras de DevOps:
- Aumento en la complejidad del proceso, debido a la necesidad de integrar herramientas y procesos de desarrollo y operaciones.
- Requiere un mayor conocimiento y habilidades técnicas, lo que puede resultar en la necesidad de capacitar al personal.
- Requiere un cambio cultural en los equipos, ya que la metodología de DevOps promueve una mayor colaboración y responsabilidad compartida entre los equipos de desarrollo, operaciones y seguridad.
- Puede ser costoso implementar y mantener herramientas y tecnologías de automatización y gestión de infraestructuras.

En resumen, los beneficios de DevOps son una mayor velocidad, calidad, eficiencia y colaboración en el proceso de desarrollo de software, mientras que los contras pueden incluir un aumento en la complejidad del proceso, la necesidad de un mayor conocimiento técnico y un cambio cultural en los equipos.


## Herramientas Devops

Existen muchas herramientas de DevOps disponibles en el mercado, a continuación se mencionan algunas de las herramientas más populares y para qué se utilizan:

- Git: Sistema de control de versiones para el seguimiento de cambios en el código fuente.
- Jenkins: Herramienta de automatización de construcción y entrega de software.
- Docker: Plataforma de contenedores que permite la creación, distribución y ejecución de aplicaciones en diferentes entornos.
- Kubernetes: Plataforma de orquestación de contenedores que simplifica la implementación, la escala y la gestión de aplicaciones en diferentes entornos.
- Ansible: Herramienta de automatización de configuración y gestión de infraestructuras.
- Nagios: Herramienta de monitoreo de infraestructuras y servicios de red.
- ELK Stack: Conjunto de herramientas de análisis de registros y visualización de datos.
- Grafana: Herramienta de visualización de datos para el monitoreo de infraestructuras y servicios.
- Terraform: Herramienta de infraestructura como código (IaC) para la creación y gestión de recursos de infraestructura en la nube.
- Chef: Herramienta de automatización de configuración y gestión de infraestructuras.
Cada herramienta se utiliza para una función específica dentro del proceso de DevOps, como la gestión de versiones de código fuente, la automatización de pruebas y entregas, la creación y gestión de contenedores, la orquestación de aplicaciones, la automatización de configuración de infraestructura, el monitoreo de infraestructuras y servicios, la visualización de datos, la gestión de recursos de infraestructura en la nube y la automatización de configuración y gestión de infraestructuras.

![](https://www.excentia.es/img/posts/2018-04-13-herramientas-devops.png)



## Equipos Devops

Un equipo de DevOps está formado por desarrolladores y profesionales de operaciones de TI que colaboran durante todo el ciclo de vida de un producto para aumentar la velocidad y la calidad de la implementación del software. Se trata de una nueva forma de trabajar, un cambio cultural que tiene una profunda repercusión tanto para los equipos como para las organizaciones en las que trabajan.

Con un modelo DevOps, se pone fin al aislamiento de los equipos de desarrollo y operaciones. A veces, estos dos equipos se fusionan en uno solo; en ese caso, los ingenieros, que cuentan con varias competencias multidisciplinarias, trabajan durante todo el ciclo de vida de una aplicación, desde la fase de desarrollo y pruebas hasta la de implementación y operaciones.

Los equipos de DevOps utilizan herramientas para automatizar y acelerar los procesos, lo que hace que sean mucho más fiables. Con una cadena de herramientas de DevOps, los equipos pueden ocuparse de aspectos básicos de esta metodología, como la integración continua, la entrega continua, la automatización y la colaboración.

Los valores de DevOps a veces se aplican a otros equipos que no son de desarrollo. Por ejemplo, cuando los equipos de seguridad adoptan un enfoque DevOps, la seguridad se convierte en una parte activa e integrada del proceso de desarrollo. 

## ¿Que Son Pipelines?

Un pipeline es una nueva forma de trabajar en el mundo devops en la integración continua. Utilizando pipeline y Jenkins, podemos definir el ciclo de vida completo de una aplicación (descargar código, compilar, test, desplegar, etc.) mediante código.

De esta forma, resulta mucho más sencillo replicar los diferentes pasos con distintas aplicaciones y gestionar mejor los cambios en cada paso.

# ¿Por qué usar pipelines?
Uno de los mayores beneficios de usar pipelines y Jenkins es poder hacer los jobs más configurables, fáciles de editar y más durables. También podemos utilizar entradas (input) humanos o esperar la aprobación de otro job para ejecutar el nuestro mediante pipelines.

Pero, además de estas ventajas, el principal valor diferencial de esta nueva estructura es que es versátil y extensible, y podemos crear pipelines para hacer un fork, un bucle, e incluso para ejecutar cosas en paralelo. Además podemos customizarlas todo lo que queramos mediante groovy.

ejemplos de pipeline

con el siguiente enlace podemos ver un `[ejemplo](https://onthedock.github.io/post/180521-pipeline-creacion-del-job-en-jenkins/)`