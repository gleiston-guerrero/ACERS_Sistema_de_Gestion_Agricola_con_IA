# Changelog
Todos los cambios notables de este proyecto se documentan en este archivo.
El formato se basa en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/),
y este proyecto sigue el versionado semántico donde es aplicable.

## [Examen suspenso] - 2026-09-17
Correcciones exigidas por la guía de cierre del examen suspenso (15/09/2026).

### Añadido
- Flujos alternativos y excepciones a los 14 casos de uso del ERS: 44 flujos, 52 menciones, 51 precondiciones, 46 poscondiciones (Kamila Calle).
- Columna ID-Flujo en la matriz de trazabilidad para trazar cada flujo alternativo (Kamila Calle).
- 6 RNF del componente inteligente (RNF-16 a RNF-21) con referencia a caso de uso y flujo (Kamila Calle).
- Declaración de registro retrospectivo en amenazas a la validez del manuscrito (Kamila Calle).
- Retrospectiva del equipo (`10_Autoria/retrospectiva_equipo.md`) con qué hicimos, quién hizo qué y qué aprendimos (creada por María Escudero, actualizada por Kamila Calle).
- Diccionario de datos convertido a CSV real con separador coma y 22 filas (María Escudero).
- Manuscrito recompilado con la declaración de registro retrospectivo (13 páginas, 408745 bytes) (María Escudero).
- Etiqueta anotada de cierre `v2.4-cierre` creada sobre el commit final del examen suspenso, reemplazando a `v2.4-suspenso` como versión vigente para evaluación (Kamila Calle).
- Etiqueta anotada de cierre `v2.5-cierre` creada tras una segunda ronda de correcciones (atribuciones del CHANGELOG y la retrospectiva, paquete de datos, capturas de autoría), reemplazando a `v2.4-cierre` como versión vigente para evaluación (Kamila Calle).
### Corregido
- Todas las menciones de "registro previo" eliminadas del ERS, protocolo, OSF y CHANGELOG (Kamila Calle).
- Recompilados `osf_registration.pdf` y `protocolo.pdf`, que todavía contenían "registro previo" aunque su `.tex` fuente ya no lo tenía (Kamila Calle).
- Corregidos 60 hashes de commit incorrectos en `10_Autoria/aporte_individual.md` y eliminada una referencia a un documento inexistente (Kamila Calle).
- Corregido error de tipeo en el nombre de Kamila Calle Delgado en la tabla de equipo del README.md (Kamila Calle).
- `checksums.sha256` regenerado tras cambios del ERS (Kamila Calle).

## [v2.4-suspenso] - 2026-09-15
Etiqueta de línea base intermedia: `v2.4-suspenso` (María Escudero), reemplazada por `v2.4-cierre` al cerrar el examen suspenso.

## [v2.3-final] - 2026-09-13
Etiqueta de línea base final: `v2.3-final`

### Añadido
- Flujos alternativos incrustados en los 14 casos de uso del ERS (A1).
- Declaración de uso de IA ampliada a las 11 carpetas del proyecto (P9).

### Corregido
- `REPOSITORIO_OFICIAL.md` actualizado con la versión entregada correcta.
- `checksums.sha256` regenerado y verificado (444 archivos, 100% válido).

## [Entrega Final - 2B] - 2026-09-05
Etiqueta de línea base: `v2.0-final` (commit `eb506d4`)

### Añadido
- Informe final del proyecto (`07_Publicacion/`), documento único generado desde LaTeX que integra la especificación auditada, el estudio empírico ejecutado y el análisis de resultados, con carátula obligatoria conforme a la sección 12 de la guía.
- Ejecución completa del componente empírico: recolección de datos primarios según el protocolo registrado, análisis reproducible mediante scripts versionados (`06_Experimento/scripts_analisis/`), magnitud del efecto con intervalo de confianza, acuerdo entre evaluadores y lista de verificación de reporte cumplimentada.
- Cierre de la matriz de trazabilidad extremo a extremo (`04_Trazabilidad/Matriz_Trazabilidad_v2.xlsx`), con tabla de huérfanos y cadenas rotas resuelta y porcentaje de sincronización con el tablero calculado.
- Fichas de requisitos de los componentes de IA: requisitos funcionales, de rendimiento, de equidad y de explicabilidad con umbral, unidad y método de comprobación; clasificación de riesgo y base legal.
- Adenda ética de la ronda de campo correspondiente a esta entrega (`08_Etica/`), protocolo de disociación de datos personales y política de conservación y supresión.
- Declaraciones obligatorias completas (`07_Publicacion/declaraciones/`): contribución individual con roles, conflicto de interés, financiamiento, cumplimiento ético, consentimiento para difusión, disponibilidad de datos y de código, uso de inteligencia artificial y originalidad.
- Informe de control de similitud y revisión cruzada entre equipos con carta de respuesta fila por fila (`07_Publicacion/revision_cruzada/`).
- Presentación de defensa individual y banco de preguntas con respuestas ancladas a artefactos (`09_Defensa/`).
- Etiqueta de línea base final anotada, alcanzable desde la rama por defecto y publicada en el repositorio remoto.
- Depósito del paquete de replicación en Zenodo con DOI persistente `10.5281/zenodo.22307881`, registro del protocolo en OSF (`https://osf.io/7cvhy`), citado en `CITATION.cff` y en el README, conforme a la compuerta I5 de la guía.

### Corregido
- Cita cruzada corregida en la sección 6 (`sec6`) del informe final.

## [Entrega 3 - 2A] - 2026-07-29
### Añadido
- ERS/SRS completo v1.0 con requisitos funcionales, no funcionales, historias de usuario en formato Connextra y criterios de aceptación en Gherkin.
- Modelado UML completo: diagrama de casos de uso general, especificación textual de casos de uso, diagrama de clases refinado, diagramas de secuencia, actividad, estados, componentes y despliegue.
- Matriz de trazabilidad extendida (Ley → Objetivo → Interesado → EV → RF/RNF/RD → CU → HU → CA → Componente → Mockup).
- Priorización combinada MoSCoW + Kano + WSJF.
- Protocolo experimental y registro en OSF.
- Segunda ronda de trabajo de campo: nuevos consentimientos, entrevistas en video/audio, cuestionario ampliado.
- LICENSE, CITATION.cff, checksums.sha256, .gitignore.

## [Entrega 2 - 1B] - 2026-07-01
### Añadido
- ERS/SRS parcial: introducción, descripción general, requisitos preliminares.
- Primera ronda de trabajo de campo: entrevistas con administrador y trabajador de campo de Agrícola Moreira.
- Wireframes HTML del sistema (dashboard, tareas de personal, registro de cosechas, control de plagas, inventario de insumos).
- Documentación UML inicial (10 casos de uso, diagrama de casos de uso).

---
