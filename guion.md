# Guion de Exposición — Ingeniería del Mantenimiento de Software

**IPS Gral. San Martín — 6to Informática**
**Docente:** Paula Ávila
**34 slides · 4 expositores**

---

## Distribución de Slides

| Persona | Slides | Temas |
|---------|--------|-------|
| **Persona 1** | 1–7 | Definiciones y Conceptos Fundamentales |
| **Persona 2** | 8–16 | Clasificación de Actividades + Métricas |
| **Persona 3** | 17–25 | Costos + Actores + 11 Actividades |
| **Persona 4** | 26–34 | Lehman + Problemas + Conceptos Técnicos + Conclusión |

---

# Persona 1 — Definiciones y Conceptos Fundamentales (Slides 1–7)

---

## Slide 1 — Portada

**Tiempo estimado:** 30 segundos

**Qué dice la slide:**
- Título: "Ingeniería del Mantenimiento de Software"
- Subtítulo: "La realidad del ciclo de vida del código"
- Institucion: IPS Gral. San Martín
- Docente: Paula Ávila
- Estudiantes: Santiago Cañal, Nicolás Paz Reyes, Valentino Aviani, Martín Moloeznik
- Fecha: mayo 2026

**Quétiene que decir:**
> "Buenos días. Somos [nombre], [nombre], [nombre] y [nombre], alumnos de 6to Informática. Hoy vamos a presentar nuestro trabajo de investigación sobre Ingeniería del Mantenimiento de Software, una materia que —como vamos a ver— consume la mayor parte del tiempo y el presupuesto en la industria del software."

---

## Slide 2 — Agenda

**Tiempo estimado:** 45 segundos

**Qué dice la slide:**
1. Definición y Síntesis Metodológica
2. Clasificación de Actividades
3. Métricas y Valores Estadísticos
4. Actores y Responsabilidades
5. Conceptos Técnicos Asociados
6. Conclusión

**Qué tiene que decir:**
> "La presentación está dividida en seis bloques. Primero vamos a definir qué es el mantenimiento de software según los estándares internacionales. Después vamos a ver cómo se clasifican las actividades de mantenimiento. Luego vamos a mostrar datos concretos sobre cuánto esfuerzo y dinero absorbe el mantenimiento. Después veremos quiénes son los actores involucrados y qué hacen. Más adelante exploraremos conceptos técnicos como mantenibilidad, efecto dominó y sistemas heredados. Y finalmente cerraremos con una valoración personal del tema."

---

## Slide 3 — Section Header: ¿Qué es el Mantenimiento?

**Tiempo estimado:** 10 segundos (solo presentar la sección)

**Qué tiene que decir:**
> "Empecemos por la pregunta fundamental: ¿qué es realmente el mantenimiento de software?"

---

## Slide 4 — Una Disciplina Fundamental

**Tiempo estimado:** 1 minuto 15 segundos

**Qué dice la slide:**
- Cita textual en la diapositiva: "El mantenimiento de software constituye una de las disciplinas fundamentales dentro de la ingeniería de software moderna. Lejos de ser una actividad secundaria o meramente correctiva, representa el conjunto de procesos sistemáticos que garantizan la supervivencia, la adaptabilidad y el valor estratégico de los sistemas informáticos a lo largo de su ciclo de vida operativo."
- Tres ejes de la presentación: Definiciones, Clasificación, Métricas + Roles + Conceptos
- **Retrato de Meir M. Lehman** — Padre de las Leyes de la Evolución del Software (1974). El software en uso cambia continuamente o muere.

**Qué tiene que decir:**
> "El mantenimiento de software no es simplemente 'arreglar errores'. Como pueden ver en la diapositiva, es una disciplina fundamental. Cuando un sistema de software se entrega, no termina su vida útil —al contrario, recién empieza un ciclo continuo de cambios. La cita que ven en pantalla lo resume perfectamente: el mantenimiento garantiza la supervivencia, la adaptabilidad y el valor estratégico de los sistemas.
>
>A la derecha tenemos a **Meir M. Lehman**, el padre de las Leyes de la Evolución del Software. En 1974 demostró algo clave: el software que se usa en el mundo real debe cambiar constantemente o simplemente muere. Esa fue la primera ley —la ley del cambio continuo— y es la base teórica que explica por qué existe el mantenimiento de software como disciplina.
>
>Esta presentación aborda tres grandes ejes que van a ver reflejados a lo largo de toda la presentación: las definiciones, la clasificación de actividades, y las métricas junto con los roles y conceptos técnicos."

---

## Slide 5 — La Crisis de Complejidad y el Ciclo Continuo

**Tiempo estimado:** 1 minuto 15 segundos

**Qué dice la slide:**
- La ingeniería de software surgió por la crisis de complejidad de fines de los 60
- La entrega inicial es solo el comienzo
- Línea temporal: Crisis de los 60 → Entrega Inicial → Ciclo Continuo
- Cita: "La entrega inicial de un programa era apenas el comienzo"
- **Retrato de Margaret Hamilton** — Acuñó el término "Ingeniería de Software" liderando el software del Apollo Guidance Computer en el MIT.

**Qué tiene que decir:**
> "Para entender el mantenimiento, tenemos que remontarnos a fines de los años 60. En esa época, el software se volvió tan complejo que se empezó a hablar de una 'crisis de complejidad'. Los proyectos se atrasaban, se iban de presupuesto, y el código era cada vez más difícil de manejar. De esa crisis nació la ingeniería de software como disciplina.
>
>Y acá a la derecha tenemos a **Margaret Hamilton**, que fue quien acuñó precisamente el término 'Ingeniería de Software' mientras lideraba el equipo que desarrolló el software de a bordo del Apollo Guidance Computer en el MIT —el software que llevó el hombre a la Luna. Ella empezó a usar ese término para que el desarrollo de software se tomara tan en serio como la ingeniería de hardware.
>
>Lo que se descubrió fue algo clave: cuando un programa se entrega al cliente, no es el final —es el comienzo de un ciclo continuo de modificaciones para mantenerlo vivo y útil. Como dice la cita en pantalla, la entrega inicial era apenas el comienzo."

---

## Slide 6 — Las Definiciones Institucionales

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
- **ANSI/IEEE 610.12 (1990):** "Modificación de un producto de software después de su entrega al cliente o usuario para corregir defectos, para mejorar el rendimiento u otras propiedades deseables, o para adaptarlo a un cambio de entorno."
- **ISO/IEC 14764 (2006):** "Proceso que describe el esqueleto de actividades destinadas a modificar un producto de software existente preservando su integridad funcional y arquitectónica. Este proceso cubre todo el ciclo de vida del sistema, desde la planificación de la transición del desarrollo inicial hasta el retiro definitivo del producto."
- **Pressman (1998):** complementa describiendo el mantenimiento como el conjunto de actividades de ingeniería de software que ocurren después de la entrega.

**Qué tiene que decir:**
> "Bueno, esta idea de que el software cambia continuamente no es solo una observación — está formalizada en estándares internacionales. Acá tenemos las dos definiciones institucionales más importantes.
>
> La primera es de la **ANSI/IEEE 610.12 de 1990**, un estándar de terminología que define el mantenimiento como la modificación del software después de la entrega para corregir defectos, mejorar el rendimiento, o adaptarlo a cambios del entorno.
>
> La segunda es de la **ISO/IEC 14764 de 2006**, que va más allá: no habla solo de modificar código, sino de un proceso que preserva la integridad del sistema y cubre TODO el ciclo de vida — desde la planificación de la transición hasta el retiro definitivo.
>
> Antes de que existiera esta última norma, **Pressman** ya en 1998 describía el mantenimiento con la misma visión: corrección de errores, adaptación a nuevos entornos y mejora de prestaciones. Un autor clásico que ya anticipaba lo que después formalizaron los estándares."

---

## Slide 7 — Nuestra Síntesis

**Tiempo estimado:** 45 segundos

**Qué dice la slide:**
> "El mantenimiento de software es el proceso de ingeniería que, posterior a la entrega del sistema, modifica su código y arquitectura para corregir defectos, adaptarlo a entornos cambiantes y mejorar su mantenibilidad y funcionalidad, preservando su estabilidad operativa."

**Qué tiene que decir:**
> "A partir de estas definiciones, nosotros construimos nuestra propia síntesis. El mantenimiento de software es el proceso de ingeniería que, después de entregar el sistema, modifica el código y la arquitectura. ¿Para qué? Para corregir defectos, adaptarlo a entornos que cambian, y mejorar su mantenibilidad y funcionalidad. Todo esto mientras se preserva la estabilidad operativa del sistema. Esta definición unifica las dos perspectivas: la correctiva y la evolutiva."

---

# Persona 2 — Clasificación de Actividades + Métricas (Slides 8–16)

---

## Slide 8 — Section Header: Clasificación

**Tiempo estimado:** 10 segundos

**Qué tiene que decir:**
> "Pasemos ahora a la clasificación de las actividades de mantenimiento."

---

## Slide 9 — Mantenimiento Correctivo

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
- Tipo: Reactivo
- Definición: Modificaciones reactivas obligadas por fallos de ejecución post-entrega. El programa no satisface los requerimientos iniciales. Elimina errores lógicos y restaura el estado óptimo original.
- Criterio: Reactivo ante fallas operacionales
- Foco del Cambio: Eliminación de errores lógicos
- Impacto Funcional: Restaura el estado óptimo original

**Qué tiene que decir:**
> "El mantenimiento correctivo es el más conocido, pero no el más común como vamos a ver después. Es reactivo: ocurre cuando el programa falla en producción. El objetivo es localizar y eliminar defectos. Un defecto es una característica del sistema con potencial de causar un fallo, y un fallo ocurre cuando el comportamiento del sistema es diferente de lo especificado. El impacto funcional es restaurar el estado óptimo original que debería haber tenido el sistema desde el principio."

---

## Slide 10 — Mantenimiento Adaptativo

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
- Tipo: Reactivo
- Definición: Cambios para mantener la operatividad cuando cambia el entorno tecnológico externo (SO, bases de datos), sin modificar la funcionalidad percibida.
- Criterio: Reactivo ante evolución de TI
- Foco del Cambio: Migración de entornos (SO, bases de datos)
- Impacto Funcional: Usuario percibe idéntica funcionalidad

**Qué tiene que decir:**
> "El mantenimiento adaptativo también es reactivo, pero no por fallos del software sino por cambios en el entorno. Por ejemplo, cuando el sistema operativo se actualiza, o cuando la base de datos cambia de versión, el software tiene que adaptarse para seguir funcionando. Lo interesante es que el usuario final no nota ningún cambio en la funcionalidad —el software hace exactamente lo mismo que antes, pero en un entorno tecnológico distinto. Puede ir desde un pequeño retoque hasta tener que reescribir prácticamente todo el programa."

---

## Slide 11 — Mantenimiento Perfectivo

**Tiempo estimado:** 1 minuto 15 segundos

**Qué dice la slide:**
- Tipo: Proactivo
- Definición: Tareas proactivas para expandir funcionalidad, optimizar rendimiento, depurar documentación o mejorar UX.
- Criterio: Proactivo, alineado al negocio
- Foco del Cambio: Nuevas características, rendimiento, docs, UX
- Impacto Funcional: Expande capacidades del software
- Subdivisión: Ampliación (nuevas funcionalidades) y Eficiencia (mejora de ejecución)
- Nota: Aumenta cuando un producto tiene éxito comercial

**Qué tiene que decir:**
> "El mantenimiento perfectivo es proactivo, está alineado a las necesidades del negocio. Acá el objetivo no es arreglar algo que está roto, sino mejorar el software: agregar nuevas funcionalidades, optimizar el rendimiento, mejorar la documentación o la experiencia del usuario. Algunos autores lo dividen en dos subtipos: mantenimiento de ampliación —cuando se agregan funcionalidades nuevas— y mantenimiento de eficiencia —cuando se mejora el rendimiento. Es importante saber que cuanto más éxito tiene un producto, más mantenimiento perfectivo requiere, porque más usuarios piden más funcionalidades."

---

## Slide 12 — Mantenimiento Preventivo

**Tiempo estimado:** 1 minuto 15 segundos

**Qué dice la slide:**
- Tipo: Proactivo (ISO/IEC 14764 e IEEE 1219)
- Definición: Modificación proactiva del código para identificar y subsanar defectos latentes ANTES de que se conviertan en fallas en producción.
- Cita: "antes de que se conviertan en fallas efectivas en el entorno de producción"
- Criterio: Proactivo, control de calidad
- Foco del Cambio: Refactorización, deuda técnica
- Impacto Funcional: Mejora mantenibilidad futura
- Subtipo: Mantenimiento para la Reutilización — modificar componentes para reutilizarlos en bibliotecas

**Qué tiene que decir:**
> "El mantenimiento preventivo es el que más partido saca de las técnicas de ingeniería inversa y reingeniería. Es proactivo: buscamos defectos latentes y debilidades de diseño antes de que se conviertan en fallas reales en producción. Es como hacerle los controles al auto antes de que se rompa, no después. El foco está en la refactorización y en reducir la deuda técnica. Y hay un subtipo interesante: el mantenimiento para la reutilización, que consiste en modificar componentes para que puedan reutilizarse en otros proyectos."

---

## Slide 13 — Cuadro 1: Clasificación de Tipos de Mantenimiento

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
Tabla con 4 filas (Correctivo, Adaptativo, Perfectivo, Preventivo) y 4 columnas:
- **Tipo** | **Criterio** | **Foco del Cambio** | **Impacto Funcional**
- Correctivo | Reactivo ante fallas operacionales | Eliminación de errores lógicos | Restaura estado óptimo original
- Adaptativo | Reactivo ante evolución de TI | Migración de entornos | Usuario percibe idéntica funcionalidad
- Perfectivo | Proactivo, alineado al negocio | Nuevas características o mejoras | Expande capacidades del software
- Preventivo | Proactivo, control de calidad | Refactorización, deuda técnica | Mejora mantenibilidad futura

**Qué tiene que decir:**
> "Acá tenemos un resumen visual muy útil. En la tabla pueden ver los cuatro tipos de mantenimiento con sus criterios, focos e impactos. Observen cómo los tipos reactivos —correctivo y adaptativo— restauran o mantienen el estado original, mientras que los proactivos —perfectivo y preventivo— expanden capacidades o mejoran la mantenibilidad futura. Es importante entender que NO todo el mantenimiento es correctivo, como mucha gente cree."

---

## Slide 14 — Section Header: El Impacto Financiero y Esfuerzo

**Tiempo estimado:** 10 segundos

**Qué tiene que decir:**
> "Pasemos ahora a los números. El mantenimiento no solo es variado, también es caro. Muy caro."

---

## Slide 15 — La Evolución Histórica

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
Tres épocas con barras visuales:
- **1970s:** Desarrollo 60–70% | Mantenimiento 30–40% — Driver: Hardware como mayor inversión
- **1990s:** Desarrollo 25–35% | Mantenimiento 65–75% — Driver: ERP multi-módulo, crisis Y2K
- **2020s:** Desarrollo 10–20% | Mantenimiento 80–90% — Driver: Legacy crisis, SaaS, deuda técnica

**Qué tiene que decir:**
> "Acá pueden ver claramente cómo cambió la industria. En los años 70, la mayor inversión era en hardware, y el mantenimiento representaba solo entre el 30 y el 40% del esfuerzo. Para los 90, la relación se invirtió: el mantenimiento pasó a ser el 65-75%, impulsado por sistemas ERP multi-módulo y la crisis del año 2000. Y hoy, en los 2020s, el mantenimiento consume entre el 80 y el 90% del esfuerzo total. Las causas: la crisis del código heredado, la proliferación de SaaS y la acumulación de deuda técnica. Esto significa que de cada 10 horas de trabajo de un desarrollador, 8 o 9 son para mantener sistemas existentes y solo 1 o 2 para crear software nuevo."

---

## Slide 16 — Distribución del Esfuerzo por Tipo

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
Tabla con los 4 tipos y rangos:
- **Perfectivo:** 25%–50% — Nuevos requerimientos de negocio
- **Adaptativo:** 15%–50% — Actualizaciones de plataformas
- **Correctivo:** 20%–25% — Diagnóstico de fallas operativas
- **Preventivo:** 4%–15% — Saneamiento arquitectónico
- Nota: Según Frazer (1992), más del 60% de las modificaciones corresponden a mantenimiento perfectivo. Respaldado por McKee (1984) y Basili et al. (1996).

**Qué tiene que decir:**
> "Esta tabla derriba el mito de que el mantenimiento es básicamente corregir errores. Miren los números: el mantenimiento perfectivo —agregar nuevas funcionalidades y mejorar el software— consume entre el 25 y el 50% del esfuerzo. El adaptativo —cambiar entornos— puede llegar hasta el 50%. Mientras tanto, el correctivo —arreglar errores— representa solo entre el 20 y el 25%. Y el preventivo, que es el que más beneficio trae a largo plazo, lamentablemente recibe solo entre el 4 y el 15%. Según Frazer, más del 60% de las modificaciones que se hacen al software son perfectivas. O sea, no estamos arreglando errores la mayor parte del tiempo, estamos mejorando sistemas."

---

# Persona 3 — Costos + Actores + 11 Actividades (Slides 17–25)

---

## Slide 17 — El Costo del Negocio

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
Grid 2×2 con 4 indicadores:
1. **55%–80%** — Presupuesto KLO ("Keeping the Lights On"): las grandes corporaciones gastan entre el 55% y el 80% de su presupuesto de TI en mantener sistemas existentes, dejando poco margen para innovación.
2. **15%–25%** — Regla del 15-25% anual: mantener una app en estado óptimo cuesta entre el 15 y el 25% de su costo de desarrollo original. Con deuda técnica: 30-40%.
3. **$40K–$80K** — Costo mensual de un equipo ágil mediano (4-6 ingenieros full-time).
4. **$2,300–$9,000/min** — Tiempo de inactividad: grandes corporaciones pierden $2,300-$9,000 por minuto de caída. Pequeñas empresas: $137-$427/min.

**Qué tiene que decir:**
> "Acá tenemos números concretos que muestran por qué el mantenimiento es un tema de negocio, no solo técnico. Primero: el presupuesto KLO —Keeping the Lights On— representa entre el 55 y el 80% del presupuesto de TI de una gran corporación. Eso es lo que gastan solo para mantener los sistemas existentes funcionando, sin innovar. Segundo: la regla del 15 al 25%: mantener una aplicación en buen estado cuesta cada año entre el 15 y el 25% de lo que costó crearla. Si hay deuda técnica, ese número sube al 30 o 40%. Tercero: un equipo de 4 a 6 ingenieros full-time cuesta entre 40 y 80 mil dólares por mes. Y cuarto: cuando un sistema crítico se cae, una gran corporación pierde entre 2.300 y 9.000 dólares por minuto. Una PYME pierde entre 137 y 427 dólares por minuto."

---

## Slide 18 — Section Header: Actores y Responsabilidades

**Tiempo estimado:** 10 segundos

**Qué tiene que decir:**
> "Ahora veamos quiénes son las personas que mantienen el software y qué hacen exactamente."

---

## Slide 19 — Cuadro 4: Actores del Mantenimiento

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
Tabla con actores, tareas clave, tipos y descripciones:
| Actor | Tarea Clave | Tipos | Descripción |
|---|---|---|---|
| Resp. de Mant. (Gestión) | Gestión de Solicitudes (MR/PR) | Todos | Prioriza colas y asigna tareas con Scrum/Kanban |
| Resp. de Mant. (Transición) | Planificación de Transición | Todos | Evalúa documentación y pruebas para pasar a mantenimiento |
| Analista de Mant. | Análisis de Impacto y Viabilidad | Correctivo, Adaptativo, Perfectivo | Evalúa componentes afectados para prevenir regresiones |
| Programador/Técnico | Codificación de Parches | Correctivo, Preventivo, Perfectivo | Hotfixes, actualización de dependencias y optimizaciones |
| Programador/Técnico | Pruebas de Regresión | Todos | Pruebas automatizadas para validar comportamiento histórico |
| Programador/Técnico | Migración y Despliegue | Adaptativo | Traslado del sistema a nuevos servidores o nubes |

**Qué tiene que decir:**
> "Esta tabla resume los actores del mantenimiento y sus responsabilidades. Tenemos básicamente tres roles. El Responsable de Mantenimiento, que se encarga de la gestión: prioriza solicitudes de cambio, asigna tareas usando metodologías ágiles como Scrum o Kanban, y planifica la transición del desarrollo al mantenimiento. El Analista de Mantenimiento, que evalúa el impacto de cada cambio, identifica dependencias ocultas y previene regresiones. Y el Programador o Técnico, que tiene tres tipos de tareas: codificar parches (como hotfixes), ejecutar pruebas de regresión, y realizar migraciones y despliegues. Cada tarea aplica a tipos específicos de mantenimiento, como indica la columna 'Tipos'."

---

## Slide 20 — Rol: Responsable de Mantenimiento

**Tiempo estimado:** 45 segundos

**Qué dice la slide:**
- Gestión de Solicitudes (MR/PR)
- Tareas: prioriza colas con Scrum/Kanban, gestiona MR y PR, coordina comunicación stakeholders-equipo
- Tipos: Todos (Correctivo, Adaptativo, Perfectivo, Preventivo)

**Qué tiene que decir:**
> "El Responsable de Mantenimiento es el rol gerencial. Sus tareas principales son: priorizar las colas de trabajo y asignar tareas usando metodologías como Scrum o Kanban, gestionar las solicitudes de modificación —MR— y los reportes de problemas —PR—, y coordinar la comunicación entre los stakeholders y el equipo técnico. Este rol participa en todos los tipos de mantenimiento."

---

## Slide 21 — Planificación de Transición

**Tiempo estimado:** 45 segundos

**Qué dice la slide:**
- Responsable de Mantenimiento (continuación)
- Tareas: revisa documentación técnica, verifica pruebas automatizadas, asegura transferencia de conocimiento
- Tipos: Todos

**Qué tiene que decir:**
> "Otra función clave del Responsable de Mantenimiento es la planificación de la transición. Cuando un sistema pasa de desarrollo a mantenimiento, hay que asegurarse de que la documentación técnica esté completa, que existan pruebas automatizadas para validar el comportamiento base, y que el equipo de desarrollo transfiera el conocimiento necesario al equipo de mantenimiento. Esto evita que el sistema se degrade rápidamente."

---

## Slide 22 — Rol: Analista de Mantenimiento

**Tiempo estimado:** 45 segundos

**Qué dice la slide:**
- Análisis de Impacto y Viabilidad
- Tareas: evalúa componentes afectados, identifica dependencias ocultas, estima esfuerzo/costo/riesgo
- Tipos: Correctivo, Adaptativo, Perfectivo

**Qué tiene que decir:**
> "El Analista de Mantenimiento es el que evalúa cada solicitud de cambio antes de que se implemente. Sus tareas son: evaluar qué componentes del sistema se van a ver afectados, identificar dependencias ocultas para prevenir regresiones —efectos dominó—, y estimar el esfuerzo, costo y riesgo de cada modificación. Este rol aplica al mantenimiento correctivo, adaptativo y perfectivo."

---

## Slide 23 — Rol: Programador / Técnico

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
Dos áreas:
- **Codificación de Parches:** hotfixes en producción, actualización de dependencias, optimizaciones (Tipos: Correctivo, Preventivo, Perfectivo)
- **Pruebas de Regresión:** pruebas automatizadas, verificar que ningún cambio rompa funcionalidad existente, mantener suites de test (Tipos: Todos)

**Qué tiene que decir:**
> "El Programador o Técnico tiene dos grandes responsabilidades. Primero, la codificación de parches: desde hotfixes urgentes en producción hasta actualizaciones de dependencias y optimizaciones de rendimiento. Segundo, las pruebas de regresión: ejecutar pruebas automatizadas para asegurar que los cambios nuevos no rompan funcionalidad que ya funcionaba. Es clave entender que cada cambio en un sistema existente puede tener efectos secundarios, por eso las pruebas de regresión son tan importantes."

---

## Slide 24 — Migración y Despliegue

**Tiempo estimado:** 30 segundos

**Qué dice la slide:**
- Programador/Técnico (continuación)
- Tareas: migración a cloud, cambio de servidores, actualización de stacks tecnológicos
- Tipo: Adaptativo

**Qué tiene que decir:**
> "Y finalmente, el Programador también se encarga de migraciones y despliegues. Esto incluye migrar infraestructura on-premise a la nube, cambiar servidores físicos por virtuales, o actualizar stacks tecnológicos completos. Este tipo de trabajo corresponde al mantenimiento adaptativo, porque el objetivo es mantener el sistema funcionando en un entorno nuevo."

---

## Slide 25 — Las 11 Actividades Concretas del Mantenimiento

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
Basili et al. (1996) identificaron 11 actividades:
1. Análisis de impacto y de costes/beneficios
2. Comprensión del cambio
3. Diseño del cambio
4. Codificación y pruebas unitarias
5. Inspección, certificación y consultoría
6. Pruebas de integración
7. Pruebas de aceptación
8. Pruebas de regresión
9. Documentación del sistema
10. Otra documentación (del usuario)
11. Otras actividades (gestión del proyecto)

Callout: La proporción de esfuerzo varía según el tipo — en correctivo se dedica más a comprensión; en perfectivo a inspección y certificación; diseño, codificación y pruebas son similares en ambos.

**Qué tiene que decir:**
> "Basili y su equipo identificaron 11 actividades concretas que se realizan con cada modificación del software. Van desde el análisis de impacto inicial hasta la documentación final. Es importante notar que el esfuerzo se distribuye distinto según el tipo de mantenimiento. En el mantenimiento correctivo, la mayor parte del tiempo se va en comprender el cambio —entender qué salió mal y por qué. En el perfectivo, en cambio, se dedica más tiempo a inspección, certificación y consultoría. Pero el diseño, la codificación y las pruebas requieren esfuerzos similares en ambos tipos."

---

# Persona 4 — Lehman + Problemas + Conceptos Técnicos + Conclusión (Slides 26–34)

---

## Slide 26 — Por qué el Software Nunca se Termina (Leyes de Lehman)

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
Las 5 leyes de Lehman (1980):
| Ley | Nombre | Descripción |
|---|---|---|
| I | Continuidad del Cambio | Un programa usado debe cambiar; si no, será cada vez menos usado. Apenas se escribe, ya está desfasado. |
| II | Incremento de la Complejidad | Con los cambios, la estructura se vuelve más compleja salvo esfuerzo activo para evitarlo. |
| III | Evolución del Programa | Proceso autorregulado: tamaño, tiempo entre versiones y errores revelan invariantes. |
| IV | Conservación de la Estabilidad Organizacional | La carga de desarrollo es aproximadamente constante, independiente de los recursos. |
| V | Conservación de la Familiaridad | El incremento de cambios por versión es aproximadamente constante. |

**Qué tiene que decir:**
> "Las Leyes de Lehman son observaciones empíricas formuladas entre 1974 y 1996 que siguen vigentes. La primera ley dice que un programa usado en el mundo real debe cambiar constantemente —si no, se vuelve obsoleto. La segunda ley es la más impactante: cada vez que modificamos un programa, su estructura se vuelve más compleja, a menos que hagamos un esfuerzo activo por evitarlo. Esto explica por qué el software tiende a degradarse con el tiempo. La tercera ley dice que la evolución del programa es un proceso autorregulado con patrones predecibles. La cuarta y quinta leyes hablan de estabilidad organizacional y familiaridad: la carga de trabajo y el ritmo de cambios se mantienen constantes a lo largo de la vida del sistema."

---

## Slide 27 — Problemas Clásicos del Mantenimiento de Software

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
10 problemas identificados por Schneidewind (1987), Pressman (1993), Baxter y Pigdeon (1997), Sommerville (1992):
1. Mantenimiento ad-hoc, sin metodología formal
2. Documentación desfasada o inexistente
3. Código que no cumple estándares
4. Incremento en tiempo para entender programas
5. Efectos secundarios por cambios
6. Costos de mantenimiento muy altos
7. Sommerville: "cualquier cambio conlleva corrupción de la estructura"
8. Decisiones de programación no documentadas
9. Falta de participación del usuario durante el desarrollo
10. Problemas de gestión: programadores ven mantenimiento como actividad inferior

**Qué tiene que decir:**
> "El mantenimiento de software enfrenta múltiples problemas clásicos. El principal es que muchas veces se hace de manera ad-hoc, sin metodología formal —Pressman dice que raramente existen organizaciones formales de mantenimiento. La documentación suele estar desfasada o directamente no existe. El código no cumple estándares y se vuelve cada vez más difícil de entender. Cada cambio puede generar efectos secundarios inesperados. Y hay un problema de gestión importante: muchos programadores consideran el mantenimiento como una actividad inferior y menos creativa que el desarrollo nuevo, lo que genera baja moral y trabajo de menor calidad. Sommerville lo resume bien: cualquier cambio conlleva corrupción de la estructura del software."

---

## Slide 28 — Section Header: Ingeniería Dura y Consecuencias

**Tiempo estimado:** 10 segundos

**Qué tiene que decir:**
> "Pasemos ahora a los conceptos técnicos más profundos."

---

## Slide 29 — Mantenibilidad (ISO/IEC 9126)

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
- **Maintainability** — Característica cualitativa del software que describe la facilidad y velocidad con la que un sistema puede modificarse después de su entrega.
- 5 subcaracterísticas:
  - **Analizabilidad:** capacidad de diagnosticar causas de fallo
  - **Cambiabilidad:** facilidad de implementar modificaciones
  - **Estabilidad:** resistencia a efectos secundarios no deseados
  - **Testabilidad:** verificación eficiente de cambios
  - **Cumplimiento:** adhesión a estándares de mantenibilidad

**Qué tiene que decir:**
> "La mantenibilidad es una característica de calidad del software. Un sistema mantenible es fácil y rápido de modificar. El estándar ISO/IEC 9126 la descompone en 5 subcaracterísticas. La analizabilidad es qué tan fácil es encontrar la causa de un problema. La cambiabilidad, qué tan fácil es hacer la modificación. La estabilidad, qué tan resistente es el sistema a efectos secundarios. La testabilidad, qué tan eficiente es verificar que los cambios funcionan. Y el cumplimiento, si el software sigue estándares. Cuando un sistema es mantenible, los costos de mantenimiento son mucho más bajos y los riesgos de errores también."

---

## Slide 30 — Efecto Dominó (Ripple Effect)

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
- Propagación de cambios no planificados: un cambio en el Módulo A rompe inesperadamente los Módulos B, C y D.
- Visual: Módulo A → B → C → D
- Cita académica: término acuñado por Haney (matrices probabilísticas), refinado por Yau, Collofello y Black (algoritmos de análisis estático). Un sistema propuesto al efecto dominó incrementa drásticamente los esfuerzos y destruye la confiabilidad.

**Qué tiene que decir:**
> "El efecto dominó es uno de los fenómenos más peligrosos en el mantenimiento de software. Ocurre cuando un cambio en un módulo —digamos el Módulo A— genera errores en cascada en otros módulos que no estaban destinados a cambiar. El término fue acuñado por Haney usando matrices probabilísticas de interconexión modular, y después refinado por Yau, Collofello y Black con algoritmos de análisis estático. Un sistema propenso al efecto dominó multiplica los esfuerzos de mantenimiento y destruye la confiabilidad del producto, porque nunca se sabe qué más se va a romper al hacer un cambio."

---

## Slide 31 — Estabilidad de un Diseño (Design Stability)

**Tiempo estimado:** 45 segundos

**Qué dice la slide:**
- Capacidad de la arquitectura para resistir la propagación de cambios: inmunidad estructural contra el efecto dominó.
- Visual: escudo con principios:
  - Bajo acoplamiento
  - Alta cohesión
  - Patrones de diseño con interfaces abstractas
  - Actúan como "escudos" que minimizan dependencias directas

**Qué tiene que decir:**
> "La estabilidad de un diseño es justamente lo opuesto al efecto dominó. Es la capacidad de la arquitectura para CONFINA R el impacto de un cambio de manera local, sin que se propague al resto del sistema. Esto se logra con tres principios: bajo acoplamiento —que los módulos dependan lo menos posible entre sí—, alta cohesión —que cada módulo tenga una responsabilidad bien definida—, y el uso de patrones de diseño con interfaces abstractas que actúan como escudos protegiendo al resto del sistema de los cambios."

---

## Slide 32 — Sistemas Heredados (Legacy Systems)

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
- Infraestructura que, a pesar de operar sobre plataformas obsoletas, resulta indispensable para el negocio.
- 4 factores de riesgo críticos:
  1. Ausencia absoluta de documentación técnica
  2. Pérdida de la traza de programadores originales
  3. Imposibilidad de realizar pruebas automatizadas
  4. Acoplamiento extremo — vulnerable al efecto dominó
- "Su reemplazo total representa un costo financiero y un riesgo prohibitivos."

**Qué tiene que decir:**
> "Un sistema heredado —legacy system— es software que funciona sobre tecnologías obsoletas pero que resulta indispensable para el negocio. Es imposible reemplazarlo porque el costo es prohibitivo y el riesgo de migración es altísimo. Estos sistemas tienen cuatro características que los hacen particularmente peligrosos: no tienen documentación actualizada, se perdieron los programadores originales que los crearon, es imposible hacer pruebas automatizadas, y tienen un acoplamiento extremo que los hace muy vulnerables al efecto dominó. Por todo esto, las organizaciones se ven obligadas a extender su vida útil con parches cada vez más costosos."

---

## Slide 33 — La Cadena Causa → Costo

**Tiempo estimado:** 1 minuto

**Qué dice la slide:**
Cadena de 6 pasos:
Diseño Deficiente → Alto Acoplamiento → Efecto Dominó → Baja Mantenibilidad → Sistema Heredado → Alto Costo

Explicación: un diseño deficiente con bajo estabilidad genera alto acoplamiento, que causa efecto dominó, que deteriora la mantenibilidad, que con el tiempo convierte el sistema en legacy, y eso dispara los costos al punto de consumir todo el presupuesto KLO y bloquear la innovación.

**Qué tiene que decir:**
> "Esta slide resume todo lo que vimos hasta ahora en una cadena de causa y efecto. Un diseño original deficiente, con malas decisiones arquitectónicas, genera alto acoplamiento entre los componentes. Ese acoplamiento causa efecto dominó cuando se hacen cambios. El efecto dominó deteriora la mantenibilidad del sistema —cuesta cada vez más entenderlo y modificarlo. Con los años, los parches apresurados erosionan la arquitectura hasta convertir el software en un sistema heredado. Y en ese punto, el costo de mantenimiento se dispara, consumiendo la mayor parte del presupuesto de TI y bloqueando la capacidad de innovación de la empresa. La moraleja es clara: la calidad del diseño inicial determina el costo de mantenimiento futuro."

---

## Slide 34 — Conclusión y Valoración Personal

**Tiempo estimado:** 1 minuto 30 segundos

**Qué dice la slide:**
- Antes de la investigación: se pensaba que el mantenimiento era solo corregir errores.
- Descubrimiento: la mayor parte del trabajo no es crear software nuevo, sino mantener el que existe.
- Dos razones fundamentales:
  - **Escalabilidad del Proyecto:** código mantenible = menos tiempo perdido entendiendo código ajeno = menos errores y frustraciones.
  - **Razón Económica:** código mal mantenido = entregas tardías = mala imagen = menos ingresos y menos proyectos nuevos.

**Qué tiene que decir:**
> "Para cerrar, queremos compartir nuestra valoración personal. Antes de hacer esta investigación, pensábamos que el mantenimiento de software era básicamente corregir errores. Pero lo que más nos sorprendió fue descubrir que la mayor parte del trabajo de un desarrollador no es crear software nuevo, sino mantener el que ya existe. Esto nos cambió completamente la perspectiva.
>
> Consideramos que el mantenimiento es sumamente importante por dos razones. La primera es la escalabilidad del proyecto: un código bien mantenido, que sea fácil de leer y modificar, permite que los desarrolladores pierdan menos tiempo entendiendo lo que otros hicieron, lo que reduce errores y frustraciones. La segunda es económica: cuanto más se traba el desarrollo por culpa de un código mal mantenido, más se demoran las entregas, lo que retrasa los pagos y deteriora la imagen del equipo frente a los clientes.
>
> Esta investigación nos ayudó a entender la industria del software desde una perspectiva más realista. [Cada grupo puede agregar su opinión personal aquí.]"

---

## Notas Generales para la Exposición

### Tiempos totales estimados
| Persona | Slides | Tiempo estimado |
|---------|--------|-----------------|
| Persona 1 | 1–7 | ~5 min |
| Persona 2 | 8–16 | ~8 min |
| Persona 3 | 17–25 | ~7 min |
| Persona 4 | 26–34 | ~8 min |
| **Total** | **34 slides** | **~28-30 min** |

### Consejos
- **No lean textualmente las slides.** Usen el guion como referencia, pero expliquen con sus palabras.
- **Señalen las slides** cuando mencionen datos o gráficos específicos.
- **Hagan pausas** entre cambios de tema.
- **Preparen 2-3 preguntas** por si la profesora pregunta al final.
- La slide 34 (Conclusión) tiene espacio para que cada uno agregue **su propia opinión personal** al final.
- Practiquen los cambios de persona para que sea fluido.
- Si alguien se olvida algo, los demás pueden complementar.
