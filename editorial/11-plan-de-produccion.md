# 11 — Plan de producción del manuscrito

**Etapa:** 1 — Fundamentos
**Estado:** plan propuesto. La ejecución de cada etapa requiere autorización expresa.

---

## 1. Regla de gobierno del proyecto

Ninguna etapa comienza sin autorización escrita del autor. Al terminar cada etapa se
actualiza `PROJECT_STATUS.md`, se publican los cambios y el trabajo se detiene hasta
recibir la autorización siguiente. Esta regla no admite excepción por conveniencia ni por
disponibilidad de tiempo.

## 2. Etapas

| Etapa | Contenido | Entregable | Estado |
|---|---|---|---|
| 1 | Fundamentos editoriales, método, índice, estilo, investigación, controles. | Este conjunto de documentos. | **Completada** |
| 2 | Muestra editorial: introducción, capítulo 1 y primera versión del Índice de Dependencia del Fundador. | Tres archivos y una evaluación crítica de la muestra. | Pendiente de autorización |
| 3 | Producción por bloques de los capítulos 2 a 25 y la conclusión. | Manuscrito por capítulos. | No autorizada |
| 4 | Revisión integral: coherencia, repeticiones, privacidad, fuentes, vocabulario, tono. | Manuscrito consolidado y lista de problemas pendientes. | No autorizada |
| 5 | Entrega editorial. | Manuscrito, sinopsis, contraportada, índice de recursos, lista de fuentes y verificaciones pendientes. | No autorizada |

## 3. Etapa 2 — Muestra editorial

Objetivo: comprobar tono, profundidad y utilidad antes de comprometer cincuenta mil
palabras.

Alcance exacto:

1. `capitulos/00-introduccion.md`, entre 1.800 y 2.500 palabras.
2. `capitulos/parte-01/01-cuando-el-propietario-tambien-es-el-sistema.md`, entre 2.000 y
   2.400 palabras.
3. `recursos/indice-dependencia-fundador.md`, primera versión completa y utilizable.
4. Autoevaluación de la muestra contra las diecisiete preguntas de la guía de estilo.
5. Actualización de los archivos de control.
6. Commit, publicación y detención.

Criterio de aceptación de la muestra, a juicio del autor:

- El fundador se reconoce en la apertura y no se siente juzgado.
- El capítulo entrega algo aplicable esta semana.
- El Índice de Dependencia del Fundador puede completarse en menos de una hora sin ayuda.
- El tono es el descrito en la guía de estilo.
- No hay ninguna afirmación factual sin fuente.

Si la muestra no se acepta, se reescribe antes de pasar a la Etapa 3. Escribir
veinticinco capítulos con un tono que el autor no ha validado es el riesgo más caro del
proyecto.

## 4. Etapa 3 — Bloques de producción

Se produce por bloques que se corresponden con las partes del libro, porque la coherencia
interna de una parte es más fácil de sostener que la de capítulos sueltos.

| Bloque | Capítulos | Palabras estimadas | Recursos que produce |
|---|---|---|---|
| B1 | 2, 3, 4, 5 | 7.700 | Cuestionario de preparación para el retiro |
| B2 | 6, 7, 8 | 6.400 | Inventario del conocimiento crítico, mapa de decisiones, mapa de relaciones, registro de excepciones |
| B3 | 9, 10 | 4.600 | Manual de criterio del fundador, matriz de autoridad |
| B4 | 11, 12, 13 | 6.600 | Información restringida, verificación de modo sombra, alertas críticas |
| B5 | 14, 15, 16 | 6.300 | Matriz de niveles de autonomía |
| B6 | 17, 18, 19, 20, 21 | 10.400 | Informe diario, informe semanal |
| B7 | 22, 23, 24, 25 y conclusión | 9.900 | Plan de 100 días, prueba de ausencia, evaluación anual |

Después de **cada bloque**, sin excepción:

1. Actualizar `revision/control-de-capitulos.md` con palabras y estado.
2. Registrar los casos usados en `revision/control-de-casos.md`.
3. Comprobar `revision/control-de-repeticiones.md` contra los capítulos ya escritos.
4. Anotar toda afirmación sin fuente en `investigacion/afirmaciones-por-verificar.md`.
5. Ejecutar la revisión de privacidad del apartado 5 de
   `editorial/09-reglas-de-casos-ficticios.md`.
6. Actualizar `PROJECT_STATUS.md`.
7. Un commit por bloque, o varios si hay grupos lógicos.

## 5. Etapa 4 — Revisión integral

Seis pasadas, cada una con un solo objetivo. Mezclar objetivos en una sola lectura es la
forma más eficaz de no encontrar nada.

| Pasada | Busca |
|---|---|
| 1. Coherencia | Contradicciones entre capítulos; promesas hechas y no cumplidas; referencias cruzadas rotas. |
| 2. Repeticiones | Argumentos repetidos; los seis pares de riesgo de `control-de-repeticiones.md`. |
| 3. Método | Que las seis etapas estén desarrolladas de forma pareja y que la Parte III no exceda el 26 % del total. |
| 4. Privacidad | Los dieciocho puntos de las reglas de casos, aplicados capítulo a capítulo. |
| 5. Fuentes | Que no quede ningún `[POR VERIFICAR]` y que cada cifra tenga fuente consultada. |
| 6. Lengua y tono | Vocabulario fijo, anglicismos, alternancia de género, tratamiento de usted, condescendencia. |

Solo después de las seis pasadas se genera `manuscrito/manuscrito-completo.md`.

## 6. Ritmo y control de calidad

- Se prefiere un bloque bien terminado a tres bloques a medias.
- Ningún capítulo se da por bueno el mismo día en que se escribe. Se revisa en una
  segunda sesión.
- Si un capítulo no alcanza su extensión sin repetir, se acorta. La extensión es un
  presupuesto, no una obligación.
- Si durante la producción aparece la necesidad de un capítulo nuevo, se propone al autor
  y se espera decisión. No se altera la estructura aprobada en silencio.

## 7. Riesgos del proyecto

| Riesgo | Efecto | Mitigación |
|---|---|---|
| Que la Parte III crezca por atractivo del tema. | El libro se lee como un libro de tecnología y pierde su lector. | Límite del 26 % y control de palabras por parte. |
| Que el tono se deslice hacia la condescendencia sin que se note. | Pérdida del lector principal. | Prueba de lectura en voz alta de la guía de estilo, aplicada por capítulo. |
| Que se acumulen afirmaciones sin verificar hasta el final. | Etapa 4 inviable o publicación con datos frágiles. | Registro obligatorio después de cada bloque. |
| Que las herramientas se redacten como listas sin instrucciones de uso. | El libro promete práctica y entrega teoría. | Criterio de diseño de `recursos/README.md`, siete condiciones. |
| Que los casos se parezcan entre sí. | Monotonía y riesgo de identificación por acumulación. | Reparto de sectores y registro previo de cada caso. |
| Que el contenido tecnológico caduque. | El libro envejece mal. | Escribir por función y no por producto; sin marcas ni configuraciones. |
| Que la producción se detenga a mitad. | Manuscrito inservible. | Bloques cerrados y publicados; cada bloque tiene valor por sí mismo. |

## 8. Próximo paso

Solicitar al autor:

1. Decisión sobre el subtítulo (D-002).
2. Decisión sobre la promesa (D-003).
3. Decisión sobre la versión recomendada del Método LEGADO (D-004).
4. Decisión sobre las cinco propuestas del índice, P-1 a P-5 (D-005).
5. Autorización para comenzar la Etapa 2.

Las decisiones 1 a 4 pueden tomarse después de la Etapa 2 sin coste, salvo D-004 y P-1,
que conviene resolver antes porque afectan al vocabulario de la introducción y al orden
de la Parte III.
