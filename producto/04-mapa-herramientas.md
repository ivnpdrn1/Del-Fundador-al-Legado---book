# 04 — Mapa de las dieciocho herramientas

**Etapa:** 2.5 · **Estado:** arquitectura conceptual.

**La plataforma digitaliza primero el método existente.** Solo se propone una herramienta
nueva si hay un vacío real. Este documento comprueba, una a una, que ninguna de las
dieciocho sobra y que no hace falta inventar ninguna.

**Regla de D-010, que sigue vigente y que la plataforma no puede erosionar:** las dieciocho
siguen publicándose completas y siendo utilizables en papel. El equivalente digital es una
comodidad, nunca el único acceso.

---

## Matriz

Leyenda de **Supervisión**: qué exige la herramienta de una persona. Leyenda de **Ruta**: A
con equipo, B individual, **AB** ambas sin cambios.

| # | Herramienta | Etapa | Problema que resuelve | Input | Procesamiento | Output / activo | Módulo | IA posible | Supervisión | Riesgo | Ruta |
|---|---|---|---|---|---|---|---|---|---|---|---|
| **1** | Índice de Dependencia de la Persona Clave | L | La dependencia se siente pero no se mide | 24 respuestas 0-3 | Suma por dimensión y total | **Índice fechado + perfil** | **1** | Ninguna. Es aritmética | Ninguna necesaria | Falsa precisión si se presenta como validado | **AB** |
| **2** | Cuestionario de preparación para el retiro | L | Se confunde la disposición personal con la preparación del negocio | Respuestas + posición deseada en el continuo | Contraste deseo/realidad | **Objetivo y horizonte** | **0** | Ninguna | Ninguna | Que el producto empuje hacia el retiro total | AB |
| **3** | Inventario del conocimiento crítico | E | No se sabe qué documentar primero | Lista con impacto si se pierde | Priorización por impacto | **Inventario priorizado** | **2** | Proponer entradas desde el cap. 2; detectar vacíos por componente | Confirmar cada entrada propuesta | Documentar lo irrelevante | AB |
| **4** | Mapa de decisiones | E | No se sabe con qué criterio se decide | Decisiones, criterio, información, plazo | Estructuración y enlace a criterio | **Grafo de decisiones** | **4** | Extraer decisiones de texto libre | Confirmar cada decisión | Que el grafo se vuelva inmanejable | **AB**, con la columna «con qué criterio» en lugar de «quién decide» |
| **5** | Mapa de relaciones críticas | E | Los vínculos externos son personales, no del negocio | Relaciones, historia, segundo contacto | Identificar vínculos sin respaldo | **Grafo de relaciones** | **6** | Detectar relaciones citadas en otros elementos | Confirmar | **Datos de terceros.** Sensibilidad alta | **AB.** Más crítica en B |
| **6** | Registro de excepciones | E | Lo excepcional no está escrito y no es transferible | Excepción, motivo, vigencia, revisor | Control de vigencia | **Registro con caducidades** | **5** | Detectar excepciones implícitas; **señalar contradicciones** | Confirmar y fijar vigencia | Excepciones vencidas sin revisar | AB |
| **7** | Plantilla del Manual de criterio | E | El porqué no existe fuera de una cabeza | Entrevista: decisión, motivo, señales, excepción, evidencia | Estructuración conversacional | **Manual de criterio** | **4** | **Entrevista estructurada. La función más diferencial del producto** | Alta: el usuario valida cada entrada | **Que la IA invente criterio.** El mayor riesgo del producto | AB |
| **8** | Matriz de autoridad y aprobaciones | G | Delegar sin límites escritos es un acto de fe | Límites, funciones o reglas propias | Detección de decisiones sin límite | **Matriz con evidencia** | **7** | Detectar decisiones recurrentes sin límite | Alta. **Revisión profesional recomendada** | Fingir separación de funciones donde no existe | **Modos A y B** (D-037) |
| **9** | Lista de información restringida | G/A | Se entrega a una herramienta lo que no debía salir | Clasificación de sensibilidad | Etiquetado y bloqueo | **Repositorio clasificado** | **8** | Proponer clasificación | **Confirmación humana obligatoria** | Clasificar de menos | AB |
| **10** | Verificación del modo sombra | A | Se confía en un sistema sin evidencia | Observaciones del sistema y decisiones humanas | Comparación | **Registro comparado** | **12** | **Observar y registrar sin decidir** | Revisión del registro | Saltarse el modo sombra | AB |
| **11** | Modelo de alertas críticas | A | Lo importante no llega, o llega demasiado | Umbrales y destinatarios | Disparo y escalado | **Reglas de alerta** | **12** | Detectar desviaciones | Definir umbrales | **Exceso de alertas**: si se ignoran, el nivel ha fracasado | AB |
| **12** | Matriz de niveles de autonomía | A | No está claro qué se le deja hacer a la tecnología | Nivel por tipo de tarea | Aplicación de permisos | **Configuración + parada** | **12** | Ninguna: **es la herramienta que gobierna a la IA** | Máxima | Subir de nivel sin evidencia del anterior | AB |
| **13** | Modelo de informe diario | O | Quien no está en la operación no sabe cómo va | Indicadores elegidos | Composición | **Informe diario** | **14** | Redactar el resumen | Revisión | Tablero con demasiadas cifras | AB, más breve en B |
| **14** | Modelo de informe semanal | O | Falta la tendencia y las excepciones | Datos de la semana | Composición y comparación | **Informe semanal** | **14** | Redactar y señalar desviaciones | Revisión | Igual que la anterior | AB |
| **15** | Prueba de ausencia de 24 horas | D | La preparación no se ha probado | Registro durante la ausencia | Recogida de fallos | **Informe + tareas** | **10** | Registrar y **convertir cada fallo en tarea** | Un tercero observa | Prepararla tanto que deje de probar nada | AB |
| **16** | Prueba de ausencia de 7 días | D | Expone la dependencia semanal y de cierre | Igual | Igual | **Informe + tareas** | **10** | Igual | Igual | Igual. **Más dura en la ruta B** | AB |
| **17** | Plan de transición de 100 días | D | La transición no tiene secuencia ni fechas | Hitos, responsables, fechas | Seguimiento | **Plan con hitos** | **9** | Recordatorios; señalar hitos vencidos | Del propietario | Plan que nadie revisa | AB |
| **18** | Evaluación anual de continuidad | O | El sistema se degrada si nadie lo mantiene | Estado de todos los activos | Comparación interanual | **Informe de Legado Inteligente** | **14** | Preparar el informe desde las evidencias | Revisor externo anual | **Convertirlo en una puntuación comercial** | AB |

## Conclusiones del mapeo

### 1. Ninguna herramienta sobra, y ninguna hace falta

Las dieciocho tienen un módulo asignado y ninguna queda huérfana. **No se propone ninguna
herramienta nueva.** El vacío que podría haber justificado una —los límites propios de la
ruta B— ya lo resuelve el modo B de la herramienta 8 (D-037), sin romper la constante de
dieciocho.

### 2. Cobertura por módulo

| Módulo | Herramientas |
|---|---|
| 0 Perfil y horizonte | 2 |
| 1 Diagnóstico | 1 |
| 2 Mapa del ADN | 3 |
| 4 Criterio y decisiones | 4, 7 |
| 5 Procesos y excepciones | 6 |
| 6 Relaciones | 5 |
| 7 Autoridad y controles | 8 |
| 8 Repositorio | 9 |
| 9 Transferencia | 17 |
| 10 Prueba de ausencia | 15, 16 |
| 12 IA supervisada | 10, 11, 12 |
| 14 Legado Inteligente | 13, 14, 18 |

**Los módulos 3 y 11 no tienen herramienta propia**, y es correcto:

- El **3, captura del conocimiento**, es el mecanismo de entrada que alimenta las
  herramientas 3, 4, 5 y 7. No es una herramienta: es cómo se rellenan las demás.
- El **11, Asistente**, no produce un activo del libro: consulta los que ya existen. Un
  asistente no es una herramienta del método; es una forma de usar el método ya aplicado.

El **módulo 13, Gemelo de IA**, tampoco tiene herramienta, y también es correcto: el libro
no entrega ninguna plantilla para construir un gemelo, y no debe hacerlo.

### 3. Dónde está el riesgo concentrado

| Riesgo | Herramientas | Mitigación |
|---|---|---|
| **Que la IA invente criterio** | 7, y por extensión 4 | Regla del §9 de la arquitectura funcional: si no está documentado, se dice. Toda entrada la valida el usuario |
| **Datos de terceros** | 5, 9 | Clasificación de sensibilidad obligatoria y confirmación humana |
| **Falsa precisión** | 1, 18 | Ya normado: el Índice declara no estar validado; el informe no es puntuación |
| **Fingir estructura que no existe** | 8 | Modo B explícito: la separación de funciones no se finge |
| **Exceso de alertas** | 11 | El propio libro lo advierte: si se ignoran, el nivel ha fracasado |

### 4. Las dos herramientas más valiosas para el producto

**La 1 y la 7.**

La **1** porque es la puerta de entrada: entrega valor en veinte minutos, sin cuenta, y
produce el dato que ordena todo lo demás.

La **7** porque es donde el producto puede hacer algo que el papel no hace: **entrevistar**.
Una plantilla en blanco del Manual de criterio es intimidante; siete preguntas encadenadas
producen la misma entrada sin que el usuario tenga que saber documentar. **Ahí está el
diferencial del producto, y por eso ahí está también su mayor riesgo.**
