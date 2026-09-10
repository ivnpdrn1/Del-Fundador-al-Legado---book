---
capitulo: 15
parte: 3
titulo: "Autonomía limitada y aprobación humana"
etapa_metodo: "A"
estado: borrador
palabras: 2170
casos_usados: ["C-12"]
recursos_producidos: ["matriz-niveles-autonomia.md"]
afirmaciones_por_verificar: []
ultima_actualizacion: "2026-09-09"
---

# 15. Autonomía limitada y aprobación humana

El capítulo anterior terminó preguntando si hay algo que la herramienta pueda hacer por sí misma
sin volver a preguntar cada vez.

**Sí.** Y dicha así de corta, es la respuesta más peligrosa de este libro, porque se entiende al
revés: suena a que la tecnología ha ganado algo. No ha ganado nada. Lo que ha ocurrido es que
**una persona autorizó por adelantado una clase de acciones dentro de límites escritos**, y
mientras un caso se parezca a esa clase, no hace falta volver a preguntar.

El permiso sigue siendo suyo. Lo que cambió es **cuándo lo concede**: antes, y para muchos casos
a la vez.

## Autorizar una regla no es aprobar cada acto

El título de este capítulo parece contradecirse, y conviene deshacerlo antes de seguir.

Si una persona tuviera que aprobar **cada ejecución antes de que ocurriera**, no habría nada
nuevo: eso es el capítulo anterior con otro nombre. La aprobación humana sigue estando aquí,
pero **ocurre una vez y sobre una regla**, no una vez por caso.

Y la convención que ya usa la matriz de autoridad no cambia: **aprobar es autorizar antes;
revisar es comprobar después.** Lo único que se añade es que **una aprobación puede autorizar una
clase de acciones y no solo un acto.**

## Las noches de Ismael

Ismael importa y distribuye por su cuenta. No tiene empleados.

Cada envío le genera varios documentos que llegan por separado y en momentos distintos, y hasta
hace poco los clasificaba y archivaba él, casi siempre de noche, cuando ya no había nadie a
quien contestar. Era trabajo real y no era complicado: mirar a qué envío corresponde cada
documento, guardarlo donde va y anotar que llegó.

Escribió un permiso de una línea y media. La herramienta puede clasificar y archivar los
documentos que lleguen, asociándolos al envío que les corresponda, y dejar constancia de que
llegaron. Nada más.

Pasaron unas semanas y funcionó: decenas de documentos, cada uno en su sitio, **sin que Ismael
tuviera que decir que sí ni una sola vez**. No porque la herramienta acertara siempre. Porque
todos esos casos **se parecían al que él había autorizado**.

## Qué es la ejecución limitada

Lo que pasó en esas semanas tiene cinco momentos distintos, y confundirlos es lo que hace que
esto salga mal.

| | | |
|---|---|---|
| **1** | **Autorización previa** | Una persona define, por adelantado, qué clase de acción puede ejecutarse y con qué límites |
| **2** | **Ejecución** | Dentro de esos límites, la acción ocurre sin nueva consulta |
| **3** | **Excepción** | Un caso se sale del permiso escrito |
| **4** | **Decisión humana** | La ejecución se detiene y el caso vuelve a una persona |
| **5** | **Revisión posterior** | Alguien mira después lo que se hizo |

El primero, el cuarto y el quinto son de una persona. **Lo único que hace la tecnología es el
segundo: ejecutar.** El tercero no es otra acción suya: **es la aparición de un caso que queda
fuera del permiso**, y lo que provoca es que la ejecución se detenga.

## El límite, y qué pasa al cruzarlo

Un límite se entiende cuando se ve qué ocurre al llegar a él, así que van juntos.

Una noche llegó un documento distinto: **una versión corregida de un documento de un envío que
Ismael ya había cerrado el mes anterior**. El permiso decía «los documentos que lleguen,
asociándolos al envío que les corresponda». Ese envío ya no estaba abierto.

La herramienta **no decidió que fuera un cambio pequeño**. No archivó encima. No abrió el envío
por su cuenta. **Se detuvo, y se lo dejó a Ismael**, que a la mañana siguiente tardó dos minutos
en decidir qué hacer.

Y esa es la frase que sostiene el capítulo:

> **Una excepción no concede autonomía: la retira.** Fuera del límite escrito, el permiso deja de
> existir **para ese caso**, y la decisión vuelve a una persona.

Es lo contrario del temor razonable: que un sistema, ante algo raro, improvise.
Lo que aquí se le pide es que **ante algo raro no haga nada**.

Y no es una excepción en el sentido del capítulo 8 —aquello eran las excepciones del negocio, las
que usted documenta—. Esta es más simple: **un caso que no se parece al que se autorizó.**

## Detener no es apagarlo todo

Conviene distinguir tres cosas, porque quien las confunde acaba sin detener nada:

| | |
|---|---|
| **Detener una acción** | La que está en curso, y solo esa |
| **Detener una tarea automatizada** | Ese permiso deja de ejercerse; los demás siguen |
| **Desconectar el sistema** | Todo se para |

**No toda excepción exige apagarlo todo**, y ese es justamente el motivo de separarlas: si la
única manera de parar algo es apagarlo entero, nadie para nada, y se deja correr lo que habría
que haber parado.

Lo que sí tiene que existir, escrito antes de necesitarlo, es **una forma concreta de detener lo
que se está ejecutando**. En las obligaciones de supervisión humana que el reglamento
europeo de inteligencia artificial impone **a los sistemas de alto riesgo** —**y solo a
ellos**— eso se llama botón de parada **o procedimiento equivalente**, y lo segundo importa tanto como lo primero: **puede ser un
procedimiento, no un botón.**

Y falta la mitad que se olvida. El marco de gestión de riesgos que ya citamos —**el documento de
uso voluntario**— pide que existan **mecanismos** para anular o desconectar un sistema **y que
haya responsabilidades asignadas y entendidas** para hacerlo. Lo segundo es fácil de dar por
supuesto y no lo es: **un mecanismo que nadie tiene encargado de usar es un mecanismo sin
dueño.**

Conviene además desconfiar de una frase cómoda: *hay una persona supervisando, así que está
controlado.* **Estar presente no es supervisar.** Lo que hace que haya control es poder
contestar cinco preguntas concretas —**quién autorizó, quién puede detenerlo, a quién le llega
la excepción, quién lo revisa y qué queda escrito**—, y ninguna de las cinco se contesta con un
nombre en un organigrama.

## Qué tiene que quedar escrito

Poco, y siempre lo mismo: **qué se ejecutó, bajo qué permiso, cuándo, si hubo alguna excepción y
qué se decidió entonces.**

Con eso una persona puede reconstruir lo que pasó sin haber estado delante. Cómo se guarda, quién
puede verlo y qué ocurre si algo falla es el capítulo siguiente, y no se adelanta aquí.

## El nivel 5, ahora que se ha visto funcionando

A esto la escala de este libro lo llama **nivel 5, ejecución limitada**, y se le pone nombre al
final a propósito: primero se ve funcionar, después se nombra.

**Debe** dejar registro, detenerse ante una excepción, devolver la decisión a una persona y tener
un procedimiento de detención. Y **no puede**, la lista es cerrada: ampliar sus propios límites,
reinterpretar su permiso para conseguir más permiso, **decidir que una excepción es lo bastante
pequeña como para seguir**, ni concederse una categoría nueva de acción.

**Qué tarea puede entrar aquí.** Este método usa un criterio propio, y conviene decir en voz alta
que es **suyo**: no es una clasificación jurídica, ni regulatoria, ni de ningún estándar
internacional. Para que una tarea sea **candidata a ejecución limitada** tienen que cumplirse
**las cinco, y las cinco a la vez**:

1. **Su alcance está acotado por escrito, y antes.** Por tipo de caso, plazo, volumen, la
   información con la que trabaja, un importe cuando de verdad venga a cuento, o cualquier otra
   condición que sirva para esa tarea. **No hacen falta todas esas formas de acotar; sí hace
   falta al menos un límite comprobable que corresponda a esa tarea.**
2. **Su efecto principal es reversible en la práctica**: existe una forma realista de deshacerlo
   sin provocar una consecuencia igual o mayor. **Borrar un registro no es deshacer lo que ese
   registro ya provocó**, y nada es reversible por el hecho de ser digital.
3. **No decide ni modifica derechos, seguridad, empleo, remuneración u obligaciones de una
   persona.** Esto no dice que la tarea no afecte a nadie —casi todo afecta a alguien—: dice **qué
   no puede decidir** una herramienta con este permiso.
4. **No decide por sí misma el uso, la divulgación ni una finalidad nueva** de información
   confidencial o de datos personales.
5. **No crea, no modifica y no cancela** compromisos del negocio frente a terceros.

Y la quinta condición viene con la sexta cosa, que ya conoce: **si el caso se sale de cualquiera
de esos límites, deja de estar autorizado.**

**Lo que este cambio no significa.** Pasar del nivel 4 al 5 no quiere decir que la herramienta sea
más lista, ni que comprenda mejor, ni que haya aprendido nada, ni que sea más fiable. Significa
**que cambió el permiso, porque una persona decidió cambiarlo.**

Y conviene ver de dónde sale la posibilidad de escribir un permiso así. Ismael pudo redactar el
suyo en línea y media porque sabía qué documentos existen, de dónde vienen, cuál manda y qué
hace con ellos. **Un permiso solo se puede acotar sobre algo que ya está ordenado**: la
información, los procesos, el criterio, las excepciones y los límites que este libro lleva nueve
capítulos poniendo por escrito. Sin eso, no hay nada a lo que ponerle un borde.

## El nivel 6, que es el techo

Por encima hay un escalón más y no hay ninguno después.

El **nivel 6** es lo que este libro llama **mano derecha digital supervisada**, y se define por lo
que hace: **coordina** tareas ordinarias, **da seguimiento**, **prepara** decisiones para que las
tome una persona, **informa** de las excepciones, **escala** lo sensible y **mantiene informado**
al propietario.

La diferencia con el nivel 5 no es que haga más cosas. Es de otra clase: **el 5 ejecuta acciones
sueltas dentro de una regla; el 6 ordena el trabajo alrededor de esas acciones.** Sigue sin
decidir estrategia, sin modificar sus permisos y sin quitarle la responsabilidad a nadie.

**Y ahí se acaba.** No existe un nivel 7 en este libro, y la autonomía total no se propone en
ningún capítulo. Tampoco hay una dirección obligatoria: **subir, mantener, bajar y retirar son
las cuatro salidas legítimas**, y bajar de nivel no es un fracaso. Es la prueba de que el permiso
era suyo.

## La matriz de niveles de autonomía

En el anexo está la **herramienta 12**. Es una fila por tarea y ocho columnas: la tarea, el nivel
autorizado hoy, qué puede hacer sin volver a preguntar, dentro de qué límites, qué obliga a
detenerse y a quién vuelve, cómo se detiene, qué queda registrado y quién puede mirarlo, y cuándo
se revisa el permiso.

**No lleva una columna de «nivel al que quiero llegar»**, y la ausencia es deliberada: un número
escrito al lado del actual se lee como una meta, y esta hoja **no empuja hacia arriba**. Solo
registra lo que hay hoy y cuándo se vuelve a mirar.

**Y no se confunde con la matriz de autoridad del capítulo 10**, aunque se parezcan:

> **Aquella dice quién puede decidir qué. Esta dice cuánto puede hacer la tecnología sin volver a
> preguntar.**

Con una relación que no puede romperse: **el permiso concedido a la tecnología no puede exceder
la autoridad de quien lo autoriza.** No se trata de lo que esa persona haga con sus manos —puede
autorizar perfectamente algo que ella no ejecuta nunca—, sino de **hasta dónde llega su
autoridad para decidirlo**.

**Trabajando solo**, la columna de a quién vuelve la excepción dice «a mí», escrito tal cual. No
hay superior, no hay comité y **no existe la autoaprobación**: hay una persona decidiendo dos
veces, antes y después, y lo que la protege no es una separación que no existe, sino que **el
límite estaba escrito antes**. **Con equipo** puede haber una función que autoriza, otra que opera
y otra que revisa —pero la hoja **no exige tres personas ni inventa cargos**: usa las que haya.

## Señales de que puede avanzar al capítulo siguiente

Con **una** tarea basta, y hacen falta nueve cosas. Ninguna dice nada sobre acertar:

- Hay un **permiso escrito**, y **un nivel autorizado hoy**.
- Está escrito **qué puede ejecutar** sin volver a preguntar.
- Hay **al menos un límite** que se puede comprobar.
- Hay una **condición que obliga a detenerse**.
- Está claro **a quién vuelve** la excepción.
- Existe una **forma de detener** la automatización.
- **Queda registro** de lo ejecutado, y **alguien puede revisarlo**.

**«Lo bajé de nivel» cumple esta señal**, y «lo retiré» también. Lo que no la cumple es tener
permiso sin límite escrito.

## Lo que este capítulo no ha contestado

Ismael acabó con una tarea funcionando sola, un documento devuelto a tiempo y una pregunta que
ya no es sobre permisos:

*Si ya hace algunas cosas sin preguntarme, ¿quién puede ver todo esto, qué queda registrado,
dónde están los datos y qué pasa cuando algo falla?*
