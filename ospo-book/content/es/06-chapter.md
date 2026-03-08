---
title: "Capítulo 6: Uso de Métricas en tu OSPO"
status: Completed
weight: 70
---

- [Introducción](#introducción)
- [Uso de Métricas para Comunicar el Impacto de tu OSPO](#uso-de-métricas-para-comunicar-el-impacto-de-tu-ospo)
- [Si Gestionas Proyectos de Código Abierto](#si-gestionas-proyectos-de-código-abierto)
- [Si Utilizas Proyectos de Código Abierto](#si-utilizas-proyectos-de-código-abierto)
- [Recursos y Notas al Pie](#recursos-y-notas-al-pie)

## Introducción

> NOTA: Este capítulo ha sido desarrollado a través de la experiencia colectiva del proyecto de código abierto CHAOSS y de los participantes del CHAOSS OSPO Metrics Working Group, con el apoyo del TODO Group.

Las métricas son una parte importante de cualquier organización moderna. Cuando se usan de manera efectiva, ofrecen una forma valiosa de rastrear el impacto de tu equipo y sus proyectos. Para una OSPO, las métricas no solo apoyan la planificación y la medición del impacto de su trabajo, sino que también proporcionan una visión más profunda de los proyectos de código abierto de los que depende la organización.

En el pasado, podría haber sido aceptable saber poco sobre los proyectos clave de código abierto. Pero ese ya no es un enfoque sostenible, dado que el panorama regulatorio y de seguridad en torno al código abierto continúa evolucionando. A medida que profundizamos en la comprensión de los proyectos de código abierto que nos importan, las métricas de la comunidad se convierten en herramientas esenciales. En este capítulo, exploraremos cómo situar esas métricas en contexto y cómo, juntas, pueden ofrecer mejores perspectivas para guiar las decisiones estratégicas de una organización.

Hay varias razones por las que las organizaciones necesitan visibilidad sobre los proyectos de código abierto. Por ejemplo:
* La organización utiliza código abierto y desea rastrear las contribuciones a proyectos clave.
* La organización participa en un ecosistema de código abierto y necesita identificar riesgos potenciales y ofrecer apoyo donde sea necesario.
* La organización quiere contribuir a la sostenibilidad del OSS, especialmente el software que es crítico para su negocio.
* La organización debe mantenerse en cumplimiento con los requisitos de licencia upstream y responder a problemas de seguridad que podrían afectar las operaciones.

### El Marco Objetivo-Pregunta-Métrica

Las métricas por el bien de las métricas no benefician a nadie. Considera estas métricas:

* La edad promedio de los issues es de 10.3 días.
* El número total de pull requests fue de 121 el mes pasado.
* Tuvimos 3 nuevas empresas uniéndose a nuestra comunidad en los últimos 15 días.

Sin contexto, estas métricas no ofrecen ningún insight, por lo que es importante asegurarse de usar un marco como "objetivo-pregunta-métrica" que te proporcione métricas que apoyen tus objetivos en lugar de trabajar en contra de ellos.

El CHAOSS Project (Community Health Analytics for OSS) aboga por usar el enfoque "objetivo-pregunta-métrica" porque es un método estructurado para derivar métricas que se alinean con los objetivos organizacionales. Implica tres pasos clave:

#### Objetivos

Identifica y comprende los objetivos de tu organización. Estos pueden variar significativamente, pero típicamente incluyen metas como reclutar talento o mejorar la participación de la comunidad.

#### Preguntas

Desglosa estos objetivos en preguntas específicas y accionables. Por ejemplo, para evaluar los esfuerzos de reclutamiento, se podría preguntar: "¿Quiénes son los contribuidores importantes?" o "¿A cuántos ayudamos a contratar?".

#### Métricas

Desarrolla métricas para responder a estas preguntas. Las métricas deben ser operativas y basadas en datos, como el número de contribuciones por nombre, éxitos de contratación o niveles de actividad del proyecto. Algunos buenos puntos de datos, como el número de commits (en un proyecto de software), pueden no ser relevantes para la pregunta que necesitas responder.

### Comprendiendo el Rol de las Métricas de la Comunidad de Código Abierto

Vale la pena tomarse un momento para entender cómo las métricas de la comunidad de código abierto apoyan otros tipos de métricas con los que las organizaciones están familiarizadas. Las métricas de la comunidad de código abierto proporcionan a las OSPO formas tangibles de medir la influencia, la efectividad y el valor estratégico de sus iniciativas de código abierto.

Al rastrear contribuciones, niveles de participación y colaboración en proyectos, las OSPO pueden evaluar qué tan bien su organización está participando y apoyando el ecosistema de código abierto.

Estas métricas ayudan a demostrar el impacto del trabajo de código abierto en objetivos de negocio más amplios, como acelerar la innovación, reducir los costos de desarrollo, atraer talento y aumentar la visibilidad del producto. Las métricas también proporcionan información sobre la salud y la sostenibilidad de la comunidad, destacando si un proyecto está ganando tracción, fomentando la colaboración y atrayendo usuarios y contribuidores activos.

Al vincular las métricas de la comunidad con los KPIs organizacionales, las OSPO pueden mostrar el valor del código abierto más allá del código, como mejores ciclos de retroalimentación de productos, tiempos de comercialización más rápidos, relaciones más sólidas con los desarrolladores y mayor credibilidad técnica. Este manual proporciona orientación para que las OSPO rastreen, analicen y comuniquen esas métricas de manera efectiva, traduciendo la participación en código abierto en impacto empresarial medible.

## Uso de Métricas para Comunicar el Impacto de tu OSPO

Las métricas juegan un papel importante en la comunicación del impacto. Siguiendo el enfoque objetivo-pregunta-métrica, aquí hay cuatro objetivos que las OSPO pueden considerar, junto con las preguntas correspondientes.

<img width="750" alt="CHAOSS Health Impacts" src="/images/CHAOSS.Health.Impacts.png" />

### 1: Impacto en Socios

**Objetivo**

Entender cómo la colaboración en código abierto fomenta asociaciones estratégicas que pueden mejorar el conocimiento del mercado, fortalecer las relaciones con los proveedores y crear valor compartido más allá de las tecnologías individuales.

**Comentario**

El trabajo en proyectos de código abierto se basa en la colaboración, una colaboración que a menudo implica asociaciones inesperadas. Estas asociaciones tienen como objetivo desarrollar tecnologías no diferenciadas que cada socio necesita, pero que no necesariamente tiene los recursos o la inclinación para producir por sí solo. Los proyectos de código abierto reúnen a miembros de organizaciones para trabajar juntos en la búsqueda de problemas comunes, y esta proximidad puede generar beneficios más allá de cualquier tecnología compartida de código abierto. Las mejores asociaciones en código abierto pueden tener efectos secundarios positivos, incluyendo lazos más fuertes con los proveedores upstream, una mejor comprensión de las posiciones de los competidores en el mercado e interacción directa con los usuarios downstream.

**Preguntas**

* ¿Qué otras empresas están involucradas en nuestros proyectos de código abierto de interés?
* ¿Qué otras empresas están involucradas en nuestros pull requests?
* ¿Cómo están involucradas otras empresas en nuestros pull requests?
* ¿Cuál es la composición de las empresas involucradas como nuestros proveedores, competidores y clientes?

**Métricas**

Considera qué datos tienes disponibles para poder responder a estas preguntas, y qué otra información necesitarías para tener la confianza suficiente sobre lo que significaría para tus objetivos si el número sube o baja.

### 2: Impacto en la Comunidad

**Objetivo**

Evaluar cómo la participación de los empleados en comunidades de código abierto refleja el apoyo organizacional, fortalece el desarrollo de habilidades individuales y mejora la presencia e influencia de la organización en proyectos clave.

**Comentario**

Hay formas en que una organización puede apoyar la participación de sus empleados en la comunidad (por ejemplo, pautas de contribución, gestión de propiedad intelectual y soporte de licencias). El apoyo generalmente incluye explicar por qué la comunidad es importante para tu organización, lo que incluye un componente de tiempo y priorización en cuanto a cuánto tiempo dedica un empleado al trabajo externo/upstream. Las empresas pueden observar a los empleados como buenos ciudadanos por razones de beneficio personal y organizacional, y ayudar a los empleados a comprender su importancia como puente entre la organización y la comunidad.

**Preguntas**

* ¿Qué porcentaje de las contribuciones de los empleados son aceptadas?
* ¿Qué porcentaje de los issues de los empleados se cierran sin conversación?
* ¿Cuántos de nuestros empleados tienen roles de mantenedor o liderazgo en proyectos clave de código abierto?
* ¿Las contribuciones upstream han ayudado a modernizar las habilidades técnicas de los empleados?
* ¿En qué proyectos nuestros empleados realizan más del 50% de las contribuciones?

**Métricas**

Considera qué datos tienes disponibles para poder responder a estas preguntas, y qué otra información necesitarías para tener la confianza suficiente sobre lo que significaría para tus objetivos si el número sube o baja.

### 3: Impacto en el Ecosistema

**Objetivo**

Monitorear y contribuir a la salud y resiliencia de los ecosistemas de código abierto para garantizar la viabilidad a largo plazo, reducir riesgos y apoyar la sostenibilidad estratégica de las dependencias clave.

**Comentario**

Trabajar con código abierto nunca es sencillo, ya que corporaciones rivales pueden dominar proyectos upstream en los que tu organización está interesada, los proyectos upstream pueden cambiar de licencia inesperadamente, y los acuerdos de contribuidores, ya sean individuales u organizacionales, pueden ser complejos de entender y cumplir. Claramente, estos desafíos pueden superarse y a menudo incluyen una participación estratégica con los proyectos de los que tu organización pretende beneficiarse. Los ecosistemas de código abierto son sistemas económicos y sociales compuestos por diferentes empresas, motivaciones y requisitos destinados a apoyar la producción y las demandas. En un esfuerzo por garantizar la eficiencia y la durabilidad de cualquier ecosistema de código abierto, las empresas no solo deben monitorear la viabilidad a largo plazo del ecosistema, sino también participar en él cuando se identifican problemas y se requiere estabilización.

**Preguntas**

* ¿Qué porcentaje de nuestros proveedores proporciona listas de materiales de OSS?
* ¿Cuál es la viabilidad a largo plazo de los proyectos de código abierto de los que dependemos?
* ¿Cuál es el riesgo para el ecosistema si un proyecto de código abierto se vuelve inviable?

**Métricas**

Considera qué datos tienes disponibles para poder responder a estas preguntas, y qué otra información necesitarías para tener la confianza suficiente sobre lo que significaría para tus objetivos si el número sube o baja.

### 4: Impacto Organizacional

**Objetivo**

Alinear la participación en código abierto con la gobernanza interna, la seguridad y el desarrollo de productos para maximizar el valor del código abierto dentro de la estrategia y las operaciones organizacionales.

**Comentario**

La participación en comunidades de código abierto incluye trabajar en el upstream para usar de manera efectiva el OSS en los productos organizacionales. En esto, existe la necesidad de monitorear la incorporación del OSS por razones de infosec, legales y de ingeniería. Las empresas pueden establecer procesos de incorporación de software, trabajando con equipos para rastrear técnicamente o considerar socialmente los problemas relacionados con la incorporación de código abierto. El impacto organizacional también puede incluir el trabajo downstream con proyectos y empresas que dependen de los productos de tu organización. Esto puede incluir trabajar para obtener una imagen más clara del código abierto presente en los productos entregados. Las organizaciones pueden trabajar en la seguridad y regulación de sus propios procesos internos de código abierto, en un esfuerzo por mejorar las actividades de desarrollo de productos.

**Preguntas**

* ¿Qué características inspecciona una organización en relación con el OSS entrante?
* ¿Qué software e infraestructura a nivel de producto contiene dependencias de OSS?
* ¿Cómo está alineada la estrategia de la OSPO con la estrategia organizacional y los objetivos departamentales?
* ¿Con qué frecuencia se utiliza la estrategia de la OSPO para guiar los procesos de toma de decisiones empresariales?
* ¿Cómo influye el uso del código abierto en el valor organizacional?

**Métricas**

Considera qué datos tienes disponibles para poder responder a estas preguntas, y qué otra información necesitarías para tener la confianza suficiente sobre lo que significaría para tus objetivos si el número sube o baja.

## Si Gestionas Proyectos de Código Abierto

Para las organizaciones que crean y gestionan sus propios proyectos de código abierto, o que están estrechamente involucradas en su gestión, existe una serie de Guías Prácticas de CHAOSS relacionadas con métricas [^1] para orientarte en la identificación de las métricas adecuadas para una selección de casos de uso.

## Si Utilizas Proyectos de Código Abierto

Para las organizaciones que utilizan proyectos de código abierto y desean comprender la salud de dichos proyectos, la siguiente información puede ayudarlas a considerar qué es lo más adecuado para ellas.

### Cómo las OSPO Pueden Navegar las Complejidades de la Salud de los Proyectos de Código Abierto

Comprender la salud de un proyecto de código abierto no es una tarea sencilla. La salud del código abierto abarca muchas preocupaciones diferentes, tanto técnicas como sociales, que pueden aparecer a nivel de proyecto o en todo el ecosistema más amplio. Una revisión de la investigación existente identificó 107 de estas preocupaciones [^2]. Para ayudar a comprender esta complejidad, los investigadores trabajaron con 17 expertos de la industria y la comunidad de código abierto para organizar estas preocupaciones en un marco de 21 aspectos de salud.

Estos aspectos de salud se centran en áreas importantes como:

* Productividad y estabilidad de la comunidad.
* Orquestación y liderazgo del proyecto.
* Procesos de producción y resultados.

Cada aspecto de salud se describe con mayor detalle utilizando atributos, elementos más pequeños y detallados, que ayudan a las organizaciones a examinar la salud del proyecto de manera estructurada.

#### Adaptando el Marco al Contexto Adecuado

Los expertos entrevistados enfatizaron que las organizaciones deben considerar el tipo y las características de cada proyecto de código abierto que están analizando. No todos los proyectos son iguales, y diferentes características pueden influir en cómo evaluar su salud. Los factores importantes a considerar incluyen:

* La etapa del ciclo de vida del proyecto (por ejemplo, fase inicial vs. maduro).
* Su complejidad (qué tan grande y técnicamente exigente es).
* El modelo de gobernanza (cómo se toman las decisiones y quién las toma).
* El valor estratégico que el proyecto tiene para la organización.

Al comparar proyectos de código abierto, las OSPO deben agrupar y evaluar proyectos con características similares. Comparar tipos de proyectos muy diferentes puede llevar a resultados engañosos [^3].

#### Tomando Decisiones Inteligentes Sobre Qué Medir

Cada organización tiene un contexto diferente: distintos mercados, tecnologías y riesgos. Por ello, no existe un enfoque único para evaluar la salud del código abierto. Las OSPO deben:

* Decidir qué aspectos de salud y atributos importan más según las necesidades de su organización.
* Priorizar esfuerzos, ya que medir todo es demasiado costoso y requiere demasiado tiempo.
* Centrarse en los datos que proporcionan los insights más útiles para la gestión de riesgos y la toma de decisiones.

En lugar de intentar medirlo todo a la vez, las OSPO deben comenzar con poco, aprender de los primeros esfuerzos y perfeccionar su enfoque con el tiempo. Las evaluaciones de salud funcionan mejor cuando son parte de un proceso práctico y escalable que evoluciona con la experiencia.

### Caso de Estudio: Cómo una Empresa Automotriz Global Mide la Salud de los Proyectos de Código Abierto

#### Un Enfoque Práctico para Evaluar y Gestionar las Dependencias de OSS

En 2024, Linåker y colegas trabajaron con una gran empresa automotriz internacional para crear una forma sencilla y efectiva de evaluar la salud de los proyectos de software de código abierto (OSS) [^4]. Su caso de estudio muestra cómo las organizaciones pueden personalizar las evaluaciones de salud para adaptarlas a sus necesidades y flujos de trabajo.

#### Construyendo un Proceso de Evaluación de Salud

El equipo comenzó hablando con los empleados a través de entrevistas y grupos de enfoque. Con base en estos conocimientos, desarrollaron un cuestionario breve y un proceso adaptado al entorno de la empresa.

**Características clave del proceso:**

* Inspecciones manuales en la etapa de incorporación mediante listas de verificación estandarizadas.
* Soporte de herramientas automatizadas cuando resulta útil.
* Documentación simple para registrar los hallazgos para futuras revisiones, seguimientos y capacitación.

El objetivo era mantener el proceso ligero y eficiente, al mismo tiempo que se capturaban los riesgos de salud importantes en los proyectos de código abierto.

#### Monitoreando Proyectos Ya en Uso

La empresa también necesitaba una forma de monitorear los proyectos de OSS ya integrados en sus sistemas. Dado que estos proyectos a menudo tienen muchas dependencias, las verificaciones manuales no eran prácticas.

Su solución propuesta:

* Usar herramientas automatizadas para ejecutar verificaciones de salud periódicas.
* Personalizar las herramientas según el ecosistema y el tipo de dependencias.
* Señalar proyectos riesgosos para que los desarrolladores o analistas puedan realizar inspecciones más profundas cuando sea necesario.

Las herramientas de la comunidad CHAOSS, como GrimoireLab y Augur, proporcionan un buen punto de partida. La empresa puede adaptarlas para satisfacer sus necesidades internas.

#### Integrando las Evaluaciones de Salud en el Trabajo Diario

Para que el nuevo proceso fuera exitoso, las recomendaciones del equipo se centraron en la capacitación y la participación del equipo:

* Realizar talleres para presentar las listas de verificación y las herramientas.
* Programar sesiones periódicas de retroalimentación para revisar proyectos de OSS reales.
* Fomentar el debate y el intercambio de conocimientos entre equipos.

Con el tiempo, la empresa puede convertir las evaluaciones de salud de OSS en una parte normal de sus flujos de trabajo de desarrollo de software y aseguramiento de calidad.

#### Qué Pueden Aprender las OSPO

Este caso ofrece lecciones útiles para las OSPO que desean reducir riesgos y mejorar la fiabilidad a largo plazo del OSS.

**Conclusiones clave:**

* Comienza de forma sencilla con listas de verificación manuales y un proceso de incorporación claro.
* Utiliza la automatización para el monitoreo continuo de un gran número de dependencias.
* Integra las evaluaciones de salud en los flujos de trabajo existentes.
* Apoya el proceso con capacitación, herramientas y debates regulares del equipo.

Al identificar los problemas temprano y responder con rapidez, las organizaciones pueden reducir los riesgos y asegurarse de que su software de código abierto permanezca seguro, estable y sostenible.

Los recursos como el CHAOSS Project y el OpenSSF Scorecard pueden ayudar a las OSPO a comenzar o a fortalecer su enfoque.

## Recursos y Notas al Pie

### Recursos

- CHAOSS Project: https://chaoss.community/
- OpenSSF Scorecard: https://github.com/ossf/scorecard
- CHAOSS OSPO Metrics Working Group: https://github.com/chaoss/wg-ospo

### Notas al Pie

[^1]: CHAOSS Practitioner Guides: https://chaoss.community/about-chaoss-practitioner-guides

[^2]: Linåker, J., Papatheocharous, E., & Olsson, T. (2022). How to Characterize the health of an Open Source Software project? A snowball literature review of an emerging practice. In the 18th International Symposium on Open Collaboration. DOI: https://doi.org/10.1145/3555051.3555067

[^3]: Lumbard, K., Germonprez, M., & Goggins, S. (2023). An Empirical Investigation of Social Comparison and Open Source Community Health, Information Systems Journal, 34(2), 499-532: https://onlinelibrary.wiley.com/doi/abs/10.1111/isj.12485

[^4]: Linåker, J., Olsson, T., & Papatheocharous, E. (2024). How to Assess the Health of Open Source Software dependencies in an Organization's Intake Process: Insights from an Interview-survey and Case Study: https://www.linaker.se/assets/slides/OSS_Health_Interview_Survey.pdf
