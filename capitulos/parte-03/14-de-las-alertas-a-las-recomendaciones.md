---
capitulo: 14
parte: 3
titulo: "De las alertas a las recomendaciones"
etapa_metodo: "A"
estado: borrador
palabras: 1986
casos_usados: ["C-11"]
recursos_producidos: []
afirmaciones_por_verificar: []
ultima_actualizacion: "2026-09-09"
---

# 14. De las alertas a las recomendaciones

El capítulo anterior terminó preguntando: si ya puede llamar mi atención, ¿cuándo debería
proponerme qué hacer?

La respuesta corta es que puede hacerlo cuando usted se lo permita para esa tarea. Lo que
cambia de verdad es otra cosa, y conviene decirla antes que nada: **a partir de aquí la
herramienta empieza a producir propuestas, y usted empieza a tener que decidir qué hace con
ellas.**

El cambio de permiso parece pequeño. Lo que no lo es: la decisión vuelve a usted **con una
salida ya pensada encima.**

## Avisar no es recomendar

Un aviso dice **algo merece su atención**. Una recomendación dice **propongo que haga esto**.

Entre las dos frases hay una diferencia que no es de tono: la primera le devuelve el asunto
entero y la segunda le entrega, además, una salida ya pensada. Y una salida ya pensada es
cómoda, que es exactamente su peligro.

## La revisión que podía esperar

Inés dirige una empresa de mantenimiento con varios técnicos. Cada mes decide en qué orden se
hacen las revisiones preventivas, y esa decisión la ha tomado siempre ella.

Es la primera tarea a la que le concedió permiso para proponer. Y lo que recibió estaba bien
escrito:

> *Propongo posponer la revisión de este equipo y adelantar la de aquel otro, para que ninguno
> llegue al mes que viene con más horas acumuladas de las previstas. El primero suma menos horas
> desde su última revisión y en las dos anteriores no se encontró nada; el segundo acumula
> bastantes más. Regla aplicada: se prioriza por horas de uso desde la última revisión.*

Inés lo leyó y pensó que sí. No porque la propuesta la convenciera, sino por algo más
incómodo: **ella también había pensado que ese equipo podía esperar.**

## Qué es una recomendación aquí

Conviene fijarlo antes de seguir, porque la palabra se usa para muchas cosas.

> Una **recomendación** es **una propuesta de qué hacer, dirigida a una persona que conserva la
> autoridad** para aceptarla, modificarla, rechazarla, posponerla, pedir más información o no
> hacer nada todavía.

Y tres cosas que no es. **No es una decisión**: la decisión sigue siendo de quien ya la tenía.
**No es una autorización**: nada queda aprobado por haberse propuesto. **No es una ejecución**:
en este nivel, aprobar una recomendación no significa que la herramienta la ponga en marcha.
Significa que usted decidió, y lo que venga después lo hace quien lo hacía antes.

## No todo aviso necesita una propuesta

Vale la pena decirlo porque el orden de los capítulos invita a lo contrario.

Un aviso puede terminar en una revisión, en un registro, en una petición de información o
sencillamente en nada, **sin que nadie tenga que proponer un curso de acción**. El nivel 4 es un
permiso más, no la continuación obligatoria del nivel 3, y se concede **por tarea**: se puede
tener una tarea que propone y otra que solo avisa. Sigue sin existir «esta empresa ya está en el
nivel 4».

## Por qué esto tiene nombre propio

Al problema que aparece cuando una herramienta empieza a proponer se le llama **sesgo de
automatización**, y no es una preocupación inventada por este libro: **lo menciona
expresamente** el reglamento europeo de inteligencia artificial, en las obligaciones de
supervisión humana que establece **para los sistemas de alto riesgo** —**y solo para ellos**—,
donde exige que las personas encargadas de supervisar sean **conscientes** de él.

Una revisión académica de literatura lo define como **la tendencia a confiar en exceso en las
recomendaciones automáticas**. La misma revisión —de estudios sobre sanidad, derecho y
administración pública, **no sobre negocios pequeños**— señala que en el asunto intervienen más
cosas de las que uno diría: la experiencia profesional de quien recibe la propuesta, cuánta
verificación exige la tarea y **lo complicada que sea la explicación**.

No hace falta diagnosticar qué le pasó a Inés por dentro. Lo que importa es observable: **la
propuesta coincidía con lo que ella ya pensaba, y por eso resultaba fácil dejar de comprobarla.**
Una propuesta con la que uno está de acuerdo **puede dejar de parecer una propuesta** y empezar
a parecer una confirmación.

## Explicar no basta

Aquí está el giro del capítulo, y va contra el sentido común.

La misma revisión registra algo incómodo: aunque las explicaciones están pensadas para reducir
ese exceso de confianza, **una explicación demasiado técnica, demasiado exigente o incluso
demasiado simple puede reforzar una confianza mal colocada**; y añade que las explicaciones
**pueden aumentar la aceptación de un sistema sin mejorar la exactitud de la decisión**. El
marco de gestión de riesgos que ya citamos apunta en la misma dirección desde otro lado:
presentar información y explicaciones a personas **es complejo**, porque cada una deriva de
ellas un significado distinto.

Dicho de otra manera: **una recomendación bien explicada puede parecer una recomendación
correcta**, y no son lo mismo.

Así que la conclusión de este capítulo **no es «hay que explicar más»**. Es otra, más
incómoda y más útil:

> **Una recomendación no se acepta porque suene bien, porque venga explicada, porque traiga
> muchos datos, porque la haya producido una herramienta ni porque coincida con lo que usted ya
> pensaba. Antes de decidir, usted tiene que poder comprobar en qué se apoya.**

Y la otra mitad, porque sin ella la regla se lee al revés: **haberla comprobado no obliga a
aceptarla.** Comprobar es lo que hace falta **antes** de decidir; no es lo que decide.

Por eso a una propuesta no se le exige elocuencia, sino **que diga dónde ir a mirar** —un
documento, un registro, una regla escrita—, **algo que exista fuera de la propia
recomendación**. Una herramienta no se valida a sí misma.

## Evidencia y criterio, separados

El «porqué» de una recomendación son en realidad dos cosas, y juntas se confunden.

La **evidencia** es lo que respalda esta situación concreta: un dato, un documento, un registro,
una condición, un resultado observado. Tiene que poder mirarse, y por eso hay que decir **dónde
está** —en la versión que el negocio reconoce como referencia vigente, no en una cuya vigencia
nadie pueda confirmar—.

El **criterio** es la regla con la que esa evidencia se interpreta: por qué esos datos llevan a
esa propuesta y no a otra. Sale del criterio que usted documentó.

Separarlos cuesta una línea más y evita el error central de este capítulo: **una frase
convincente no es una prueba.** Con las dos cosas delante, una propuesta se puede discutir por
partes —los datos son correctos, la regla no aplica aquí— en lugar de aceptarse o rechazarse
entera.

Y conviene decir lo que no significa: que una recomendación diga qué regla aplica **no quiere
decir que su manual de criterio se haya convertido en un mecanismo automático**. Se apoya en él;
no lo reemplaza.

## Lo que no sabe

El nivel 4 pide algo más, y es lo que más cuesta escribir: que la propuesta **diga qué no sabe**.

Y no en forma de porcentaje. Un «noventa por ciento de confianza», por sí solo, **no dice qué
información falta, qué supuesto puede fallar ni qué haría cambiar la propuesta**. Por eso este
formato no lo usa **como sustituto de esas preguntas**. Si su negocio ya emplea una medida
propia, consérvela: lo que no puede es ocupar ese sitio. La incertidumbre se dice en el idioma
del negocio y **referida a esta propuesta**:

> «falta este dato» · «esta información puede estar desactualizada» · «hay dos reglas que
> podrían aplicarse» · «hay una excepción sin resolver»

**Y no vale un descargo general.** «Puede equivocarse» o «consúltelo con alguien» al pie de todas
las recomendaciones no es declarar incertidumbre: es no declararla. Si la misma advertencia
sirve para cualquier propuesta, no dice nada de esta.

Hay además una salida que conviene tener disponible desde el principio: **«no hay recomendación
todavía»**. Cuando falta información que importa, lo prudente es no proponer, y eso no es un
fallo del sistema ni del método.

## El formato de recomendación explicada

De ahí sale el entregable de este capítulo. **Seis componentes**, media hoja, y funciona escrito
a mano:

| | Componente | |
|---|---|---|
| **1** | **Qué propone, y para qué** | En una frase. Aquí cabe «no hay recomendación todavía» |
| **2** | **En qué evidencia se apoya, y dónde está** | El dato o el documento, **y en qué fuente mirarlo** |
| **3** | **Qué criterio o regla aplica** | La regla, separada de los datos |
| **4** | **Qué no sabe** | De esta propuesta. Nada genérico |
| **5** | **Qué haría cambiar la propuesta** | Qué información la volvería del revés |
| **6** | **La decisión** | ☐ aceptar ☐ modificar ☐ rechazar ☐ posponer ☐ pedir más información. Quién decidió, cuándo y, si modificó, qué cambió |

El componente **5** es el que más trabaja, aunque parezca el más blando: convierte una laguna en
una indicación de **dónde mirar**. Y el **6** tiene una regla propia: **ninguna de las cinco
respuestas está predeterminada.** No existe «aceptar por omisión»; las cinco son decisiones
explícitas de una persona, y la que se tome queda escrita.

**Con equipo**, quien recibe la propuesta y quien decide pueden ser dos personas distintas.
**Trabajando solo** son la misma, y eso no se disfraza de nada: no hay ninguna «autoaprobación»,
hay una persona decidiendo. Lo que el formato conserva en los dos casos es lo mismo: **la
propuesta y la decisión son cosas separadas**, aunque pasen por la misma mesa.

Y una advertencia sobre el propio formato, para no venderlo por más de lo que es: **está
construido contra el problema que este capítulo describe, y eso no es lo mismo que estar
comprobado.** **Ninguna de las fuentes revisadas sostiene que rellenarlo evite el exceso de
confianza.** Lo que hace es obligar a escribir lo que se queda sin escribir.

## Lo que Inés encontró al comprobar

Volvamos a la propuesta que le pareció bien.

Los datos eran correctos y la regla también: en su negocio se prioriza por horas de uso desde la
última revisión, y esas horas estaban bien contadas. Lo que la recomendación no sabía estaba en
el componente 4, escrito por ella misma al revisar: **ese equipo llevaba unas semanas trabajando
en condiciones distintas**, y eso no aparece en ningún parte, porque los partes registran horas
y no condiciones. Se lo había comentado un técnico de palabra.

No aceptó ni rechazó. **Modificó.** Mantuvo el adelanto del segundo equipo, que estaba bien
argumentado, y no pospuso el primero. Y anotó una cosa más, que era el verdadero hallazgo: que
sus partes de trabajo llevaban años sin recoger algo que sí cambia las prioridades.

La recomendación era defendible con lo que sabía. La modificación era defendible con lo que Inés
sabía y no estaba escrito. **Estar de acuerdo no es lo mismo que haber comprobado**, y la
diferencia entre las dos cosas es este capítulo entero.

## Señales de que puede avanzar al capítulo siguiente

Con **una** tarea basta, y ninguna de estas seis dice nada sobre acertar:

- Existe **permiso** para que esa tarea produzca propuestas.
- Se distingue **qué es la propuesta y qué es la decisión**.
- La propuesta **muestra su evidencia**, y dónde comprobarla.
- **Dice qué criterio aplica.**
- **Declara qué no sabe**, en términos de esa propuesta.
- Y hay **una decisión escrita**, de una persona.

«La rechacé» cumple esta señal igual que «la acepté». Y no hay ninguna obligación de seguir
subiendo.

## Lo que este capítulo no ha contestado

Inés terminó el mes con varias propuestas leídas, dos modificadas y una rechazada. Y con una
pregunta que ya no es sobre la calidad de las recomendaciones:

*Si ya puede proponerme qué hacer y yo sigo decidiendo cada vez, ¿hay algo que pueda hacer por
sí mismo sin volver a preguntármelo?*
