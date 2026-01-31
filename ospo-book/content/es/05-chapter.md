---
title: "Capítulo 5: Gestión de la Seguridad del Código Abierto"
status: Completed
weight: 60
---

- [Introducción](#introducción)
- [Capacitación y Educación](#capacitación-y-educación)
- [Pasos Clave](#pasos-clave)
- [Cómo Aplicar Esto a Tu Organización](#cómo-aplicar-esto-a-tu-organización)
- [Recursos y Notas al Pie](#recursos-y-notas-al-pie)

## Introducción

> NOTA: Este capítulo ha sido desarrollado a través de la experiencia de representantes de la Open Source Security Foundation (OpenSSF), con apoyo del TODO Group

El software de código abierto es una parte importante de la cadena de suministro de software. Por esta razón, es parte de la responsabilidad de una OSPO ayudar a asegurar la cadena de suministro del código abierto. Esto incluye tareas como:

- Ayudar a los equipos de desarrollo a evaluar la seguridad del software de código abierto (OSS) que utilizan en los productos.
- Alentar a los equipos de desarrollo a contribuir a proyectos de código abierto upstream para ayudar a mejorar su seguridad.
- Seguir las mejores prácticas de desarrollo de software seguro en proyectos de código abierto que la empresa mantiene, a los que contribuye o lidera.

Este capítulo incluye recursos útiles para ayudar a las OSPO y desarrolladores de código abierto a aplicar prácticas seguras de desarrollo de software y de cadena de suministro, tanto en el software que utilizan como en el que crean.

En ciertos aspectos, la seguridad es como cualquier otro requisito. Sin embargo, muchos desarrolladores de software y sus gerentes no han recibido suficiente capacitación en seguridad. Además, la seguridad se trata de defender contra atacantes inteligentes, y a menudo depende de cómo funciona el sistema completo en su conjunto, no solo de una parte.

Solucionar problemas de seguridad más adelante a menudo es costoso. Es mejor prevenirlos, reducir sus probabilidades o impacto, y estar preparados en caso de que algo salga mal. Es importante planificar desde el principio y asignar recursos (como tiempo y dinero) para manejar la seguridad adecuadamente. El software de código abierto puede tener una ventaja de seguridad porque permite la revisión por pares en masa y sigue el principio de "open design", pero estos beneficios no ocurren automáticamente.

## Capacitación y Educación

Muchos desarrolladores de software y gerentes no saben lo que necesitan saber sobre seguridad. Esta falta de conocimiento a menudo causa problemas. Aquí hay algunas áreas clave para entender, junto con enlaces a cursos gratuitos de OpenSSF que pueden ayudar. Estos cursos específicos no son obligatorios, pero es importante que todos los involucrados en el desarrollo de software reciban la capacitación adecuada.

Los gerentes (tanto de proyectos de código abierto como cerrado) deben entender cómo gestionar el desarrollo seguro de software. Esto incluye conocer términos de seguridad básicos, cómo gestionar riesgos, cómo construir la seguridad en el diseño, cómo proteger todos los entornos, cómo identificar riesgos temprano y cómo establecer expectativas claras con los stakeholders. Los gerentes también deben entender lo que sus desarrolladores necesitan aprender. Si aún no han sido capacitados, pueden tomar el curso gratuito de la Open Source Security Foundation (OpenSSF) *Security for Software Development Managers (LFD125)* [^1].

Los desarrolladores deben tomar un curso sobre desarrollo seguro de software. Esto incluye cómo construir software seguro durante la planificación, diseño, codificación, pruebas y lanzamiento. Los desarrolladores también necesitan saber cómo evaluar software de terceros. Deben entender las vulnerabilidades comunes (como las del OWASP Top Ten for web apps [^2] y CWE Top 25 for general software [^3]) y cómo evitarlas. También deben saber cómo asegurar entornos de desarrollo y responder a reportes de vulnerabilidades. Si no han recibido esta capacitación, pueden tomar el curso gratuito de OpenSSF *Developing Secure Software (LFD121)* [^4].

Tanto los desarrolladores como los gerentes deben entender cualquier ley o regulación que deban cumplir. Por ejemplo, cualquiera involucrado en software que pueda ser utilizado en la Unión Europea (UE) debe entender la Cyber Resilience Act (CRA). Esto incluye conocer a qué aplica la CRA, los diferentes roles que define (como fabricante o custodio de código abierto) y las responsabilidades legales que crea. Debido a que la CRA cubre un rango amplio e incluye sanciones fuertes, aquellos que necesiten comprenderla pueden tomar el curso gratuito de OpenSSF *Understanding the European Union (EU) Cyber Resilience Act (CRA) (LFEL1001)* [^5].

## Pasos Clave

**Para desarrollar tu propio software:**

1. Revisa la OpenSSF Concise Guide for Developing More Secure Software, que vincula a recursos prácticos [^6].

2. Trabaja para cumplir con el OpenSSF Baseline, una lista breve de verificaciones de seguridad [^7].

3. Obtén un distintivo de Mejores Prácticas de OpenSSF para tu proyecto. Comienza con "aprobado" y planifica lograr "plata" u "oro" con el tiempo [^8].

4. Mejora tu puntuación de OpenSSF Scorecard. Aunque esto se utiliza a menudo para evaluar otros proyectos, también puede ayudarte a medir el tuyo [^9].

**La mayoría del software moderno reutiliza otro software. Elige y usa componentes de código abierto cuidadosamente:**

1. Utiliza la Guía Concisa para Evaluar Software de Código Abierto [^10].

2. Verifica dos veces los nombres de software para evitar ataques de "typosquatting" (donde paquetes maliciosos tienen nombres similares a los de confianza).

1. Utiliza OpenSSF Scorecard para evaluar software antes de usarlo [^9].

**Protege tus entornos, incluyendo desarrollo, construcción, prueba y distribución:**

1. Utiliza autenticación multifactor (MFA) para dificultar que los atacantes obtengan acceso.

2. Asegura tu entorno de compilación. Consulta OpenSSF SLSA para obtener más orientación [^11].

**Utiliza herramientas automatizadas en tu pipeline de integración continua (CI) para detectar problemas de seguridad temprano:**

1. Utiliza múltiples tipos de herramientas, ya que cada una puede encontrar diferentes problemas, consulta la Guide to Security Tools [^12].

2. Para proyectos nuevos ("green field"), habilita todas las verificaciones de seguridad. Para proyectos antiguos ("brown field"), comienza con las verificaciones más importantes para que los reportes sean manejables.

3. Habilita herramientas que detecten vulnerabilidades conocidas en componentes reutilizados.

Prepárate para reportes de vulnerabilidades, pueden ocurrir en cualquier proyecto. Explica claramente cómo las personas pueden reportar vulnerabilidades. Los proyectos de código abierto deben revisar la OpenSSF Guide to implementing a coordinated vulnerability disclosure process [^13].

## Cómo Aplicar Esto a Tu Organización

Mejorar la seguridad del código abierto en tu organización no se trata solo de usar herramientas. También requiere cambios en la cultura y los procesos diarios de trabajo. Uno de los primeros pasos es construir una mentalidad donde la seguridad sea responsabilidad de todos, no solo el trabajo de un pequeño equipo. Los líderes deben comunicar claramente que el desarrollo seguro de software es importante y respaldar esto con tiempo, recursos y reconocimiento para quienes trabajan en ello.

Las prácticas de seguridad deben ser parte del trabajo de desarrollo diario, no algo separado. Por ejemplo, en lugar de ejecutar verificaciones de seguridad solo ocasionalmente, convierte herramientas como scorecards y escaneos de vulnerabilidades en parte de tu pipeline regular de CI/CD. Esto ayuda a hacer que la seguridad sea una parte normal y esperada de cómo tu equipo construye software.

La capacitación y educación deben ocurrir regularmente, no solo una vez. Los desarrolladores y gerentes deben ser alentados a aprender los conceptos básicos del desarrollo seguro de software. Esto puede incluir cursos gratuitos de OpenSSF y otros programas. Asegúrate de que tus equipos sepan que aprender sobre seguridad es importante y será reconocido. Esto construye interés y responsabilidad a largo plazo.

También es útil ser abierto sobre el progreso de seguridad. Alienta a los equipos a rastrear y compartir su progreso en objetivos como obtener distintivos de Mejores Prácticas o mejorar sus resultados de Scorecard. Esto crea un entorno positivo donde los equipos se ayudan mutuamente y mejoran juntos, en lugar de sentirse culpados cuando algo sale mal.

Por último, apoya la mejora continua. La seguridad no es algo que termines, siempre está cambiando. Establece tiempos regulares para revisar riesgos, actualizar herramientas y prácticas, y compartir lo que tus equipos han aprendido. Brinda a los equipos la libertad de tomar decisiones sobre seguridad temprano en el proceso de desarrollo, no solo al final o después de que ocurra un problema.

Al crear una cultura de responsabilidad compartida, integrar seguridad en el trabajo diario, invertir en aprendizaje, fomentar la apertura y mejorar con el tiempo, tu organización puede lograr progreso real en asegurar el software de código abierto que construye y utiliza.

## Recursos y Notas al Pie

### Recursos

- OpenSSF: https://openssf.org
- OWASP: https://owasp.org/
- CWE: https://cwe.mitre.org/index.html

### Notas al Pie

[^1]: Open Source Security Foundation OpenSSF course *Security for Software Development Managers: (LFD125)*
 https://training.linuxfoundation.org/training/security-for-software-development-managers-lfd125/.

[^2]: OWASP Top Ten for web apps: https://owasp.org/www-project-top-ten/

[^3]: CWE Top 25 for general software: https://cwe.mitre.org/top25/

[^4]: OpenSSF course Developing Secure Software (LFD121): https://training.linuxfoundation.org/training/developing-secure-software-lfd121/

[^5]: Understanding the EU Cyber Resilience Act (CRA): https://training.linuxfoundation.org/express-learning/understanding-the-eu-cyber-resilience-act-cra-lfel1001/

[^6]: Concise Guide for Developing More Secure Software: https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software

[^7]: OpenSSF Baseline: https://baseline.openssf.org/

[^8]: OpenSSF Best Practices badge: https://www.bestpractices.dev/

[^9]: OpenSSF Scorecard: https://github.com/ossf/scorecard

[^10]: Concise Guide for Evaluating Open Source Software: https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software

[^11]: OpenSSF SLSA: https://slsa.dev/

[^12]: Guide to Security Tools: https://github.com/ossf/wg-security-tooling/blob/main/guide.md#readme

[^13]: OpenSSF Guide to implementing a coordinated vulnerability disclosure process:
https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md#readme
