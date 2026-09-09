# 02 — Mapa libro → plataforma

**Etapa:** 2.5 · **Estado:** arquitectura conceptual.

Matriz de las **veintisiete piezas del manuscrito**: los 25 capítulos numerados más la
introducción y la conclusión. Terminología fijada en `editorial/03-indice-maestro.md`
apartado 0.

**No es un mapa de pantallas.** Un capítulo no equivale a una pantalla: algunos son
conceptuales o emocionales y no generan nada digital, y otros alimentan varios módulos a la
vez.

**La aplicación sigue la lógica del método, no el índice del libro.** Este mapa sirve para
saber qué entiende el usuario en cada punto, no para copiar la tabla de contenidos.

**Aviso de lectura, importante.** La columna «Función de la plataforma» describe **lo que el
producto podría hacer** en el punto del método al que corresponde ese capítulo. **No
describe lo que el libro menciona.** El producto puede tener una función asociada a un
capítulo en el que el manuscrito no dice ni una palabra sobre la plataforma. Las menciones
permitidas en el manuscrito, y solo ellas, están en
`editorial/16-libro-metodo-y-plataforma.md` §5, y se resumen al final de este documento.

Leyenda de **Madurez**: la etapa del Método LEGADO en la que el usuario se encuentra
conceptualmente. Ver `03-arquitectura-funcional.md` §7: **no existe una escala de madurez
propia del producto**; la progresión es el método.

---

## Parte I — El negocio que depende de una persona

*Función: reconocimiento. **Nivel 1 de presencia editorial: no se menciona ningún
producto.***

| Cap. | Qué comprende y descubre el lector | Input que podría generar | Herramienta | Activo digital | Función de la plataforma | Función de IA | Madurez |
|---|---|---|---|---|---|---|---|
| Intro | Que su negocio depende de él; que eso tiene nombre —ADN Empresarial— y que puede transferirse | Ninguno | — | — | Ninguna | Ninguna | Antes de L |
| **1** | Cuánto depende el negocio de él, con un número y un perfil por dimensiones | **24 respuestas + 8 subtotales + total, fechados** | 1. Índice de Dependencia | **Índice fechado + perfil por dimensiones** | **Diagnóstico. Es la puerta de entrada del producto.** Cálculo, almacenamiento y comparación a seis meses | Ninguna en esta etapa. El cálculo es aritmético y no necesita IA | **L** |
| 2 | Que hay conocimiento que nunca se consideró conocimiento: criterio, historia, excepciones, señales | Lista libre de «cosas que solo yo sé» | Ejercicio de reconocimiento | Semilla del mapa de ADN | Recoger la lista y clasificarla por los diez componentes | **Clasificar** cada entrada en su componente y detectar cuáles faltan | L→E |
| 3 | Que la autonomía que ve puede depender de que él esté disponible | Tres respuestas, propias o del equipo | Prueba de las tres preguntas | Contraste percepción/realidad | Recoger respuestas y compararlas con las del propietario; en modo B, comparar lo que cree saber explicar con lo que consigue escribir | Comparar y señalar divergencias | L |
| 4 | Qué cambia porque no está disponible, y qué de eso es pausa y qué es pérdida | Cuadro de una semana por estados, con cifra solo donde exista | Cálculo del impacto de una semana de ausencia | **Mapa de riesgos de ausencia** | Registrar y priorizar por impacto | Sugerir puntos no considerados a partir del ADN ya capturado | L |
| 5 | **Elección de participación y objetivo del tiempo recuperado**; el Mapa de Participación. **Actualizado el 2026-09-09 (D-075/D-076):** decía «que retirarse no es abandonar», que era la objeción y no la tesis | Posición actual y posición deseada en el mapa + horizonte | 2. Cuestionario de preparación para el retiro | **Objetivo y horizonte del usuario** | **Módulo 0**: fijar el destino, que condiciona todo lo demás | Ninguna | L |

**Observación.** El capítulo 1 es el único de esta parte que produce un activo estructurado,
y es el que justifica que el diagnóstico sea la puerta de entrada del producto. Los
capítulos 2 a 5 generan material valioso pero todavía informe: la plataforma lo recoge, no
lo exige.

## Parte II — Convertir experiencia en memoria transferible

*Función: es donde se construye el ADN. **Nivel 2: se alude a que esto necesita un sitio
(cap. 6) y se nombran opciones digitales genéricas (final del cap. 9).***

| Cap. | Qué comprende y descubre el lector | Input que podría generar | Herramienta | Activo digital | Función de la plataforma | Función de IA | Madurez |
|---|---|---|---|---|---|---|---|
| **6** | Que el ADN puede identificarse y priorizarse por impacto | Inventario priorizado de conocimiento crítico | 3. Inventario del conocimiento crítico | **Inventario con impacto, responsable y estado** | **Primera alusión indirecta**: esto necesita un sitio, una fecha y un responsable | Proponer entradas a partir del capítulo 2; detectar vacíos | **E** |
| 7 | Que hay tres mapas distintos: procesos, decisiones y relaciones | Procesos reales, decisiones con su criterio, relaciones críticas | 4. Mapa de decisiones · 5. Mapa de relaciones | **Grafo de decisiones y relaciones** | Captura por entrevista; conexiones entre elementos | **Entrevista estructurada.** Extraer entidades y relaciones de texto libre y de documentos | E |
| 8 | Que la excepción no documentada es la mayor fuente de dependencia | Excepciones con motivo, vigencia y revisor | 6. Registro de excepciones | **Registro con vigencia y alertas de caducidad** | Recordar vencimientos; escalar excepciones vencidas | Detectar excepciones implícitas en lo ya capturado y **señalar contradicciones** | E |
| **9** | Que el porqué es lo valioso, y que documentarlo es un trabajo continuo | Entradas de criterio: decisión, motivo, señales, excepciones, evidencia | 7. Plantilla del Manual de criterio | **Manual de criterio estructurado** | **Aquí llega el punto de dolor real.** Al final del capítulo: primera mención de opciones digitales, sin plataforma concreta | **Entrevista de criterio.** Es la función más diferencial del producto | E |
| 10 | Que hay que fijar por escrito quién decide qué y hasta dónde | Límites por función, o límites propios en la ruta B | 8. Matriz de autoridad, modos A y B | **Matriz de autoridad con evidencia de aplicación** | Registro de aprobaciones; señalar decisiones sin límite escrito | Detectar decisiones recurrentes sin límite definido | **G** |

**Observación decisiva.** Al terminar el capítulo 9 el lector tiene **cinco documentos
vivos**, cada uno con fecha, responsable y revisión pendiente. Ese es el momento en que
organizarlo a mano empieza a doler, y por eso la mención de herramientas digitales va aquí
y no antes.

## Parte III — Construir una mano derecha digital

*Función: ordenar y luego asistir. **Nivel 3 en el cap. 11; nivel 4 desde el 12.***

| Cap. | Qué comprende y descubre el lector | Input que podría generar | Herramienta | Activo digital | Función de la plataforma | Función de IA | Madurez |
|---|---|---|---|---|---|---|---|
| **11** | Que antes de automatizar hay que ordenar: fuente única, dato fiable, información clasificada | Clasificación de sensibilidad; fuentes únicas | 9. Lista de información restringida | **Repositorio del ADN, con clasificación de sensibilidad** | **PRESENTACIÓN EXPLÍCITA DE LA PLATAFORMA.** Máximo 450 palabras, al final del capítulo | Clasificar sensibilidad **con confirmación humana obligatoria** | E→G |
| 12 | Qué es y qué no es la inteligencia artificial; que el nivel es un permiso, no una capacidad | Nivel de autonomía deseado por tipo de tarea | Cuadro de lo que puede y no puede | Perfil de permisos | Configurar permisos por tipo de tarea | Ninguna todavía: aquí se **explica** la IA, no se usa | **A** |
| 13 | Modo sombra y primeras alertas | Registro comparado sombra; umbrales de alerta | 10. Verificación del modo sombra · 11. Modelo de alertas | **Registro comparado + reglas de alerta** | Ejecutar el modo sombra y guardar la comparación | **Observar y registrar sin decidir.** El nivel 2 es aquí un modo del producto | A |
| **14** | Que una recomendación sin evidencia no se acepta; el sesgo de automatización | Recomendaciones aceptadas y rechazadas | Formato de recomendación explicada | Historial de recomendaciones con su evidencia | **Se nombra el Asistente del ADN Empresarial.** Toda respuesta muestra su fuente | **Asistente**: localizar, resumir, comparar, recuperar antecedentes, preparar decisiones | A |
| **15** | Autonomía limitada, aprobación humana y techo del nivel 6 | Matriz de niveles por tarea; procedimiento de detención | 12. Matriz de niveles de autonomía | Configuración de autonomía + botón de parada | Ejecutar dentro de límites escritos, con registro | **Primer momento admisible para el Gemelo de IA.** Nunca antes (V-25b) | A→D |
| 16 | Quién ve qué, qué queda registrado, qué pasa si falla | Permisos, registros, plan de contingencia | Lista de comprobación de seguridad | Configuración de gobierno y auditoría | Permisos, trazas, exportación, eliminación | Ninguna. Es capa de gobierno, no de IA | A |

## Parte IV — Transferir el control sin perderlo

*Función: traspaso. **Cero invitaciones y una sola mención funcional, en el capítulo 19.***

| Cap. | Qué comprende y descubre el lector | Input que podría generar | Herramienta | Activo digital | Función de la plataforma | Función de IA | Madurez |
|---|---|---|---|---|---|---|---|
| 17 | Cómo se comunica una transición sin que se lea como abandono | Guion adaptado; lista de personas afectadas | Guion de conversación | Plan de comunicación | Recoger el plan. **Sin mención de producto** | Ninguna | **D** |
| 18 | Delegar por bloques, revisar después y no antes | Bloques, receptores, límites, evidencia | Plan de delegación por bloques | **Plan de transferencia con evidencia** | Seguimiento de cada bloque delegado y de su resultado | Señalar bloques delegados sin evidencia registrada | D |
| **19** | Qué mirar cada día, cada semana, cada mes | Indicadores elegidos y umbrales | 13. Informe diario · 14. Informe semanal | **Tablero del propietario** | **Mención funcional**: el tablero puede vivir aquí. Una frase | Preparar los informes y señalar desviaciones | **O** |
| 20 | Cuándo intervenir y cuándo callarse; el retroceso controlado | Reglas de intervención | Reglas de intervención | Reglas de escalado | Aplicar reglas de escalado y registrar intervenciones | Escalar según reglas, nunca decidir | O |
| 21 | Que puede no haber sucesor, y que hay salidas | Árbol de opciones recorrido | Árbol de opciones de continuidad | Escenario de continuidad elegido | Recoger el escenario. **Sin mención de producto** | Ninguna | D |

## Parte V — Del fundador al legado

| Cap. | Qué comprende y descubre el lector | Input que podría generar | Herramienta | Activo digital | Función de la plataforma | Función de IA | Madurez |
|---|---|---|---|---|---|---|---|
| 22 | Qué hace y qué ya no hace; su propósito después de la operación | Descripción escrita del nuevo papel | Descripción del nuevo papel | Papel definido | Recoger y publicar el papel a quien corresponda | Ninguna | O |
| 23 | Secuencia concreta con responsables y fechas | Plan a cien días | 17. Plan de transición de 100 días | Plan con hitos y responsables | Seguimiento de hitos | Recordatorios; señalar hitos vencidos | D |
| **24** | El examen: 24 horas y 7 días | **Registro de la prueba: preguntas, bloqueos, excepciones, procesos detenidos** | 15-16. Prueba de ausencia | **Informe de la prueba + tareas derivadas** | **Mención funcional.** Prueba acumulativa; cada fallo se convierte en tarea | Registrar durante la ausencia y **convertir cada fallo en una tarea de reducción de dependencia** | D→O |
| 25 | Qué significa que un negocio pueda continuar | Evaluación anual | 18. Evaluación anual de continuidad | **Informe de Legado Inteligente** | Comparación interanual con evidencias | Preparar el informe a partir de las evidencias acumuladas | **O** |
| Concl. | Cierre; las cuatro preguntas | Ninguno | — | — | Ninguna, o una línea en el anexo | Ninguna | O |


## Arquitectura futura de los capítulos 22, 24, 25 y la conclusión (2026-09-09, D-075)

**Solo arquitectura. Ninguno está escrito y esta etapa no los escribe.**

| Pieza | Qué cambia en su correspondencia con el producto |
|---|---|
| **22 — Su nuevo papel** | El módulo 0 recoge el objetivo del usuario; **el 22 lo revisa al final del recorrido**, porque el objetivo pudo cambiar. El nuevo papel puede ser supervisor, estratégico, asesor, o **fundador de otra cosa**. El producto no puede ofrecer una lista cerrada de papeles ni marcar uno como completo. |
| **24 — La prueba de ausencia** | **La mecánica no cambia.** Lo que cambia es su lectura: el módulo 10 debe permitir declarar que la ausencia simulada corresponde a **atención reasignada**, no solo a vacaciones o retiro. El informe es el mismo. |
| **25 — El negocio que puede continuar** | El módulo 14 mide continuidad del negocio, **no éxito de lo siguiente**. Si el usuario tiene un segundo ámbito, el tablero **no los suma ni los compara**. |
| **Conclusión — Usted elige cómo seguir** | Cierre del recorrido, no del producto. **No hay pantalla de «has terminado»** y no la habrá. |


## Resumen de la presencia digital en el manuscrito

| Momento | Capítulo | Qué |
|---|---|---|
| Primera invitación | Pie de la herramienta 1, en el anexo | Versión digital gratuita del Índice |
| Primera alusión de organización (**categoría A**) | 6 | Una frase: esto necesita sitio, fecha y responsable. **No es una mención de la plataforma** |
| Primera alusión a herramientas o sistemas (**categoría B**) | Final del 9 | Un párrafo neutro, genérico y en plural. **No es una mención de la plataforma** |
| **Presentación explícita (categoría D)** | **11** | Sección de 450 palabras, al final. **Primera vez que el libro identifica la plataforma** |
| Funciones de IA | 12, 13, 14 | Una frase por capítulo |
| Asistente del ADN Empresarial | 14 | Se nombra por primera vez |
| **Gemelo de IA** | **15 o posterior** | Nunca antes (V-25b) |
| Menciones funcionales | 19, 24 | Una frase cada una |
| Recurso final | Anexo de recursos | Enlace y explicación |

**Capítulos sin ninguna mención identificable de nuestra plataforma** —cero de las
categorías C, D y E de `editorial/16-libro-metodo-y-plataforma.md` §5—: **1 a 10, 16, 17,
18, 20, 21, 22, 23 y 25.** La conclusión queda a decidir en la Etapa 3 (V-30b).

**Esto no impide que esos capítulos hablen de organizar el material.** La alusión del
capítulo 6 es **categoría A**, lenguaje genérico de organización, y el párrafo del capítulo
9 es **categoría B**, opciones genéricas en plural. Ninguna de las dos es una mención de la
plataforma, y por eso no son excepciones a la regla: están fuera de ella.

Que un capítulo aparezca en esa lista **tampoco impide que el producto tenga funciones
asociadas** a lo que ese capítulo enseña: impide que el libro hable de ellas. Es la
distinción del aviso de lectura del principio, y es la que mantiene el manuscrito limpio.
