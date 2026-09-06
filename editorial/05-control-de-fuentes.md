# 05 — Control de fuentes en el manuscrito

**Etapa:** 1 — Fundamentos
**Estado:** estructura creada. **Sin registros**, porque no existe manuscrito.

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

*Vacía. Se llenará a partir de la Etapa 2.*

| Cap. | Afirmación en el texto | ID de fuente | Tipo de enunciado | Verificado el | Estado |
|---|---|---|---|---|---|
| — | — | — | — | — | — |

## 4. Registro de menciones a productos y marcas

Toda mención de una herramienta, plataforma o marca concreta se anota aquí para poder
revisarlas todas juntas antes de publicar. Norma vigente (D-011): solo como ejemplo de
una categoría, siempre con al menos una alternativa, nunca con configuraciones ni
enlaces.

*Vacía.*

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
