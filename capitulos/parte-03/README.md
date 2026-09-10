# Parte III — Construir una mano derecha digital

Capítulos 11 a 16. **Producción iniciada y terminada el 2026-09-09. Los seis capítulos están escritos.** **Con el capítulo 16 se cierra también la etapa A del Método LEGADO**, que ocupa esta parte entera.

Las dos partes anteriores sirvieron para **mirar** y para **trabajar**: cuánto depende el
negocio de una persona, qué es exactamente lo que depende, cómo se documenta y quién puede
decidir con ello. Esta parte introduce la tecnología, y lo hace en el orden que el libro
defiende: **primero se ordena, después se asiste**.

## Capítulos

| # | Capítulo | Etapa | Entregable | Estado |
|---|---|---|---|---|
| 11 | Ordenar antes de automatizar | **A, con G como requisito** | Lista de información que no debe entregarse libremente a una inteligencia artificial (9) | **borrador** |
| 12 | La inteligencia artificial como aprendiz | A | **Cuadro de lo que puede y lo que no puede hacer — dentro del capítulo, no es una de las 18** | **borrador** |
| 13 | El periodo de sombra y las primeras alertas | A | Lista de verificación del modo sombra (10) y Modelo de alertas críticas (11) | **borrador** |
| 14 | De las alertas a las recomendaciones | A | **Formato de recomendación explicada — dentro del capítulo, no es una de las 18** | **borrador** |
| 15 | Autonomía limitada y aprobación humana | A | Matriz de niveles de autonomía (12) | **borrador** |
| 16 | Seguridad, privacidad y auditoría | A | **Lista de comprobación de seguridad básica — dentro del capítulo, no es una de las 18 (D-078)** | **borrador** |

El índice completo, con la idea central y el presupuesto de palabras de cada capítulo, vive en
`editorial/03-indice-maestro.md`. Aquí no se duplica.

## Frontera con la Parte II

El capítulo 10 cerró **quién puede decidir y hasta dónde**. El capítulo 11 contesta la otra
mitad: **con qué información se decide, cuál manda y cuál no debería salir sin pensarlo**.

**Con eso queda completa la etapa G del método** —G-1, gobernanza de decisiones, en el capítulo
10; **G-2, gobernanza de información, en el 11**—. Y conviene decir qué significa eso y qué no:
significa que **existe una base gobernada suficiente para empezar a asistir la operación con
tecnología**. **No** significa que el negocio esté documentado entero, ni para siempre.

## Frontera dentro de la parte

- **11** — ¿con qué información se decide, y qué puede ver una herramienta externa?
- **12** — ¿qué clase de ayudante es una inteligencia artificial, y cuál no es?
- **13** — ¿qué pasa cuando observa sin decidir?
- **14** — ¿cuándo puede pasar de avisar a recomendar?
- **15** — ¿hasta dónde puede llegar sola, y quién aprueba?
- **16** — ¿cómo se protege y cómo se comprueba lo que hace?

**El capítulo 11 no enseña inteligencia artificial**, y es deliberado: el primer acto de la
parte que trata de la tecnología es **no entregarle nada todavía**. Nombra la IA porque la
herramienta 9 decide qué se le puede entregar, pero no explica modelos, ni instrucciones, ni
autonomía. El cambio pedagógico lo hace el capítulo 12.

## Qué hace el capítulo 12, y qué deja para después

Establece el marco que gobierna los cuatro capítulos siguientes: **la capacidad la trae la
herramienta; el permiso lo decide el negocio**, y se decide **por tarea**. Define qué es una
inteligencia artificial en términos de función, delimita la metáfora del aprendiz en su primera
aparición, presenta la escala de siete niveles **declarándola como diseño de este proyecto y no
como estándar**, y advierte con fuente que **juntar persona y sistema no garantiza un resultado
mejor**.

**Lo que no hace:** no desarrolla el modo sombra (13), ni las recomendaciones y su evidencia
(14), ni la ejecución y la aprobación (15), ni la seguridad (16). **Y no usa inteligencia
artificial:** aquí se explica, no se prueba. No hay demostración, ni instrucción para el lector,
ni una sola marca, modelo o proveedor en todo el capítulo.

**Su entregable no es una de las dieciocho herramientas.** El *Cuadro de lo que puede y lo que
no puede hacer* se rellena dentro del propio capítulo, con su tabla de columnas y una fila de
ejemplo completa. No hay archivo en `recursos/` y **el catálogo sigue en 9 de 18**.

## Qué hace el capítulo 16, y con qué cierra la parte

Contesta las cuatro preguntas con que termina el 15 —**quién puede ver qué, qué queda
registrado, dónde están los datos y qué pasa si algo falla**— y las trata como lo que son:
**preguntas de gobierno, no de tecnología**. Separa cuatro palabras que se usan como
sinónimos —**seguridad, privacidad, confidencialidad y auditoría**— y añade una quinta que no
es ninguna de ellas, **continuidad**. Y deja escrita la regla que gobierna todo el capítulo:
**auditar es poder reconstruir, no registrarlo todo.**

**Su entregable no es una de las dieciocho herramientas.** La *Lista de comprobación de
seguridad básica* —ocho preguntas, cinco respuestas posibles y una columna de «qué voy a
hacer»— **se rellena dentro del propio capítulo** (D-078). No hay archivo en `recursos/` y
**el catálogo sigue en 12 de 18**.

**Lo que no hace, y es lo más importante:** **no enseña ciberseguridad**. No nombra cifrado,
doble factor, cortafuegos, antivirus ni ningún producto; **no fija ninguna periodicidad** para
copias ni revisiones; **no dice de quién son los datos** que guarda un proveedor, porque es
una pregunta jurídica que depende del contrato y del país; y **enumera expresamente las ocho
cosas que no promete**, empezando por que su negocio quede seguro. Donde hace falta un
profesional, **remite y enseña qué preguntarle** (D-033).

## Con qué cierra la Parte III

Con una frase que el lector debería poder decir al terminarla: **la tecnología ya puede
ayudarme sin que yo le haya entregado el control.** Y con una pregunta que **no se contesta
aquí** y que abre la Parte IV: *¿qué ocurre cuando quienes tienen que trabajar con todo esto
son otras personas?*

## La plataforma

El capítulo 11 contiene, al final y en una sección delimitada, **la primera presentación de la
plataforma en todo el libro** (momento M3 de `editorial/16-libro-metodo-y-plataforma.md`).
Está escrita **en futuro de proyecto**, sin afirmar que exista ni que garantice nada, **sin
nombre comercial** y **sin ninguna llamada a la acción**. Y con una frase que no admite lectura
ambigua: **este libro está completo sin ella.**
