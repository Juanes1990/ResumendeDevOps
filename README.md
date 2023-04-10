# ResumendeDevOps
## _Contenido:_
##### 1. _Que es?_
##### 2. _Para que sirve?_
##### 3. _Beneficios y contras?_
##### 4. _Herramientas de devops_
##### 5. _Equipos devops_
##### 6. _Que son pipelines_
##### 7. _ejemplos de pipeline_
#
#
# 1. Que es DevOps
DevOps es una metodología de desarrollo de software que busca integrar los equipos de desarrollo y operaciones para mejorar la calidad del software y la velocidad de entrega al mercado. Se basa en la colaboración y la automatización de procesos para lograr una mayor eficiencia y productividad en el ciclo de vida del software.Los equipos de DevOps trabajan juntos para automatizar el proceso de desarrollo y despliegue de software.
### DevOps es más...
- **Cultura:**  el deseo en ambos equipos en colaborar 
- **Automatización:** poder reproducir infraestructura como repoducimos bugs 
- **Medidas:** saber cuánto tomaron nuestras metas en común
- **Sharing:** mejores herramientas internas compartidas por todos los equipos 

# 2. Para que sirve?
DevOps es un conjunto de prácticas, herramientas y filosofía cultural que sirve para automatizar e integrar los procesos que comparten el equipo de desarrollo de software y el de TI. Se centra en el empoderamiento de los equipos, la comunicación y colaboración entre ellos y la automatización de la tecnología.
# 3. Beneficios y contras?
 ![](https://huecograbadopando.files.wordpress.com/2015/10/ventajas-y-desventajas-de-buscar-pareja-en-internet.jpg)
## Beneficios
- Mayor eficiencia y productividad en el ciclo de vida del software.
- Reducción del tiempo de desarrollo y despliegue.
- Mejora de la calidad del software y reducción de errores.
- Mayor colaboración y comunicación entre los equipos de desarrollo, operaciones y seguridad.
- Mayor satisfacción del cliente.
- Mayor escalabilidad y flexibilidad para responder a los cambios del mercado.

## Contras
- Requiere una fuerte cultura empresarial y un cambio de mentalidad en los equipos.
- Puede ser costoso implementar y mantener herramientas de automatización.
- Puede ser difícil de implementar en organizaciones grandes y complejas.
- Puede requerir una curva de aprendizaje para que los equipos aprendan nuevas herramientas y procesos.
- Puede haber riesgos de seguridad si no se implementan adecuadamente las prácticas de seguridad y privacidad.

En general, los beneficios de DevOps superan las desventajas, pero es importante que las organizaciones tomen en cuenta tanto los beneficios como los costos y riesgos potenciales antes de implementar DevOps en su ciclo de vida de desarrollo de software.

# 4. Herramientas de DevOps
DevOps trabaja en el modo multifuncional, involucrando varias herramientas de diversos tipos y propósitos, en lugar de una sola herramienta. Estas herramientas también se conocen como cadenas de herramientas DevOps, como se ha comentado.
Las herramientas ayudan en todo el ciclo de vida de la producción de software, incluyendo el desarrollo, la gestión y la entrega.
La organización que utiliza la práctica de DevOps coordina estas herramientas y encaja cada una de ellas en una o más actividades de producción como la planificación, la creación, la verificación, el empaquetado, la liberación, la configuración, la supervisión y el control de versiones.

## Etapa de Planeación
##### Jira
##### Asana
##### Trello
##### Notion
## Etapa de Codigo
##### GitHub
##### GitLab
## Etapa de compilación
##### Maven
##### Gradle
## Etapa de Testing
##### Selenium
##### Gremlin
## Etapa de CI/CD
##### Jenkins
##### CircleCI
##### GitHub Actions
##### GitLab
## Etapa de Operaciones
##### Chef
##### Ansible
##### Puppet
##### Terraform
## Contenedores / MicroServicios
##### Docker
##### Kubernetes
## Monitoreo
##### New Relic
##### Amazon Cloud Watch
##### Grafana
##### Prometheus
# 5. Equipo DevOps
Un equipo DevOps es un grupo de profesionales que trabajan juntos para mejorar la colaboración y la comunicación entre los desarrolladores de software y los profesionales de operaciones de TI. El objetivo principal del equipo DevOps es acelerar el desarrollo de software y mejorar su calidad, al mismo tiempo que se reducen los tiempos de inactividad y se garantiza la estabilidad del sistema.

El equipo DevOps está formado por desarrolladores de software, administradores de sistemas, ingenieros de automatización, analistas de seguridad, especialistas en control de calidad, entre otros roles que varían según la empresa. Los miembros del equipo trabajan juntos para implementar procesos ágiles de desarrollo, integración y entrega continua de software, utilizando herramientas y tecnologías avanzadas como la automatización de pruebas, el control de versiones, la virtualización de servidores, la infraestructura como código, entre otras.

En resumen, un equipo DevOps es esencial para mejorar la eficiencia, la calidad y la seguridad del proceso de desarrollo de software, y para garantizar una mayor satisfacción del cliente.
# 6. Que son Pipelines?
En el contexto del desarrollo de software, un pipeline (o tubería, en español) es un conjunto de etapas que se utilizan para compilar, probar y entregar software de manera automatizada. Un pipeline de software típicamente se compone de una serie de pasos, cada uno de los cuales tiene una tarea específica que realizar.

Los pipelines son muy comunes en la metodología DevOps, ya que permiten automatizar el proceso de entrega continua de software. Esto significa que cada vez que se realiza un cambio en el código fuente, se puede ejecutar automáticamente un pipeline para compilar, probar y entregar el software actualizado al entorno de producción.

Cada paso en un pipeline puede ser diseñado para llevar a cabo una tarea específica, como compilar el código fuente, ejecutar pruebas unitarias, crear imágenes de contenedores, desplegar la aplicación en un servidor, etc. Los pipelines pueden ser configurados para ejecutarse automáticamente cuando se detectan cambios en el código fuente o cuando se activan eventos específicos, como una solicitud de confirmación de un repositorio de control de versiones.

En resumen, los pipelines son una herramienta esencial en la entrega continua de software, ya que permiten automatizar y estandarizar el proceso de desarrollo y entrega, lo que mejora la eficiencia y la calidad del software entregado.
# 7. Ejemplos de Pipelines
Hay muchos ejemplos de pipelines de software, algunos de los más comunes incluyen:

1. **Pipeline de Integración Continua (CI):** Este pipeline se utiliza para compilar, probar y validar cambios de código realizados por los desarrolladores en un repositorio de control de versiones. Cada vez que se realiza un cambio, el pipeline de CI se ejecuta automáticamente para garantizar que el nuevo código no rompa la funcionalidad existente.

2. **Pipeline de Entrega Continua (CD):** Este pipeline se utiliza para entregar y desplegar automáticamente el software en diferentes entornos, como pruebas, preproducción y producción. El pipeline de CD incluye etapas para compilar, probar, empaquetar y desplegar la aplicación en cada uno de los entornos.

3. **Pipeline de Automatización de Pruebas:** Este pipeline se utiliza para automatizar la ejecución de pruebas de software, como pruebas de unidad, pruebas de integración y pruebas de aceptación. El pipeline de automatización de pruebas ayuda a detectar errores de manera temprana y a garantizar que el software entregado sea de alta calidad.

3. **Pipeline de Despliegue de Infraestructura:** Este pipeline se utiliza para crear y desplegar infraestructura en la nube o en entornos locales. El pipeline de despliegue de infraestructura incluye etapas para crear y configurar máquinas virtuales, instalar software y configurar servicios de red.

![](https://biplus.com.vn/wp-content/uploads/2022/11/Ci-CD-pipeline-tools.png)

En resumen, los pipelines de software se utilizan para automatizar el proceso de desarrollo, pruebas, entrega y despliegue de software, lo que mejora la eficiencia, la calidad y la velocidad de entrega del software.


