---
capitulo: 16
parte: 3
titulo: "Seguridad, privacidad y auditoría"
etapa_metodo: "A"
estado: borrador
palabras: 2138
casos_usados: []
recursos_producidos: []
afirmaciones_por_verificar: []
ultima_actualizacion: "2026-09-09"
---

# 16. Seguridad, privacidad y auditoría

El capítulo anterior terminó preguntando quién puede ver todo esto, qué queda registrado, dónde
están los datos y qué pasa cuando algo falla.

Son cuatro preguntas y ninguna es técnica. Son las cuatro que hay que contestar **antes de dejar
que una tarea siga funcionando sola**.

## Lo que aparece un martes cualquiera

Una empresa pequeña con equipo tenía una tarea funcionando desde hacía meses: se ejecutaba, se
registraba, y nadie tenía que mirarla. Una persona dejó el negocio en buenos términos y todo
siguió igual.

Semanas después, alguien preguntó por qué en el registro aparecía siempre el mismo nombre. La
tarea llevaba desde el principio funcionando **con la cuenta de esa persona**, que fue quien la
puso en marcha. No pasó nada malo. Pero nadie había decidido que aquello dependiera de una
cuenta que ya no debería existir.

Esa es la idea de este capítulo, y no es una advertencia sobre tecnología:

> **Automatizar una tarea también crea una responsabilidad de gobierno.** No una tecnología más
> que aprender: **cuatro preguntas que contestar antes de dejarla seguir.**

## Cuatro palabras que no significan lo mismo

Se usan como sinónimos y no lo son. **Estas son definiciones de trabajo de este libro**, no
definiciones legales ni profesionales, y sirven solo hasta donde el capítulo las necesita.

| | Contesta a |
|---|---|
| **Seguridad** | Que solo pueda ver y hacer lo previsto **quien deba**, y que se pueda volver a funcionar si algo se rompe |
| **Privacidad** | Qué puede hacerse con información **de personas** |
| **Confidencialidad** | Lo que se debe **a otro**: por un contrato, por una relación o por un secreto del negocio |
| **Auditoría** | **Poder reconstruir qué ocurrió y comprobar si se actuó dentro del permiso** |

Y hay una quinta que no es ninguna de las cuatro: **continuidad**, que es que el negocio siga
funcionando mientras el problema se resuelve. La separo a propósito porque es fácil darla por
incluida en las otras, y es la única que importa cuando las demás ya no ayudan.

Dos precisiones cortas. **Privacidad depende de dónde esté usted**: qué se puede hacer con
información de personas cambia según el país, la finalidad, la relación y el contexto, y este
libro no le va a decir cuál es su regla. Y **algo puede no ser un dato personal y aun así ser
información que usted le debe a otro**: un procedimiento que le confió un cliente no es un dato
personal de nadie, y tampoco es suyo para enseñarlo.

**Auditoría, aquí, no es** auditoría contable, ni legal, ni una certificación de cumplimiento.
Es lo que dice la tabla: poder reconstruir.

## Quién puede ver qué

La distinción que hace falta es esta: **autoridad no es acceso.**

Una persona puede tener autoridad para decidir algo **sin necesitar ver toda la información del
negocio**. Y al revés: puede tener acceso a mucha información sin tener ninguna autoridad para
decidir con ella. Son dos cosas distintas y se pueden conceder por separado, aunque nada obliga
a separarlas y lo más cómodo es darlas juntas sin pensarlo.

Lo mismo vale para una herramienta. Que tenga permiso para una tarea **no significa que necesite
acceso a todo lo demás**.

Aquí hay un apoyo que conviene tener, con su ámbito dicho: una guía del instituto estadounidense
de normas y tecnología dirigida a los negocios pequeños —**de 2016, y una guía de referencia, no
una norma**— recomienda que cada quien acceda **solo a los sistemas y a la información concreta
que necesita para hacer su trabajo**, y que cada persona entre con su propia cuenta. Y da el
motivo que más sirve aquí: **sin cuentas individuales resulta difícil investigar una pérdida de
información o un uso no autorizado.**

Traducido a este método: el acceso no se concede por comodidad. Se concede porque hace falta, y
se retira cuando deja de hacer falta.

**Con equipo** puede haber personas distintas que autoricen accesos, administren sistemas o
revisen lo ocurrido. **Trabajando solo** son la misma persona, y las preguntas no desaparecen:
cambian de sentido. Ya no son «quién más entra», sino **«qué queda abierto cuando yo no estoy»**.

## Qué queda registrado

Del capítulo anterior ya viene lo mínimo: qué se ejecutó, bajo qué permiso, cuándo, si hubo
alguna excepción y qué se decidió entonces.

Lo que este capítulo añade es **para qué sirve**. La misma guía señala que los registros pueden
ser valiosos **cuando hay que investigar algo**, y esa es exactamente su función: no vigilar a
nadie, sino poder reconstruir.

Y de ahí sale la regla, porque la palabra «auditoría» empuja hacia el lado contrario:

> **Auditar no es registrarlo todo.** Un registro que nadie puede leer no es trazabilidad: es
> volumen.

Lo que hay que poder reconstruir es **lo importante**, y lo importante ya está definido: lo que
usted autorizó.

## Dónde están los datos

La segunda escena es de un negocio de una sola persona.

Necesitaba recuperar algo de unos meses atrás. Estaba en la cuenta de un proveedor, y a esa
cuenta se entraba con un correo que había dejado de usar. Lo resolvió en dos días. Pero durante
esos dos días descubrió que **una parte del negocio existía en un solo sitio, y que ese sitio no
era suyo**.

No hace falta un desastre para descubrir una dependencia. Basta con necesitar algo.

Y aquí conviene no discutir lo que este libro no puede resolver. **De quién son los datos que
guarda un proveedor es una pregunta jurídica**, depende del contrato y del país, y no la voy a
contestar. La pregunta que sí sirve, y que puede contestar usted esta semana, es otra:

> **¿Puede sacar de ahí lo que necesita para seguir funcionando?**

Si la respuesta es «creo que sí», todavía no la ha contestado.

Hay una cosa más que sí conviene decir, y va con su ámbito pegado. En la Unión Europea, la
autoridad europea de protección de datos sostiene que **quien encarga a un proveedor el
tratamiento de datos personales** solo debe recurrir a proveedores que ofrezcan **garantías
suficientes**, y **debe poder demostrar que lo valoró antes**. **Es una regla de ese marco y para
esa materia**, y no debe leerse como obligación general. Pero el principio que hay detrás viaja
bien, y lo formulo como regla de este método: **contratar a un proveedor no traslada
automáticamente la responsabilidad del negocio sobre lo que necesita proteger.**

## Qué pasa si algo falla

Dentro de «que algo falle» caben cinco cosas distintas, y conviene nombrarlas por separado porque
no se parecen: **falla la herramienta** —deja de funcionar, o funciona mal—; **falla el acceso**
—nadie puede entrar, o entra quien no debía—; **falla el proveedor** —el servicio no está, o deja
de prestarse—; **falla la información** —se pierde, se estropea o se queda vieja sin que nadie lo
note—; y **alguien usa algo que no debía usar**, que es la única de las cinco que no es una
avería.

No hace falta un plan para cada una.

Hace falta contestar una pregunta:

> **¿Qué necesita el negocio para seguir funcionando mientras el problema se resuelve?**

Y aquí entran las copias, que es donde una respuesta rápida se parece mucho a una comprobada. La
misma guía recomienda guardar las copias **fuera del sitio donde ocurre el trabajo**, para que un
problema en un sitio no se lleve las dos cosas. Eso es de la fuente. Lo que añade este método es
lo otro:

> **Tener una copia no demuestra que pueda recuperarla.** Una copia que nadie ha restaurado
> todavía es una suposición, no un respaldo.

No le voy a decir cada cuánto hacerlas, ni cuántas, ni dónde. Le voy a decir que **compruebe una
vez que se recupera de verdad**, y que anote el día que lo comprobó.

## La lista de comprobación de seguridad básica

Ocho preguntas, en cuatro pares: **quién entra** (1 y 2), **con qué llaves y con qué rastro** (3
y 4), **qué hay fuera de su alcance** (5 y 6) y **qué pasa cuando algo falla** (7 y 8). Las cuatro
primeras miran hacia dentro y las cuatro últimas hacia fuera. Se contestan en una hoja y no hay
que ser especialista para entenderlas.

| | | Respuesta |
|---|---|---|
| **1** | ¿Cada persona —y cada herramienta— entra **con su propia cuenta**? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |
| **2** | ¿Alguien, o algo, tiene acceso a **más de lo que necesita** para su trabajo? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |
| **3** | ¿Sabe **dónde están las credenciales** y quién las conoce? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |
| **4** | Si mañana hubiera que reconstruir **qué se hizo, quién lo autorizó y qué pasó con una excepción**, ¿podría? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |
| **5** | ¿Sabe qué existe **solo** en la cuenta de un proveedor, y qué pasaría si mañana no pudiera entrar? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |
| **6** | ¿Hay una **copia fuera de ahí**, y ha comprobado alguien que se restaura? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |
| **7** | Si algo falla, ¿sabe **quién se entera, quién puede detenerlo** y a quién se avisa? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |
| **8** | ¿Sabe **qué necesita el negocio para seguir funcionando** mientras se resuelve? | ☐ sí ☐ no ☐ no lo sé ☐ no aplica |

**Y una quinta columna, que es la que convierte la hoja en algo:** **qué voy a hacer.** Una línea
por pregunta, con fecha.

> **«No lo sé» es la respuesta más útil de esta hoja.** No es peor que «no»: es la única que le
> dice **dónde tiene que mirar**. Un «no» ya es una decisión; un «no lo sé» es un sitio del
> negocio que nadie ha mirado todavía.

**«No aplica» se escribe con su motivo**, en media línea, igual que en la matriz del capítulo
anterior. Una casilla que no aplica no es una casilla vacía.

## Qué preguntar cuando haga falta preguntar

Varias de estas respuestas dependen de cosas que este libro no puede resolver: su jurisdicción,
sus contratos, su sector, su profesión si está regulada, o una revisión de seguridad hecha por
alguien que se dedique a eso. **Y donde una actividad esté sometida a una norma profesional, el
permiso que usted le dé a una herramienta no sustituye la responsabilidad de la persona
habilitada.**

Pero remitir no es lo mismo que no enseñar. Si acaba el capítulo sabiendo **qué preguntar** —qué
puedo exportar, qué queda registrado, quién tiene acceso a qué, qué dice mi contrato sobre lo que
pasa cuando me voy—, llegará a esa conversación sabiendo qué necesita de ella. Y eso no lo puede
poner el profesional por usted.

Y conviene dejar escrito lo que este capítulo **no** promete, porque en este terreno la
diferencia entre lo hecho y lo prometido cuesta cara: no promete que su negocio esté seguro, ni
que evite una filtración, ni que cumpla ninguna regulación, ni que su información esté
protegida. Una copia no garantiza una recuperación, un registro no garantiza
una auditoría, un proveedor no asume su responsabilidad por el hecho de cobrarle, y **que algo
quede registrado no significa que alguien lo esté mirando**.

## Lo que queda al cerrar esta parte

Estos seis capítulos han hecho una sola cosa, repetida: **poner condiciones antes de conceder
permisos.** Ordenar la información antes de entregarla. Decidir qué se permite antes de que algo
sea capaz de hacerlo. Observar antes de avisar. Comprobar antes de aceptar. Escribir el límite
antes de ejecutar. Y ahora, proteger y poder reconstruir antes de dejar que siga.

Y el material sobre el que todo eso funciona es el mismo desde el capítulo 6: lo que su negocio
sabe hacer, puesto por escrito. **No basta con tenerlo documentado.** Tiene que estar también
bajo un acceso claro, recuperable, y suficientemente registrado como para poder mirar atrás.

Al terminar esta parte, la frase que debería poder decir es esta: **la tecnología ya puede
ayudarme sin que yo le haya entregado el control.**

## Lo que este capítulo no ha contestado

Hay información ordenada, criterio escrito, permisos, límites y controles. Todo eso existe fuera
de su cabeza, que era el objetivo.

Pero hasta ahora lo ha usado usted, o una herramienta a la que usted dio permiso. Queda la
pregunta que abre la parte siguiente, y es de otra naturaleza:

*¿Qué ocurre cuando quienes tienen que trabajar con todo esto son otras personas?*
