---
capitulo: 08
parte: 2
titulo: "Cómo documentar las excepciones"
etapa_metodo: "E"
estado: borrador
palabras: 2067
casos_usados: []
recursos_producidos: ["registro-de-excepciones.md"]
afirmaciones_por_verificar: []
ultima_actualizacion: "2026-09-07"
---

# 8. Cómo documentar las excepciones

Coja una de las marcas que dejó al margen. Cualquiera. Vamos a abrirla.

Debajo de esa señal hay una frase que se dijo usted mismo sin darle importancia: *«esto
normalmente se hace así, pero con este cliente no»*, *«el pedido va completo, salvo cuando
lo pide aquel»*, *«se cobra por adelantado, menos en dos casos»*. Ese **pero**, ese **salvo**
y ese **menos** son lo que vamos a trabajar aquí.

Y conviene decir desde el principio cómo se trabaja, porque el orden lo es todo: **primero
se registra, después se juzga.** Quien se pone a decidir si la excepción está bien mientras
la está escribiendo termina escribiendo una justificación, no un registro.

## Qué es una excepción, exactamente

Hace falta una definición estrecha, porque si no cabe cualquier cosa.

> **Hay una excepción cuando existe una forma normal de proceder y un caso concreto hace que
> se actúe de otra manera.**

Fíjese en que la forma normal **no tiene que estar escrita**. Puede ser una costumbre, algo
que se aprendió por experiencia o simplemente lo que se hace cuando nadie dice lo contrario.
Basta con que exista una referencia de normalidad, aunque solo esté en la cabeza de la gente.

Y de ahí sale un caso que conviene separar. Si al mirar una situación descubre que **cada
caso se resuelve desde cero**, sin ninguna referencia común, ahí no hay una excepción: hay
una regla que todavía no existe. Son dos hallazgos distintos y piden trabajos distintos.
Anótelo como lo que es y siga.

## Lo que no es una excepción

**No es un error.** Un error es algo que no debería repetirse en las mismas condiciones. Una
excepción puede ser perfectamente correcta. El problema es que, vistas por primera vez, las
dos se parecen bastante: alguien hizo algo distinto de lo previsto. Por eso no conviene
etiquetar mientras se observa. Registre el hecho; la clasificación viene después y viene con
más información.

**Y no es cualquier adaptación.** Esto importa sobre todo si su trabajo consiste en hacer
cada encargo a medida: ahí la variación no es una excepción, es el oficio. La pregunta que
separa una cosa de la otra es esta:

> **¿Esto se aparta de la manera en que resuelvo normalmente las situaciones comparables?**

Si la respuesta es que no, no lo registre. Personalizar no es apartarse de nada cuando
personalizar es la forma normal.

## Dónde están, según cómo trabaje

**Con equipo** las excepciones pueden dejar rastro, porque alguien tiene que preguntar o
alguien tiene que hacer algo distinto. Aparecen en las consultas que suben, en las
autorizaciones que se dan de palabra, en el «con este cliente lo hacemos de otra manera» que
se repite sin estar escrito en ningún sitio, y en los ajustes que hace una persona con
experiencia sin llegar a explicarlos, porque para ella son evidentes.

Y la pregunta con la que se busca importa mucho. **No es «¿quién se salta el
procedimiento?»**, que convierte el ejercicio en una cacería y garantiza que nadie vuelva a
contar nada. Es **«¿en qué situaciones nos apartamos de la forma normal, y por qué?»**. La
primera busca un culpable; la segunda busca una razón, que es lo único que sirve.

**Trabajando solo** el rastro es otro, porque quien decide y quien ejecuta son la misma
persona: una excepción puede pasar inadvertida sin que nadie diga «oye, ¿y esto por qué se
hace así?», y el apartamiento se aplica y se olvida en el mismo gesto. Ahí hay que buscarlo a
propósito: en las condiciones especiales que aplica a algún cliente, en los
encargos que acepta de una manera que no aceptaría de otro, en las secuencias que cambia
según el caso, y en los acuerdos que tiene con alguien de fuera y no están en ningún papel.

## El motivo vale más que el desvío

Anotar «aquí hicimos algo distinto» sirve de poco. Lo que hay que salvar es **por qué**.

Con un ejemplo se ve en tres líneas. Lo normal es cobrar antes de entregar. La excepción fue
entregar antes de cobrar. Y el motivo: se trataba de un cliente con determinado historial.
Con eso basta en este capítulo.

Lo que **no** hay que hacer todavía es explicar qué significa exactamente ese historial,
desde cuándo cuenta, cuántas veces, qué lo rompe y qué combinaciones lo cambian. Eso es un
trabajo grande, tiene su propio capítulo y se hace mejor con todas las excepciones delante.
Aquí se registra el motivo en una frase. Si esa frase se le está convirtiendo en media
página, escriba al lado **«necesita explicación aparte»** y pase a la siguiente.

## Cuando nadie sabe por qué

Si aparece esta situación, no es un fallo del ejercicio.

*«Con este proveedor siempre se ha hecho así.»* *«Lo montó mi padre y nunca lo tocamos.»*
*«No sé de dónde salió, ya estaba cuando entré.»*

**Escriba «motivo no conocido».** No invente una explicación razonable a posteriori, que es
la tentación y es la peor salida posible: convierte una laguna en una regla falsa que además
queda por escrito. Un motivo desconocido es un hallazgo de los buenos, porque señala algo
que se lleva haciendo mucho tiempo sin que nadie sepa defenderlo.

## Un plazo que nadie recordaba haber concedido

Una mujer que lleva un negocio de importación y distribución empezó por tres marcas de las
que había dejado al margen. Dos se resolvieron en dos líneas cada una.

La tercera era un plazo de pago más largo para un cliente. Al buscar el motivo no lo
encontró. Preguntó a la persona que llevaba administración desde hacía años y tampoco lo
sabía: se aplicaba porque estaba en la ficha, y en la ficha estaba porque alguien lo puso.
Escribió «motivo no conocido» y siguió.

Lo interesante vino después, al revisarlo con distancia. Al reconstruir la fecha aproximada,
aquel plazo coincidía con una campaña concreta que terminó hace años. La razón había
existido y había caducado, y el plazo se había quedado. No era una excepción válida ni un
error: era una excepción **temporal que nadie retiró** cuando se acabó la condición que la
justificaba.

Nada de eso habría aparecido si el primer día se hubiera escrito una explicación plausible
en lugar de «no lo sé».

## Por qué esta zona es útil

Las excepciones son una de las partes de lo que en la introducción llamamos ADN empresarial,
y aquí conviene no exagerar: no son la más importante ni la más difícil. Lo que las hace
útiles es otra cosa, y es bastante concreta.

Una excepción es, por definición, **el punto donde la forma normal de trabajar deja de
bastar**. Y eso convierte esta zona en un sitio especialmente bueno para encontrar criterio,
porque ahí alguien tuvo que decidir algo que la regla no resolvía sola. No siempre: hay
excepciones ya previstas, con su condición escrita y su respuesta prevista. Pero **se llega
antes al criterio buscando dónde la regla se queda corta que preguntando en abstracto por
qué se decide como se decide**.

## Primero el hecho, después el juicio

De ahí que el registro se haga en dos tiempos, y que convenga separarlos incluso
físicamente en la hoja.

**Lo primero es el hecho**, y se escribe sin opinar: cuál era la situación, cuál es la forma
normal, qué se hizo distinto, qué motivo se conoce —o que no se conoce—, qué resultado se
observó y quién lo decidió aquel día. Lo de «quién» es descriptivo, para entender el caso; no
estamos repartiendo quién podrá decidir mañana, que es otro asunto y llega más adelante.

Una advertencia sobre el resultado. Si el cliente quedó satisfecho, escriba que el cliente
quedó satisfecho. **No escriba que la excepción funcionó**: una cosa es lo que se observó y
otra es afirmar que lo uno causó lo otro, y desde una sola vez no se puede saber.

**Lo segundo es el juicio**, y se hace con distancia. Ahí cada excepción cae en uno de estos
cuatro sitios:

| | |
|---|---|
| **Se mantiene** | La razón sigue viva y sigue siendo buena. |
| **Es temporal** | Tiene sentido mientras dure una condición concreta, y debe retirarse cuando esa condición termine. |
| **Hay que mirarla** | No hay información suficiente para decidir todavía. Aquí van casi todas las de motivo desconocido. |
| **Debería dejar de hacerse** | Ya no tiene razón, o nunca la tuvo. |

Ese cuarto casillero es el que da sentido a los otros tres. **No toda excepción se conserva**,
y un registro que solo sirva para legitimar lo que ya se hacía no sirve para nada.

Dos frases que no bastan como motivo, y conviene tenerlas presentes al revisar: *«siempre lo
hemos hecho así»* y *«funcionó aquella vez»*. La primera describe una costumbre, no una
razón. La segunda describe un caso, no una regla.

## Cuando la excepción es en realidad otra cosa

Al revisar aparecen dos hallazgos que no son excepciones y que vale la pena reconocer.

**Puede ser una regla que nadie ha escrito.** Si el mismo apartamiento se repite bajo las
mismas condiciones y por el mismo motivo, quizá ya no sea un caso especial: puede ser cómo
se trabaja, sencillamente sin anotar en ninguna parte. Compruébelo antes de darlo por hecho;
el patrón lo sugiere, no lo demuestra. Ojo, que lo que lo delata no es cuántas
veces ha pasado, sino que haya un patrón estable: una excepción que ocurre una vez cada tres
años puede seguir siendo una excepción, y otra que ocurre cada semana puede ser una regla
encubierta.

**O puede ser la forma normal, que está mal.** Si para que el trabajo salga hay que
apartarse continuamente de lo previsto, quizá el problema no esté en los apartamientos.
Anótelo como hallazgo y no lo arregle ahora: cambiar un procedimiento base es una decisión
que conviene tomar con todo el registro delante, no a mitad de la primera hoja.

## Hasta cuándo, y quién vuelve a mirarlo

Cada excepción que se conserva necesita dos cosas más, y son las que evitan que el registro
se convierta en un cementerio.

**Hasta cuándo.** No tiene por qué ser una fecha. Puede ser una condición —«mientras dure
este proyecto», «hasta que cambie el proveedor»—, y puede ser «sin plazo, se revisa». Lo que
no puede es quedar en blanco, porque una excepción sin horizonte **puede mantenerse por
inercia** mucho después de que su razón se acabe, como el plazo de la ficha.

**Quién vuelve a mirarlo.** Con equipo, alguien que participe en ese trabajo. **Trabajando
solo, usted mismo, y conviene decir con todas las letras que eso es más débil**: quien
registró y quien revisa son la misma persona, así que no hay ninguna mirada independiente.
Lo que sí ayuda es la distancia: registrar dentro de la situación y volver cuando ya está
fuera de ella. No se inventa un revisor que no existe.

## Lo que no se negocia

Una excepción interna no autoriza a apartarse de una ley, de una obligación regulatoria, de
los requisitos de una licencia, de una norma de seguridad, de un contrato firmado ni de las
normas de una profesión. Este libro no puede decirle qué apartamientos son admisibles en su
actividad y en su país, y no va a intentarlo.

Lo que sí puede decirle: si al registrar una excepción aparece cualquiera de esos ámbitos,
márquela y consúltela con quien corresponda antes de seguir aplicándola. Que lleve años
haciéndose no la vuelve admisible.

## Señales de que puede avanzar al capítulo siguiente

- Tiene registradas las marcas que traía del capítulo anterior, con su motivo en una frase o
  con un «no lo sé» honesto.
- Cada una tiene un hasta cuándo, aunque sea «se revisa».
- Ha clasificado las que registró, **incluida la posibilidad de que ninguna deba retirarse**:
  que todas sigan teniendo razón también es un resultado.
- Tiene apartadas las que le pedían media página de explicación.

---

Esas últimas son el trabajo que viene. Ahora tiene una lista de excepciones con su motivo
apuntado en una línea, y algunas de esas líneas no se sostienen solas: dicen «según el
historial», «si el cliente es de los antiguos», «depende de cómo venga el mes», y quien las
lea sin usted dentro no sabrá cuándo aplicarlas.

Que algo esté escrito no significa que otra persona sepa reconocer cuándo toca. Ese
reconocimiento es criterio, y todavía no está en ninguna hoja. La pregunta que abre el
capítulo siguiente es la más difícil del libro: **cómo se explica aquello que hasta ahora
usted solo sabía reconocer cuando lo tenía delante.**
