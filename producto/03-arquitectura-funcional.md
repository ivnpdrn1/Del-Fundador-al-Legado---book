# 03 — Arquitectura funcional

**Etapa:** 2.5 · **Estado:** arquitectura conceptual. **Sin stack, sin proveedores, sin base
de datos, sin código.**

---

## 1. Onboarding: empezar por el problema humano

**Prohibido empezar con «cree su clon de IA» o «entrene una inteligencia artificial».** Sería
la traición exacta al principio del libro y ahuyentaría al lector principal.

Secuencia propuesta, en el registro del libro:

| Pantalla | Qué dice | Por qué |
|---|---|---|
| **1** | *Si mañana usted no estuviera disponible, ¿qué se detendría?* | Es la pregunta que abre el libro. Reconocimiento antes que producto. |
| **2** | *Vamos a ponerle un número. Veinte minutos, veinticuatro preguntas.* | Convierte la inquietud en una acción concreta y acotada. Fija expectativa de tiempo. |
| **3** | *[Resultado]* Aquí está su punto de partida, y aquí las dos dimensiones donde se concentra. | **Entrega valor antes de pedir nada.** |
| **4** | *Lo que acaba de medir tiene un nombre: el ADN de su negocio. Vamos a construirlo por partes, empezando por donde más dolería perderlo.* | Introduce el concepto **después** de que el usuario haya visto su propio dato. |

**Reglas del onboarding:**

1. **El resultado del diagnóstico se entrega completo antes de pedir una cuenta.**
2. Se pregunta al principio si trabaja con equipo o solo: **determina la ruta y no se
   vuelve a preguntar**.
3. No se menciona inteligencia artificial en ninguna de las cuatro pantallas.
4. La palabra «empresarial» no aparece en la interfaz de entrada (§6).

## 2. Módulos

Contrastados contra el orden del Método LEGADO. **El orden del método manda** (D-059).

| Módulo | Nombre funcional | Etapa LEGADO | Capítulos | Produce |
|---|---|---|---|---|
| **0** | Perfil, objetivo y horizonte | Antesala | 5 | Posición deseada en el Mapa de Participación |
| **1** | Diagnóstico de dependencia | **L** | 1 | Índice fechado y perfil por dimensiones |
| **2** | Mapa del ADN Empresarial | L→E | 2, 6 | Inventario priorizado por impacto |
| **3** | Captura del conocimiento | **E** | 6, 7 | Entradas de conocimiento con evidencia |
| **4** | Experiencia, criterio y decisiones | **E** | 9 | Manual de criterio estructurado |
| **5** | Procesos y excepciones | **E** | 7, 8 | Procesos reales y registro de excepciones |
| **6** | Relaciones y memoria histórica | **E** | 7 | Mapa de relaciones con segundo contacto |
| **7** | Autoridad, controles y supervisión | **G** | 10, 16 | Matriz de autoridad y configuración de gobierno |
| **8** | Repositorio del ADN Empresarial | G→A | 11 | Repositorio clasificado por sensibilidad |
| **9** | Transferencia | **D** | 17, 18, 23 | Plan de transferencia con evidencia |
| **10** | Prueba de ausencia | **D** | 24 | Informe de prueba y tareas derivadas |
| **11** | Asistente del ADN Empresarial | **A** | 14 | Respuestas con fuente y vacíos detectados |
| **12** | IA supervisada | **A** | 13, 15 | Modo sombra, alertas, ejecución limitada |
| **13** | Gemelo de IA *(opcional)* | A→D | **15 o posterior** | — |
| **14** | Legado Inteligente | **O** | 19, 20, 25 | Tablero e informe de continuidad |

**Comprobación contra el método.** El orden de los módulos reproduce L → E → G → A → D → O
con una sola inversión aparente: el módulo 8, repositorio, se sitúa entre G y A porque
clasificar la información por sensibilidad es requisito de G y condición de A. **Coincide con
D-017**, que puso «ordenar antes de automatizar» al principio de la Parte III. No hay
conflicto.

**Módulos 13 y 14 no son consecutivos en el tiempo.** Se puede llegar al 14 sin pasar nunca
por el 13.

## 3. Capas conceptuales

Sin proveedores, sin tecnologías, sin decisiones de implementación.

| Capa | Responsabilidad | Nota |
|---|---|---|
| **Experiencia guiada** | La conversación, los ejercicios, el progreso. Distinta para ruta A y ruta B. | Es lo que el usuario ve. |
| **Motor de flujo LEGADO** | La secuencia metodológica: qué toca ahora, qué requisitos faltan, qué desbloquea qué. | **Aquí vive el método.** Si el método cambia, cambia esta capa y no las demás. |
| **Modelo del ADN Empresarial** | Representación estructurada de los diez componentes. Ver §4. | El corazón del producto. |
| **Almacén de evidencias** | Documentos y fuentes de las que procede cada elemento. | Separado del modelo: el modelo apunta a la evidencia, no la contiene. |
| **Grafo de relaciones, procesos y decisiones** | Las conexiones: qué decisión depende de qué relación, qué proceso tiene qué excepción. | Es lo que permite responder «si falta esta persona, ¿qué se cae?». |
| **Asistencia de IA** | Extracción, clasificación, consulta, asistencia. | **Solo lee del modelo y de las evidencias. Nunca escribe sin confirmación humana.** |
| **Gobierno** | Permisos, supervisión, trazabilidad, marca de «requiere intervención humana». | Atraviesa todas las capas. |
| **Analítica** | Dependencia, progreso y continuidad. | Alimenta el tablero y el informe de Legado Inteligente. |

**Regla de separación:** la capa de IA es **sustituible** y ninguna otra capa puede depender
de ella para funcionar. Si mañana se retira, el producto sigue siendo útil: pierde
asistencia, no pierde el ADN. Es la traducción técnica del principio de que el libro
funciona sin la plataforma.

**No decidido y expresamente fuera de alcance:** proveedor de nube, base de datos,
framework, proveedor de modelos, integraciones.

## 4. Modelo conceptual del ADN Empresarial

Sobre los diez componentes de D-043. **No es un diseño de base de datos.**

Cada elemento capturado, sea del componente que sea, lleva estos metadatos:

| Metadato | Para qué sirve | Por qué importa aquí |
|---|---|---|
| **Componente** | Cuál de los diez | Permite ver qué partes del ADN están vacías |
| **Fuente** | De dónde salió: entrevista, documento, importación | Base de la trazabilidad |
| **Propietario** | De quién es ese conocimiento | En la ruta B casi siempre el usuario; en la A, no |
| **Responsable** | Quién lo mantiene vivo | Sin responsable, un documento muere |
| **Fecha** y **última revisión** | Cuándo se capturó y cuándo se revisó | Un criterio de hace ocho años puede haber cambiado |
| **Evidencia** | Enlace al documento que lo respalda | Distingue lo documentado de lo recordado |
| **Confianza** | Alta, media o baja, declarada por la persona | Un recuerdo sin evidencia no vale lo mismo que un contrato |
| **Vigencia** | Permanente, o con fecha de caducidad | Imprescindible en excepciones |
| **Sensibilidad** | Clasificación de qué puede salir y qué no | Alimenta la lista de información restringida (cap. 11) |
| **Transferibilidad** | Alta, media o baja | Los componentes 4 y 8 serán casi siempre baja, y así debe verse |
| **Riesgo si se pierde** | Impacto declarado | Ordena el trabajo: se empieza por lo que más dolería |
| **Conexiones** | A qué otros elementos se enlaza | Es lo que convierte una lista en un grafo |
| **Requiere intervención humana** | Marca booleana | **Bloquea toda ejecución automática** sobre ese elemento (§10) |

**Dos consecuencias de diseño que salen de esta tabla:**

1. **El modelo distingue lo documentado de lo recordado.** Un elemento con confianza baja y
   sin evidencia es una tarea pendiente, no un activo.
2. **El modelo sabe lo que no sabe.** Un componente sin ninguna entrada es un vacío
   explícito, y el sistema debe poder mostrarlo.

## 5. Captura progresiva

La plataforma podría recibir, con el tiempo: texto, cuestionarios, documentos, hojas de
cálculo, procedimientos existentes, notas, audio, entrevistas, fotografías de documentos,
vídeo cuando sea útil y datos de otros sistemas.

**No se diseñan integraciones en esta etapa.**

Lo que la IA podría hacer sobre ese material: transcribir · resumir · clasificar por
componente · extraer entidades y relaciones · comparar versiones · **detectar
contradicciones** · formular nuevas preguntas · identificar vacíos · proponer estructuras.

**Siempre bajo revisión humana, y con dos reglas:**

1. **Nada entra en el modelo del ADN sin confirmación de una persona.** La IA propone
   entradas; no las crea.
2. **La IA nunca rellena un vacío con una inferencia.** Si falta, se marca como vacío.

## 6. Las dos rutas

**Regla de experiencia (D-060):** la plataforma nunca debe hacer sentir al usuario de la
ruta B que está usando software diseñado para una empresa grande.

| | **Ruta A** — con equipo | **Ruta B** — solo o casi solo |
|---|---|---|
| Módulo 0 | Objetivo, horizonte y quién más participa | Objetivo y horizonte |
| Destinatario de la transferencia | Personas, en primer lugar | **Procedimientos y sistemas, en primer lugar** |
| Módulo 7, autoridad | Matriz por función y persona, **modo A** | Límites propios escritos, **modo B** (D-037) |
| Separación de funciones | Se configura | **No se finge.** Se ofrecen los sustitutos parciales y se dicen parciales |
| Módulo 9, transferencia | Bloques delegados a personas | Bloques transferidos a procedimientos, automatizaciones, colaboradores externos, un socio, un sucesor o un comprador |
| Prueba de ausencia | Alguien queda al mando | **Nadie queda al mando.** La prueba mide qué sobrevive solo |
| Vocabulario | Equipo, responsables, áreas | Usted, su trabajo, quien le apoya |

**Ejemplo de la diferencia, que resume la regla entera.** Donde una aplicación corriente
preguntaría:

> ¿Qué departamento aprobará esto?

esta pregunta:

> ¿Cómo podría esta decisión dejar de depender exclusivamente de usted?

con opciones reales para ambas rutas: **una persona · un procedimiento · una regla escrita ·
una automatización · un colaborador externo · un sucesor · un sistema · o mantenerla bajo su
control, a conciencia.**

La última opción importa tanto como las otras: **decidir conservar una decisión es un
resultado legítimo**, y el producto debe permitirlo sin penalizarlo. Es la traducción
funcional de D-040.

## 7. Progreso y madurez

### 7.1 No se crea una escala nueva

Se evaluó el modelo de madurez de siete niveles propuesto y **se descarta como escala
propia** (D-058). Motivo: el proyecto ya tiene dos escalas, y una tercera confundiría.

| Escala existente | Qué mide | Dónde vive |
|---|---|---|
| **Índice de Dependencia**, 0-72 | El **estado**: cuánto depende el negocio de una persona | Herramienta 1 |
| **Niveles de autonomía**, 0-6 | El **permiso**: qué se le deja hacer a la tecnología | `08-niveles-de-autonomia.md` |

La progresión que faltaba no es una escala nueva: **es el propio Método LEGADO expresado
como estado del usuario**. La correspondencia es casi exacta:

| Estado propuesto | Etapa LEGADO |
|---|---|
| Dependencia desconocida | Antes de L |
| Dependencia diagnosticada | L |
| ADN identificado | L→E |
| ADN estructurado | E |
| ADN transferible | E→G |
| Operación asistida | A |
| Delegación supervisada | D |
| Legado Inteligente | O |

**Decisión: el modelo de madurez es LEGADO.** El producto muestra la letra en la que está el
usuario, el Índice mide su estado y los niveles de autonomía gobiernan la tecnología. Tres
instrumentos, ninguno duplicado.

### 7.2 Indicadores con significado

**Prohibido el «43 % completado».** Un porcentaje de relleno no dice nada sobre el negocio y
premia rellenar en lugar de pensar.

Los indicadores se derivan del modelo, no se inventan:

| Indicador | De dónde sale |
|---|---|
| **Dependencia**: alta → media → baja | Índice de Dependencia, medido y remedido |
| **Conocimiento crítico**: 12 de 19 áreas documentadas | Inventario del capítulo 6, con estado por entrada |
| **Criterio**: 7 de 11 decisiones críticas estructuradas | Manual de criterio, contra el mapa de decisiones |
| **Procesos**: 14 de 18 transferibles | Metadato de transferibilidad |
| **Excepciones**: 9 identificadas, 6 cubiertas | Registro de excepciones, con vigencia |
| **Prueba de ausencia**: 1 día ✓ · 7 días ✓ · 30 días pendiente | Módulo 10 |
| **Riesgos críticos**: 8 → 3 | Mapa de riesgos del capítulo 4, actualizado |

**Regla:** ningún indicador puede subir por rellenar un campo. Sube por **cerrar un vacío
real y con evidencia**. Si un indicador puede mejorarse escribiendo cualquier cosa, está mal
diseñado.

## 8. Prueba de ausencia acumulativa

El libro entrega dos pruebas, de 24 horas y 7 días. La plataforma las convierte en un
**proceso acumulativo**: 1 día → 3 días → 7 días → 30 días → 90 días, cuando corresponda.

Se registra durante la ausencia: preguntas recibidas · decisiones bloqueadas · excepciones
aparecidas · procesos detenidos · personas que necesitaron ayuda · sistemas insuficientes ·
información que faltaba.

> **Cada fallo se convierte automáticamente en una tarea de reducción de dependencia**,
> enlazada al elemento del ADN que faltaba.

Es el mecanismo que cierra el círculo del producto: la prueba no evalúa, **alimenta**. Y
recoge la regla del libro de que lo que se corrige es el sistema, no la persona.

**Cautela:** las duraciones superiores a siete días **no están en el libro**. Si el producto
las ofrece, no puede presentarlas como parte del método hasta que el método las incorpore
(D-059). Registrado como asunto para la Etapa 3.

## 9. Asistente del ADN Empresarial

Nivel conservador **anterior** al Gemelo de IA, y probablemente el techo real del producto
durante mucho tiempo.

**Puede:** localizar información · resumir · comparar · explicar procedimientos · recuperar
antecedentes · sugerir preguntas · **mostrar siempre sus fuentes** · preparar decisiones.

**No puede:** inventar criterio.

> **Regla central: si el ADN capturado no contiene la respuesta, el sistema debe decir
> «esto todavía no está documentado» y convertir esa ausencia en una tarea.**

Esa regla es el mayor diferencial defendible del producto y, a la vez, su mayor coherencia
con el libro: **un sistema que reconoce lo que no sabe es lo contrario de uno que suena
convincente.** Enlaza con el sesgo de automatización del capítulo 14 (D-019).

### 9.1 Trazabilidad obligatoria

Toda respuesta debe poder decir de dónde salió, distinguiendo cinco cosas:

| Tipo | Qué es | Cómo se presenta |
|---|---|---|
| **A** | Información documentada | Con enlace a la evidencia |
| **B** | Regla explícita del usuario | Citando la regla y su fecha |
| **C** | Inferencia del sistema | **Marcada como inferencia**, siempre |
| **D** | Recomendación | Con sus motivos y su grado de incertidumbre |
| **E** | Ausencia de información | Como vacío, y como tarea |

> **La IA nunca presenta una inferencia como si fuera criterio documentado del propietario.**

Es la regla más importante de esta sección. Un sistema que confunde C con A destruye el
valor del ADN capturado, porque el usuario deja de poder distinguir lo suyo de lo inventado.

## 10. Gemelo de IA

Se mantienen **D-045 y V-25b sin ninguna variación**.

Avanzado · opcional · **no es el producto inicial** · no aparece antes del capítulo 15 · no
sustituye a una persona · no tiene identidad humana · no asume responsabilidad profesional ·
opera bajo supervisión, con persona en el circuito o sobre el circuito según el riesgo.

> **La plataforma debe poder entregar un valor enorme sin llegar nunca a esta etapa.**

**Requisito funcional derivado de las profesiones reguladas:** todo elemento marcado como
«requiere intervención humana» **bloquea la ejecución automática**, en cualquier nivel de
autonomía y también para el gemelo. La marca es del contenido, no una preferencia del
usuario, y no puede desactivarse desde una pantalla de ajustes.

## 11. Legado Inteligente en el producto

**No es una puntuación comercial** y no se convierte en un porcentaje. Es un **estado
demostrado por evidencias**, y la plataforma solo puede mostrarlo cuando existan:

menor dependencia medida y sostenida · conocimiento crítico disponible fuera de una cabeza ·
decisiones transferibles · procesos documentados · excepciones conocidas y vigentes ·
supervisión definida · pruebas de ausencia superadas · continuidad comprobada en el tiempo.

**Prohibido:** un medidor de «Legado Inteligente» que suba con la actividad del usuario.
Sube con evidencia, o no sube.

## 12. Correspondencia con el libro

La plataforma debería poder reconocer **en qué capítulo está conceptualmente el usuario**,
usando el mapa de `02-mapa-libro-plataforma.md`.

**No para obligarle a leer.** Para ajustar preguntas, ejercicios, profundidad,
recomendaciones, explicaciones y recursos.

**Dos cautelas:**

1. **El usuario puede no haber leído el libro**, y el producto no puede darlo por supuesto ni
   hacérselo notar.
2. **El usuario puede ir en otro orden.** El motor de flujo señala requisitos que faltan; no
   bloquea.
