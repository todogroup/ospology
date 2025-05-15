---
title: "Capítulo 2: El Valor de las Open Source Program Offices"
status: Completed
weight: 40
---

- [Introducción](#introducción)
- [¿Cómo Podría tu OSPO Añadir Valor?](#cómo-podría-tu-ospo-añadir-valor)
- [Aplicando Esto a tu Organización](#aplicando-esto-a-tu-organización)
- [Ejemplos del valor de la OSPO](#ejemplos-del-valor-de-la-ospo)
- [Posibles Problemas y cómo Superarlos](#posibles-problemas-y-cómo-superarlos)
- [Recursos y Notas al Pie](#recursos-y-notas-al-pie)

## Introducción

Probablemente tu organización ya tiene una relación con el open source, incluso si no es consciente de ello. Casi todo el software producido hoy en día incluye componentes open source, o se desarrolla o aloja utilizando herramientas open source. Incluso las organizaciones que no *crean* software suelen *utilizar* software que contiene componentes open source.

Para muchas organizaciones, vale la pena considerar cómo la gestión activa de su relación con el open source puede aportar beneficios y reducir riesgos. Como se mencionó en el capítulo anterior, esto implica comprender el uso actual del open source y luego evaluar cómo podría gestionarse mejor para apoyar los objetivos de la organización.

Este capítulo te ayudará a comprender las posibles áreas donde la gestión del open source a través de una OSPO puede aportar valor a tu organización. Esto será diferente para cada organización, por lo que conocer la estrategia y los objetivos de tu organización es importante.

El trabajo de una OSPO es comprender dónde el open source puede aportar valor a su organización y gestionar o supervisar activamente todas las actividades relacionadas.

Cada organización tendrá sus propias razones para querer iniciar una OSPO; algunas razones comunes dadas en el informe *el valor empresarial de la OSPO* [^1] son las siguientes:

- Construir procesos estandarizados en torno al open source
- Aprender cómo acercarse a la comunidad open source
- Adoptar la sostenibilidad de los proyectos open source
- Gestionar el cumplimiento
- Ampliar el acceso al conocimiento abierto
- Mejorar la velocidad de desarrollo
- Mitigar los riesgos de seguridad

## ¿Cómo Podría tu OSPO Añadir Valor?

### Si Creas Software

Este es un caso de uso común y relativamente completo para una OSPO. Es posible que otras organizaciones solo necesiten considerar un subconjunto de estos problemas.

A veces, los interesados de la organización asumen que su producto no utiliza ningún componente open source porque su producto final no es open source. Sin embargo, cuando se observa toda la cadena de suministro de software, se puede ver que casi todo el software contiene dependencias o artefactos open source. Si los contribuidores que trabajan en esos proyectos open source decidieran marcharse, el proyecto podría volverse obsoleto o ser un objetivo para vulnerabilidades de seguridad. Esto afecta a cualquier software que la organización utilice o venda, y podría impactar directamente su reputación, rendimiento o ingresos.

Una OSPO puede ayudar comprendiendo y gestionando activamente el uso de componentes open source en tu software.

#### Cómo Ayuda la OSPO

- **Gestión de Vulnerabilidades:** Los proyectos open source pueden ser una fuente de vulnerabilidades de seguridad en un producto que depende de ellos. Puede ser difícil hacer un seguimiento de cómo tu organización está utilizando los proyectos open source y realizar evaluaciones de riesgo en los proyectos identificados. Cuando identificas proyectos clave dentro de la organización, puedes priorizar su seguridad mediante el seguimiento de vulnerabilidades y exposiciones comunes. A menudo, el equipo de Arquitectura Empresarial es el que realiza el seguimiento de los componentes open source de las aplicaciones y tecnologías, y las OSPOs están ahí para aportar su experiencia en la materia.

- **Comprensión de los Riesgos en la Cadena de Suministro:** El panorama del open source es amplio y descentralizado, y puede ser difícil identificar quiénes son los contribuidores de los proyectos individuales y realizar evaluaciones de riesgo en los proyectos identificados. Estos factores pueden dificultar que las organizaciones evalúen con precisión los riesgos y comprendan los estándares de seguridad y calidad del software, hardware, datos, etc.

- **Construir Relaciones Saludables con Proyectos Open Source Clave:** Las organizaciones comerciales que utilizan open source suelen estar interesadas en contribuir de nuevo a los proyectos que utilizan. Sin embargo, la presión por lanzar funcionalidades en sus propios productos significa que las contribuciones a open source pueden quedar en segundo plano cuando las cosas se ponen ajetreadas. Incluso cuando se sabe que contribuir con funcionalidades y correcciones de errores al proyecto principal (upstream) requiere menos esfuerzo a largo plazo que mantener una bifurcación del proyecto, las organizaciones a menudo optimizan los beneficios a corto plazo y no dedican el esfuerzo adicional para integrar los cambios en el proyecto principal.

- **Apoyar e Influir en Proyectos Open Source Clave:** Tu organización podría estar en una buena posición para proporcionar recursos a proyectos open source. Esto podría ser a través de codificación, experiencia o donaciones monetarias como incentivos para corregir vulnerabilidades comunes. También podría ser productivo colaborar con grupos de trabajo de la industria para abordar las preocupaciones de seguridad de manera integral. Elaborar un plan que se alinee con la estrategia de tu organización y proporcione valor a los proyectos open source es una buena manera de ser un miembro útil de la comunidad.

- **Cerrar la Brecha entre los Procesos Regulados y los Procesos Open Source:** El open source es un ecosistema dinámico cuyas contribuciones deben ocurrir de la manera más fluida y natural posible. Los largos procesos de adquisición que se enfrentan en entornos altamente regulados, como las empresas financieras y los gobiernos, crean una barrera para la contribución y el compromiso con el open source.

- **Mejorar la Alfabetización en Open Source para Asegurar un Enfoque de Alto Beneficio y Bajo Riesgo:** El concepto de open source puede no tomarse en serio en otras áreas de la organización involucradas en los procesos de toma de decisiones, gestión o formulación de políticas. Esto requerirá una educación constante y la demostración de los riesgos y el valor del open source en la organización.

Para obtener el máximo beneficio del open source y reducir los riesgos, las organizaciones deben invertir en la gestión adecuada de las operaciones open source tanto a nivel cultural como práctico. Esto se logra a menudo a través de la OSPO, ya que fomenta una colaboración interfuncional comprometida dentro de la organización para abordar los problemas de open source que encuentran diversos equipos o departamentos. La OSPO opera como un centro de excelencia.

### Si Ofreces Servicios Públicos

#### Cómo Ayuda la OSPO

Vemos que más organizaciones del sector público se están dando cuenta del valor de una Open Source Program Office para alcanzar sus objetivos de política digital, servir mejor a sus ciudadanos y transformar sus organizaciones para lograr estos objetivos.

Las organizaciones del sector público enfrentan desafíos únicos cuando se trata de gestionar sus operaciones open source, incluida la necesidad de cumplir con leyes y regulaciones estrictas, y el requisito de proporcionar operaciones transparentes y responsables. Una OSPO puede ayudar a los gobiernos y organizaciones del sector público a superar estos desafíos.

- **Mejorar el Cumplimiento:** Una OSPO ayuda a garantizar que sus operaciones open source cumplan con las leyes y regulaciones pertinentes, incluidas las leyes de privacidad de datos, las regulaciones de adquisición y los requisitos de transparencia. Esto ayuda a las organizaciones a evitar costosos desafíos legales y regulatorios, y a mantener su reputación como organizaciones responsables del sector público.

- **Aumentar la Colaboración:** Una OSPO ayuda a fomentar la colaboración entre diferentes departamentos y con partes interesadas externas, incluidas otras organizaciones del sector público, comunidades open source y organizaciones de la sociedad civil. Esta mayor colaboración ayuda a las organizaciones a acceder a un grupo más amplio de talento y recursos, y a desarrollar mejores soluciones open source.

- **Mejorar la Asignación de Recursos:** Una OSPO ayuda a asignar recursos de manera más eficaz, asegurando que las operaciones open source estén bien respaldadas y que las iniciativas clave reciban los recursos que necesitan para tener éxito. Esto ayuda a las organizaciones a maximizar los beneficios de la tecnología open source y a impulsar la innovación y el crecimiento.

- **Mejorar la Prestación de Servicios:** Una OSPO ayuda a mejorar la prestación de servicios públicos, permitiéndoles adoptar tecnologías innovadoras y rentables, y colaborar con partes interesadas externas para desarrollar mejores soluciones. Esto ayuda a las organizaciones a proporcionar mejores servicios a los ciudadanos y a satisfacer las necesidades cambiantes de sus comunidades.

La Open Source Program Office (OSPO) de la Comisión Europea ha lanzado un nuevo portal que sirve como wiki o archivo de conocimiento, proporcionando información actualizada sobre los avances en temas relacionados con la OSPO para los administradores públicos. Este portal ofrece una variedad de recursos, incluidos estudios útiles, presentaciones, casos de uso, guías y más, a los lectores interesados en aprender más sobre temas relacionados con la OSPO. Consulta la sección de Recursos al final del capítulo para obtener la URL.

### Como Influencia Cultural

En un mundo gobernado por el software, las Open Source Program Offices (OSPOs) sirven como poderosos catalizadores culturales dentro de las organizaciones. Más allá de simplemente gestionar la integración técnica de soluciones open source, las OSPOs transforman fundamentalmente la cultura organizacional fomentando la colaboración abierta, la transparencia y la innovación.

A medida que las organizaciones dependen cada vez más del open source para problemas de misión crítica —ya sean sociales, económicos o tecnológicos— la influencia cultural de la OSPO se vuelve esencial para remodelar mentalidades y flujos de trabajo. Este cambio cultural permite a las organizaciones ir más allá de ver el open source simplemente como un recurso del que extraer valor, para convertirse en miembros activos y contribuyentes del ecosistema open source más amplio. Al incorporar los valores y prácticas del open source en toda una organización, las OSPOs cultivan campeones internos, establecen normas de colaboración y nutren una cultura donde prospera el intercambio de conocimientos.

Esta transformación cultural no solo respalda la gestión de riesgos y la innovación, sino que garantiza la sostenibilidad de las comunidades open source de las que dependen. Sin la influencia cultural continua de una OSPO, las organizaciones corren el riesgo de perder experiencia en open source, aumentar las vulnerabilidades legales y de seguridad, reducir la participación de la comunidad y dañar la reputación.

El Open Source es una necesidad crítica silenciosa, y el impacto cultural de una OSPO es vital para evolucionar la cultura y el conocimiento organizacional, ayudando a construir un OSS más seguro y sostenible.

#### Cómo Ayuda la OSPO

- **Actúa como Consejero:** A veces, un enfoque estratégico simplemente significa dar un paso atrás y tomarse el tiempo para pensar en algunas de las preguntas difíciles sobre qué tipo de modelo de participación es el adecuado para un proyecto en particular o cuán involucrada debería estar la organización en cada proyecto. También existe la cuestión de cuándo tiene sentido contribuir a un proyecto existente en lugar de crear un nuevo proyecto. Una OSPO que tenga estas conversaciones a nivel estratégico podrá proporcionar directrices a los trabajadores de los diferentes equipos para que no tengan que considerar las implicaciones comerciales de los diferentes modelos de participación en open source cada vez que intenten resolver un problema.

- **Actúa como Facilitador:** La OSPO también desempeña una especie de papel de traducción entre los intereses de los equipos y los responsables de la toma de decisiones de la organización con respecto al open source y las necesidades de la comunidad open source. También ayudan a las organizaciones a navegar los cambios culturales, de procesos y de herramientas necesarios para interactuar con la comunidad open source de manera eficaz y saludable.

- **Actúa como Defensor:** Las OSPOs pueden promover el uso del open source y sus mejores prácticas en diferentes unidades organizativas. Esto puede ayudar a las organizaciones a obtener los beneficios del open source, así como a involucrar a las personas para que contribuyan a proyectos open source o inicien otros nuevos.

- **Actúa como Ambientalista:** Las OSPOs pueden ayudar a las organizaciones a apoyar y sostener proyectos open source a largo plazo abordando cuestiones como la seguridad, el mantenimiento y la salud del proyecto. Esto puede ayudar a garantizar que los proyectos open source se mantengan saludables a largo plazo y continúen beneficiando a la comunidad en general.

- **Actúa como Guardián:** Las OSPOs pueden ayudar a hacer cumplir las políticas de open source y fortalecer la gobernanza del open source. Esto puede ayudar a las organizaciones a garantizar el cumplimiento y mitigar los riesgos de seguridad del open source.

![ospo-support](/images/ospo-support.png)

### Como Paso Intermedio hacia un Modelo de Gestión Open Source Descentralizado

Las OSPOs ayudan a gestionar el open source como una actividad continua y trabajan para integrarlo bien en todas las unidades de una organización. Algunas organizaciones están dando un paso más para asumir la propiedad de la gestión completa del open source dentro de sus estructuras y funciones habituales. Existe una pregunta abierta relacionada con si la OSPO se convertiría en un paso intermedio para lograr esto.

La respuesta depende de cómo veas la OSPO. Más allá de las múltiples estructuras diferentes que puede tener una OSPO, fundamentalmente se trata de su gente. Una OSPO es un grupo de expertos en la materia de open source que brindan apoyo, conocimiento y gestión en relación con todas las actividades de open source. Estas personas no solo deben ser retenidas, sino también reforzadas y financiadas eficazmente para el futuro, ya que una mayor integración del open source es inevitable.

En un escenario ideal, el conocimiento, la experiencia técnica y la cultura del open source deberían integrarse como cualquier otra habilidad de los empleados. Sin embargo, la realidad es que esto está muy lejos de suceder. Actualmente, es un desafío encontrar expertos en open source que puedan cerrar eficazmente la brecha entre las comunidades open source y las unidades de trabajo específicas (por ejemplo: seguridad, legal, negocios), y mucho menos suficientes personas para colocar en cada parte del negocio.

Sin embargo, lo que podría cambiar en los próximos años es la visión centralizada de la OSPO. Esta percepción tradicional puede disminuir, lo que lleva a estructuras más descentralizadas en todos los equipos y unidades de negocio.

![ospowork](/images/ospowork.png)

_[Fuente: OSPOs, key lever for open source sustainability][1](https://speakerdeck.com/anajsana/ospos-a-key-lever-for-open-source-sustainability)_

## Aplicando Esto a tu Organización

### Evalúa el Valor del Uso del Open Source

Las organizaciones pueden subestimar cuánto dependen ya del uso del open source. Varios estudios analizan el uso de OSS en la industria. Por ejemplo, el *Informe de Análisis de Riesgos y Seguridad de Open Source de Synopsys 2024* [^2] encuentra que el proyecto de software promedio consta de un 77% de OSS. Además, un *estudio de Harvard Business School* [^3] estima que el valor del lado de la oferta del OSS ampliamente utilizado es de 4.15 mil millones de dólares, mientras que el valor del lado de la demanda es mucho mayor, de 8.8 billones de dólares. Además, un estudio de OpenForum Europe [^4] estima que el OSS contribuye entre 65 y 95 mil millones de euros al PIB de la Unión Europea y promete importantes oportunidades de crecimiento para la economía digital de la región.

Evalúa este valor para tu propia organización tomando medidas como:

- Recopilar información sobre qué OSS utilizan tus equipos de desarrollo y operaciones.
- Obtener una visión clara de qué componentes open source hay en el software comercial que compras o los servicios que utilizas; pregunta a los proveedores qué OSS utilizan, por ejemplo, solicitando Listas de Materiales de Software (del inglés Software Bill of Materials, SBOMs).
- Evaluar el ahorro de costos del uso actual del open source evaluando lo que costaría si tuvieras que reemplazarlo con alternativas comerciales.
- Evaluar cómo el uso de componentes open source existentes puede aumentar la velocidad de la innovación o la agilidad de la ingeniería.

### Considera qué Valor Podría Aportar tu OSPO en el Futuro

El valor de una OSPO para tu organización puede aumentar con el tiempo a medida que cambian la estrategia y los objetivos de tu organización. Tu OSPO debe revisar periódicamente su valor para la organización y planificar aumentar su nivel de madurez si es necesario. Hay más información sobre la madurez de la OSPO disponible en el Capítulo 3, donde se introduce el tema de los Modelos de Madurez.

### Comunícate con las Partes Interesadas

Al comunicar el valor de tu OSPO a tu organización, la mejor ruta a seguir es presentar las 2-3 áreas principales de valor que estén más claramente alineadas con la estrategia organizacional. Puede haber muchas otras áreas donde la OSPO añade valor, pero la investigación muestra que una larga lista de beneficios puede debilitar el caso de negocio en lugar de fortalecerlo (puedes buscar "Weak Argument Effect" en línea para obtener más información). Trabaja en una propuesta de valor corta, clara y convincente que destaque, y úsala como ancla para presentar la OSPO en todas las situaciones.

No confíes en argumentos generales de "buenas prácticas". Aunque puedan basarse en la verdad, no suelen ser muy convincentes y no ayudan a generar una fuerte adhesión en toda la organización.

No confíes en el valor de que tu OSPO satisfaga necesidades futuras especulativas. Es genial estar preparado, pero a menos que haya una iniciativa clara que esté a punto de comenzar y con la que tu OSPO pueda ayudar, es mejor centrarse en el valor que puedes ofrecer aquí y ahora.

## Ejemplos del valor de la OSPO

Para ilustrar cómo tu OSPO puede aportar valor a tu organización, algunas historias de ejemplo pueden ser una excelente manera de generar adhesión. Aquí hay dos ejemplos en los que una OSPO podría ser de vital importancia:

### Gestionar una Vulnerabilidad en la Cadena de Suministro de Software

Por ejemplo: un ataque de ingeniería social tuvo como objetivo xz/liblzma [^5], una biblioteca open source esencial. El ataque fue meticulosamente planeado, ganando confianza dentro de la comunidad antes de ejecutar un ataque malicioso. Este incidente fue descubierto inadvertidamente por un proyecto no relacionado, lo que subraya la sofisticación y el sigilo de tales vulnerabilidades. El desafío para las OSPOs radica en identificar y mitigar estas vulnerabilidades, que no siempre son evidentes hasta después de que ocurren. A pesar de los procedimientos y políticas existentes, las OSPOs reconocen la necesidad de mecanismos para medir y responder proactivamente a tales amenazas.

#### Cómo Ayuda la OSPO

1. **Preparación para el Cumplimiento con SBOMs:** Asegurar que todos los componentes de software estén documentados a través de SBOMs generadas automáticamente. Esta documentación ayuda a identificar rápidamente los componentes potencialmente comprometidos una vez que se divulga una vulnerabilidad.

2. **Comprobaciones de Seguridad Automatizadas:** Implementar comprobaciones de seguridad automatizadas, como el OpenSSF Scorecard [^6], para evaluar continuamente la postura de seguridad de los proyectos. Esta medida proactiva puede resaltar vulnerabilidades o anomalías que merecen una mayor investigación.

3.  **Tener un Computer Emergency Response Team (CERT)** dentro de la organización y hacer que la OSPO colabore estrechamente con ellos. Este equipo especializado debe estar equipado con las herramientas y la autoridad para responder rápidamente a los incidentes de seguridad. Las relaciones preexistentes dentro del equipo facilitan la comunicación interna rápida sobre la gravedad de los incidentes.

4. **Gestión de Tarjetas de Puntuación:** Mantener actualizadas las tarjetas de puntuación de seguridad y vulnerabilidades. Estas deben reflejar las últimas comprobaciones y evaluaciones de seguridad, ayudando en la toma de decisiones rápida durante una crisis.

5. **Bucles de Retroalimentación Automatizados:** Desarrollar bucles de retroalimentación bien automatizados para la notificación y corrección de errores. Saber quién es responsable de abordar un error en particular y garantizar que este proceso sea lo más automatizado posible puede reducir significativamente los tiempos de respuesta.

### Gestionar un Cambio de Licencia en la Cadena de Suministro de Software

 Las OSPOs enfrentan el desafío de navegar los cambios de licencia y evaluar la confiabilidad del software. Cuando proyectos como Redis cambian sus términos [^7], puede tener implicaciones significativas para el uso, la distribución y la contribución. Las OSPOs necesitan comunicar estos cambios claramente y comprender los roles y responsabilidades dictados por los nuevos términos de licencia. Además, las OSPOs tienen la tarea de evaluar la confiabilidad del software, que puede variar según si un proyecto es mantenido por un solo proveedor o alojado bajo una fundación. Por ejemplo, la Fundación AlmaLinux OS [^8] presenta un caso en el que donar un proyecto a una fundación mitigó los riesgos asociados con la gobernanza de un solo proveedor, mejorando así la confianza en el proyecto.

#### Cómo Ayuda la OSPO

1. **Iniciativas Educativas sobre las Implicaciones de las Licencias:** Desarrollar materiales educativos y sesiones para desarrolladores y usuarios dentro de la organización para comprender los matices de las diferentes licencias. Esta comprensión les ayudará a tomar decisiones informadas al usar o contribuir a proyectos open source.
2. **Términos de Licencia Explícitos:** Trabajar con equipos legales para garantizar que los términos de la licencia sean lo más explícitos e inequívocos posible. Los términos claros ayudan a evitar malentendidos y posibles conflictos legales.
3. **Sistema de Calificación de Confianza del Software:** Implementar un sistema para evaluar y calificar la confiabilidad del software, considerando factores como la estructura de gobernanza, las prácticas de mantenimiento y la participación de la comunidad. Los proyectos alojados bajo fundaciones de renombre podrían calificarse más alto en confiabilidad debido a la supervisión y gobernanza proporcionadas.
4. **Fomentar Proyectos Alojados en Fundaciones:** Abogar por donar proyectos a fundaciones para mitigar los riesgos asociados con el control de un solo proveedor. Destacar casos exitosos como AlmaLinux para ilustrar los beneficios de este enfoque, como una mayor confianza y apoyo de la comunidad.
5. **Participación de las Partes Interesadas en las Decisiones sobre Licencias:** Involucrar a una amplia gama de partes interesadas, incluidos desarrolladores, asesores legales y usuarios finales, en discusiones sobre cambios de licencia o la adopción de nuevos proyectos. Sus conocimientos pueden ayudar a tomar decisiones equilibradas que se alineen con los valores y la tolerancia al riesgo de la organización.


## Posibles Problemas y Cómo Superarlos

En esta sección, encontrarás una serie de escenarios del mundo real que se encuentran en la gestión de open source en las organizaciones. Para cada escenario, puedes encontrar recomendaciones de experiencias del mundo real de profesionales del open source.

### Problema

Existe una falta de comprensión sobre las prácticas de open source en toda la organización.

### Recomendación

Puede ser difícil demostrar el valor de la OSPO si hay una comprensión deficiente del open source en la organización. Centrarse en hablar sobre tus áreas clave de valor y usar el poder de las historias te ayudará a construir rápidamente la comprensión en la organización. Compartir historias del mundo real sobre cómo tu organización está utilizando open source y compartir cuentos con moraleja sobre momentos en que una OSPO salvó a una organización de un riesgo puede ayudar a educar a las personas a través de narrativas fácilmente repetibles.

Con el tiempo, puedes comenzar a promover una mejor comprensión a nivel organizacional de las prácticas de open source ofreciendo talleres educativos, creando recursos accesibles y estableciendo campeones de open source en diferentes departamentos para fomentar una cultura de alfabetización en open source.

-----

### Problema

El valor de la OSPO se considera una ganancia de ventas o una herramienta de marketing.

### Recomendación

Debido a que la OSPO tiene un papel en el apoyo a las relaciones con las comunidades y socios de open source, puede ser natural que los departamentos de ventas y marketing vean algún valor para ellos en esta participación.

Como OSPO, solo puedes cumplir con tus responsabilidades generando confianza con terceros a lo largo del tiempo. Establece límites con ventas y marketing y di "no" a cosas que podrían reducir tu reputación en el ecosistema. Trabaja en construir una comprensión interna de la OSPO como parte integral de la estrategia digital, de software o de TI de la organización, y destaca el trabajo que fomenta las mejores prácticas de open source, contribuye a la innovación tecnológica y apoya los objetivos generales de la organización.

-----

### Problema

El valor de la OSPO se considera secundario o discrecional, y no como crítico para las funciones principales de la organización.

### Recomendación

La causa de este problema es que la OSPO no está alineada con las necesidades de la organización, o que la OSPO no está comunicando bien su valor. Revisa el valor de la OSPO y planifica tus comunicaciones para destacar cómo la OSPO mejora los procesos comerciales clave, impulsa la innovación y apoya directamente los objetivos estratégicos, integrándola así como un componente esencial del marco operativo de la organización.

-----

### Problema

La OSPO lucha por obtener apoyo ejecutivo y adhesión.

### Recomendación

Los ejecutivos requieren un tipo particular de comunicación. Necesitan tener una imagen clara del papel y el valor que aporta cada parte de la organización. Si el mensaje es demasiado detallado o vago, o si el tema es demasiado especializado, pueden tener dificultades para "entenderlo". Como OSPO, necesitas comunicar el valor estratégico del open source y del trabajo que realiza la OSPO para gestionarlo. Mostrar beneficios visibles a través de estudios de caso, historias de éxito o informes numéricos puede ayudar a destacar con una presentación clara y sencilla que demuestre que las iniciativas de la OSPO están cumpliendo con las prioridades organizacionales clave.


## Recursos y Notas al Pie

### Recursos

- Log4Shell real vulnerability example: https://en.wikipedia.org/wiki/Log4Shell
- Open source and the software supply chain - John Mark Walker: https://opensource.com/article/16/12/open-source-software-supply-chain
- Strategy: End Game for FINOS Maturity Model - Victor Lu: https://docs.google.com/presentation/d/1jJtR6-fvU-dCrGq_gTm4P1Awv90oCu4RClj1919970A/edit#slide=id.g1ed9ae7029f_0_29
- Securing the Software Supply Chain: The Role of OSPOs - Jessica Marz: https://www.intel.com/content/www/us/en/developer/articles/community/securing-software-supply-chain-the-role-of-ospo.html
- Simple Frequently Asked Questions OSPO Guide - OSPO SWG Japan: https://qiita.com/owada-k/items/017d1b98d0e437766bd0
- The Business Value of the OSPO Report - Linux Foundation: https://www.linuxfoundation.org/research/business-value-of-ospo
- EC Open Source Programme Office - European Commission Joinup: https://joinup.ec.europa.eu/collection/ec-ospo
- Public Services Should Sustain Critical Open Source Software - FOSSEPS: https://joinup.ec.europa.eu/collection/ec-ospo
- How Governments Want to Use OSPOs to Transform Themselves - Sivan Pätsch: https://joinup.ec.europa.eu/collection/open-source-observatory-osor/news/growing-case-ospos-government
- Open Source Security and Risk Analysis Report 2022 - Synopsys: https://www.synopsys.com/software-integrity/resources/analyst-reports/open-source-security-risk-analysis.html
- Open Technology - Scheerder, Jeroen & Koymans: https://www.researchgate.net/publication/254920512_Open_Technology#pf7
- The Pros and Cons of Open Source Software - Khalil Khalaf: https://medium.com/@kylekhalaf/the-pros-and-cons-of-open-source-software-d498304f2a95

### Notas al Pie

[^1]: Informe sobre el valor empresarial de la OSPO: https://www.linuxfoundation.org/research/business-value-of-ospo

[^2]: Informe de Análisis de Riesgos y Seguridad de Open Source de Synopsys 2024: https://www.synopsys.com/content/dam/synopsys/sig-assets/reports/rep-ossra-2024.pdf

[^3]: Estudio de Harvard Business School: https://www.hbs.edu/ris/Publication%20Files/24-038_51f8444f-502c-4139-8bf2-56eb4b65c58a.pdf

[^4]: Estudio de OpenForum Europe: https://openforumeurope.org/publications/study-about-the-impact-of-open-source-software-and-hardware-on-technological-independence-competitiveness-and-innovation-in-the-eu-economy/

[^5]: Ataque de ingeniería social dirigido a xz/liblzma: https://research.swtch.com/xz-timeline

[^6]: OpenSSF Scorecard: https://scorecard.dev/

[^7]: Redis cambia sus términos: https://www.theregister.com/2024/03/22/redis_changes_license/

[^8]: AlmaLinux OS Foundation: https://thenewstack.io/jack-aboutboul-how-almalinux-came-to-be-and-why-it-was-needed/