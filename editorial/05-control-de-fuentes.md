# 05 — Control de fuentes en el manuscrito

**Etapa:** 1 — Fundamentos. Con registros desde la Etapa 2.
**Estado:** vigente. **Treinta y seis afirmaciones registradas a 2026-09-09, todas cerradas**,
en nueve de las catorce piezas escritas: introducción y capítulos 1, 2, 5, 9, 10, 11, 12 y 13.
Cero marcas `[POR VERIFICAR]` en el manuscrito.

**Aviso de recuento (2026-09-09).** El encabezado decía «siete afirmaciones registradas», cifra
de la Etapa 2 que dejó de describir el archivo hace mucho. Se corrige aquí y **se cuenta de una
sola manera, para que no vuelva a divergir: una fila de la tabla del apartado 3 es una
afirmación**, aunque cite dos fuentes. Las cinco piezas restantes no llevan ninguna
referencia externa, por decisión razonada registrada más abajo: los capítulos 3, 4, 6, 7 y 8.

Este archivo controla el uso de fuentes **dentro del texto**. El repositorio de fuentes
en sí vive en `investigacion/fuentes-verificadas.md`. La separación es deliberada: una
fuente puede estar verificada y no usarse, y una afirmación puede necesitar fuente y no
tenerla todavía.

---

## 1. Regla

Ninguna cifra, estudio, autor, norma o afirmación factual entra en el manuscrito sin:

1. Consulta directa de la fuente original.
2. Registro en `investigacion/fuentes-verificadas.md` con identificador.
3. Anotación en la tabla del apartado 3 de este archivo.

Mientras falte cualquiera de las tres, la afirmación se marca en el texto de trabajo con
`[POR VERIFICAR]` y se anota en `investigacion/afirmaciones-por-verificar.md`.

**Ningún `[POR VERIFICAR]` puede sobrevivir a la Etapa 4.** La opción por defecto ante una
afirmación que no se logra verificar no es publicarla con reservas: es suprimirla o
reformularla como observación cualitativa del autor, debidamente marcada como tal.

## 2. Tipos de enunciado

El lector debe poder distinguir, sin esfuerzo, qué está leyendo.

| Tipo | Se escribe así | ¿Necesita fuente? |
|---|---|---|
| Hecho verificable | "Según [institución], …" | Sí, siempre. |
| Marco o norma | "El marco [nombre] establece…" | Sí, con versión y fecha. |
| Inferencia del autor | "De esto se sigue que…" | No, pero debe apoyarse en un hecho citado antes. |
| Recomendación | "Recomiendo que…" | No. |
| Propuesta propia del libro | "En este libro llamamos…" | No. |
| Caso ficticio | "Imagine una empresa que…" | No. Se registra en `revision/control-de-casos.md`. |
| Observación cualitativa | "Es frecuente que…" | No, pero **no puede** incluir cifras ni porcentajes. |

La última fila es la más importante en la práctica: la tentación habitual es escribir "el
setenta por ciento de las empresas familiares…" cuando lo que se quiere decir es "es
frecuente que…". Si no hay fuente, se escribe la segunda forma y se elimina la cifra.

## 3. Registro de fuentes usadas en el manuscrito

Nueve afirmaciones con fuente en las tres piezas escritas. Ninguna cifra sin fila en esta
tabla.

| Cap. | Afirmación en el texto | ID de fuente | Tipo de enunciado | Verificado el | Estado |
|---|---|---|---|---|---|
| Intro | «El estudio en que se apoya identificó más de 90 definiciones distintas de empresa familiar, y advierte que las cifras varían entre estudios porque dependen de la definición que se emplee.» | F-001 | Hecho verificable | 2026-09-06 | Cerrada |
| Intro | «Ese mismo informe europeo sitúa a las empresas familiares en más del 60 % de todas las empresas europeas.» | F-001 | Hecho verificable | 2026-09-06 | Cerrada. Ámbito europeo declarado en el texto. **Revisado el 2026-09-07:** la comparación con la cifra estadounidense ya no se presenta como atribuible solo a la definición. |
| Intro | «El 27,3 % de las empresas eran familiares [en Estados Unidos, 2021] y daban empleo al 34,1 % de los trabajadores; allí se considera familiar una empresa cuando dos o más miembros de una familia poseen la mayoría del negocio.» | F-002 | Hecho verificable | 2026-09-06 | Cerrada. País, año y definición declarados en el texto. |
| Intro | «En América Latina ni siquiera existe una definición común de micro, pequeña y mediana empresa, y la información disponible es escasa y a menudo de mala calidad.» | F-004 | Hecho verificable | 2026-09-06 | Cerrada. Ámbito y fuente declarados en el texto. |
| Intro | «La Comisión Europea, al analizar en 2006 la transmisión de empresas en la Unión Europea, señaló que cuando una compañía cierra únicamente por problemas en la fase de traspaso se destruye conocimiento, contactos establecidos y otros activos intangibles.» | F-003 | Hecho verificable | 2026-09-06 | Cerrada. Institución, año y ámbito declarados en el texto. |
| Intro | «Veinte años después, la misma institución sigue advirtiendo de que un número creciente de propietarios se acerca al retiro sin sucesor designado.» | F-012 | Hecho verificable | 2026-09-06 | Cerrada. Sin cifras, por decisión: la fuente no las aporta. |
| 1 | «Según la Oficina de Defensa de la Pequeña Empresa, con datos censales de 2021, el 57,9 % de las empresas familiares del país tenía más de diez años de vida.» | F-002 | Hecho verificable | 2026-09-06 | Cerrada. País y año declarados en el texto. **Revisado el 2026-09-07:** se suprimió la generalización «la mayoría son organizaciones maduras», que excedía el ámbito del dato. |
| 2 | «En 1991, el investigador Ikujiro Nonaka publicó en la *Harvard Business Review* un artículo que popularizó una distinción…»: la distinción entre conocimiento explícito y tácito, el maestro artesano y el enunciado de que el conocimiento no explicitado no puede aprovecharlo el conjunto. | F-016 | **Distinción conceptual atribuida**, no dato ni norma | 2026-09-07 | Cerrada. Autor, publicación y año declarados en el texto. **Revisado el 2026-09-07 (Etapa 3.1.1):** siete de los ocho fragmentos entrecomillados se convirtieron en paráfrasis; solo se conserva entre comillas «en la punta de los dedos». El original en inglés de cada frase consta íntegro en F-016, de modo que la paráfrasis sigue siendo verificable. **Alcance comprobado:** la fuente sostiene la distinción tácito/explícito, la dificultad de formalizar, el ejemplo del artesano y la importancia de hacer el conocimiento compartible, y **no se usa para nada más**: ni eficacia del Método LEGADO, ni valor financiero, ni prevalencia en negocios pequeños, ni facilidad de transferencia, ni ventajas cuantitativas, ni IA. |
| 2 | «Ese conocimiento sí puede pasar de una persona a otra sin escribirse: el mismo artículo describe al aprendiz que se coloca junto al maestro y aprende observando, imitando y practicando. Pero advierte de que esa vía, por sí sola, tiene un límite…» | F-016 | Descripción atribuida a la fuente | **2026-09-07 (Etapa 3.1.2)** | Cerrada. Corresponde al patrón **tácito a tácito** del artículo y a la acotación que el propio Nonaka le pone. **Verificado releyendo el PDF, no de memoria.** Se restituye además el «easily» que la redacción anterior había perdido: la fuente dice que el conocimiento no explicitado «cannot **easily** be leveraged», no que no pueda aprovecharse. El capítulo **no nombra el modelo SECI** ni sus cuatro patrones: los usa para no equivocarse, no para exponerlos. |
| 2 | «podemos saber más de lo que podemos decir», atribuida a Michael Polanyi. | F-016 (donde se leyó) + F-017 (corrobora obra y frase) | Cita atribuida | 2026-09-07 | Cerrada. **Conservada tras la revisión 3.1.1** como la única cita memorable que justifica serlo. **No se ha leído el libro de Polanyi**; la frase se leyó citada en F-016 y se corroboró en la ficha del editor (F-017), que la reproduce como frase inicial de *The Tacit Dimension*. El texto la atribuye a Polanyi **a través de Nonaka**, que es como se leyó. No se le atribuye ninguna otra idea, **no se cita número de página** y el capítulo no menciona ningún contenido del libro de Polanyi. |

**Recuento de referencias externas por pieza.** Introducción: cinco fuentes distintas
(F-001, F-002, F-003, F-004, F-012), en seis afirmaciones. Capítulo 1: una (F-002).
Capítulo 2: dos (F-016 y F-017), concentradas en un solo apartado, sin ninguna cifra y, tras
la revisión 3.1.1, con una sola cita textual breve. El
máximo orientativo del plan de investigación es de tres por capítulo; la introducción lo
excede de forma deliberada y por una sola vez, porque es allí donde se explica al lector
por qué el libro no dará cifras y esa explicación exige mostrar las fuentes que sí
resisten. **No se repetirá en ningún capítulo.**

**Capítulo 3: cero referencias externas, por decisión.** Se evaluó si el capítulo necesitaba
respaldo para hablar de autonomía, dependencia y toma de decisiones, y se concluyó que no:
todo lo que afirma es o bien una observación cualitativa reconocible, o bien el desarrollo
de un principio propio del libro —presencia no es autonomía—, o bien instrucciones de un
ejercicio. **No contiene ninguna cifra, ninguna afirmación de frecuencia y ninguna
atribución a autor o institución.** El control de dos pasos del apartado 3, «Regla corregida el 2026-09-07» se aplicó
íntegro: la búsqueda literal devolvió «siempre», «nunca» y «todo el mundo», y la lectura
dirigida las clasificó como negaciones y universales referidos a la historia del propio
lector o como instrucciones del ejercicio, no como enunciados sobre el mundo. Ninguna
requería fuente.

**Capítulo 6: cero referencias externas, por decisión razonada.** Antes de escribirlo se
comprobó si necesitaba alguna afirmación factual externa. No la necesita: lo que el capítulo
sostiene es una **definición operativa propia** de conocimiento crítico —dos condiciones que
deben cumplirse a la vez—, un **procedimiento de búsqueda** sobre el rastro del propio
lector, **instrucciones** y una **microescena**. Ninguna cifra, ninguna afirmación sobre el
mundo y ninguna atribución. **Q-16 estaba mapeada a este capítulo y no se ejecutó**, para no
citar marcos de gestión del conocimiento como adorno; su plazo real es antes del capítulo 9.




**Capítulo 13: tres referencias externas, dos documentos, ninguna cifra.** Las tres son del
mismo instituto —**F-007** y **F-045**— y las tres se usan **para limitar lo que el método puede
prescribir**, no para autorizarlo. Es el primer capítulo del libro en que una fuente sirve
principalmente para **negarse a dar un número**.

| Cap. | Afirmación en el texto | ID | Tipo | Estado |
|---|---|---|---|---|
| 13 | «El marco de gestión de riesgos del instituto estadounidense de normas y tecnología —el documento **de uso voluntario** que ya citamos— pide que los criterios se demuestren **en condiciones parecidas a las del uso real**, y advierte que medir en un entorno controlado **puede dar un resultado distinto del que aparece en la operación de verdad**.» | **F-007** | Requisito y advertencia atribuidos | Cerrada. Corresponde a **MEASURE 2.3** —«demonstrated for conditions similar to deployment setting(s)»— y al pasaje **«Risk in real-world settings»** del cuerpo, los dos registrados al ampliar F-007 en la Etapa 3.12A. **El carácter voluntario va dentro de la frase**, y el capítulo ya lo había dicho en el 12: **no se presenta como obligación de nadie**. Es el respaldo de por qué el modo sombra se hace sobre trabajo real y no sobre una prueba pequeña. |
| 13 | «El propio marco citado advierte que el dato con el que uno compara **puede sencillamente no existir**.» | **F-007** | Advertencia atribuida, **parafraseada** | Cerrada. El original dice «**the ground truth may either not exist or not be available**». **La paráfrasis evita el término técnico a propósito**, por la regla del capítulo: cuando el comparador es una decisión de una persona, el libro la llama **«decisión real tomada»** y **nunca *ground truth***. La fuente se usa aquí **en apoyo de una cautela**, no de un método. |
| 13 | «El instituto de normas, en un informe de 2026 sobre la vigilancia de sistemas ya en funcionamiento, coloca **“cuál es la cadencia correcta”** entre sus **preguntas abiertas**, y describe las metodologías validadas del asunto como incipientes. Eso no demuestra que no exista una duración adecuada; dice que **las fuentes revisadas no la establecen**.» | **F-045** | **Ausencia declarada**, y es el uso más delicado del capítulo | Cerrada. Traduce «What is the right cadence for monitoring?», del apartado 3.3.3 del informe, y «best practices, validated methodologies, and common terminology **is nascent**». **La naturaleza del documento va dicha dentro de la frase** —«un informe sobre la vigilancia de sistemas ya en funcionamiento»—, y **la frase siguiente impide el salto lógico** que la Etapa 3.12A.1 tuvo que corregir en la ficha de la propia fuente: una pregunta abierta dice **qué no está establecido**, no **qué no existe**. **Prohibido**, y no se hace: «se ha demostrado que no existe» y «nadie sabe». |

**Fuentes disponibles que el capítulo 13 decidió NO citar.**

| Fuente | Por qué estaba disponible | Por qué no se cita |
|---|---|---|
| **F-010** (Reglamento UE 2024/1689, art. 14) | Contiene las condiciones de la supervisión —poder no usar, ignorar, anular, revertir e interrumpir—, que encajarían en el paso al nivel 3. | **Se citó entera en el capítulo 12**, con su doble acotación de ámbito, y volver a citarla aquí habría sido repetir el mismo párrafo con otras palabras. **La cautela sí actúa**: el capítulo 13 conserva la autoridad donde estaba y no presenta ninguna alerta como aprobación. |
| **F-043** (revisión sistemática sobre sesgo de automatización) | El nivel 3 introduce avisos, y el exceso de confianza en una salida automática es su riesgo natural. | **Su capítulo propietario sigue siendo el 14** (D-019). El capítulo 13 formula el problema del volumen de alertas **como regla de diseño del método** —«si todo interrumpe, crítico deja de distinguir»— y **declara expresamente que no es una estadística**, precisamente para no apoyarse en una fuente cuyo turno no ha llegado. |

**Sobre las herramientas 10 y 11.** La herramienta 10 repite, en su apartado 10, **la misma
afirmación de F-045** con la misma acotación. **Las herramientas no forman parte del manuscrito**
y no se cuentan en la tabla de arriba, pero la afirmación se comprobó igual: dice lo mismo, con
el mismo ámbito y sin cifras. **La herramienta 11 no contiene ninguna referencia externa.**

**Control de universalidades del capítulo 13.** Ejecutado en las dos pasadas obligatorias.
**Primera, literal: dieciséis apariciones.** **Segunda, de lectura: doce legítimas y cuatro
corregidas.** Las legítimas son pronombres negativos —«sin nadie mirando», «vigilar a nadie»,
«sin que nadie actuara por eso»—, usos internos del caso —«lo que hacía siempre», «ese cliente
manda siempre la hora mal»—, modismos —«las excepciones de siempre», «el procedimiento de
siempre»— y reglas —«nunca en una decisión», «siempre que se pueda»—. Las cuatro corregidas:
**«casi todos los días coincidían»**, que era una afirmación de frecuencia dentro del caso y se
sustituyó por «unos días coincidían y otros no»; **«su primera reacción fue la de cualquiera»**,
que afirmaba cómo reacciona la gente y se quedó en «su primera reacción»; **«la pregunta llega
siempre»**, que afirmaba algo sobre los lectores; y **«nadie la ha establecido todavía»**, que
era la más grave porque reintroducía exactamente la formulación que la Etapa 3.12A.1 acababa de
prohibir, y se corrigió a **«las fuentes revisadas no la establecen»**.

**Y una quinta, que la segunda pasada encontró en un pasaje añadido después:** «la función que
revisa **suele ver** algo que quien ejecuta no ve». Se sustituyó por una formulación condicional
—«hay algo que esa separación **puede** aportar»—. **Cinco correcciones**, y **las cinco en
frases de transición**, que es el patrón registrado desde el capítulo 9 y que ya lleva cinco
capítulos cumpliéndose sin excepción.

**Capítulo 12: cinco afirmaciones y tres fuentes, ninguna con cifras.** Es el capítulo con más
riesgo de exageración del libro, y el riesgo va en la dirección contraria a la del 11: allí la
tentación era convertir una norma en obligación universal; **aquí la tentación es prometer**.
Por eso la fuente más citada del capítulo se usa **en su contra**: el hallazgo que más pesa dice
que juntar persona y sistema **puede empeorar** el resultado.

| Cap. | Afirmación en el texto | ID | Tipo | Estado |
|---|---|---|---|---|
| 12 | «…el marco de gestión de riesgos del instituto estadounidense de normas y tecnología —un documento **de uso voluntario**, no una ley— describe configuraciones que **recorren ese abanico**, e incluye la posibilidad de que un sistema se use **como una opinión más** dentro de una decisión que sigue siendo de una persona.» **Redacción ajustada el 2026-09-09 (Etapa 3.11B.1)**, sin cambio de contenido. | **F-007** | Descripción atribuida | Cerrada. Apéndice C, **registrado en la Etapa 3.11A al releer el PDF oficial completo**. Traduce «Human-AI configurations can span from fully autonomous to fully manual… or be used by a human decision maker as an additional opinion». **La naturaleza del documento va dentro de la frase**, entre guiones, y el capítulo dice acto seguido que **los siete escalones concretos son del libro y no de la fuente**. |
| 12 | «…advierte que **los resultados de la interacción entre personas y sistemas varían**: en ciertas condiciones, la parte del sistema puede amplificar los sesgos de la persona y llevar a decisiones **peores que las que habrían tomado la persona o el sistema por separado**. Y añade lo otro…: cuando esas variaciones se tienen en cuenta al organizar el trabajo, sí puede aparecer complementariedad y un resultado mejor.» | **F-007** | **Hallazgo atribuido, en sentido contrario a la intuición** | Cerrada, y es **la afirmación más importante del capítulo**. Traduce el apéndice C íntegro, **con sus dos mitades**: la fuente dice las dos cosas y el libro no puede quedarse con una. **La condición «en ciertas condiciones» se conserva**; el ejemplo que da la fuente —tareas de juicio perceptivo— **no se reproduce**, porque nombrarlo habría obligado a explicar un dominio que el libro no trata. De aquí sale la constante **«persona más sistema no es automáticamente mejor»**. **Corrección del 2026-09-09 (Etapa 3.11B.1), y es la más importante de ese control:** el capítulo cerraba esta sección con «la mejora no viene de juntarlos: **viene de gobernar cómo se juntan**», y esa segunda mitad **afirmaba una causalidad que F-007 no sostiene**. La fuente dice que la complementariedad **puede** aparecer cuando las variaciones se tienen en cuenta; no dice que gobernarlas produzca mejora. Redacción vigente: **«juntarlos no garantiza una mejora, y precisamente por eso importa gobernar cómo trabajan juntos», seguida de «gobernarlo tampoco la garantiza: lo que hace es dejar de confiarla al azar»**. **Prohibido** volver a la formulación anterior: convertía una posibilidad condicionada en una promesa del método. |
| 12 | «Y el marco voluntario pide que existan **mecanismos y responsables asignados** para desconectar un sistema cuyos resultados no encajan con el uso previsto.» | **F-007** | Requisito atribuido | Cerrada. Corresponde a **MANAGE 2.4**. **Se dice «pide», no «exige»**, y el carácter voluntario ya quedó dicho dos párrafos antes en la misma sección, de modo que no se repite el inciso. |
| 12 | «El reglamento europeo de inteligencia artificial —**una norma de la Unión Europea, y solo para sistemas de alto riesgo**, de modo que **no es una obligación general**— exige que las personas encargadas puedan **no usar la salida, ignorarla, anularla, revertirla e interrumpir el sistema**.» | **F-010** | Obligación atribuida, **con ámbito doble** | Cerrada. Artículo 14. **El ámbito se acota dos veces en la misma frase** —jurisdicción y clase de sistema— y el capítulo añade a continuación que **el libro toma esas condiciones como buen diseño, no como deber legal**. **Corregido durante la redacción (2026-09-09):** la primera versión decía «no es una obligación para cualquier lector», formulación que se leía como enunciado sobre lectores; se sustituyó por una **de alcance**. **Prohibido**, y no se hace: escribir que la ley obliga al lector. |
| 12 | «Un estudio experimental sobre una tarea concreta —**no sobre negocios, y sin muestra declarada, así que no puede convertirse en una afirmación sobre nadie**— observó que a las personas les cuesta juzgar su propio metaconocimiento… y que delegar bien en un sistema depende justamente de eso.» | **F-044** | Hallazgo atribuido, **con sus límites dentro de la frase** | Cerrada. **La acotación va antes del contenido**, que es la regla que este archivo viene aplicando desde el capítulo 10. **Prohibido**, y no se hace: convertirlo en «las personas delegan mal». La cita literaria del resumen original **no se reproduce**. La consecuencia práctica que el capítulo extrae —escribir el permiso en frío— **se presenta como del método, no como resultado del estudio**. |

**Fuentes disponibles que el capítulo 12 decidió NO citar.**

| Fuente | Por qué estaba disponible | Por qué no se cita |
|---|---|---|
| **F-043** (Romeo y Conti, revisión sistemática sobre sesgo de automatización) | Es la fuente central de Q-17 sobre el exceso de confianza, y su hallazgo contraintuitivo —que explicar mejor **no basta**— habría encajado en la sección sobre supervisión. | **Su capítulo propietario es el 14** (D-019), y adelantarla habría vaciado ese capítulo. El 12 tenía permitido **nombrar el problema**; decidió **ni nombrarlo**, porque nombrarlo sin poder desarrollarlo habría obligado a un párrafo de aplazamiento. **La cautela que aporta sí actúa**: el capítulo no promete en ningún punto que explicar el razonamiento corrija la confianza. |
| **F-009** (OCDE) | Contiene la capacidad de intervención y supervisión humanas, y es no vinculante. | **No añadía nada que F-007 y F-010 no dieran con más precisión**, y una tercera fuente en la misma sección habría convertido dos párrafos de argumento en una lista de citas. Sostiene el capítulo sin aparecer. |

**Control de universalidades del capítulo 12.** Ejecutado en las dos pasadas obligatorias el
2026-09-09, y **el recuento se da entero para que pueda comprobarse**.

*Primera pasada, literal, de clase abierta:* **diez apariciones**. *Segunda pasada, de lectura,
clasificándolas una a una:* **ocho son legítimas y dos se corrigieron.** Las ocho son pronombres
negativos o usos internos del caso —«nadie le había pedido que la fijara» y «nadie le había dicho
que no», del relato; «una réplica de nadie», dentro de la delimitación de la metáfora; «una
afirmación sobre nadie», que es precisamente la acotación de F-044; «si hoy nadie responde de esa
tarea», y «ninguna condición que nadie autorizó», de la fila de ejemplo, las dos condicionales;
«nunca por empresa entera», instrucción; «lo ha hecho siempre ella», del caso—. Las dos corregidas: **«va contra lo que promete casi cualquier folleto»**, que afirmaba
qué promete el mercado y **se eliminó sin sustituto**, aplicando la lección registrada en la
Etapa 3.10B.1 —**un enunciado de frecuencia no se corrige con otro adverbio de frecuencia, se
corrige quitándolo**—; y **«no es una obligación para cualquier lector»**, que se leía como
enunciado sobre lectores y se sustituyó por uno de alcance, «no es una obligación general».

*Y una tercera corrección que la búsqueda literal no podía encontrar*, porque no contenía
ninguna palabra de la lista: **«un buen resultado da confianza, y la confianza pide margen»**,
que enunciaba cómo se comporta la gente sin respaldo alguno. Se sustituyó por el enunciado del
riesgo —**«dejar que la calidad de la salida decida el permiso»**—, que es una regla del libro y
no una descripción de nadie. **Es la confirmación de por qué la segunda pasada es obligatoria:
la afirmación más discutible del capítulo era invisible a la primera.**

**Cuarta corrección, en el control posterior (Etapa 3.11B.1, 2026-09-09).** Al reescribir el criterio de evidencia de la fila de Nuria desapareció «ninguna condición que **nadie** autorizó», de modo que **el recuento literal del capítulo baja de diez apariciones a nueve, y las nueve son legítimas**: entraron dos usos nuevos —«en cualquier momento se pueden mantener, reducir o retirar» y «nunca por defecto»—, que son **enunciados de permiso y de regla, no afirmaciones sobre cómo se comporta la gente**. **Cero afirmaciones de frecuencia sin respaldo en el capítulo.**

**Tres correcciones en la redacción**, frente a las cuatro del capítulo 11 y las tres de su control posterior.
El patrón registrado desde el capítulo 9 —de tres a cuatro afirmaciones de frecuencia por
capítulo, **siempre en frases de transición**— **vuelve a cumplirse**: las tres estaban en
frases de enlace, ninguna en el argumento central ni en el caso.

**Capítulo 11: tres referencias externas, ninguna con cifras y las tres con su ámbito dicho
dentro de la propia frase.** Es el capítulo con más riesgo del libro hasta ahora, porque trata
de protección de datos y confidencialidad sin ser un capítulo jurídico: **la tentación no era
citar de menos, sino convertir la norma de una jurisdicción en una obligación para cualquier
lector.** Por eso cada cita dice **qué es la fuente y a quién obliga antes de decir lo que
dice**, y por eso el capítulo remite a la jurisdicción cada vez que el asunto lo exige.

| Cap. | Afirmación en el texto | ID | Tipo | Estado |
|---|---|---|---|---|
| 11 | «Los **Estándares de Protección de Datos de los Estados Iberoamericanos** —un marco regional de referencia aprobado en 2026 por las autoridades de protección de datos de la región, **que no es una ley y cuya aplicación jurídica depende de la legislación de cada país**— piden tratar solo los datos “adecuados, pertinentes y limitados al mínimo necesario”.» | **F-038** | Principio atribuido | Cerrada. **Lectura directa del PDF oficial.** Corresponde al apartado 18.1. **El ámbito va en un inciso, antes del contenido.** Corregido el 2026-09-09 (Etapa 3.10B.1): la redacción anterior decía «que cada país aplica a través de la suya», que afirmaba más de lo que la fuente permite sobre lo que hace cada Estado. |
| 11 | «…y añaden una frase que vale la pena tener a mano: usar tecnologías automatizadas o sistemas de inteligencia artificial **no justifica por sí solo pedir más datos de los que harían falta sin ellos**.» | **F-038** | Principio atribuido, **parafraseado** | Cerrada. El original dice que la IA «no justificará, por sí sola, la obtención masiva, indiscriminada o desproporcionada de datos personales». **La paráfrasis conserva el sentido y baja el registro**, que es lo que pide la guía de estilo; el original consta íntegro en la fila de F-038. |
| 11 | «En la **Unión Europea**, la autoridad europea de protección de datos sostiene que quien contrata a un proveedor debe comprobar **antes** que ofrece garantías suficientes, y **poder demostrar que lo comprobó**; y que lo que se mira para eso son cosas concretas, como su política de privacidad o sus términos de servicio. **Es una regla de ese marco, y no debe leerse como una obligación general para quien esté en otra jurisdicción.** La pregunta práctica, en cambio, sigue sirviendo.» | **F-040** | Principio atribuido, **con exclusión expresa** | Cerrada. Corresponde a los párrafos 94 y 95 de las *Guidelines 07/2020*. **Lectura directa del PDF oficial.** Corregido el 2026-09-09 (Etapa 3.10B.1): decía «Ese régimen no rige fuera de la Unión», una exclusión más amplia de lo que hacía falta y de lo que las fuentes registradas permiten sostener. La redacción vigente **acota el ámbito sin pronunciarse sobre lo que rige en ninguna otra parte**. |
| 11 | «En **Estados Unidos**, personal de la Federal Trade Commission publicó en 2024 una nota —**una entrada de su blog, no una norma**— advirtiendo de que las empresas de estos servicios deben cumplir lo que prometen a sus clientes, incluidas las promesas de no usar sus datos para entrenar o actualizar sus sistemas.» | **F-042** | Advertencia atribuida | Cerrada. **La naturaleza del documento va dentro de la frase, entre guiones**, para que no pueda leerse como legislación. **Prohibido**, y no se hace: escribir «la ley estadounidense dice» o «la FTC exige a toda empresa». |
| 11 | «Y observaba algo que describe exactamente el momento de Óscar: **los clientes introducen en estas herramientas documentos internos e información de sus propios clientes.**» | **F-042** | Observación atribuida | Cerrada. Traduce «customers may reveal sensitive or confidential information when using a company's models, such as internal documents and even their own users' data». **Es una observación de riesgo, no una obligación**, y así entra. |

**Fuentes disponibles que el capítulo 11 decidió NO citar.**

| Fuente | Por qué estaba disponible | Por qué no se cita |
|---|---|---|
| **F-039** (SIC Colombia, Circular Externa 002 de 2024) | Es el ejemplo más concreto de la tanda: una autoridad nacional que ya escribió reglas sobre IA y datos personales, con cuatro criterios de ponderación. | **No añadía nada que F-038 no diera con ámbito más amplio**, y habría obligado a explicar por qué aparece un país concreto en un libro que se dirige a lectores de muchos. **Informa el diseño de la herramienta 9 sin aparecer en el manuscrito.** Queda disponible para el capítulo 16, donde el asunto jurídico sí se trata de frente. |
| **F-041** (EDPB, *Opinion 28/2024*) | Sostiene que los modelos entrenados con datos personales **no pueden considerarse anónimos en todos los casos**, y que la anonimidad se valora caso por caso. | **La cautela que respalda —que quitar un nombre no es anonimizar— se enuncia como constante propia del libro y no necesita la cita.** Citarla habría obligado a entrar en entrenamiento de modelos, que es **exactamente lo que el capítulo 11 tiene prohibido**. Sostiene la constante en `06-control-de-continuidad.md` sin aparecer aquí. |

**Control de universalidades del capítulo 11.** Ejecutado en dos pasadas. La primera, el
2026-09-09 al escribirlo: veintiocho apariciones, **cuatro corregidas** por afirmar cómo se
comporta la gente sin respaldo —«casi nunca el problema es que no haya datos», «la pregunta que
casi todo el mundo se hace», «casi nunca» como respuesta, «la parte que casi nadie mira»—. La
segunda, en la Etapa 3.10B.1: **tres correcciones más**. Dos eran adverbios de frecuencia que
habían entrado como sustitutos de los anteriores —«muchas veces sobra» y «muchas veces, no»—,
sustituidos ahora por formas condicionales, «puede que sobre» y «puede que no»; y la tercera
era «porque se usa mal constantemente», que se eliminó sin sustituto. **La lección que deja:
corregir un enunciado de frecuencia con otro adverbio de frecuencia no lo corrige.** En la
herramienta 9 se retiraron además un umbral inventado —«con tres o cuatro veces deja de
necesitar la hoja»— y una progresión presentada como segura —«las primeras veces con la hoja
delante; después, de memoria»—.

**Capítulo 10: dos referencias externas, ninguna con cifras y ambas con su ámbito dicho en la
propia frase.** Es el capítulo con más riesgo de convertir una práctica de control en una
obligación para el lector, y por eso las dos citas llegan acompañadas de lo que la fuente **no**
es.

| Cap. | Afirmación en el texto | ID | Tipo | Estado |
|---|---|---|---|---|
| 10 | «Un manual de la administración tributaria estadounidense, escrito para orientar inspecciones fiscales y no para gestionar negocios […]: muchos negocios pequeños tienen un propietario y ningún empleado, y **en esa situación esa separación no puede existir**, aunque sí puedan existir otros procedimientos.» | **F-035** | Hecho estructural atribuido | Cerrada. **El ámbito va dentro de la frase**, antes del contenido: se dice qué es la fuente y para qué se escribió, de modo que el lector no pueda leerla como una norma de gestión. Corresponde verbatim a IRM 4.10.3.6.3.3. **No se le hace decir nada sobre cómo debe gobernarse un negocio.** |
| 10 | «Y la norma de control interno del gobierno federal estadounidense —**que obliga a organismos públicos de aquel país, no a su negocio**— prevé exactamente lo mismo: cuando separar funciones **no resulta practicable**, se diseñan controles alternativos.» | **F-034** | Principio atribuido | Cerrada. Corresponde a los párrafos 10.21 y 10.23 del Green Book. **La exclusión del lector va en un inciso, no en una nota al pie.** |
| 10 | «la propia norma que acabo de citar advierte que ningún conjunto de controles da **certeza absoluta**, por error humano, por juicios equivocados o porque quien manda pase por encima de sus propias reglas.» | **F-034** | Límite atribuido | Cerrada. Es el uso más importante de la fuente en el capítulo: **entra para impedir que la matriz prometa algo**, no para respaldarla. |
| 10 | «ninguna de esas fuentes dice que un control alternativo **equivalga** a la separación, y tampoco dice que sea peor. **Su suficiencia depende del caso.** Este libro le recomienda tratarlos con más cautela que un control ajeno, y eso es un consejo nuestro, no un hallazgo.» | **F-034, F-035** | **Declaración expresa de lo que las fuentes no dicen** | Cerrada. Es la aplicación literal de **V-61**. El capítulo **no resuelve por redacción** lo que la investigación dejó abierto, y separa en la misma frase lo verificado de la recomendación propia. |

**Fuentes disponibles que el capítulo 10 decidió NO citar.**

| Fuente | Por qué estaba disponible | Por qué no se cita |
|---|---|---|
| **F-036** (PCAOB, *staff views*, 2009) | Dice que menos personal limita la separación y que se usan enfoques alternativos. | **No añadía nada que F-034 y F-035 no dijeran mejor**, y habría exigido explicar al lector qué es una empresa cotizada pequeña y por qué un regulador de mercados aparece en un libro para negocios familiares. **Tres fuentes para el mismo principio son decoración.** Queda disponible si una revisión posterior necesita una confirmación independiente. |
| **F-037** (COSO, 2013) | Es el marco de referencia más conocido del asunto. | **Solo se tiene su identidad**: el marco se vende y no se abrió. **Cero contenido citado**, y el capítulo no dice que se base en él. |

**Control de universalidades del capítulo 10, ejecutado el 2026-09-08.** Búsqueda literal como
clase abierta más lectura dirigida de las treinta y cinco apariciones. **Cuatro se corrigieron por
ser afirmaciones sobre el mundo o sobre las personas sin respaldo:** el título de apartado «el
límite casi nunca es el dinero»; «cuando alguien oye “límite de autoridad” piensa en un importe […]
en muchos negocios ni siquiera es la principal»; «mucha gente cree que ha aprobado algo cuando lo
que hizo fue enterarse a tiempo»; y «hay un exceso simétrico y **hace igual daño**», que afirmaba
una equivalencia de perjuicio que nadie ha medido. Las demás quedaron clasificadas como
definiciones del libro, límites del método, negaciones deliberadas o material del caso. En la
herramienta 8 se revisó además un superlativo sobre sus propios campos.

**Capítulo 9: tres referencias externas, ninguna con cifras.** Es el capítulo insignia y el
que más tentación tenía de convertirse en revisión académica. Se cita poco y cada fuente hace
un trabajo concreto; ninguna está ahí de adorno.

| Cap. | Afirmación en el texto | ID | Tipo | Estado |
|---|---|---|---|---|
| 9 | «Existe desde hace décadas un campo dedicado a sacar a la luz lo que saben las personas expertas, repartido entre disciplinas muy distintas. Una revisión metodológica publicada en 1995 en *Organizational Behavior and Human Decision Processes* agrupa esas técnicas, **a efectos de exposición**, en tres familias: analizar las tareas que la persona hace habitualmente, entrevistarla de varias maneras y plantearle **tareas preparadas que dejan ver su razonamiento sin preguntarle por ese razonamiento**.» | **F-028** | Descripción atribuida a la fuente | Cerrada. Publicación y año declarados en el texto. **Dentro del nivel de lectura**: las tres familias constan verbatim en el resumen leído, y el texto **reproduce la cautela de los propios autores** —«a efectos de exposición»— en lugar de presentarlo como taxonomía cerrada. **No se usa nada por debajo de las tres familias**, ni la comparación empírica entre técnicas, ni las recomendaciones: no se han leído. |
| 9 | «Que exista una familia entera construida así **no demuestra** que preguntar “¿por qué?” sea un error —la fuente no dice tal cosa y nosotros tampoco—, pero sí enseña algo aprovechable: hay más maneras de llegar al criterio que la pregunta directa.» | **F-028** | **Delimitación expresa del alcance de la fuente** | Cerrada. Es la aplicación literal del preflight de la Etapa 3.8B: la fuente acredita que **existen** métodos que no dependen de la pregunta directa, y **no acredita** que esa pregunta sea incorrecta ni que produzca racionalización. El capítulo lo dice en voz alta en lugar de dejarlo implícito. |
| 9 | «Un análisis de Michael Eraut publicado en 2000 en el *British Journal of Educational Psychology* describe el desempeño profesional como secuencias de acción rutinizada interrumpidas por decisiones intuitivas rápidas, y sitúa entre lo tácito precisamente las reglas que sostienen esas decisiones.» | **F-029** | Hallazgo conceptual atribuido | Cerrada. Autor, publicación y año declarados. Corresponde a dos fragmentos verbatim del resumen depositado por el editor: «sequences of routinised action punctuated by rapid intuitive decisions» y «the tacit rules that underpin intuitive decision-making». **Se usa para defender la intuición, no para desacreditarla**, que es lo que la fuente permite. |
| 9 | «El equilibrio entre decidir de manera intuitiva, analítica o deliberada **depende del tiempo disponible, de la experiencia y de la complejidad**.» | **F-029** | Hallazgo conceptual atribuido | Cerrada. Verbatim en el resumen del editor: «The balance between these modes depends on time, experience and complexity». Es lo que justifica la cuarta columna del Manual. |
| 9 | «El conocimiento tácito es problemático en dos frentes distintos: **detectarlo y representarlo**. Son dos trabajos, no uno.» | **F-029** | Hallazgo conceptual atribuido | Cerrada. Verbatim: «with respect to both detecting it and representing it». Sostiene la constante registrada en `06-control-de-continuidad.md` y, con ella, el derecho del lector a escribir «no sé explicarlo todavía». |
| 9 | «Una revisión sistemática de la investigación sobre conocimiento en pequeñas y medianas empresas, publicada en 2005 en el *International Journal of Management Reviews*, concluye que las cualidades del conocimiento en esos negocios **se resisten a tratarse como un activo separable y material**.» | **F-033** | Hallazgo atribuido, **usado como contrapeso** | Cerrada. Publicación y año declarados. Verbatim del resumen depositado por el editor: «qualities that resist conceptualization as some form of separable, material asset». Entra precisamente para **impedir** que el capítulo prometa vaciar una mente en un papel. **No se le hace decir que el conocimiento no pueda transferirse**, que es lo que la fuente no autoriza. |

**Cuatro fuentes disponibles que el capítulo 9 decidió NO citar**, y por qué. Se registra
porque la decisión de no citar es tan sujeta a control como la de citar (D-013).

| Fuente | Por qué estaba disponible | Por qué no se cita |
|---|---|---|
| **F-027** (método del incidente crítico, 1989) | Es el origen de tres piezas del diseño: trabajar sobre un incidente concreto, extraer señales de decisión y juzgar la tipicidad del caso. | **Su fila depende de un registro agregado para todo el contenido**: el depósito del editor no incluye resumen. Citarla en el manuscrito para un detalle concreto rozaría la regla del propio proyecto de no verificar en agregadores. **Solución adoptada:** las tres piezas se presentan como **diseño del Método LEGADO**, sin atribuírselas a nadie, que es exactamente lo que son en el texto. No se abrió investigación nueva para salvar la cita. |
| **F-030** (revisión de técnicas, 1994) | Documenta que el campo está disperso entre nueve disciplinas. | **V-59.** Sus categorías no se han obtenido y no deben confundirse con las tres familias de F-028. Lo que aportaría —la dispersión del campo— ya lo sostiene F-028 con su propio resumen leído. **Citarla sería una segunda fuente para lo mismo**, es decir, decoración. |
| **F-031** (ACTA, 1998) | Precedente de simplificar un método experto para quien no es especialista, y respaldo de consolidar en una sola tabla. | **No hacía falta.** El capítulo no afirma que ACTA funcione —su evaluación no se ha leído— y la idea de simplificar se sostiene sola como decisión del libro. Se prefirió no cargar el capítulo con una referencia que no cambiaba ninguna frase. |
| **F-016** (Nonaka, 1991) | Conocimiento tácito y dificultad de formalizar. | **Es del capítulo 2 y allí está desarrollado.** El 9 remite al fenómeno sin reabrirlo ni volver a citarlo, según el deslinde 2-9. |

**Control de universalidades del capítulo 9, ejecutado el 2026-09-08.** Se aplicó el control
de dos pasos del apartado 3: búsqueda literal como clase abierta más lectura dirigida de cada
aparición. Treinta y dos apariciones; veintiocho quedaron clasificadas como definiciones,
negaciones deliberadas, instrucciones del ejercicio o afirmaciones acotadas a lo leído.
**Cuatro se corrigieron** por ser afirmaciones sobre el mundo sin respaldo: «casi todo el mundo
intenta primero», «una palabra que suele decirse como si fuera una excusa», «suele contestarse
mucho mejor que un por qué» y el superlativo «es la pregunta que más rinde». En la herramienta
7 se corrigieron otras tres: «todos son mejores que pensar en abstracto», «los rechazos suelen
tener el criterio más a la vista que los síes» y «dos casos nunca son idénticos».

**Capítulo 5: tres referencias, todas en un solo apartado y ninguna con cifras.**

| Cap. | Afirmación en el texto | ID | Tipo | Estado |
|---|---|---|---|---|
| 5 | «diez profesionales autónomos ya jubilados… ninguno de los diez dejó de trabajar cuando empezó a cobrar la prestación… jubilarse no supuso desvincularse del trabajo, sino una transformación del papel de trabajador… esa desvinculación no tiene por qué ser brusca» | **F-024** | Hallazgo cualitativo atribuido | Cerrada. **Única fuente de Q-09 leída íntegra.** El texto declara el tamaño (diez), el país (implícito como «un país concreto») y **reproduce la limitación de los propios autores**: no pretenden resultados generalizables. |
| 5 | «un trabajo publicado en 2020 en el *Journal of Small Business Management* describe el retiro del empresario como una decisión voluntaria sobre la que tiene un control considerable, con inclinación al retiro parcial, y observa que la identidad empresarial influye» | **F-018** | Hallazgo atribuido | Cerrada. Se atribuye expresamente al trabajo, con año y publicación. **Solo se dice lo que consta en el resumen**, que es lo único a lo que se tuvo acceso. Sin cifras. |
| 5 | «Un estudio sobre registros administrativos finlandeses encontró que quienes trabajaban por su cuenta sin empleados seguían trayectorias más uniformes que los propietarios de empresa, ajustadas a la normativa de pensiones de aquel país» | **F-025** | Hallazgo atribuido, **usado como contrapeso** | Cerrada. Entra precisamente para **impedir** la afirmación de que trabajar solo dé más libertad, que es lo que prohíbe V-56A. País declarado en la frase. Sin cifras. |

**Ninguna afirmación regional.** El capítulo no dice nada sobre países hispanohablantes, y por
eso **no necesita declarar el vacío de V-56B**: la solución adoptada fue no hacer
afirmaciones regionales, no advertir de su ausencia.

**El principio central del capítulo no se atribuye a nadie.** El texto dice literalmente:
«Esto no es un hallazgo de nadie ni una conclusión de ninguna investigación. Es la propuesta
de este libro».

**Capítulo 4: cero referencias externas, y todas las cifras clasificadas.** El capítulo habla
necesariamente de cantidades, así que se le aplicó una regla más estricta: **toda cifra del
texto está clasificada** en A (dato real del lector), B (ejemplo ficticio identificado), C
(valor de la herramienta) o D (afirmación sobre el mundo, que exigiría fuente).

| Categoría | Qué hay en el capítulo 4 |
|---|---|
| **A** | Ninguna. Las cifras del lector las pone el lector en su hoja. |
| **B** | Solo los recuentos del caso C-05: seis encargos, cuatro aplazados, uno perdido, uno sin decidir, dos semanas de recuperación. **Sin moneda y sin importes.** |
| **C** | La ventana de una semana, los seis estados, los cinco pasos, las cinco reglas y la orientación de diez o quince entradas, declarada expresamente como recomendación y no como umbral. |
| **D** | **Ninguna.** No se afirma nada sobre costos de interrupción, pérdida de clientes, productividad ni pequeñas empresas, y por eso el capítulo no necesita ninguna fuente. |

**Cero símbolos de moneda y cero importes en todo el capítulo**, comprobado por búsqueda. La
regla se declara además dentro del propio texto: cuando no hay cifra real se escribe «no
medido», que no es cero ni es una pérdida.

**Afirmaciones sin fuente en el manuscrito.** Todas las demás son observaciones
cualitativas, inferencias del autor, recomendaciones o propuestas propias del libro, y
están escritas en la forma reconocible que exige el apartado 2. Ninguna incluye cifras.

**Revisión 2.1 del 2026-09-07.** Se depuraron además once enunciados que, sin ser cifras,
tenían forma de afirmación empírica de frecuencia sin fuente que los respaldara —«casi
todos», «la mayoría», «es el caso normal», «es lo más habitual», «el resultado más
frecuente»—. Ninguno tenía fila en esta tabla, porque ninguno llevaba cifra; el problema
era de forma, no de dato. El detalle está en `revision/control-de-calidad-etapa-2.md`,
apartado «Revisión intermedia 2.1». **Regla añadida para la Etapa 3:** un enunciado de
frecuencia sin fuente se escribe como observación cualitativa o no se escribe, y en ningún
caso con la apariencia de un hallazgo.

### Regla corregida el 2026-09-07 (Etapa 3.1.1)

**La búsqueda literal no cierra el control de frecuencias.** En el capítulo 2 el control
automático informó de cero enunciados de frecuencia y la lectura humana encontró cinco. El
fallo no fue del texto sino del control: buscaba una **lista cerrada de cadenas** —«casi
todos», «la mayoría», «suele», «normalmente»— y no contenía «rara vez», «habitualmente», «a
menudo» ni «casi todo», que son la misma clase de enunciado.

**Regla mínima, obligatoria desde el capítulo 3.** El control tiene dos pasos y el segundo no
es opcional:

1. **Búsqueda literal**, con la lista tratada como *ejemplos de una clase*, nunca como lista
   cerrada. Se añaden al menos: rara vez, raras veces, a menudo, con frecuencia,
   habitualmente, generalmente, típicamente, de ordinario, por lo común, lo normal, casi
   todo, muchas veces, pocas veces, lo bastante, **tanta gente, mucha gente, todo el mundo**.
   Estas tres últimas se añadieron el 2026-09-07: la lectura dirigida del capítulo 4 encontró
   «por qué tanta gente lo confunde con marcharse», que la búsqueda literal no había visto.
   **Es la segunda vez que la lista cerrada falla y la lectura dirigida acierta**, que es
   exactamente para lo que existe el paso 2.
2. **Lectura dirigida**: recorrer toda frase que **atribuya una propiedad al mundo** y no sea
   ni cita ni parte de un caso, y clasificarla en cuatro categorías:

| | Qué es | Qué se hace |
|---|---|---|
| **A** | La respalda una fuente registrada | Se conserva |
| **B** | Pertenece a una cita o a un caso ficticio | Se conserva; no es una afirmación del libro |
| **C** | Innecesaria | Se suprime |
| **D** | Reformulable sin afirmar frecuencia | Se reescribe |

**Lo que no cuenta como enunciado de frecuencia**, para no volver a discutirlo en cada
capítulo: las preguntas al lector sobre su propia conducta, los condicionales explícitos
sobre su situación («es posible que ya lo tenga documentado») y las negaciones definitorias
(«ninguna de las cuatro depende de tener equipo»).

## 4. Registro de menciones a productos y marcas

Toda mención de una herramienta, plataforma o marca concreta se anota aquí para poder
revisarlas todas juntas antes de publicar. Norma vigente (D-011): solo como ejemplo de
una categoría, siempre con al menos una alternativa, nunca con configuraciones ni
enlaces.

*Vacía. Ninguna marca, producto ni plataforma se menciona en la introducción, en el
capítulo 1 ni en el Índice de Dependencia de la Persona Clave. D-011 se cumple sin excepciones.*

| Cap. | Mención | Categoría a la que ilustra | Alternativa citada | Justificación |
|---|---|---|---|---|
| — | — | — | — | — |

## 5. Comprobación de la Etapa 4

1. Recuento de `[POR VERIFICAR]` restantes. Debe ser cero.
2. Toda cifra del manuscrito tiene una fila en la tabla del apartado 3.
3. Ninguna afirmación importante depende de una sola fuente.
4. Ninguna fuente citada tiene una fecha de consulta anterior a doce meses sin
   recomprobar su vigencia.
5. Toda mención de marca cumple D-011.
6. Los avisos de alcance aparecen en preliminares, en los capítulos 10 y 16 y al pie de
   cada herramienta.
