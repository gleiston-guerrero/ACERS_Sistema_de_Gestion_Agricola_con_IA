# Aporte individual — Proyecto ACERS (SGA)

Aporte de cada integrante del equipo, con las rutas de los archivos de los que es
responsable y los IDs de commits que lo acreditan, según la Guía de desarrollo y
consolidación del PFC (Entrega 4 / 2B).

> Firmado por los integrantes activos del equipo (nombre y firma) en la sección final.
> Nota sobre el equipo: el proyecto inició con cinco integrantes. Jeanpierre Robinson
> Espinoza se alejó del equipo el 2026-09-01 sin continuar contribuyendo al
> repositorio durante varios días; Kamila Calle, Danela Arteaga, María Escudero y
> Roselyn Sánchez se repartieron entre tanto las tareas pendientes que él dejó sin
> concluir (cierre del modelo legal-first, cierre del manuscrito, registro OSF).
> Robinson manifestó posteriormente su intención de reincorporarse antes del cierre
> de esta entrega. Esta nota describe su situación de forma explícita según lo
> previsto por el gatekeeper P8 de la Guía de desarrollo (contribución individual
> verificable): su factor individual final dependerá de la contribución que quede
> efectivamente acreditada en el repositorio (commits propios, no ediciones de
> terceros) y de su participación en la defensa oral, no de esta nota.

## Jeanpierre Robinson Espinoza (`jean200525`)
- **Rol hasta el 2026-09-01:** coordinación metodológica; enfoque legal-first; borrador inicial del manuscrito.
- **Archivos en los que contribuyó:** `01_ERS/Modelo_Legal_LOPDP.md` (versión inicial), `07_Publicacion/manuscrito_final.tex` (borrador inicial), `06_Experimento/osf_registration.md` (versión inicial).
- **Commits acreditados (hasta el 2026-09-01):** `712bbdc`, `2832440`, `a62d74f`, `3e2864c`, `c7bea48`, `dc7e9f6`, `1472944`, `faf9859`, `36a7816`, `3d79ed6`, `28c81bb`, `72d4136`, `802475c`, `b69acfa`, `ffb5e03`.
- **Estado (actualizado):** Retomé el trabajo el 4 de septiembre de 2026 con 3 commits propios verificables (`f54a568`, `8422c88`, `f8ae68a`), firmados con mi correo institucional. El 16 de septiembre de 2026 corregí la mención de "registro previo" en el README.md y agregué la referencia a v2.4-suspenso entre las etiquetas históricas, y corregí la notación del p-value a p<0,001 en el manuscrito (`5881be4`), y deposité capturas propias de autoría mostrando este trabajo en tiempo real. Conforme al gatekeeper P8, mi factor individual se determina por esta contribución verificable acreditada a mi nombre en el repositorio.

## Kamila Annabella Calle Delgado (`kcalled`)
- **Rol (redistribuido el 2026-09-02, tras el retiro de Robinson):** Analista de Requerimientos — apoya y verifica el trabajo de Danela en RF/RNF/CU (verificación por persona distinta de quien produce el artefacto, gatekeeper P11); construcción conjunta del enfoque legal-first y del conjunto de comparación; evaluación independiente de cobertura legal en `10_Autoria/doble_codificacion/`; inventario de insumos; modelo legal-first (`Modelo_Legal_LOPDP.md`); cierre técnico del manuscrito y gestión del depósito FAIR.
- **Archivos responsables:** `04_Trazabilidad/Matriz_Trazabilidad_v2.xlsx`, `01_ERS/ERS_SRS_2B_v2.0.*`, `01_ERS/Modelo_Legal_LOPDP.md`, `10_Autoria/doble_codificacion/`.
- **Commits acreditados:** `76b7c8a`, `85c36e2`, `1a7a4f0`, `9aea1a7`, `16c0241`, `6b1fd9f`, `84a2129`, `0540df2`.
- **Cierre técnico completado (2026-09-04):** verificación de las 47 referencias de `07_Publicacion/referencias.bib` (todas con DOI real, cero fabricadas); depósito del paquete de replicación en Zenodo con DOI persistente `10.5281/zenodo.22307881` (commits `d306eaa`, `e4dd900`); obtención del SWHID en Software Heritage `swh:1:snp:465aaeba1b5d8a07e1c7bca122fc8277812e825a` (commit `1d89e63`, gatekeeper G3 resuelto); ejecución de F-UJI con puntaje agregado de 92.3% sobre 60% exigido (commits `fe9044a`, `f42054d`, `cb0feb7`); corrección de codificación de `CITATION.cff` (commit `975b3cb`); actualización de `CHANGELOG.md` y `07_Datos/registro_deposito.md` reflejando los depósitos completados (commits `377372d`, `4659aa1`); confirmación de uso de IA en la sección "Glosario y siglas" del ERS en `10_Autoria/declaracion_uso_ia.md` (commit `894fe53`); redacción de las 7 actas de sesión de validación (walkthrough) en `02_Evidencias/Validacion_Walkthrough/` a partir de las transcripciones originales (commit `5ef8840`).

## Danela Dayana Arteaga Álava (`darteagaa-boop`)
- **Rol (redistribuido el 2026-09-02, tras el retiro de Robinson):** Diseño y Modelado UML (`03_Modelado/Diagrams/`, `03_Modelado/Mockups/`); asume además la especificación completa que dejó Robinson sin terminar — los 39 RF, 21 RNF y 14 CU en alcance (CU-15 queda documentado como Won't have, sin desarrollar) con actores, precondiciones, flujo principal, flujos alternativos y poscondiciones — flujo principal y flujos alternativos ya agregados a las 38 fichas RF testeables en `01_ERS/ERS_SRS_2B_v2.0.md`; las 6 RNF del componente inteligente (detección/predicción, explicabilidad, equidad, supervisión humana, monitoreo, clasificación de riesgo); la matriz de correspondencia obligación legal → artículo/cláusula → requisito; y su vínculo con la matriz de trazabilidad. Elicitación de requisitos, entrevistas, codificación de evidencia y anexos éticos.
- **Archivos responsables:** `03_Modelado/Diagrams/`, `03_Modelado/Mockups/`, `02_Evidencias/Transcripciones/`, `02_Evidencias/Codificacion_Tematica/`, `08_Etica/`, `01_ERS/ERS_SRS_2B_v2.0.*` (especificación RF/RNF/CU), `10_Autoria/bitacora_sesiones.csv`.
- **Commits acreditados:** `6fd0d36` (diagramas y mockups de `03_Modelado/`), `2c97f67`, `abb49b9`.

## María del Rosario Escudero Plaza (`charito20` / `María Escudero`)
- **Rol:** ERS/SRS; protocolo de investigación; registros OSF; coordinación de evidencias.
- **Archivos responsables:** `01_ERS/ERS_SRS_2B_v2.0.*`, `06_Experimento/protocolo.*`, `06_Experimento/osf_registration.md`.
- **Commits acreditados:** `73837f8`, `c8b1312`, `607083c`, `26b3f1a`, `9e80f2a`, `b06c0e3` (y resto del lote 2026-09-01 de `charito20`).

## Roselyn Andreina Sánchez Centeno (`rsanchezc4` / `Roselyn Sánchez` / `Roselyn15`)
- **Rol:** Repositorio, infraestructura y DevOps; paquete de datos (`07_Datos/`); checksums; codificación temática y curva de saturación; etiqueta de línea base.
- **Archivos responsables:** `07_Datos/`, `10_Autoria/`, `checksums.sha256`, `02_Evidencias/fichas_tecnicas.csv`, `02_Evidencias/Codificacion_Tematica/`.
- **Commits acreditados:** `bce6d16`, `78858c9`, `a5ac2f2`, `bf3b7b9`, `ab5818d`, `5a19cd3`, `ed5db7f`, `1205191`, `9a56b7c`, `c098683`, `3f65406`, `40979d4`, `7ddcec8`, `05a2e0c`, `8340364`, `f4b78e5`, `5359ee1`, `ea0d9f4`, `dde7ba7`, `738d212`, `f14c3ab`, `2172f04`, `d81e9d4`, `7bc42b1`, `56ef342`, `50073a3`, `156b33c`.

---

## Firmas

> Cada integrante completa su fila con su firma y la fecha real en que la registra.

| Integrante | Nombre | Firma | Fecha |
|---|---|---|---|
| Jeanpierre Robinson Espinoza | Jeanpierre Robinson Espinoza | Jeanpierre Robinson Espinoza | 2026-09-03 |
| Kamila Annabella Calle Delgado | Kamila Annabella Calle Delgado | Kamila Calle | 2026-09-03 |
| Danela Dayana Arteaga Álava | Danela Dayana Arteaga Alava| Danela Arteaga | 2026-09-03 |
| María del Rosario Escudero Plaza | María del Rosario Escudero Plaza | María Escudero | 2026-09-03 |
| Roselyn Andreina Sánchez Centeno | Roselyn Andreina Sánchez Centeno  | Roselyn Sánchez | 2026-09-03|

