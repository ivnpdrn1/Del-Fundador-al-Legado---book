---
capitulo: 13
parte: 3
titulo: "El periodo de sombra y las primeras alertas"
etapa_metodo: "A"
estado: borrador
palabras: 2213
casos_usados: ["C-10"]
recursos_producidos: ["verificacion-modo-sombra.md", "modelo-alertas-criticas.md"]
afirmaciones_por_verificar: []
ultima_actualizacion: "2026-09-09"
---

# 13. El periodo de sombra y las primeras alertas

Terminó el capítulo anterior con una pregunta: ya sé qué le permito hoy, ¿cómo averiguo si
merece más sin entregarle todavía ninguna decisión?

Hay una manera evidente de contestarla, y es la equivocada: probar la herramienta en algo
pequeño, que no importe, a ver qué tal sale. El problema de esa prueba es que funciona
demasiado bien. Una tarea que no importa se hace con información incompleta, sin las
excepciones de siempre y sin nadie mirando el resultado, así que lo único que se aprende es
cómo se comporta el sistema **en una tarea que no importa**.

La respuesta es la contraria y solo suena rara la primera vez: **póngalo a trabajar sobre algo
real, y no le dé la decisión.**

## Julián y las dos listas

Julián hace rutas de reparto por su cuenta. Trabaja solo: recoge, lleva y responde él de todo.
Cada mañana repasa lo que ha entrado y decide qué acepta para ese día y qué aparta para
llamar antes.

Probó a que una herramienta hiciera ese mismo repaso. No para que decidiera: para que dijera,
por su cuenta, qué apartaría ella. Él siguió haciendo exactamente lo que hacía siempre —mirar,
decidir, salir— y al volver comparó las dos listas.

Unos días las dos listas coincidían y otros no. Y hubo uno en que la diferencia importaba.

## Qué es el modo sombra

Lo que hizo Julián tiene nombre en este método, y conviene decir enseguida que **el nombre es
una convención de este libro**: no es un estándar, ni una certificación, ni un término técnico
reconocido por nadie.

> **Modo sombra:** un sistema **trabaja sobre una tarea real y produce su propia salida**, pero
> esa salida **no gobierna la decisión ni la ejecución**. La operación sigue por su
> procedimiento de siempre, decide quien decidía, y después **se compara**.

Y va acompañado de seis deslindes, porque la palabra invita a seis malentendidos distintos.

**Uno. No es secreto.** «Sombra» describe que **la salida no tiene autoridad**, no que el
sistema esté escondido. No autoriza vigilar a nadie sin decírselo, ni observar a escondidas, ni
usar información de forma clandestina. Lo que puede entregarse a una herramienta lo decidió
usted en el capítulo 11, y aquí no cambia nada.

**Dos. No es entrenamiento.** El sistema **no aprende de usted** durante este periodo, no se
entrena con sus decisiones y no absorbe su criterio. Lo que hace es producir salidas y quedar
registrado junto a lo que ocurrió. Si algo mejora después, será porque **una persona** cambió
la información, una regla o un permiso.

**Tres. No es un examen que el sistema apruebe.** No hay resultado obligatorio y no hay nota
de corte.

**Cuatro. No es una medición.** Sin puntuación, sin porcentaje, sin tasa de aciertos. Si su
negocio ya tiene una medida que sirve para esto, úsela; el método no le inventa una.

**Cinco. No cambia quién manda.** La matriz del capítulo 10 sigue igual. Decide quien ya
decidía.

**Seis. No ejecuta.** No actúa, no corrige, no envía, no bloquea y no ajusta nada. Si lo hace,
esto ya no es modo sombra.

Aquí es, además, donde el trabajo de las dos partes anteriores se pone por primera vez delante
de una tecnología. **Clonar el ADN Empresarial no es enseñarle a una máquina a imitarle**: es
dejar accesibles, dentro de condiciones que usted fijó, la información, el criterio escrito,
los procesos, las excepciones, las relaciones y los límites. El modo sombra es la primera
comprobación de qué ocurre cuando un sistema trabaja con todo eso **sin autoridad para
usarlo**.

Y tiene un motivo que no es del libro. El marco de gestión de riesgos del instituto
estadounidense de normas y tecnología —el documento de uso voluntario que ya citamos— pide que
los criterios se demuestren **en condiciones parecidas a las del uso real**, y advierte que
medir en un entorno controlado **puede dar un resultado distinto del que aparece en la
operación de verdad**.

## Qué se compara

Cinco cosas, y ninguna más:

**qué información había · qué señaló el sistema · qué ocurrió realmente, o qué se decidió · qué
diferencia hay · qué explicación tiene esa diferencia**

Julián lo anotó así el día que las listas no coincidieron. El sistema había apartado un
encargo que él aceptó sin dudarlo. Su primera reacción: *se ha equivocado*.

## Seis maneras de leer una diferencia

No se había equivocado. Y él tampoco.

El sistema apartó ese encargo porque **la hora de recogida y la dirección venían en dos
documentos distintos y no cuadraban**. Julián lo aceptó porque ese cliente manda siempre la
hora mal y la corrige por teléfono, cosa que Julián sabe y no ha escrito en ninguna parte. Los
dos tenían razón con la información que cada uno tenía.

Por eso una diferencia admite **seis lecturas**, y ninguna vale más que las otras:

1. se equivocó el sistema;
2. se equivocó la persona;
3. faltaba información;
4. había una excepción;
5. la regla estaba mal formulada;
6. **las dos respuestas eran defendibles con información distinta.**

La de Julián fue la tercera y la sexta a la vez. Hubo también un caso en sentido contrario: un
encargo que él apartó y el sistema no señaló, porque el motivo no estaba escrito en ningún
documento. Eso también se anota, y no siempre tiene arreglo.

Las dos cosas tienen nombre en esta hoja, y con eso basta. **Falso aviso:** el sistema señaló
algo y no había nada que mereciera atención. **Omisión:** ocurrió algo que debía haberse
señalado y el sistema no lo señaló. No hacen falta métricas para anotarlas: hacen falta dos
columnas y la honestidad de rellenarlas cuando el sistema queda mal **y cuando queda bien**.

## Comparar no es imitar

Aquí está la trampa del capítulo, y es fina.

Cuando el comparador es una decisión de una persona, es tentador tratarla como la respuesta
correcta y medir cuánto se aparta el sistema de ella. **No es eso.** Ese casillero se llama
**decisión real tomada**, no «respuesta correcta», y se llama así para recordar que **una
persona también se equivoca**. El propio marco citado advierte que el dato con el que uno
compara **puede sencillamente no existir**.

Si la tarea tiene un desenlace comprobable —llegó o no llegó, faltaba o no faltaba—, entonces
sí hay un hecho, y se anota como **resultado observado**. La diferencia entre las dos cosas
importa más de lo que parece: **el objetivo no es que el sistema acabe pareciéndose a usted.**

## Con equipo, la misma hoja y una persona más

Julián trabaja solo, así que ejecuta, decide y revisa la comparación él mismo. La hoja lo
admite y **no finge que eso sea una revisión independiente**: no lo es, y decirlo es parte de
usarla bien.

Con equipo cambia una cosa, y solo una: **la comparación la revisa quien tenga esa
responsabilidad de verdad**, según la matriz del capítulo 10. El modo sombra **no la modifica**
y no crea ningún puesto nuevo para vigilar a la máquina. Si en su negocio esa decisión la
autoriza una función concreta, es esa función la que mira las diferencias. Y hay algo que esa
separación puede aportar: **las excepciones se explican distinto cuando hay que explicárselas a
alguien.**

## La lista de verificación del modo sombra

En el anexo está la **herramienta 10**. Son seis bloques, caben en dos páginas y se rellenan a
mano: la tarea observada, qué información puede recibir, qué salida produce y con qué se
compara, dónde queda registrado y quién lo revisa, qué diferencias aparecieron y cómo se
explican, y la decisión.

Lo que la hoja **no** le pregunta: si la herramienta ya aprendió, si usted ya confía, qué
porcentaje acertó o cuánto tiempo lleva. Ninguna de esas preguntas se puede contestar, y las
cuatro empujan hacia el mismo sitio.

## Qué hacer con la evidencia

La revisión termina en **una** de estas seis, y las seis son legítimas:

**mantener en sombra · revisar información · revisar la regla · reducir el alcance · detener ·
permitir alertas de nivel 3**

No hay «aprobado», no hay «listo» y **no hay obligación de subir**. Julián eligió dos a la vez
sobre tareas distintas: revisar la regla en una y permitir alertas en la otra.

## Cuánto dura esto

Es la pregunta que este capítulo tiene que contestar, y la respuesta honesta es incómoda:
**este método no le va a dar un número.**

No por prudencia. **Las fuentes revisadas no establecen una duración ni una cadencia
universales**, y el propio instituto de normas, en un informe de 2026 sobre la vigilancia de
sistemas ya en funcionamiento, coloca **«cuál es la cadencia correcta»** entre sus **preguntas
abiertas**, y describe las metodologías validadas del asunto como incipientes. Eso no
demuestra que no exista una duración adecuada; dice que **las fuentes revisadas no la
establecen**, y que quien le prometa una cifra se la está sacando de algún sitio que no es la
evidencia.

Lo que este método sí dice: **no se fija por calendario.** La evidencia se acumula a partir de
situaciones reales que le importen a esa tarea, y **una persona decide cuándo mirarla**. Una
tarea que ocurre a menudo dará más ocasiones de comparar que una excepción rara, y eso es una
observación sobre la tarea, no una fórmula.

## Del registro a una persona

Hasta aquí, todo lo que produce el sistema va a un papel que alguien mira después. Eso es el
**nivel 2**: observa, clasifica, resume, compara y registra.

El **nivel 3** cambia una sola cosa, y no es la que se piensa. **No es que la herramienta se
haya vuelto más lista.** Es que **su salida deja de ir a un registro y empieza a ir a una
persona**. Informa, organiza, recuerda, detecta diferencias y avisa. Sigue sin proponer qué
hacer y sigue sin ejecutar nada.

La pregunta también cambia. En el nivel 2 era: *¿qué habría señalado el sistema, sin que nadie
actuara por eso?* En el nivel 3 es: **¿qué merece que el sistema me interrumpa?**

## Qué es una alerta, y qué no

> Una **alerta** dice: **algo necesita su atención.**
> Una **recomendación** dice: propongo que haga esto.

La primera es este capítulo. La segunda es el siguiente, y no se adelanta.

«Esta hora de recogida no coincide con la de la otra hoja» es una alerta. «Rechace el encargo»
no lo es, y no puede aparecer en este nivel.

Una alerta tampoco es una decisión: no aprueba, no rechaza, no compromete, no firma, no ordena
y no ejecuta. **Eleva algo a la atención de alguien, y la autoridad se queda donde estaba.**

Y **«crítico» no es una categoría oficial de nada**. Aquí significa una condición que **su
negocio** ha decidido que merece interrumpir, y se escribe **antes** de que ocurra siempre que
se pueda. La de Julián le salió del propio periodo de sombra: *si la hora de recogida y la
dirección no coinciden entre los dos documentos, avísame antes de que salga la ruta.*

## El modelo de alertas críticas

La **herramienta 11** sirve para escribir eso sin que se convierta en otra cosa. Siete campos:
la condición, de qué fuente sale la información, por qué merece atención, a quién se avisa,
cuándo, qué debe ver esa persona para juzgarlo y cuándo deja de estar activa.

El campo sexto es el que impide que un aviso sea inútil: **qué condición se cumplió y qué
información la disparó**. Con eso una persona puede juzgar en diez segundos si el aviso importa.
No hace falta que el sistema explique cómo llegó ahí —**eso es del capítulo siguiente**—; hace
falta que se pueda seguir el rastro de la condición.

El «cuándo» tiene tres respuestas y solo tres: **interrumpir ahora · mostrar en la próxima
revisión · solo registrar**. La «próxima revisión» no es una periodicidad que imponga el
libro: es la que su negocio ya tenga.

Hace falta porque el nivel 3 tiene un modo propio de fracasar, y es sencillo de enunciar: **si
todo interrumpe, «crítico» deja de distinguir nada.** No es una estadística, es aritmética de
la atención. La tercera columna existe para eso.

Cuando el sistema no pueda determinar si una condición se cumple, eso puede convertirse en un
aviso para revisar. **Nunca en una decisión.**

## Señales de que puede avanzar al capítulo siguiente

Con **una** tarea basta, y hacen falta seis cosas:

- Hay registro de lo que el sistema habría señalado.
- Hay un resultado real con el que compararlo.
- Las diferencias están revisadas —**y que no hubiera ninguna también cuenta**.
- Está escrito qué merece un aviso.
- Está escrito quién lo recibe.
- **Y usted ha decidido** qué hacer con el permiso.

Cualquiera de las seis salidas cumple esta señal. **«Lo detuve» vale exactamente lo mismo que
«permití alertas de nivel 3»**, y si alguna vez le parece que no, vuelva al capítulo 12: el
permiso era suyo, no de la herramienta.

## Lo que este capítulo no ha contestado

Julián terminó con una condición escrita y con un sistema que ya puede interrumpirle. Y con la
pregunta siguiente, que es la que abre el capítulo 14:

*Si ya puede llamar mi atención, ¿cuándo debería proponerme qué hacer?*
