# 16 — Libro, método y plataforma

**Etapa:** 2.5 — Arquitectura del ecosistema
**Estado:** vigente y obligatorio. **Norma editorial**, no documento de producto.

Este documento existe para una sola cosa: **proteger el libro del producto**. La
arquitectura de la plataforma vive en `producto/`. Aquí solo están las reglas que el
manuscrito debe cumplir, y que se comprueban en la Etapa 4 como cualquier otra norma.

---

## 1. La regla que gobierna todas las demás

> **El libro debe ser completo, útil y accionable aunque el lector nunca utilice la
> plataforma.**

No es una aspiración: es un criterio de aceptación. Un capítulo que no se sostenga sin la
plataforma vuelve a revisión.

**Consecuencias, todas ellas prohibiciones:**

1. **No se esconde contenido necesario detrás de una suscripción.** D-010 ya lo exigía para
   los servicios; se extiende a la plataforma.
2. **No se retira ninguna de las dieciocho herramientas del libro** ni se publica mutilada
   para empujar hacia el software. Las dieciocho siguen siendo utilizables en papel.
3. **Ningún capítulo se escribe como publicidad.**
4. **No se fabrica una necesidad.** Si la plataforma resuelve algo, es porque el lector ya
   ha topado con ese problema haciendo los ejercicios.
5. **Ningún ejercicio termina en una llamada a comprar.**
6. **No se usa el miedo al retiro, a la enfermedad ni a la ausencia para vender
   tecnología.** Esto ya estaba prohibido para el libro; se extiende al producto.

**Reparto de papeles, para que ninguna pieza invada a otra:**

| Pieza | Responde a |
|---|---|
| El libro | **Qué** y **por qué** |
| El Método LEGADO | **Cómo** |
| La plataforma | Ayuda a **hacerlo** |

## 2. Principio narrativo: la necesidad antes que la solución

La plataforma **no se presenta al comienzo**. El lector tiene que llegar por sí mismo a la
pregunta *«¿cómo organizo todo esto?»*, y esa pregunta solo es sincera después de haber
producido material suficiente para que organizarlo duela.

Recorrido de descubrimiento, con el capítulo donde ocurre cada paso:

| # | Lo que el lector descubre | Dónde |
|---|---|---|
| 1 | Que existe dependencia | 1 |
| 2 | Cuánto depende el negocio de él | 1 + herramienta 1 |
| 3 | Qué se perdería si no estuviera disponible | 4 |
| 4 | Que buena parte del negocio vive en conocimiento no transferido | 2 |
| 5 | Que también hay experiencia, criterio, decisiones, excepciones, relaciones y memoria sin transferir | 2, 7, 8, 9 |
| 6 | Que todo eso junto es su ADN Empresarial | Intro, reforzado en 2 |
| 7 | Que ese ADN puede identificarse | 6 |
| 8 | Que puede estructurarse | 7, 8, 9 |
| 9 | Que puede transferirse | 10, 18 |
| 10 | **Que hacerlo a mano se convierte en un proceso complejo y continuo** | **Final de la Parte II** |

**El punto 10 es el que abre la puerta, y no llega antes.** Al terminar el capítulo 9 el
lector tiene cinco documentos vivos —inventario, tres mapas, registro de excepciones y
manual de criterio—, cada uno con fecha, responsable y revisión pendiente. Ahí la pregunta
se hace sola.

## 3. Los cuatro niveles de presencia editorial

Los niveles describen el recorrido del lector. **La regla operativa son las cinco categorías
del apartado 5**, y en caso de discrepancia manda el apartado 5.

| Nivel | Qué se dice | Dónde | Categoría |
|---|---|---|---|
| **1 — Necesidad** | El lector descubre que necesita registrar, documentar, organizar, medir, transferir y verificar. **No se menciona ningún producto ni ninguna herramienta.** | Capítulos 1 a 8, y 10 | **A** |
| **1 bis — Organización explícita** | Se dice que estos documentos necesitan un sitio, una fecha y un responsable. Sigue sin hablarse de herramientas. | Capítulo 6 | **A** |
| **2 — Herramientas** | Se dice que esto puede llevarse en papel, en documentos, en hojas de cálculo, en un repositorio compartido o en un sistema. **Genérico, en plural y sin plataforma concreta.** | Final del capítulo 9 | **B** |
| **3 — Plataforma** | Se presenta que existe —o puede existir— una plataforma diseñada para ejecutar el Método LEGADO. | **Capítulo 11**, una sola vez | **C + D + E** |
| **4 — IA y Gemelo** | Funciones asistidas por IA. **Gemelo de IA solo desde el capítulo 15.** | 12-15; gemelo en 15 | **C** |

## 4. Momentos exactos, decididos

Ninguno de estos se mueve sin registrar una decisión.

**Aviso de nomenclatura.** Los momentos se numeran **M1 a M6** para no confundirlos con las
cinco **categorías A a E** del apartado 5. Momento = cuándo ocurre; categoría = qué clase de
frase es.

| Momento | Cuándo | Forma | Categoría | Extensión máxima |
|---|---|---|---|---|
| **M1. Primera alusión de organización** | Capítulo 6 | Una frase: estos documentos necesitan un sitio, una fecha y un responsable. Sin decir «digital». | **A** | 1 frase |
| **M2. Primera alusión a herramientas o sistemas** | Final del capítulo 9 | Párrafo breve: a partir de aquí el material crece; puede llevarse en papel, en documentos, en un repositorio o en un sistema. **Genérico, en plural, sin marca.** | **B** | 1 párrafo |
| **M3. Presentación explícita de la plataforma** | **Capítulo 11**, sección delimitada al final | Qué es, qué hace, que es opcional y que el libro funciona sin ella. **Primera vez que el libro identifica la plataforma.** | **D** (+ C, + 1 E al cierre) | **450 palabras** |
| **M4. Primera invitación al lector** | Pie de la herramienta 1, en el anexo de recursos | Versión digital gratuita del Índice. **No en el cuerpo del capítulo 1.** | **E** | 2 frases |
| **M5. Primeras funciones de IA** | Capítulos 12 a 15 | Menciones de una frase. El **Asistente del ADN Empresarial** se nombra en el 14, donde ya se exige mostrar la evidencia. | **C** | 1 frase por capítulo |
| **M6. Gemelo de IA** | **Capítulo 15 o posterior. Nunca antes.** | Según D-045 y V-25b. | **C** | — |

**M4 es cronológicamente anterior a M1**, porque el pie de la herramienta 1 se lee al hacer
el ejercicio del capítulo 1. No es una contradicción: el anexo no es un capítulo, y por eso
la invitación no cae bajo la prohibición de los capítulos 1 a 10. Es la única puerta de
entrada temprana, es gratuita y entrega un instrumento que el libro ya publica completo.

**Por qué el capítulo 11 y no la frontera entre las Partes II y III.** Se evaluó esa
frontera, que era la hipótesis de partida, y se descartó por precisión: el capítulo 11 trata
**exactamente** de ordenar la información y de que cada dato tenga una fuente única. La
plataforma no es ahí un producto que se intercala: es el ejemplo natural de lo que el
capítulo está explicando. Además, situarla en el 11 la deja **antes** de los capítulos de
inteligencia artificial, de modo que el lector la conoce como un sitio donde ordenar cosas y
no como un producto de IA. Eso protege la secuencia del libro.

**Por qué la invitación va al pie de la herramienta y no al capítulo 1.** El capítulo 1 es
donde se gana o se pierde al lector. Una invitación en su cuerpo lo convertiría en un embudo. En
el pie de la herramienta, en el anexo, es lo que es: una comodidad opcional para un
instrumento que el libro ya entrega completo.

## 5. Qué cuenta como mención: cinco categorías

**Corregido el 2026-09-07 (Etapa 2.5.1).** La versión anterior de este apartado y de D-053
usaban la palabra «mención» con dos significados distintos y enunciaban la regla como una
prohibición con excepciones, lo que la hacía ambigua. Se sustituye por cinco categorías
definidas y una tabla que dice, para cada capítulo, qué está permitido.

### 5.1 Las cinco categorías

| | Categoría | Qué es | ¿Es una mención de la plataforma? |
|---|---|---|---|
| **A** | **Lenguaje genérico de organización** | Hablar de ordenar, archivar, fechar, asignar un responsable, mantener algo vivo. | **No.** Es contenido del método. |
| **B** | **Alusión funcional a herramientas o sistemas** | Decir que esto puede llevarse en papel, en documentos, en hojas de cálculo, en un repositorio compartido o en un sistema. Genérico y en plural. | **No**, siempre que no identifique ninguna plataforma concreta ni sugiera que existe una nuestra. |
| **C** | **Mención identificable de nuestra plataforma** | Cualquier frase de la que un lector pueda deducir que existe, o existirá, una plataforma de este proyecto. | **Sí.** |
| **D** | **Presentación explícita del producto** | Qué es, qué hace, para qué sirve, que es opcional. | **Sí.** |
| **E** | **Invitación o llamada a la acción** | Enlace, código, «entre en», «regístrese», «pruébelo». | **Sí.** |

**Prueba para distinguir B de C**, cuando haya duda al redactar:

> Si al leer la frase el lector puede pensar *«ah, entonces estos autores tienen una
> herramienta»*, es **C**. Si solo puede pensar *«tendré que buscar dónde guardar esto»*, es
> **B**.

En caso de duda irresoluble, la frase se trata como **C** y se aplica la restricción más
severa.

### 5.2 Qué está permitido en cada capítulo

Regla enunciada en positivo, para que no haga falta interpretar excepciones.

| Capítulos | A | B | C | D | E |
|---|---|---|---|---|---|
| **1 a 5** | ✅ siempre | ❌ | ❌ | ❌ | ❌ |
| **6** | ✅ **incluida la alusión decidida**: estos documentos necesitan un sitio, una fecha y un responsable | ❌ | ❌ | ❌ | ❌ |
| **7, 8, 10** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **9** | ✅ | ✅ **una vez**, el párrafo neutro del final | ❌ | ❌ | ❌ |
| **11** | ✅ | ✅ | ✅ | ✅ **1 vez, 450 palabras máximo** | ✅ **1** |
| **12, 13, 14, 15** | ✅ | ✅ | ✅ **1 frase por capítulo** | ❌ | ❌ |
| **16** | ✅ | ✅ | ❌ | ❌ | ❌ |
| **17, 18, 20, 21, 22, 23, 25** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **19 y 24** | ✅ | ✅ | ✅ **1 frase por capítulo** | ❌ | ❌ |
| **Pie de la herramienta 1**, en el anexo | ✅ | ✅ | ✅ | ❌ | ✅ **1** |
| **Anexo de recursos** | ✅ | ✅ | ✅ | ❌ | ✅ **1** |
| **Conclusión** | ✅ | ❌ | 0 o 1, **a decidir en la Etapa 3** (V-30b) | ❌ | ❌ |

### 5.3 La regla de los capítulos 1 a 10, sin ambigüedad

> **En los capítulos 1 a 10 no hay ninguna mención identificable de nuestra plataforma,
> ningún nombre de producto, ninguna venta y ninguna llamada a la acción.** Es decir: **cero
> de C, cero de D y cero de E.**
>
> Lo que sí puede haber: **A en cualquiera de ellos**, y **B una sola vez, en el capítulo 9**.

Esto no es una excepción a la prohibición: es que **A y B no son menciones de la
plataforma**. La alusión del capítulo 6 es categoría A —habla de organizar documentos, no de
herramientas— y el párrafo del capítulo 9 es categoría B —nombra opciones genéricas en
plural, ninguna nuestra—.

### 5.4 Presupuesto numérico

| Tipo | Máximo en todo el manuscrito |
|---|---|
| **D — presentación explícita** | **1** (capítulo 11) |
| **E — invitaciones** | **3** (pie de la herramienta 1; final de la sección del capítulo 11; anexo de recursos) |
| **D + E, más la posible línea de la conclusión** | **5 menciones destacadas** |
| **C — menciones identificables de una frase** | **7** (11, 12, 13, 14, 15, 19, 24) |
| **B — alusiones funcionales** | 1 en el capítulo 9; libres en los capítulos 11 a 16, 19 y 24 |
| **A — lenguaje de organización** | Sin límite. Es contenido del libro. |

**Se cuentan en la Etapa 4 (V-26b) y un exceso vuelve a revisión.**

### 5.5 Prohibiciones que no dependen del capítulo

1. Llamada a la acción al final de un capítulo que no sea el 11.
2. Mencionar la plataforma en el pie de una herramienta que no sea la 1.
3. Cualquier C, D o E en los capítulos 1 a 10, 16, 17, 18, 20, 21, 22, 23 y 25.
4. Cualquier B en los capítulos 1 a 8, 10, 17, 18, 20, 21, 22, 23 y 25.

## 6. Cómo se escribe cuando se menciona

1. **Se nombra por su función**, no por su marca: «una plataforma que guía el Método
   LEGADO». La marca comercial no está decidida (D-061) y el libro no la necesita.
2. **Siempre acompañada de su carácter opcional**, en la misma frase o en la siguiente.
3. **Nunca en una promesa de resultado.** Ni «con la plataforma conseguirá», ni equivalentes.
4. **Nunca como requisito** de ningún ejercicio del libro.
5. **En minúsculas y de forma descriptiva**, igual que las demás expresiones propias del
   proyecto (D-036).
6. **Sin capturas de pantalla, sin precios y sin descripciones de funciones concretas**, que
   caducarían antes que el libro. La regla de D-011 sobre productos se aplica también aquí,
   incluido el producto propio.

## 7. El software se adapta al método, nunca al revés

> **No se cambia la metodología para facilitar el software.**

Si en algún momento una herramienta del libro resulta incómoda de implementar, **se
implementa peor, no se simplifica la herramienta**. Primero el mejor método; después la
tecnología que lo ejecuta.

Corolario para la Etapa 3: **ningún capítulo puede escribirse pensando en cómo quedará en
pantalla.** Si al redactar aparece la tentación de simplificar un ejercicio para que sea más
fácil de digitalizar, la tentación se anota en `producto/` como restricción del software y
el capítulo se escribe como debe ser.

## 8. Control de no distracción

Pregunta obligatoria antes de dar por buena cualquier mención, en la Etapa 3 y en la 4:

> **¿Este pasaje mejora el libro para un lector que nunca va a usar la plataforma?**

Si la respuesta es no, se elimina. No se reescribe: se elimina.

Señales de alarma que obligan a revisar:

- Un capítulo introduce un concepto tecnológico antes de lo previsto para poder mencionar la
  plataforma.
- Un ejercicio queda incompleto en papel.
- La palabra «plataforma» aparece en un capítulo no autorizado por el apartado 5.
- Un pasaje describe funciones concretas del producto.
- El cierre de un capítulo empuja en lugar de cerrar.

## 9. Comprobaciones de la Etapa 4

1. Recuento de menciones contra el presupuesto del apartado 5.
2. Ninguna mención en capítulos prohibidos.
3. La presentación explícita no supera las 450 palabras y está en el capítulo 11.
4. El Gemelo de IA no aparece antes del capítulo 15 (V-25b).
5. Las dieciocho herramientas siguen completas y utilizables en papel (V-38).
6. Ninguna mención dentro de una promesa de resultado.
7. Ninguna captura, precio ni descripción de funciones concretas.
8. La pregunta del apartado 8 se responde afirmativamente para cada mención.
9. Lectura seguida de la Parte II a la Parte III comprobando que la aparición de la
   plataforma no rompe el tono.
10. **Clasificación de cada aparición según las cinco categorías del apartado 5.1**, y
    contraste con la tabla del 5.2. Una frase mal clasificada como B cuando es C es el
    error más probable de la Etapa 3.
