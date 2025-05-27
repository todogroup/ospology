---
title: "Capítulo 3: Creando tu OSPO"
status: Completed
weight: 50
---

- [Introducción](#introducción)
- [Comenzando con la Estrategia](#comenzando-con-la-estrategia)
- [Diseñando tu OSPO](#diseñando-tu-ospo)
- [Usando Maturity Models para OSPOs](#usando-maturity-models-para-ospos)
- [Aplicando Esto a tu Organización](#aplicando-esto-a-tu-organización)
- [Posibles Problemas y Cómo Superarlos](#posibles-problemas-y-cómo-superarlos)
- [Recursos y Notas al Pie](#recursos-y-notas-al-pie)

## Introducción

Las OSPOs pueden ser muy diversas, por lo que es importante tomarse el tiempo para diseñar una OSPO que cumpla con los objetivos de tu organización.

Este capítulo primero te ayudará a identificar tu estrategia para que puedas tener una base para planificar el trabajo que tu organización debería hacer y cómo debería estructurarse la OSPO.

Luego, analizará el diseño y la construcción de una OSPO estable y sólida, capaz de cubrir las tareas y responsabilidades relacionadas con el open source que necesita tu organización.

Finalmente, este capítulo introducirá el Maturity Model (modelo de madurez) como una forma de comprender qué es apropiado para tu OSPO ahora y en el futuro a medida que cambian las necesidades.

## Comenzando con la Estrategia

### Cómo Desarrollar la Estrategia

> Para los individuos en las Open Source Program Offices, comunicar eficazmente la estrategia de open source a los ejecutivos del C-level exige una profunda comprensión del panorama de la industria y la alineación con las consideraciones clave de los CEOs y CFOs. Esta alineación requiere una clara comprensión de la estrategia corporativa general y la identificación de tecnologías dentro del ámbito del open source que puedan impulsar a la organización hacia sus objetivos estratégicos.
>
> Victor Lu and Rob Moffat Presentation - Strategy - End Game for FINOS Maturity Model [^1]

Una OSPO logra esto creando y manteniendo un marco que cubra los siguientes aspectos: estrategia, gobernanza, cumplimiento y participación comunitaria. La estrategia de la OSPO se centra en alinear el uso, las contribuciones y las actividades de cumplimiento del open source de la organización con sus objetivos organizacionales generales en todos sus proyectos, productos, servicios e infraestructura interna.

Una estrategia crea un consenso de alto nivel sobre temas concretos y su impacto en tu organización y las personas dentro de ella.

Aspectos a considerar al crear tu estrategia:

1.  **Crea un documento de estrategia:** Una buena práctica es documentar esta estrategia en un *open source strategy document* [^2]. Esta guía te lleva a través del proceso paso a paso.
2.  **Comprende los Objetivos de tu Organización:** Como se mencionó en el capítulo anterior, necesitarás comprender los objetivos de tu organización y su compromiso actual con el open source.
3.  **Considera el Contexto:** Al desarrollar la estrategia y el diseño de tu OSPO, tienes diferentes formas de abordar su estructura y posición en el organigrama antes de pensar en el personal, la tecnología y el presupuesto. Existe una excelente guía producida por el TODO Group, llamada *A deep dive into OSPOs* [^3], que explica toda la información esencial sobre las estructuras y operaciones de las OSPOs.
4.  **Revisa la estructura de una OSPO de ejemplo:** Para obtener una visión general de las actividades potenciales de una OSPO, puedes revisar el *OSPO Mind Map* [^4]. Este describe las principales responsabilidades, roles, comportamientos y tamaños de equipo dentro del ecosistema de una OSPO.

## Diseñando tu OSPO

### Identificando lo que tu OSPO Debería Gestionar

El trabajo de una OSPO ejecutado eficazmente tiene en cuenta los elementos de la arquitectura de una organización, ya que comprender los objetivos de la organización es fundamental para tomar decisiones informadas orientadas al open source. Por ejemplo, en un campo corporativo, una OSPO podría analizar las siguientes áreas e identificar el papel que juega el open source en cada situación:

![organization-architecture](/images/organization-architecture.png)

Dado que cada organización es única en sus valores, impulsores de negocio y cultura, es un desafío proporcionar contenido específico. Sin embargo, abordar las siguientes preguntas puede ayudar a estructurar el documento de manera eficaz:

*   ¿Qué tecnología open source es y cuál será importante para los objetivos y la hoja de ruta de productos de tu organización?
*   ¿Qué proyectos open source desarrollan o influyen directa e indirectamente en estas tecnologías y en los objetivos de tu organización?
*   ¿Qué prácticas específicas pueden fomentar mejor un ecosistema open source sostenible?
*   ¿Qué procesos de la organización tienen áreas de mejora?
*   ¿Cómo puede el open source apoyar esas mejoras?
*   ¿Cómo puedes convertir a los trabajadores en defensores del open source?
*   ¿Cómo se puede transmitir eficazmente el mensaje a la dirección para su comprensión?

Tomarte el tiempo para comprender dónde puede agregar valor la OSPO te ayudará a reconocer quiénes son tus stakeholders.

### Identificando los Stakeholders de tu OSPO

Hay algunas partes comunes del negocio donde una OSPO puede encontrar a sus stakeholders. Los stakeholders son todas las personas que se verán afectadas por el trabajo que realizarás. El OSPO Flower Diagram (Diagrama de Flor de la OSPO) ayuda a visualizar los diferentes grupos de stakeholders. Cada pétalo representa un cierto grupo de stakeholders con actividades específicas asociadas a este grupo. El *OSPO Flower Diagram* también se puede utilizar para ayudarte a mapear los canales de comunicación específicos, la documentación y otro material utilizado con cada grupo de stakeholders.

Dependiendo de la complejidad de tu organización y los recursos disponibles para tu OSPO, estos pétalos pueden volverse más granulares e incluir pétalos adicionales con diferentes nombres.

![ospoflower](/images/ospo-flower.png)
[ospoflower.pdf](/pdfs/ospoflower-seconddraft-1.pdf)

*   **Individual Contributors (Contribuidores Individuales):** Este pétalo representa a las personas con las que la OSPO trabajará dentro de la organización, centrándose en los motivadores intrínsecos y extrínsecos de contribuir al open source desde un punto de vista individual. Requiere un esfuerzo de cambio cultural y puede implicar actividades como el establecimiento de programas de mentoría.

*   **Management (Dirección):** En este pétalo, la OSPO se centra en la estrategia y en encontrar la alineación entre el open source y la estrategia general del negocio/organización. Los directivos enfrentan desafíos únicos, y usar las fortalezas del open source les ayuda a superar estos desafíos de manera efectiva.

*   **Legal (Legal):** Este pétalo representa los aspectos legales del open source. Se ocupa de comprender y gestionar los requisitos y obligaciones legales relacionados con las iniciativas open source dentro de la organización. Esto asegura el cumplimiento y reduce los riesgos legales.

*   **Business (Negocio):** Este pétalo se centra en cómo la OSPO asegura que todas las piezas de la estructura de la organización encajen. Implica compartir mejores prácticas entre diferentes unidades de negocio/equipos y fomentar la colaboración y la transferencia de conocimiento.

*   **Open Source Ecosystem (Ecosistema Open Source):** Este pétalo representa la comunidad open source más amplia y el ecosistema de proyectos fuera de la organización. La OSPO se relaciona con este ecosistema, que incluye otras organizaciones, proyectos e individuos, para intercambiar ideas, colaborar y contribuir a la comunidad open source en general.

*   **OSPO:** Esto representa el funcionamiento interno de la propia OSPO. Las personas dentro de la OSPO colaboran y coordinan todas las iniciativas open source dentro de la organización. Supervisan las actividades, aseguran operaciones fluidas y brindan orientación y apoyo a otros stakeholders involucrados en el open source.

### Colaborando con Reguladores Externos

Los reguladores externos no están incluidos en el OSPO Flower Diagram, ya que este es un caso especializado.

Las organizaciones están sujetas a varios reguladores externos que influyen y dan forma a sus políticas y procesos. Estos reguladores aseguran el cumplimiento de los requisitos legales, los estándares éticos y las directrices específicas de la industria. Algunos reguladores externos incluyen:

*   Agencias Gubernamentales: Los organismos gubernamentales establecen y hacen cumplir leyes y regulaciones que impactan a las organizaciones.
*   Reguladores de la Industria: Muchas industrias tienen sus propios organismos reguladores o asociaciones profesionales que establecen directrices y estándares que las organizaciones deben seguir.
*   Agencias de Protección al Consumidor: Las agencias de protección al consumidor aseguran que las organizaciones proporcionen productos o servicios justos y seguros a los consumidores.

Para que el open source tenga éxito y sea sostenible dentro de una organización, es crucial colaborar no solo con la comunidad open source sino también con los reguladores externos. Esta colaboración asegura una comprensión clara de los principios del open source al crear políticas que afectan al ecosistema. El objetivo principal es trabajar juntos y tomar decisiones informadas comprendiendo completamente las implicaciones del open source y su comunidad. Por lo tanto, se recomienda que la OSPO considere formas de desarrollar un plan para acercarse y comunicarse con los reguladores, definiendo claramente los roles que desempeñarán en el proceso de formulación de políticas.

## Usando Maturity Models para OSPOs

### Una Introducción a los Maturity Models

El compromiso de una organización con el open source generalmente se sitúa a lo largo de una escala que va de lo táctico a lo estratégico. Los maturity models te ayudan a comprender en qué parte de esta escala se encuentran las diferentes partes de la organización y a tener conversaciones sobre si está en el lugar correcto.

Existen muchos maturity models de open source diferentes. Algunos son generales, otros especializados. Hay maturity models para gobiernos, ONGs, empresas y más, con versiones y subversiones para adaptarse a cualquier organización.

> NOTA: Los maturity models pueden verse como una prescripción de cómo deben desarrollarse las OSPOs o el compromiso con el open source. Puede ser tentador pensar que siempre es mejor aumentar la madurez. Pero, recuerda que debes considerar qué *nivel* de madurez es apropiado para tu OSPO, o cada función de tu OSPO. No todas las partes necesitan estar altamente desarrolladas. Es posible que ya entreguen el valor necesario sin mayor desarrollo. Si los maturity models no se ajustan a tu OSPO, considera usar un modelo de capacidad o algo más que prefieras.

### Ejemplos de Maturity Models

Cada uno de estos maturity models es ligeramente diferente, pero todos clasifican el compromiso con el open source desde lo táctico y menos intencional, hasta lo estratégico y más intencional.

#### Maturity Model 1 - Adopción del Compromiso Open Source por Dr. Ibrahim H [^5]:

*   Denial (Negación) - Uso nulo o inconsciente de open source
*   Consumption / Usage (Consumo / Uso) - Uso pasivo de OSS
*   Participation (Participación) - Compromiso con las comunidades open source
*   Contribution (Contribución) - Contribuciones pragmáticas a proyectos open source
*   Leadership (Liderazgo) - Implicación estratégica con el open source para impulsar el valor empresarial

![opensourceinvolvementmodel](/images/opensourceinvolvementmodel.png)

#### Maturity Model 2 - Charla sobre las Cinco Etapas de Adopción Corporativa de Open Source por Carl-Eric [^6]:

*   Accidental - la organización utiliza open source sin saber que lo usa
*   Repetitive (Repetitivo) - existen procesos establecidos tanto para el consumo como para la contribución, pero las contribuciones son esporádicas
*   Directed (Dirigido) - participación activa en proyectos open source críticos
*   Collaborate (Colaborativo) - la colaboración open source se utiliza como herramienta para crear valor empresarial
*   Prevail (Prevaleciente) - el open source se utiliza para influir en áreas estratégicas del negocio y la tecnología

![osmm-carl](/images/osmm-carl.png)

#### Maturity Model 3 - The OSPO Maturity Model by The TODO Group [^7]

*   Etapa 0: Adopción Ad Hoc de Open Source
*   Etapa 1: Proporcionar Cumplimiento de OSS, Inventario y Educación para Desarrolladores
*   Etapa 2: Evangelizar el Uso de OSS y la Participación en el Ecosistema
*   Etapa 3: Alojar Proyectos OSS y Hacer Crecer Comunidades
*   Etapa 4: Convertirse en un Socio Estratégico para la Toma de Decisiones

![OSPO Maturity Model](/images/ospo-maturity-model.jpg)

## Aplicando Esto a tu Organización

Aquí hay algunas sugerencias sobre cómo podrías usar las ideas y consejos anteriores para configurar tu OSPO. Estas se basan en el Maturity Model 3 - The OSPO Maturity Model by The TODO Group.

### Usando una Checklist Simple

La *TODO OSPO checklist* [^8] ofrece un conjunto simplificado de hitos comunes tanto para OSPOs en etapa temprana como para las experimentadas, para navegar cada etapa del OSPO Maturity Model mencionado anteriormente. Ten en cuenta que una OSPO podría eliminar, agregar o editar parte del contenido de esta checklist para adaptarla a las necesidades de su organización.

### Usando Maturity Models

Una vez que tengas cierta familiaridad con los maturity models de open source, puedes comenzar a usar uno para construir tu estrategia y crear tu plan.

El OSPO Japan Local Meetup Working Group, con el apoyo de The TODO Group y OpenChain, ha estado desarrollando una guía simple de preguntas frecuentes (FAQ) sobre OSPOs. Esta guía tiene como objetivo responder preguntas en cada paso del OSPO Maturity Model, que categoriza diferentes actividades de open source desde la etapa 0 a la 4, y describe el papel de la OSPO en cada nivel.

Aquí hay algunos aspectos destacados de su trabajo para inspirarte:

![ospo-role](/images/ospo-role.png)
![benefits-of-oss](/images/benefits-of-oss.png)

> NOTA: Puedes encontrar un resumen de su trabajo tanto en japonés como en inglés en un artículo de Qiita escrito por uno de sus miembros [^9].

Mientras planificas la OSPO, es muy útil tener conversaciones 1:1 con gerentes, ejecutivos de alto nivel y trabajadores/contratistas de diferentes equipos que usan open source en sus operaciones diarias, o cuya estrategia implica tratar con proyectos open source (en términos de licencias, vulnerabilidades de seguridad). Utiliza los conocimientos de estas conversaciones para definir los motivadores únicos de la organización y mapearlos a áreas dentro de la organización donde el open source aporta valor.

Esto también ayudará a construir apoyo para tu trabajo en toda la empresa incluso antes de que la OSPO se cree y lance oficialmente.

Mapea estos motivadores con diferentes tipos de actividad en toda la organización, utilizando el OSPO Maturity Model y creando una segunda división que categorice cada uno de estos motivadores únicos según las diferentes etapas. Usa esto como referencia cuando te relaciones y comuniques con tus stakeholders.

Por ejemplo:

<img width="942" alt="activityparticipationcategorization" src="/images/activityparticipationcategorization.png">

## Posibles Problemas y Cómo Superarlos

### Problema

Mientras creas la OSPO, recibes muchas preguntas y tienes que adaptar tu plan para tener en cuenta nueva información. Parece que hay una falta de coherencia en cómo se percibe la comprensión y el valor del open source en toda la organización, lo que genera confusión y riesgos potenciales.

### Recomendación

Asegúrate de tomarte el tiempo para identificar a todos tus stakeholders y comprender sus motivaciones. Crear manifiestos, principios y sitios web de open source disponibles públicamente es una forma eficaz de fomentar una comprensión común de los valores, principios y objetivos entre todos los equipos y subsidiarias. Tomarse el tiempo para establecer y hacer cumplir una comprensión coherente del open source en toda la organización garantizará una base estable y sólida para la OSPO.

## Recursos y Notas al Pie

### Recursos

- TODO guide to outbound OSS: https://todogroup.org/resources/guides/a-guide-to-outbound-open-source-software/
- TODO guide to participating in open source communities: https://todogroup.org/resources/guides/participating-in-open-source-communities/
- DevOps uses Capability, not Maturity: https://octopus.com/blog/devops-uses-capability-not-maturity
- Porsche Open Source Website: https://opensource.porsche.com/
- The Evolution of the OSPO: https://linuxfoundation.org/tools/the-evolution-of-the-open-source-program-office-ospo/
- OSPO 101 training module - OSPO and your organization: https://github.com/todogroup/ospo-career-path/tree/main/OSPO-101/module3

### Notas al Pie

[^1]: Strategy - End Game for FINOS Maturity Model: https://osr.finos.org/docs/presentations/strategy

[^2]: Creating an open source strategy document: https://todogroup.org/resources/guides/setting-an-open-source-strategy/

[^3]: A deep dive into OSPOs: https://www.linuxfoundation.org/research/a-deep-dive-into-open-source-program-offices

[^4]: OSPO Mind Map: https://todogroup.org/resources/mindmap/

[^5]: Dr. Ibrahim H, Guide to Enterprise Open Source: https://www.linuxfoundation.org/research/guide-to-enterprise-open-source

[^6]: Carl-Eric: https://web.archive.org/web/20240419100823/https://debricked.com/blog/what-is-open-source-maturity-model/

[^7]: The TODO Group Maturity Model: https://github.com/todogroup/ospology/blob/main/ospo-model/en/five-stage-OSPO-maturity-model.md

[^8]: The TODO OSPO checklist: https://github.com/todogroup/ospology/blob/main/ospo-model/en/ospo-checklist.md

[^9]: Resumen del trabajo de The OSPO Japan Local Meetup Working Group en japonés e inglés en un artículo de Qiita escrito por uno de sus miembros: https://qiita.com/owada-k/items/017d1b98d0e437766bd0
