---
capitulo: 12
parte: 3
titulo: "La inteligencia artificial como aprendiz"
etapa_metodo: "A"
estado: borrador
palabras: 2225
casos_usados: ["C-09"]
recursos_producidos: []
afirmaciones_por_verificar: []
ultima_actualizacion: "2026-09-09"
---

# 12. La inteligencia artificial como aprendiz

Nuria dirige un negocio agrícola con varias personas a su cargo. Contestar a los compradores lo
ha hecho siempre ella: llega una petición de información, mira lo que hay, escribe la respuesta
y la envía.

Una tarde probó a pedirle a una herramienta que le preparase una de esas respuestas. Le
describió la petición, le entregó lo que hacía falta para contestarla y esperó sin demasiada fe.

Lo que le devolvió era mejor que lo que ella habría escrito con prisa. Estaba ordenado, no se
dejaba nada de lo que el comprador preguntaba y decía las cosas en un tono que ella misma habría
firmado. Lo leyó dos veces. La segunda vez se hizo una pregunta razonable: *si lo hace así de
bien, ¿por qué estoy yo leyéndolo?*

Este capítulo entero existe para contestar esa pregunta. Pero antes conviene mirar el borrador
una tercera vez, porque llevaba dentro algo que Nuria no había visto: **fijaba una fecha de
entrega**. No una disparatada. Una plausible, deducida de lo que ella misma le había dado. Nadie
le había pedido que la fijara. Nadie le había dicho que no.

## Lo que la escena demuestra y lo que no

La herramienta demostró una capacidad: sabe redactar esa clase de respuesta. No demostró nada
sobre una cuestión distinta, que es si **debe fijar una fecha de entrega en nombre del negocio**.

Son dos preguntas separadas y el idioma las junta en un mismo verbo. Cuando se dice que una
herramienta «puede» hacer algo, a veces se quiere decir *es capaz* y a veces *está autorizada*.
En este libro van separadas:

> **Capacidad** es lo que la herramienta sabe hacer. Viene con ella.
>
> **Permiso** es lo que este negocio le deja hacer. Lo decide usted.

De ahí sale la frase que sostiene el capítulo: **que sea capaz de hacerlo no contesta si debe
permitírsele hacerlo.**

Y de ahí sale también la trampa, que es fina: **dejar que la calidad de la salida decida el
permiso**. Pero **la autoridad no se gana produciendo buenas respuestas: la asigna el negocio.** El
capítulo 10 ya dijo de dónde sale la autoridad —de personas, funciones u órganos reales— y nada
de eso cambia porque quien ejecute sea un programa.

## Qué es, en lenguaje llano

Este libro va a usar una definición funcional, que es la que hace falta para decidir permisos:

> Una inteligencia artificial es un sistema que **recibe información y produce una salida** —un
> texto, una clasificación, un aviso, un resumen, una propuesta— **a partir de patrones
> extraídos cuando se construyó**.

Eso es todo, y no exige entender cómo está hecha por dentro. Aquí no se explica esa parte por dos
razones: no hace falta para lo que el libro tiene que resolver, y caducaría antes que el resto.

Lo que esa definición deja fuera importa más que lo que incluye:

- **No comprende su negocio.** Produce salidas verosímiles, que no es lo mismo que correctas.
- **No sabe qué es importante aquí.** La fecha de entrega del borrador de Nuria era plausible
  precisamente porque el sistema no tenía manera de saber que esa era la parte delicada.
- **No conoce lo que no está en lo que recibe.**
- **No responde de nada.** Ante un comprador molesto no hay ningún sistema a quien preguntarle.

De la primera se deduce lo que hicimos en el capítulo anterior: si no comprende su negocio, todo
lo que sepa de su negocio se lo tiene que dar usted, y por eso ordenar la información iba antes.

## El aprendiz, y hasta dónde llega la comparación

A un aprendiz no se le entrega la caja el primer día. Primero mira. Después avisa de lo que ve.
Más tarde propone. Y solo entonces se le deja hacer algo pequeño por su cuenta. Ese orden —y no
otra cosa— es lo que este libro toma prestado al llamar aprendiz a una inteligencia artificial.

**La metáfora dice eso y no dice nada más.** Conviene delimitarla en su primera aparición, porque
se estira sola. No significa que el sistema se reentrene, que cambien sus parámetros, que aprenda
de su negocio con el uso, que recuerde todo lo que ha visto, que adquiera criterio ni que se
vuelva autónomo de tanto usarlo. Y el aprendiz de la comparación **no es empleado, ni sucesor, ni
socio, ni una réplica de nadie**: aquí no se clona a la persona.

Queda además una diferencia que la comparación no salva, y es mejor decirla que dejarla flotando:
**un aprendiz humano se convierte con los años en alguien que sabe.** La escala de este libro no
describe ese camino. Describe el orden en que un negocio va concediendo permisos, que es un
asunto del negocio y no del aprendiz.

## Una escala que es de este libro

El Método LEGADO usa siete niveles, del 0 al 6: dependencia manual, orden y digitalización,
observación, asistente que informa, recomendaciones, ejecución limitada dentro de reglas
escritas, y coordinación supervisada como techo. Cada uno tiene su sitio en los capítulos que
vienen.

Tres advertencias antes de seguir.

**Primera: es diseño de este proyecto.** No es un estándar, ninguna institución reconoce estos
siete niveles y no debe presentarse como algo más de lo que es. Que exista un abanico entre lo
totalmente manual y lo totalmente autónomo sí está reconocido fuera: el marco de gestión de
riesgos del instituto estadounidense de normas y tecnología —un documento **de uso voluntario**,
no una ley— describe configuraciones que van de lo uno a lo otro, e incluye la posibilidad de que
un sistema se use **como una opinión más** dentro de una decisión que sigue siendo de una
persona. Los siete escalones concretos, en cambio, son de aquí.

**Segunda: la escala mide autorización.** No mide inteligencia, ni calidad, ni potencia, ni
precio, ni tamaño. Un sistema muy capaz puede estar en nivel cero de permisos en su negocio, y
eso no es un defecto del sistema.

**Tercera, sobre el primer escalón.** El nivel 0 no describe el permiso de ninguna herramienta:
describe la situación de partida, un negocio que depende de una persona. Está ahí porque es donde
estaba usted al empezar este libro, no porque haya nada autorizado que medir.

## El nivel se asigna por tarea

Aquí está el error que conviene no cometer: decir «mi negocio está en el nivel 3».

Nuria, esa misma tarde, podía permitir dos cosas distintas con la misma herramienta. Redactar el
borrador de una respuesta: se lo permite. Fijar una fecha de entrega: no. No es incoherencia. Son
dos tareas, y **el permiso se concede por tarea**.

Lo mismo dentro de una empresa con personas: que una tarea de un área esté autorizada no dice
nada sobre otra. **El nivel no es un rasgo del negocio ni un rasgo de la herramienta.** Es una
decisión sobre un trabajo concreto, y por eso se escribe en filas.

## Subir, mantener y bajar

Los permisos se conceden hacia arriba, en orden, y **se pueden retirar**. Bajar de nivel no es un
fracaso del proyecto: es la prueba de que el permiso era suyo y no de la herramienta.

Lo que sí conviene es decidirlo antes, y hay un motivo para no dejarlo al momento. Un estudio
experimental sobre una tarea concreta —no sobre negocios, y sin muestra declarada, así que no
puede convertirse en una afirmación sobre nadie— observó que a las personas les cuesta juzgar su
propio metaconocimiento, es decir, saber qué saben bien y qué no, y que delegar bien en un
sistema depende justamente de eso. La consecuencia práctica para este método: **si juzgar el
propio límite es difícil, más vale escribir el permiso en frío que decidirlo delante de una
salida que impresiona.**

Por eso el cuadro de este capítulo pregunta también **qué tendría que ver usted para ampliar o
para reducir**. Escrito antes, es un criterio. Improvisado después, es una justificación.

## Juntar a los dos no garantiza nada

Hay una promesa que este libro no va a hacer, y conviene decirlo con la fuente delante.

El mismo marco de uso voluntario citado más arriba advierte que **los resultados de la
interacción entre personas y sistemas varían**: en ciertas condiciones, la parte del sistema
puede amplificar los sesgos de la persona y llevar a decisiones **peores que las que habrían
tomado la persona o el sistema por separado**. Y añade lo otro, que es lo que salva el asunto:
cuando esas variaciones se tienen en cuenta al organizar el trabajo, sí puede aparecer
complementariedad y un resultado mejor.

**Léalo dos veces.** La mejora no viene de juntarlos: **viene de gobernar cómo se juntan.** Que es
exactamente lo que usted lleva once
capítulos haciendo.

De ahí sale también qué se le pide a la supervisión. El reglamento europeo de inteligencia
artificial —**una norma de la Unión Europea, y solo para sistemas de alto riesgo**, de modo que
**no es una obligación general**— exige que las personas encargadas puedan **no usar la
salida, ignorarla, anularla, revertirla e interrumpir el sistema**. Y el marco voluntario pide que
existan **mecanismos y responsables asignados** para desconectar un sistema cuyos resultados no
encajan con el uso previsto. Este libro toma esas condiciones como **buen diseño**, no como deber
legal.

Con una consecuencia incómoda: **supervisar no es aprobar.** Quien pulsa «aceptar» sin poder
decir que no, sin con qué juzgar y sin manera de parar, no está supervisando. Está firmando.

## El cuadro de lo que puede y lo que no puede hacer

El entregable de este capítulo lleva a propósito la misma palabra ambigua que llevamos veinte
párrafos deshaciendo, y la deshace por dentro: **tiene una columna para lo que es capaz de hacer
y otra distinta para lo que tiene permitido**. Si las dos se rellenan igual, no se ha decidido
nada.

**Una fila por tarea. Nunca por empresa entera. Empiece por una.**

| | Columna | Qué contesta |
|---|---|---|
| 1 | **La tarea** | Concreta y reconocible, tal como se hace hoy |
| 2 | **Qué información necesita** | Sale del capítulo 11 y de la lista de lo que no se entrega libremente |
| 3 | **Qué podría hacer técnicamente** | La capacidad, sin exagerarla ni minimizarla |
| 4 | **Qué le permito hoy** | El permiso. Esta columna y la anterior **no se rellenan igual** |
| 5 | **Qué no le permito** | Escrito, y con la razón al lado: qué queda fuera y por qué |
| 6 | **Quién responde** | Una persona, un puesto o un órgano que existan de verdad |
| 7 | **Qué tendría que ver para ampliar o reducir** | La condición. Sin plazo, sin porcentaje y sin nota |

Así quedó la primera fila de Nuria, escrita el mismo día:

| Columna | Lo que escribió |
|---|---|
| **La tarea** | Preparar el borrador de respuesta a una petición de información de un comprador |
| **Qué información necesita** | La petición y los datos de la fuente de referencia. Sin las condiciones pactadas con ese comprador |
| **Qué podría hacer técnicamente** | Redactarla entera, con fechas y condiciones incluidas |
| **Qué le permito hoy** | Redactar el texto y ordenar lo que el comprador pregunta |
| **Qué no le permito** | Fijar fechas de entrega ni condiciones, porque de eso responde el negocio. Enviar nada. Aparecer como remitente |
| **Quién responde** | Quien atiende a compradores. De las condiciones, ella |
| **Qué tendría que ver para ampliar o reducir** | Borradores en los que no haya tenido que quitar ninguna condición que nadie autorizó |

Tres precisiones sobre cómo se rellena.

**Si trabaja solo**, las columnas 6 y 7 no desaparecen: usted usa, autoriza y revisa. Aquí no se
finge una separación que no existe, y la protección viene de otro sitio —el permiso escrito antes
de usar, la gradualidad, poder deshacer y poder parar—. **No se afirma que eso equivalga a
separar funciones**; es lo que hay cuando no hay a quién separar.

**Si tiene equipo**, la columna 6 se apoya en la matriz de autoridad del capítulo 10, y vale la
misma regla: no se inventan cargos. Si hoy nadie responde de esa tarea, se escribe eso.

**Si su actividad tiene reglas profesionales o sectoriales**, la fila puede quedar marcada como
sujeta a esa regla y el asunto se consulta fuera de aquí. Este libro no decide qué puede delegar
ninguna profesión.

Sin puntuación, sin porcentajes, sin marcas y sin nombres de programas. Cabe en una hoja.

## La señal de paso

**Con una tarea basta.** Ha terminado este capítulo cuando puede decir, de un solo trabajo de su
negocio, qué podría hacer una herramienta con él, qué le permite hoy, qué no, quién responde y
qué tendría que ver para cambiarlo.

No hace falta que tenga ninguna tecnología funcionando. Y **«hoy no le permito nada» es una fila
válida**: es una decisión escrita, que es justo lo que se pedía.

## Lo que este capítulo no ha contestado

Nuria terminó con su fila escrita y con una pregunta nueva, que es la buena: *ya sé qué le
permito hoy; ¿cómo consigo saber si merece más, sin entregarle todavía ninguna decisión?*

Esa pregunta tiene respuesta, y ocupa el capítulo siguiente.
