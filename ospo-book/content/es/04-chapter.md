---
title: "Capítulo 4: Operaciones diarias"
status: Completed
weight: 60
---

- [Introducción](#introducción)
- [Actividades Comunes](#actividades-comunes)
- [Cómo Aplicar Esto a Tu Organización](#cómo-aplicar-esto-a-tu-organización)
- [Posibles Problemas y Cómo Superarlos](#posibles-problemas-y-cómo-superarlos)
- [Recursos y Notas al Pie](#recursos-y-notas-al-pie)

## Introducción

Una vez que tienes tu estrategia, necesitas un plan. Tu plan consistirá en crear y ejecutar un conjunto de actividades regulares que lleven a cabo tu estrategia. Este capítulo te ayudará a comprender cuál es el rango de actividades de una OSPO y qué valor aporta cada una a tu organización.

## Actividades Comunes

Las operaciones diarias de una OSPO abarcan un amplio espectro de actividades destinadas a mejorar la participación y el cumplimiento del open source (código abierto) dentro de la organización, incluyendo:

- **Soporte Directo de Código Abierto:** Implica responder preguntas sobre todos los aspectos del código abierto, incluido el cumplimiento de licencias, la selección de software de código abierto (OSS) y las interacciones con proveedores. También incluye la interacción con la comunidad y los socios, la obtención de patrocinios y la organización de eventos de código abierto.

- **Herramientas de Automatización:** Crear automatización de procesos para respaldar las políticas de código abierto es importante porque las políticas por sí solas pueden no ser siempre efectivas. Los gerentes saben que sus trabajadores no siempre seguirán la política y, por lo tanto, desean opciones efectivas para automatizar el uso, la gestión y el seguimiento de los componentes de código abierto. La automatización es útil en muchas áreas del código abierto, incluido el cumplimiento de licencias y la seguridad.

- **Documentación, Capacitación y Educación:** Una OSPO puede desempeñar un papel de liderazgo para garantizar que las personas estén cualificadas para evaluar proyectos de código abierto para su uso en la organización y contribuir a proyectos de código abierto críticos para la organización. El desarrollo de materiales de capacitación y documentación y/o ayudar a los equipos a producirlos en diferentes departamentos son tareas clave.

- **Asignación de Recursos:** Puede haber muchas áreas en las que una OSPO puede ofrecer valor a una organización. Por lo tanto, priorizar el trabajo y asignar recursos estratégica y tácticamente es una actividad importante que mejorará el impacto de la OSPO.

- **Gestión de Riesgos:** Las OSPO están bien posicionadas para tener una visión integral del riesgo que enfrenta la organización al usar proyectos de código abierto. Es útil para la OSPO evaluar los riesgos obteniendo una visión completa del tech stack de la organización. Esto puede incluir la generación de SBOMs, que permiten a la OSPO considerar los riesgos en el software de proveedores, software heredado y software propietario, así como en el código abierto. Se trata más de una perspectiva de evaluación empresarial que de una simple recopilación de datos, ya que el riesgo solo se puede gestionar, no eliminar. Optimizar los SBOMs consiste en equilibrar los riesgos frente a los beneficios.

- **Patrocinio de Comunidades y Fundaciones de Código Abierto:** Tu organización depende del código abierto. Los proyectos de código abierto son tan saludables como lo sean sus comunidades, y puedes invertir tu tiempo y dinero en apoyar a las comunidades, ya sea directamente o a través de fundaciones. Estas relaciones deben comprenderse y gestionarse con atención para lograr beneficios mutuos. A veces, el dinero no es la solución ideal; resulta más valioso estrechar lazos de colaboración y contribuir activamente con desarrollo, marketing o apoyo en la gestión de sus programas.

- **Medición de la Deuda Técnica:** Proporcionar conocimiento sobre cómo medir la deuda técnica en un proyecto de código abierto ayuda a determinar los riesgos asociados con el proyecto y, cuando se realiza en colaboración con la comunidad del proyecto, es una forma de labor educativa para ayudar a los proyectos a mejorar y sostenerse.

- **Coordinación con Varias Partes de la Organización:** Puede ser útil verificar que conoces a todos tus stakeholders y que tienes la cantidad correcta de interacción con ellas. Echa un vistazo al diagrama de la flor de la OSPO en el Capítulo 3 para obtener ayuda para mapear las interacciones.

- **Asesoramiento Sobre el Consumo de Código Abierto:** La OSPO considera tanto la visión estratégica sobre qué proyectos de código abierto consumir como las mejores prácticas para usar los proyectos seleccionados. La OSPO debe proporcionar materiales de referencia y orientación sobre cómo la empresa debe seleccionar qué proyectos de código abierto utiliza y cómo los gestiona. Las pautas y políticas pueden ser puramente técnicas o pueden incluir consideraciones basadas en la salud y las prácticas del proyecto de código abierto, como el *Secure Supply Chain Consumption Framework (S2C2F)*[^1].

## Cómo Aplicar Esto a Tu Organización

### El OSPO Mind Map

El OSPO Mind Map [^2] es, una vez más, una herramienta útil. Puedes utilizarlo para obtener una visión general de las actividades potenciales de una OSPO. El Mapa Mental de la OSPO describe las principales responsabilidades, roles, comportamientos y tamaños de equipo dentro del ecosistema de una OSPO. Como siempre, esto es un insumo para tu trabajo, no un plan fijo a seguir. Debes adaptarlo a tus necesidades.

### Actividades por Etapa de Madurez

En la siguiente tabla, se utiliza el modelo de participación en actividades de código abierto de Ibrahim H. (visto anteriormente en el Capítulo 2) como mapa para enumerar y explorar las actividades en una OSPO.

#### ETAPA: Consumidor

| Actividades                                                                                                                 | Valor para la OSPO                                                                                                                                     | Valor para la Organización                                                                                                                                                                                                                                                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Definir reglas y prácticas de cumplimiento de código abierto                                                                          | Un consenso explícito sobre las reglas y prácticas de cumplimiento de código abierto de la organización entre las partes interesadas legales y de negocio.            | La organización sabe que tiene un enfoque gestionado para los aspectos legales del consumo de código abierto, el cual puede mantenerse y mejorarse con el tiempo. Cada empresa tiene diferentes aspectos de cumplimiento, interpretaciones de licencias y diferente apetito de riesgo (por ejemplo, al lidiar con regulaciones). Tener reglas y prácticas de cumplimiento bien definidas es el primer paso hacia un cumplimiento de código abierto determinista.                                                                                                                                               |
| Definir reglas y políticas sobre el uso de código abierto (criterios para usar software de código abierto (OSS) relacionados con la salud del código abierto)                     | El consumo de proyectos de código abierto no se ve solo a través de la lente del cumplimiento, sino que se considera de manera más holística e incluye los riesgos asociados con proyectos no saludables. Se construye un consenso en la empresa relacionado con la "higiene" de los componentes de código abierto consumidos. La organización tiene políticas claras a seguir. | Los proyectos de código abierto consumidos tienen menor riesgo porque son saludables, corrigen vulnerabilidades de seguridad, implementan nuevas funcionalidades y lanzan versiones regularmente.                                                                                                                                                                                                                                                                                         |
| Definir reglas y políticas sobre cómo contribuir al código abierto (criterios sobre cómo participar en la comunidad, transferencia de derechos, Acuerdos de Licencia de Contribuidor - CLA)| La OSPO puede aumentar la conciencia sobre la relación bidireccional con los proyectos de código abierto. El uso de políticas respalda un enfoque consistente y ético. La organización tiene políticas claras a seguir.                                                                                                     | Las políticas y prácticas aseguran que la organización considere cómo construir valor conjuntamente con los proyectos de código abierto. Es probable que las contribuciones realizadas mejoren la reputación de la empresa, no que la dañen.                                                                                                                                                                                                                                                                                                                                |
| Adoptar el cumplimiento de la norma ISO/IEC 5230 (OpenChain)                                                                                        |     La OSPO puede implementar un estándar internacional definido en lugar de crear uno desde cero.                                                                                                                                               | La organización puede demostrar su cumplimiento con un estándar reconocido internacionalmente.                                                                                                                                                                                                                                                                                                                          |
| Gestionar un inventario de software de código abierto (OSS) utilizado en la organización                                                                                     |         La OSPO es consciente de la superficie de software de código abierto (OSS) que supervisa.                                                                                                                                           | La organización tiene una base para la gestión global de riesgos. Esta es una herramienta importante para lidiar con problemas relacionados con proyectos específicos (problemas de seguridad, cambios de licencia, problemas de ciclo de vida, etc.).                                                                                                                                                                                                                                           |
| Capacitación sobre concienciación de código abierto                                                                                         |                 Proporcionar capacitación sobre código abierto aumenta la visibilidad del rol del código abierto, la visibilidad de la OSPO y su valor, y mejora la comprensión de cómo la organización usa e interactúa con el código abierto.                                                                                                                                   | Aumenta la competencia presente en la organización para trabajar con software de código abierto (OSS) a través de una conciencia sobre el valor del código abierto, las licencias, las contribuciones, etc.                                                                                                                                                                                                                                                                             |
| Introducir herramientas para el cumplimiento de licencias                                                                                     |                           Proporcionar estructura y visibilidad para el cumplimiento de licencias dentro de la organización, lo que ayuda a informar la estrategia de gestión.                                                                                                                         | La automatización es esencial para poder abordar los riesgos con una cantidad razonable de esfuerzo y medir la efectividad de los esfuerzos para mejorar el cumplimiento.                                                                                                                                                                                                                                                                                            |
| Aclarar cómo dar soporte al software de código abierto (OSS)                                                                                |      Asegurar que el software de código abierto (OSS) se adopte con una comprensión adecuada de cómo puede ser soportado.                                                                                                                                               | La organización debe ser consciente de los costos ocultos de usar software de código abierto (OSS) en escenarios de producción. El soporte externo para componentes de código abierto a veces se puede comprar a un proveedor. Alternativamente, otras opciones son gestionar el soporte uno mismo con la ayuda de la comunidad (siendo realista al considerar qué se puede esperar que soporte una comunidad), o asumir el riesgo de no tener soporte, lo cual puede ser apropiado para escenarios donde el riesgo es bajo. |

#### ETAPA: Participante

| Actividades                                     | Valor para la OSPO | Valor para la Organización                                                                                                     |
| ---------------------------------------------- | -------------- | ----------------------------------------------------------------------------------------------------------------- |
| Apoyo financiero a comunidades de código abierto | Mejores relaciones con las comunidades, mayor influencia.   | Mayor estabilidad en el ecosistema y en la cadena de suministro de software de la que depende la organización.                                                  |
| Membresía en organizaciones de código abierto       | eneficios de membresía como co-marketing, descuentos en eventos.  | Interacción con las comunidades de las que depende la organización. Influencia potencial y acceso a información estratégica útil. Apoyo al ecosistema.                                 |
| Probar InnerSource                             | El personal de la organización obtendrá experiencia práctica con metodologías de código abierto, lo que genera conciencia, comprensión y promoción del modelo.  | La organización desarrollará habilidades en su fuerza laboral que contribuirán a un mejor uso e interacción con los proyectos de código abierto.  |

#### ETAPA: Contribuidor

| Actividades                             | Valor para la OSPO | Valor para la Organización                                                                                                                                                      |
| -------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Crear política y proceso de contribución | Gestionar las contribuciones de código abierto se vuelve más fácil. | Tener procedimientos claros significa que la organización puede realizar contribuciones de código abierto de una manera legalmente segura, tanto para los proyectos de código abierto, como para la organización y sus empleados. |
| Cualificación de los contribuidores          | Los contribuidores requieren menos supervisión y se convierten en buenos embajadores. | Los contribuidores capacitados realizan mejores aportaciones en proyectos visibles públicamente. Esto significa menos riesgo para la organización.               |

#### ETAPA: Liderazgo

| Actividades                                                                  | Valor para la OSPO | Valor para la Organización                                                                                                                                                                |
| --------------------------------------------------------------------------- | -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Liberar como código abierto proyectos previamente propietarios                               | La OSPO puede reducir la carga en los departamentos de Ingeniería (y otros). | Se abrirán nuevas oportunidades para mejorar el código base de un componente estandarizado a través de la colaboración pública. Mayor participación estratégica en código abierto. Acceso a nueva experiencia y talento.                                                                                                           |
| Establecer una política de priorizar el origen                                        | Ofrecer a la organización una forma de obtener más valor por la misma, o menor, cantidad de esfuerzo. | La organización puede apoyar o incluso liderar proyectos de código abierto y convertirlos en parte de la creación de valor principal de la organización sin perder sus diferencias competitivas, y al mismo tiempo beneficiarse de las contribuciones de toda una comunidad.                                                                              |
| Apoyar la autonomía de los contribuidores y mantenedores de proyectos de código abierto | Los expertos internos en código abierto son valiosos para la OSPO. | Emplear personas que se dedican únicamente al trabajo de código abierto significa que la organización puede fortalecer estratégicamente proyectos importantes de código abierto de la manera más orgánica y efectiva. |

## Posibles problemas y Cómo Superarlos

### Problema

La nueva OSPO tarda mucho en mostrar progresos visibles, y comienzan a surgir dudas sobre la necesidad de tener una OSPO.

### Recomendación

Al igual que con cualquier nueva iniciativa, es fundamental mantener el enfoque en generar un impacto significativo tanto a corto como a largo plazo. El impacto a corto plazo reafirma a los stakeholders que la OSPO es necesaria y competente, y otorga confianza al personal de la misma. El impacto a largo plazo crea valor sostenible y consolida firmemente la posición de la OSPO dentro de la organización. Intenta identificar algo importante que pueda entregarse en los primeros 3 a 6 meses, mientras trabajas también en proyectos a más largo plazo que darán resultados en 6-12 meses, 12-24 meses y 2-5 años. Mantén una lista breve de proyectos activos al principio para asegurar que se entreguen con calidad y a tiempo. A medida que crezca la confianza en la OSPO, estarás en una posición más sólida para solicitar más recursos si cuentas con un historial de éxitos comprobado.

## Recursos y Notas al Pie

### Recursos

- A Guide to Enterprise Open Source: https://www.ibrahimatlinux.com/wp-content/uploads/2022/05/LFR_LFAID_Guide_to_Enterprise_Open_Source_052522.A4.pdf
- A Deep Dive Into Open Source Program Offices: Structure, Roles, Responsibilities, and Challenges: https://8112310.fs1.hubspotusercontent-na1.net/hubfs/8112310/LF%20Research/LFR_LFAID_Deep_Dive_Open_Source_Program_Offices_081922.pdf
- OpenSSF Scorecard: https://github.com/ossf/scorecard
- Software Bill of Materials (SBOMs): https://www.ntia.gov/SBOM
- Computer Emergency Response Team (CERT): https://www.cisa.gov/uscert/

### Notas al Pie

[^1]: Secure Supply Chain Consumption Framework (S2C2F): https://www.microsoft.com/en-us/securityengineering/opensource/osssscframeworkguide

[^2]: OSPO Mind Map https://todogroup.org/resources/mindmap/
