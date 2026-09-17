# Retrospectiva del equipo ACERS - Examen suspenso

**Fecha:** 15 al 17 de septiembre de 2026
**Integrantes:** Roselyn Sánchez, Danela Arteaga, Kamila Calle, María Escudero, Jeanpierre Robinson

## Qué hicimos entre el 13 y el 17 de septiembre de 2026

### Kamila Calle (analista de requerimientos)
- Agregó flujos alternativos y excepciones a los 14 casos de uso del ERS (CU-01 a CU-14), documentando 44 flujos con 52 menciones, 51 precondiciones y 46 poscondiciones.
- Actualizó la matriz de trazabilidad con columna ID-Flujo para trazar cada flujo alternativo.
- Redactó los 6 RNF del componente inteligente (RNF-16 a RNF-21) con referencia a caso de uso y flujo.
- Corrigió todas las menciones de "registro previo" en ERS, protocolo, OSF, CHANGELOG y manuscrito.
- Agregó la declaración de registro retrospectivo en amenazas a la validez del manuscrito (`manuscrito_final.tex`, commit `9509a1a`).
- Corrigió la afirmación "orden correcto" en `osf_registration.md` (commit `a2957cd`).
- Recompiló el PDF del ERS (pasó de 37 a 44 páginas).
- Reejecutó `python 07_Datos/scripts/run_all.py` sobre un clon limpio: las tablas y figuras regeneradas (chi2=16.056, p<0,001, diferencia de cobertura 0.692, IC95% [0.5, 0.846]) coinciden exactamente con las del ERS y el manuscrito; regeneró `checksums_datos.sha256` y `checksums.sha256` en consecuencia (commits `6428ddb`, `58e9a41`).
- Creó la etiqueta anotada `v2.3-final` (13/09) y la etiqueta anotada de cierre del examen suspenso.
- Agregó el campo `url` a `CITATION.cff` y convirtió los enlaces internos del `README.md` a URLs absolutas (16/09).
- Corrigió los dominios y completó las filas faltantes de `07_Datos/diccionario_datos.csv` (incluyendo la fila por cada columna de `Matriz_Trazabilidad_v2.xlsx` y la columna `valores_perdidos`).
- Corrigió `07_Datos/scripts/run_all.py` para que ejecute también `power_calc_mcnemar.py`.
- Corrigió las atribuciones falsas y la fecha de la entrada del examen suspenso en `CHANGELOG.md`, y agregó la entrada faltante de la etiqueta `v2.4-suspenso`.

### María Escudero (investigación experimental)
- Corrigió la afirmación "orden correcto" en `osf_registration.md` en una ronda anterior de la Entrega 4.
- Actualizó la URL canónica del repositorio a `gleiston-guerrero` en `CITATION.cff`, `README.md` y `REPOSITORIO_OFICIAL.md` (commit `7f1467d`, 15/09).
- Recompiló el PDF del manuscrito con la declaración de registro retrospectivo y el p-value corregido (commit `e6f6981`).
- Regeneró `checksums.sha256` tras actualizar `REPOSITORIO_OFICIAL.md` y corregir un problema de codificación (BOM) del archivo.
- Generó las notas de campo de las sesiones de member checking (ENTR-11, ENTR-12, ENTR-14).
- Convirtió el diccionario de datos a CSV real con separador coma (commit `d7038e4`).
- Creó la etiqueta anotada `v2.4-suspenso` (15/09), reemplazada luego por la etiqueta de cierre del examen suspenso.

### Roselyn Sánchez (gestión del repositorio)
- Sin commits registrados en el repositorio desde el 08/09. No participó en esta ronda del examen suspenso.

### Danela Arteaga (diseño y modelado UML)
- Sin cambios asignados en esta ronda (modelado UML cerrado en 100%). Sin commits registrados desde el 08/09.

### Jeanpierre Robinson (líder)
- Retomó el trabajo el 4 de septiembre de 2026 con 3 commits propios verificables (`f54a568`, `8422c88`, `f8ae68a`).
- El 16 de septiembre corrigió la mención de "registro previo" en el README.md, agregó la referencia a `v2.4-suspenso` entre las etiquetas históricas, y corrigió la notación del p-value a `p<0,001` en el manuscrito (commit `5881be4`).
- Depositó capturas propias de autoría mostrando este trabajo en tiempo real, con fecha y hora reales verificables en cada imagen.

## Qué aprendimos

1. **El preregistro OSF no cubre la totalidad del campo.** Las 6 primeras entrevistas (junio 2026) se hicieron antes de registrar en OSF (agosto 2026). Documentamos esta limitación en las desviaciones sin intentar disimularla.
2. **Los flujos alternativos son esenciales en un ERS.** Un caso de uso sin flujos alternativos está enunciado, no especificado. Esta corrección fue la de mayor peso en el examen.
3. **Los manifiestos de checksums deben regenerarse en orden:** primero el de la subcarpeta, luego el raíz. Regenerarlos al revés crea inconsistencias.
4. **El CHANGELOG es un archivo vivo y debe atribuir correctamente la autoría.** Cada versión etiquetada y cada ronda de correcciones debe registrarse con fecha, quién hizo qué realmente, y la etiqueta correspondiente; una atribución incorrecta, aunque no sea intencional, es un error que hay que corregir con la misma seriedad que un error técnico.
5. **La evidencia de autoría debe reflejar el momento real de la acción**, no una fecha reconstruida o conveniente; una captura de pantalla vale como evidencia solo si su fecha visible coincide con el nombre del archivo y con el commit que documenta.

## Firmas

Cada integrante que trabajó en esta ronda confirma este documento con un commit propio agregando su línea aquí:

- Kamila Annabella Calle Delgado — kcalled — confirmado
- María del Rosario Escudero Plaza — charito20 — confirmado
- Jeanpierre Robinson Espinoza — jean200525 — confirmado
