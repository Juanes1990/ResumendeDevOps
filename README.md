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

=======

Gretty
# Resumen de DevOps


## Contenido:

### **1. ¿Qué es DevOps?**

Development &rarr; desarrollo y Operations &rarr; operaciones

DevOps es una práctica complementaria al desarrollo de software ágil, su principal propósito es hacer más rápido el ciclo de vida del desarrollo de software, facilitando una entrega continua de alta calidad y actividad constante de una manera más eficiente. 

![](https://lh6.googleusercontent.com/O7PX4R3FGXkAF2iD8H1C9Yht6-msuEH_UnC7Ev0sM8mO2xex5whMCySABXqCdyrSKUwwdG6htMEdFl3t7NhwjgdLojzFAdW6M6HQf4G7quyA6YZnwnwutC1-jv3297uyPSlq0vnx=s0)
> Imagen tomada de: https://www.itdo.com/blog/

**Fases:**

* _Planeación:_ Definición de los requisitos y valores empresariales. 
* _Codificación:_ Diseño y creación del software. 
* _Compilación:_ Administración de versiones y compilaciones de manera automatizada para publicar el código en producción.
* _Prueba:_ Se crean pruebas de manera constante (manuales o automatizadas) para asegurar calidad del software.
* _Lanzamiento:_ Contiene una serie de cambios como mejoras, nuevas características, corrección de errores, entre otros, durante el ciclo de vida del software.
* _Despliegue:_ Se pone en marcha la aplicación o software en un ambiente de producción después de ser validado. 
* _Operar:_ Supervisión y mantenimiento del Software para garantizar su correcto funcionamiento.
* _Monitorizar:_ Observación del desempeño y la disponibilidad de los sistemas y aplicaciones en uso, con el objetivo de identificar posibles problemas o cuellos de botella, y tomar medidas para resolverlos antes de que afecten a los usuarios.


### **2. ¿Para qué sirve?**
Ayuda a las empresas a mejorar la creación y entrega de software al fomentar la colaboración entre equipos de trabajo, la automatización y la mejora continua en todo el ciclo de vida del software. Esto permite que el trabajo sea más eficiente, la entrega del producto sea más rápida, con menos errores y de mejor calidad, generando una mayor satisfacción del usuario final.


### **3. ¿Cuáles son sus ventajas y desventajas?** 
| Ventajas  | Desvenjatas |
| --------- | --------- |
| Desarrollo más rápido del producto. | La empresa no logre familiarizar a los trabajadores. | 
| Plazos más cortos entre actualizaciones y nuevas versiones. | Podría requerir de una inversión inicial en herramientas y procesos  |
| Mayor calidad del producto gracias a la evaluación constante. | Mayor presión sobre los equipos de desarrollo y operaciones. |
| Mayor productividad al fomentar la colaboración entre equipos los de trabajo. | Generar dependencia en determinadas herramientas, lo cual podría ocasionar problemas si estas fallan o no están disponibles.|
| Mayor satisfacción del usuario final. | Implica tener un cambio cultural en la organización. |


### **4. Herramientas de devops**

![](https://i0.wp.com/blog.educacionit.com/wp-content/uploads/2021/06/2-1.png?ssl=1)
> Imagen tomada de: https://blog.educacionit.com/


### **5. Equipos devops**
* _Equipos de desarrollo:_ Son los responsables del diseño y desarrollo del producto. 
* _Operaciones:_ Son los responsables de asegurar que los sistemas y aplicaciones se ejecuten sin problemas en un entorno de producción. 


### **6. ¿Qué son pipelines?**
Grupo de procesos automatizados que abarca desde el proceso de integración continua (CI), que implica la compilación y prueba de código cada vez que se realizan cambios, hasta la entrega continua (CD), que implica la automatización del proceso de despliegue de software en los entornos de producción.


### **7. Ejemplos de pipeline**
* Compilación de código fuente.
* Pruebas unitarias y de integración.
* Análisis estático de código.
* Análisis de seguridad.
* Pruebas de aceptación del usuario.
* Despliegue en entornos de pruebas.
* Despliegue en entornos de producción.

=======

Melissa
# ⭐Que es ?
*Responde a la pregunta: ¿Como dos departamentos, Desarrollo y Operaciones, trabajan juntos en colaboración?*

Devops es una cultura de colaboración entre los equipos de desarrollo y los equipos de operaciones, es romper los silos organizacionales del testing y desarrollo creados antiguamente y hacer una comunicación entre ellos , teniendo en cuenta que no se trata de que las personas pierdan su especialización o rol, sino de que todos puedan colaborar en el ciclo completo del desarrollo.
![imagen de introduccion](https://static.vecteezy.com/system/resources/previews/003/250/944/original/team-of-programmer-concept-with-devops-software-development-free-vector.jpg)

## ⭐Para que sirve?
- Esta cultura, sirve para:
- aportar valor entregando software rápidamente 
- crear productos mejores, de más calidad y más confiables 
- responder mejor a las necesidades de los clientes
- aumentar la confianza en las aplicaciones que se crean, y
- alcanzar los objetivos empresariales en menos tiempo  


## ⭐Beneficios y contras?
### 🙂Beneficios: 
- aumenta la cooperación y el entendimiento entre los departamentos implicados: desarrollo y operaciones.
- incrementa la producción y el despliegue 
- aumenta la agilidad que resulta en una mejora a la calidad pues se van verificando los productos desde las etapas más tempranas de desarrollo
- automatización de procedimiento de control contra amenazas que ofrece una mayor seguridad en las aplicaciones construidas
- la entrega continua permite una mayor flexibilidad y adaptación al entorno 

### 😪Contras:
- Implementar DevOps puede ser un desafío, ya que requiere cambios culturales, de procesos y de tecnología
- DevOps puede ser costoso, especialmente si la empresa no tiene la infraestructura y las herramientas adecuadas
- Los empleados pueden resistirse a los cambios que se producen con la implementación de DevOps, especialmente si no se les comunica adecuadamente los beneficios de la metodología
- DevOps se basa en la automatización de procesos, lo que puede crear dependencia de la tecnología y generar riesgos de fallos si no se mantiene adecuadamente

## ⭐herramientas de devops:
- Docker: es una plataforma de contenedores que permite empaquetar una aplicación y sus dependencias en un contenedor aislado y portable.
- Kubernetes: permite la administración de sistemas distribuidos complejos para desarrolladores que trabajen con contenedores Linux
- GitHub: plataforma de control de versiones de desarrollo 
- Jenkins: se utiliza para informar cambios, realizar pruebas en vivo y distribuir código en varias maquinas 
- Grafana: permite conectar con multitud de fuentes de datos para el análisis de datos 
- Prometheus: herramientas de supervisión y alertas para contenedores y microservicios
- Ansible: es una herramienta de automatización de infraestructura que permite configurar y administrar servidores de manera eficiente.
- Terraform: es una herramienta de infraestructura como código que permite definir y gestionar la infraestructura en la nube de manera programática
- Nagios: es una herramienta de monitoreo de sistemas y aplicaciones que permite recopilar métricas y alertar sobre problemas
![imagen de introduccion](https://blog.educacionit.com/wp-content/uploads/2021/06/2-1.png)

## ⭐Equipos devops:
Es un equipo enfocado en la colaboración con el fin de entregar un Software de manera rápida y de mayor calidad. Compuesto por :
- Desarrolladores de Software: son los encargados de escribir el código fuente de la aplicación, asegurándo que se cumpla con los requisitos del cliente y se integre correctamente con las demás partes del sistema 
- Ingenieros de operaciones: encargados de configurar y mantener los servidores y sistemas en los que se ejecuta la aplicación
- Especialistas en automatización: son los encargados de automatizar tareas repetitivas y manuales
- Especialistas en Seguridad: encargados de garantizar que el sistema sea seguro y esté protegido contra amenazas externas e internas
- Especialistas en Calidad: son los encargados de asegurar que el software cumpla con los estándares de calidad requeridos
- Especialistas en análisis de Datos: son los encargados de recopilar y analizar datos sobre el sistema y la aplicación. Utilizan esta información para identificar cuellos de botella, puntos débiles y oportunidades de mejora
![imagen de equipo Devops](https://kinsta.com/es/wp-content/uploads/sites/8/2021/04/herramientas-devops-1024x512.png)

## ⭐que son pipelines:
Pipelines o tuberías de datos es una forma automatizada y eficiente de entregar software de alta calidad, es decir que hace referencia a un conjunto de procesos automatizados y herramientas que permiten la entrega rápida y confiable de software de alta calidad, desde el código fuente hasta la implementación en producción.

Un pipeline de entrega de software común empieza con la integración continua (CI) que implica la construcción y pruebas automatizadas del código fuente. Si esta construcción y las pruebas son exitosas, entonces el código se envía a la entrega continua (CD)que es donde se realiza una serie de pruebas adicionales y se prepara para la implementación en producción. Finalmente, el código se implementa en producción de forma automatizada, lo que reduce el riesgo de errores y tiempos de inactividad.

## ⭐ejemplos de pipeline:
- Pipeline de entrega continua de una aplicación web
- Pipeline de gestión de configuración: se utiliza para automatizar la gestión de la configuración del sistema. El pipeline comienza con la definición de la configuración como código, lo que implica la escritura de scripts y configuraciones que definen la configuración del sistema. Luego, los scripts se prueban y se validan mediante pruebas automatizadas antes de implementarse en el sistema real
- Pipeline de pruebas de aceptación del usuario: se utiliza para realizar pruebas automatizadas de aceptación del usuario en una aplicación o servicio. El pipeline comienza con la definición de los requisitos de aceptación del usuario, seguido de la creación de pruebas automatizadas que verifican si se cumplen los requisitos. Luego, se ejecutan las pruebas y se analizan los resultados.
>>>>>>> feature/melissa
=======
Cristhian
# ResumendeDevOps


# Contenido:
=======

Contenido:
>>>>>>> feature/ivan

## Que es?

<<<<<<< HEAD
DevOps es una filosofía o conjunto de prácticas que se enfoca en la colaboración y la comunicación entre los equipos de desarrollo y operaciones de TI, con el objetivo de acelerar la entrega de software y mejorar la calidad del mismo. Se originó a partir de la necesidad de mejorar la colaboración entre los equipos de desarrollo y operaciones, y cómo ha evolucionado para incluir otras áreas, como la seguridad y el monitoreo de sistemas. También destaca la importancia de la automatización y cómo puede mejorar la eficiencia y la calidad del software.
La automatización es una parte clave de DevOps, y esta filosofía se ha expandido para incluir otras áreas como la seguridad y el monitoreo de sistemas.

## Para que sirve?

La cultura de equipo colaborativa y ágil que fomenta DevOps es muy importante. Los equipos de desarrollo y operaciones trabajan juntos en un ambiente de colaboración y comunicación, lo que permite que la información fluya libremente y que los problemas se solucionen más rápidamente. Además, al trabajar juntos de manera constante, los equipos pueden construir una mejor comprensión de las necesidades del negocio y de los requisitos de los usuarios, lo que a su vez les permite desarrollar software que es más relevante y útil.
DevOps ayuda a reducir el tiempo que se necesita para desarrollar y entregar el software. Esto es especialmente importante en un mundo en el que las empresas necesitan responder rápidamente a los cambios en el mercado y en las necesidades de los usuarios. DevOps permite a las empresas ser más ágiles, lo que a su vez les permite mantenerse competitivas.


## Beneficios y contras?

### Pros:

- Mayor colaboración y comunicación entre los equipos de desarrollo y operaciones, lo que permite una entrega más rápida y efectiva de software.
- Mayor automatización de tareas, lo que puede reducir el tiempo de inactividad y errores humanos.
- Mayor enfoque en la calidad del software y la satisfacción del cliente.
- Mayor capacidad de respuesta a las necesidades del mercado y del cliente.
- Mayor visibilidad y transparencia en todo el proceso de entrega de software.

### Contras:

- Implementar DevOps puede requerir una inversión significativa de tiempo y recursos.
- Puede ser difícil para los equipos cambiar su forma de trabajo y adaptarse a la cultura de DevOps.
- Se necesita una buena planificación y coordinación para garantizar que los cambios en el software se realicen de manera segura y sin interrupciones en los servicios.
- Se requiere un alto nivel de confianza y colaboración entre los equipos de desarrollo y operaciones.
- La automatización puede reducir la necesidad de personal, lo que puede tener un impacto en los empleados y la cultura de la empresa.

### Herramientas de devops

Las herramientas que son comúnmente son utilizadas en la metodología DevOps son las siguientes:

- Control de versiones: Tenemos como herramienta Git. Es una herramienta de control de versiones distribuida y de código abierto que permite a los equipos colaborar en el desarrollo de software.

- Integración continua: Tenemos como herramienta Jenkins. Jenkins es una herramienta de automatización de construcción que permite a los equipos compilar, probar y entregar software automáticamente.

- Gestión de configuración: Tenemos como herramienta Ansible. Ansible es una herramienta de automatización de TI que permite a los equipos configurar y administrar servidores de manera eficiente.

- Provisionamiento de infraestructura: Tenemos como herramienta Terraform. Terraform es una herramienta de código abierto que permite a los equipos definir y automatizar la infraestructura en la nube.

- Orquestación de contenedores: Tenemos como herramienta Kubernetes. Kubernetes es una plataforma de orquestación de contenedores de código abierto que permite a los equipos automatizar la implementación, la escalabilidad y la administración de contenedores.

- Monitoreo y registro: Tenemos como herramienta Prometheus. Prometheus es una herramienta de monitoreo de código abierto que permite a los equipos recopilar métricas y datos de registro para analizar el rendimiento de su software.

### Equipos devops

Los integrantes que podemos encontrar en los equipos DevOps son los siguientes:

- Product Owner: Es el responsable de definir las funcionalidades del producto y de mantener el backlog del producto actualizado. El backlog es una lista priorizada de todas las funcionalidades del producto que se deben desarrollar en el futuro. El Product Owner trabaja estrechamente con el equipo de desarrollo para definir los requisitos y priorizarlos en función de su importancia para el negocio. También es responsable de tomar decisiones sobre qué características son las más importantes para el negocio y cuáles deben ser desarrolladas primero.

- El Scrum Master: Es el responsable de asegurarse de que el equipo de desarrollo está siguiendo los procesos y prácticas adecuados de Scrum. También actúa como un facilitador para el equipo, ayudándoles a resolver problemas y a mejorar continuamente. El Scrum Master también se encarga de organizar y coordinar reuniones, tales como las reuniones diarias de Scrum, la revisión del sprint y la retrospectiva del sprint. Además, es responsable de asegurarse de que el equipo de desarrollo está comprometido con la entrega del software en cada sprint.

- El Development Team: Este grupo de personas trabaja juntos para construir y entregar el software. El equipo de desarrollo puede incluir desarrolladores de software, diseñadores, analistas y otros roles relacionados con el desarrollo de software. El equipo de desarrollo es responsable de cumplir con los objetivos del sprint y de entregar software funcional al final de cada sprint. Trabajan en estrecha colaboración con el Product Owner para entender los requisitos del cliente y con el Scrum Master para asegurarse de que están siguiendo los procesos de Scrum.

- El Stakeholder: Es cualquier persona o grupo que tenga un interés en el proyecto de software, como los usuarios finales, los clientes, los gerentes, los patrocinadores, los accionistas, entre otros. Los Stakeholders son una parte importante del proceso de desarrollo de software, ya que proporcionan retroalimentación sobre el software en desarrollo y pueden tener requisitos que deben ser considerados durante el desarrollo. El Product Owner es responsable de interactuar con los Stakeholders para asegurarse de que sus necesidades sean entendidas y priorizadas en el backlog del producto.

- QA Team: El equipo de control de calidad (QA) se encarga de asegurar la calidad del software desarrollado por el equipo de desarrollo. El equipo de QA puede incluir ingenieros de pruebas, analistas de pruebas y otros roles relacionados con el control de calidad del software. Los miembros del equipo de QA se aseguran de que el software cumpla con los requisitos y está libre de errores antes de su lanzamiento. También pueden crear planes de pruebas y realizar pruebas de aceptación y pruebas de integración para asegurar la calidad del software.

- Solution Architect: El arquitecto de soluciones es responsable de diseñar y definir la arquitectura del sistema de software. El arquitecto de soluciones trabaja en estrecha colaboración con el Product Owner y el equipo de desarrollo para comprender los requisitos del negocio y diseñar soluciones de software que satisfagan esos requisitos. El arquitecto de soluciones también puede proporcionar orientación técnica al equipo de desarrollo y asegurarse de que se sigan las mejores prácticas de diseño de software.

- Platform Engineer: El ingeniero de plataforma es responsable de diseñar, implementar y mantener la infraestructura de software necesaria para ejecutar y entregar el software desarrollado por el equipo de desarrollo. El ingeniero de plataforma puede trabajar en áreas como la automatización de la implementación, el monitoreo y la escalabilidad del software. También se encarga de mantener la infraestructura actualizada y asegurarse de que esté disponible para el equipo de desarrollo en todo momento.

### Que son pipelines?

Los pipelines son una forma automatizada de construir, probar y lanzar software. Estos pipelines se crean mediante el uso de herramientas de automatización de CI/CD, y se pueden personalizar para satisfacer las necesidades específicas del equipo de desarrollo.

El proceso de pipeline comienza con la integración continua (CI), donde se integran los cambios de código en una única rama principal y se realiza una serie de pruebas automáticas. Si las pruebas son exitosas, el software se empaqueta y se pasa a la entrega continua (CD), donde se realiza la entrega del software a los usuarios finales.

Existen varias herramientas de pipeline disponibles, como Jenkins, Azure DevOps, GitLab CI/CD y GitHub Actions. Cada una de estas herramientas tiene sus propias características y ventajas, y es importante elegir la herramienta adecuada para el equipo de desarrollo.

### Ejemplo de pipeline

https://www.youtube.com/watch?v=XIuZiWZDqYU
>>>>>>> feature/Cristhian
=======
Ivan
DevOps es una filosofía de trabajo que se enfoca en mejorar la colaboración entre los equipos de desarrollo y operaciones,
automatizar los procesos de desarrollo y operaciones, y buscar la mejora continua en el ciclo de vida del software.

Esto se logra mediante la implementación de prácticas como la integración continua, entrega continua, despliegue continuo,
pruebas continuas y monitorización constante del software en producción. Con DevOps, se busca aumentar la eficiencia y la
calidad del desarrollo de software, permitiendo que los equipos entreguen software de manera rápida, confiable y con mayor
frecuencia.

Para que sirve?

DevOps sirve para mejorar la eficiencia y calidad en el desarrollo de software, permitiendo que los equipos entreguen
software de manera rápida, confiable y con mayor frecuencia.

Al implementar DevOps, los equipos de desarrollo y operaciones trabajan juntos para automatizar los procesos de desarrollo
y despliegue de software, lo que reduce los tiempos de espera y aumenta la calidad del software entregado. Además, las
pruebas y la monitorización continuas permiten detectar errores lo antes posible y garantizar que el software se ejecute
de manera óptima en producción.

En resumen, DevOps sirve para optimizar el ciclo de vida del software, mejorar la colaboración entre equipos, aumentar la calidad y rapidez de la entrega de software, y permitir a las empresas ser más competitivas en el mercado.

Beneficios y contras?

Beneficios:

- Mayor eficiencia y rapidez: DevOps permite que los equipos entreguen software de manera más rápida y eficiente gracias
a la automatización de procesos y la colaboración entre equipos.

- Mayor calidad: La integración continua, entrega continua, despliegue continuo, pruebas continuas y monitorización
constante del software en producción permiten detectar errores lo antes posible y asegurar la calidad del software
entregado.

- Mayor colaboración entre equipos: DevOps fomenta la colaboración entre los equipos de desarrollo y operaciones,
lo que permite una mejor comunicación y trabajo en equipo.

- Mayor agilidad en la entrega: DevOps permite a los equipos de desarrollo realizar cambios y despliegues de software
de manera más ágil y con menor riesgo de errores.

- Mejora continua: DevOps se basa en la mejora continua, lo que permite a los equipos de desarrollo y operaciones
identificar áreas de mejora y trabajar en ellas para optimizar el ciclo de vida del software.

- Mejora en la satisfacción del cliente: DevOps permite a las empresas ofrecer software de alta calidad y sin errores,
lo que mejora la satisfacción del cliente y la retención de clientes.

- Mayor capacidad de innovación: DevOps fomenta la experimentación y la innovación, permitiendo que los equipos de
desarrollo prueben nuevas ideas y funcionalidades de manera rápida y eficiente.

- Reducción de costos: DevOps puede reducir los costos operativos al permitir una mayor automatización y eficiencia en
los procesos de desarrollo y despliegue de software.

- Mayor transparencia y visibilidad: DevOps permite una mayor transparencia y visibilidad en el ciclo de vida del
software, lo que permite a los equipos de desarrollo y operaciones identificar y solucionar problemas de manera más
rápida y eficiente.

- Mayor flexibilidad y escalabilidad: DevOps permite a las empresas adaptarse rápidamente a los cambios en el mercado y
escalar sus operaciones de manera más eficiente.

Contras:

- Costo y tiempo de implementación: La implementación de DevOps puede ser costosa y llevar tiempo, especialmente si se
requiere la adquisición de nuevas herramientas y tecnologías.

- Cambio cultural: La implementación de DevOps puede requerir un cambio cultural en la organización, ya que es necesario
fomentar la colaboración y el trabajo en equipo entre los equipos de desarrollo y operaciones.

- Requiere habilidades técnicas: La implementación de DevOps requiere habilidades técnicas y conocimientos específicos
en herramientas y tecnologías de automatización.

- Seguridad: DevOps puede aumentar el riesgo de vulnerabilidades de seguridad si no se implementa adecuadamente.

- Complejidad: La implementación de DevOps puede ser compleja debido a la cantidad de herramientas y tecnologías
involucradas, lo que puede aumentar la complejidad del ciclo de vida del software.

- Riesgo de errores: La automatización de procesos puede aumentar el riesgo de errores si no se implementa adecuadamente.

- Falta de experiencia: La implementación de DevOps puede requerir habilidades técnicas y conocimientos específicos que
no estén disponibles en la organización.

- Dependencia de herramientas y tecnologías: La implementación de DevOps puede crear una dependencia de ciertas
herramientas y tecnologías, lo que puede dificultar la migración a nuevas tecnologías en el futuro.

- Dificultad para medir el ROI: Es posible que sea difícil medir el retorno de inversión (ROI) de la implementación
de DevOps, especialmente si la mejora de la eficiencia y calidad del software no se traduce directamente en ingresos.

herramientas de devops

- Control de versiones: Git, SVN
- Integración continua: Jenkins, CircleCI, Travis CI
- Entrega continua: AWS CodePipeline, Azure DevOps, GitLab CI/CD
- Despliegue continuo: Kubernetes, Docker, AWS Elastic Beanstalk
- Monitorización y análisis: Nagios, New Relic, Prometheus
- Automatización de infraestructura: Ansible, Terraform, Chef
- Colaboración: Slack, Microsoft Teams, Asana
- Gestión de la configuración: Puppet, SaltStack
- Pruebas: Selenium, JUnit, NUnit

Equipos devops

- Desarrolladores: Son los encargados de escribir el código y asegurar que este se integre correctamente en el repositorio
de código.

- Ingenieros de operaciones: Son los encargados de garantizar que la infraestructura y los sistemas estén en
funcionamiento y sean escalables, confiables y seguros.

- Ingenieros de automatización: Son los encargados de diseñar, implementar y mantener herramientas y procesos de
automatización para facilitar la integración continua, la entrega continua y el despliegue continuo.

- Especialistas en seguridad: Son los encargados de garantizar la seguridad de las aplicaciones y sistemas, asegurándose
de que se implementen los controles de seguridad adecuados y de que se realicen las pruebas de seguridad necesarias.

- Especialistas en monitoreo y análisis: Son los encargados de monitorear el rendimiento y la disponibilidad de las
aplicaciones y sistemas, así como de analizar los datos para identificar posibles problemas y oportunidades de mejora.

que son pipelines

Los pipelines son procesos automatizados y estructurados que abarcan desde la etapa de desarrollo hasta la producción. Están diseñados para permitir una entrega rápida y confiable de software, mejorar la calidad del software y fomentar la colaboración entre los equipos de desarrollo y operaciones. Las herramientas y plataformas como Jenkins, Travis CI, CircleCI, AWS CodePipeline y GitLab CI/CD son utilizadas para crear y administrar pipelines, lo que permite a los equipos automatizar el proceso de entrega de software, monitorear el estado del pipeline en tiempo real y proporcionar información valiosa sobre el rendimiento y la calidad del software. Los pipelines son una herramienta clave en el arsenal de DevOps para lograr una entrega continua y despliegue continuo de software de alta calidad.

ejemplos de pipeline

Ejemplo 1:

- Control de versiones: El desarrollador escribe código y lo sube al sistema de control de versiones, como Git.
- Integración continua: Cada vez que se realiza una confirmación de código en Git, Jenkins, una herramienta de integración
continua, verifica y compila el código automáticamente.
- Pruebas: Jenkins ejecuta automáticamente una serie de pruebas unitarias para detectar cualquier problema en el código.
- Entrega continua: Si todas las pruebas pasan, Jenkins empaqueta el código en un artefacto, lo almacena en un repositorio
de artefactos y despliega el artefacto en un entorno de pruebas o de preparación.
- Pruebas de aceptación: Se realizan pruebas adicionales en el entorno de preparación o pruebas de aceptación para
verificar que la nueva funcionalidad se integre sin problemas con el sistema existente.
- Despliegue continuo: Si las pruebas de aceptación son exitosas, Jenkins despliega automáticamente el artefacto en
producción.
- Monitoreo y análisis: Una vez en producción, la plataforma de monitoreo y análisis del sistema, como New Relic, recopila
métricas y proporciona información valiosa sobre el rendimiento del sistema y la calidad del software.

Ejemplo 2:

- Control de versiones: El desarrollador crea una rama de desarrollo y escribe código en su estación de trabajo local.
El desarrollador luego realiza varias confirmaciones de código en Git.
- Integración continua: Jenkins detecta automáticamente las confirmaciones de código y ejecuta una serie de pruebas
unitarias y de integración.
- Validación de código: Jenkins utiliza SonarQube para analizar automáticamente el código en busca de errores,
vulnerabilidades y malas prácticas de codificación.
- Empaquetado de artefactos: Jenkins utiliza Maven para compilar el código y empaquetar el artefacto de la aplicación.
- Pruebas de aceptación: Jenkins despliega el artefacto en un entorno de pruebas, donde se realizan pruebas de aceptación
automatizadas utilizando herramientas de pruebas de comportamiento, como Cucumber.
- Despliegue en producción: Si las pruebas de aceptación son exitosas, Jenkins utiliza Ansible para orquestar el
despliegue de la aplicación en el entorno de producción.
- Monitoreo y análisis: La plataforma de monitoreo y análisis, como Prometheus y Grafana, recopila métricas en tiempo real
y proporciona información valiosa sobre el rendimiento del sistema y la calidad del software.
>>>>>>> feature/ivan
