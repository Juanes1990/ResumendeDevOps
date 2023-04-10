
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

-------------------------------------------------
Sergio
## Que es DevOps?

DevOps es una cultura de colaboración y comunicación entre los equipos de desarrollo de software y operaciones de tecnología de la información, que tiene como objetivo entregar software de manera más rápida, confiable y con mayor calidad. DevOps se enfoca en la automatización de procesos, la mejora continua y el monitoreo en tiempo real, para asegurar que el software sea entregado de manera eficiente y efectiva. Esto implica un enfoque en la integración continua, entrega continua, y despliegue continuo (CI/CD), así como también la colaboración y la transparencia entre los equipos.

### Integración Continua (CI)

La Integración Continua es una práctica de desarrollo de software que se enfoca en la automatización de la compilación y pruebas de un código fuente a medida que se va escribiendo, con el objetivo de detectar errores lo antes posible en el ciclo de vida del software.

En un proceso de integración continua, cada vez que se realiza una modificación en el código fuente, ya sea por parte de un desarrollador o por medio de una herramienta de automatización, el código es compilado y se ejecutan pruebas automatizadas para detectar problemas. Si se detecta algún error, se notifica al equipo de desarrollo de inmediato, lo que permite corregir el problema de manera oportuna

### Entrega Continua

La Entrega Continua es una práctia de desarrollo de software que se enfoca en la automatización de procesos de construcción, prueba y entrega de software en un flujo de trabajo constante y repetitivo.

En la Entrega Continua, el software se construye, prueba y se despliega automáticamente en un entorno de preproducción tan pronto como se realiza una modificación en el código fuente. Si los resultados de las pruebas son satisfactorios, el software se despliega automáticamente en el entorno de producción. Si se detecta algún error, el proceso se detiene y se notifica al equipo de desarrollo para que se corrijan los problemas.

## Para que sirve?

Como se menciono anteriormente, la metodología DevOps sirve para mejorar la colaboración entre los equipos de desarrollo de software y los equipos de operaciones de tecnología, y para automatizar y optimizar el proceso de entrega continua de software. Permite que los equipos trabajen de manera más efectiva, mejorando la comunicación, mejorando la comunicación, la colaboración y la eficiencia en todo el ciclo de vida del software. Esto puede conducir a una entrega más rápida y confiable de software, con menos errores y con una mayor capacidad de respuesta a las necesidades del cliente.

Al adoptar esta metodología, los equipos de desarrollo pueden aprovechar herramientas y técnicas de automatización para optimizar el proceso de construcción, pruebas, integración, entrega y despliegue de software. Esto puede reducir el tiempo y los costos de entrega, al tiempo que aumenta la calidad  y la confiabilidad del software entregado.

## Beneficios y contras?

Aunque algunos de los beneficios y ventajas de implementar la metodología DevOps se han mencionado en los apartados anteriores, en esta sección se enumeran cinco de sus ventajas:

1. Mayor eficiencia en la entrega de software: La implementación de DevOps puede ayudar a acelerar la entrega de software y a reducir el tiempo necesario para corregir errores o implementar nuevas características.

2. Mayor calidad del software: La automatización de pruebas y de la integración continua puede ayudar a detectar errores y defectos en el código fuente temprano en el proceso de desarrollo, lo que puede mejorar la calidad del software entregado.

3. Mayor colaboración y comunicación: DevOps se enfoca en la colaboración entre los equipos de desarrollo y operaciones, lo que puede mejorar la comunicación y la eficiencia en el proceso de entrega de software.

4. Mayor seguridad: Puede ayudar a mejorar la seguridad del software mediante la automatización de pruebas de seguridad y la integración de prácticas de seguridad en todo el proceso de desarrollo y entrega.

5. Mejor experiencia del usuario: La entrega más rápida y la mayor calidad del software puede mejorar la experiencia del usuario final, lo que puede aumentar la satisfacción del cliente y la lealtad hacia la empresa o el equipo de desarrollo.

Ahora se presentan cinco desventajas que se pueden presentar a la hora de trabajar con DevOps:

1. Requiere un cambio cultural: La implementación de DevOps puede requerir un cambio cultural significativo dentro de una organización, ya que implica mayor colaboración y una mayor responsabilidad compartida entre los equipos de desarrollo y operaciones. Este cambio cultural puede ser difícil de lograr y puede llevar tiempo.

2. Requiere una inversión significativa en herramientas y tecnologías: Para implementar DevOps de manera efectiva, es necesario invertir en herramientas y tecnologías específicas, como herramientas de automatización, servicios en la nube y plataformas de integración continua. Esto puede ser costoso para algunas organizaciones.

3. Puede ser difícil de implementar en grandes organizaciones: La implementación puede ser más difícil en organizaciones más grandes y complejas, debido a la necesidad de coordinar múltiples equipos y procesos.

4. Requiere habilidades y capacitación específicas: Para la implementación de DevOps, es necesario contar con personal altamente capacitado en la metodología y las herramientas específicas asociadas. Esto puede ser difícil de lograr para algunas organizaciones.

5. Riesgo de dependencia de herramientas y tecnologías específicas: Puede haber un riesgo de dependencia de estas herramientas y tecnologías, y en caso que estas herramientas se vuelvan obsoletas o dejan de ser compatibles, la organización puede enfrentar dificultadas para mantener su proceso de entrega de software.

## Herramientas de devops

Existen muchas herramientas para ser utilizadas por los equipos en DevOps. Aquí se mencionan algunas de ellas:

### Git
Git es una herramientas de control de versiones que se utiliza para gestionar y mantener el código fuente. Permite a los desarrolladores colaborar en el mimso proyecto y trabajar diferentes versiones del código de manera simultanea.

### Jenkins

Es una herramienta de integración continua que automatiza el proceso de construcción, pruebas, integración y entrega de software. Permite a los equipos de desarrollo detectar y corregir errores de manera temprana en el proceso de desarrollo.

### Docker

Es una plataforma de contendedores que permite empaquetar, distribuir y ejecutar aplicaciones de manera eficiente. Los contenedores de Docker son una forma ligera y portátil de encapsular el software y sus dependencias, lo que facilita el despliegue y la administración de aplicaciones.

### Ansible

Es una herramienta de automatización de la configuración que se utiliza para automatizar tareas de infraestructura y configuración de servidores. Permite al equipo de operaciones automatizar el proceso de configuración y gestión de servidores, lo que puede reducir el tiempo y los errores asociados con la configuración manual.

### Kubernets

Plataforma de orquestación de contenedores que se utiliza para gestionar y escalar aplicaciones en contenedores. Permite a los equipos de operaciones administrar y coordinar múltiples contenedores en diferentes máquinas, lo que puede simplificar la administración y el despliegue de aplicaciones en entornos de producción.

## Equipos devops

Los equipos Devops se componen típicamente de personas con habilidades y responsabilidades específicas, que trabajan juntas para desarrollar, implementar y mantener aplicaciones y sistemas de software. Aquí se presentan algunas de las funciones y responsabilidades comunes dentro de los equipos DevOps:

1. Desarrollo de software: Este equipo es responsable de escribir y mantener el código fuente de las aplicaciones. Utilizan herramientas de control de versiones y colaboran con el equipo de operaciones para asegurarse de que el software se pueda implementar y ejecutar de manera eficiente.

2. Operaciones TI: Este equipo es responsable de implementar, configurar y administrar los sistemas y servicios que ejecutan las aplicaciones. Utilizan herramientas de automatización y orquestación para gestionar los servidores, redes y otros componentes de la infraestructura TI.

3. QA y pruebas de software: Este equipo es responsable de desarrollar y ejecutar prueabas para garantizar la calidad del software. Trabajan con el equipo de desarrollo para desarrollar casos de prueba, ejecutar pruebas de regresión y realizar pruebas de integración.

4. Seguridad de la información: Este equipo es responsable de proteger los sitemas y datos de la organización. Desarrollan políticas de seguridad, realizan pruebas de penetración y monitorean la seguridad de los sistemas y redes.

5. Soporte al cliente: Este equipo es responsable de proporcionar soporte y asistencia a los usuarios finales de las aplicaciones. Responden a los tickets de sporte, resuelven problemas y trabajan con otros equipos de DevOps para corregir errores y mejorar la funcionalidad de las aplicaciones.

## Pipelines

En DevOps, un pipeline es un conjunto de pasos automatizados que se ejecutan en secuencias para implementar, probar y entregar una aplicación de software. Estos pasos pueden incluir desde la compilación del código fuente, la ejecución de pruebas unitarias y de integración, hasta la implementación en un entorno de producción.

En un pipeline típico, cada paso es una tarea automatizada que se ejecuta en una etapa específica del proceso de entrega de software. Por ejemplo el primer paso prodría ser la compilación del código fuente, seguido por la ejecución de pruebas unitarias, pruebas de integración y finalmente la implementación en un entorno de producción. Cada paso puede estar asociado con una herramienta o script específico que se encarga de realizar la tarea correspondiente.

Los pipelines están diseñados para automatizar el proceso de entrega de software y garantizar que cada cambio en el código sea probado y entregado de manera confiable y repetible. Al automatizar estos procesos, se puede reducir el tiempo necesario para implementar cambios y mejorar la calidad del software entregado.

## Ejemplo de pipeline

1. Etapa de compilación: En esta etapa, el código fuente se compila en un paquete de software que se puede implementar en diferentes entornos. Se utiliza una herramienta de compilación como Maven, Gradle o MSBuild para realizar esta tarea.

2. Etapa de pruebas unitarias: En esta etapa, se ejecutan pruebas automatizadas para asegurarse de que el código cumpla con los requisitos y funcione correctamente. Se utilizan herramientas de prueba como JUnit, NUnit o PHPUnit para realizar estas pruebas.

3. Etapa de pruebas de integración: En esta etapa, se ejecutan pruebas automatizadas para asegurarse de que los diferentes componentes de la aplicación funcionen correctamente juntos. Se utilizan herramientas de prueba como Selenium, Cucumber o Postman para realizar estas pruebas.

4. Etapa de implementación en un entorno de preproducción: En esta etapa, se implementa la aplicación en un entorno de preproducción para probarla en un entorno similar al de producción. Se utiliza una herramienta de implementación como Ansible, Chef o Puppet para realizar esta tarea.

5. Etapa de pruebas de aceptación: En esta etapa, se ejecutan pruebas manuales para asegurarse de que la aplicación cumpla con los requisitos y expectativas del usuario. Los usuarios finales o los equipos de pruebas manuales pueden realizar estas pruebas.

6. Etapa de implementación en producción: En esta etapa, la aplicación se implementa en un entorno de producción. Se utiliza una herramienta de implementación como Ansible, Chef o Puppet para realizar esta tarea.

7. Cada una de estas etapas se puede automatizar y configurar en un pipeline de DevOps. El pipeline asegura que cada etapa se ejecute en orden y que se realicen las pruebas y comprobaciones necesarias antes de la implementación en producción. Además, el pipeline proporciona un registro de cada etapa y permite identificar rápidamente cualquier problema que pueda surgir durante el proceso de entrega de software.

=======

Yeison

## ¿Que Es?

El término DevOps, que es una combinación de los términos ingleses development (desarrollo) y operations (operaciones), designa la unión de personas, procesos y tecnología para ofrecer valor a los clientes de forma constante.

¿Qué significa DevOps para los equipos? DevOps permite que los roles que antes estaban aislados (desarrollo, operaciones de TI, ingeniería de la calidad y seguridad) se coordinen y colaboren para producir productos mejores y más confiables. Al adoptar una cultura de DevOps junto con prácticas y herramientas de DevOps, los equipos adquieren la capacidad de responder mejor a las necesidades de los clientes, aumentar la confianza en las aplicaciones que crean y alcanzar los objetivos empresariales en menos tiempo.

![](https://orangematter.solarwinds.com/wp-content/uploads/2022/03/DevOps-lifecycle-capabilities-1024x621.png)

## ¿Para Que Sirve?

DevOps sirve para mejorar y acelerar el proceso de desarrollo de software, mediante la automatización, integración y colaboración entre los equipos de desarrollo, operaciones y seguridad.

En lugar de trabajar de forma aislada y secuencial, los equipos de DevOps trabajan de manera colaborativa y simultánea, lo que les permite detectar y solucionar problemas de manera más rápida y eficiente, así como entregar software de manera más frecuente y con mayor calidad.

Además, DevOps fomenta la cultura de la mejora continua, lo que significa que los equipos están constantemente buscando formas de optimizar y mejorar el proceso de desarrollo y entrega de software.


### Beneficios y Contras

## Beneficios
- **Mayor velocidad y frecuencia en el lanzamiento de software.**
- **Mejora en la calidad del software**, debido a la automatización de pruebas y procesos de integración continua.
- **Reducción en el tiempo de resolución de problemas**, gracias a la detección temprana y la resolución rápida de problemas.
- **Mayor colaboración y comunicación entre los equipos de desarrollo, operaciones y seguridad.**
- **Mayor eficiencia y reducción de costos**, gracias a la automatización de tareas manuales y repetitivas.
- **Promueve la cultura de la mejora continua**, lo que significa que los equipos están constantemente buscando formas de optimizar y mejorar el proceso de desarrollo y entrega de software.

## Contras:

- **Aumento en la complejidad del proceso**, debido a la necesidad de integrar herramientas y procesos de desarrollo y operaciones.
- **Requiere un mayor conocimiento y habilidades técnicas**, lo que puede resultar en la necesidad de capacitar al personal.
- **Requiere un cambio cultural en los equipos**, ya que la metodología de DevOps promueve una mayor colaboración y responsabilidad compartida entre los equipos de desarrollo, operaciones y seguridad.
- **Puede ser costoso implementar y mantener herramientas y tecnologías de automatización y gestión de infraestructuras.**

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

Enlace de Interes https://devopsdays.io/

=======
Nevardo
# Resumen de DevOps


# Contenido:

# **Que es ?**

DevOps es una filosofía en constante evolución que busca mejorar el desarrollo de aplicaciones y 
publicar nuevas funciones de software rápidamente. Se promueve la comunicación, colaboración,
integración, visibilidad y transparencia entre equipos de desarrollo de aplicaciones y 
operaciones tecnológicas. La relación entre Dev y Ops se extiende a cada fase del ciclo de vida de DevOps. 
Esta relación impulsa un bucle de retroalimentación continua con los clientes sobre las mejoras y
cambios que se necesitan en las funciones. El resultado de estos esfuerzos puede ser la publicación continua
y más rápida de las adiciones y los cambios que se necesitan en las funciones.

# **Para que sirve?**
DevOps mejora el proceso de desarrollo y entrega de software mediante la colaboración 
y comunicación entre los equipos de desarrollo y operaciones. 
La automatización de tareas reduce errores y aumenta la productividad, lo que lleva a una entrega 
de software más rápida y de mayor calidad.

# **Beneficios y contras?**
### Beneficio

* Una mejor y más rápida entrega de productos
* Entornos de funcionamiento más estables
* Mejor escalabilidad y disponibilidad
* Resolución de problemas en menos tiempo y con menor complejidad
* Mayor visibilidad de resultados del sistema

### Contras
* Proceso de resolución de problemas alargado
* Comunicación incompetente del equipo
* Configuración de operación inestable
* Más complejidad para administrar
* Tiempo de ciclo más largo

# **Herramientas de devops**

DevOps utiliza una serie de herramientas diferentes en todo el ciclo de vida del software, 
desde el desarrollo hasta la entrega. Estas herramientas se coordinan y se integran en varias actividades
de producción, incluyendo la planificación, creación, verificación, empaquetado, liberación, configuración,
supervisión y control de versiones. Existen diversas herramientas de DevOps que se pueden segmentar 
según las actividades de producción en las que se pueden utilizar. En general, el objetivo es optimizar
el proceso de producción y ofrecer software de mayor calidad y más rápido al cliente. 
Estas son algunas de las herramientas.

* Jenkins
* Docker
* Puppet
* Apache Maven
* Gradle
* CircleCI
* Bamboo
* Buddy
* Git
* GitHub



# **Equipos devops**

Los equipos de DevOps son grupos que combinan desarrolladores de software y 
personal de operaciones tecnológicas para trabajar en conjunto durante todo 
el ciclo de vida del software, con el objetivo de mejorar la colaboración,
la comunicación y la coordinación entre departamentos. Estos equipos pueden 
incluir a otros profesionales, como especialistas en seguridad, automatización 
y gestión de proyectos, según las necesidades de la organización. Todo esto se 
traduce en una entrega de software más rápida y de mejor calidad.

# **Que son pipelines**

Es un proceso automatizado que permite a los equipos de desarrollo de software y
operaciones tecnológicas trabajar de manera colaborativa para entregar código de
software de manera rápida y confiable. Un pipeline típico de DevOps consta de varias fases, 
como la compilación de código, pruebas unitarias, integración de código, pruebas de integración,
empaquetado, despliegue y monitoreo. Cada fase del pipeline se ejecuta de manera automatizada, 
lo que reduce los errores humanos y permite una entrega más rápida de software a los clientes.
Los pipelines también pueden incluir herramientas de monitoreo y análisis de métricas que ayudan 
a los equipos a identificar problemas y a optimizar su proceso de entrega de software.

# **Ejemplos de pipeline**

* Pipeline de seguridad:integra pruebas de seguridad en el proceso de entrega de software.
* Pipeline de infraestructura como código: Pipeline de automatización de la configuración de 
  infraestructura de software, que incluye creación de servidores virtuales, instalación y 
  configuración de software y bases de datos.
* Pipeline de pruebas automatizadas: Este tipo de pipeline automatiza pruebas de software,
* desde pruebas unitarias hasta pruebas funcionales. El objetivo es garantizar que el software
* cumpla con los requisitos y funcione correctamente antes de su entrega.




![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMaAO037ARx6uJO_jkQvXF5UAI3i-hn1nbbsvtotuYIHUogezLyofZctQzUbQY-SGlW74&usqp=CAU)

![](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcRf7uUEqaTJCS511O90ot43AnsfSZ4IoId90cKau3B51wS1-13m)
