# ResumendeDevOps
Jesus
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

<img src="https://th.bing.com/th/id/R.e43a5b2e22cf4113e9d1c8e9a6ebd663?rik=fMElY%2boQNNRG3g&riu=http%3a%2f%2fagapeconsultinggroup.com%2fwp-content%2fuploads%2f2017%2f07%2fDevOps.png&ehk=4kG1HWZ4%2bu%2fRDTuBY8WweZ%2fv%2bQWtZWO5kHL0QnTT3WU%3d&risl=&pid=ImgRaw&r=0" width="500" height="400">

---------------------------------------------
Jessica
## **Tabla de Contenido:**  :white_check_mark:
- [¿Qué es DevOps?](#qué-es-devops)
- [¿Para qué sirve?](#para-qué-sirve)
- [Beneficios y contras](#beneficios-y-contras)
- [Herramientas de DevOps](#herramientas-de-devops)
- [Equipos DevOps](#equipos-devops)

### **_¿Qué es DevOps?_**
DevOps es un acrónimo inglés de development (desarrollo) y operations (operaciones). Es un conjunto de prácticas que agrupan el desarrollo de software (Dev) y las operaciones de TI (Ops). Su objetivo es hacer más rápido el ciclo de vida del desarrollo de software y proporcionar una entrega continua de alta calidad.

DevOps es un marco de trabajo y una filosofía en constante evolución que promueve un mejor desarrollo de aplicaciones en menos tiempo y la rápida publicación de nuevas o revisadas funciones de software o productos para los clientes. Con DevOps se promueve una comunicación continua más fluida, la colaboración, la integración, la visibilidad y la transparencia entre equipos de desarrollo de aplicaciones (Dev) y sus homólogos en operaciones tecnológicas (Ops).

Esta relación estrecha entre «Dev» y «Ops» se extiende a cada una de las fases del ciclo de vida de DevOps: desde la planificación inicial del software a las fases de codificación, compilación, pruebas y publicación, y en la puesta en marcha, las operaciones y la supervisión continua. Esta relación impulsa un bucle de retroalimentación continua con los clientes sobre las mejoras, el desarrollo, las pruebas y la puesta en marcha. Uno de los resultados de todos estos esfuerzos puede ser la publicación continua y más rápida de las adiciones y los cambios que se necesitan en las funciones.

Además de los esfuerzos por romper las barreras de comunicación y fomentar la colaboración entre los equipos de desarrollo y operaciones tecnológicas, uno de los principales valores de DevOps es lograr la satisfacción del cliente y prestar sus servicios en menos tiempo. DevOps también se ha creado para impulsar la innovación empresarial y ser el motor de continuas mejoras en los procesos. La práctica de DevOps propicia que cada empresa se ponga como objetivo ofrecer un mejor servicio cada vez, en menos tiempo, de mejor calidad y con mayor seguridad a sus clientes finales; por ejemplo, con actualizaciones, funciones o versiones de producto más frecuentes.

DevOps se basa en técnicas de gestión ágil de proyectos y en el uso de microservicios, y aborda el ciclo de vida completo del desarrollo de software desde la planificación hasta la supervisión.

Haz clic [DevOps en 5 minutos | ¿Qué es DevOps? | Explicación DevOps](https://youtu.be/3-vd5NDH1-I)

### **_¿Para qué sirve?_**
DevOps sirve para mejorar la colaboración y comunicación entre los equipos de desarrollo de software y operaciones de TI. Esto permite una entrega más rápida y eficiente de software y productos de alta calidad a los clientes. También ayuda a impulsar la innovación empresarial y a mejorar continuamente los procesos.

### **_Beneficios y contras_**
| Pros  | Contras |
| ------------- | ------------- |
| Velocidad: DevOps puede ayudarlo a lanzar software más rápido, con actualizaciones más frecuentes y un tiempo de comercialización más corto.  | Cambio cultural: Uno de los mayores desafíos es el cambio cultural requerido para adoptar esta metodología. Muchas organizaciones están acostumbradas a trabajar en silos y puede ser difícil romper esas barreras.  |
| Colaboración: al romper los silos entre los equipos de desarrollo y operaciones, DevOps promueve una mejor colaboración y comunicación.  |Inversión en herramientas: la implementación de DevOps requiere inversión en nuevas herramientas y tecnologías, lo que puede ser un gasto significativo para algunas empresas.  |
|Mejora de la calidad del software: DevOps puede ayudar a mejorar la calidad del software al promover pruebas automatizadas e integración continua. | Medición del ROI: puede ser difícil medir el impacto de DevOps en la rentabilidad de una organización. |
|Mayor flexibilidad: DevOps permite una mayor flexibilidad en el desarrollo de software, ya que se pueden realizar cambios y actualizaciones con mayor facilidad y rapidez.| Requiere habilidades adicionales: La implementación de DevOps requiere habilidades adicionales, tanto técnicas como no técnicas, lo que puede ser un desafío para algunas organizaciones.|

### **_Herramientas de DevOps_**
Hay muchas herramientas disponibles para ayudar a implementar DevOps en una organización. Estas herramientas pueden ayudar a mejorar la colaboración y comunicación entre los equipos de desarrollo y operaciones, automatizar el proceso de implementación y mejorar la calidad del software.

Algunas herramientas populares de DevOps incluyen:

- **JIRA:** una herramienta de gestión de proyectos desarrollada por Atlassian que se utiliza para el seguimiento de problemas, errores y proyectos.

- **SVN:** una herramienta de control de versiones que permite a los equipos colaborar en el desarrollo de software.

- **Ant:** una herramienta de automatización de compilación que ayuda a automatizar el proceso de compilación y prueba de software.

- **Puppet:** una herramienta de gestión de configuración que ayuda a automatizar la configuración y el mantenimiento de sistemas y aplicaciones.
Prometheus: una herramienta de seguridad continua que ayuda a monitorear y proteger aplicaciones y sistemas.

- **Selenium:** una herramienta de automatización de pruebas que ayuda a automatizar las pruebas de software.

- **Nagios:** una herramienta de monitoreo que ayuda a monitorear sistemas y aplicaciones para detectar problemas y mejorar el rendimiento.

- **AWS:** un proveedor líder de servicios en la nube que ofrece una amplia gama de servicios para ayudar a implementar y ejecutar aplicaciones en la nube.

### **_Equipos DevOps_** :restroom:
Un equipo de DevOps es un grupo interdisciplinario de profesionales que trabajan juntos para mejorar la colaboración y comunicación entre los equipos de desarrollo y operaciones. El objetivo de un equipo de DevOps es mejorar la eficiencia y calidad del desarrollo de software mediante la implementación de prácticas y herramientas de DevOps.

Un equipo de DevOps típicamente incluye miembros de los equipos de desarrollo y operaciones, así como otros roles relevantes como ingenieros de calidad, ingenieros de seguridad y gerentes de producto. Los miembros del equipo trabajan juntos para planificar, desarrollar, probar e implementar software de manera más eficiente y efectiva.

La estructura y composición exacta de un equipo de DevOps puede variar según las necesidades y objetivos específicos de cada organización. Lo importante es que el equipo esté formado por profesionales con habilidades complementarias que puedan trabajar juntos para mejorar el proceso de desarrollo de software.

Puede estar compuesto por profesionales de diferentes áreas y con diferentes habilidades. Algunos de los roles comunes en un equipo de DevOps pueden incluir:

- **Desarrolladores de software:** responsables de escribir y mantener el código fuente de la aplicación.

- **Ingenieros de operaciones:** responsables de mantener y mejorar la infraestructura y los sistemas que soportan la aplicación.

- **Ingenieros de calidad:** responsables de garantizar que el software cumpla con los estándares de calidad y funcione correctamente.

- **Ingenieros de seguridad:** responsables de garantizar que el software y la infraestructura sean seguros y cumplan con los estándares de seguridad.

- **Gerentes de producto:** responsables de definir y priorizar las características y funcionalidades del producto.

- **Scrum Masters o facilitadores de Agile:** responsables de facilitar la comunicación y colaboración entre los miembros del equipo y asegurar que se sigan las prácticas ágiles.

La composición exacta de un equipo de DevOps puede variar según las necesidades y objetivos específicos de cada organización. Lo importante es que el equipo esté formado por profesionales con habilidades complementarias que puedan trabajar juntos para mejorar el proceso de desarrollo de software.
que son pipelines

### **_Ejemplos de Pipeline_**
Un pipeline de CI/CD es un componente fundamental en el desarrollo de software automatizado. Este término se utiliza para ilustrar las amplias aplicaciones de comportamientos y procesos involucrados en la integración continua (CI) y la entrega continua (CD). La CI es una estrategia de desarrollo de software que aumenta la velocidad de desarrollo al tiempo que garantiza que la calidad del código implementado no se vea comprometida. La CD es una extensión de esta automatización y permite que el software se implemente después de cada confirmación de código que pasa su conjunto de pruebas.

1. Un desarrollador realiza cambios en el código y los envía al repositorio compartido.
2. El pipeline de CI/CD se activa automáticamente y comienza a construir y probar el código.
3. Si las pruebas son exitosas, el código se fusiona con el repositorio compartido.
4. El pipeline de CD se activa y comienza a implementar el código en el entorno de producción.
5. Si la implementación es exitosa, el código se encuentra en producción y está disponible para los usuarios.

![pipeline](https://th.bing.com/th/id/R.26fc95b19bd7db6643306784f901cbaf?rik=YSqDK6dBKf15Xw&riu=http%3a%2f%2fautomated-360.com%2fwp-content%2fuploads%2f2020%2f01%2fdevops-pipeline-overview.png&ehk=wKXW2II6HtMwojp6zrgOn7kxA93fKwRexPxgWwbvk9o%3d&risl=&pid=ImgRaw&r=0)

La imagen muestra un ejemplo de un pipeline de DevOps. Un pipeline de DevOps es un conjunto de procesos y herramientas que se utilizan para automatizar el ciclo de vida del desarrollo de software, desde la planificación hasta la entrega y el monitoreo.

En la imagen, podemos ver las diferentes etapas del pipeline de DevOps:

1. **Plan:** En esta etapa, se planifica el trabajo a realizar y se definen las tareas y los requisitos.
2. **Code:** En esta etapa, los desarrolladores escriben y revisan el código.
3. **Build:** En esta etapa, el código se compila y se prepara para su implementación.
4. **Test:** En esta etapa, el código se somete a una serie de pruebas para asegurarse de que funciona correctamente.
5. **Release:** En esta etapa, el código se implementa en el entorno de producción.
6. **Deploy:** En esta etapa, el código se despliega en los servidores y está disponible para los usuarios.
7. **Operate:** En esta etapa, se monitorea el funcionamiento del sistema y se resuelven los problemas que puedan surgir.
8. **Monitor:** En esta etapa, se recopilan datos sobre el rendimiento del sistema y se utilizan para mejorar el proceso de desarrollo.

Cada una de estas etapas puede estar automatizada utilizando diferentes herramientas y tecnologías. El objetivo del pipeline de DevOps es mejorar la eficiencia y la calidad del proceso de desarrollo de software.

### **_Referencias_**
https://azure.microsoft.com/es-mx/resources/cloud-computing-dictionary/what-is-devops/
https://es.linkedin.com/pulse/ventajas-y-desventajas-de-las-metodolog%C3%ADas-desarrollo-wagner
https://geekflare.com/es/devops-tools/

