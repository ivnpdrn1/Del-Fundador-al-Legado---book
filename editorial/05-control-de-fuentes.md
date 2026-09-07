# 05 — Control de fuentes en el manuscrito

**Etapa:** 1 — Fundamentos. Con registros desde la Etapa 2.
**Estado:** vigente. Siete afirmaciones registradas, todas cerradas. Cero marcas
`[POR VERIFICAR]` en el manuscrito.

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
| 2 | «podemos saber más de lo que podemos decir», atribuida a Michael Polanyi. | F-016 (donde se leyó) + F-017 (corrobora obra y frase) | Cita atribuida | 2026-09-07 | Cerrada. **Conservada tras la revisión 3.1.1** como la única cita memorable que justifica serlo. **No se ha leído el libro de Polanyi**; la frase se leyó citada en F-016 y se corroboró en la ficha del editor (F-017), que la reproduce como frase inicial de *The Tacit Dimension*. El texto la atribuye a Polanyi **a través de Nonaka**, que es como se leyó. No se le atribuye ninguna otra idea, **no se cita número de página** y el capítulo no menciona ningún contenido del libro de Polanyi. |

**Recuento de referencias externas por pieza.** Introducción: cinco fuentes distintas
(F-001, F-002, F-003, F-004, F-012), en seis afirmaciones. Capítulo 1: una (F-002).
Capítulo 2: dos (F-016 y F-017), concentradas en un solo apartado, sin ninguna cifra y, tras
la revisión 3.1.1, con una sola cita textual breve. El
máximo orientativo del plan de investigación es de tres por capítulo; la introducción lo
excede de forma deliberada y por una sola vez, porque es allí donde se explica al lector
por qué el libro no dará cifras y esa explicación exige mostrar las fuentes que sí
resisten. **No se repetirá en ningún capítulo.**

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
   todo, muchas veces, pocas veces, lo bastante.
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
