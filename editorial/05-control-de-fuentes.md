# 05 — Control de fuentes en el manuscrito

**Etapa:** 1 — Fundamentos. Con registros desde la Etapa 2.
**Estado:** vigente. Ocho afirmaciones registradas, todas cerradas. Cero marcas
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

Seis afirmaciones con fuente en las dos piezas escritas. Ninguna cifra sin fila en esta
tabla.

| Cap. | Afirmación en el texto | ID de fuente | Tipo de enunciado | Verificado el | Estado |
|---|---|---|---|---|---|
| Intro | «El estudio en que se apoya identificó más de 90 definiciones distintas de empresa familiar, y advierte que las cifras varían entre estudios porque dependen de la definición que se emplee.» | F-001 | Hecho verificable | 2026-09-06 | Cerrada |
| Intro | «Ese mismo informe europeo sitúa a las empresas familiares en más del 60 % de todas las empresas europeas.» | F-001 | Hecho verificable | 2026-09-06 | Cerrada. Ámbito europeo declarado en el texto. |
| Intro | «El 27,3 % de las empresas eran familiares [en Estados Unidos, 2021] y daban empleo al 34,1 % de los trabajadores; allí se considera familiar una empresa cuando dos o más miembros de una familia poseen la mayoría del negocio.» | F-002 | Hecho verificable | 2026-09-06 | Cerrada. País, año y definición declarados en el texto. |
| Intro | «En América Latina ni siquiera existe una definición común de micro, pequeña y mediana empresa, y la información disponible es escasa y a menudo de mala calidad.» | F-004 | Hecho verificable | 2026-09-06 | Cerrada. Ámbito y fuente declarados en el texto. |
| Intro | «La Comisión Europea, al analizar en 2006 la transmisión de empresas en la Unión Europea, señaló que cuando una compañía cierra únicamente por problemas en la fase de traspaso se destruye conocimiento, contactos establecidos y otros activos intangibles.» | F-003 | Hecho verificable | 2026-09-06 | Cerrada. Institución, año y ámbito declarados en el texto. |
| Intro | «Veinte años después, la misma institución sigue advirtiendo de que un número creciente de propietarios se acerca al retiro sin sucesor designado.» | F-012 | Hecho verificable | 2026-09-06 | Cerrada. Sin cifras, por decisión: la fuente no las aporta. |
| 1 | «Según la Oficina de Defensa de la Pequeña Empresa, con datos censales de 2021, el 57,9 % de las empresas familiares del país tenía más de diez años de vida.» | F-002 | Hecho verificable | 2026-09-06 | Cerrada. País y año declarados en el texto. |

**Recuento de referencias externas por pieza.** Introducción: cinco fuentes distintas
(F-001, F-002, F-003, F-004, F-012), en siete afirmaciones. Capítulo 1: una (F-002). El
máximo orientativo del plan de investigación es de tres por capítulo; la introducción lo
excede de forma deliberada y por una sola vez, porque es allí donde se explica al lector
por qué el libro no dará cifras y esa explicación exige mostrar las fuentes que sí
resisten. **No se repetirá en ningún capítulo.**

**Afirmaciones sin fuente en el manuscrito.** Todas las demás son observaciones
cualitativas, inferencias del autor, recomendaciones o propuestas propias del libro, y
están escritas en la forma reconocible que exige el apartado 2. Ninguna incluye cifras.

## 4. Registro de menciones a productos y marcas

Toda mención de una herramienta, plataforma o marca concreta se anota aquí para poder
revisarlas todas juntas antes de publicar. Norma vigente (D-011): solo como ejemplo de
una categoría, siempre con al menos una alternativa, nunca con configuraciones ni
enlaces.

*Vacía. Ninguna marca, producto ni plataforma se menciona en la introducción, en el
capítulo 1 ni en el Índice de Dependencia del Fundador. D-011 se cumple sin excepciones.*

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
