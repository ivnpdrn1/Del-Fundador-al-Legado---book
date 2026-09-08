# 07 — Método LEGADO

**Etapa:** 1 — Fundamentos. Aprobado en la Etapa 2.
**Estado:** **vigente.** El autor aprobó el 2026-09-06 la versión recomendada del
apartado 3 (D-004). **Esa es la formulación oficial del método** y la que debe usarse en
todo el manuscrito y en todo material derivado. El apartado 1 se conserva únicamente como
registro histórico de la versión provisional recibida; no debe citarse como vigente.

---

## 1. Versión provisional recibida

| Letra | Etapa |
|---|---|
| L | Localizar la dependencia. |
| E | Extraer y documentar el conocimiento crítico. |
| G | Gobernar procesos, permisos y decisiones. |
| A | Acompañar la operación con inteligencia artificial. |
| D | Delegar progresivamente con controles. |
| O | Observar y supervisar el legado a distancia. |

## 2. Evaluación

Se evaluó con seis criterios: claridad de cada verbo, distinción entre etapas, lógica de
la secuencia, correspondencia con el título, capacidad de producir entregables propios y
resistencia al uso comercial.

### 2.1 Lo que funciona y debe conservarse

- **El acrónimo es legítimo en español.** No fuerza palabras ni recurre a extranjerismos,
  que es donde fracasan la mayoría de las metodologías traducidas.
- **Coincide con el título.** El método se llama igual que el libro, lo que evita tener
  que enseñar dos nombres al lector y facilita después el uso comercial.
- **Seis etapas es un número manejable.** Con cuatro habría que agrupar cosas distintas;
  con ocho el lector deja de recordarlas.
- **La secuencia general es correcta.** Diagnosticar antes de documentar, documentar
  antes de gobernar, gobernar antes de automatizar y automatizar antes de delegar es la
  única de las órdenes posibles que no produce daño.

### 2.2 Problemas detectados

**Problema 1 — La letra A convierte la tecnología en una etapa.**
Presentar "Acompañar la operación con inteligencia artificial" como la cuarta etapa
sugiere que en el mes X toca comprar tecnología. Eso contradice una regla central del
propio libro: no automatizar antes de haber ordenado los datos. Además, el verbo
"acompañar" es vago y no dice quién acompaña a quién.

**Problema 2 — La letra O contiene una redundancia.**
"Observar y supervisar" son en la práctica sinónimos. Una etapa cuyo nombre repite dos
veces la misma idea comunica menos, no más.

**Problema 3 — Colisión de vocabulario con el modo sombra.**
El libro reserva el verbo "observar" para describir lo que hace la inteligencia
artificial en el nivel 2, cuando mira sin decidir. Usar el mismo verbo para la etapa
final, donde quien observa es el fundador, crea una ambigüedad innecesaria en el término
más delicado del libro.

**Problema 4 — La etapa final no nombra el resultado.**
"Observar el legado a distancia" describe la postura del fundador, no el estado de la
empresa. El resultado que el libro promete es que la empresa opere. Conviene que la
última letra lo diga.

**Problema 5 — La frontera entre G y D puede difuminarse.**
Gobernar incluye fijar límites de autoridad, y delegar consiste en usar esos límites. Si
no se separan con precisión, los capítulos 10 y 18 se repetirán. La distinción debe ser:
**G escribe la regla; D la pone en práctica con personas concretas y mide el resultado.**

### 2.3 Sobre el orden de A y D

Se consideró adelantar D antes de A, con el argumento de que delegar en personas debería
preceder a introducir tecnología. Se descarta, y conviene explicitar el motivo en el
libro porque es una de sus tesis distintivas:

> La delegación fracasa cuando el fundador no tiene forma de ver lo que ocurre después
> de delegar. La capa de observación y alerta es lo que hace tolerable soltar. Por eso
> se instala antes de delegar, no después.

No obstante, la delegación humana **no empieza** en la etapa D: empieza en G, cuando se
escribe la matriz de autoridad. Lo que ocurre en D es la transferencia progresiva y
medida. Esto debe quedar dicho en el libro para evitar la lectura de que el fundador
delega primero en una máquina y luego en su equipo.

## 3. Versión vigente (aprobada el 2026-09-06, D-004)

**Formulación oficial. No se admite ninguna variante.**

| Letra | Etapa |
|---|---|
| **L** | Localizar la dependencia. |
| **E** | Extraer el conocimiento y el criterio. |
| **G** | Gobernar decisiones, permisos y controles. |
| **A** | Asistir la operación con tecnología supervisada. |
| **D** | Delegar de forma progresiva y verificable, en personas, procedimientos o sistemas supervisados. |
| **O** | Operar sin dependencia y sostener el legado. |

### 3.1 Cambios respecto de la versión provisional y su justificación

| Letra | Etapa recomendada | Cambio respecto a la versión provisional |
|---|---|---|
| **L** | **Localizar** la dependencia. | Sin cambios. |
| **E** | **Extraer** el conocimiento y el criterio. | Se añade "el criterio". Es la aportación diferencial del libro y debe estar en el nombre. |
| **G** | **Gobernar** decisiones, permisos y controles. | Se sustituye "procesos" por "controles". Los procesos se documentan en E; lo que se gobierna son decisiones y límites. |
| **A** | **Asistir** la operación con tecnología supervisada. | Cambia el verbo y el sustantivo. "Asistir" subordina explícitamente la herramienta; "tecnología supervisada" evita que la etapa se lea como "comprar inteligencia artificial". |
| **D** | **Delegar** de forma progresiva y verificable. | Se sustituye "con controles" por "verificable". Los controles ya son de G; lo propio de D es que la delegación produzca evidencia. |
| **O** | **Operar** sin dependencia y sostener el legado. | Cambia el verbo. Elimina la redundancia observar/supervisar, libera "observar" para el modo sombra y nombra el resultado en lugar de la postura. |

**Justificación en una frase:** los seis cambios buscan que cada letra nombre una acción
distinta, que ninguna palabra se use con dos significados en el libro y que la
tecnología no ocupe el lugar de un objetivo cuando es un medio.

**Consecuencia de la aprobación:** el verbo «observar» queda reservado en todo el libro a
la conducta del sistema en el nivel 2, sin ambigüedad, porque ha desaparecido del nombre
de la etapa O. Así se registra en `06-control-de-continuidad.md`, apartado 3.

## 4. Definición preliminar de cada etapa

Cada etapa se define con los diez elementos exigidos. Las herramientas citadas están
catalogadas en `recursos/README.md` y todavía no están redactadas.

---

### L — Localizar la dependencia

**Propósito.** Sustituir la sensación de que "aquí todo pasa por mí" por una medida
comparable en el tiempo.

**Diagnóstico.** Recuento durante dos semanas de: interrupciones recibidas por la persona
clave, decisiones que solo ella puede tomar, compromisos que solo ella puede cerrar y
asuntos que quedan detenidos cuando no está disponible. **Trabajando sola**, el recuento es
el mismo cambiando quién interrumpe: lo que llega de clientes y proveedores, lo que solo
ella sabe empezar y lo que queda esperando a que vuelva.

**Preguntas a la persona clave.**
1. ¿Qué se detiene hoy si usted no contesta el teléfono?
2. ¿A cuántas personas debe usted responder al día para que la operación siga?
3. ¿Qué tres relaciones externas se enfriarían si usted dejara de atenderlas?
4. ¿Cuándo fue la última vez que se ausentó siete días seguidos, y qué pasó?
5. ¿Qué información solo usted sabe dónde encontrar?

**Acciones.** Registro de interrupciones. Recuento de decisiones. Cálculo del **Índice de
Dependencia de la Persona Clave**. Inventario de lo que sigue concentrado en una sola
persona. Con equipo, además, conversación con dos o tres personas que participen en las
decisiones; trabajando solo, ese contraste se sustituye por el ejercicio de explicar una
decisión por escrito sin ejecutarla.

**Herramientas.** Índice de Dependencia de la Persona Clave (1). Cuestionario de preparación
para elegir su participación (2, renombrada por D-069). Inventario del conocimiento crítico
(3).

**Indicadores.** Valor inicial del índice. Número de decisiones exclusivas. Horas
semanales dedicadas a asuntos operativos. Duración máxima de ausencia sin incidencias.

**Riesgos.** Que se conteste lo que se cree que debería ocurrir en lugar de lo que ocurre.
Que quien responda suavice por respeto. Que el diagnóstico se viva como una evaluación
personal, siendo que **no evalúa a nadie: localiza dónde está concentrado el conocimiento**.

**Responsables.** La persona clave. Con equipo, puede ayudar alguien que registre los datos
sin interpretarlos. **Trabajando sola no hace falta observador**: el registro lo lleva ella
misma, por escrito y con fecha.

**Evidencia de avance.** El índice calculado, fechado y archivado, y el inventario iniciado.

**Criterio de paso a E.** Existe una lista escrita y ordenada de las dependencias de mayor
impacto, aceptada por la persona clave. **El número diez es un límite práctico por dónde
empezar, no un umbral demostrado.**

---

### E — Extraer el conocimiento y el criterio

**Propósito.** Llevar a un soporte consultable lo que el negocio necesita para seguir
funcionando, incluido el porqué de las decisiones.

**Diagnóstico.** De cada dependencia identificada en L, en qué estado está: solo en la
memoria de una persona, escrita a medias, repartida en correos y conversaciones, documentada
y localizable, o **ya usada por alguien sin recurrir a la persona clave**. Los cinco estados
y la advertencia de que **documentado no es transferido** están en la herramienta 3.

**Preguntas a la persona clave.**
1. ¿Por qué a este cliente se le dan condiciones distintas, y desde cuándo?
2. ¿Qué mira usted primero cuando algo no le cuadra?
3. Si alguien llegara nuevo a esto, ¿qué haría siguiendo el procedimiento al pie de la
   letra que aun así estaría mal?
4. ¿Qué acuerdos existen que no consten por escrito?
5. ¿Qué hace usted distinto de lo que dice el manual, y por qué?

**Acciones.** Partir del inventario priorizado que produce L. Trazar el **proceso real**,
no el oficial, de las dependencias de más impacto. Mapa de decisiones. Mapa de relaciones
críticas. Registro de excepciones. Primera versión del Manual de criterio.

**Herramientas.** Mapa de decisiones (4). Mapa de relaciones críticas (5). Registro de
excepciones (6). Plantilla del Manual de criterio (7). El inventario del conocimiento
crítico (3) pertenece a L y es de donde E toma su material. **El proceso real se traza
dentro del capítulo 7 y no es una de las dieciocho herramientas.**

**Indicadores.** Cuántas de las dependencias prioritarias han pasado de la memoria a un
soporte consultable. Número de excepciones registradas con su motivo. **Con equipo**, número
de relaciones críticas con un segundo contacto asignado; **trabajando solo**, número de
relaciones críticas cuyo contexto queda escrito y con una vía de continuidad declarada,
aunque esa vía sea reconocer que hoy no la hay.

**Riesgos.** Documentar todo y no terminar nada. Documentar el procedimiento y omitir el
criterio, que es lo valioso. Que la documentación quede en un formato que nadie consulta.
Exponer en el documento información sensible sin clasificarla.

**Responsables.** La persona clave aporta el contenido. **Con equipo**, conviene que otra
persona redacte y pregunte: quien sabe algo da por supuesto lo que más falta. **Trabajando
sola**, ese segundo par de ojos no existe y no se inventa; se sustituye por dos mecanismos
más débiles y honestos: escribir primero y releer días después, y **comprobar el documento
usándolo**, siguiéndolo al pie de la letra la próxima vez sin recurrir a la memoria.

**Evidencia de avance.** Documentos fechados, con autor, con fecha de revisión y con una
persona responsable de mantenerlos.

**Criterio de paso a G.** Las dependencias de mayor impacto están documentadas y **han
dejado de ser exclusivamente personales**. Ese es el principio; la comprobación cambia según
el caso. **Con equipo:** otra persona ha ejecutado la tarea siguiendo el documento, sin
preguntar. **Trabajando solo:** el documento se ha usado al menos una vez tal como está,
sin recurrir a la memoria, y produjo el mismo resultado; o lo ha utilizado un colaborador
externo, cuando exista. **No se inventan empleados ni segundos contactos internos para poder
cerrar la etapa**, y una comprobación diferida por la propia persona es más débil que una
ajena, lo que debe reconocerse en lugar de disimularse. La prueba formal de ausencia es otra
cosa y llega en el capítulo 24.

---

### G — Gobernar decisiones, permisos y controles

**Propósito.** Escribir quién puede decidir qué, hasta qué límite, con qué información y
quién lo revisa. Sin esto, delegar es un acto de fe y automatizar es imprudente.

**Diagnóstico.** ¿Existen límites de gasto escritos? ¿Alguien puede iniciar y aprobar la
misma operación? ¿Quién revisa las excepciones? ¿Existe registro de quién hizo qué?

**Preguntas al fundador.**
1. ¿Hasta qué monto puede comprometer dinero cada responsable, hoy y por escrito?
2. ¿Qué decisiones no delegaría bajo ninguna circunstancia, y por qué?
3. ¿Quién revisa lo que hace la persona en quien más confía?
4. ¿Qué ocurre hoy cuando alguien se salta un límite?
5. ¿Qué decisiones toma usted que en realidad no necesitan su criterio?

**Acciones.** Matriz de autoridad y aprobaciones. Separación de funciones en los procesos
que mueven dinero, inventario o datos personales. Definición de la lista de decisiones
reservadas a personas. Reglas de excepción con vigencia y responsable. Registro de
actividad.

**Herramientas.** Matriz de autoridad y aprobaciones. Registro de excepciones, ampliado
con vigencia y revisor.

**Indicadores.** Porcentaje de procesos críticos con límite escrito. Número de procesos
con separación de funciones. Número de excepciones vencidas sin revisar. Tiempo medio de
aprobación.

**Riesgos.** Escribir una matriz que nadie aplica. Fijar límites tan bajos que todo
vuelva al fundador. Confundir control con desconfianza al comunicarlo al equipo.
Establecer controles que la legislación local exija de otra forma: este punto requiere
revisión profesional en cada jurisdicción.

**Responsables.** El fundador y la propiedad. Contador o auditor externo como revisor.

**Evidencia de avance.** Matriz firmada, comunicada al equipo y aplicada durante al menos
un ciclo mensual completo.

**Criterio de paso a A.** Existe una matriz de autoridad vigente, hay registro de quién
aprueba qué, y los datos que la tecnología va a observar están clasificados por
sensibilidad.

---

### A — Asistir la operación con tecnología supervisada

**Propósito.** Incorporar una capa que observe, ordene, resuma, compare y avise, siempre
por debajo de una persona responsable, y hacerla avanzar por niveles.

**Diagnóstico.** ¿Los datos son confiables y tienen una fuente única? ¿Qué información no
puede salir de la empresa? ¿Qué se quiere saber sin tener que ir a preguntarlo?

**Preguntas al fundador.**
1. ¿Qué le gustaría que alguien revisara todos los días sin que usted lo pida?
2. ¿Qué diferencia, si apareciera, querría saber antes de que termine el día?
3. ¿Qué información no debe salir nunca de la empresa?
4. ¿Qué error automático sería inaceptable, aunque ocurriera una sola vez?
5. ¿Cómo sabría usted que la herramienta se equivocó?

**Acciones.** Ordenar datos y definir fuentes únicas antes de conectar nada. Clasificar
la información. Fijar el nivel de autonomía máximo por tipo de tarea. Ejecutar un periodo
en modo sombra en el que el sistema observa y registra sin decidir. Comparar sus
observaciones con las decisiones humanas. Medir aciertos y errores antes de dar un paso
más. Activar alertas. Después, y solo después, recomendaciones con aprobación humana.

**Herramientas.** Lista de información que no debe entregarse libremente a una
inteligencia artificial. Lista de verificación del modo sombra. Modelo de alertas
críticas. Matriz de niveles de autonomía.

**Indicadores.** Duración del periodo en modo sombra. Coincidencia entre lo que el
sistema señala y lo que un humano habría señalado. Falsas alarmas por semana. Excepciones
detectadas antes que por una persona. Porcentaje de recomendaciones aceptadas.

**Riesgos.** Automatizar sobre datos malos. Confiar en una herramienta que no explica su
razonamiento. Enviar información sensible a servicios de terceros sin haberlo evaluado.
Alertas excesivas que el equipo aprende a ignorar. Depender de un proveedor único sin
plan de salida. Creer que el sistema entiende el negocio porque acierta en lo fácil.

**Responsables.** Una persona nombrada como responsable de la herramienta. El fundador
como autoridad final. Revisión externa de seguridad y de protección de datos, según la
jurisdicción.

**Evidencia de avance.** Registro comparado de modo sombra durante un periodo completo,
con aciertos y errores contados.

**Criterio de paso a D.** El sistema lleva al menos un ciclo completo emitiendo alertas
útiles, con un número tolerable de falsas alarmas, y existe un procedimiento escrito para
detenerlo.

---

### D — Delegar de forma progresiva y verificable

**Propósito.** Transferir responsabilidades reales, con límites escritos y con evidencia de
resultado, en lugar de transferirlas de golpe o no transferirlas nunca.

**Ampliación del 2026-09-07 (D-026): a quién o a qué se delega.** La formulación original
suponía personas concretas. Sigue siendo el caso principal en una empresa con estructura,
pero no en un negocio de una sola persona, donde contratar puede no ser deseado ni
necesario. Los destinatarios legítimos de la transferencia son tres:

1. **Personas.** Equipo, socios, colaboradores externos, un sucesor, un comprador.
2. **Procedimientos.** Lo que antes exigía criterio pasa a estar escrito y cualquiera
   —incluido usted dentro de dos años— puede seguirlo.
3. **Sistemas supervisados.** Automatizaciones y herramientas dentro de límites escritos,
   con registro y con un procedimiento de detención.

Las tres exigen lo mismo: límite escrito, evidencia del resultado y una persona con nombre
que responda. **Delegar en un sistema no traslada la responsabilidad al sistema.** Un
capítulo que presente la contratación como el único camino incumple esta ampliación.

**Diagnóstico.** ¿Qué decisiones podrían pasar hoy a otra persona sin riesgo? ¿Quién está
preparado, quién puede estarlo y quién no lo estará?

**Preguntas al fundador.**
1. ¿Qué decisión, si se tomara mal una vez, no pondría en riesgo la empresa?
2. ¿A quién ha corregido más veces, y por qué motivo se repite?
3. ¿Qué necesitaría ver para no revisar una decisión que ya delegó?
4. ¿Qué va a hacer usted con el tiempo que libere?
5. ¿Qué señal le indicaría que hay que dar marcha atrás en una delegación?

**Acciones.** Plan de transición por bloques, de menor a mayor riesgo. Periodo de
delegación acompañada: la otra persona decide, el fundador revisa después, no antes.
Reducción gradual de la revisión. Pruebas de ausencia de veinticuatro horas y de siete
días. Revisión posterior de lo que falló y corrección del sistema, no de la persona.

**Herramientas.** Plan de transición de cien días. Prueba de ausencia de veinticuatro
horas y de siete días.

**Indicadores.** Número de decisiones transferidas y sostenidas durante tres meses.
Frecuencia con la que el fundador revoca una decisión delegada. Interrupciones recibidas
durante una ausencia. Asuntos detenidos durante la prueba de ausencia.

**Riesgos.** Delegar la responsabilidad sin la autoridad. Retirar la delegación al primer
error, lo que enseña al equipo a no decidir. Delegar por parentesco y no por capacidad.
Sobrecargar a una sola persona de confianza y crear una segunda dependencia idéntica a la
primera.

**Responsables.** El fundador. Cada persona receptora, por escrito. Un tercero que
observe la prueba de ausencia y registre lo ocurrido.

**Evidencia de avance.** Informe de la prueba de ausencia, con lo que funcionó, lo que se
detuvo y las correcciones aplicadas.

**Criterio de paso a O.** Una prueba de ausencia de siete días completada sin incidencias
graves y sin que el fundador haya tenido que intervenir fuera de los canales previstos.

---

### O — Operar sin dependencia y sostener el legado

**Propósito.** Estabilizar el nuevo funcionamiento y darle al fundador una posición de
supervisión con visibilidad y autoridad, pero sin operación diaria.

**Diagnóstico.** ¿Qué necesita saber el fundador cada día, cada semana y cada mes para
estar tranquilo, y qué está mirando de más por costumbre?

**Preguntas al fundador.**
1. ¿Qué tres cifras necesita ver cada semana para dormir tranquilo?
2. ¿Qué debe interrumpirle a cualquier hora, y qué puede esperar?
3. ¿Cuál es su papel a partir de ahora, dicho en una frase?
4. ¿Quién decide si usted no está disponible en veinticuatro horas?
5. ¿Cómo se revisará todo esto dentro de un año?

**Acciones.** Definir el tablero del propietario. Fijar el informe diario, el semanal y
el umbral de alerta crítica. Establecer el nuevo papel del fundador por escrito, con lo
que sí hace y lo que ya no hace. Calendario de revisión anual. Plan de contingencia y
copias de seguridad. Revisión periódica de permisos.

**Herramientas.** Modelo de informe diario. Modelo de informe semanal. Evaluación anual
de continuidad.

**Indicadores.** Índice de Dependencia de la Persona Clave comparado con el valor inicial. Horas
semanales del fundador en operación. Número de intervenciones fuera de los canales
previstos. Resultado de la evaluación anual.

**Riesgos.** Volver a intervenir en todo ante la primera crisis. Un tablero con tantos
indicadores que nadie lo mira. Que el sistema se degrade porque nadie lo mantiene. Que el
fundador pierda propósito y eso, y no la empresa, haga fracasar la transición. Que la
supervisión se convierta en control informal que anule la delegación.

**Responsables.** El fundador como supervisor. La dirección operativa. Un revisor externo
anual.

**Evidencia de avance.** Evaluación anual de continuidad firmada, con comparación
interanual del índice.

**Criterio de cierre.** La empresa opera durante un trimestre dentro de los límites
acordados, el fundador recibe información sin pedirla, y existe una fecha en el
calendario para la siguiente revisión.

---

## 5. Reglas transversales del método

Se aplican en las seis etapas y ninguna es negociable:

1. Siempre existe una persona responsable con nombre.
2. Ninguna etapa se salta. Se puede recorrer despacio, no en desorden.
3. Nada se automatiza antes de estar ordenado y escrito.
4. Todo mecanismo automático debe poder detenerse, y debe estar escrito cómo.
5. Toda recomendación automática debe poder explicarse y mostrar su evidencia.
6. El fundador fija la velocidad de la transición.
7. Cada etapa deja un documento fechado. Sin documento, la etapa no está hecha.
8. Lo que se mide al principio se vuelve a medir al final, con el mismo instrumento.
9. Ningún ejemplo, plantilla o registro del libro contiene información de una empresa
   real.
10. Donde la decisión toca obligaciones legales, fiscales, laborales o de protección de
    datos, el libro remite a profesionales de la jurisdicción correspondiente.

## 6. Relación con la estructura del libro

| Parte | Capítulos | Etapas del método |
|---|---|---|
| I — El negocio que depende de una persona | 1–5 | Antesala de L: reconocimiento del problema. |
| II — Convertir experiencia en memoria transferible | 6–10 | L, E y el inicio de G. |
| III — Construir una mano derecha digital | 11–16 | A, con G como requisito previo. |
| IV — Transferir el control sin perderlo | 17–21 | D, apoyada en G. |
| V — Del fundador al legado | 22–25 | O. |

Cada capítulo declara en su encabezado la etapa del método a la que pertenece. Ese dato
permite comprobar en la Etapa 4 que el método avanza de forma pareja y que ninguna letra
queda sin desarrollo suficiente.
