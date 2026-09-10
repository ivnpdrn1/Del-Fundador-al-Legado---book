# Plan de investigación

**Etapa:** 1 — Fundamentos. Ejecutada en parte en la Etapa 2.
**Estado:** estrategia vigente. **Q-01 a Q-04 resueltas el 2026-09-06**, con doce fuentes
abiertas y leídas y cuatro consultadas y descartadas. Ver
`investigacion/fuentes-verificadas.md`. Q-05 a Q-12 siguen sin iniciar.

Declaración explícita, para que no quede ninguna duda al leer este repositorio: durante la
Etapa 1 no se verificó ninguna fuente y no se citó ningún dato. La investigación empezó en
la Etapa 2, limitada a Q-01, Q-04 y a lo necesario para la introducción y el capítulo 1.
Lo que sigue es la estrategia y una lista de **candidatas a consultar**; el listado de
fuentes realmente usadas está en `fuentes-verificadas.md` y solo ese archivo respalda
afirmaciones.

---

## 1. Principio rector

El libro puede sostenerse casi por completo sobre razonamiento, método y ejemplos
ficticios. Los datos externos son un refuerzo, no un cimiento. Esta decisión reduce
drásticamente el riesgo de publicar cifras frágiles o mal atribuidas.

En consecuencia:

- **Se prefiere una afirmación cualitativa bien argumentada a una cifra sin fuente
  sólida.**
- Se admite escribir "es frecuente que…" y no escribir ningún porcentaje.
- Una cifra solo entra si aporta algo que el argumento no puede aportar por sí mismo.

## 2. Reglas de verificación

1. Toda cifra, estudio, autor, norma o afirmación factual se consulta **directamente en
   la fuente original**. No se cita a partir de resúmenes, artículos de prensa,
   agregadores ni de la memoria.
2. Se registra: título, institución u autoría, fecha de publicación, dirección web, fecha
   de consulta y qué afirmación concreta respalda.
3. No se inventan estadísticas, investigaciones, autores ni referencias.
4. No se cita ninguna fuente que no se haya abierto y leído en el pasaje pertinente.
5. Las afirmaciones importantes no dependen de una sola fuente.
6. Se prefiere, en este orden: organismos oficiales y estadísticos; universidades y
   centros de investigación académica; organizaciones profesionales reconocidas;
   organismos técnicos de normalización; informes de consultoría, solo cuando publiquen
   metodología.
7. Se comprueba la vigencia. Una cifra de hace ocho años se etiqueta con su fecha en el
   propio texto o no se usa.
8. Se distingue siempre entre hecho, inferencia, recomendación y propuesta propia.
9. Cuando una afirmación toque materia legal, fiscal, laboral, contable o de protección
   de datos, se acompaña de la advertencia de que varía por jurisdicción y requiere
   revisión profesional.
10. Toda afirmación pendiente se marca con `[POR VERIFICAR]` y se registra en
    `afirmaciones-por-verificar.md`.

## 3. Preguntas de investigación

Ordenadas por prioridad. La prioridad alta significa que el capítulo no puede escribirse
con solidez sin resolverla.

| # | Pregunta | Cap. | Prioridad | Estado |
|---|---|---|---|---|
| Q-01 | ¿Qué proporción del tejido empresarial es de propiedad familiar, y con qué definición de "empresa familiar" en cada fuente? | Intro, 1 | Alta | **Resuelta 2026-09-06.** F-001, F-002, F-004. No existe cifra mundial comparable; el libro cita dos cifras oficiales con su definición y su ámbito. |
| Q-02 | ¿Qué evidencia existe sobre tasas de continuidad entre generaciones, y qué fiabilidad tiene? | Intro, 21 | Alta | **Resuelta 2026-09-06 en sentido negativo.** No se localizó fuente primaria legible. Ninguna cifra generacional entra en el libro (D-016). El argumento se apoya en F-003 y F-012. |
| Q-03 | ¿Qué marcos reconocidos existen sobre continuidad del negocio y gestión de riesgos operativos? | 4, 16 | Alta | **Resuelta 2026-09-06.** F-005, F-006, F-011. |
| Q-04 | ¿Qué marcos existen sobre gestión de riesgos de la inteligencia artificial y qué recomiendan sobre supervisión humana? | 12, 15, 16 | Alta | **Resuelta 2026-09-06.** F-007, F-008, F-009, F-010. Coinciden con las reglas 4 y 5 del método (D-020). |
| Q-05 | ¿Qué obligaciones generales de protección de datos afectan a una pyme que trate información con herramientas de terceros, y cómo varían por jurisdicción? | 11, 16 | Alta | **RESUELTAS CONJUNTAMENTE con límites el 2026-09-09 (Etapa 3.10A)**: F-038 a F-042, las cinco leídas directamente en el documento oficial. **El hallazgo que decide el capítulo 11 es negativo y era previsible: no existe una regla única aplicable a todos los lectores.** Lo que sí existe es un conjunto de **preguntas de control que siguen sirviendo aunque cambie la jurisdicción**. Resultado completo al final de este documento. Antes: sin iniciar, prioridad alta por D-014. |
| Q-06 | ¿Qué dice la literatura académica sobre transferencia de conocimiento tácito en organizaciones pequeñas? | 2, 9 | **Alta** | **RESUELTA, para el capítulo 2 y para el capítulo 9. Cerrada el 2026-09-07 (Etapa 3.8A.1).** Ver «Q-06 · Q-13 · Q-16 — Resultado conjunto» al final de este documento. Antes: **resuelta para el capítulo 2 el 2026-09-07** con F-016 (Nonaka, *HBR* 1991, leída íntegra) y F-017 (ficha del editor de *The Tacit Dimension*). Aporta la distinción tácito/explícito, la imagen del maestro artesano y el enunciado de que el conocimiento no explicitado no se aprovecha por el conjunto. La parte que quedaba abierta —métodos de externalización del criterio, no solo diagnóstico— **se cerró en la Etapa 3.8A.1** con las tres categorías de técnicas de F-028, leídas en el resumen del propio artículo. **No queda ninguna parte de Q-06 abierta.** **Lo que no se encontró:** literatura específica sobre organizaciones pequeñas; F-016 es literatura general de gestión con ejemplos de empresas grandes, y así se usa: como distinción conceptual, nunca como dato aplicable al tamaño del lector. |
| Q-07 | ¿Qué recomendaciones de ciberseguridad básica publican organismos oficiales para pequeñas empresas? | 16 | Media | **RESUELTA con límites el 2026-09-09 (Etapa 3.15A), con una sola fuente: F-046**, NISTIR 7621 Rev. 1, *Small Business Information Security: The Fundamentals*, **leída entera en su PDF oficial**. Se ejecutó tras una **prueba de necesidad**: el entregable del capítulo 16 se llama «lista de comprobación de seguridad básica» y **ninguna de las 45 fuentes anteriores decía nada sobre seguridad**. **Lo que aporta, y basta:** el principio de **mínimo acceso**, las **cuentas individuales** y su consecuencia —sin ellas no se puede investigar qué pasó—, el valor de los **registros** para reconstruir, y las **copias guardadas fuera** como condición para poder restaurar. **Lo que no aporta y no se le pide:** es de **2016**, es una **guía de referencia estadounidense y no una norma**, y su lista concreta de tecnología no se usa. **Sus cadencias —«al menos una vez al mes»— no se adoptan**, y su afirmación sobre el origen de los incidentes **no se cita**. |
| Q-08 | ¿Qué principios de control interno y separación de funciones son aplicables a organizaciones pequeñas? | 10 | Media, **materialmente necesaria antes del capítulo 10** | **RESUELTA con límites el 2026-09-08 (Etapa 3.9A)**: F-034, F-035, F-036 y F-037. Tres de las cuatro leídas directamente en el original. **El hallazgo que decide el capítulo 10:** la separación de funciones **no es una regla universal**, y las tres fuentes leídas coinciden en que cuando no hay personal suficiente se diseñan **controles alternativos**. **Límite que permanece:** ninguna fuente cubre negocios privados pequeños como estándar de gestión —una es federal, otra es de auditoría fiscal y otra de empresas cotizadas—, y **ninguna dice que un control alternativo equivalga a la separación ni que sea más débil**. Resultado completo al final de este documento. |
| Q-09 | ¿Qué se ha publicado sobre planificación del retiro de personas propietarias y su dimensión no financiera? | 5, 22 | **Alta** | **RESUELTA PARCIALMENTE.** Etapa 3.4A: seis fuentes, F-018 a F-023. **Ampliación dirigida a la ruta B en la Etapa 3.4A.1:** tres fuentes más, F-024 a F-026, una de ellas **leída íntegra**. Resultados completos al final de este documento. **Sigue abierta para el capítulo 22** y por el vacío de evidencia hispanohablante (V-56B), que no se ha podido cerrar. |
| Q-10 | ¿Qué evidencia hay sobre efectos de la ausencia imprevista de una persona clave en organizaciones pequeñas? | 4 | Media | Sin iniciar |
| Q-11 | ¿Qué estructuras de gobierno se recomiendan para separar propiedad y dirección en empresas familiares? | 17 | Media | **NO EJECUTADA, y diferida por prueba de necesidad el 2026-09-10 (Etapa 3.16A).** La pregunta previa se contesta que no: **el capítulo 17 no necesita afirmar que exista una estructura de gobierno que una empresa familiar deba adoptar**. La distinción que el capítulo usa —**propiedad, dirección y ejecución**— se construye entera sobre **D-072**, que ya define autoridad, ejecución y control para todo el libro, más la remisión jurisdiccional de **D-014** y **D-033**. **Nombrar consejo, junta, protocolo familiar, comité o holding sería prescribir arquitectura** —lo mismo que el capítulo 16 se negó a hacer con la seguridad— y trasplantaría estructuras de empresas con tamaño a un libro que sirve también a un negocio de una sola persona. **La afirmación que la haría necesaria, escrita para poder comprobarlo:** cualquier frase de la forma «para separar propiedad y dirección conviene constituir X». **El capítulo 17 no la escribe.** **Propuesta, no decisión: su plazo real es el capítulo 21**, cuyo índice sí nombra dirección profesional, socios y venta. |
| Q-12 | ¿Qué límites y obligaciones plantea la prestación de servicios tecnológicos a terceros? | Modelo de negocio | Baja para el libro, alta para el negocio | Sin iniciar |

### Preguntas añadidas en la Etapa 2.2 (2026-09-07)

Derivadas de la ampliación del público (D-021) y del concepto de clonación del conocimiento
(D-023). **Ninguna se ha investigado todavía.** Mientras no se resuelvan, el libro trata
estos asuntos por razonamiento y mecanismo, nunca con cifras ni con afirmaciones de
frecuencia (regla V-41).

| ID | Pregunta | Cap. | Prioridad | Estado |
|---|---|---|---|---|
| Q-13 | ¿Qué dice la literatura sobre transferencia de conocimiento tácito en el trabajo experto e individual, y no solo en organizaciones? | 2, 9 | **Alta** | **RESUELTA en su parte conceptual el 2026-09-07 (Etapa 3.8A)** con F-029 (Eraut). **Vacío que permanece:** ninguna literatura localizada sobre el trabajo por cuenta propia o de una sola persona. Resultado completo al final de este documento. Antes: **Corrección del 2026-09-07:** el informe de la Etapa 3.3 la dio por pertinente para el capítulo 5, y no lo es; sus capítulos son el 2 y el 9. El 2 ya está escrito y se cerró con Q-06, de modo que **su plazo real es antes del capítulo 9**. |
| Q-14 | ¿Qué se ha publicado sobre continuidad, traspaso o venta de negocios unipersonales y de carteras de clientes profesionales? | 21, 25 | **Alta** | Sin iniciar. Es el vacío declarado al lector en la introducción. |
| Q-15 | ¿Reconocen los marcos de continuidad y de riesgo la dependencia de una persona concreta como riesgo de primer orden, y con qué nombre? | 4, 16 | Alta | **NO EJECUTADA, y diferida por prueba de necesidad el 2026-09-09 (Etapa 3.15A).** La pregunta previa se contesta que no: **el capítulo 16 no necesita afirmar externamente que la dependencia de una persona sea un riesgo reconocido**. El libro lo construyó **por mecanismo** a lo largo de las Partes I, II y III, y el capítulo 16 trata de otra cosa —acceso, registro, protección y recuperación—. **Investigarla ahora sería decorar un capítulo que no la pide.** Sigue disponible para el capítulo 4 si alguna vez se revisa. Hallazgo previo de Q-03: aparece de forma secundaria. |
| Q-16 | ¿Qué marcos existen sobre gestión del conocimiento y codificación de conocimiento, y qué evidencia los respalda? | 6, 9 | Media | **RESUELTA con límites el 2026-09-07 (Etapa 3.8A.1)**: F-027, F-028, F-030, F-031, F-032 y F-033. **Corrige el estado de la Etapa 3.8A**, que la dejó parcialmente resuelta por no haber podido leer F-028: el resumen íntegro de F-028 sí se obtuvo después, y con él las tres categorías de técnicas que faltaban. **Límite que permanece:** ningún texto completo, de modo que el libro puede nombrar las tres categorías pero no sus subtipos ni la comparación empírica entre técnicas. Resultado completo al final de este documento. Antes: **no ejecutada para el capítulo 6, por decisión razonada (2026-09-07).** Se comprobó antes de escribir si el capítulo necesitaba alguna afirmación factual externa, y no la necesita: todo lo que sostiene es una definición propia de «crítico», un procedimiento de búsqueda, instrucciones y una microescena. **Investigar marcos de gestión del conocimiento solo para citarlos habría sido decoración.** Su plazo real era **antes del capítulo 9**, y se cumplió. |
| Q-17 | ¿Qué se sabe sobre colaboración entre personas y sistemas automáticos: supervisión efectiva, sesgo de automatización, delegación a sistemas? | **12, 13, 14, 15** | **Alta** | **RESUELTA con límites el 2026-09-09 (Etapa 3.11A)**: releídas F-007, F-009 y F-010, **ampliada F-007 con su apéndice C**, y dos fuentes nuevas —F-043 y F-044— solo para lo que ninguna norma contesta: cómo se comportan las personas. **El hallazgo que decide el capítulo 12 es negativo:** la combinación de persona y sistema **puede dar peor resultado que cualquiera de los dos por separado**, según el apéndice C de F-007. Resultado completo al final de este documento. **Alcance ampliado al capítulo 13 el 2026-09-09 (Etapa 3.12A), y el estado resuelto no se reabre.** El campo de capítulos decía «12, 14, 15» y **omitía el 13 por descuido, no por criterio**: el periodo de sombra es colaboración persona-sistema en el sentido más literal de la pregunta —una persona decide, un sistema observa, y después se comparan— y la supervisión, que es la mitad del enunciado de Q-17, **es exactamente lo que el capítulo 13 pone en práctica**. **No se crea otra pregunta para corregir una omisión de alcance**, y no se vuelve a investigar: las fuentes que el capítulo 13 usa —F-007 ampliada y F-045— entran por esta misma pregunta. |
| Q-18 | ¿Qué obligaciones generales de confidencialidad y de protección de datos de terceros afectan a un profesional que usa herramientas de IA, y cómo varían por jurisdicción? | 11, 16 | **Alta** | **RESUELTAS CONJUNTAMENTE con límites el 2026-09-09 (Etapa 3.10A)**: F-038 a F-042, las cinco leídas directamente en el documento oficial. **El hallazgo que decide el capítulo 11 es negativo y era previsible: no existe una regla única aplicable a todos los lectores.** Lo que sí existe es un conjunto de **preguntas de control que siguen sirviendo aunque cambie la jurisdicción**. Resultado completo al final de este documento. **Se ejecutó fusionada con Q-05, como el propio plan preveía**, y aporta lo que Q-05 sola no da: la distinción entre **dato personal**, **información confidencial de terceros** y **credenciales**, que son tres problemas distintos. |
| Q-19 | ¿Quién es titular del conocimiento codificado y de lo producido con herramientas de terceros, y qué ocurre si el negocio se vende o el proveedor cierra? | ~~9~~, 16 | Media | **Diferida el 2026-09-07 (Etapa 3.8A) y desligada del capítulo 9.** Se evaluó si el Manual de criterio la necesitaba y no la necesita: el capítulo 9 funciona entero en papel y no discute titularidad ni proveedores. **NO EJECUTADA para el capítulo 16, y diferida otra vez por prueba de necesidad el 2026-09-09 (Etapa 3.15A).** El capítulo pregunta **dónde están los datos** y **qué pasa si algo falla**, y podría parecer que necesita Q-19. **No la necesita**, y la distinción importa: lo que el capítulo tiene que decirle al lector es **«compruebe si puede sacar de ahí lo que necesita para seguir funcionando»**, que es **una pregunta de control y una regla de prudencia del método**, no una afirmación jurídica sobre titularidad. **El capítulo no dirá de quién es lo que el proveedor guarda**, porque para eso sí haría falta Q-19 y probablemente no exista respuesta universal. **Lo que sí dirá, y no necesita fuente:** que la pregunta se hace antes de depender, no después. Permanece abierta para el momento en que la titularidad sea materialmente necesaria —una venta, una transferencia—, previsiblemente en la Parte V. | Origen: `13-adn-empresarial.md` §6.3. |
| Q-20 | ¿Qué reservan las normas profesionales al juicio de la persona con licencia, en las profesiones del público previsto? | 15, 16 | Media | **NO EJECUTADA, y diferida por segunda vez el 2026-09-09 (Etapa 3.15A); la primera fue en el preflight del capítulo 15.** El capítulo 16 puede limitarse a lo que **D-033** ya autoriza: **un permiso tecnológico no sustituye la responsabilidad ni las obligaciones de una persona habilitada**, y donde haya norma profesional se remite a ella y a un profesional de esa jurisdicción. **Investigar una multitud de profesiones y países para escribir esa frase sería desproporcionado**, y el resultado previsible es el mismo que ya se anotó: **se resuelve remitiendo, no citando.** |
| Q-21 | ¿Existe evidencia de que documentar el conocimiento y los procesos aumente el valor o el precio de venta de un negocio pequeño? | 21, 25 | Media | Sin iniciar. **Mientras no se resuelva rige D-032:** el libro habla de transferibilidad y continuidad, no de valor. |

## 4. Categorías de fuentes candidatas

**Ninguna de estas fuentes ha sido consultada.** Se enumeran como categorías y como
puntos de partida de la búsqueda, no como respaldo de ninguna afirmación. Al consultarlas
habrá que comprobar existencia, versión vigente, fecha y aplicabilidad geográfica antes
de citar nada.

| Categoría | Qué se busca en ella | Preguntas |
|---|---|---|
| Institutos nacionales de estadística y registros mercantiles | Estructura empresarial por tamaño y por tipo de propiedad, con definiciones explícitas. | Q-01 |
| Organismos internacionales de desarrollo económico y financiero | Estudios comparados sobre pequeñas y medianas empresas. | Q-01, Q-02 |
| Ministerios y agencias públicas de apoyo a la pyme | Guías de continuidad, digitalización y relevo generacional. | Q-02, Q-03, Q-07 |
| Centros universitarios de empresa familiar | Investigación revisada por pares sobre sucesión y continuidad. | Q-02, Q-06, Q-09, Q-11 |
| Revistas académicas de gestión y de empresa familiar | Literatura sobre conocimiento tácito y sobre gobierno familiar. | Q-06, Q-11 |
| Organismos de normalización internacional | Normas sobre continuidad del negocio, seguridad de la información y gestión de riesgos. | Q-03, Q-04, Q-07 |
| Organismos técnicos nacionales de ciberseguridad | Guías de seguridad básica dirigidas a pequeñas organizaciones. | Q-05, Q-07 |
| Marcos públicos de gestión de riesgos de inteligencia artificial | Principios de supervisión humana, trazabilidad y explicabilidad. | Q-04 |
| Autoridades de protección de datos | Obligaciones al usar servicios de terceros y al tratar datos de personas. | Q-05 |
| Organizaciones profesionales de auditoría y control interno | Principios de control interno aplicables a organizaciones pequeñas. | Q-08 |
| Colegios profesionales de contabilidad y asesoría | Prácticas de control y conservación documental. | Q-08 |

**Advertencia sobre las fuentes de consultoría.** Muchas cifras que circulan sobre
empresas familiares proceden de informes comerciales con metodología no publicada y se
repiten durante años sin que nadie compruebe su origen. Ante una cifra llamativa y muy
citada, la instrucción es rastrear el estudio primario. Si no aparece, la cifra no se usa.
Esta advertencia se aplica especialmente a Q-02, donde abundan afirmaciones repetidas sin
respaldo localizable.

## 5. Riesgos de la investigación

| Riesgo | Mitigación |
|---|---|
| Citar una cifra muy repetida cuyo estudio primario no existe o no se localiza. | Regla del apartado 4: sin estudio primario, no se usa. |
| Extrapolar datos de un país a un lector de otro. | Indicar siempre el ámbito geográfico de cada dato en el propio texto. |
| Usar definiciones incompatibles de "empresa familiar" entre fuentes. | Explicitar la definición de cada fuente al citarla. |
| Que una norma o marco citado cambie de versión antes de publicar. | Registrar versión y fecha; recomprobar en la Etapa 4. |
| Que el libro adquiera tono académico por acumulación de citas. | Máximo orientativo: tres referencias externas por capítulo. |
| Que una afirmación legal se lea como universal. | Advertencia de jurisdicción obligatoria junto a cada una. |

## 6. Cuándo se ejecuta

La investigación **no se ejecuta en la Etapa 1**. Se ejecuta por bloques, inmediatamente
antes de escribir cada bloque de capítulos, para que las fuentes estén frescas y para no
verificar material que quizá no se use.

Excepción, ya ejecutada: Q-01, Q-02, Q-03 y Q-04 se resolvieron antes de escribir la
Etapa 2. La previsión de que pudieran no aparecer fuentes sólidas se cumplió en parte, y
se aplicó la regla prevista: **Q-02 se cerró sin cifra**. El argumento del libro no
dependía de ella y no la echa de menos.

### Calendario, corregido el 2026-09-07 (Etapa 3.3.1)

**Principio rector: se investiga inmediatamente antes de que la fuente sea necesaria.** Ni
antes, porque una fuente leída cinco capítulos antes se olvida y tienta a usarla donde no
toca; ni después, porque entonces el capítulo ya se escribió sin ella.

La secuencia anterior —«Q-06 y Q-13 juntas, más Q-05 y Q-18, antes del bloque B1»— venía de
la Etapa 2.2, cuando la producción se planificaba por bloques. Desde la Etapa 3 se escribe
capítulo a capítulo, y esa secuencia había quedado desalineada: arrastraba preguntas cuyos
capítulos están lejos y no señalaba la que hace falta ahora.

| Cuándo | Pregunta | Por qué entonces |
|---|---|---|
| **Antes del capítulo 5** | **Q-09** | Es la única temáticamente pertinente: retiro de personas propietarias y su dimensión no financiera. Sube a prioridad alta. |
| ~~Antes del capítulo 9~~ **Ejecutada** | **Q-06** (parte abierta), **Q-13** y **Q-16** | El 9 es el capítulo del Manual de criterio, donde hacía falta literatura sobre métodos de externalización, y donde Q-13 aporta la escala individual. **Q-16 no figuraba en esta tabla y tenía el mismo plazo; se añade aquí para que la tabla no vuelva a omitirla.** Las tres se ejecutaron en la Etapa 3.8A y se cerraron en la 3.8A.1. |
| Antes de los capítulos 11 y 16 | **Q-05** y **Q-18** | Privacidad y terceros no son materialmente relevantes hasta ahí. **No se adelantan por arrastre administrativo.** |
| Antes del capítulo 22 | **Q-09** (segunda parte, si hiciera falta) | Segundo capítulo asignado a esa pregunta. |

**Q-06, Q-13 y Q-16 quedaron cerradas el 2026-09-07**, las tres antes de escribir el capítulo 9,
que es lo que exigía el principio de calendario enunciado arriba. **Q-19 se difirió al capítulo
16** tras comprobar que el capítulo 9 no la necesita. Ninguna pregunta se ha eliminado ni ha
bajado de prioridad.

**Investigación de producto, separada.** Desde la Etapa 2.5 existe un backlog de
investigación de producto y de categorías competidoras en
`producto/01-vision-y-principios.md`, apartado 11. **No alimenta el manuscrito**: cualquier
dato que quisiera entrar en el libro tiene que pasar antes por las reglas de este documento,
sin excepción. Mientras esa investigación no se haga, **está prohibido afirmar que el
producto es único, primero o sin competencia**, dentro y fuera del libro.

**Advertencia sobre el público nuevo.** No existe todavía ninguna fuente verificada sobre
profesionales independientes en este repositorio. Hasta que la haya, está prohibido escribir
«la mayoría de los freelancers», «casi todos los consultores» o cualquier equivalente. La
regla V-41 se aplica con el mismo rigor a los dos públicos.


---

## Q-09 — Resultado de la investigación (Etapa 3.4A, 2026-09-07)

**Estado: RESUELTA PARCIALMENTE.** Hay respaldo suficiente para escribir el capítulo 5 con
prudencia, y hay dos vacíos declarados que el capítulo tendrá que reconocer en voz alta.

**Seis fuentes localizadas y registradas: F-018 a F-023.** Dos se leyeron en la página del
editor con muestra, método y limitaciones (F-020, F-023). Una más se leyó en la página del
editor con resumen estructurado, pero **la página no declara la muestra** (F-021). Tres solo
llegaron a nivel de resumen porque el editor bloquea la consulta automatizada (F-018, F-019,
F-022). **No se ha leído íntegro ningún artículo**, y por tanto ninguna afirmación del libro
puede ir más allá de lo que dice la fila correspondiente.

### 1. Las ocho preguntas que había que contestar

| # | Pregunta | Respuesta con evidencia |
|---|---|---|
| 1 | ¿El retiro empresarial es un proceso y no un suceso binario? | **Sí, respaldado.** F-019 dice que la terminología corriente no describe bien el caso del emprendedor e identifica cuatro tipos. F-018 encuentra inclinación al retiro parcial y a edad más tardía. F-023 mide una incertidumbre alta sobre el momento entre quienes trabajan por cuenta propia. |
| 2 | ¿Hay evidencia de retiro parcial o de continuidad de participación? | **Sí, para el retiro parcial** (F-018). Ojo: es una inclinación declarada, no una descripción de arreglos concretos de participación. |
| 3 | ¿Qué papel tiene la identidad? | **Respaldado.** F-018: la identidad emprendedora influye en cómo se afronta el retiro. F-022: la diversificación de la identidad y el apoyo social facilitan la transición. F-021: la necesidad apremiante genera ansiedad; la convicción propia motiva a planificar. |
| 4 | ¿Qué dimensiones no financieras aparecen? | Ver el apartado 3. **Solo las que sostiene alguna fuente.** |
| 5 | ¿Hay evidencia sobre conservar un papel tras reducir la operación? | **Muy débil.** F-018 habla de retiro parcial y de preferencias de salida; F-021, de buscar actividades satisfactorias después. **Ninguna fuente estudia el arreglo «deja la operación y conserva la propiedad» como un diseño.** Aquí el libro propone, no informa. |
| 6 | ¿Qué se puede decir de la ruta A? | Bastante: F-018, F-019, F-021 y F-022 tratan de propietarios y fundadores con negocio. |
| 7 | ¿Qué se puede decir de la ruta B? | **Poco, y solo desde F-023**, que es la única que separa expresamente a quien trabaja por cuenta propia **sin empleados**. Y mide preferencias declaradas, no experiencias. Las demás suponen un negocio con algo que traspasar. |
| 8 | ¿Qué no podemos afirmar? | Ver el apartado 5. |

### 2. El hallazgo más importante, y es incómodo

**La literatura no describe un continuo lineal. Describe tipos.** F-019 encuentra *cuatro
tipos de aproximación al retiro*, no cuatro etapas de un recorrido, y cada tipo depende de la
experiencia previa y de circunstancias ajenas al negocio. Nuestro continuo del retiro está
ordenado de más a menos operativo, y eso sugiere un camino que se recorre en un sentido.

**No es una contradicción, pero sí un matiz que el capítulo 5 debe recoger:** el continuo es
un mapa de posiciones posibles, no una escalera que todo el mundo suba en el mismo orden.
Una persona puede entrar por la mitad, quedarse, o retroceder. **Resuelto el 2026-09-07 en la Etapa 3.4A.1:** el autor cerró V-55 y el concepto pasa a ser
el **Mapa de Participación** (D-067), con sucesión y legado fuera del eje (D-068).

### 3. Dimensiones no financieras, cada una con su fuente

| Dimensión | Fuente | Qué sostiene exactamente |
|---|---|---|
| Identidad emprendedora | F-018, F-022 | Influye en cómo se afronta el retiro; diversificarla facilita la transición. |
| Control sobre la decisión | F-018 | El retiro se vive como decisión voluntaria con control considerable. |
| Capacidad de trabajo | F-020 | Cuando decae, fuerza el retiro de quien no estaba satisfecho. |
| Satisfacción vital | F-020 | Quien la tiene alta se retira en sus propios términos. |
| Salud | F-022 | Aparece entre los obstáculos prácticos. |
| Prioridades cambiantes | F-022 | Ídem. |
| Apoyo social | F-022 | Facilita la transición. |
| Familia y circunstancias ajenas al negocio | F-019, F-022 | Condicionan el tipo de aproximación. |
| Ansiedad ante el retiro no elegido | F-021 | La necesidad apremiante produce resistencia al cambio. |
| Actividades satisfactorias posteriores | F-021 | Asociadas a la convicción propia, no a la necesidad. |
| Autonomía y flexibilidad del trabajo | F-023 | Median parte de la preferencia por retirarse más tarde. |

**No respaldadas por estas fuentes, y por tanto no atribuibles a la literatura:** propósito,
legado, preparación psicológica como constructo medido, y relaciones sociales como categoría
distinta del apoyo social. Si el libro las usa, son del libro.

### 4. Propietario y empleado no son lo mismo

**Respaldado por F-023**, que compara los dos grupos en la misma encuesta: quien trabaja por
cuenta propia prefiere retirarse más tarde —2,15 años de media—, tiene más incertidumbre
sobre el momento (33 % frente a 27 %), mucha más flexibilidad (79 % puede trabajar desde
casa, frente al 39 %) y mucha menos seguridad percibida (27 % declara ninguna, frente al
8 %). **Es material de contexto, no una cifra para el manuscrito**: es neerlandés, de 2016 y
sobre preferencias.

### 5. Lo que NO podemos afirmar

1. **Nada sobre países hispanohablantes.** Las muestras localizadas son de Irlanda (F-019),
   Finlandia (F-020) y Países Bajos (F-023); en F-018, F-021 y F-022 el país de la muestra
   **no consta**. Cero evidencia de América Latina o España.
2. **Que el retiro parcial sea mejor.** Ninguna fuente lo evalúa como resultado deseable.
3. **Que trabajar sobre la identidad cause una mejor transición.** F-022 observa asociación,
   no causa.
4. **Que el continuo del libro esté validado.** No lo está, y no puede presentarse como escala.
5. **Cifras.** Ninguna de las cifras de F-023 entra en el manuscrito; se registran aquí para
   fijar el contexto y su ámbito.
6. **Nada sobre el negocio de una sola persona más allá de F-023.** No hay literatura
   localizada sobre cómo vive el retiro quien trabaja solo con un oficio.

### 6. Evaluación del continuo del retiro, escalón por escalón

**A** directamente respaldado · **B** compatible, no estudiado · **C** propuesta del método ·
**D** potencialmente contradictorio.

| Escalón | Clase | Motivo |
|---|---|---|
| 100 % operativo | **C** | Punto de partida descriptivo del libro. |
| Reducción del trabajo manual | **C** | Propuesta del método. |
| Supervisión | **C** | Propuesta del método. |
| Intervención por excepción | **C** | Propuesta del método. |
| Asesoría estratégica | **B** | Compatible con las actividades posteriores de F-021 y con las preferencias de salida de F-018; no estudiado como escalón. |
| Participación voluntaria | **B** | Compatible con el «control considerable» y la voluntariedad de F-018. |
| **Retiro parcial** | **A** | Directamente respaldado por F-018. |
| Retiro total | **A** | Es el resultado que estudian F-018, F-019, F-020 y F-023. |
| Sucesión o legado | **B** | F-021 trata la sucesión familiar; el escalón como final del recorrido es propio. |

**Ningún escalón queda en D.** La única tensión es la del apartado 2: la forma **lineal** del
continuo, no sus escalones.

### 7. La frase central

> «Su participación debe dejar de ser una obligación operativa y convertirse en una elección.»

**Clasificación: propuesta del autor respaldada por evidencia compatible.** No es la
conclusión de ninguna fuente y no debe presentarse como tal. Lo que la hace defendible es
F-018 —el retiro del empresario como decisión voluntaria con control considerable— y, por el
lado contrario, F-021: cuando el retiro llega por necesidad apremiante y no por convicción,
aparece ansiedad y resistencia. La distinción entre elegir y verse obligado está, pues,
presente en la literatura; la formulación es del libro.

### 8. Dimensiones para el futuro cuestionario

**No se redacta ninguna pregunta en esta etapa.** Solo se separa lo que tendría respaldo de
lo que sería diseño propio.

| Dimensión | Con respaldo | Diseño propio del libro |
|---|---|---|
| Deseo y voluntariedad del retiro | F-018 | |
| Horizonte y control del momento | F-018, F-023 | |
| Capacidad de trabajo | F-020 | |
| Satisfacción vital | F-020 | |
| Identidad y papel futuro | F-018, F-021, F-022 | |
| Apoyo familiar y social | F-019, F-022 | |
| **Preparación del negocio** | | **Sí.** Ninguna fuente la mide. **Es la aportación distintiva del libro**, y conviene decirlo: la literatura estudia la disposición de la persona; el libro añade la capacidad del negocio. |
| **Alternativas de participación** | | **Sí.** Es el continuo, que es propuesta del método. |

### 9. Cómo debe citarse todo esto en el capítulo 5

**Como máximo dos fuentes en el manuscrito**, y solo si añaden algo: **F-018** para la
voluntariedad y el retiro parcial, y **F-021** para la diferencia entre retirarse por
convicción y retirarse por necesidad. F-020 y F-023 quedan como contexto que sostiene el
argumento sin aparecer. F-019 y F-022 se reservan por si el capítulo necesita el matiz de los
tipos o el de la identidad.

**Prohibido en el capítulo 5:** cifras, porcentajes, lenguaje clínico o de diagnóstico
psicológico, y cualquier afirmación de alcance universal. La dimensión de identidad se trata
al nivel de la literatura de empresa y de retiro, nunca como terapia.


---

## Q-09 — Ampliación dirigida a la ruta B (Etapa 3.4A.1, 2026-09-07)

Tres fuentes nuevas: **F-024, F-025 y F-026**. La primera se leyó **íntegra**.

### 1. Intención y experiencia no son lo mismo

La Etapa 3.4A trabajó casi entera sobre **intenciones y preferencias declaradas**. Esta
ampliación aporta por fin **experiencia real de personas ya retiradas** (F-024) y
**secuencias observadas en registros administrativos** (F-025). La distinción manda:

| Fuente | Qué mide | Ruta |
|---|---|---|
| F-018, F-023 | Intenciones y preferencias declaradas | A / B |
| F-024 | **Experiencia vivida**, personas ya jubiladas | **B directa** |
| F-025 | **Secuencias observadas** en registros | **Comparación A/B** |
| F-019, F-021, F-022 | Relatos y casos | A |
| F-026 | Relatos, mayoría de antiguos empleados | Contexto |

### 2. Lo que aporta F-024, y es mucho

Es la fuente más alineada con el capítulo 5, y conviene decir por qué sin exagerarla.
Entrevista a **diez profesionales autónomos ya jubilados**, de 60 a 91 años, y **ninguno
dejó de trabajar al empezar a cobrar la prestación**. Su conclusión, en palabras de los
autores, es casi el título del capítulo:

> «o fato de estar aposentado não significa necessariamente um desligamento do trabalho, mas
> sim uma **transformação do papel de trabalhador**».

Y añade dos cosas que el libro necesitaba y no tenía:

- La transición se describe como **rearranjo de papeles sociales y contextos de vida**, no
  como abandono de uno solo.
- «O desengajamento do papel de trabalhador **não precisa ocorrer abruptamente**,
  possibilitando que o sujeito **controle a melhor forma e o melhor momento** de parar de
  trabalhar.»

**Límite declarado por los propios autores:** el estudio «não possuindo a intenção de
apresentar resultados generalizáveis a qualquer tipo de público ou de contexto», y es
transversal. Diez personas, Brasil. **No se puede convertir en una afirmación general.**

### 3. Lo que aporta F-025, y complica el cuadro

Aquí está el hallazgo incómodo de esta ampliación, y hay que registrarlo tal cual:

> «the solo self-employed form a **homogenous group**, retiring at age 65 with an old-age
> pension. They follow state pension regulations. In contrast, company owners form a
> **heterogeneous group, displaying agency**.»

Es decir: en los registros finlandeses, **quien trabaja solo mostró menos variedad de
trayectorias que el propietario con empresa**, y siguió la regulación estatal. Eso tira
contra la suposición cómoda de que el lector de la ruta B tiene el mismo margen de elección
que el de la ruta A.

**Y sin embargo no lo contradice, por dos motivos que hay que sostener a la vez.** Primero,
F-025 mide **lo que ocurrió**, no lo que se quería: la homogeneidad puede ser efecto del
sistema de pensiones, y el propio hallazgo lo dice al añadir que ese grupo «sigue la
regulación estatal». Segundo, en Brasil (F-024) pasa lo contrario: ninguno de los diez dejó
de trabajar al cobrar la prestación. Y en Países Bajos (F-023) quienes trabajan por cuenta
propia **prefieren** retirarse más tarde que los empleados.

**Conclusión honesta: no hay un patrón universal para quien trabaja solo. Lo que se observa
depende mucho del país y del sistema de pensiones.** Eso es un resultado, no un fracaso, y
el capítulo 5 debe escribirse sabiéndolo: **está prohibido afirmar que el lector de la ruta
B tenga, por naturaleza, más o menos libertad de elección.**

### 4. Comprobación hispanohablante

**Sigue sin haber evidencia académica hispanohablante sobre el retiro de personas
propietarias y su dimensión no financiera.** Lo único localizado en lengua española es
F-026, colombiana, sobre empleo puente: útil como contexto, pero **ocho de sus doce
participantes eran antiguos empleados**, así que no sostiene nada sobre propietarios.

La búsqueda en español devolvió, por lo demás, prensa económica, blogs de despachos y
publicaciones de consultoras, con cifras llamativas y sin origen trazable. **Ninguna se
registra**, por la misma regla que hizo al libro renunciar a su dato más vendedor en Q-02.
El descarte queda anotado en `fuentes-verificadas.md`, apartado 2.

### 5. Estado de las dos mitades de V-56

| | Pregunta | Estado |
|---|---|---|
| **V-56A** | ¿Hay evidencia suficiente para escribir con prudencia sobre la ruta B? | **REDUCIDA.** De una sola fuente sobre preferencias se pasa a tres, una de ellas leída íntegra y sobre experiencia vivida. Sigue abierta porque el cuadro es contradictorio entre países y ninguna muestra es grande. |
| **V-56B** | ¿Hay evidencia pertinente de países hispanohablantes? | **ABIERTA.** No se ha localizado ninguna. Brasil no cuenta como hispanohablante. El vacío se mantiene declarado, sin forzarlo. |

### 6. Qué puede y qué no puede decir el capítulo 5

**Puede decir, con fuente:**

- Que jubilarse no equivale necesariamente a dejar de trabajar, y que para muchos autónomos
  significa **transformar el papel** en lugar de abandonarlo (F-024).
- Que la desvinculación **no tiene por qué ser brusca**, y que la persona puede controlar la
  forma y el momento (F-024).
- Que el retiro del empresario se vive como **decisión voluntaria con control considerable**,
  con inclinación al retiro parcial (F-018).
- Que retirarse por **convicción propia** produce una experiencia distinta de retirarse por
  **necesidad apremiante** (F-021).
- Que la capacidad de trabajo y la satisfacción vital influyen en si uno se retira en sus
  propios términos o forzado (F-020).

**No puede decir:**

- Que exista un patrón universal, y menos aún para quien trabaja solo (F-024 frente a F-025
  frente a F-023).
- Nada apoyado en evidencia hispanohablante, porque no la hay (V-56B).
- Que el retiro parcial sea mejor que cualquier otra posición.
- Ninguna cifra. **Ninguna de las cifras de F-023 ni de F-025 entra en el manuscrito.**
- Nada en registro clínico o de diagnóstico. La identidad se trata al nivel de la literatura
  de empresa y de retiro (§16 del encargo).

### 7. Para el cuestionario de la Etapa 3.4B

**No se ha redactado ninguna pregunta.** Se confirma la arquitectura de dos ejes:

| Eje | Qué pregunta | Respaldo |
|---|---|---|
| **Personal** | ¿Estoy preparado yo? | Deseo y voluntariedad (F-018), horizonte y control (F-018, F-023, F-024), capacidad de trabajo (F-020), satisfacción (F-020), identidad y papel futuro (F-018, F-021, F-022, F-024), apoyo familiar y social (F-019, F-022, F-026) |
| **Del negocio** | ¿Está preparado el negocio? | **Ninguno. Es construcción propia del Método LEGADO** y así debe presentarse: no es una escala validada académicamente. |

**Posibilidad registrada para la Etapa 3.4B, sin construir todavía la herramienta:** una
matriz de dos por dos que cruce los dos ejes. **Regla esencial si se adopta: ningún cuadrante
es un juicio.** En particular, *persona no preparada + negocio preparado* **no es un
fracaso**; puede significar exactamente «puedo retirarme, pero no quiero», que es compatible
con la promesa central del libro y con la regla 7 del Mapa de Participación.


---

## Q-06 · Q-13 · Q-16 — Resultado conjunto (Etapa 3.8A, 2026-09-07)

Las tres preguntas se investigaron juntas porque desembocan en el mismo sitio: **cómo se hace
visible el razonamiento que una persona usa para decidir.** Siete fuentes registradas,
**F-027 a F-033**.

### 1. La limitación que condiciona todo lo demás

**Cero textos completos en esta tanda**, y eso no ha cambiado. Lo que sí cambió en la Etapa
3.8A.1 es **cuánto se llegó a leer de cada uno**. La primera tanda se detuvo en las páginas de
editor y en los repositorios que devuelven error; la recuperación dirigida usó otras vías
—depósitos Crossref del propio editor, portales institucionales de investigación y una copia
académica del original— y **subió tres fuentes de nivel y corrigió una autoría**.

| Nivel de lectura | Etapa 3.8A | **Etapa 3.8A.1 (vigente)** |
|---|---|---|
| **Original leído en parte** | — | **F-031** (facsímil escaneado del MIT: portada, palabras clave y el apartado del método; **no** la evaluación) |
| **Resumen íntegro verbatim depositado por el editor** | — | **F-029** (Wiley), **F-033** (Wiley) |
| **Resumen verbatim en portal institucional** | F-030 | F-030 (ASU), **F-028** (Bond University) |
| **Resumen de registro agregado** | F-027, F-029, F-031, F-032, F-033 | F-027, F-032 |
| **Solo identidad bibliográfica** | **F-028** | — |

**La corrección que más importa: F-028 ya no es inutilizable.** La Etapa 3.8A la registró como
identidad sin contenido y prohibió citarla; su resumen íntegro se obtuvo después en el portal
de investigación de Bond University. Junto a ella, **la autoría de F-032 estaba mal**: no es de
un solo autor.

Sigue en pie el límite de fondo, y con la misma fuerza: **ninguna afirmación del capítulo 9
puede ir más allá de lo que consta en la fila de cada fuente.** De F-028 se puede usar su
resumen y nada más; de F-031, el método y no la evaluación.

### 2. El hallazgo que más afecta al libro

**Las cuatro fuentes de método localizadas suponen un entrevistador, sin excepción.** El
método del incidente crítico (F-027) consiste en que alguien sondee a un experto; ACTA (F-031)
son tres entrevistas, comprobado en el original; la revisión de Cooke (F-030) recorre técnicas
de elicitación, que por definición implican a quien elicita. **Añadido en la Etapa 3.8A.1:**
las tres familias de F-028 —analizar las tareas del experto, entrevistarlo, ponerle tareas
construidas— **también las administra alguien**, incluida la tercera, que evita preguntar pero
no evita al examinador.

Es una afirmación acotada y comprobable: **no dice que no exista literatura de autoelicitación,
dice que no se ha encontrado ninguna.**

Eso choca de frente con la ruta B, y no se puede disimular: **la literatura localizada no
ofrece respaldo para la autoentrevista.** Un profesional que trabaja solo no tiene
entrevistador, y el capítulo 9 va a proponerle que se lo haga a sí mismo. **Eso es diseño
propio del Método LEGADO, no un método respaldado**, y debe decirse así.

### 3. Q-06, continuación — métodos de externalización

**RESUELTA para lo que el capítulo 9 necesita, con límites.** Existe un campo entero de
técnicas de elicitación, disperso —F-030 lo dice literalmente: repartido entre psicología,
gestión, educación, orientación, ciencia cognitiva, lingüística, filosofía, ingeniería del
conocimiento y antropología— y organizable por semejanza metodológica, con fortalezas y
debilidades por categoría.

**Actualización de la Etapa 3.8A.1: las categorías sí se obtuvieron, pero de otra fuente.** El
resumen de F-030 sigue sin nombrarlas. Las que el libro puede nombrar son las de **F-028**, y
son **tres**: análisis de las tareas que el experto realiza habitualmente; entrevistas de
varios tipos; y **tareas construidas que revelan el razonamiento del experto sin preguntarle
por ese razonamiento**.

Esa tercera categoría es la que más dice: existe un modo entero de elicitación que **no
pregunta por el razonamiento**.

**Corrección de la Etapa 3.8B, y es importante.** La redacción anterior de este apartado decía
que eso daba «fuente en lugar de razonamiento propio» a la clase D. **Atribuía a F-028 más de lo
que dice.** Lo que la fuente sostiene es que **existe** una familia de técnicas construida así.
**No sostiene** que preguntar «¿por qué decidió eso?» sea incorrecto, que produzca
racionalizaciones, que deba prohibirse ni que no aporte nada útil. La doctrina que el libro puede
defender es más estrecha y es suya: **no dependa exclusivamente de una pregunta abstracta sobre el
porqué.** Preguntar «¿por qué?» en una conversación es legítimo; hacer que todo el Manual descanse
en esa única respuesta, no.

**Dos cautelas obligatorias.** Primera: los autores las presentan «for discussion purposes», así
que **el libro debe decir que es una agrupación expositiva, no una clasificación cerrada**.
Segunda: **los subtipos no se han leído**, de modo que se pueden nombrar las tres familias y
nada por debajo de ellas.

Lo que se sostiene además es más modesto y más útil: **ninguna de las fuentes leídas ofrece un
método universal**, y dos de ellas explican por qué —F-030 describe el campo como «widely
scattered» entre nueve disciplinas, y F-028 dice que, dada esa diversidad, «it is difficult to
make the literature cohere around a methodological theme»—. **No se afirma que ese método no
exista; se afirma que la literatura localizada no lo ofrece.** Y
**existe precedente de simplificar métodos expertos para quien no lo es** (F-031, que se
define a sí mismo como *streamlined* y motivado por la poca accesibilidad de la técnica
completa). Eso legitima lo que hace el libro sin exagerarlo.

### 4. Q-13 — el trabajo experto individual

**RESUELTA en su parte conceptual, gracias a F-029**, que es la fuente más útil de la tanda
para el capítulo 9. Eraut distingue **tres tipos de conocimiento tácito**:

1. la comprensión de personas y situaciones;
2. las acciones rutinizadas;
3. **las reglas que subyacen a la decisión intuitiva**.

Y cuatro procesos —**leer la situación, decidir, actuar y metacognición**— con tres modos
cognitivos, **intuitivo, analítico y deliberativo**, cuyo equilibrio **depende del tiempo
disponible, la experiencia y la complejidad**.

Tres consecuencias para el libro:

- **«Leer la situación» es un proceso propio**, distinto de decidir. Eso respalda que el
  Manual de criterio recoja **señales** y no solo reglas.
- **El modo depende del tiempo.** La misma persona resuelve distinto con prisa que con calma,
  así que registrar «cómo decido» sin decir en qué condiciones deja fuera la mitad.
- Y una que incomoda: el aprendizaje situado produce a menudo **variación individual, no
  conformidad**. Dos personas del mismo negocio pueden no converger en el mismo criterio solo
  por trabajar allí. **Documentar no es, por sí solo, uniformar.**

**Añadido en la Etapa 3.8A.1, del resumen verbatim del editor.** Eraut señala que el
conocimiento tácito es problemático «with respect to both **detecting it and representing it**».
Son dos problemas distintos, y el capítulo 9 debe tratarlos como tales: **encontrar el criterio
y escribirlo no son el mismo paso**, y una herramienta puede resolver el primero y fallar en el
segundo. Segundo añadido: donde domina la acción rápida, «**periods of deliberation are needed
to maintain critical control**». Eso respalda con fuente algo que el Manual de criterio necesita
—que el criterio se revisa en frío, no en caliente—, y es exactamente la fase 2 que el capítulo
8 ya introdujo para las excepciones. Tercero: el autor advierte que la importancia del
aprendizaje deliberativo «**is commonly overemphasised**», lo que obliga al libro a **no
presentar el Manual de criterio como si capturara todo el aprendizaje** de una persona.

**Vacío que queda:** F-029 es trabajo profesional en general. **Sigue sin haber literatura
localizada sobre el trabajo por cuenta propia o de una sola persona.** No se fuerza.

### 5. Q-16 — marcos y evidencia

**RESUELTA con límites en la Etapa 3.8A.1.** Se localizaron **seis** piezas del mapa: un método
de elicitación por incidentes (F-027), la revisión metodológica que agrupa las técnicas en tres
familias (F-028), una revisión de técnicas que documenta lo disperso del campo (F-030), un
método simplificado para practicantes (F-031), una revisión crítica de la propia idea de
codificar (F-032) y una revisión sistemática de pymes que advierte contra tratar el
conocimiento como activo separable (F-033).

**Qué cambió respecto de la Etapa 3.8A.** Aquella la dejó parcialmente resuelta por dos
motivos, y uno de los dos ha caído: **F-028 sí pudo leerse en resumen**, y con ella llegaron
las categorías que faltaban. El segundo motivo sigue en pie: **de F-030 no se obtuvieron sus
categorías**, y no se obtendrán sin abrir el texto.

**Los límites, enunciados sin rodeos.** Tres familias sí; subtipos no. Existencia de evaluación
empírica comparada sí —F-028 dice que la hay—; **qué concluye esa evaluación, no**. Y ninguna
de las seis fuentes ha sido leída íntegra.

### 6. Los métodos, uno por uno

| Método | Qué respaldo tiene |
|---|---|
| **Incidente concreto** —«cuénteme una ocasión»— | **A.** Es el núcleo de F-027, que extiende la técnica del incidente crítico. |
| **Señales / cues** | **A.** F-027 elicita expresamente *decision cues* y *discriminaciones perceptivas*. F-029 hace de «leer la situación» un proceso propio. |
| **Juicio de tipicidad** —caso típico frente a raro— | **A.** F-027 lo nombra entre las dimensiones que extrae. |
| **Sondeos dirigidos sobre el episodio** | **A.** F-027, con la salvedad de que sus sondeos concretos no se han leído. **Reforzado en la Etapa 3.8A.1:** F-031 muestra en el original un juego de sondeos escrito y publicado —la *knowledge audit*, con sondeos básicos y opcionales—, de modo que **la idea de trabajar con preguntas fijadas de antemano está documentada**, aunque las preguntas concretas de este libro sean suyas. |
| **Reconstrucción temporal del episodio** | **B.** Compatible con un método de incidentes; no confirmado en lo leído. |
| **Alternativas consideradas** | **B.** Compatible; no confirmado. |
| **Pregunta de contraste** —«qué habría cambiado su decisión»— | **C. Diseño propio.** Es plausible y coherente con la elicitación por incidentes, pero **no se ha verificado en ninguna fuente leída**, y el libro debe presentarla como suya. |
| **Escenario contrafactual** | **C.** Igual que la anterior. |
| **Pregunta abstracta directa** —«¿por qué decide así?»— | **D, con una precisión de la Etapa 3.8B.** F-028 describe una familia de técnicas que revelan el razonamiento «without necessarily asking about these processes». Eso acredita que **existen** métodos que no dependen de la pregunta directa. **No acredita** que la pregunta directa sea incorrecta, ni que cause racionalización, ni que deba evitarse: la fuente no dice nada de eso y el libro no lo dirá. **Lo único que se sostiene:** el campo construyó alternativas, y por tanto un método que descanse solo en esa pregunta se está apoyando en menos de lo que hay disponible. |
| **Descomponer la tarea antes de entrevistar** | **A, nuevo en la Etapa 3.8A.1.** F-031, leída en el original: la *task diagram interview* descompone la tarea en «less than six, but more than three steps» y solo después pregunta cuáles exigen destreza cognitiva difícil. **Respalda empezar por un mapa grueso y estrechar después**, que es lo que ya hacen los capítulos 6 y 7. |
| **Consolidar lo extraído en una sola tabla** | **A, nuevo en la Etapa 3.8A.1.** F-031 cierra sus tres entrevistas con una *cognitive demands table* «offered as a means to consolidate and synthesize the data». **Respalda que el Manual de criterio sea una tabla y no un relato.** |
| **Observación y pensar en voz alta** | **Sin evaluar.** No se localizó respaldo en lo leído; no entra. |
| **Autoentrevista** | **C, y es el punto débil.** Ver apartado 2. |

### 7. Recuerdo retrospectivo

**No se encontró respaldo, y por tanto el libro no dirá nada sobre sesgo retrospectivo.** El
encargo advertía de no introducir una afirmación sobre sesgo sin fuente, y no la hay entre
lo leído.

Lo que sí puede sostenerse sin fuente, porque es una regla de diseño y se declarará como tal:
**una explicación plausible dada después no es prueba de lo que guio la decisión.** Es la
misma cautela que el capítulo 8 ya aplica al prohibir inventar un motivo a posteriori.

### 8. Los límites de la codificación, y sí están respaldados

Esta era la pregunta doctrinal importante, y la respuesta es que **sí**.

- **F-032** es literalmente una guía escéptica sobre el uso de «conocimiento tácito» y
  «codificación» en economía, y propone reconceptualizarlos. Es decir: la frontera entre lo
  tácito y lo codificado **es objeto de discusión, no un hecho asentado**.
- **F-033**, revisión sistemática de pymes, concluye —ahora con el resumen verbatim del propio
  editor a la vista— que la investigación ha venido tratando ese conocimiento «**as an asset
  that is transferred by routines**», y que las cualidades relacionales e insertas que lo
  caracterizan en las pymes son «**qualities that resist conceptualization as some form of
  separable, material asset**». Es decir: la propia literatura señala como problema justo el
  supuesto sobre el que descansaría una promesa de clonación.
- **F-029** sitúa parte del conocimiento profesional en acciones rutinizadas y en modos
  intuitivos que dependen del tiempo y de la experiencia.

**Conclusión: el libro no puede prometer que todo lo que una persona sabe quepa en un
manual.** Y conviene decir que F-033 llega como contrapeso del propio concepto de **clonación
del ADN empresarial**: la advertencia de `13-adn-empresarial.md` §1 —que no todo se
documenta— **queda reforzada por evidencia externa**, no solo por prudencia del autor.

### 9. La arquitectura del Manual de criterio, clasificada

**A** respaldado · **B** compatible, no confirmado · **C** diseño propio · **D** problemático

| Componente | Clase | Nota |
|---|---|---|
| Trabajar sobre **casos concretos** | **A** | F-027 |
| **Señales** que importaron | **A** | F-027, F-029 |
| Caso **típico** frente a caso raro | **A** | F-027 |
| Qué **información** se tenía | **B** | |
| **Alternativas** que existían | **B** | |
| Qué se eligió y **por qué** | **B** | El «por qué» directo es justo lo que la elicitación considera insuficiente por sí solo |
| **Qué habría cambiado la decisión** | **C** | Declararlo como propuesta del libro |
| **Excepciones** | **C** | Viene del capítulo 8, no de la literatura |
| **Cuándo detenerse y preguntar** | **C** | Diseño propio |
| **Registrar la incertidumbre** y el «no sé explicarlo todavía» | **C** | Coherente con F-029, que admite conocimiento no verbalizable, pero el campo es del libro |
| **Nueve campos** | **D** | Demasiados. F-031 respalda **simplificar**, no ampliar. Resuelto abajo: **cinco**. |

**Sobre las condiciones:** F-029 obliga a añadir algo que no estaba en la arquitectura
provisional. Como el modo cognitivo depende del tiempo disponible, **conviene registrar en
qué condiciones se decidió** —con prisa o con calma, con información completa o incompleta—.
Sin eso, el criterio escrito describe un caso que quizá no se repita.

#### Recomendación cerrada: cinco campos

La arquitectura provisional tenía nueve campos y la evidencia empujaba en dirección contraria.
F-031 existe **porque** el método completo era demasiado costoso para quien no es especialista,
y su propia descripción se llama a sí misma *streamlined*. Un formulario que nadie rellena dos
veces no documenta nada. Esta es la versión recomendada para el capítulo 9:

| # | Campo | Clase | De dónde sale |
|---|---|---|---|
| 1 | **El caso**: qué pasó, cuándo, y qué se hizo | **A** | F-027 y F-028 sitúan el incidente concreto en el centro; F-031 empieza descomponiendo una tarea real |
| 2 | **Qué me hizo darme cuenta**: las señales | **A** | F-027 elicita *decision cues* y discriminaciones perceptivas; F-029 hace de «leer la situación» un proceso propio; F-031 audita destrezas perceptivas y reconocimiento de anomalías |
| 3 | **Si fue un caso típico o raro** | **A** | F-027 nombra el juicio de tipicidad entre las dimensiones que extrae |
| 4 | **En qué condiciones decidí**: con prisa o con calma, con cuánta experiencia previa en un caso así, y con qué información a mano | **A en sus tres primeras condiciones; C en la cuarta** | F-029 respalda **tiempo, experiencia y complejidad**. **Corrección de la Etapa 3.8B:** la disponibilidad de información **no aparece en el material leído** y la redacción anterior se la atribuía. Se conserva porque es una condición práctica útil, pero **es diseño propio del libro**, compatible con la fuente y no derivada de ella |
| 5 | **Qué habría cambiado mi decisión** | **C, diseño propio** | Coherente con la elicitación por incidentes, **no verificada en ninguna fuente leída**, y el capítulo debe declararla como propuesta del libro |

**El campo 4 es nuevo**: no estaba entre los nueve provisionales. Sus tres primeras condiciones
las obliga F-029; la cuarta, la información disponible, **la añade el libro por su cuenta** y así
queda clasificada. Los que no siguen no se pierden por descuido, y esta es la razón de cada uno:

- **«Qué información se tenía»** se absorbe en el campo 4. Era una condición, no un campo aparte.
- **«Alternativas que existían»** sale de la tabla y su material se recoge, cuando aparece, al
  trabajar el campo 5. **Corrección de la Etapa 3.8B: no son la misma pregunta y no debe decirse
  que lo sean.** «¿Qué otras opciones tenía?» busca **el abanico**; «¿qué habría cambiado su
  decisión?» busca **la condición que mueve la elección**. Se puede tener la segunda respuesta sin
  la primera y al revés. Que solo una de las dos ocupe un campo **es una decisión de diseño del
  Método LEGADO** tomada para no pasar de cinco campos, y así se declara. Preguntar por las
  alternativas durante la conversación sigue siendo útil y está permitido; lo que no es, es un
  campo obligatorio.
- **«Qué se eligió y por qué»**: el «qué se eligió» ya está en el campo 1. El «por qué» directo
  **deja de ser un campo de la tabla**, y esa es la decisión de fondo de este apartado. **Se declara
  como decisión de diseño del Método LEGADO, no como conclusión de la investigación.** Lo que aporta
  F-028 es solo que existen técnicas que llegan al razonamiento sin preguntar por él, de modo que
  hay de dónde elegir. Lo que aporta el capítulo 8 es la cautela ya establecida contra escribir un
  motivo reconstruido a posteriori. Con las dos cosas, el libro prefiere que el porqué **salga de
  relacionar los cinco campos** en lugar de pedirlo en una casilla. **El porqué no desaparece del
  método**: desaparece de la casilla. Preguntarlo en voz alta, durante el trabajo, sigue estando
  bien.
- **«Excepciones»** no entra: es la herramienta 6, del capítulo 8, y duplicarla aquí rompería el
  límite entre ambos capítulos.
- **«Cuándo detenerse y preguntar»** y **«registrar la incertidumbre»** no son campos de un caso:
  son **una regla del método y un permiso de escritura**. Van en el texto del capítulo, no en la
  tabla. El permiso —poder escribir «esto no sé explicarlo todavía» en cualquiera de los cinco
  campos— está además respaldado por F-029, que separa **detectar** el conocimiento tácito de
  **representarlo**: se puede haber detectado algo y no saber aún escribirlo.

**Forma del entregable: una tabla, no un cuestionario.** F-031 cierra sus tres entrevistas con
una *cognitive demands table* «offered as a means to consolidate and synthesize the data». El
Manual de criterio debe consolidar en una sola vista, con una fila por caso.

### 10. Comprobación del criterio escrito

**No se localizó literatura sobre cómo comprobar que un criterio documentado es utilizable.**
Lo que el capítulo 9 proponga en esta materia será **diseño propio**, y debe apoyarse en la
constante que ya rige desde la Etapa 3.5.1: **documentado no es transferido**, y solo cuenta
como transferido cuando alguien lo ha usado sin recurrir a su autor.

### 11. Lo que el capítulo 9 podrá y no podrá decir

**Podrá decir, con fuente:**

- Que existe un cuerpo de métodos para extraer conocimiento experto, disperso entre muchas
  disciplinas, y que ninguna fuente ofrece un método universal (F-030).
- Que hay métodos construidos sobre **incidentes concretos** en lugar de preguntas abstractas,
  y que extraen **señales de decisión, discriminaciones perceptivas y juicios de tipicidad**
  (F-027).
- Que el conocimiento tácito profesional incluye **comprender situaciones y personas**,
  **acciones rutinizadas** y **reglas que subyacen a decisiones intuitivas**, y que el modo de
  decidir **depende del tiempo, la experiencia y la complejidad** (F-029).
- Que existe precedente de **simplificar** estos métodos para quien no es especialista
  (F-031), y que ese método simplificado consta de **tres entrevistas y una tabla que consolida
  lo extraído** (F-031, leída en el original).
- Que las técnicas de elicitación se agrupan, **a efectos de exposición y según sus propios
  autores**, en tres familias: analizar las tareas habituales del experto, entrevistarlo de
  varios modos, y **tareas construidas que revelan su razonamiento sin preguntarle por él**
  (F-028).
- Que **detectar** el conocimiento tácito y **representarlo** son dos problemas distintos, y que
  donde domina la acción rápida hacen falta **periodos de deliberación para mantener el control
  crítico** (F-029).
- Que la idea de codificar conocimiento **está discutida**, y que en las pequeñas empresas el
  conocimiento **se resiste a tratarse como un activo separable** (F-032, F-033).

**No podrá decir:**

- **Ningún subtipo ni ninguna técnica concreta por debajo de las tres familias de F-028**, ni
  presentarlas como una clasificación cerrada: sus autores las declaran «for discussion purposes».
- **Qué concluye la comparación empírica entre técnicas.** F-028 dice que existe; no se ha leído.
- **Que ACTA funcione.** Se leyó en el original qué es y qué hace; **la evaluación de usabilidad
  y utilidad no se leyó** (F-031).
- Nada de F-030 más allá de que el campo está disperso y de que el artículo clasifica las
  técnicas: **sus categorías siguen sin obtenerse**, y no deben confundirse con las de F-028.
- Nada sobre sesgo o distorsión del recuerdo retrospectivo.
- Que la autoentrevista tenga respaldo metodológico. **No lo tiene.**
- Que estos métodos estén validados para negocios pequeños. **Los dominios son bomberos,
  urgencias, militares e ingeniería.**
- Que el Manual de criterio esté validado de ninguna manera.
- Que todo el conocimiento de una persona pueda pasar a un documento.

### 12. Vías de acceso: lo que funciona y lo que no (Etapa 3.8A.1)

Se registra porque **es la segunda tanda seguida bloqueada por los editores** y porque la
recuperación dirigida encontró rutas que no se habían probado. No es una nota técnica: decide
cuánta evidencia puede tener el libro.

| Vía | Resultado |
|---|---|
| **Depósito Crossref del propio editor** (`api.crossref.org/works/<DOI>`) | **La mejor.** Identidad siempre; y **el resumen íntegro cuando el editor lo depositó** —Wiley lo hace, Elsevier, IEEE y OUP no—. Es el editor hablando, no un agregador. |
| **Portales institucionales de investigación** (Pure, CRIS) | **Muy buena y poco usada.** Bond University desbloqueó F-028 tras fallar Elsevier y Southampton; ASU dio F-030; Maastricht resolvió la autoría de F-032. **En los tres casos probados** reprodujeron el resumen del editor y **no bloquearon**; son tres, no una regla. |
| **Copias académicas del original en dominios universitarios** | **La única que dio texto original**: el PDF de F-031 alojado por el MIT. |
| **PubMed / E-utilities de la NLM** | Buena para corroborar de forma independiente en lo biomédico y educativo (F-029). |
| **OpenAlex, Semantic Scholar** | Solo para **localizar**. Sus resúmenes son reconstrucciones y así se marcan en la fila. |
| **Páginas de editor** (Elsevier, Wiley, Taylor & Francis, SAGE, IEEE, OUP) | **Bloqueadas o vacías, sin excepción en esta tanda.** |
| **Repositorios institucionales de los autores** (Southampton, UWE, EPFL, HAL, figshare, DTIC) | **Bloqueados.** Southampton falló por tres rutas distintas, incluida la dirección exacta del fichero. |

**Dos lecciones que valen para las tandas siguientes.** Primera: **un registro sin resumen no
prueba que el artículo no tenga resumen**; F-028 pasó de «inutilizable» a resumen íntegro sin
que el artículo cambiara. Segunda: **un depósito incompleto no prueba autoría**; el registro de
OUP para F-032 lista un autor de tres.

**Y una advertencia sobre el propio proyecto:** ambos errores se cometieron aquí, en la Etapa
3.8A, y ambos se registraron con una seguridad que no correspondía al nivel de comprobación
alcanzado. La regla que queda: **antes de declarar una fuente inutilizable o una autoría
dudosa, agotar las vías institucionales**, que son gratuitas y no estaban probadas.

---

## Q-08 — Resultado (Etapa 3.9A, 2026-09-08)

Se investigó porque el capítulo 10 usa, en cada página, palabras que en el mundo profesional
tienen dueño: autoridad, aprobación, revisión, separación de funciones, control. **El riesgo no
era escribir poco: era convertir prácticas de control en reglas universales.**

### 1. Nivel de lectura, y por qué esta tanda es distinta

| Fuente | Qué es | Lectura alcanzada |
|---|---|---|
| **F-034** GAO, *Green Book*, 2025 | Norma de control interno para entidades federales de EE. UU. | **Leída directamente en el PDF oficial.** Definición, limitaciones, separación de funciones, preventivo/detectivo, documentación y tabla de categorías. |
| **F-035** IRS, *Internal Revenue Manual* 4.10.3.6 | Manual de procedimiento para inspectores fiscales | **Leída directamente en la página oficial**, apartado por apartado. |
| **F-036** PCAOB, *Staff Views*, 2009 | Guía de personal para auditores de empresas cotizadas pequeñas | **Leída directamente en el PDF oficial.** |
| **F-037** COSO, marco de 2013 | Marco privado de referencia | **Solo identidad.** El marco se vende y la etapa tenía prohibido comprar documentos. |

**Es la primera tanda del proyecto con la mayoría de sus fuentes leídas enteras**, y el motivo no
tiene mérito: son documentos públicos de organismos que no bloquean la consulta, al revés que los
editores académicos de las dos tandas anteriores.

### 2. Las once preguntas de la etapa, contestadas

**1. ¿Qué es control interno?** El Green Book lo define como «a process effected by an entity's
oversight body, management, and other personnel, designed to provide **reasonable assurance** that
the objectives of an entity will be achieved», en tres categorías: operaciones, información y
cumplimiento. **Para el libro basta con mucho menos**, y conviene que el libro use su propia
formulación en lugar de traducir una norma: *el conjunto de límites, comprobaciones y registros que
hacen menos probable que algo se salga de lo previsto sin que nadie se entere a tiempo.*

**2. Autorizar, aprobar, ejecutar, registrar, revisar.** Aquí hay un hallazgo que obliga a corregir
una intuición del proyecto. **La tríada de la norma no son cuatro funciones ni cinco: son tres** —
«management considers the need to separate control activities related to **authority, custody, and
accounting**» (F-034, 10.22)—. Lo que sí aparece nombrado, en la tabla de categorías de F-034 y en
F-035:

| Verbo del libro | Respaldo |
|---|---|
| **Autorizar / aprobar** | **A.** «Authorization of transactions» figura como categoría de actividad de control (F-034, tabla 1); *authority* es uno de los tres elementos que se separan. |
| **Registrar** | **A.** «Control activities over complete, accurate, and timely recording of valid transactions» (F-034); «timely recording of all transactions» (F-035). |
| **Revisar** | **A.** Revisiones de alto nivel y revisiones por la dirección en el nivel funcional (F-034); «supervision of work and **periodic review by independent third parties**» (F-035). |
| **Ejecutar** | **B.** Lo más próximo en la norma es *custody*, que no es lo mismo. El libro puede usar «ejecutar» como palabra llana, **sin presentarlo como término del marco**. |
| **Iniciar** | **C. Diseño propio.** Ninguna de las fuentes leídas lo aísla como función. Si el capítulo 10 lo usa, es del libro. |

**3. ¿Qué intenta evitar la separación de funciones?** Que la misma persona pueda **hacer y ocultar**:
«separation of duties will **reduce the opportunity** for any person to both **perpetrate and
conceal** errors or irregularities» (F-035). Y ayuda a limitar que la dirección pase por encima de
sus propios controles (F-034, 10.22). Nótese el verbo: **reduce la oportunidad**, no la elimina.

**4. ¿Es una regla universal que cada función la haga una persona distinta?** **No, y esto es lo más
importante que trae Q-08.** El propio Green Book prevé lo contrario en su texto normativo: «**Where
such segregation is not practical, management designs alternative control activities to mitigate the
risk**» (10.21). Y añade que el control interno «is flexible to allow management to tailor control
activities to meet the entity's unique needs», atendiendo entre otras cosas al «**size and complexity
of the entity**» (10.03). **El libro tiene prohibido enunciar «quien inicia no aprueba ni registra»
como regla general.**

**5. ¿Qué ocurre cuando no hay suficientes personas?** Las tres fuentes leídas dicen lo mismo desde
tres sitios distintos, y esa coincidencia es lo que hace sólido el hallazgo:

- **F-034 (10.23), norma federal:** «If segregation of duties is not practical within a business
  process **because of limited personnel or other factors**, management designs alternative control
  activities to mitigate the risk of fraud, waste, or abuse in the business process.»
- **F-036, regulador de cotizadas:** «smaller, less complex companies have fewer employees, which
  limits the opportunity to segregate incompatible duties. Smaller, less complex companies **might use
  alternative approaches** to achieve the objectives of segregation of duties.»
- **F-035, administración tributaria, y es la que llega al caso extremo:** «**Many small businesses
  have one owner and no employees. Although no separation of duties can exist in this situation, other
  control procedures might be in place** to assure accurate reporting of income and expenses.»

**El problema estructural de la ruta B está reconocido por escrito en una fuente oficial.** Eso es
exactamente lo que el proyecto necesitaba y no tenía.

**6. ¿Qué controles alternativos existen?** F-035 nombra tres junto a la separación: documentación de
procedimientos y transacciones; supervisión del trabajo y revisión periódica por terceros
independientes; y registro oportuno de todas las transacciones. F-034 añade la distinción operativa
más útil del capítulo: **preventivo** es «designed to avoid an unintended event or result **before**
it occurs»; **detectivo**, «designed to discover and timely correct an unintended event or result
**after** it occurs». Esa pareja traduce directamente la distinción que el capítulo 10 necesita entre
**aprobar** y **revisar**.

**7. ¿Qué controles alternativos NO equivalen a la separación? Hallazgo negativo, y hay que decirlo.**
**Ninguna fuente leída afirma que un control alternativo equivalga a la separación de funciones, y
ninguna afirma que sea más débil.** F-036 deja la cuestión expresamente abierta: el auditor «should
**evaluate whether** those alternative controls achieve the control objectives». Consecuencias:

- El libro **no puede decir** que un control alternativo sustituya a la separación.
- El libro **no puede apoyarse en estas fuentes** para decir que es más débil. Si lo dice —y creemos
  que debe decirlo—, **es juicio propio del Método LEGADO** y así debe declararse.
- Lo que **sí está respaldado** es más estrecho y basta: la separación de funciones **existe para que
  una misma persona no pueda hacer y ocultar** (F-035); donde una sola persona hace todo, esa
  posibilidad **no desaparece**, y la propia norma reconoce que ni siquiera la separación la elimina
  del todo, por el riesgo de colusión (F-034, 10.22).

**8. ¿Qué debe quedar documentado?** El Green Book convierte la documentación en requisito (3.09) y
le pone la medida correcta para este libro: «The extent of documentation… **is a matter of judgment
for management**», considerando «the benefits and costs… as well as **the size, nature, and complexity
of the entity**» (3.12). Y aporta una frase que sostiene la tesis entera del libro desde una norma
pública: documentar «provides a means to **retain organizational knowledge and mitigate the risk of
having that knowledge limited to a few personnel**» (3.10).

**9. ¿Qué puede revisar después la misma persona? Sin respaldo.** Ninguna de las fuentes leídas
describe la autorrevisión como control. F-035, cuando habla de revisión, la califica de
**independiente**. Por tanto: **lo que el capítulo 10 proponga para quien trabaja solo es diseño
propio**, no puede llamarse revisión independiente y **no puede presentarse como más débil ni como más fuerte** que otra clase de control —eso quedó sin resolver en las dos direcciones (V-61)—. El método puede recomendar mayor cautela, y entonces es recomendación del
libro, no por autoridad de nadie.

**10. ¿Qué puede requerir un tercero real?** La revisión periódica por terceros independientes figura
entre los procedimientos de control reconocidos (F-035). **Pero ninguna fuente la exige a un negocio
pequeño**, y el libro no puede convertirla en obligación ni suponer que exista.

**11. ¿Qué no puede prometer una matriz de autoridad?** El límite lo pone la propia norma, y conviene
citarlo tal cual: «no matter how well designed, implemented, or operated, an internal control system
**cannot provide absolute assurance** that an entity will meet all its objectives», por factores
externos, **juicios sesgados, error humano, que la dirección pase por encima de sus propios controles,
colusión** u objetivos mal planteados (F-034). Una matriz no impide que se cruce un límite: hace que
cruzarlo sea **visible**.

### 3. Matriz de evidencia

| Fuente | Ámbito | Nivel de lectura | Principio que aporta | ¿Aplica a pyme? | ¿Aplica a negocio de una persona? | Qué puede respaldar en el capítulo 10 | Qué NO puede respaldar |
|---|---|---|---|---|---|---|---|
| **F-034** GAO Green Book 2025 | Entidades **federales** de EE. UU.; su propio texto extiende el uso posible a entidades estatales, locales, cuasigubernamentales y sin ánimo de lucro, **y no menciona empresas privadas** | **Directa, amplia** | Definición de control interno; seguridad razonable y no absoluta; separación de *authority, custody, accounting*; **controles alternativos cuando la separación no es practicable**; preventivo/detectivo; documentación proporcional al tamaño | **Solo con cautela.** No le es aplicable; sirve como enunciado de principio | **Solo con cautela** | Que los principios existen y qué dicen; que la separación admite alternativas; que ningún control da certeza absoluta; que documentar reduce que el conocimiento quede en pocas personas | Que una pyme deba cumplirla. Que el capítulo 10 la implemente. Cualquier obligación |
| **F-035** IRS, IRM 4.10.3.6 | Auditoría **tributaria** de EE. UU.; apartados de 2003 | **Directa** | En un negocio de un propietario sin empleados **no puede existir separación de funciones**, y aun así pueden existir otros procedimientos; la separación reduce la oportunidad de hacer y ocultar; el propietario puede pasar por encima de los controles | **Solo con cautela**, y como descripción, no como norma | **SÍ, y es la única.** Es la fuente que nombra el caso | Que el problema de la ruta B existe y está reconocido por escrito; que la ausencia de separación no cancela la necesidad de fiabilidad | Ninguna obligación de gestión. Nada sobre cómo debe gobernarse un negocio |
| **F-036** PCAOB Staff Views 2009 | Auditoría de **empresas cotizadas pequeñas** de EE. UU.; **no son reglas del organismo** | **Directa** | Menos empleados limitan la separación; se usan enfoques alternativos **cuya suficiencia hay que evaluar**; la implicación intensa de la dirección **aumenta la oportunidad de pasar por encima** de los controles | **Solo con cautela** | **No directamente**: habla de empresas con empleados | Confirmación independiente de que la separación se limita por tamaño y de que existen alternativas; que la concentración añade riesgo de anulación | Que sea norma. Que valga para negocios privados o profesionales independientes |
| **F-037** COSO 2013 | Marco privado internacional | **Solo identidad** | — | — | — | Como mucho, que existe un marco de ese nombre y que una norma pública lo cita como origen de sus principios | **Nada de contenido.** Ninguna cita. Que obligue a alguien. Que el capítulo o la herramienta se basen en él |

### 4. Clasificación de los componentes del capítulo 10

**A** respaldado · **B** compatible, no confirmado · **C** diseño propio del Método LEGADO ·
**D** no respaldado, no se escribe

| Componente | Clase | Nota |
|---|---|---|
| Que existan **límites escritos** para las decisiones | **A** | Es el núcleo de las actividades de control en F-034 |
| **Autorización** como control | **A** | F-034, tabla 1 |
| **Registro** de lo decidido | **A** | F-034 y F-035 |
| **Revisión posterior** como control | **A** | F-034 (revisiones de dirección) y F-035 (revisión periódica) |
| **Aprobación antes / revisión después** | **A** | Traduce la pareja preventivo/detectivo de F-034 |
| Que la **separación de funciones** reduzca la posibilidad de hacer y ocultar | **A** | F-035 |
| Que la separación **no siempre sea practicable** y se sustituya por otros controles | **A** | F-034 (10.21, 10.23), F-036, F-035 |
| Que en un negocio de una persona **no exista separación** | **A** | F-035, verbatim |
| Que **ningún control dé certeza** | **A** | F-034 |
| Que documentar **reduzca que el conocimiento quede en pocas personas** | **A** | F-034 (3.10). Es la frase más útil de la tanda para el libro |
| **Proporcionalidad** al tamaño y la complejidad | **A** | F-034 (3.12, 10.03) |
| Distinguir **iniciar** como función propia | **C** | Ninguna fuente lo aísla |
| **Riesgo y reversibilidad** como dos lentes separadas | **C** | La reversibilidad no aparece en ninguna fuente leída como criterio de control |
| Clasificar decisiones en **proceder / pausar / aprobación previa / reservada** | **C** | Diseño del libro. Compatible con los principios, no derivado de ellos |
| **Revisión diferida por uno mismo** | **C** | Sin respaldo. No puede llamarse independiente |
| Que la revisión propia sea **más débil** que la ajena | **C** | Razonable, pero **es juicio del libro**: ninguna fuente lo dice |
| Que los controles alternativos sean **más débiles** que la separación | **C** | F-036 deja la suficiencia abierta a evaluación; no la resuelve |
| **Decisiones reservadas por ley, licencia o responsabilidad profesional** | **C**, con remisión | El libro señala la categoría; **no dice qué está reservado**, que es materia de cada jurisdicción (D-033) |
| Que una regla o un procedimiento **tenga autoridad** | **D** | Ninguna fuente atribuye autoridad a un objeto. Corregido en D-072 |
| Cualquier **puntuación de riesgo** o semáforo | **D** | Ninguna fuente la ofrece; el proyecto ya prohíbe puntuar |
| Que la matriz **evite** errores o fraude | **D** | F-034 lo desmiente expresamente |

### 5. Lo que el capítulo 10 no podrá decir

- Que exista una obligación de control interno para el negocio del lector. **Ninguna de las fuentes
  leídas le es aplicable.**
- Que «quien inicia no aprueba ni registra» sea una regla. **La propia norma prevé lo contrario
  cuando no hay personal suficiente.**
- Que un control alternativo equivalga a la separación de funciones.
- Que la revisión de uno mismo sea independiente.
- Que una matriz de autoridad impida errores, fraude o que alguien se salte un límite.
- Nada citando a COSO.
- Nada sobre qué decisiones están legalmente reservadas en ningún país.

### 6. Lo que sí podrá decir, con fuente

- Que existe un cuerpo de principios de control interno reconocido por organismos públicos, y que su
  propósito es **dar seguridad razonable, nunca absoluta** (F-034).
- Que la separación de funciones existe para que **una misma persona no pueda hacer y ocultar**
  (F-035), y que **reduce la oportunidad** sin eliminarla (F-035, F-034).
- Que **cuando no hay personal suficiente, se diseñan controles alternativos**: lo dice una norma
  federal (F-034), lo confirma un regulador de mercados (F-036) y lo reconoce una administración
  tributaria para el caso extremo de un propietario sin empleados (F-035).
- Que la extensión de lo que se documenta **depende del tamaño y la complejidad**, y es un juicio de
  quien dirige (F-034).
- Que documentar sirve, entre otras cosas, para **que el conocimiento no quede limitado a unas pocas
  personas** (F-034).

### 7. Advertencia de método

**No validar por asociación.** Que el Green Book, el IRS y el PCAOB respalden algunos principios **no
convierte a la Matriz de autoridad en un instrumento respaldado**. Su estructura —clasificar por lo
que importa si sale mal y por la posibilidad de deshacerlo, y después fijar límite, pausa, revisión y
evidencia— **no procede de ninguna de estas fuentes**. Es diseño del Método LEGADO informado por
principios, y el capítulo debe decirlo con esas palabras.

---

## Q-05 · Q-18 — Resultado conjunto (Etapa 3.10A, 2026-09-09)

Las dos preguntas se ejecutaron juntas porque el propio plan preveía que se fusionarían, y así
ha sido: el profesional que pega un documento en una herramienta externa y la pyme que sube un
listado de clientes **tienen el mismo problema con distinta ropa**.

### 1. La pregunta que se investigó, y la que no

**No se investigó** «qué leyes de privacidad existen». Eso es derecho comparado y el libro no lo
hace. **Se investigó** esto:

> Antes de entregar información de un negocio a una herramienta externa, **¿qué debe saber,
> comprobar o reducir la persona responsable?**

### 2. Nivel de lectura

| Fuente | Qué es | Lectura |
|---|---|---|
| **F-038** RIPD, *Estándares Iberoamericanos*, **26 de mayo de 2026** | **Marco regional de referencia. No es ley.** | **Directa, PDF oficial** |
| **F-039** SIC Colombia, Circular Externa 002 de 2024 | Norma vinculante **en Colombia** | **Directa, PDF oficial** |
| **F-040** EDPB, *Guidelines 07/2020*, v2.1 | Directriz interpretativa **UE/EEE** | **Directa, PDF oficial** |
| **F-041** EDPB, *Opinion 28/2024* | Dictamen **UE/EEE**, sobre modelos de IA | **Directa, PDF oficial** |
| **F-042** FTC, entrada de blog del personal, 2024 | **Blog de un organismo. No es norma.** | **Directa, página oficial** |

**Tercera tanda consecutiva con lectura directa mayoritaria.** El riesgo aquí no era citar de
menos: era **convertir la norma de un sitio en obligación de todos**.

### 3. El resultado principal, y es negativo

**No existe una regla única aplicable a todos los lectores de este libro.** Cambian el país, el
estado o provincia, el sector, el tipo de dato, el contrato, la profesión, la relación con la
persona afectada, el destino del dato y el proveedor. **Y el libro no debe enseñar cumplimiento
global.**

Pero el resultado negativo no deja las manos vacías, y esta es la conclusión útil de la etapa:

> **Lo que sobrevive al cambio de jurisdicción no son las obligaciones: son las preguntas.**

### 4. Principios que aparecen de forma suficientemente transversal

Aparecen, con distinto nombre y distinta fuerza jurídica, en más de una de las fuentes leídas:

| Principio | Dónde aparece | Qué permite decir al libro |
|---|---|---|
| **Finalidad y minimización** | F-038, 18.1: solo datos «adecuados, pertinentes y limitados al mínimo necesario»; F-039, criterio de **necesidad** | Que **preguntarse si hace falta el dato completo** es un paso reconocido, no una manía |
| **La tecnología no cambia la obligación** | F-039: las normas son «neutrales temática y tecnológicamente» y se aplican «al margen de… las tecnologías»; F-042: «There is no AI exemption from the laws on the books» | Que **usar una herramienta nueva no crea una excepción**. Dos jurisdicciones muy distintas dicen lo mismo |
| **Responsabilidad de quien decide** | F-038, «responsabilidad demostrada»; F-039, *accountability*; F-040: el responsable debe **poder probar** que evaluó las garantías | Que **la responsabilidad no se subcontrata** |
| **Comprobar antes de contratar** | F-040: solo proveedores que ofrezcan «sufficient guarantees», valorando pericia, fiabilidad, recursos y certificaciones | La lista de **qué mirar en un proveedor** |
| **El proveedor no va más allá de lo instruido** | F-040: «documented instructions»… «shall not go beyond»; F-038, 34.4: el encargado que decide por su cuenta **pasa a ser responsable** | Que **hay una frontera** entre quien encarga y quien ejecuta, y que cruzarla cambia de sitio la responsabilidad |
| **Seguridad y confidencialidad** | F-038, 34.3.c y e; F-039, instrucción VIII, con medidas técnicas, humanas, administrativas, físicas y **contractuales** | Que la seguridad **también se pacta**, no solo se instala |
| **Fin de la relación** | F-038, 34.3.f: suprimir, devolver o comunicar los datos al terminar | Que **preguntar qué pasa al cerrar la cuenta** es pertinente |
| **Subcontratación** | F-038, 35.1: hace falta **autorización previa por escrito** del responsable | Que **quién más toca el dato** es una pregunta legítima |
| **Información sobre el propio sistema** | **F-038, 34.3.k**, y es la pieza más útil de la tanda | Que cuando el servicio implica IA, **el proveedor debe dar información sobre funcionamiento, limitaciones, seguridad, trazabilidad, calidad de datos, supervisión y gestión de riesgos** |

### 5. Lo que hay que remitir siempre a la jurisdicción

**Sin excepción, y el capítulo debe decirlo:**

- **Qué datos son «sensibles» o de categoría especial.** Ninguna de las fuentes leídas permite una
  lista universal, y las que existen no coinciden entre sí.
- **Qué base legitima un tratamiento** y si hace falta consentimiento.
- **Qué exige un contrato con un proveedor**, y si hace falta uno por escrito.
- **Cuándo puede salir un dato del país.**
- **Qué obligaciones impone una profesión regulada.** No lo decide este libro (D-033).
- **Qué hay que notificar, a quién y en cuánto tiempo, si algo se filtra.**

### 6. Las tres clases de información, que no son lo mismo

La distinción más útil que produce esta investigación, y **es del libro, no de las fuentes**:

| | Qué es | Qué la gobierna |
|---|---|---|
| **A. Datos personales** | Información vinculada a una persona identificada o identificable | Normas de protección de datos, **que varían por jurisdicción** |
| **B. Información confidencial del negocio o de terceros** | Puede **no** ser dato personal: precios, fórmulas, un documento de un cliente | Contrato, secreto empresarial, deber profesional, relación comercial |
| **C. Credenciales y secretos de acceso** | Contraseñas, claves, tokens, códigos de recuperación | **Ni privacidad ni confidencialidad: es otra cosa.** Una credencial no es información que se analiza |

**Meterlas todas dentro de «privacidad» es el error que la herramienta 9 debe evitar.** Un
documento puede ser suyo, no contener ningún dato personal **y aun así no poder entregarlo**,
porque lo protege un contrato. Y de ahí una regla que el capítulo 11 puede enunciar:

> **«Es mío» no significa «puedo entregarlo».**

### 7. Datos sensibles: por qué no habrá lista

Las fuentes tratan las categorías reforzadas de manera distinta y remiten a la legislación
nacional. **Una taxonomía universal en el libro sería falsa y además envejecería mal.** La
herramienta preguntará en su lugar:

> **¿Su jurisdicción o su profesión tratan este tipo de dato con protección reforzada?**

Es menos vistoso y **es más seguro**: obliga a mirar donde hay que mirar.

### 8. El proveedor externo: qué preguntar, y de dónde sale cada pregunta

**A** respaldado · **B** compatible · **C** diseño propio del Método LEGADO

| Pregunta | Clase | Origen |
|---|---|---|
| ¿Para qué usa los datos? | **A** | F-040: instrucciones documentadas; F-038, 34.3.b |
| ¿Los usa para entrenar o mejorar su sistema? | **A** | F-042: los compromisos sobre no usar datos «to train or update their models» obligan |
| ¿Cuánto los conserva y cómo se eliminan? | **A** | F-038, 34.3.f |
| ¿Quién más puede acceder? ¿Hay subproveedores? | **A** | F-038, 35.1 |
| ¿Qué medidas de seguridad declara? | **A** | F-038, 34.3.c; F-039, instrucción VIII |
| ¿Qué dice sobre el funcionamiento y las limitaciones de su sistema? | **A** | **F-038, 34.3.k** |
| ¿Dónde se procesa la información? | **B** | Las fuentes tratan transferencias, pero remiten a la ley nacional |
| ¿Qué documentación puede enseñarle? | **A** | F-040: política de privacidad, términos de servicio, registro de tratamientos |
| ¿Qué pasa si cierra la cuenta? ¿Puede exportar o borrar? | **B** | Compatible con F-038, 34.3.f; no enunciado así en ninguna fuente |
| ¿Ha cambiado sus condiciones sin avisar? | **B** | F-042 lo trata como problema del proveedor, no como comprobación del cliente |

**Ninguna de estas preguntas es una obligación legal universal**, y el capítulo debe presentarlas
como lo que son: **lo que conviene saber antes de entregar algo**.

### 9. Minimización antes que prohibición

**La herramienta 9 no dirá «si hay datos personales, no use la herramienta».** Sería falso y
además inútil. La secuencia respaldada es la contraria —F-038 pide el mínimo necesario y F-039
exige comprobar que no haya «otra medida más moderada e igual de eficaz»—:

**¿necesita de verdad el dato completo?** Y si no: quitar nombres, resumir, sustituir
identificadores, trabajar con un extracto, usar datos inventados para probar, separar la parte
sensible.

**Con una cautela terminológica que el libro debe respetar.** Quitar un nombre **no es
anonimizar**. F-041 lo confirma desde el otro extremo del problema: la anonimidad de un modelo se
valora **caso por caso**, y los modelos entrenados con datos personales **no pueden considerarse
anónimos en todos los casos**. De modo que el libro usará **«reducir»**, que es lo que el lector
va a hacer de verdad, y reservará *seudonimizar* y *anonimizar* para cuando correspondan.

### 10. Qué podrá afirmar el capítulo 11, y qué no

**Podrá decir, con la fuente y su ámbito dentro de la frase:**

- Que existe un marco regional iberoamericano de referencia —**no una ley**— actualizado en 2026,
  y que pide tratar solo los datos mínimos necesarios, con una frase que vale la pena citar: **la
  IA «no justificará, por sí sola, la obtención masiva, indiscriminada o desproporcionada de datos
  personales»** (F-038).
- Que cuando el servicio implica IA, ese marco espera que **el proveedor informe sobre el
  funcionamiento, las limitaciones, la seguridad, la trazabilidad, la calidad de los datos, la
  supervisión y la gestión de riesgos** (F-038, 34.3.k).
- Que **una autoridad nacional ya ha escrito reglas concretas** sobre IA y datos personales, y que
  parte de comprobar **idoneidad, necesidad, razonabilidad y proporcionalidad** (F-039, Colombia).
- Que en la Unión Europea **quien contrata debe comprobar antes** que el proveedor ofrece garantías
  suficientes, **y poder probar que lo comprobó** (F-040).
- Que **usar una herramienta nueva no crea una excepción**: en Estados Unidos el personal de la FTC
  lo dice en una frase, «no hay exención de IA respecto de las leyes vigentes» (F-042).

**No podrá decir:**

- Ninguna obligación como universal. **Ninguna de las cinco fuentes obliga a todos los lectores.**
- Que exista una lista universal de datos sensibles.
- Que haya que firmar un contrato de encargo, como regla general.
- Nada sobre entrenamiento de modelos más allá de que **no se dé por anónimo** lo que pasó por uno.
- Que la RIPD sea una ley, que la circular colombiana valga fuera de Colombia, que el EDPB obligue
  fuera de la UE, o que una entrada de blog de la FTC sea «la ley de privacidad de Estados Unidos».
- Qué puede o no puede compartir una profesión regulada.

### 11. Arquitectura de G-2 — gobernanza de la información

G-2 no es poner los archivos en una carpeta. Debe dejar contestadas **siete preguntas**, y solo
sobre la información que sostiene las decisiones prioritarias:

| | Pregunta | Nota |
|---|---|---|
| 1 | **¿Qué información existe?** | Sale del inventario del capítulo 6; aquí no se rehace |
| 2 | **¿Cuál es la fuente de referencia?** | La versión que manda hoy |
| 3 | **¿Quién puede cambiarla?** | Enlaza con la matriz del capítulo 10 |
| 4 | **¿Cuándo se revisa?** | Vigencia, no exactitud eterna |
| 5 | **¿Qué tan sensible es?** | Las tres clases del apartado 6 |
| 6 | **¿Quién puede verla o usarla?** | Acceso, distinto de autoridad |
| 7 | **¿Qué no debe entregarse libremente a terceros?** | Es la herramienta 9 |

**Fuente de referencia, no copia única.** «Fuente única» leído literalmente es imposible: hay
copias, respaldos y exportaciones, y está bien que las haya. Lo que debe poder contestarse es
**cuál es la versión que manda hoy**.

**Y tres cosas que no se mezclan:** **fuente** —cuál manda—, **vigencia** —hasta cuándo se puede
confiar en ella— y **sensibilidad** —qué cuidado pide—. Un dato puede ser el bueno y estar
desactualizado; puede estar actualizado y ser delicado. **No hay una puntuación que las combine.**

**Criterio de cierre de G-2.** La información que sostiene las decisiones prioritarias tiene:
fuente de referencia identificada, vigencia o condición de revisión, sensibilidad declarada, regla
de acceso y uso, y —hasta donde el negocio pueda saberlo— tratamiento por terceros definido. **No
se exige tener el negocio entero ordenado, ni software, ni porcentaje alguno.**

### 12. Arquitectura de la herramienta 9

**No se crea el archivo en esta etapa.** Nombre y ubicación vigentes en el catálogo: *Lista de
información que no debe entregarse libremente a una inteligencia artificial*,
`recursos/informacion-restringida-ia.md`, herramienta 9 de 18.

**«Entregar libremente», definición operativa del libro** —no es un término jurídico—:

> **Introducir información en una herramienta externa sin haber decidido antes si hace falta, si
> puede reducirse, si se tiene autorización suficiente, qué hará el proveedor con ella y en qué
> condiciones queda protegida.** Lo contrario de entregar libremente no es negarse: es **entregar
> habiendo decidido**.

**Seis bloques, imprimibles:**

| | Bloque | Qué resuelve |
|---|---|---|
| 1 | **¿Qué quiero entregar?** | Describirlo en una línea |
| 2 | **¿De quién es y a quién afecta?** | Aquí se separan las tres clases: dato personal, confidencial de tercero, credencial |
| 3 | **¿Qué tan delicado es?** | Con la pregunta de la protección reforzada remitida a la jurisdicción o a la profesión |
| 4 | **¿Puedo reducirlo?** | Minimización antes que prohibición |
| 5 | **¿Sé qué hará el proveedor?** | Las preguntas del apartado 8 |
| 6 | **Decisión** | Una de las cuatro salidas |

**Cuatro salidas, y son del método, no categorías jurídicas:**

| | |
|---|---|
| **Puede usarse tal cual** | No hay información restringida en juego |
| **Reducir antes de usar** | Se entrega, pero menos |
| **Solo en un entorno aprobado** | Existe un sitio pactado para ese tipo de información |
| **No entregar libremente** | Hoy no sale sin resolver antes lo que falta |

**Regla propia sobre credenciales.** Q-07 no está ejecutada, así que el libro **no hará ninguna
afirmación de ciberseguridad**. Lo que sí puede fijar como regla del método: **una credencial no
es material de análisis y no se pega en una conversación.** Se declara como diseño propio.

**Ruta A:** debe quedar escrito **quién puede entregar qué tipo de información a qué clase de
herramienta**. **No se inventan cargos** —ni delegado de protección de datos, ni responsable de
seguridad, ni departamento legal— si no existen. **Ruta B:** el problema no desaparece, empeora,
porque quien decide, prepara y pega es la misma persona; **la función de la hoja es crear una
pausa** antes de entregar algo que se enviaría sin pensarlo. **No se finge aprobación externa.**

### 13. Diseño de M3 — primera presentación de la plataforma

**No se escribe en esta etapa.** Presupuesto vigente (D-053): capítulo 11, sección delimitada al
final, **máximo 450 palabras**, categoría **D**, más **C** y, si corresponde, una **E** al cierre.

**Por dónde debe entrar.** Por la necesidad que el lector acaba de descubrir, no por la
tecnología: tiene inventario, mapas, excepciones, manual de criterio, matriz de autoridad e
información clasificada, y **todo eso hay que mantenerlo vivo, ordenado y consultable**. Esa es
la pregunta que abre la puerta.

**Qué puede decir:** que existe —o puede existir— **una plataforma digital guiada que implementa
el Método LEGADO**, **opcional**, y que **el libro funciona entero sin ella**.

**Qué NO puede decir, y esto es lo más importante del apartado.** Los documentos de producto
declaran hoy **«arquitectura conceptual. Sin stack, sin proveedores, sin base de datos, sin
código»**. Por tanto **está prohibido escribir en presente** «la plataforma cifra», «la plataforma
cumple», «la plataforma protege», «la plataforma elimina», ni **prometer cumplimiento** de ninguna
norma. Un principio de diseño **no es una certificación**. Y tampoco puede presentarse como
agente, copiloto, cerebro ni gemelo: en el capítulo 11 la plataforma es **un sitio guiado para
organizar el método**, y las funciones de IA empiezan progresivamente después.

**Nombre:** ninguno. **D-061 sigue vigente** y no hay marca decidida. Se nombrará por su función.

**El problema del CTA, que no se resuelve aquí.** El presupuesto de D-053 **permite** una
invitación al cierre de M3, y M4 ya promete una versión digital gratuita del Índice al pie de la
herramienta 1. **Pero no existe ningún destino real**: ni dirección, ni registro, ni producto
disponible, comprobado por búsqueda en todo el repositorio. **No se inventa ninguno.** Queda
registrado como **V-62**, y la regla para la Etapa 3.10B es simple: **si al escribir el capítulo 11
no hay destino aprobado, no se escribe la invitación.** La categoría E es un presupuesto, no una
obligación.

---

## Q-17 — Resultado (Etapa 3.11A, 2026-09-09)

Se investigó para tres capítulos —12, 14 y 15— y con una consigna de austeridad: **tres de las
cuatro preguntas ya estaban cubiertas** por fuentes verificadas. Solo se buscó fuera para la que
no lo estaba.

### 1. Qué aportaba cada fuente ya verificada, releída

| Fuente | Qué contesta de Q-17 | Ámbito |
|---|---|---|
| **F-007** NIST AI RMF 1.0 | Supervisión documentada (MAP 3.5); mecanismos y responsables para **anular, desconectar o desactivar** (MANAGE 2.4); roles diferenciados en configuraciones persona-sistema (GOVERN 3.2). **Y el apéndice C, no registrado hasta ahora.** | **Voluntario**, internacional |
| **F-009** OCDE | Mecanismos y salvaguardas, incluida la **capacidad de intervención y supervisión humanas**; responsabilidad y trazabilidad. | **No vinculante** |
| **F-010** Reglamento (UE) 2024/1689, art. 14 | Supervisión por personas físicas; **conciencia del sesgo de automatización**; poder no usar, ignorar, anular o revertir la salida; e **interrumpir con un botón de parada** o procedimiento equivalente. | **UE, y solo alto riesgo** |

**Hallazgo negativo que conviene registrar:** **NIST no menciona el sesgo de automatización en
ningún punto**. Ese concepto llega al libro por F-010, y así debe atribuirse.

### 2. El hallazgo más importante de la etapa

Del **apéndice C de F-007**, que estaba sin registrar:

> «**Human-AI interaction results vary.** Under certain conditions —for example, in
> perceptual-based judgment tasks— the AI part of the human-AI interaction **can amplify human
> biases, leading to more biased decisions than the AI or human alone**. When these variations are
> judiciously taken into account in organizing human-AI teams, however, they **can result in
> complementarity and improved overall performance**.»

**Consecuencia editorial, y es una prohibición:** el libro **no puede prometer sinergia
automática**. Ni «lo mejor de ambos mundos», ni «la IA libera al humano para lo importante», ni
«persona más sistema siempre es mejor». La propia fuente dice que **puede salir peor**, y que la
mejora depende de **cómo se organice el trabajo**. Eso es exactamente lo que el Método LEGADO
propone hacer, y ahora puede decirlo sin exagerar: **la mejora no viene de juntarlos, viene de
gobernar cómo se juntan.**

El mismo apéndice añade dos matices útiles. **Contra el universal de supervisión:** «Some AI
systems may not require human oversight… Other systems may specifically require human oversight».
Y sobre el abanico real: «Human-AI configurations can span from **fully autonomous to fully
manual**… AI systems can autonomously make decisions, defer decision making to a human expert, or
be used by a human decision maker **as an additional opinion**.»

### 3. Sobre el exceso de confianza

**F-043**, revisión sistemática con PRISMA 2020 sobre **35 estudios de 2015 a 2025**, define el
sesgo de automatización como **la tendencia a confiar en exceso en las recomendaciones
automáticas**, y va más allá de la explicación habitual —exceso de confianza y falta de atención—
para nombrar factores que interactúan: **alfabetización en IA, nivel de experiencia profesional,
perfil cognitivo, cómo evoluciona la confianza con el tiempo, cuánta verificación exige la tarea y
la complejidad de la explicación**.

**Lo que no sabemos:** el texto completo no se abrió, así que **no puede atribuirse ningún dato
concreto, ninguna magnitud y ningún estudio individual**. Y su ámbito son dominios de alto riesgo
—sanidad, derecho, administración—, **no negocios pequeños**.

### 4. Sobre las explicaciones, y es contraintuitivo

Aquí F-043 contradice la intuición de la que parte casi todo el mundo:

> «although Explainable AI (XAI) and transparency mechanisms are designed to mitigate AB,
> **overly technical, cognitively demanding, or even simplistic explanations may inadvertently
> reinforce misplaced trust**, especially among less experienced professionals with low AI
> literacy… although explanations may increase perceived system acceptability, **they are often
> insufficient to improve decision accuracy or mitigate AB**.»

**Prohibición que se deriva:** el libro **no puede decir que explicar el razonamiento elimine el
sesgo**, ni que la explicabilidad garantice una confianza correcta. Una explicación puede subir
la aceptación **sin mejorar la decisión**, y una mala explicación —demasiado técnica o demasiado
simple— puede **reforzar una confianza equivocada**.

**Lo que la fuente sí propone**, y hay que citarlo como propuesta y no como resultado medido:
**el punto de intervención más viable es la participación del usuario**, porque «increased
verification effort has been shown to reduce complacency toward AI mis-recommendations». Los
autores **proponen** diseñar explicaciones que promuevan «critical engagement and independent
verification».

**Esto pertenece al capítulo 14** (D-019). El capítulo 12 **solo puede nombrar el problema**.

### 5. Sobre la delegación

**F-044** aporta lo que ninguna norma dice, y es asimétrico:

> «Modern AI can do a remarkable job of **efficient delegation to humans because it knows what it
> knows well and what it does not**. Humans, on the other hand, are **poor judges of their
> metaknowledge and are not good at delegating knowledge work to AI**.»

**Cómo puede usarse y cómo no.** Es **un estudio experimental sobre una tarea concreta**, y su
resumen no declara muestra ni dominio: **prohibido convertirlo en «las personas delegan mal»**.
Lo que sí sostiene, y es suficiente para el capítulo 12: **saber qué sabe uno y qué no es
difícil, y delegar bien depende de eso**. De ahí una consecuencia práctica del método: **si
juzgar el propio límite es difícil, más vale escribir el permiso antes que decidirlo en caliente,
delante de una salida que impresiona.**

### 6. Sobre la supervisión efectiva

Ninguna fuente define «supervisión efectiva» como concepto medible. Lo que sí hay es **una lista
de condiciones concretas**, y viene de F-010: poder **no usar** la salida, **ignorarla**,
**anularla**, **revertirla** e **interrumpir el sistema**. Más, de F-007, que existan
**mecanismos y responsables asignados** para anular o desconectar, y que los roles estén
**definidos y diferenciados**.

**Consecuencia:** *human-in-the-loop* **no es una garantía y no se usará como tal**. Una persona
que solo pulsa «aceptar» **no está supervisando**; lo que hace que una supervisión sea real es
poder decir que no, tener con qué juzgar y poder parar. **Y el ámbito de F-010 es la UE y solo
alto riesgo**: el libro toma de ahí **las condiciones como buen diseño**, no como obligación.

### 7. Clasificación de los principios del capítulo 12

**A** respaldado · **B** compatible, no confirmado · **C** diseño del Método LEGADO · **D** no
respaldado, no se afirma

| Principio | Clase | Nota |
|---|---|---|
| Que exista un abanico entre lo totalmente manual y lo totalmente autónomo | **A** | F-007, apéndice C |
| Que un sistema pueda usarse **como una opinión más** | **A** | F-007, apéndice C |
| Que la supervisión exija poder **ignorar, anular, revertir y detener** | **A**, con ámbito | F-010, UE y alto riesgo |
| Que tenga que haber **mecanismos y responsables** para desconectar | **A** | F-007, MANAGE 2.4 |
| Que los roles persona-sistema deban **definirse y diferenciarse** | **A** | F-007, GOVERN 3.2 |
| Que juntar persona y sistema **pueda empeorar** el resultado | **A** | F-007, apéndice C |
| Que **explicar no baste** para corregir el exceso de confianza | **A** | F-043. **Su capítulo es el 14** |
| Que a las personas les cueste juzgar **su propio metaconocimiento** | **A**, acotado | F-044 |
| **Capacidad ≠ permiso** | **C** | Es del libro. Ninguna fuente lo formula así |
| **El nivel se asigna por tarea, no a la empresa** | **C** | Compatible con F-007, que diferencia por configuración; **no derivado de él** |
| **Escala de siete niveles** | **C** | Diseño del proyecto. **Prohibido presentarla como estándar** |
| **Se puede bajar de nivel** | **C**, compatible | F-010 exige poder revertir y detener; bajar de nivel es del método |
| **Una buena respuesta no es un ascenso** | **C** | Del libro |
| **Responsable con nombre en cada nivel** | **C**, compatible | F-007 asigna responsabilidades; el «con nombre» es del método |
| Que la IA «aprenda» del uso ordinario | **D** | **No se afirma.** Ninguna fuente lo respalda y la metáfora del aprendiz no lo implica |
| Que persona + sistema sea mejor | **D** | **Desmentido** por F-007, apéndice C |
| Que *human-in-the-loop* garantice supervisión | **D** | **No se afirma** |

### 8. Auditoría de la escala de siete niveles

Hecha contra la evidencia de Q-17 y contra D-008, D-019, D-020, D-044 y D-045. **La escala se
mantiene: no hay motivo para rediseñarla.** Es diseño del método y no necesita coincidir con
ninguna taxonomía externa. Lo que sí aparecen son **dos residuos y una tensión**.

| Nivel | Función | Permiso | Qué NO permite | Respaldo | Diseño propio |
|---|---|---|---|---|---|
| **0** | Operación dependiente y manual | — | — | — | **Todo.** Ver la tensión abajo |
| **1** | Organización y digitalización | Ninguno de IA | Nada automático | Compatible con F-007 (MAP) | La secuencia |
| **2** | Observación, modo sombra | Recibir, clasificar, comparar, registrar | Recomendar lo sensible; ejecutar | **A**: «as an additional opinion» y configuraciones no autónomas (F-007) | El nombre y el propósito |
| **3** | Asistente informativo | Informar, avisar | Proponer qué hacer | Compatible | La frontera con el 4 |
| **4** | Recomendaciones | Proponer con evidencia | Ejecutar | **A**: F-043 obliga a no fiarlo a la explicación | La condición de explicabilidad |
| **5** | Ejecución limitada | Actuar dentro de reglas escritas | Salirse de ellas | **A**: F-010 y MANAGE 2.4 exigen poder detener | El criterio de «bajo riesgo» |
| **6** | Mano derecha digital supervisada | Coordinar y preparar | Decidir sin supervisión | Compatible | El techo (D-008) |

**Residuo 1 — «Aprende de las decisiones humanas» (nivel 2).** Esa frase puede leerse como
aprendizaje técnico automático, y **ninguna fuente de Q-17 respalda que un sistema mejore solo
por ser usado**. Corregido aquí: el nivel 2 **registra y compara** sus resultados con las
decisiones humanas, para que una persona pueda evaluar si merece más permisos.

**Residuo 2 — «Ganarse la confianza del fundador» (nivel 2).** Predetermina el resultado del
periodo de observación, que es exactamente el defecto que la Etapa 3.2.1 convirtió en regla del
proyecto: **ninguna señal de avance puede exigir un resultado determinado**. La evidencia puede
llevar a ampliar permisos, mantenerlos, reducirlos o retirar el sistema. Corregido: el propósito
es **construir evidencia para calibrar la confianza**.

**Tensión registrada, no corregida — el nivel 0.** Describe **dependencia de una persona**, no
**autonomía de un sistema**, de modo que la escala mezcla dos ejes en su primer escalón. **No se
toca**: el nivel 0 funciona bien como punto de partida narrativo y cambiarlo obligaría a rehacer
la correspondencia con los capítulos 1 a 5. Queda como **V-64**, para que el capítulo 12 lo
explique en una frase en lugar de disimularlo.

**Tercer hallazgo, en el índice.** La fórmula «primero mira, luego sugiere, después hace lo
pequeño» **se salta el escalón informativo**: entre mirar y sugerir está **avisar**, que es el
nivel 3 y tiene su propio capítulo. La secuencia correcta es **mira → avisa → recomienda →
ejecuta poco**. Se corrige al escribir el capítulo; el índice conserva su formulación como
resumen, con la advertencia registrada.

### 9. Arquitectura del capítulo 12

**Apertura.** Una escena donde una herramienta produce algo que impresiona de verdad —correcto,
rápido, mejor de lo que el lector esperaba— y el propietario se hace la pregunta natural: *si
puede hacerlo, ¿por qué no dejarla?* **Cero cliché tecnológico**: nada de revoluciones, nuevas
eras ni «cada día más empresas».

**Tesis central**, pendiente de mejor redacción al escribir:

> **Que una herramienta sea capaz de hacer algo no contesta si debe permitírsele hacerlo. La
> capacidad la trae de fábrica; el permiso lo da usted.**

**Progresión:** la escena → capacidad no es permiso → qué es y qué no es, en lenguaje llano → la
metáfora del aprendiz, con sus límites → la escala, declarada como del libro → el nivel se asigna
por tarea → subir, mantener o bajar → el cuadro → puente al modo sombra.

**Definición funcional de IA**, sin tecnicismos y sin fuente porque es del libro: **un sistema que
recibe información y produce una salida —un texto, una clasificación, un aviso, un resumen, una
recomendación— a partir de patrones extraídos durante su construcción.** Cero *transformers*,
*tokens*, *embeddings*, parámetros o redes neuronales.

**El aprendiz, delimitado.** Es **una metáfora sobre el orden en que se conceden permisos**, y
nada más. **No significa** que el sistema se reentrene, que cambien sus parámetros, que aprenda
de su negocio con el uso, que recuerde todo, que adquiera criterio, que construya personalidad ni
que se vuelva autónomo por exposición. Y no es **empleado, sucesor, socio, conciencia, réplica ni
persona digital**: **la autoridad no se gana produciendo buenas respuestas; la asigna el negocio.**

**Qué NO hace el capítulo 12.** No desarrolla el modo sombra (13), ni las recomendaciones, la
evidencia, las explicaciones y el sesgo de automatización (14), ni la ejecución, la aprobación y
la detención (15). **Y no usa IA**: aquí se explica, no se prueba. Cero demostración, cero
instrucción para el lector, cero asistente.

**Señal de paso, falsable.** Con **una sola tarea** basta: poder decir qué puede hacer
técnicamente la herramienta, qué le permite hoy, qué no, quién responde y **qué tendría que ver
para ampliar el permiso**. **No exige que exista tecnología implantada**, y responder «hoy no le
permito nada» es un resultado válido.

**Puente al 13.** «Ya sé qué le permito. ¿Cómo consigo evidencia sin entregarle todavía la
decisión?» Esa pregunta abre el modo sombra, y el capítulo 12 **no la contesta**.

### 10. Arquitectura del entregable

Nombre oficial vigente: **Cuadro de lo que puede y lo que no puede hacer**. **No se crea en esta
etapa** y **no se renombra** sin decisión editorial, aunque su nombre contenga la ambigüedad que
el propio capítulo existe para deshacer —«puede» significa a la vez *es capaz* y *está
autorizado*—. **Se resuelve dentro del cuadro, con dos columnas separadas.**

**Una fila por tarea. Nunca por empresa entera.**

| | Columna | Qué resuelve |
|---|---|---|
| 1 | **La tarea** | Concreta y reconocible. Una sola para empezar |
| 2 | **Qué información necesita** | Enlaza con el capítulo 11 y con la herramienta 9 |
| 3 | **Qué podría hacer técnicamente** | La capacidad, sin exagerarla ni minimizarla |
| 4 | **Qué le permito hoy** | El permiso. **Esta columna y la anterior no se rellenan igual** |
| 5 | **Qué no le permito** | En positivo, escrito |
| 6 | **Quién responde** | Persona, puesto u órgano real (D-073). Trabajando solo, usted |
| 7 | **Qué tendría que ver para ampliar o reducir** | La condición, **sin número, sin plazo y sin porcentaje** |

**Sin puntuación, sin porcentaje, sin marca, sin modelo y sin software.** Imprimible.

**En qué se diferencia de la herramienta 12**, la matriz de niveles del capítulo 15: **el cuadro
del 12 fija permisos iniciales por tarea** y contesta *¿qué le permito hacer hoy con esto?*; **la
matriz del 15 gobierna la autonomía de ejecución**, con sus condiciones, su aprobación y su
procedimiento de detención. **El cuadro no se convierte en la matriz**, y la matriz no repite el
cuadro.

**Ruta A:** la autorización puede recaer en una función o un responsable reales. **No se inventan
comités de IA, ni responsables de IA, ni cargos técnicos** que no existan. **Ruta B:** la misma
persona usa, autoriza y revisa; **no se finge separación**, y la protección viene de otro sitio:
límites escritos antes de usar, gradualidad, evidencia, reversibilidad y poder detener. **No se
afirma que eso equivalga a una separación de funciones** (V-61).

**Profesiones reguladas:** el cuadro puede marcar **«sujeto a regla profesional o sectorial»** y
remitir. **No decide qué puede delegar ninguna profesión** (D-033).

**Plataforma:** M3 ya ocurrió en el capítulo 11 y **no se repite**. El mapa producto-libro prevé
que la plataforma podría configurar permisos por tipo de tarea, pero **eso es arquitectura del
producto y no entra en el manuscrito**.

### 11. Qué podrá y qué no podrá afirmar el capítulo 12

**Podrá, con fuente y ámbito:** que existe un abanico entre lo totalmente manual y lo totalmente
autónomo, y que un sistema puede usarse **como una opinión más** (F-007); que una supervisión que
merezca el nombre exige poder **ignorar, anular, revertir y detener** (F-010, UE y alto riesgo);
que debe haber **mecanismos y responsables asignados** para desconectar (F-007); y que **juntar
persona y sistema no garantiza un resultado mejor** (F-007, apéndice C).

**No podrá:** prometer sinergia; decir que explicar elimina el sesgo —y además eso es del 14—;
presentar la escala como estándar; afirmar que el sistema aprende del negocio con el uso; usar
*human-in-the-loop* como garantía; nombrar marcas, modelos o proveedores; ni decidir qué puede
delegar una profesión regulada.


---

## Preflight del capítulo 13 (Etapa 3.12A, 2026-09-09)

**No se ha escrito el capítulo 13, ni la herramienta 10, ni la herramienta 11.** Esto es el
diseño previo, y su función es que la Etapa 3.12B no tenga que decidir nada estructural con el
texto ya empezado.

### 1. Suficiencia de la evidencia

La etapa empezó por comprobar si **F-007 bastaba**, antes de buscar nada. Casi.

**Lo que F-007 sí afirma, y sirve al capítulo 13** (releído en su PDF oficial, ampliando el
registro con la función MEASURE entera):

| Qué respalda | Dónde |
|---|---|
| Que los criterios se demuestren **para condiciones parecidas al entorno de uso real**, y que la medida pueda ser **cualitativa o cuantitativa** | MEASURE 2.3 |
| Que el comportamiento del sistema **se monitorice cuando está en producción** | MEASURE 2.4 |
| Que el enfoque de medición esté **conectado al contexto de despliegue** y consultado con quien conoce el dominio | MEASURE 4.1 |
| Que los resultados los **valide una persona experta en el dominio**, no el propio sistema, y queden documentados | MEASURE 4.2 |
| Que exista un **plan de monitorización posterior al despliegue** con mecanismos de **anulación y de retirada del sistema** | MANAGE 4.1 |
| Que **la frecuencia de la revisión periódica la determine la organización** | GOVERN 1.5 |
| Que medir en un entorno controlado **puede diferir de los riesgos que aparecen en la operación real** | Cuerpo, «Risk in real-world settings» |
| Que **«the ground truth may either not exist or not be available»** | Cuerpo, riesgos propios de la IA |

**Lo que F-007 NO afirma**, y hacía falta decirlo: no dice cuánto debe durar un periodo de
observación, no fija cadencia, no da umbral, no da porcentaje, no define cuándo la evidencia
acumulada basta para ampliar un permiso, y **no menciona en ningún punto el modo sombra ni las
alertas**. El término «shadow» no aparece; «alert» tampoco.

**Por eso se registró una fuente, y solo una: F-045**, NIST AI 800-4, *Challenges to the
Monitoring of Deployed AI Systems*, marzo de 2026. Aporta un límite material que F-007 no da y
lo aporta la misma institución: que las buenas prácticas y las metodologías validadas de
monitorización posterior al despliegue son **nascent**, que la prueba previa está
**inherentemente limitada** por hacerse en entornos controlados, y —lo que decide el capítulo—
que **«What is the right cadence for monitoring?» es una pregunta abierta declarada**.

**No se buscó «shadow mode» para legitimar el nombre**, por la razón que fija el propio encargo:
el nombre es una convención de este método y no necesita respaldo. Lo que necesita respaldo es
**la práctica** —observar, comparar y monitorizar antes de ampliar permisos—, y esa la dan las
dos fuentes.

### 2. Qué es el modo sombra, en este método

> **Modo sombra** es una **convención operativa del Método LEGADO**, no un estándar ni un
> término técnico reconocido. Describe una situación: **un sistema trabaja sobre una tarea real
> del negocio y produce su propia salida, pero esa salida no gobierna la decisión ni la
> ejecución.** La operación sigue por su procedimiento vigente, decide quien decidía, y después
> **se compara**.

Lo que define el nivel 2 no es que el sistema esté escondido: es que **su salida no tiene
autoridad operativa**.

### 3. Qué NO es el modo sombra

Seis deslindes, y los seis van en el capítulo:

| No es | Por qué importa decirlo |
|---|---|
| **No es secreto.** «Sombra» describe **ausencia de autoridad de la salida**, no invisibilidad ante las personas | La palabra invita al malentendido más caro del capítulo: uso oculto, vigilancia de empleados sin autorización, captura indiscriminada de comunicaciones. **Nada de eso está autorizado**, y **el capítulo 11 sigue gobernando qué información puede entregarse** |
| **No es entrenamiento** | **Prohibidas** estas seis formulaciones: «la IA aprende durante el periodo sombra», «se va entrenando con sus decisiones», «aprende cómo piensa usted», «absorbe su criterio», «se acostumbra al negocio», «cada decisión la hace más inteligente». El modo sombra **registra y compara**; lo que cambie después —reglas, información, configuración, permisos— **lo cambia una persona** |
| **No es una prueba que el sistema apruebe** | No hay aprobación automática ni ascenso por calendario |
| **No es una métrica** | Sin score, sin porcentaje mínimo, sin tasa de aciertos obligatoria, sin nota, sin «90 % para avanzar». Si el negocio ya tiene una medida pertinente, **puede registrarla**; el método **no inventa una para todos** |
| **No cambia la matriz de autoridad** | Quien decidía sigue decidiendo. **No se inventa ningún responsable de IA** |
| **No es ejecución** | Cero «actúa», «corrige», «resuelve», «bloquea», «envía», «ajusta», salvo para decir que no debe hacerlo |

### 4. Relación con la clonación del ADN Empresarial

Sin publicidad y en una frase: **clonar el ADN Empresarial no es enseñarle a una IA a repetir lo
que hace el fundador.** Es hacer accesibles, dentro de condiciones definidas, la información, el
criterio documentado, los procesos, las excepciones, las relaciones registradas, los límites y
los permisos. **El modo sombra comprueba qué ocurre cuando un sistema trabaja con ese contexto
sin tener autoridad operativa.** Es la primera vez en el libro que el material de las Partes II y
III se pone delante de una tecnología, y por eso el capítulo 13 es donde el método se mira al
espejo.

### 5. Qué se compara, y qué no significa comparar

**Arquitectura mínima, deliberadamente corta.** Para una tarea concreta:

**qué información estaba disponible · qué señaló el sistema · qué ocurrió realmente o qué decidió
la persona · qué diferencia hay · qué explicación tiene esa diferencia**

Cinco cosas, no siete. Las dos que se retiraron del diseño de partida —«qué registró» y «qué
ocurrió realmente» como columna separada de «qué decidió la persona»— se absorben: **el registro
es el soporte, no una columna, y el resultado real y la decisión humana son el mismo casillero
con dos posibles contenidos** según la tarea tenga o no un desenlace comprobable.

**La decisión humana no es verdad automática.** Cuando el comparador sea una decisión de una
persona, el libro la llama **«decisión real tomada»** o **«resultado observado»**, nunca *ground
truth* —término que además F-007 usa para advertir que puede no existir—. Una divergencia admite
**seis lecturas** y el capítulo las enumera sin jerarquía: se equivocó el sistema · se equivocó la
persona · faltaba información · había una excepción · la regla estaba mal formulada · **las dos
respuestas eran defendibles con información distinta**.

De ahí la regla del capítulo: **comparar no es imitar.** El objetivo no es que el sistema
converja con la persona.

### 6. Duración y salida del periodo

**Cero cifras.** No 7 días, no 14, no 30, no 90, no un número de casos ni de observaciones.
**Y la formulación importa tanto como la cifra ausente.** Lo autorizado es: **las fuentes
revisadas no establecen una duración ni una cadencia universales** —**F-045** clasifica «What
is the right cadence for monitoring?» como pregunta abierta, y **F-007** deja la frecuencia de
la revisión en manos de la organización—, **y por eso el Método LEGADO no fija una**.
**Prohibido** escribir que se haya demostrado que no exista, o que nadie lo sepa: una pregunta
abierta dice qué no está establecido, no qué no existe.

**El método no fija la duración por calendario.** La evidencia se acumula a partir de
**situaciones reales relevantes para la tarea**, y **una persona decide cuándo revisarla**. Una
tarea que ocurre a menudo puede dar más ocasiones de observar que una excepción rara, y eso es
una observación sobre la tarea, **no una fórmula de duración**: el método **tampoco mide el
periodo en número de casos**.

**El periodo no termina por calendario: termina cuando una persona revisa la evidencia y decide.**
**Seis salidas, todas legítimas**, y son **las mismas que produce la herramienta 10**:

**mantener en sombra · revisar información · revisar la regla · reducir el alcance · detener ·
permitir alertas de nivel 3**

**No existe la aprobación automática**, y **no se exige un resultado favorable**: la señal de paso
del capítulo se cumple con cualquiera de las seis.

**Reconciliación de recuento del 2026-09-09 (Etapa 3.12A.2), y conviene dejar dicho qué pasó
porque no se ha añadido ni quitado ninguna opción.** Este apartado enumeraba **cinco** salidas
—«seguir en sombra · corregir información o reglas y repetir · mantener el mismo permiso · pasar
la tarea al nivel 3 · reducir o retirar el uso del sistema»— y el apartado 9 enumeraba **seis**
para la misma decisión. **Eran la misma lista con distinto grano**, y tener dos recuentos bajo la
misma palabra habría llegado al capítulo. Se adopta **la de seis, que es la operativa**, porque
es la que el lector rellena. La correspondencia, para que se vea que nada se pierde: «corregir
información o reglas y repetir» se abre en **revisar información** y **revisar la regla**, que son
dos trabajos distintos; «reducir o retirar el uso» se abre en **reducir el alcance** y
**detener**, que no son lo mismo; «mantener el mismo permiso» es **mantener en sombra**; y «pasar
la tarea al nivel 3» es **permitir alertas de nivel 3**. **Seis, y son las únicas.**

### 7. La frontera entre el nivel 2 y el nivel 3

| | Nivel 2 | Nivel 3 |
|---|---|---|
| **Qué hace** | Observa, clasifica, resume, compara, registra | Informa, organiza, recuerda, detecta diferencias, **avisa** |
| **La pregunta** | **¿Qué habría señalado el sistema, sin que nadie actuara por eso?** | **¿Qué merece que el sistema llame mi atención?** |
| **Quién ve la salida** | Quien revisa la comparación, después | La persona a quien va dirigido el aviso, cuando corresponde |
| **No hace** | No propone qué hacer. No ejecuta | **No propone qué hacer.** No ejecuta |

El cambio no es de capacidad: es de **destino de la salida**. En el nivel 2 la salida va a un
registro; en el nivel 3 va a una persona.

### 8. Alerta: qué es y qué no

> Una **alerta** dice: **algo necesita su atención.** Una **recomendación** dice: **propongo que
> haga esto.** La primera es el capítulo 13; la segunda, el 14.

**Alerta ≠ decisión.** Una alerta no aprueba, no rechaza, no compromete, no firma, no ordena y no
ejecuta. **Eleva algo a la atención de una persona, y la autoridad permanece donde estaba.**

Ejemplo abstracto, del tipo que el capítulo usará: **«este dato se aparta de la condición
definida»** es una alerta. «Cambie de proveedor», «rechace el pedido» o «suba el precio» **no lo
son**, y ninguna de las tres puede aparecer en el capítulo 13.

**«Crítico» no es una categoría universal.** En este método significa **una condición que el
negocio ha decidido que justifica interrumpir o elevar la atención**, y se define **antes de que
ocurra** siempre que sea posible. No es una definición jurídica ni un estándar.

**Sobre el exceso de alertas**, y sin estadística: **si todo interrumpe, la categoría «crítico»
deja de distinguir.** Es razonamiento, no un dato sobre el comportamiento humano, y así se
escribe. **No se abre investigación sobre fatiga de alertas**, y **no se extrapolan** hospitales,
aviación, ciberseguridad ni emergencias a los negocios del lector.

**Tres destinos de una señal**, adoptados como diseño del método: **interrumpir ahora · mostrar
en la próxima revisión · solo registrar.** No es un calendario: la «próxima revisión» es la que
el negocio ya tenga. Su función es impedir que todo se convierta en notificación inmediata.

**Umbral no significa dinero.** Puede ser una cantidad, una condición, un estado, una combinación
de sucesos, **la ausencia de algo esperado**, una excepción, un vencimiento o un cambio frente a
una referencia. **Cero cifras**: las condiciones las define el negocio.

**Incertidumbre.** Si la herramienta no puede determinar con la información disponible si una
condición se cumple, **eso puede ser una alerta de revisión, y nunca una decisión**. Sin
porcentaje de confianza. La incertidumbre en las recomendaciones es del capítulo 14.

**Trazabilidad, no explicación.** Una alerta debe poder mostrar **qué condición se cumplió y qué
información la disparó**. Explicar el razonamiento de un sistema **es del capítulo 14**.

**Falsos avisos y omisiones**, en lenguaje llano y sin métricas: **el sistema avisó y no había
nada que mereciera atención**; **ocurrió algo que debía haberse señalado y el sistema no lo
señaló**. Se registran las dos.

### 9. Arquitectura de la herramienta 10 — Lista de verificación del modo sombra

Archivo futuro: `recursos/verificacion-modo-sombra.md`. **Herramienta 10 de 18. No se crea en
esta etapa.**

**Propósito:** comprobar que el sistema **observa, registra y compara sin decidir, sin recomendar
y sin ejecutar** —y que alguien ha mirado el resultado—.

**Seis bloques, no ocho.** Los ocho del diseño de partida se simplifican: «dónde se registra» y
«quién revisa» caben en un mismo bloque de gobierno, y «qué diferencias se encontraron» y «qué
decisión se toma después» son las dos caras de la revisión.

| | Bloque | Qué resuelve |
|---|---|---|
| 1 | **La tarea observada** | Una, concreta, ya definida en el cuadro del capítulo 12 |
| 2 | **Qué información puede recibir** | Remite a la herramienta 9. No se decide aquí |
| 3 | **Qué salida produce en sombra, y con qué se compara** | Y si el comparador es una decisión humana, se dice |
| 4 | **Dónde queda registrado y quién lo revisa** | Persona, puesto u órgano reales (D-073). Trabajando solo, usted |
| 5 | **Qué diferencias aparecieron y cómo se explican** | Con las seis lecturas de una divergencia, y con «no resuelto» como opción |
| 6 | **La decisión** | Una de las **seis salidas** de esta herramienta, listadas más abajo |

**Cabe en dos páginas imprimibles** en la parte que se rellena, como exige el catálogo.

**Lo que la herramienta 10 tiene prohibido preguntar**, porque predetermina el resultado:
«¿aprendió la IA?» · «¿ya confía?» · «¿qué porcentaje acertó?» como obligación · «¿cuánto tiempo
lleva?» como criterio de aprobación · «¿está lista para producción?».

**Salidas:** mantener en sombra · revisar información · revisar la regla · reducir el alcance ·
detener · permitir alertas de nivel 3. **Ninguna es la correcta, y no obliga a subir.**

### 10. Arquitectura de la herramienta 11 — Modelo de alertas críticas

Archivo futuro: `recursos/modelo-alertas-criticas.md`. **Herramienta 11 de 18. No se crea en esta
etapa.**

**Propósito:** definir **qué condición merece llamar la atención de una persona y cómo se
presenta**, sin decirle qué decisión tomar.

**Siete campos, no ocho.** «Qué se observa» y «condición que activa el aviso» se funden: una
condición ya nombra lo que observa.

| | Campo | Nota |
|---|---|---|
| 1 | **La condición** | Escrita **antes** de que ocurra, siempre que sea posible: «si falta X», «si aparece Y», «si cambia Z», «si esta excepción sigue vigente» |
| 2 | **De qué fuente sale la información** | Enlaza con la fuente de referencia del capítulo 11 |
| 3 | **Por qué merece atención** | En una línea, y del negocio: es lo que hace que «crítico» signifique algo |
| 4 | **A quién se avisa** | Persona, puesto u órgano reales. **No se inventan cargos** |
| 5 | **Cuándo** | Interrumpir ahora · próxima revisión · solo registrar |
| 6 | **Qué debe ver la persona para evaluarlo** | La condición cumplida y el dato que la disparó. **Nada más** |
| 7 | **Cuándo deja de estar activa** | Toda alerta caduca o se revisa. Si no, se acumulan |

**Lo que la herramienta 11 no puede contener:** «acción recomendada» · «decisión sugerida» ·
«aceptar recomendación» · «ejecutar» · «aprobar automáticamente» · «la IA decide la prioridad».
**La prioridad la gobierna una condición definida por el negocio.**

**El mismo dato, dos resultados.** Una misma observación puede no interrumpir en una tarea y
generar alerta en otra, **porque los permisos y las condiciones son por tarea**. Sigue sin existir
«una empresa en nivel 3».

### 11. Las dos rutas

**Ruta A.** El sistema observa una tarea cuya decisión **sigue tomando quien ya la tenía**. El
modo sombra **no cambia la matriz de autoridad**, y la evidencia la revisa quien tenga esa
responsabilidad de verdad. **No se inventa un responsable de IA.**

**Ruta B.** La misma persona ejecuta la tarea, decide y después revisa la comparación. **La
herramienta funciona igual** y debe poder decir «la comparación la hago yo después». **No se
finge independencia**, y **la revisión propia no se presenta como independiente** —constante ya
registrada—.

**Profesiones reguladas.** El capítulo **no decide** qué alertas debe usar una profesión concreta
ni qué puede observar una IA sobre datos regulados. **Remite** al capítulo 11 y al 16.

### 12. Arquitectura narrativa propuesta

Trece movimientos, y la secuencia se aparta del orden de partida en dos sitios, por un motivo
concreto en cada caso.

1. **La pregunta heredada del capítulo 12**, en la primera línea.
2. **Ver sin entregar la decisión**: la escena del caso, con el sistema observando y la persona
   decidiendo como siempre.
3. **Qué es el modo sombra**, con la definición y **los seis deslindes juntos** —incluido «sombra
   no es secreto», que va **aquí y no al final**: si el lector sospecha vigilancia, deja de leer.
4. **Qué se compara**, con las cinco cosas.
5. **Por qué una divergencia no es automáticamente un error del sistema**: las seis lecturas.
6. **Comparar no es imitar**, y **la decisión humana no es verdad automática**.
7. **La herramienta 10.**
8. **Qué hacer con la evidencia**: las salidas previstas, **sin resultado obligatorio**.
9. **Cuánto dura esto**, con la negativa razonada y las dos fuentes.
10. **El paso al nivel 3**: cambia el destino de la salida, no la capacidad.
11. **Qué es una alerta y qué no es**: frente a recomendación y frente a decisión.
12. **La herramienta 11**, con los tres destinos de una señal y el exceso de alertas.
13. **Señal de paso y puente al 14.**

**Los dos cambios respecto al orden de partida**, y por qué: «qué NO es el modo sombra» sube al
movimiento 3 en lugar de quedar después de la definición suelta, porque los seis deslindes son la
definición; y «cuánto dura» baja al 9, después de la herramienta 10, porque la pregunta solo se
hace de verdad cuando el lector ya tiene una hoja rellenándose.

### 13. El caso

**No se elige en esta etapa, y hay una razón para no elegirlo.** El encargo lo permite, y elegir
ahora repetiría el error de asignar sector con las listas todavía abiertas: **las herramientas 10
y 11 llevan ejemplo propio y se escriben en la misma etapa 3.12B**, de modo que los tres sectores
se deciden a la vez, mirando las dos listas —regla registrada en la Etapa 3.9B—.

**Lo que sí queda fijado, y son restricciones, no preferencias:**

| | |
|---|---|
| **Nuria no continúa** | La regla del apartado 5 de `control-de-casos.md` prohíbe **historia continuada entre capítulos**. Se comprobó expresamente. El capítulo 13 puede abrir **recordando la pregunta** con la que terminó el 12, pero **no la escena ni el personaje** |
| **Ruta** | **B**, salvo motivo mejor. El capítulo 12 fue ruta A y el reparto está en **5 A / 4 B**; una ruta B lo deja en 5 y 5, y el modo sombra en un negocio de una persona es **más fácil, no más difícil**, como ya anota el índice |
| **Género** | **Hombre**, por la alternancia caso a caso, que no se ha roto en nueve casos |
| **Sector** | **Sin fijar.** El previsto es *distribución regional*, disponible y sin repetición consecutiva —el 12 fue agricultura—, pero su único caso, C-01, es de ruta A y de una empresa con estructura. Si el capítulo va por ruta B, la lista corta es **mantenimiento**, **construcción** o **logística**, las tres con cero apariciones de caso |
| **Qué debe permitir ver el caso** | Una salida en sombra · una decisión humana tomada con independencia de ella · **una divergencia** · la revisión de esa divergencia · y **el primer aviso de nivel 3** |
| **Cómo no puede salir** | **Que el sistema acierte todo** —convierte el capítulo en publicidad— ni **que falle de forma caricaturesca** —lo convierte en una advertencia—. La lección está en la comparación, no en el resultado |

### 14. Señal de paso, falsable

Para **una** tarea, el lector puede avanzar cuando existan las seis cosas:

- un registro de lo que el sistema habría señalado;
- un resultado real con el que compararlo;
- las divergencias revisadas, **incluida la posibilidad de que no hubiera ninguna**;
- escrito **qué merece alerta**;
- escrito **quién la recibe**;
- y **una decisión humana** entre mantener, modificar, detener o pasar al nivel 3.

**No exige un resultado favorable**, y «lo detuve» cumple la señal igual que «lo subí a nivel 3».

### 15. Puente al capítulo 14, y las dos fronteras

El capítulo 13 termina cuando el sistema ya puede **avisar**. La pregunta nueva: **si ya puede
llamar mi atención, ¿cuándo debería proponerme qué hacer?** El capítulo 13 **no la contesta**.

| Frontera | Del 13 | Del 14 o del 15 |
|---|---|---|
| **13 / 14** | Observa, compara, registra, informa, alerta | **Propone**, explica razones, muestra evidencia, señala incertidumbre |
| **13 / 15** | **Cero ejecución** | Ejecución limitada dentro de reglas escritas |

**Cualquier frase que cruce esas fronteras es un defecto**, no una licencia narrativa.

### 16. Extensión y plataforma

**Objetivo 2.100 palabras; tope de D-030 con dos rutas, 2.415.** Las herramientas 10 y 11 viven
en `recursos/` y **no cuentan** en el manuscrito, aunque el capítulo las explique. **No se
rellena para llegar al objetivo.**

**Plataforma:** una mención de categoría C como máximo, **y no es obligatoria**. `producto/`
prevé ejecutar el modo sombra y guardar la comparación, pero **el libro debe poder hacer lo mismo
con papel y una tabla**, y eso es lo que el capítulo enseña. Si se menciona: **una frase, sin
llamada a la acción, sin dirección web, sin producto comercial y sin afirmar que existe hoy.**

### 17. Alcance ampliado (D-075)

El capítulo 13 trata **confianza operativa y permisos**, no jubilación. **No necesita mencionar la
expansión** y **no puede contradecirla**. La razón para construir evidencia es la misma para los
dos lectores de D-075: **no reducir la participación humana antes de saber qué ocurre cuando el
sistema observa el trabajo real.** Y sigue prohibido prometer que la IA llevará el negocio.


---

## Preflight del capítulo 14 (Etapa 3.13A, 2026-09-09)

**No se ha escrito el capítulo 14 y no se ha creado ningún archivo en `recursos/`.**

### 1. Suficiencia de la evidencia

**Cero investigación nueva, y la comprobación se hizo antes de decidirlo.** Q-17 ya cubre el
capítulo 14, y las tres fuentes que hacían falta estaban registradas.

| Fuente | Qué sostiene para el capítulo 14 | Qué NO sostiene |
|---|---|---|
| **F-010**, Reglamento (UE) 2024/1689, art. 14 | Que la supervisión humana exige poder **no usar la salida, ignorarla, anularla y revertirla**, y que quien supervisa debe ser **consciente del sesgo de automatización**. **Es la fuente de la que el concepto entra en el libro** (D-019) | **Nada fuera de su ámbito: Unión Europea y solo sistemas de alto riesgo.** No es ley mundial ni obligación del lector. **D-020: coincidencia no es cumplimiento**, y el libro no puede decir que seguirlo signifique cumplir nada |
| **F-043**, Romeo y Conti, revisión sistemática PRISMA | La **definición**: «the tendency to **over-rely on automated recommendations**». Los factores que interactúan —alfabetización en IA, experiencia, perfil cognitivo, evolución de la confianza, **cuánta verificación exige la tarea**, complejidad de la explicación—. Y el hallazgo que decide el capítulo: explicaciones **demasiado técnicas, exigentes o incluso demasiado simples pueden reforzar una confianza mal colocada**, y «although explanations may increase perceived system acceptability, **they are often insufficient to improve decision accuracy or mitigate AB**» | **Ningún dato, ninguna magnitud, ningún estudio individual**: solo se leyó el resumen íntegro del editor. Su ámbito son **dominios de alto riesgo**, no negocios pequeños. Y la verificación aparece como **propuesta de los autores**, no como resultado medido |
| **F-007**, NIST AI RMF | Que los resultados de la interacción persona-sistema **varían** y pueden ser **peores que los de cualquiera de los dos por separado**; que **presentar información y explicaciones a personas es complejo**, porque cada una deriva significado de manera distinta; y que la supervisión debe **definirse y documentarse** | **Complementariedad no es promesa.** Prohibido «humano + IA es mejor» |

**F-044 se evalúa y se descarta para este capítulo.** Aporta que juzgar el propio metaconocimiento
es difícil, lo cual sostiene *cuándo* delegar —capítulos 12 y 15—, no *cómo se presenta una
propuesta*, que es lo que trata el 14. **No se introduce solo porque exista.** **F-009** tampoco:
lo que aporta sobre intervención humana ya está dicho, con más precisión, por F-010.

**Conclusión: las fuentes actuales bastan. Cero investigación nueva y cero fuentes nuevas.**

### 2. Qué es una recomendación, en este método

> Una **recomendación** es **una propuesta de qué hacer, dirigida a una persona que conserva la
> autoridad** para aceptarla, modificarla, rechazarla, pedir más información o no actuar
> todavía.

**No es una decisión, ni una orden, ni una aprobación, ni una ejecución.**

### 3. Las tres fronteras

| Frontera | De un lado | Del otro |
|---|---|---|
| **Alerta / recomendación** | «**Algo necesita su atención**». Capítulo 13 | «**Propongo que haga esto**». Capítulo 14 |
| **Recomendación / decisión** | La produce el sistema y **no obliga a nada** | La toma una persona, **y la autoridad no se mueve** |
| **Capítulo 14 / capítulo 15** | **Propone.** Termina en una decisión humana, **sin ninguna ejecución automática** | Puede empezar a **ejecutar dentro de reglas escritas** |

**La tercera es absoluta.** En el capítulo 14, «**aprobé la recomendación**» **no significa** «la
herramienta la ejecutó». Significa que una persona decidió, y lo que pase después lo hace quien
lo hacía antes. **Prohibido en el capítulo 14:** ejecutar, aprobar por sí solo, enviar
comunicaciones, contratar, comprar, cancelar, modificar registros, cambiar permisos o reglas,
cerrar una alerta o retirar una condición.

**Y una cuarta que no es de nivel sino de expectativa: no todo aviso necesita recomendación.**
Una alerta puede terminar en revisión, en registro, en pedir más información o simplemente en
cerrarse. **El nivel 4 es un permiso adicional, no el destino obligatorio del nivel 3**, y el
paso requiere concederlo **para esa tarea** —sigue sin existir «su negocio ya está en nivel 4»—.

### 4. El sesgo de automatización, y por qué explicar no basta

Es el concepto que D-019 reserva a este capítulo, y **entra por F-010**, que exige que quien
supervisa sea consciente de él. **Definición**, sostenida por F-043: **la tendencia a confiar en
exceso en una recomendación automatizada.**

**Lo que el capítulo NO puede decir**, y es lo contrario de lo que casi cualquiera esperaría:
que explicar la recomendación haga desaparecer el problema. F-043 registra que las explicaciones
**pueden aumentar la aceptación sin mejorar la exactitud de la decisión**, y que una explicación
demasiado técnica, demasiado exigente **o incluso demasiado simple** puede **reforzar una
confianza mal colocada**.

**La consecuencia para el método no es «explicar más». Es otra, y más robusta:**

> **Una recomendación no se acepta porque suene bien, porque venga explicada, porque traiga
> muchos datos ni porque la haya producido una herramienta. Se acepta cuando usted ha podido
> comprobar algo.**

La explicación ayuda. La evidencia ayuda. **Ninguna de las dos sustituye la evaluación de una
persona.**

**Verificación activa, con su etiqueta puesta.** F-043 recoge que sus autores **proponen**
—no que hayan demostrado— que un mayor esfuerzo de verificación reduce la complacencia ante
recomendaciones incorrectas. El libro lo traduce sin tecnicismo y **como diseño propio**: la
persona **no solo recibe una propuesta; recibe algo que puede ir a comprobar**. Por eso el
formato exige decir **dónde mirar**, no solo qué se concluyó.

### 5. Qué significa «explicar» aquí

**No significa mostrar el razonamiento interno de un modelo.** El capítulo **no pide** cadena de
razonamiento, pasos ocultos, «cómo pensó la IA» ni explicación técnica de nada —y **F-007
advierte además que presentar explicaciones a personas es complejo**, porque cada una deriva un
significado distinto—.

Significa algo operativo y comprobable: **qué propone · en qué hechos o documentos se apoya ·
qué criterio aplicó · qué no sabe · qué cambiaría la propuesta.** Es **rastreabilidad**, no
narración del interior de la herramienta.

**Y explicación no es evidencia.** Una frase convincente no es una prueba: la evidencia es un
documento, un dato, un registro, una condición, una excepción, una regla o un resultado
observado, **con su fuente de referencia** (capítulo 11). Separar **evidencia** de **criterio**
—el criterio documentado del capítulo 9— es lo que impide confundir **fluidez** con **solidez**,
que es el mecanismo exacto que F-043 describe.

**Sobre el criterio, una cautela.** Que una recomendación diga qué regla aplica **no significa
que el Manual de criterio se haya convertido en un motor de reglas** ni que ese criterio esté
automatizado sin pérdida. Puede apoyarse en criterio documentado **sin prometer que lo aplica
perfectamente**.

### 6. La incertidumbre

**Sin porcentajes, sin scores, sin «confianza del 87 %».** Un número sin contexto es
exactamente lo que este capítulo tiene que evitar: da apariencia de rigor y no se puede
comprobar.

La incertidumbre se declara **en términos del negocio y específica de esa recomendación**:

> «falta este dato» · «esta fuente lleva sin actualizarse desde tal cosa» · «hay dos reglas que
> podrían aplicarse» · «hay una excepción sin resolver»

**Y no puede ser un descargo genérico.** «Puede equivocarse» o «consulte a un profesional» al
pie de todas las recomendaciones **no es declarar incertidumbre: es no declararla**. Si la misma
frase vale para cualquier propuesta, no dice nada de esta.

**«No hay recomendación todavía» es una salida legítima.** Cuando la información no alcanza, la
propuesta prudente es no proponer, y el formato debe admitirlo **sin que parezca un fallo**.

### 7. La decisión humana, y por qué no puede ser automática

El capítulo 13 estableció que **la decisión de una persona no es verdad automática**. El 14
necesita la cara contraria: **la recomendación del sistema no puede convertirse en la opción por
defecto.**

**Regla del método, no afirmación empírica** —el libro no diseña pantallas ni mide esfuerzos—:
**ninguna de las cinco respuestas se presenta como predeterminada o privilegiada, y no existe
«aceptar por omisión».** Las cinco son decisiones explícitas de una persona, y van juntas:

**aceptar · modificar · rechazar · posponer · pedir más información**

**Y aprobar no es ejecutar.** En este capítulo la aprobación termina en una persona que hace, o
manda hacer, lo que ya hacía. Qué puede ocurrir *después* de una aprobación es el capítulo 15.

**Registro mínimo, no auditoría.** Basta con que quede **qué se recomendó, quién decidió, qué
decidió, cuándo y qué modificó si modificó algo**. Lo suficiente para que una recomendación **no
desaparezca al aceptarse o rechazarse**; la auditoría completa es del capítulo 16.

### 8. Situación del Formato de recomendación explicada

**Comprobado antes de diseñarlo, y no hay contradicción que requiera una decisión nueva.**

- El **índice maestro** asigna al capítulo 14 el entregable *Formato de recomendación
  explicada*.
- El **catálogo de recursos** tiene **dieciocho** herramientas y **ninguna del capítulo 14**: la
  herramienta 12 es la *Matriz de niveles de autonomía*, del capítulo 15.
- **Ninguna decisión editorial vigente** dice que el formato deba ser una de las dieciocho. Se
  revisó el registro completo.

**Por tanto es un entregable interno del capítulo**, y hay **dos precedentes exactos**: la vista
del proceso real del capítulo 7 —**D-070**, que además dice literalmente «no se crea una
herramienta 19»— y el *Cuadro de lo que puede y lo que no puede hacer* del capítulo 12, resuelto
igual en la Etapa 3.11B **sin decisión nueva**.

**Consecuencia: el catálogo sigue en 18, la herramienta 12 no se desplaza, y al terminar la
Etapa 3.13B los recursos seguirán en 11 de 18.** **No se propone ninguna decisión editorial**,
porque no hay nada que decidir que no esté ya decidido; si el autor prefiere elevarlo a decisión
formal para que los tres casos queden bajo una sola regla, **es una preferencia razonable y no
un requisito**.

### 9. Arquitectura del Formato de recomendación explicada

**No se redacta en esta etapa.** Vive **dentro del capítulo 14** y tiene que caber sin convertir
el capítulo en una plantilla.

**Seis componentes, y se llega a seis desde los siete de partida.** Se fusionan «qué propone» y
«para qué», que **una sola frase bien escrita contesta a la vez** y que separadas invitan a
rellenar dos casillas con lo mismo. **No se fusionan** «qué no sabe» y «qué cambiaría la
propuesta», porque hacen trabajos distintos: la primera es honestidad, la segunda es **la que
le dice a usted dónde mirar**.

| | Componente | Qué impide |
|---|---|---|
| **1** | **Qué propone, y para qué** | Una propuesta sin finalidad. Y admite **«no hay recomendación todavía»** |
| **2** | **En qué evidencia se apoya, y dónde está** | Que una frase convincente pase por prueba. **Con la fuente de referencia**, para poder ir a mirarla |
| **3** | **Qué criterio o regla aplica** | Una conclusión sin origen. Separado de la evidencia **a propósito** |
| **4** | **Qué no sabe** | El descargo genérico. Tiene que ser de **esta** recomendación |
| **5** | **Qué haría cambiar la propuesta** | Que declarar una laguna se quede en gesto. Es el componente que **convierte la duda en algo comprobable** |
| **6** | **La decisión** | Que exista una respuesta por omisión. Cinco decisiones explícitas al mismo nivel, más **quién, cuándo y qué modificó** |

**Los componentes 2 y 3 son el «por qué» partido en dos**, y esa partición es deliberada: junta,
una explicación fluida se confunde con una explicación sólida.

**Ruta A y ruta B: el mismo formato, sin dos versiones.** Con equipo, quien recibe la propuesta y
quien decide pueden ser personas distintas. Trabajando solo son la misma, **y eso no se disfraza
de nada**: no existe la «autoaprobación» como función, es simplemente su decisión. Lo que el
formato conserva en las dos rutas es **la separación entre la propuesta y la decisión**, aunque
las dos pasen por la misma mesa. **No se finge separación de funciones** (V-61).

### 10. El caso C-11

**No se escribe en esta etapa.** Queda elegido, porque el capítulo 14 **no produce herramienta** y
hay un solo sector que asignar.

| | |
|---|---|
| **Ruta** | **A.** El 13 fue ruta B y el reparto está en 5 y 5 |
| **Género** | **Mujer**, por la alternancia caso a caso, intacta en diez casos |
| **Sector** | **Mantenimiento.** Cero apariciones de caso, y su único capítulo previsto —el 7— ya está escrito, así que **no le cuesta nada a nadie**. Sin repetición consecutiva: el 13 fue logística |
| **Riesgo** | **Bajo**, con las medidas de siempre |

**Por qué no importación y distribución, que es el sector previsto.** Porque el ejemplo de la
**herramienta 9** es **una mujer, de ruta A, en importación y distribución**, y C-11 iba a ser
mujer y de ruta A: **la misma triple coincidencia que hizo mover el capítulo 12 en la Etapa
3.11B**, ahora a tres capítulos de distancia en vez de uno. La regla se aplica igual. **El sector
conserva sus capítulos 14 y 17**; solo pierde el turno.

**Y la coincidencia que sí queda anotada**, porque es real aunque lejana: el ejemplo de la
**herramienta 4** —capítulo 7, siete capítulos atrás— transcurre en un taller de reparación de
maquinaria. Se diferencia en **género, escala y decisión**: aquel es un hombre en un taller
pequeño decidiendo *cuándo se acepta un trabajo urgente*, y **ese asunto está vedado a C-11**,
porque el ejemplo de la herramienta 8 lo usa otra vez. El caso del capítulo 14 **no puede tratar
de aceptar trabajos urgentes.**

**El mecanismo que el caso debe mostrar, en siete pasos:** una situación o alerta previa · una
recomendación · su evidencia · su criterio · **algo que la recomendación no sabe** · la revisión
de una persona · y una salida que **no sea aceptar ni rechazar, sino modificar**, que es la
respuesta que el formato existe para hacer posible y la que ningún capítulo ha mostrado todavía.

**El sesgo de automatización, encarnado sin caricatura.** **Prohibido** el retrato de la persona
crédula que obedece a la máquina. El mecanismo elegido es el más incómodo y el más creíble: **la
recomendación está bien escrita, viene con datos y coincide con lo que ella ya sospechaba.** Se
acepta fácil porque **se está de acuerdo**, y estar de acuerdo es exactamente cuando nadie
comprueba. **No se afirma que esto le pase a nadie en general**: le pasa a ella, en esa tarea.

**Y no puede salir ni acertando todo ni fallando de forma ridícula.** La recomendación tiene que
ser **defendible con la información que tenía** y aun así insuficiente, por algo que no podía
saber.

**Profesiones reguladas: no se usa ninguna** (D-033). Mantenimiento no lo es, y el mecanismo se
enseña sin necesidad de entrar ahí.

### 11. Arquitectura narrativa

**Once movimientos.** Doce era una opción y se descarta: «aceptar, modificar, rechazar o pedir
más información» **no es un movimiento aparte**, es el contenido del componente 6 del formato y
del desenlace del caso.

1. **La pregunta heredada del capítulo 13**, en la primera línea.
2. **Alerta y recomendación**, la diferencia en dos frases. **Sin reexplicar las alertas ni el
   modo sombra**, que se reciben hechos.
3. **La escena**: la recomendación que llega, bien escrita, y la tentación de aceptarla.
4. **Qué es una recomendación en este método**, y las tres cosas que no es.
5. **No todo aviso necesita recomendación**, y el nivel 4 como permiso por tarea.
6. **El sesgo de automatización**, con F-010 y F-043 y sus ámbitos dentro de la frase.
7. **Por qué explicar no basta**, que es el giro del capítulo.
8. **Evidencia y criterio**, el «por qué» partido en dos.
9. **La incertidumbre**, específica y sin números.
10. **El Formato de recomendación explicada**, con sus seis componentes y la decisión que no
    puede ser automática.
11. **Señal de paso y puente al 15.**

**El orden se aparta del de partida en un punto y por un motivo:** el sesgo de automatización va
**antes** de «por qué explicar no basta», no después, porque el segundo solo se entiende como
consecuencia del primero. Y la escena sube al tercer movimiento para que el lector tenga delante
una recomendación concreta antes de que el capítulo empiece a desconfiar de ella.

### 12. Señal de paso, falsable

Para **una** tarea, y **ninguna de las seis condiciones habla de acertar**:

- existe **permiso** para que esa tarea produzca recomendaciones;
- la **propuesta está separada de la decisión**, y se ve cuál es cuál;
- la recomendación **muestra su evidencia**, con dónde comprobarla;
- **dice qué criterio aplica**;
- **declara lo que no sabe**, en términos de esa propuesta;
- y **hay una decisión humana registrada**, que puede ser rechazarla o modificarla.

**No exige que la recomendación fuera buena, ni que el lector confíe, ni pasar al nivel 5.**
«La rechacé» cumple la señal.

### 13. Puente al capítulo 15

> *Si ya puede proponerme qué hacer y yo sigo decidiendo, ¿hay algo que pueda hacer por sí mismo
> sin volver a preguntarme cada vez?*

**El capítulo 14 no la contesta.**

### 14. Extensión y controles

**Objetivo 2.000 palabras**, con el margen de D-030. **El formato vive dentro y cuenta dentro.**

**Aviso de presupuesto, para decisión del autor.** La Parte III lleva **6.739 palabras en tres
capítulos** frente a un objetivo acumulado de 6.400, y los tres han salido por encima. Con los
objetivos vigentes de los capítulos 14, 15 y 16, la parte terminaría en torno a **13.000
palabras, el 24,5 % del manuscrito**, por debajo del techo del 26 %. **Si el patrón de desviación
se mantiene** —entre un 5 y un 9 % por capítulo—, rondaría el **25,5 %**: sigue dentro, pero sin
el margen de antes. **No se propone cambiar ningún objetivo**; se anota para que la decisión
exista antes y no después.

**Lo que el capítulo 14 tiene prohibido prometer**, y son siete: que las explicaciones reduzcan
el sesgo · que la supervisión humana garantice seguridad · que persona más sistema sea mejor ·
que la herramienta explique por qué piensa · que una recomendación explicada sea fiable · que
más evidencia produzca mejores decisiones · que la persona vaya a detectar el error.


---

## Preflight del capítulo 15 (Etapa 3.14A, 2026-09-09)

**No se ha escrito el capítulo 15, no se ha creado la herramienta 12 y no se ha ejecutado
ninguna investigación.** Y hay **un asunto que este preflight no puede cerrar solo**: está en el
apartado 4.

### 1. Qué cambia, y qué no

La pregunta que deja el capítulo 14: *si ya puede proponerme qué hacer y yo sigo decidiendo cada
vez, ¿hay algo que pueda hacer por sí mismo sin volver a preguntármelo?*

**El cambio no es que la herramienta empiece a decidir.** Es este:

> **Una persona autoriza por adelantado una clase de acciones dentro de límites escritos.**
> Después, la tecnología puede ejecutar **sin volver a preguntar en cada caso**, mientras el
> caso siga dentro de esos límites.

Y de ahí sale la frontera nueva del libro, que se suma a la del capítulo 12 sin sustituirla:

| Capítulo 12 | Capítulo 15 |
|---|---|
| **Que pueda hacerlo no contesta si debe permitírsele hacerlo** | **Que tenga permiso para una clase de casos no significa que lo tenga fuera de ella** |

### 2. Los cinco momentos, y por qué el título no se contradice

El título del capítulo es *Autonomía limitada y aprobación humana*, y hay una contradicción
aparente que conviene deshacer antes de escribir: **si una persona tuviera que aprobar cada
ejecución individual antes de que ocurra, el nivel 5 sería el nivel 4 con otro nombre.**

No lo es, porque «aprobación» aquí ocurre **una vez y sobre una regla**, no una vez por caso:

| | Momento | Quién |
|---|---|---|
| **1** | **Autorización previa del permiso.** Qué clase de tarea puede ejecutarse y con qué límites | Una persona, **antes** |
| **2** | **Ejecución.** Dentro de esos límites, sin nueva consulta | La tecnología |
| **3** | **Excepción.** El caso sale del límite: **se detiene** | La tecnología, y ahí acaba lo suyo |
| **4** | **Decisión sobre la excepción** | Una persona |
| **5** | **Revisión posterior** de lo ejecutado | Una persona |

**Y la convención de la herramienta 8 se conserva sin tocarla:** **aprobación** es autorizar
**antes**; **revisión** es comprobar **después**. Lo que el capítulo 15 añade es que **una
aprobación puede autorizar una regla y no un acto**. Es la misma palabra haciendo un trabajo
más grande, no una palabra nueva.

### 3. Nivel 5 y nivel 6

**Nivel 5 — Ejecución limitada.** Ejecuta solo tareas de bajo riesgo dentro de reglas escritas
y autorizadas antes. **Debe**: registrar lo que hace, detenerse ante una excepción, devolverla a
una persona y poder detenerse de inmediato. **No puede**, y la lista es cerrada: **ampliar sus
propios límites**, reinterpretar su permiso para obtener más permiso, **decidir qué excepción
deja de ser excepción**, ni concederse una categoría nueva de acción.

**Nivel 6 — Mano derecha digital supervisada.** Coordina tareas ordinarias, prepara decisiones,
da seguimiento, informa de excepciones, escala lo sensible y mantiene informado al propietario.
**Bajo supervisión humana.**

**La frontera 5/6 no es «cuánto puede hacer»: es sobre qué.** El nivel 5 **ejecuta acciones
sueltas** dentro de una regla; el nivel 6 **coordina un conjunto de tareas** y **prepara** lo que
decide una persona. Un sistema de nivel 6 no ejecuta más cosas: ejecuta lo mismo y además
**ordena el trabajo alrededor**.

**El nivel 6 es el techo** (D-008). **No existe un nivel 7**, y el capítulo no puede escribirse
como una escalera en la que subir sea mejor: **subir, mantener, bajar y retirar son las cuatro
salidas legítimas**, igual que en el modo sombra.

**El capítulo 15 presenta el nivel 6; no lo desarrolla.** No es autonomía absoluta, no sustituye
al propietario, no decide estrategia, no modifica sus permisos y no actúa fuera de lo
autorizado.

### 4. Auditoría de «bajo riesgo» — **RESUELTA POR EL AUTOR (D-077, Etapa 3.14A.1)**

**Este apartado se conserva porque explica el problema; lo que sigue describe la definición que ya NO rige.** El autor aprobó la corrección el 2026-09-09 y la adoptó **con una formulación más precisa que la propuesta aquí**: cinco condiciones en lugar de cuatro, añadiendo **datos personales e información confidencial** y **compromisos frente a terceros** como fronteras propias, y **la excepción incorporada a la propia definición**. La redacción vigente está en `editorial/08-niveles-de-autonomia.md` y en **D-077**. **La Etapa 3.14B ya no está bloqueada.**

**Redacción anterior, que queda sustituida:**

> *Criterio para clasificar una tarea como de bajo riesgo:* es reversible, su impacto económico
> está acotado por escrito, **no afecta a personas** y no compromete a la empresa frente a un
> tercero.

**Problema 1, y es el que obliga a detenerse: «no afecta a personas» no se puede usar
literalmente.** Casi cualquier acción de un negocio afecta a alguna persona de alguna manera:
reordenar unas revisiones cambia la semana de un técnico, clasificar una reclamación toca a un
cliente. **Leída al pie de la letra, la condición vacía el nivel 5**: no habría ninguna tarea que
la cumpliera. Leída con manga ancha, no filtra nada. **Las dos lecturas son malas**, y el
capítulo 15 no puede apoyarse en una condición que no se puede aplicar.

**Lo que el método parece querer excluir** —y esto es interpretación, no doctrina aprobada— no
es *afectar a alguien*, sino **producir un efecto material sobre**: derechos · seguridad ·
empleo, remuneración o condiciones de trabajo · obligaciones · relaciones contractuales · datos
personales.

**Problema 2: «impacto económico acotado por escrito» reduce el límite a dinero**, y eso choca
con lo que el capítulo 10 ya estableció y este archivo registró como constante: **el importe es
una forma de límite entre varias**. Un permiso puede acotarse por alcance, tipo de caso, plazo,
reversibilidad, terceros implicados o categoría de tarea, y en muchas tareas **no hay ninguna
cifra que poner**.

**Problema 3: «reversible» no está definido**, y es la palabra de la que cuelga todo lo demás.

**Redacción propuesta, para decisión:**

> *Criterio para clasificar una tarea como de bajo riesgo **en este método**:*
> **(a)** es **reversible** —existe una forma realista de deshacer su efecto principal sin
> causar un daño mayor—; **(b)** su alcance está **acotado por escrito**, por importe, tipo de
> caso, plazo, volumen o cualquier otro límite que sirva para esa tarea; **(c)** **no produce
> efectos materiales sobre derechos, seguridad, empleo, remuneración, obligaciones o datos
> personales de nadie**; y **(d)** no compromete al negocio frente a un tercero.

**Consecuencias si se adopta:** el nivel 5 pasa a tener un criterio **aplicable**; el capítulo 15
puede apoyarse en él sin contradecirse; se alinea con la constante del importe como una forma de
límite entre varias; y **no cambia ningún nivel, ninguna herramienta ni ninguna decisión
vigente**. **Consecuencia si no se adopta:** el capítulo 15 tendría que escribirse **evitando**
citar el criterio, lo cual es posible pero deja la escala con una condición inaplicable en su
escalón más delicado.

~~**No se ha registrado ninguna decisión y no se ha modificado `08-niveles-de-autonomia.md`.**~~
**Resuelto el 2026-09-09: D-077 registra la decisión, `08-niveles-de-autonomia.md` recoge la redacción vigente y V-69 queda cerrada.** La formulación aprobada por el autor es **más estricta que la propuesta** en dos puntos que este preflight no había visto: separa **datos personales y confidencialidad** como frontera propia —el nivel 5 no adquiere por sí mismo autoridad para decidir un uso, una divulgación o una finalidad nueva— y separa **los compromisos frente a terceros** en sus tres verbos: **no crea, no modifica y no cancela**.

### 5. Reversibilidad, límites, excepción y detención

**Reversible**, definición operativa propuesta para el método —y es **razonamiento propio**, no
de ninguna fuente—: **existe una forma realista de deshacer el efecto principal de la acción sin
crear un daño mayor.** Con dos cautelas que el capítulo debe decir: **no todo lo digital es
reversible**, y **poder borrar un registro no es lo mismo que deshacer lo que ese registro ya
provocó** —un aviso leído, una expectativa creada, una decisión que otro tomó a partir de él—.

**El límite no es necesariamente dinero.** Puede ser alcance, tipo de caso, información,
reversibilidad, terceros, plazo, consecuencia o categoría de tarea. **Cero umbrales
inventados**: los pone el negocio.

**Excepción**, y aquí está una de las dos frases fuertes del capítulo: **una excepción no
concede autonomía; la retira.** Fuera del límite se pausa, y la decisión vuelve a una persona.
**El sistema no decide que una excepción es lo bastante pequeña como para seguir.** Enlaza con
el capítulo 8 **sin reexplicarlo**.

**Detener tiene tres alcances**, y confundirlos es lo que hace que nadie detenga nada:

| | |
|---|---|
| **Detener una acción** | Esta, la que está en curso |
| **Detener una tarea automatizada** | Ese permiso deja de ejercerse; los demás siguen |
| **Desconectar el sistema** | Todo se para |

**No toda excepción exige apagarlo todo**, y esa es exactamente la razón de distinguirlos: si la
única forma de parar es apagar, nadie para. **F-010** habla, **en su ámbito**, de un botón de
parada **o procedimiento equivalente**; el método conserva **la función y no el producto**: cero
interfaz, cero botón físico universal.

### 6. Evidencia: qué basta y qué no

**Q-17 basta. Cero investigación nueva y cero fuentes nuevas.**

| Fuente | Qué sostiene para el capítulo 15 | Qué NO sostiene |
|---|---|---|
| **F-007** | Que los procesos de supervisión se **definan, evalúen y documenten** (MAP 3.5); que existan **mecanismos y responsables asignados para anular, desconectar o desactivar** (MANAGE 2.4); que los roles persona-sistema estén **definidos y diferenciados** (GOVERN 3.2); **monitorización posterior al despliegue** con anulación y retirada (MANAGE 4.1); y que **la frecuencia de la revisión periódica la determina la organización** (GOVERN 1.5) | **Ningún criterio de bajo riesgo**, ningún umbral, ninguna cadencia. Y **el hallazgo negativo del apéndice C sigue vigente**: persona más sistema **puede dar peor resultado**. **Prohibido** presentar la supervisión como garantía |
| **F-009** | Mecanismos y salvaguardas, **capacidad de intervención y supervisión humanas**, responsabilidad y trazabilidad. **Uso previsto: una sola mención, o ninguna** | Es **no vinculante**, y no añade nada que F-007 no diga con más precisión. **Se cita solo si el capítulo necesita una segunda voz para la trazabilidad** |
| **F-010** | Que la supervisión exija poder **no usar, ignorar, anular, revertir e interrumpir**, y el **botón de parada o procedimiento equivalente** | **Solo Unión Europea y solo alto riesgo.** **D-020: coincidencia no es cumplimiento.** El método toma **las condiciones como buen diseño**, no como deber del lector |

**F-043** pertenece al capítulo 14 y **no se reincorpora**. **F-044** —lo difícil que es juzgar el
propio metaconocimiento— **sí tiene aquí su segundo capítulo registrado**, y **se evalúa**: podría
sostener por qué conviene escribir el límite antes y no en caliente. **Pero eso ya lo dijo el
capítulo 12 con esa misma fuente**, y repetirlo sería citar dos veces lo mismo. **Decisión:
disponible, y solo si el capítulo la necesita para algo que no sea repetir.**

**Q-20 — «qué reservan las normas profesionales al juicio de una persona con licencia»: NO se
ejecuta, y sigue diferida.** La pregunta previa del encargo se contesta que no: **el capítulo 15
no necesita hacer ninguna afirmación sobre ninguna profesión regulada.** La arquitectura
—autorizar una clase, ejecutar dentro del límite, detenerse en la excepción— se enseña entera sin
entrar ahí, y **D-033 sigue gobernando**: cuando el asunto aparezca, se remite a la jurisdicción
y al profesional competente. **El caso C-12 no será de una actividad regulada.**

**Y una cautela que el capítulo debe respetar:** el criterio de bajo riesgo es **diseño del
Método LEGADO**. **Prohibido** escribir «los marcos internacionales consideran de bajo riesgo…»
o atribuirlo a NIST, la OCDE, el reglamento europeo o ISO. Se dice **«para este método»**.

**Human-in-the-loop no se usa como garantía.** El capítulo habla de funciones concretas: quién
autoriza, quién puede detener, quién recibe la excepción, quién revisa y qué queda registrado.
**Una persona formalmente presente no es una supervisión efectiva** (V-65, abierta).

### 7. Herramienta 12 — Matriz de niveles de autonomía

**No se crea en esta etapa.** Archivo futuro: `recursos/matriz-niveles-autonomia.md`.
**Herramienta 12 de 18.** Al terminar este preflight, **los recursos siguen en 11 de 18**.

**Qué la distingue de la herramienta 8, en una línea que el propio capítulo usará:**

> **La matriz de autoridad dice quién puede decidir qué. Esta dice cuánto puede hacer la
> tecnología sin volver a preguntar.**

La 8 gobierna **autoridad humana**; la 12 gobierna **autonomía de la tecnología, por tipo de
tarea**. Se relacionan —el permiso de la 12 no puede exceder lo que la 8 permite a quien lo
autoriza— pero **no se rellenan dos veces los mismos campos**, y la 12 **remite** a la 8 en lugar
de repetirla.

**Qué decisión produce la matriz**, antes que ninguna columna: **para cada tipo de tarea, cuál es
el nivel de autonomía que hoy tiene autorizado.**

**Ocho campos.** Se llega a ocho desde los once del encargo, y **la fusión más importante es la
primera**:

| | Campo | Por qué existe |
|---|---|---|
| **1** | **La tarea** | Una, concreta. **El nivel es de la tarea, no del negocio** |
| **2** | **Nivel autorizado hoy** | **Una sola columna, no dos.** Ver abajo |
| **3** | **Qué puede hacer sin volver a preguntar** | El permiso en positivo. Si no se puede escribir, no está autorizado |
| **4** | **Dentro de qué límites** | Alcance, tipo de caso, plazo, volumen, importe… **lo que sirva para esa tarea** |
| **5** | **Qué obliga a detenerse, y a quién vuelve** | La excepción **y su destinatario**, juntos: una excepción sin destinatario es solo una parada |
| **6** | **Cómo se detiene la automatización** | Los tres alcances. **Escrito antes de necesitarlo** |
| **7** | **Qué queda registrado, y quién puede mirarlo** | Lo mínimo para saber qué se ejecutó, bajo qué permiso y qué pasó con las excepciones |
| **8** | **Cuándo se revisa este permiso** | **Fecha o condición.** Un permiso no es eterno |

**Por qué una sola columna de nivel y no dos.** El encargo planteaba «nivel actual» y «nivel
máximo permitido», y **escribir un máximo superior al actual convierte la matriz en una hoja de
objetivos**: el número de al lado se lee como la meta. La alternativa —**«nivel autorizado hoy»**
más el campo 8— dice exactamente lo mismo sin sugerir dirección: **este es el permiso, y así se
revisa.** Coherente con D-040 y con las cuatro salidas del modo sombra.

**Ningún nivel se gana automáticamente.** No hay fórmula, no hay número de casillas, no hay
puntuación. **La matriz no otorga permisos: los registra.** Los concede una persona, y la
evidencia puede justificar subir, mantener, bajar o retirar.

**Revisión sin cadencia inventada.** El campo 8 admite **una fecha o una condición** —«cuando
cambie el procedimiento», «cuando entre un tipo de caso nuevo»—. **F-007 (GOVERN 1.5) deja la
frecuencia en manos de la organización**, y el método no inventa ninguna.

**Ruta A:** puede haber una persona que autoriza, otra que opera y otra que revisa, **pero la
herramienta no exige tres**: usa las funciones que existan, y **no se inventan cargos** (D-073).
**Ruta B:** la misma persona define el permiso, recibe la excepción y revisa después. **No se
finge separación de funciones** y **no existe la «autoaprobación»**: el campo 5 dice a quién
vuelve la excepción, y en ruta B la respuesta es «a mí», escrita tal cual. Lo que protege ahí no
es la separación —no la hay— sino que **el límite estuviera escrito antes**, la pausa exista y
haya registro.

**Dos páginas** para lo que se imprime y rellena, papel, lenguaje no técnico, ejemplo ficticio,
responsable, frecuencia y salida operativa, como exige el catálogo.

### 8. El caso C-12

**No se escribe en esta etapa.**

| | |
|---|---|
| **Nombre** | **Ismael** (solo nombre de pila) |
| **Género** | **Hombre**, por la alternancia caso a caso: el reparto está en 6 mujeres y 5 hombres |
| **Ruta** | **B.** El reparto está en 6 A y 5 B, y el 14 fue ruta A |
| **Sector** | **Importación y distribución** |
| **Riesgo** | **Bajo**, con las medidas de siempre |

**Por qué importación y distribución, después de haberlo evitado dos veces.** Se apartó en los
capítulos 12 y 14 **por una razón que aquí no aplica**: en los dos casos el protagonista iba a
ser **mujer y de ruta A**, exactamente el perfil del ejemplo de la herramienta 9. **C-12 es
hombre y de ruta B**, opuesto en los dos ejes, y el ejemplo de la herramienta 9 queda ya a cuatro
capítulos. El sector tiene **cero apariciones de caso** y ha perdido dos de sus tres turnos: usarlo
ahora lo deja en **1 de 3**, conservando el capítulo 17.

**Por qué no manufactura ligera, que era el sector previsto.** Porque **el ejemplo de la
herramienta 10 es manufactura ligera** y está **dos capítulos atrás**, que es la distancia más
corta de todo el libro. El sector conserva sus capítulos 2 y 15… y pierde el 15; le queda el
turno del capítulo 2 ya usado y **una aparición disponible**.

**La tarea, y cumple las cinco condiciones del encargo.** Ismael importa y distribuye por su
cuenta. Cada envío genera **varios documentos que llegan por separado y en momentos distintos**,
y hasta ahora los clasificaba y archivaba él, de noche. Autoriza una clase de acción: **clasificar
y archivar los documentos que llegan, asociándolos al envío que les corresponde, y registrar que
llegaron.**

- **(A)** se ejecuta muchas veces dentro del límite;
- **(B)** no necesita preguntar en cada documento;
- **(C)** la excepción es realista: **llega un documento corregido de un envío que ya estaba
  cerrado**. **Corregido el 2026-09-09 (Etapa 3.14A.1):** el borrador decía «una factura
  corregida», y eso metía en el capítulo contabilidad, fiscalidad y modificación de registros
  financieros **que el mecanismo no necesita**. La tarea sigue siendo clasificar y archivar **los
  documentos corrientes de cada envío**;
- **(D)** el sistema **se detiene**;
- **(E)** y le devuelve la decisión: reabrir el registro es cosa suya.

**Es interna, reversible y acotada**, y **no es trivial**: le ahorra el trabajo de todas las
noches. **Y el error se puede parar antes de tener consecuencias**, que es lo que la hace apta
para enseñar. **Nada de** transferencias, pagos, contratación, contratos, decisiones
regulatorias, salud, seguridad física ni acciones irreversibles.

**El segundo hallazgo del caso, que es el que enseña:** el sistema **no decidió** que el documento
corregido era un cambio menor y podía archivarse igual. **Se detuvo porque estaba fuera del
límite**, y eso es lo contrario de lo que el lector teme.

**Tres rasgos**, no más: (1) importa y distribuye por su cuenta, sin empleados; (2) cada envío
genera varios documentos que llegan por separado; (3) archivaba todo él, de noche.

### 9. Arquitectura narrativa

**Once movimientos.** Doce se descarta: «qué es un límite operativo» y «qué es una excepción» son
**las dos caras de lo mismo** y se leen mejor juntas —el límite se entiende cuando se ve qué pasa
al cruzarlo—.

1. **La pregunta heredada del capítulo 14**, en la primera línea.
2. **Autorizar una regla no es aprobar cada ejecución**, y por qué el título no se contradice.
3. **La escena**: Ismael, los documentos y la noche.
4. **Qué es la ejecución limitada**, con los cinco momentos.
5. **El límite y la excepción**, juntos. **Una excepción no concede autonomía: la retira.**
6. **Cómo se detiene**, con los tres alcances.
7. **Qué queda registrado**, y hasta dónde llega este capítulo.
8. **El nivel 5 entero**, con lo que no puede hacer.
9. **El nivel 6 como techo**, y por qué no hay un 7.
10. **La Matriz de niveles de autonomía**, y su frontera con la herramienta 8.
11. **Señal de paso y puente al 16.**

**El orden se aparta del encargo en un punto:** el nivel 5 **no abre** el capítulo, lo cierra.
Primero se ve funcionando —permiso, límite, excepción, parada— y solo entonces se le pone
nombre. Poner el nombre delante convertiría el capítulo en una explicación de la escala.

### 10. Señal de paso, falsable

Para **una** tarea, y **ninguna de las nueve condiciones dice nada sobre acertar**:

hay un **permiso escrito** · hay un **nivel autorizado** · se sabe **qué puede ejecutar** · hay
**al menos un límite** · hay una **condición que obliga a detenerse** · está claro **quién recibe
la excepción** · existe **una forma de detener la automatización** · **queda registro** de lo
ejecutado · y **alguien puede revisarlo**.

**No exige resultado favorable.** **«Lo bajé de nivel» cumple el método**, y «lo retiré» también.

### 11. Puente al capítulo 16

> *Si ya puede hacer algunas cosas sin preguntarme cada vez, ¿quién puede ver todo esto, qué
> queda registrado, dónde están los datos y qué pasa cuando algo falla?*

**El capítulo 15 no la contesta.** Puede exigir registro, capacidad de detener, responsable y
límites; **no desarrolla** arquitectura de seguridad, control de acceso, almacenamiento,
retención, ciberseguridad, auditoría técnica ni tratamiento profundo de datos personales.

### 12. Decisiones de vocabulario

**«Mano derecha digital»: se usa**, es el nombre del nivel 6 y del título de la parte. **Se
define por función** —coordina, sigue, informa, escala, prepara— y **nunca** como persona
digital, clon, doble del fundador ni réplica de nadie.

**Gemelo de IA: NO se usa.** V-25b abre la ventana en el capítulo 15, y **abrir la ventana no
obliga a entrar**. La doctrina de la autonomía limitada funciona entera sin él, e introducirlo
traería un concepto de producto que el capítulo no necesita. **Queda disponible para el 16 o
posterior**, y su ausencia aquí es **una elección registrada**, no un olvido.

**ADN Empresarial: como mucho una frase**, y solo si hace falta. Si aparece, sería para decir que
lo que el nivel 5 ejecuta actúa sobre **conocimiento, criterios, reglas, procesos y permisos ya
organizados** —el trabajo de las Partes II y III—. **Prohibido** «la IA ya conoce el ADN del
negocio», y prohibido adelantar arquitectura de producto.

### 13. Extensión y presupuesto

**Objetivo 2.200 palabras**, preferencia **2.100–2.300**, sin rellenar. La herramienta 12 **no
cuenta** en el manuscrito.

La Parte III lleva **8.719 palabras en cuatro capítulos**. Con el 15 en 2.200 y el 16 en 2.100,
terminaría en **13.019 palabras, el 24,4 % del manuscrito**, por debajo del techo del 26 %. **Hay
margen, y no es motivo para cortar una distinción necesaria**; tampoco para repetir lo ya dicho.

### 14. Lo que el capítulo 15 tiene prohibido prometer

Nueve, y conviene tenerlas a la vista al escribir: que **el nivel 5 es seguro** · que **la
supervisión humana evita errores** · que **si es reversible no tiene riesgo** · que **un humano
siempre puede corregirlo** · que **la herramienta sabe cuándo detenerse** · que **más autonomía
es mejor** · que **el nivel 6 reemplaza al propietario** · que **la mano derecha digital decide
por usted** · y que **cumplir la matriz autoriza a automatizar**.


---

## Preflight del capítulo 16 (Etapa 3.15A, 2026-09-09)

**No se ha escrito el capítulo 16 y no se ha creado la lista de comprobación.** El capítulo
**cierra la Parte III** y la etapa A del método.

### 1. Qué enseña este capítulo, y qué no

Recoge la pregunta con la que terminó el 15: *si ya hace algunas cosas sin preguntarme, ¿quién
puede ver todo esto, qué queda registrado, dónde están los datos y qué pasa cuando algo falla?*

**Idea rectora, y es de gobierno y no de miedo:**

> **Automatizar una tarea también crea una responsabilidad de gobierno.** No una nueva
> tecnología que aprender: **cuatro preguntas que contestar antes de dejarla seguir.**

**Lo que NO va a enseñar**, y conviene fijarlo antes de escribir: no es un tratado técnico, ni un
manual jurídico, ni un manual de ciberseguridad, ni una política de cumplimiento. **No enseña a
configurar nada.** Y **no reexplica** la clasificación de la información (capítulo 11), capacidad
frente a permiso (12), el modo sombra (13), el sesgo de automatización (14) ni la escala de
niveles (15). **Añade cuatro cosas: acceso, registro, protección y recuperación.**

### 2. Las cuatro palabras que no son la misma

En lenguaje llano y solo hasta donde el capítulo las necesita. **Son definiciones de trabajo de
este libro**, no definiciones profesionales:

| | Contesta a |
|---|---|
| **Seguridad** | Que solo pueda ver y hacer lo previsto **quien deba**, y que se pueda volver a funcionar si algo se rompe |
| **Privacidad** | Qué puede hacerse con la información **de personas**. Depende de la jurisdicción, y el capítulo lo dice cada vez |
| **Confidencialidad** | Lo que se debe **a otro** por un contrato, una relación o un secreto del negocio |
| **Auditoría** | **Poder reconstruir qué ocurrió y comprobar si se actuó dentro del permiso** |

**Y una quinta que no es ninguna de las cuatro: continuidad.** Que el negocio **siga funcionando
mientras se resuelve el problema**. Se separa a propósito, porque es lo que queda en pie cuando
las otras cuatro han fallado.

**Auditoría, con su acotación explícita.** Aquí **no** significa auditoría contable, ni legal, ni
profesional, ni certificación de cumplimiento. **Es un uso del término en este libro**, y así se
declara la primera vez.

### 3. Las cuatro preguntas, y qué contesta cada una

**A. ¿Quién puede ver qué?** La distinción que el capítulo aporta: **autoridad no es acceso.**
Una persona puede tener autoridad sobre una decisión **sin necesitar ver toda la información del
negocio**, y una herramienta con permiso para una tarea **no necesita acceso a todo lo demás**.
Con dos apoyos de **F-046**: **cada quien accede solo a lo que necesita para su trabajo**, y
**cada persona entra con su propia cuenta** —porque sin cuentas individuales «you may find it
difficult to investigate data loss or unauthorized data manipulation»—. **Las credenciales** son
la tercera categoría del capítulo 11 y aquí solo se pregunta **dónde están y quién las conoce**.

**B. ¿Qué queda registrado?** Se hereda del capítulo 15 —qué se ejecutó, bajo qué permiso,
cuándo, si hubo excepción y qué se decidió— y se añade **para qué sirve**: para poder
reconstruir. **F-046** lo dice de la forma más útil: los registros «may be valuable **in case of
an investigation**». **Prohibido convertir «auditoría» en «registrarlo todo»**: un registro que
nadie puede leer no es trazabilidad, es volumen.

**C. ¿Dónde están los datos?** La pregunta operativa del capítulo **no es de quién son**, y esa
elección se explica en el apartado 5. Es: **¿qué hay solo en la cuenta de un proveedor, y qué
pasaría si mañana no pudiera entrar?** Con la frase que el capítulo necesita y que **F-040**
—Unión Europea y EEE, y así se dice— permite sostener en su ámbito: quien contrata a un
proveedor **debe comprobar antes que ofrece garantías suficientes y poder demostrar que lo
comprobó**. De ahí el principio del método, formulado sin exceder la fuente: **contratar a un
proveedor no traslada automáticamente la responsabilidad del negocio sobre lo que necesita
proteger.**

**D. ¿Qué pasa si algo falla?** Cinco clases de falla, comprimidas en el texto y no convertidas
en secciones: **la herramienta**, **el acceso**, **el proveedor**, **el dato** y **el uso no
autorizado**. La pregunta que las une es de continuidad: **¿qué necesita el negocio para seguir
funcionando mientras se resuelve?** Con **F-046** para las copias —**guardadas fuera** del sitio
donde ocurre el trabajo— y la regla propia que la fuente no da: **una copia que nadie ha
restaurado nunca es una suposición, no una copia.**

### 4. Jurisdicción, y lo que el capítulo tiene prohibido decir

**D-014 y `12-alcance-jurisdiccional.md` son obligatorios aquí más que en ningún otro capítulo.**
Y hay una herencia que ayuda: **Q-05 y Q-18 ya establecieron que no existe una regla única de
privacidad aplicable a todos los lectores** (V-63, abierta). El capítulo **no la busca**: usa
**preguntas de control** y **remite**.

**Prohibido**: «la ley exige» sin ámbito · «debe conservar durante X años» · «usted es
propietario de todo lo producido» · «el proveedor debe devolverle sus datos» · y cualquier
recomendación de F-046 presentada como obligación universal.

**Y las ocho promesas que el capítulo no hace**, para tenerlas delante al escribir: que su
negocio estará **seguro** · que **evitará filtraciones** · que **cumplirá la regulación** · que
su información **está protegida** · que una copia **garantiza** recuperación · que un registro
**garantiza** auditoría · que **el proveedor es el responsable** · que **la herramienta detectará
el incidente**.

### 5. Qué investigación se ejecutó y cuál no

**Solo Q-07, y tras una prueba de necesidad.** Las otras tres se difieren con motivo escrito:

| | Estado | Por qué |
|---|---|---|
| **Q-07** | **EJECUTADA. Parcialmente necesaria** | El entregable se llama *lista de comprobación de seguridad básica* y **ninguna de las 45 fuentes anteriores decía nada sobre seguridad**. Escribirla sin ninguna referencia habría sido inventarla. **Una sola fuente nueva: F-046** |
| **Q-15** | **NO NECESARIA. Diferida** | El capítulo **no necesita afirmar externamente** que la dependencia de una persona sea un riesgo reconocido. El libro lo construyó por mecanismo en las Partes I a III |
| **Q-19** | **NO NECESARIA. Diferida** | Lo que el capítulo dice es **«compruebe si puede sacar de ahí lo que necesita»**, que es pregunta de control y regla de prudencia. **No dirá de quién es lo que el proveedor guarda**, y para eso sí haría falta Q-19 |
| **Q-20** | **NO NECESARIA. Diferida por segunda vez** | **D-033** ya autoriza la frase necesaria: un permiso tecnológico no sustituye la responsabilidad de una persona habilitada. Se remite, no se cita |

**Lo que se reutiliza sin volver a investigar:** **Q-03** —F-011, análisis de impacto y
estrategias de recuperación—; **Q-04** —F-007, mecanismos y responsables asignados para anular o
desconectar—; **Q-05 y Q-18** —F-038, F-040 y F-042, con el hallazgo negativo intacto—.

**Aviso de fuentes que NO se citarán, y hay que registrarlo:** **F-005 (ISO 22301)** y **F-006
(ISO 31000)** están verificadas **solo en identidad**, porque son normas de pago. **El capítulo 16
no las cita**, y por tanto **V-16 —advertir de que son de pago al citarlas— no se activa en este
capítulo**; queda viva para el capítulo 4.

### 6. La Lista de comprobación de seguridad básica

**Es un entregable del capítulo (D-078).** **No es la herramienta 13, no es la herramienta 19, no
crea archivo en `recursos/` y el catálogo sigue en 18.** Vive dentro del capítulo y **cuenta
dentro de sus palabras**.

**Ocho preguntas, dos por cada una de las cuatro.** Se llegó a ocho desde las doce dimensiones de
partida aplicando dos filtros: **si la respuesta «no sé» no le dice al lector qué riesgo
investigar, la pregunta sobra**; y **si contestarla exige ser especialista, la pregunta sobra**.
Cayeron por eso las dimensiones de cifrado, de detección y de portabilidad como asunto jurídico;
**portabilidad sobrevive convertida en la pregunta 5**, que es operativa.

| | Pregunta | Qué revela un «no sé» |
|---|---|---|
| **1** | ¿Cada persona que entra a algo lo hace **con su propia cuenta**? | Que no se podrá saber quién hizo qué |
| **2** | ¿Alguien —o algo— tiene acceso a **más de lo que necesita** para su trabajo? | Que el acceso se concedió por comodidad y no por necesidad |
| **3** | ¿Dónde están las **credenciales**, y quién las conoce? | Que la salida de una persona puede dejar puertas abiertas |
| **4** | Si mañana hubiera que reconstruir **qué se hizo, quién lo autorizó y qué pasó con una excepción**, ¿se podría? | Que hay permisos concedidos sin forma de comprobarlos |
| **5** | ¿Qué existe **solo** en la cuenta de un proveedor, y qué pasaría si mañana no pudiera entrar? | Una dependencia que nadie eligió |
| **6** | ¿Hay **una copia fuera de ahí**, y alguien ha comprobado que se restaura? | Que hay copia y no hay recuperación |
| **7** | Si algo falla, ¿**quién se entera, quién puede detenerlo** y a quién se avisa? | Que el mecanismo de parada del capítulo 15 no tiene dueño |
| **8** | ¿Qué necesita el negocio para **seguir funcionando mientras se resuelve**? | Que no hay plan B para lo que ya depende de esto |

**Cinco respuestas por pregunta**, y la última es la que la convierte en instrumento: **sí · no ·
no lo sé · no aplica · y qué voy a hacer.**

**«No lo sé» es la respuesta más útil de la hoja** y así se dirá: es la única que señala dónde
mirar. **«No aplica» se escribe con su motivo**, como en la herramienta 12.

**Ruta A y ruta B, sin dos versiones.** Con equipo pueden existir personas distintas para
autorizar accesos, administrar sistemas, recibir incidentes y revisar registros; **la hoja no
exige que existan** y **no inventa un departamento de sistemas**. Trabajando solo, las cuatro son
la misma persona, y las preguntas 1, 2 y 3 **no se vuelven triviales**: cambian de sentido —de
quién más entra, a qué queda abierto cuando yo no estoy—.

**La remisión a profesionales va después de la lista, no en lugar de ella.** El capítulo debe
dejar al lector **sabiendo qué preguntar**; remitir sin enseñar los controles básicos sería usar
al profesional como excusa.

### 7. El caso: NO se crea C-13

**Y la decisión es deliberada.** El capítulo tiene que meter cuatro definiciones, cuatro
preguntas, ocho comprobaciones y un cierre de parte en 2.100 palabras: **un caso completo lo
rompería**. Además, **Ismael no puede continuar** —la regla prohíbe historia continuada entre
capítulos— y presentar a un duodécimo protagonista en el capítulo de cierre le quitaría al
capítulo lo que necesita, que es **volver sobre lo que el lector ya construyó**.

**Precedente exacto: el capítulo 5**, que quedó registrado «sin caso, por decisión» y funcionó
con dos microescenas sin nombre, una por ruta.

**Dos microescenas sin nombre, por debajo de las 120 palabras de la guarda de D-030**, y ninguna
es catastrófica: **prohibidos** los hackers de película, el rescate, la filtración masiva y la
catástrofe. **Son dependencias invisibles que aparecen un martes cualquiera:**

- **Ruta A:** alguien deja el negocio y, semanas después, se descubre que la tarea automatizada
  seguía funcionando **con su cuenta**.
- **Ruta B:** hace falta recuperar algo de hace unos meses y **está solo en la cuenta de un
  proveedor** a la que se entra con un correo que ya no se usa.

**Ninguna de las dos es un desastre.** Las dos son el mismo hallazgo: **una dependencia que nadie
decidió tener.**

### 8. Arquitectura narrativa

**Diez movimientos.**

1. **La pregunta heredada del capítulo 15**, en la primera línea.
2. **La primera microescena** y la idea rectora: automatizar crea una responsabilidad de
   gobierno.
3. **Las cuatro palabras que no son la misma**, más continuidad como quinta.
4. **¿Quién puede ver qué?** — autoridad no es acceso.
5. **¿Qué queda registrado?** — auditar es poder reconstruir, no registrarlo todo.
6. **¿Dónde están los datos?** — la segunda microescena, y la responsabilidad que no se traslada.
7. **¿Qué pasa si algo falla?** — las cinco clases, y la continuidad.
8. **La lista de comprobación**, con sus ocho preguntas.
9. **Qué preguntar a un profesional**, y las ocho promesas que este libro no hace.
10. **Cierre de la Parte III y puente a la Parte IV.**

**Por qué la segunda escena va en el movimiento 6 y no al final:** porque la dependencia de un
proveedor es la más difícil de ver de las cuatro preguntas, y **abstraerla no funciona**.

### 9. Cómo cierra la Parte III, y qué abre

El capítulo debe dejar al lector con una frase que resuma seis capítulos: **la tecnología ya
puede ayudarle sin que usted haya entregado el control.**

Y entonces **cambia el sujeto**, que es lo que abre la Parte IV: de un sistema supervisado a
**personas que tienen que saber funcionar sin usted**.

> *Ya tengo la información ordenada, el criterio escrito, los permisos, los límites y los
> controles. ¿Y qué pasa cuando quienes tienen que trabajar con todo esto son otras personas?*

**El capítulo 16 no la contesta.** No se escribe el capítulo 17.

### 10. Extensión, clasificación de afirmaciones y controles

**Objetivo 2.100 palabras**, y la arquitectura se diseñó para caber: diez movimientos de entre 90
y 380 palabras, con la lista ocupando el bloque mayor. **El entregable cuenta dentro.**

**Clasificación de lo que el capítulo va a afirmar:**

| Clase | Qué entra |
|---|---|
| **A. Doctrina del método** | Autoridad ≠ acceso · auditar es poder reconstruir · una copia no restaurada es una suposición · contratar un proveedor no traslada la responsabilidad · continuidad como quinta palabra |
| **B. Instrucción práctica** | Las ocho preguntas de la lista y sus cinco respuestas |
| **C. Afirmación factual externa** | **Solo cuatro, todas de F-046**, y cada una con su fecha y su ámbito dentro de la frase |
| **D. Afirmación jurídica** | **Ninguna.** Lo que toca ley se convierte en pregunta de control y remisión |
| **E. Afirmación contractual** | **Una, de F-040 y en su ámbito**: comprobar antes las garantías del proveedor y poder demostrarlo |
| **F. Ciberseguridad** | Las mismas cuatro de F-046. **Cero configuración, cero producto, cero interfaz** |

**Control de obsolescencia**, que en este capítulo es el riesgo mayor: **funciones, no
productos**. «Una forma adicional de comprobar quién entra» y no el nombre del mecanismo; «poder
exportar» y no un botón; «un sitio distinto» y no un servicio. **Cero marcas, cero nube concreta,
cero comparación de proveedores.**

**Verificaciones que afectan al capítulo 16:** **V-52** —revisión técnica de los capítulos 11 a
16 por un profesional de seguridad, en la Etapa 4—; **V-63**, que sostiene el uso de preguntas de
control en lugar de una regla universal; **V-65**, que impide presentar cualquiera de estos
controles como supervisión efectiva demostrada; y **V-16**, que **no se activa** porque el
capítulo no cita las normas ISO. **Ninguna necesita decisión del autor.**

**Decisiones nuevas propuestas: ninguna.** Todo lo que el capítulo necesita está resuelto por
D-014, D-020, D-033, D-078 y las constantes vigentes.

**`producto/` no necesita cambios.** Las ocho preguntas podrían existir mañana como revisión
periódica dentro de la plataforma **sin diseñar nada hoy**, y la arquitectura de producto ya
contempla aislamiento por negocio, permisos y trazabilidad. **No se diseña, no se programa, no se
elige proveedor.**


---

## Preflight del capítulo 17 (Etapa 3.16A, 2026-09-10)

**Abre la Parte IV y la etapa D del método.** Es el primer capítulo del libro cuyo sujeto no es
el negocio del lector sino **la relación entre el lector y otras personas**, y esa es la
dificultad que lo gobierna entero.

### 1. Cómo recibe al capítulo 16, y un problema en la propia pregunta heredada

El capítulo 16 cierra con esta pregunta, y el 17 la recibe en su primera línea sin volver antes
sobre tecnología:

> *¿Qué ocurre cuando quienes tienen que trabajar con todo esto son otras personas?*

**Y hay que decir de entrada que esa pregunta, tal como está, supone algo que no siempre existe:
otras personas.** Es correcta para la ruta A y puede ser falsa para la ruta B. **El capítulo 17
no puede empezar excluyendo a la mitad de sus lectores**, de modo que su primer movimiento tiene
que hacer dos cosas a la vez: recoger la pregunta **y ensancharla** —«otras personas» puede ser
un equipo, puede ser una sola persona, puede ser un cliente, y puede no ser nadie todavía—.

**Cuando no hay nadie**, la respuesta honesta no es inventar una conversación: es que el trabajo
recae sobre **procedimientos**, que es uno de los tres destinatarios legítimos de la etapa D
(**D-026**) y materia del capítulo 18. El 17 lo dice en una frase y no lo desarrolla.

**El sujeto cambia, y conviene que el cambio se note.** Hasta aquí el lector ha trabajado sobre
su negocio y sobre su propia dependencia. Ahora trabaja sobre **cómo va a ser leído por otro**.
**Prohibido** abrir el capítulo hablando de herramientas, de permisos técnicos o de cualquier
material de la Parte III.

### 2. «Transferir el control sin perderlo»: definición operativa

Es el título de la Parte IV y hay que definirlo antes de usarlo, porque leído deprisa promete lo
contrario de lo que el método sostiene.

**No significa** conservar el control de cada acción. Si eso fuera, no habría transferencia.

**Significa** poder transferir la ejecución, o parte de la decisión, **sin perder cuatro cosas**:

| | Qué es | Dónde se construye |
|---|---|---|
| **Visibilidad** | Poder ver lo que está ocurriendo sin tener que estar dentro | **Capítulo 19** |
| **Límites** | Que esté escrito hasta dónde llega lo transferido | **Capítulos 10 y 18** |
| **Capacidad de revisión** | Poder comprobar después, sin aprobar antes (**D-072**) | **Capítulo 18** |
| **Criterios de intervención** | Saber cuándo se entra y cuándo no | **Capítulo 20** |

**Las cuatro son arquitectura del Método LEGADO y no una definición universal**, y así deben
declararse. **El capítulo 17 las nombra y no construye ninguna**: su trabajo es anterior. La
tabla cabe en un bloque corto y sirve de mapa de la parte; **prohibido convertirla en una sección
larga**, porque cada fila tiene su capítulo.

### 3. Propiedad, dirección y ejecución — y por qué no se crea vocabulario nuevo

**Aquí estaba el riesgo estructural de este capítulo, y conviene dejarlo resuelto por escrito.**

El libro ya tiene un vocabulario vigente y obligatorio para repartir el trabajo de decidir:
**autoridad, ejecución y control** (**D-072**), más la distinción entre **aprobación** —antes— y
**revisión** —después—; y **D-074** separó al **ejecutor** —quien realiza la acción autorizada—
del **soporte de la ejecución**: un procedimiento, una plantilla, una lista o una regla **apoyan
a quien ejecuta y no ejecutan**.

**Y hay que citar D-074 con su alcance, no recortada** *(corregido el 2026-09-10, Etapa
3.16A.1)*. D-074 dice «ejecutor: quien realiza la acción autorizada; **hoy, en este libro**,
siempre una persona», y **reserva expresamente** el caso de **un sistema supervisado que sí
realiza acciones** a la etapa A y a los capítulos 12 a 15. **Esos capítulos ya están escritos.**
De modo que **la Parte IV no puede convertir esa frase en una afirmación universal**: borraría la
autonomía limitada que el libro acaba de construir y contradiría la tercera modalidad de
**D-026**. **Lo que sí es universal, y no se toca:** la **autoridad** se asigna a una persona,
una función o un órgano real (**D-073**), y **un sistema no adquiere autoridad porque pueda
realizar una acción**.

**Si el capítulo 17 introdujera «dirección» como un cuarto término en paralelo, crearía una
segunda taxonomía para lo mismo.** No se hace. **Se fija así, y no es doctrina nueva: es
aplicación de D-072:**

| | Qué es aquí | Estado en el libro |
|---|---|---|
| **Propiedad** | Quién posee participación o derechos sobre el negocio, según corresponda | **Fuera del método.** Depende de estructura jurídica, contrato y país. **El libro no la define y no la reparte** |
| **Dirección** | **No es un término nuevo:** es la **mirada agregada** de la autoridad que ya se repartió decisión por decisión en el capítulo 10 y en la herramienta 8. Quién toma o coordina un conjunto de decisiones de gestión | Ya definido por **D-072** |
| **Ejecución** | Quién realiza la acción autorizada: **una persona**, o **un sistema supervisado dentro de un permiso escrito** (caps. 12-15). **Un procedimiento no ejecuta: soporta la ejecución** | Ya definido por **D-072** y **D-074** |
| **Autoridad** | No es una cuarta fila de la lista del capítulo: es **la que gobierna las tres**. Permanece en una persona, una función o un órgano real, **cualquiera que sea la modalidad de la delegación** | Ya definido por **D-072** y **D-073** |

**Las dos frases operativas del capítulo, y son las únicas dos que necesita:**

> **Delegar dirección no significa necesariamente transferir propiedad.**
> **Conservar propiedad no significa tener que dirigir cada decisión.**

**Clasificación de las dos:** son **doctrina del Método LEGADO construida sobre D-072**, no
afirmaciones factuales ni jurídicas, **y no requieren fuente**. Lo que sí requiere tratamiento es
lo que hay debajo: **quién puede dirigir, quién representa legalmente el negocio, qué derechos
tiene una persona empleada, qué exige una sucesión y qué autoridad tiene un familiar dependen de
la estructura jurídica, del contrato, del empleo, de la regulación, del país y de la profesión**.
**El capítulo lo dice y remite** (**D-014**, **D-020**, **D-033**). **Prohibido** resolver
ninguna de esas preguntas.

### 4. Qué función tiene la conversación: informar, consultar, acordar, autorizar

No todas las conversaciones de una transición son la misma, y **decidir cuál es antes de
empezarla es lo que impide que signifique una cosa para quien habla y otra para quien escucha.**

| | Qué hace |
|---|---|
| **Informar** | Se comunica un cambio que ya está dentro de la autoridad de quien lo comunica |
| **Consultar** | Se pide opinión antes de decidir, y se dice que la decisión no está tomada |
| **Acordar** | El cambio necesita la conformidad de la otra parte para funcionar |
| **Autorizar** | El cambio necesita el permiso de alguien distinto, que puede no ser quien habla |

**Prohibido resolver jurídicamente cuál corresponde en cada caso.** Cuando dependa de contrato,
propiedad, empleo o regulación, se dice y se remite a revisión profesional. **Lo que el capítulo
sí puede exigir** es que el lector **elija una de las cuatro y la diga**, porque presentar como
acuerdo lo que es información —o al revés— es la fuente de ambigüedad más cara del capítulo.

### 5. Con quién se habla: las tres audiencias del título, sin dar ninguna por supuesta

**El título nombra equipo, familia y clientes, y es un título editorial. La doctrina es general:
se habla con quien realmente se vea afectado.** El título **no se amplía**.

**Regla que gobierna toda la Parte IV, y esta es la parte donde más importa (índice maestro):
no se da por supuesta la familia.** **Prohibido** escribir «su hijo», «sus herederos», «la
siguiente generación» o «cuando sus hijos tomen el negocio» como escenario general. **Familia no
equivale a sucesión, sucesión no equivale a herencia, y ninguna de las dos es el destino
obligatorio del negocio** —lo fija el apartado 7.4 de `14-publico-y-rutas.md`, que separa el
**Mapa de Participación** del **destino del negocio**—. El método registra además, entre los
riesgos de la etapa D, **delegar por parentesco y no por capacidad**.

**Dónde cambia de verdad el mecanismo, y por eso son tres variaciones y no tres herramientas:**

| Audiencia | Lo que hay que separar | Deslinde |
|---|---|---|
| **Equipo** | Que **responsabilidad, autoridad y límite** sigan alineados. Dos errores opuestos: presentar la delegación como pérdida de confianza, o presentarla como una ampliación de autoridad **que en realidad no existe** | Se **remite** a la herramienta 8. **Prohibido reexplicarla** |
| **Familia**, cuando participe de verdad | Cuatro posiciones que **no tienen por qué coincidir**: **familia** como relación personal · **propietarios** · **quienes trabajan en el negocio** · **quienes podrían participar en el futuro** | **No se diseña ningún protocolo familiar.** Ver el apartado 7 |
| **Clientes** | **¿Qué cliente necesita saber qué para que la relación siga funcionando?** No comunicar de más para demostrar transparencia; no ocultar un cambio que afecte de verdad a la relación | **Ninguna de las dos se convierte en regla jurídica** |

### 6. Las dos rutas

**Ruta A.** Puede haber equipo, familia propietaria, responsables, clientes relevantes,
proveedores y sucesores posibles. Lo que el capítulo tiene que desmontar es el atajo: **comunicar
una transición no consiste en anunciar «a partir de ahora manda otra persona»**. Antes hay que
separar qué cambia, qué no, quién decide, quién ejecuta, qué sigue requiriendo autorización y qué
relación mantiene quien estaba al frente.

**Ruta B.** **Prohibido** escribir «reúna a su equipo» o «prepare a la familia». Puede no existir
ninguno de los dos. La conversación puede ser con un cliente, con un colaborador, con un
proveedor o con una sola persona que empieza a recibir parte de una tarea; **y puede no haber
conversación amplia** si la transición solo cambia procedimientos internos. **La ruta B se sirve
con la misma dignidad que la A y en el mismo texto**, no en un apartado aparte (regla 1 de
`14-publico-y-rutas.md`).

### 7. Q-11 — prueba de necesidad: **NO NECESARIA. No se ejecuta.**

**Q-11:** *¿Qué estructuras de gobierno se recomiendan para separar propiedad y dirección en
empresas familiares?* Capítulo 17. Prioridad media. Sin iniciar.

**La pregunta previa, que es la que decide:** ¿necesita el capítulo 17 afirmar que existe una
estructura de gobierno determinada que una empresa familiar **debe** adoptar?

**No.** Y conviene decir por qué, porque la tentación era real:

1. **La distinción que el capítulo necesita ya está construida.** Propiedad, dirección y ejecución
   se resuelven con **D-072** y con la remisión jurisdiccional, como queda escrito en el apartado
   3. **Ninguna de las dos frases operativas del capítulo requiere una fuente externa.**
2. **Nombrar consejo, junta, protocolo familiar, comité, consejo de familia o holding sería
   prescribir arquitectura**, que es exactamente lo que el capítulo 16 acaba de dejar de hacer con
   la seguridad, y lo que **D-020** prohíbe convertir en cumplimiento.
3. **Importaría estructuras de empresas con tamaño a un libro que sirve también a un negocio de
   una sola persona**, y la regla 6 de `14-publico-y-rutas.md` obliga a no diluir los problemas de
   la ruta A **pero no autoriza a trasplantarlos a la ruta B**.
4. **Convertiría «buena práctica» en obligación**, que es el error que el proyecto lleva seis
   etapas evitando.

**Qué afirmación haría necesaria a Q-11, para que quede escrito y se pueda comprobar:** cualquier
frase de la forma *«para separar propiedad y dirección conviene constituir X»*. **El capítulo 17
no la va a escribir.**

**Propuesta, no decisión: su plazo real es el capítulo 21**, *Qué hacer cuando no existe el
sucesor ideal*, cuyo índice sí nombra **dirección profesional, socios y venta**. Ahí sí podría
hacer falta nombrar figuras reales. **Se anota en el plan y no se ejecuta ahora**, igual que se
hizo con Q-16 y su plazo real.

### 8. Q-09 y el retiro: **no se reabre**

Q-09 contiene evidencia sobre formas de participación y de retiro, y **la tentación es usarla
aquí para darle peso al capítulo**. No se hace. **D-075** ya resolvió el problema conceptual —el
motivo del lector puede ser continuidad, reducción voluntaria de la participación o reasignación
estratégica de tiempo y atención, **y ninguno es la finalidad del método**— y **D-040** fija el
principio permanente. **Citar Q-09 aquí sería decoración.**

**Consecuencia directa para el capítulo 17: no es un capítulo sobre retiro** (**D-075**,
**D-076**). La conversación **no** se presenta como «voy a retirarme». Quien la tiene puede estar
reduciendo tareas, cambiando de papel, delegando una función, creando espacio para otra unidad,
abriendo otro negocio, trabajando menos, quedándose como estratega, preparando continuidad o
simplemente dejando de ser imprescindible. **El mecanismo es el mismo en todos los casos: cambia
quién hace qué.**

### 9. El caso: **NO se crea C-13**

**Recuento comprobado en `revision/control-de-casos.md`:** doce casos, **C-01 a C-12**, con
**6 ruta A / 6 ruta B** y **6 mujeres / 6 hombres**.

**Decisión razonada: dos microescenas sin nombre, una por ruta, por debajo de 120 palabras cada
una.** Motivos:

1. **Lo que el capítulo enseña no es una trayectoria, es una lectura.** Un caso formal necesita
   protagonista, situación y desenlace; aquí lo que hay que mostrar es **la misma frase entendida
   de dos maneras**, y para eso un protagonista con historia estorba.
2. **Precedentes ya publicados:** capítulos **5, 6, 7, 8** y **16** entregan su enseñanza con
   microescenas sin nombre. **No es una excepción.**
3. **Un C-13 solo rompería el equilibrio** de los dos ejes sin añadir mecanismo.
4. **La regla 3 de `14-publico-y-rutas.md`** pide precisamente ejemplos breves en paralelo, de dos
   o tres frases, cuando el mecanismo se manifieste distinto en cada escala. **Es este caso
   exactamente.**

**El reparto por sector no se toca.** La tabla reservaba *importación y distribución* como
capítulo previsto para el 17; **queda sin usar y no hace falta ninguna corrección**, porque esa
columna registra previsiones, no compromisos.

**Las dos microescenas, y qué debe demostrar cada una:**

- **Ruta A —** alguien del equipo oye que una tarea va a dejar de pasar por quien siempre la
  revisaba, y **lo entiende como que ya no se confía en su trabajo**. Nadie dijo eso. **Lo que
  faltó fue decir qué no cambiaba.**
- **Ruta B —** una persona que trabaja sola avisa a un cliente de que a partir de ahora una parte
  del trabajo la prepara otra persona, y **el cliente entiende que va a dejar de atenderle**.
  Nadie dijo eso. **Lo que faltó fue decir quién sigue respondiendo.**

**Las dos ilustran lo mismo:** el daño no lo hizo lo que se dijo, **lo hizo lo que quedó sin
decir**. **Prohibido** presentar ninguna de las dos como reacción típica ni frecuente (**V-41**).

### 10. Arquitectura del Guion de conversación

**Es el entregable del capítulo 17 y vive dentro del capítulo (D-078).** **No es la herramienta
13** —que es el *Modelo de informe diario*, del capítulo 19— **ni la 19**, que no existe. **No
se añade al catálogo, que sigue en dieciocho, y no crea archivo en `recursos/`.**

**Lo que no es:** un discurso que se memoriza; un comunicado; un correo universal; un mensaje de
relaciones públicas. **Lo que sí es:** una hoja que se rellena **antes** de una conversación y se
completa **después**.

**Ocho campos. Se evaluaron las ocho candidatas del encargo y se conservan las ocho, con dos
cambios de fondo:**

| | Campo | Cuándo se rellena |
|---|---|---|
| **1** | **Con quién hablo, y qué función tiene esta conversación con esa persona** — informar · consultar · acordar · autorizar | Antes |
| **2** | **Qué cambia** | Antes |
| **3** | **Qué no cambia** | Antes |
| **4** | **Por qué, y por qué ahora** | Antes |
| **5** | **Qué queda dentro de la autoridad de esa persona** | Antes |
| **6** | **Qué decisiones siguen volviendo a mí, o a quien corresponda** | Antes |
| **7** | **Qué necesito escuchar** / **qué escuché** | **Las dos mitades: una antes, otra después** |
| **8** | **Cuándo volvemos a hablar** — una fecha **o** una condición | Antes |

**Cambio 1, y es el que más importa: el campo 1 no es una etiqueta.** La lista de las ocho
candidatas empezaba por «con quién hablaré», que por sí solo no hace trabajo. **Se le incorpora
la función de la conversación** —apartado 4— porque **cuál de las cuatro es depende de quién está
delante**, y decidirlo antes es lo que impide que un lector presente como acuerdo lo que era
información.

**Cambio 2: el campo 7 se rellena en dos momentos.** Una conversación en la que solo se habla no
es una conversación, y un guion que solo se rellena antes es un discurso. **La segunda mitad
—qué escuché, qué objeción o qué incertidumbre apareció— es la que convierte la hoja en algo que
sirvió.** Y es también la única casilla que puede decirle al lector que **la conversación no
salió como esperaba**, que es información y no fracaso.

**Por qué cinco y seis no se funden**, aunque parezcan las dos mitades de una sola cosa: porque
**autoridad y ejecución son distintas** (**D-072**) y fundirlas devolvería la confusión que el
capítulo 10 deshizo. **Una casilla dice qué puede decidir; la otra, qué sigue sin poder decidir.**

**Un solo guion base, no tres versiones** (**§31 del encargo**). No hay versión familia, versión
equipo ni versión clientes: **hay ocho campos y un campo 1 que los adapta**. Las tres variaciones
del apartado 5 se muestran **después** del guion, en un párrafo corto cada una, y **solo donde el
mecanismo cambia de verdad**.

**Una hoja por conversación.** No una por audiencia y no una por negocio.

### 11. Arquitectura narrativa — **nueve movimientos**

1. **Lo que quiero decir y lo que el otro puede escuchar.** La pregunta heredada del 16, y su
   ensanchamiento inmediato: «otras personas» puede ser un equipo, una persona, un cliente o
   nadie todavía.
2. **Qué significa transferir el control sin perderlo.** Las cuatro condiciones, cada una con su
   capítulo. Bloque corto.
3. **Qué cambia y qué no cambia**, y por qué lo que hace daño es lo que queda sin decir.
4. **Propiedad, dirección y ejecución.** Las dos frases operativas y la remisión.
5. **Qué función tiene esta conversación.** Informar · consultar · acordar · autorizar.
6. **Con quién hay que hablar.** Equipo, familia y clientes cuando existan; **las dos
   microescenas**, una por ruta.
7. **El guion de conversación.** Los ocho campos.
8. **Escuchar, y lo que este capítulo no promete.**
9. **La señal, y la pregunta que abre el capítulo 18.**

**Apertura, y su deslinde obligatorio.** El tipo es **una misma frase y las lecturas opuestas que
admite, antes de que exista ninguna escena**. **Tipo no usado antes.** **Se distingue del
capítulo 9**, que también abre con dos cosas casi iguales y desenlaces opuestos, en dos puntos
que hay que respetar al escribir: allí el objeto son **dos situaciones que ocurrieron** y la
diferencia está en **un criterio no escrito**; aquí el objeto es **una sola frase** y la
diferencia está en **lo que no se dijo después**. Y hay una segunda distinción que además protege
el control de frecuencias: **las lecturas del 17 son posibles, no ocurridas**, de modo que la
apertura **no puede afirmar que nadie reaccione de ninguna manera**.

### 12. Señal de paso, falsable

**No exige** que todos estén de acuerdo, que nadie tenga miedo ni que la conversación saliera
bien. **Ninguna de las tres es comprobable y ninguna depende del lector.**

**Un solo criterio, y dos formas según haya o no interlocutor** *(reformulado el 2026-09-10,
Etapa 3.16A.1: la versión anterior decía «la señal no se comprueba en usted: se comprueba en la
otra persona» y a continuación admitía la ruta B sin interlocutor, de modo que la primera mitad
era universal de más)*. **Las cinco cuestiones son las mismas en los dos casos; lo que cambia es
dónde se comprueban.**

> **Con interlocutor —** la comprensión se comprueba **en la otra persona**: si puede decir **con
> sus propias palabras** qué cambia, qué no cambia, qué queda dentro de su autoridad, qué sigue
> volviendo a otro sitio y cuándo se vuelve a hablar. **Si no puede, la conversación no llegó**
> —por bien que fuera—.
>
> **Sin interlocutor —** cuando la transición solo cambia procedimientos internos y todavía no hay
> nadie a quien decírselo, la preparación se comprueba **por escrito**: que las cinco cuestiones
> puedan formularse en el guion **sin huecos**.

**La segunda no es una versión menor de la primera.** Son dos formas del mismo criterio según la
estructura del negocio, igual que en la herramienta 12 trabajando solo se escribe «a mí» y **no
se finge una separación que no existe**.

**Las cinco no se puntúan, no tienen umbral y no garantizan nada.** **Que alguien entienda un
cambio no significa que esté de acuerdo con él**, y el capítulo tiene prohibido prometer lo
contrario.

### 13. Puente al capítulo 18

El capítulo cierra cambiando la pregunta del lector, **y no la contesta**:

> *De «¿cómo lo explico?» a «¿cómo empiezo a delegarlo sin entregar demasiado de una sola vez?».*

### 14. Fronteras con los capítulos vecinos

| Par | Deslinde |
|---|---|
| **17 y 18** | **17 prepara la relación; 18 ejecuta la delegación.** 17 comunica y aclara expectativas; 18 **transfiere bloques reales y produce evidencia**, y la evidencia tiene tres formas según la modalidad (**D-026** leída con **D-074**): que **otra persona** realiza la acción autorizada; que **un procedimiento** hace que la tarea deje de depender del criterio de una sola cabeza —**el procedimiento no ejecuta**—; o que **un sistema supervisado** ejecuta dentro de su permiso escrito. **El 17 no desarrolla:** delegación por bloques, orden de menor a mayor riesgo, revisión después y no antes, el primer error, ni el plan de delegación |
| **17 y 19** | El 17 **promete que habrá revisión**; **no diseña** tablero, informe diario, informe semanal, métricas ni frecuencia de supervisión |
| **17 y 20** | El 17 **no resuelve** cuándo intervenir, cuándo callarse ni cuándo tolerar un error |
| **17 y 21** | El 17 **no trata** sucesión, venta, dirección profesional, continuidad sin heredero ni elección de sucesor. Aquí solo se prepara a quienes participan o se ven afectados por **una transición ya decidida**. El argumento «el sucesor no tiene por qué ser un familiar» **pertenece al 21** y en el 17 solo cabe **en una frase** |
| **17 y 10** | El 17 **remite** a la matriz de autoridad y **no la reexplica** |
| **17 y 5** | «Delegar no es soltar» pertenece al **18**; en el 17, **una frase como mucho**. «El fundador centralizó por buenas razones» pertenece al **1**; en el 17, **una frase** |

### 15. Lo que el capítulo 17 tiene prohibido prometer

**Ninguna de estas frases, ni ninguna equivalente:** «si usted lo explica bien, todos
confiarán» · «el equipo lo entenderá» · «la familia lo apoyará» · «los clientes aceptarán el
cambio».

> **Una buena conversación reduce ambigüedad. No controla la reacción de otra persona.**

**Y una segunda cosa que no se promete:** que la conversación transfiera nada. **El ADN
Empresarial no se transfiere porque exista un documento ni porque se haya conversado.** La
conversación **prepara**; la delegación del capítulo 18 **prueba**. **Prohibido** declarar la
transferencia hecha en este capítulo.

### 16. Vocabulario a auditar al escribir

**Barrido obligatorio, término por término**, comprobando que cada aparición respeta las dos
rutas y `14-publico-y-rutas.md` §6: *sucesor · heredero · familia · hijo · empleado · equipo ·
jefe · propietario · dueño · director · gerente · retirarse · reemplazar · sustituir · abandonar
· desconfianza · delegar · control · autoridad · responsabilidad*.

**Antropomorfismo de la organización.** **Prohibido** «el negocio quiere», «la empresa entiende»
o «el equipo siente» como estado colectivo. Las interpretaciones se atribuyen **a personas
concretas** o se formulan **como posibilidades**.

**Control de frecuencias (V-41).** **Prohibido** «los empleados suelen», «las familias
normalmente», «los clientes casi siempre», «los fundadores tienden». **Formas admitidas** cuando
no pretendan frecuencia: «puede interpretarse», «una persona puede leerlo como», «en algunos
casos». **Y el control se pasa después de completar el capítulo, no solo antes** —lección
registrada cinco veces en `editorial/05-control-de-fuentes.md`—.

### 17. Extensión, clasificación de afirmaciones y controles

**Objetivo: 2.000 palabras. Diseñado para 1.900–2.100, con el guion dentro del total.** El tope
del +15 % (**D-030**) es un tope, no un objetivo. **La arquitectura de nueve movimientos se
diseñó para caber**: los movimientos 2, 4 y 5 son bloques cortos con tabla, el 6 lleva las dos
microescenas por debajo de 120 palabras cada una, y el 7 es el más largo.

**Clasificación de todo lo que el capítulo va a afirmar:**

| Clase | Qué hay | Necesita fuente |
|---|---|---|
| **A — doctrina del Método LEGADO** | Las cuatro condiciones de «sin perderlo»; propiedad ≠ dirección ≠ ejecución; las cuatro funciones de la conversación; la señal de paso | **No.** Se declaran como diseño de este método |
| **B — instrucción práctica** | El guion y sus ocho campos; las tres variaciones | **No** |
| **C — afirmación factual externa** | **Ninguna prevista** | — |
| **D — afirmación jurídica** | **Ninguna.** Todo lo jurídico se remite | — |
| **E — gobierno empresarial** | **Ninguna.** Por eso Q-11 no se ejecuta | — |

**Fuentes nuevas previstas: cero. Total: 46.** **Investigación nueva: ninguna.** **Preguntas
nuevas de investigación: ninguna** —y **prohibido** abrir una sobre comunicación o cambio
organizacional para adornar un capítulo que se sostiene por mecanismo—.

**Verificaciones que afectan al capítulo 17.** **V-41**, barrido de afirmaciones de frecuencia,
**en vigor y es la más pertinente de todo el libro en este capítulo**. **V-56B**, el vacío de
evidencia hispanohablante, que refuerza lo anterior: **no hay con qué sostener ninguna
afirmación de frecuencia sobre la ruta B**. **V-61**, separación de funciones, que **no se
reabre**: el capítulo habla de alinear responsabilidad, autoridad y límite, **no de separar
funciones**. **V-40**, referencias cruzadas a la numeración antigua, que se comprueba en la
Etapa 4. **Y V-70, nueva**, que registra que el libro **no define ni reparte la propiedad ni la
dirección en términos jurídicos** y que el capítulo 17 remite. **Ninguna necesita decisión del
autor.**

**Decisiones nuevas propuestas: ninguna.** Todo lo que el capítulo necesita está resuelto por
**D-014**, **D-020**, **D-026**, **D-030**, **D-033**, **D-040**, **D-072**, **D-074**, **D-075**,
**D-076** y **D-078**.

**`producto/` no necesita cambios.** `producto/02-mapa-libro-plataforma.md` ya registra el
capítulo 17 con **«sin mención de producto»** y **ninguna llamada a la acción**, y lo incluye en
la lista de capítulos sin ninguna mención identificable de la plataforma. **El guion podría
existir mañana como experiencia digital —destinatario, cambio, motivo, autoridad, límites,
preguntas, objeciones, seguimiento— y hoy no se diseña nada: sin esquema, sin base de datos, sin
programación y sin elección de proveedor.** **El capítulo debe estar completo sin software.**


---

## Preflight del capítulo 18 (Etapa 3.17A, 2026-09-10)

**Es el capítulo donde la etapa D deja de explicarse y empieza a ocurrir**, y el único del libro
que puede producir la evidencia que **D-071** reservó: detectar y representar son la etapa E;
**transferir es esto**.

### 0. Resultado que condicionaba la escritura — **RESUELTO**

**El preflight se cerró con un asunto que requería decisión del autor: V-71**, sobre la línea
«corrección del sistema, no de la persona» de la etapa D, desarrollada en el apartado 9.
**Resuelto el 2026-09-10 por decisión del autor: D-079**, que aprueba la reformulación como
**orden de examen**. **El movimiento 7 ya puede escribirse** y la Etapa 3.17B deja de estar
bloqueada. El resto de la arquitectura no dependía de esa decisión y no cambia.

### 1. La pregunta central, y de dónde viene

El capítulo 17 termina exactamente así, y el 18 no puede inventarse otra entrada:

> *Ya no es «¿cómo lo explico?». Es «¿cómo empiezo a delegarlo sin entregar demasiado de una sola
> vez?».*

**La pregunta trae un atajo dentro, y el capítulo tiene que desactivarlo en su primer
movimiento.** Quien teme entregar demasiado de una vez **puede corregirlo entregando tan poco que
no ocurre nada observable**, y entonces no hay evidencia de ninguna clase: ni de que funciona ni
de que no. **Los dos extremos fallan por el mismo motivo —después no se puede saber qué pasó—**, y
esa es la puerta de entrada a la definición de bloque.

**Movimiento emocional del capítulo:** de *«ya lo expliqué»* a *«ahora tengo que dejar que ocurra
sin mí, dentro del límite»*. **Sin dramatizar**: el primer error no es una catástrofe y el primer
acierto no es una prueba.

### 2. Qué es un bloque

**Definición del método, y se declara como tal:**

> **Un bloque es una transferencia acotada que se puede observar por separado.**

**No es** un departamento, ni una semana, ni un porcentaje, ni un número fijo de tareas, ni una
fase temporal, ni un nivel de riesgo. **Es la combinación mínima de cuatro cosas que el libro ya
tiene escritas:** una **tarea o decisión** concreta · su **límite** · **a quién o a qué** se
transfiere · y **quién responde**.

**La prueba de tamaño, que es lo que hace útil la definición, y es falsable en las dos
direcciones:**

> **Un bloque tiene el tamaño correcto cuando, al revisarlo, usted puede decir qué pasó con él
> sin tener que mirar nada más.**
>
> **Demasiado grande:** para saber qué ocurrió hay que desenredarlo de otras cosas que cambiaron a
> la vez. **Demasiado pequeño:** no ocurre nada observable, y no produce evidencia.

**Prohibido fijar un tamaño universal**, un número de tareas o una duración. La prueba sustituye a
la cifra, igual que en el capítulo 13 el método se negó a fijar la duración del periodo de
observación.

### 3. Por dónde se empieza: reversibilidad, no una métrica nueva

El índice dice «de menor a mayor riesgo». **Eso se lee, no se convierte en un instrumento.** El
libro **no tiene ni va a tener una escala de riesgo**, y crear una aquí competiría con los niveles
de autonomía del capítulo 15 y con la matriz del 10.

**Lo que sí tiene, ya escrito y sin fuente nueva:** la **reversibilidad práctica** de **D-077**
—«deshacerlo sin provocar una consecuencia igual o mayor»—, la columna de límites de la
herramienta 8 —que ya incluye consecuencias y posibilidad de deshacer— y la primera pregunta al
fundador de la etapa D: *¿qué decisión, si se tomara mal una vez, no pondría en riesgo la
empresa?*

**Formulación adoptada para el capítulo:** se empieza **por donde un error se pueda deshacer**, y
—esto es lo que se añade— **por donde usted pueda contestar esa pregunta sin dudar**. Si no sabe
si es reversible, ese no es el primer bloque.

### 4. Las tres modalidades, un solo mecanismo

**D-026** es obligatoria y **D-074** la acota. **El capítulo no se parte en tres**: hay **un solo
ciclo** y las modalidades cambian **una casilla**, no el método.

| Modalidad | Qué cambia en el bloque | Qué no cambia |
|---|---|---|
| **Persona** | Otra persona **realiza la acción autorizada** dentro del límite | La autoridad sigue asignada a una persona, función u órgano real (**D-073**) |
| **Procedimiento** | La tarea **deja de depender del criterio concentrado en una sola cabeza**, porque queda escrito lo que hay que seguir. **No ejecuta** (**D-074**): lo sigue alguien | Ídem |
| **Sistema supervisado** | Ejecuta acciones autorizadas **dentro del permiso ya definido en el capítulo 15**. El 18 **no lo redefine** | Ídem, y **no adquiere autoridad, responsabilidad ni criterio propios** |

**Y en las tres hay una persona identificable que responde.** **Prohibidas**, y se comprueban
antes del commit: «el procedimiento decide», «el procedimiento responde», «el sistema es
responsable», «la IA tiene autoridad».

**Los dos argumentos que este capítulo posee y debe desarrollar aquí, no anunciar** (control de
repeticiones): **«delegar no es soltar»** —consumido una vez en el capítulo 1— y **«delegar no
significa contratar»** —consumido en la introducción y en el 1—. **Es su capítulo propietario y
es la última oportunidad de desarrollarlos.**

### 5. Revisar después en lugar de aprobar antes, y sus tres límites

**No necesita fuente.** **D-072** ya fija que **aprobación es antes** y **revisión es después**, y
`recursos/README.md` la declara **convención operativa de este método**. Lo que el capítulo añade
es el uso: **dentro del permiso escrito, la ejecución deja de necesitar el visto bueno previo de
la persona clave y se comprueba después.**

**Y hay que decir los tres límites en el propio capítulo, porque sin ellos la frase es
peligrosa:**

1. **Fuera del permiso escrito no aplica.** Ahí la tarea se detiene y vuelve —doctrina del
   capítulo 15, y el capítulo 18 la **usa** sin reexplicarla—.
2. **No suprime un control previo que una obligación legal, contractual o profesional imponga.**
   Donde una norma exija autorización antes, la autorización sigue antes. **D-033** gobierna y el
   capítulo **remite**, no resuelve.
3. **No significa dejar de mirar.** Qué se mira es el capítulo **19**; cuándo se interviene es el
   **20**. El 18 promete las dos cosas y **no construye ninguna**.

### 6. Qué es evidencia en este capítulo

**Prohibido** aceptar como evidencia «funcionó bien», «salió perfecto», «ya confío» o «ya puede
hacerlo solo». **Ninguna de las cuatro se puede reconstruir.**

**El mínimo ya está escrito** en la columna 7 de la herramienta 12 —qué se ejecutó, bajo qué
permiso, cuándo, si hubo excepción y qué se decidió— y el capítulo 16 fijó su techo: **auditar no
es registrarlo todo**. **El capítulo 18 no inventa un registro nuevo.** Añade **una sola cosa,
que es específica del bloque:**

> **Qué volvió a la persona clave, y por qué volvió.**

Esa lista —no un número, no un porcentaje— es lo que permite decidir el bloque siguiente. **Si no
volvió nada, también es evidencia**, y hay que escribirlo.

### 7. El primer bloque

Lo que tiene que quedar escrito antes de empezar, y todo sale de material ya existente: **qué se
transfiere · a quién o a qué · bajo qué límite ya escrito · quién responde · qué obliga a
detenerse y a quién vuelve · cuándo se revisa.**

**No se exige un resultado.** La prueba está para producir **evidencia**, no obediencia, no
confianza por decreto y no un éxito predeterminado.

### 8. Progresividad: qué crece, y de una en una

**No es tiempo, no es confianza y no es «más tareas».** Y **no es una escalera nueva**: los
niveles de autonomía son del capítulo 15 y la herramienta 12 ya dice que **ningún nivel se gana
por acumulación** y que las salidas son cuatro. El capítulo 18 **remite** a eso.

**Lo que puede crecer en un bloque son tres cosas, y solo tres:**

| | Qué significa |
|---|---|
| **El alcance** | Más casos **del mismo tipo** |
| **La variedad** | Casos que antes se apartaban por ser distintos |
| **La revisión** | Menos frecuente, o por muestreo en lugar de una por una |

> **Se amplía una sola de las tres cada vez.** Si crecen dos a la vez, la revisión siguiente ya no
> puede decir cuál de las dos produjo lo que ocurrió, **y el bloque deja de ser observable** —que
> es exactamente lo que la prueba de tamaño del apartado 2 trataba de evitar—.

### 9. Cuando algo sale distinto de lo previsto — **y aquí está V-71**

**Primero, la reducción.** El encargo proponía siete clases y **varias son la misma cosa vista dos
veces**. Contrastadas con la doctrina ya existente quedan **cuatro**, y **el orden en que se
recorren es la mitad del contenido**:

| | Clase | De dónde viene |
|---|---|---|
| **1** | **El caso estaba fuera del permiso.** **Y entonces no es un error: es el límite funcionando** | Capítulo 15 y **C-12**, donde una excepción **retira** el permiso en lugar de concederlo |
| **2** | **Faltaba información, o faltaba criterio escrito** | Capítulos 9 y 11, y el mecanismo de **C-10** |
| **3** | **El límite estaba mal escrito** — demasiado amplio, demasiado estrecho o no comprobable | Capítulo 10 y la herramienta 8 |
| **4** | **La ejecución falló dentro de un permiso correcto y con material suficiente** | **Es la única de las cuatro que apunta a una conducta**, y aun así admite dos lecturas: falta de competencia para esa tarea, o incumplimiento deliberado de un límite escrito |

**Se recorren en ese orden, y el motivo es comprobable: tres de las cuatro se resuelven sin tocar
a nadie.** La cuarta solo se sostiene cuando las tres primeras quedaron descartadas.

**La pregunta que el capítulo no debe contestar por el lector:** *¿el error demuestra que la
delegación no debía existir, o demuestra qué parte del sistema todavía necesita corrección?*
**Depende de la clase**, y por eso la clasificación va antes que la decisión.

**V-71 — auditoría de «corrección del sistema, no de la persona». RESUELTA POR DECISIÓN DEL AUTOR EL 2026-09-10: D-079, opción A.** Lo que sigue es el análisis tal como se presentó, y se conserva porque explica por qué la frase cambió.

**A. Qué colisiona.** La línea de *Acciones* de la etapa D en `07-metodo-legado.md` —«Revisión
posterior de lo que falló y **corrección del sistema, no de la persona**»— contra **D-072** y
**D-073**, que hacen que la autoridad y la responsabilidad sean **de una persona**; y contra un
riesgo que la propia etapa D registra, **«delegar por parentesco y no por capacidad»**, que solo
tiene sentido si la competencia de una persona puede ser el problema.

**B. Por qué no conviven tal como están.** Una doctrina que **nunca** atribuye nada a la conducta
vacía la responsabilidad que D-072 asigna, y deja al libro sin manera de tratar dos situaciones
reales: **el incumplimiento deliberado de un límite escrito** y **la falta de competencia para la
tarea transferida**. La clase 4 del cuadro de arriba no se podría escribir.

**C. Opciones.**

| | Qué haría | Coste |
|---|---|---|
| **A** | **Reformular como orden de examen:** «se examina **primero** la arquitectura de la transferencia —permiso, límite, información y criterio escrito— y **solo después**, si esas quedan descartadas, la conducta» | Una línea de `07-metodo-legado.md`. **Conserva íntegra la intención protectora** y deja de ser universal |
| **B** | Dejarla como está y que el capítulo 18 no la cite | **La contradicción sigue viva** entre el documento del método y el manuscrito, y la Etapa 4 la encontrará |
| **C** | Suprimirla | Pierde la protección que hoy da. **No se recomienda** |

**D. Recomendación: opción A.**

**E. Impacto.** Una línea. **Cero decisiones nuevas**: es reconciliación de una frase con
D-072/D-073, exactamente como la Etapa 3.16A.1 reconcilió D-026 con D-074. Y **desbloquea el
movimiento 7** del capítulo 18.

### 10. Qué se decide con el bloque, y por qué la confianza no mide

**Cuatro salidas, y ninguna es premio ni castigo:**

| | Cuándo | Qué evidencia la sostiene |
|---|---|---|
| **Mantener** | El bloque se movió dentro del límite y lo que volvió, volvió por las razones previstas | El registro del bloque, sin más |
| **Ampliar** | Hay evidencia suficiente sobre **una** de las tres dimensiones del apartado 8 | Se amplía **esa**, no las tres |
| **Reducir** | Apareció una clase de caso que el límite no cubría | Se estrecha el alcance **en lugar de retirar todo** |
| **Detener** | La evidencia no se pudo reconstruir, o la corrección necesaria está fuera del alcance de quien recibió el bloque | La ausencia de evidencia **también es un resultado** |

> **Retroceder no es un fracaso y continuar no es un éxito.** Las cuatro son respuestas legítimas
> a la evidencia, y la que corresponde la dice el bloque, no el ánimo con que se mire.

**Y la regla que gobierna las cuatro:** **se amplía porque hay evidencia, no porque haya
confianza.** La confianza puede ser una consecuencia humana de que algo funcione; **no es la
unidad de medida de este método**, y el capítulo tiene prohibido escribir «cuando confíe, delegue
más».

### 11. El Plan de delegación por bloques — **seis campos**

**Es el entregable del capítulo 18 y vive dentro del capítulo (D-078).** **No es la herramienta
13** —que es el *Modelo de informe diario*, del capítulo 19—, **no es el Plan de transición de 100
días** —que es la herramienta 17, del capítulo 23— y **no crea archivo en `recursos/`**. **El
catálogo sigue en dieciocho y los recursos producidos en 12 de 18.**

**Se evaluaron los ocho campos candidatos y se reducen a seis**, porque tres de los ocho ya viven
en la herramienta 12 y **duplicarlos convertiría el Plan en una segunda matriz de niveles**:

| | Campo | Cuándo |
|---|---|---|
| **1** | **El bloque** — qué se transfiere, en una línea y en verbos | Antes |
| **2** | **A quién o a qué**, y **quién responde** — persona · procedimiento · sistema supervisado | Antes |
| **3** | **Bajo qué límite ya escrito** — **remisión** a la fila de la matriz de autoridad o de la matriz de niveles. **No se reescribe aquí** | Antes |
| **4** | **Cuándo se revisa, y qué se va a mirar** | Antes |
| **5** | **Qué ocurrió** — qué se hizo, **qué volvió y por qué**, qué excepción apareció | Después |
| **6** | **Qué se corrige, y qué se decide**: mantener · ampliar *(una sola dimensión)* · reducir · detener | Después |

**Qué se fusionó, y por qué.** *«Quién responde»* entra en el campo 2 porque es el mismo acto que
elegir destinatario. *«Límite vigente»* y *«qué obliga a detener o devolver»* se convierten en el
campo 3, que es **un puntero y no una copia**: los dos están en la herramienta 12, columnas 4 y 5.
*«Qué debe ocurrir sin volver a la persona clave»* es el campo 1 escrito en verbos, que es la
disciplina que el capítulo 15 ya impuso.

**Tres campos antes y tres después**, como el guion del capítulo 17. **Una hoja por bloque**, no
por persona y no por negocio.

### 12. El caso: **se propone C-13, y no se crea en esta etapa**

**Los doce existentes se revisaron uno por uno y ninguno sirve.** El más cercano es **C-07**
(Pilar), donde un límite escrito reparte decisiones que antes volvían todas a la misma persona;
**pero ese es el mecanismo del capítulo 10**, y reutilizarlo aquí borraría precisamente la
frontera 10/18 que este preflight tiene que proteger.

**Por qué aquí sí hace falta un caso formal, después de dos capítulos sin ninguno.** Lo que el
capítulo 18 enseña es **un ciclo en el tiempo** —se transfiere, ocurre, se revisa, se clasifica,
se decide—. **Una microescena es una instantánea y no puede mostrar un ciclo**, que es justo lo
contrario del razonamiento que llevó a los capítulos 16 y 17 a no crear caso. Además es el
capítulo propietario de **«delegar no es soltar»** y **«delegar no significa contratar»**, y los
dos necesitan una trayectoria concreta para no quedarse en eslogan.

**Propuesta, con todo lo que las reglas de casos exigen:**

| | |
|---|---|
| **ID** | **C-13** |
| **Ruta** | **A** — empresa con estructura |
| **Género** | **Mujer.** Balance actual 6/6; con este queda 7/6. **De los tres últimos casos formales, dos son hombres** (C-10, C-12), de modo que también corrige el reparto reciente |
| **Sector** | **Construcción** — **cero casos formales** hasta hoy |
| **Modalidad** | **Persona**, con **dos ejemplos breves en paralelo** —no casos— para procedimiento y para sistema supervisado, según la regla 3 de `14-publico-y-rutas.md` |
| **Qué demuestra** | **El ciclo completo sobre un solo bloque**: se transfiere una decisión acotada, algo vuelve, se clasifica en cuál de las cuatro clases cae, y se decide entre las cuatro salidas. **Y demuestra que ampliar una sola dimensión es lo que permite leer la siguiente revisión** |
| **Qué NO demuestra** | Que la delegación funcione; que la persona receptora fuera la correcta; que el resultado se repita; ni que el negocio ya no dependa de quien delegó. **Un bloque no es el negocio** |
| **Riesgo de semejanza** | **Bajo**, por diseño: tres rasgos, sin lugar, sin cifras, sin fechas, sin composición familiar y **sin vocabulario de oficio** |

**Por qué no se usa comercio mayorista, que era la previsión del índice para el 18.** Ese sector
ya carga **C-04** (hombre, ruta A) **y el ejemplo de la herramienta 11** (hombre, ruta A). Un
tercer caso ahí sería la **tercera instancia de ruta A en un solo sector** y agotaría su cupo. **La
previsión del índice registra previsiones, no compromisos**, y ya se resolvió así en el preflight
del capítulo 17.

**No se registra todavía en `revision/control-de-casos.md`:** la regla dice que un caso se
registra antes de escribirse, y escribirlo es la Etapa 3.17B.

### 13. Arquitectura narrativa — **nueve movimientos**

| | Movimiento | Qué contesta | Qué introduce | Qué recibe | Qué prepara |
|---|---|---|---|---|---|
| **1** | **La pregunta del 17, y los dos atajos** | ¿Por dónde se empieza a delegar? | Que entregar de más y entregar de menos fallan por el mismo motivo | El cierre del 17 | La definición de bloque |
| **2** | **Qué es un bloque** | ¿Qué tamaño tiene lo que se transfiere? | La definición y **la prueba de tamaño en dos direcciones** | El movimiento 1 | El orden de los bloques |
| **3** | **Por dónde se empieza** | ¿Cuál va primero? | **Reversibilidad**, sin métrica nueva | D-077 y la herramienta 8 | El primer bloque |
| **4** | **A quién o a qué** | ¿Quién recibe? | Las tres modalidades en un solo ciclo; **destinatario ≠ ejecutor**; y los dos argumentos propios | D-026, D-074, D-073 | La ejecución real |
| **5** | **Revisar después, no antes** | ¿Cuándo se comprueba? | La distinción de D-072 **y sus tres límites** | Capítulos 10, 15 y D-033 | Los capítulos 19 y 20 |
| **6** | **El primer bloque, ejecutado** — **C-13** | ¿Cómo se ve esto de verdad? | El ciclo completo sobre un caso | Los movimientos 2 a 5 | La clasificación |
| **7** | **Cuando algo sale distinto** | ¿Qué falló? | **Las cuatro clases, recorridas en orden** | Capítulos 8, 9, 10, 11, 15 | La decisión |
| **8** | **Qué se decide, y el Plan** | ¿Y ahora qué? | Las cuatro salidas, la ampliación de una en una, y **los seis campos** | El movimiento 7 | El bloque siguiente |
| **9** | **La señal, y lo que viene después** | ¿Cuándo se puede seguir? | La señal falsable | Todo lo anterior | El capítulo 19 |

**Apertura.** Tipo a fijar en 3.17B, **con una condición: no puede ser una pregunta heredada
contestada de frente**, porque los capítulos 13, 14, 15 y 16 ya agotaron ese recurso y el 17
usó la variante de la frase con dos lecturas. **La dirección recomendada** es abrir con **el atajo
contrario al que el lector teme** —entregar tan poco que no ocurra nada—, que es un tipo no usado
y que además es el material del movimiento 1.

### 14. Fronteras, todas por escrito

| Par | Deslinde |
|---|---|
| **G / D** | **G escribe la regla; D la pone en práctica.** El lector llega al 18 **con el límite ya escrito**. El 18 **no enseña a construir la matriz de autoridad, no rediseña límites y no repite el capítulo 10** |
| **10 y 18** | El 10 **reparte autoridad decisión por decisión** y produce la matriz. El 18 **usa una de esas filas** en una transferencia real y observa qué ocurre. **Remite, no reexplica** |
| **15 y 18** | El 15 fija **qué puede ejecutar una tecnología y con qué permiso**. El 18 trata **qué ocurre cuando una tarea real empieza a pasar por esa vía**. **El 18 no vuelve a explicar la escala de autonomía y no mueve ningún nivel**: usa el permiso ya definido |
| **17 y 18** | El 17 **comunica y prepara**; el 18 **transfiere y prueba**. **Ya escrito y comprobado desde el lado del 17** |
| **18 y 20** | El 18 dice **qué se transfiere y qué evidencia produce**. El 20 dice **cuándo se interviene y cuándo no**. **El 18 no fija reglas de intervención** |
| **18 y 23** | El 18 es la **mecánica de una transferencia**; el 23 es la **secuencia de la transición en el tiempo**, con hitos y fechas. **Un bloque no es una fase de un calendario**, y el Plan por bloques **no es el Plan de transición de 100 días** (herramienta 17) |
| **18 y 24** | El 18 prueba la delegación **mientras la persona clave sigue disponible**. El 24 prueba qué ocurre **cuando esa disponibilidad se retira a propósito**. **El 18 no adelanta las 24 horas, los 7 días ni la prueba de ausencia**; como mucho las nombra como destino posterior |
| **18 y 19** | El 18 **promete que habrá algo que mirar**; el 19 **construye el instrumento**. Sin tablero, sin informes, sin métricas y sin frecuencias |

### 15. Señal de paso del capítulo, falsable

**No exige** que el bloque saliera bien, que no volviera nada, ni que la persona clave se sienta
cómoda. **Ninguna de las tres es evidencia.**

> **Se puede pasar al bloque siguiente cuando, mirando solo la hoja de este, se puede decir qué se
> transfirió, qué ocurrió, qué volvió y por qué, en cuál de las cuatro clases cayó lo que salió
> distinto, y cuál de las cuatro salidas se eligió.**
>
> **Si para contestar eso hay que recordar en lugar de leer, el bloque no está cerrado** —por bien
> que fuera—.

**Y su forma cuando la modalidad no es una persona:** idéntica. Lo que cambia es de dónde sale el
registro, no qué hay que poder reconstruir.

**Prohibido** puntuar, fijar un umbral, contar bloques o convertir «cuatro de cuatro» en un
aprobado.

### 16. Puente al capítulo 19

El capítulo cierra cambiando la pregunta, **y no la contesta**:

> *Ya no reviso cada decisión antes de que ocurra. Entonces, ¿qué miro?*

### 17. Investigación, fuentes y decisiones

**Investigación ejecutada: ninguna. Fuentes nuevas: cero. Total: 46.**

**Ninguna pregunta del plan está asignada al capítulo 18** —comprobado una por una sobre la tabla
de Q-01 a Q-21—, y **no se abre ninguna nueva**. La prueba de necesidad se hizo afirmación por
afirmación:

| Clase | Qué hay en el capítulo | Necesita fuente |
|---|---|---|
| **A — doctrina del método** | La definición de bloque y su prueba de tamaño; la ampliación de una dimensión cada vez; las cuatro clases y su orden; las cuatro salidas; la señal | **No.** Se declaran como diseño de este método |
| **B — instrucción práctica** | Los seis campos del Plan | **No** |
| **C — afirmación factual externa** | **Ninguna prevista** | — |
| **D — afirmación jurídica** | **Ninguna.** El límite 2 del apartado 5 **remite** (D-033) | — |

**Lo que se comprobó antes de descartar:** «aprobación antes / revisión después» **ya está fijada
por D-072** y `recursos/README.md` la declara **convención operativa de este método**, de modo que
el capítulo no necesita apoyarla en nada externo. **Y el reflejo de buscar literatura sobre
delegación gradual se descartó expresamente**: el capítulo se sostiene por mecanismo, y citar por
citar es lo que este proyecto lleva siete etapas evitando.

**Decisiones nuevas: cero.** Todo se resuelve con **D-026**, **D-030**, **D-033**, **D-040**,
**D-071**, **D-072**, **D-073**, **D-074**, **D-075**, **D-077** y **D-078**. **V-71 no es una
decisión nueva:** pide reconciliar una frase con decisiones que ya existen.

### 18. Controles previos sobre la propia arquitectura

**Universalidades.** Barrido sobre este preflight: las apariciones de *siempre · nunca · todos ·
nadie · garantiza · debe · necesariamente · automáticamente* que quedan son **prohibiciones
metodológicas y negaciones** —«prohibido fijar un tamaño universal», «ninguna de las cuatro es
premio ni castigo», «no es la unidad de medida»—. **Se retiraron las predicciones**: no se afirma
que un bloque pequeño funcione, ni que el primer error sea frecuente, ni que ampliar despacio dé
mejor resultado. **Y una que hubo que corregir dentro de este mismo preflight, antes del commit:** el apartado 1
decía «quien teme entregar demasiado de una vez **suele** corregirlo entregando muy poco», que es
una afirmación de frecuencia sobre conducta ajena (**V-41**). Quedó en **«puede corregirlo»**, y
así debe llegar al capítulo.

**Antropomorfismo.** La arquitectura no atribuye a un procedimiento ni a un sistema los verbos
*pensar, decidir, responder, querer, entender* ni criterio propio. **Lo que un sistema
supervisado sí puede hacer, porque así se diseñó y se autorizó: ejecutar, registrar, comparar y
detenerse.**

### 19. Extensión

**Objetivo: 2.200 palabras. Tope por D-030: 2.530**, que es un tope y no un objetivo. **Reparto
previsto:** el movimiento 6 —el caso— alrededor de 300, el 8 alrededor de 350, y los otros siete
entre 180 y 230 cada uno. **El Plan y el caso cuentan dentro del total.**


---

## Preflight del capítulo 19 (Etapa 3.18A, 2026-09-10)

**Es el primer capítulo de la etapa O**, y el primero desde el 15 cuyos entregables son
**herramientas del catálogo** —la 13 y la 14— y no entregables internos bajo D-078.

### 0. Resultados que condicionan la escritura: ninguno bloquea

**Tres hallazgos, los tres resueltos con doctrina vigente y ninguno exige decisión del autor.**
Están en los apartados 1, 2 y 12. **Cero decisiones nuevas, cero investigación, cero fuentes
nuevas.** Se abre **V-72**, que registra una imprecisión de `07-metodo-legado.md` §6 **con una
recomendación y sin aplicarla**.

### 1. Auditoría D → O: la letra marca lo que el capítulo desarrolla, no dónde está el lector

**El problema, planteado con los textos delante.** El capítulo 19 pertenece a la etapa **O**
según el índice. Pero el **criterio de paso a O** de `07-metodo-legado.md` es *«una prueba de
ausencia de siete días completada sin incidencias graves»*, y **esa prueba se enseña en el
capítulo 24**. Además, el índice **intercala** letras a partir del 19 —19 O, 20 O, 21 D, 22 O, 23
D, 24 D, 25 O— y la **regla transversal 2** dice: *«Ninguna etapa se salta. Se puede recorrer
despacio, no en desorden.»*

**Resuelto a favor de la lectura A, y con tres pruebas del propio repositorio:**

1. **`07-metodo-legado.md` §6 dice para qué sirve la letra**, y es lo decisivo: *«Cada capítulo
   declara en su encabezado la etapa del método a la que pertenece. **Ese dato permite comprobar
   en la Etapa 4 que el método avanza de forma pareja y que ninguna letra queda sin desarrollo
   suficiente.**»* Es un **marcador de cobertura** —qué letra desarrolla el capítulo—, no una
   afirmación sobre la posición cronológica del lector.
2. **El libro ya usa la letra así, y tres veces.** El **11** figura como «**A, con G como
   requisito**»: la letra dice qué desarrolla y el prerrequisito va aparte. El **10** es «**G
   (G-1)**» dentro de una parte cuya fila resume «L, E y **el inicio de** G». Y el índice dice del
   **11** que abre A «con G como requisito previo».
3. **La regla transversal 2 habla del trabajo del lector, no del orden de los capítulos**, y el
   propio índice lo confirma cuando dice que *«el orden de esfuerzo cambia aunque el orden de las
   etapas no. El método no se reordena, pero los capítulos pueden decir dónde está el mayor
   rendimiento para cada uno»*.

**Formulación que el capítulo puede usar, y que no crea doctrina:** el tablero se construye
**cuando se cierra el primer bloque**, no cuando la etapa D está terminada. Empieza pequeño
porque hay poco delegado, y crece con lo que se delega. **Es el mismo patrón que el capítulo 15**,
que construyó la matriz de niveles antes de que ningún lector hubiera completado un periodo de
observación.

**Y una imprecisión real que queda registrada y no se toca: V-72.** La tabla de
`07-metodo-legado.md` §6 asigna **Parte IV (17–21) = D** y **Parte V (22–25) = O**, mientras el
índice asigna letra por capítulo e **intercala**. Las dos no dicen lo mismo para **seis
capítulos**: 19, 20, 22, 23, 24 y 25. **No bloquea** —la tabla es un resumen por parte y ya usa
lenguaje aproximado en las otras filas: «el inicio de G», «con G como requisito previo», «apoyada
en G»— pero **se hace visible por primera vez justo aquí**, en el primer capítulo cuya letra
difiere de la de su parte. Ver el apartado 13.

### 2. Prueba de necesidad de investigación: **CERO**

**Ninguna pregunta del plan está asignada al capítulo 19** —comprobadas Q-01 a Q-21 una por una—.
Antes de buscar nada se escribieron las afirmaciones externas que el capítulo tendría que hacer:

| ¿Necesita afirmar…? | Respuesta |
|---|---|
| que existe un **número universal de indicadores** | **No.** El capítulo se niega expresamente, y una negativa no necesita fuente |
| que existe una **frecuencia universal** para cada señal | **No.** Misma negativa |
| que existe un **KPI** que todo negocio deba mirar | **No** |
| que existe una **estructura universal de tablero** | **No** |
| que una cadencia es **empíricamente superior** a otra | **No.** Y afirmarlo exigiría evidencia que el proyecto no tiene |

**Todo lo que el capítulo afirma es doctrina del método o instrucción práctica.** **Investigación
nueva: cero. Fuentes nuevas: cero. Total: 46. Preguntas nuevas: ninguna.**

**Y se comprobó qué fuentes existentes podrían tentar, antes de descartarlas** (§34 del encargo):
**F-034 a F-037** —control interno, con su componente de *monitoring*— sostienen afirmaciones
sobre **marcos de control interno**, no sobre el instrumento privado de una persona propietaria;
**F-007** (MEASURE) y **F-045** miden **sistemas de inteligencia artificial desplegados**, no
tableros. **Ninguna sostiene una frase concreta que este capítulo necesite, y usarlas sería citar
por asociación.** F-045 ya prestó en el capítulo 13 el único argumento que aquí serviría —que la
cadencia de monitorización es una pregunta abierta—, y repetirlo sería citar dos veces el mismo
apoyo, además de arrastrar la monitorización de IA a un capítulo cuyo sujeto es una persona.

### 3. La pregunta heredada, y la que este capítulo contesta

El capítulo 18 termina así, y el 19 la recibe:

> *Ya no reviso cada decisión antes de que ocurra. Entonces, ¿qué miro?*

**El 19 contesta exactamente eso: qué mirar.** **No contesta cuándo intervenir**, que es el
capítulo 20 y se deja dicho en el propio texto.

**La tentación que abre el capítulo**, y que es la heredera natural del atajo del 18: **delegar y
después pedir un informe de todo**. Quien acaba de dejar de aprobar cada decisión puede querer
compensarlo sabiéndolo todo después, y eso tiene nombre en el propio método: la etapa O registra
como riesgo **«que la supervisión se convierta en control informal que anule la delegación»** y
como diagnóstico **«qué está mirando de más por costumbre»**. **El capítulo no lo inventa: lo
desarrolla.**

### 4. Qué es el tablero del propietario, y qué no es

**Definición de trabajo del método, declarada como tal:**

> **El tablero del propietario es el conjunto pequeño de señales que llegan solas, con una fuente
> identificable, y que permiten ver un cambio, una excepción o una decisión que espera.**

**«Que llegan solas» es la parte que hace trabajo**, y viene del criterio de cierre de la etapa O:
*«el fundador **recibe información sin pedirla**»*. Si hay que pedirla, todavía no es un tablero.

**Qué no es, y conviene decirlo porque la palabra arrastra:** no es un *dashboard*, ni un programa,
ni un sistema de gestión, ni una hoja de cálculo obligatoria, ni un informe contable, ni un estado
financiero, ni un reporte legal, ni una lista de tareas, ni una lista de alertas, ni un panel
gobernado por una tecnología. **Puede vivir en papel, en una hoja, en un correo o en un documento**
—y más adelante, si el lector quiere, en un programa—. **La función precede al formato**, y el
libro no recomienda ningún producto ni proveedor.

### 5. Qué merece entrar: la prueba de la señal

Es la contribución propia del capítulo, y es **falsable**:

> **Una señal merece estar en el tablero si usted haría algo distinto según lo que diga.** Si la
> mira, la entiende y no cambia nada en ningún caso, no es una señal: es una costumbre.

**Contesta directamente al diagnóstico de la etapa O** —«qué está mirando de más por costumbre»—
y **no necesita fuente ni número**.

**El tablero contiene dos clases de cosa, y hay que separarlas:**

| | Qué es | Quién la elige |
|---|---|---|
| **Las señales del negocio** | Lo poco que el lector decide mirar para saber cómo va su actividad | **El lector.** El libro **no elige ninguna** y lo dice |
| **Lo que el método ya produce** | Lo que se salió del límite, lo que volvió y por qué, y lo que espera una decisión | Sale de los capítulos 15, 16 y 18. **No hay que inventarlo** |

### 6. Auditoría de «tres cifras» y de «pocas cifras»

**La pregunta 1 de la etapa O dice: «¿Qué tres cifras necesita ver cada semana para dormir
tranquilo?». Auditada, «tres» es una pregunta de concentración y NO una regla del método.**
Cuatro pruebas:

1. **Está bajo «Preguntas al fundador»**, junto a «¿cuál es su papel a partir de ahora, **dicho en
   una frase**?». Nadie ha convertido esa segunda en una regla de que los papeles se escriban en
   una sola frase.
2. **El índice dice «pocas cifras, bien elegidas»**, no «tres».
3. **El riesgo que la etapa O registra es el exceso** —«un tablero con tantos indicadores que
   nadie lo mira»—, no un número.
4. **`06-control-de-continuidad.md` lleva la lista de los números fijos del proyecto** —dos
   escalas, ocho posiciones, dieciocho herramientas, 24 horas y 7 días, 100 días, doce pasos,
   cuatro preguntas— y **«tres cifras» no está en ella**.

**Consecuencia para el capítulo:** puede **usar la pregunta como pregunta** —es buena y es del
método— y **tiene prohibido convertir «tres» en máximo, umbral, estándar o recomendación**. Lo que
enseña es la prueba del apartado 5, no una cantidad.

### 7. Los tres horizontes, y por qué el mensual no crea ninguna herramienta

El índice dice que se mira **cada día, cada semana y cada mes**; el catálogo reserva **solo dos**
herramientas, la 13 y la 14. **No hay contradicción, y conviene decir por qué:** la columna de
**entregables** del índice para el capítulo 19 dice «Modelos de informe diario y semanal» —dos—, y
«cada mes» aparece en la **idea central**, no en los entregables. **El índice nunca prometió una
herramienta mensual.**

**Cómo vive el horizonte mensual, entonces:** **como una relectura de lo que ya está escrito**, sin
documento nuevo. Y cada horizonte contesta una pregunta distinta:

| | Pregunta que contesta | De dónde sale |
|---|---|---|
| **El día** | ¿Ha pasado algo que no debería esperar a mañana? | **Herramienta 13** |
| **La semana** | ¿Algo está cambiando, y hay algo esperando una decisión mía? | **Herramienta 14** |
| **El mes** | ¿Lo que decidí sigue teniendo sentido? | **Ningún documento nuevo:** se releen los partes semanales y las hojas de bloque del capítulo 18, y se miran las revisiones que la columna 8 de la herramienta 12 tenga vencidas |

**Prohibido crear una herramienta 15 mensual:** la 15 y la 16 son las pruebas de ausencia del
capítulo 24, y la 18 es la evaluación anual del 25. **El catálogo no se toca y no se renumera.**

### 8. Ver no es decidir

Frontera estricta del capítulo, y **no es doctrina nueva**: en el vocabulario de **D-072** un
informe es un **control** —«la regla, el límite, la comprobación o la constancia»— y **los
controles no tienen autoridad**.

> **Un informe puede mostrar, resumir, comparar, señalar y dejar constancia. No puede autorizar,
> aprobar, rechazar, cambiar un permiso, ampliar una autonomía ni decidir una intervención.**

### 9. Fronteras, todas por escrito

| Par | Deslinde |
|---|---|
| **19 y 20** | **El 19 construye el instrumento; el 20, la conducta.** El 19 dice **qué mirar**; el 20, **cuándo intervenir y cuándo callarse**. El 19 **puede anunciar que esas reglas existen y tiene prohibido desarrollarlas** |
| **19 y 13 (herramienta 11)** | **Una alerta es una excepción al flujo; un informe es el flujo.** La alerta interrumpe **ahora**, tiene destinatario y destino temporal (herramienta 11); el informe llega **haya pasado algo o no**. **Regla falsable:** si algo puede esperar al parte del día, no era una alerta; si algo no puede esperar al parte, no es materia del tablero |
| **19 y 15 (herramienta 12)** | El tablero **muestra información producida dentro de los permisos** y **no redefine ninguno**. **No se copia la matriz dentro del informe**: se remite |
| **19 y 18** | El Plan por bloques registra **una transferencia**; el tablero da **la vista agregada**. **El tablero no es una colección de hojas de bloque:** resume, y **apunta** a la hoja cuando algo necesita explicación |
| **19 y 11** | El principio de **fuente de referencia** es del capítulo 11 y **no se reexplica**: se usa. **Una cifra sin origen identificable no entra al tablero**, y ese origen puede ser un registro, un sistema, una hoja, un libro contable o una persona responsable, según el dato |
| **19 y 22** | El tablero **libera atención** y **no prescribe qué hacer con ella** (**D-075**). Funciona para quien sigue trabajando, trabaja menos, supervisa, abre otra unidad, crea otro negocio, se retira en parte o del todo |
| **19 y 25** | El 19 es **visibilidad operativa recurrente**; el 25 es **continuidad en el tiempo**, con la herramienta 18. **Ni el informe semanal ni la relectura mensual son una evaluación anual** |
| **19 y 24** | El 19 mira **con la persona disponible**. El 24 mira **cuando se retira esa disponibilidad**. Sin 24 horas, sin 7 días |

### 10. Trazabilidad: el tablero apunta, no copia

**Se aplica la lección del campo 3 del Plan del capítulo 18, y se comprueba que aplica:** allí, dos
versiones del mismo límite hacen que una empiece a mentir en cuanto la otra cambie. **Aquí el
riesgo es el mismo con los datos**, y por eso:

> **Si una cifra, una excepción o una decisión pendiente necesita explicación, el informe apunta
> al registro donde está. No lo copia.**

**Lo que sí cambia respecto del capítulo 18, y hay que decirlo:** allí el puntero iba a **una fila
de una matriz que el propio lector escribió**; aquí puede ir a un registro que produce otra
persona o un sistema. **El principio es el mismo; el origen no siempre.**

### 11. Las dos rutas, una sola arquitectura

**El índice ya lo resuelve y no hace falta inventar nada:** *«para el lector B el tablero es **más
corto, no distinto**»*.

**Lo que cambia es de dónde viene la información, no qué se mira.** En la **ruta A** puede llegar
de otras personas, funciones o sistemas. En la **ruta B** una parte de la operación puede seguir
haciéndola el propio lector, y ahí la herramienta hace un trabajo extra que conviene nombrar:
**ayudarle a separar lo que mira para operar de lo que mira para supervisar lo que ya dejó de
depender de su intervención inmediata.** **Prohibido fingir que hay equipo cuando no lo hay**
(criterio 8 de diseño de las herramientas y **D-031**).

### 12. Herramienta 13 — Modelo de informe diario. **DISEÑADA, NO CREADA**

**Propósito vigente en el catálogo:** «Resumen operativo breve para quien ya no está en la
operación». **Auditado contra D-075, y hay que precisarlo al redactar la herramienta**, no aquí:
**«ya no está en la operación» no puede leerse como retiro**. Se escribirá **«para quien ya no
está en esa parte de la operación»**, y dónde esté esa atención —otra unidad, otro negocio,
estrategia, clientes, menos horas o descanso— **es elección del lector**. **La fila del catálogo
es un resumen de una línea y no se toca**; la precisión vive en el archivo de la herramienta.

| | |
|---|---|
| **Pregunta que contesta** | ¿Ha pasado algo que no debería esperar a mañana? |
| **Quién lo escribe** | **Ruta A:** quien tenga la operación ese día. **Ruta B:** usted mismo, y ahí está la clave de lectura del apartado 11 |
| **Quién lo revisa** | Quien ya no está en esa parte de la operación |
| **Cuándo** | Al cerrar el día |
| **Qué excluye** | El relato de lo que salió bien; el detalle de lo ya resuelto; cualquier cifra sin origen identificable |

**Cuatro campos, y son pocos a propósito:**

| | Campo |
|---|---|
| **1** | **La fecha, y quién lo escribe** |
| **2** | **Qué quedó sin hacer de lo previsto** — y si nada, **«nada»** |
| **3** | **Qué se salió del límite, y adónde volvió** — con el puntero al registro, no con su contenido |
| **4** | **Qué necesita una decisión antes de mañana** — y si nada, **«nada»** |

**Por qué no pregunta qué salió bien:** porque eso es lo que convierte un parte en un relato, y un
relato en algo que nadie lee. **Y los dos «nada» son evidencia**, igual que en el campo 5 del Plan
del capítulo 18. **Produce una acción o una constancia expresa de que no hace falta ninguna**
(criterio 4 de diseño).

**Ejemplo previsto:** **comercio minorista, ruta A** —sector no usado en ningún ejemplo de
herramienta—. **Prueba de dos páginas:** sobra; cabe en media. **Prueba de papel:** cuatro líneas
escritas a mano.

### 13. Herramienta 14 — Modelo de informe semanal. **DISEÑADA, NO CREADA**

**Propósito vigente:** «Vista de tendencia, excepciones y decisiones pendientes».

| | |
|---|---|
| **Pregunta que contesta** | ¿Algo está cambiando, y hay algo esperando una decisión mía? |
| **Quién lo escribe** | El mismo criterio que la 13 |
| **De dónde sale** | **De los partes diarios y de las hojas de bloque ya escritas.** No se recoge información nueva |
| **Qué excluye** | El detalle de lo que ya se resolvió el día que ocurrió |

**Cinco campos:**

| | Campo |
|---|---|
| **1** | **La semana, y quién lo escribe** |
| **2** | **Qué se repitió** — lo que apareció más de una vez en los partes diarios |
| **3** | **Qué cambió respecto de la semana anterior** — en palabras, no en porcentajes |
| **4** | **Qué sigue esperando una decisión, y desde cuándo** |
| **5** | **Qué se decide esta semana** — o se escribe que nada, y por qué |

**Ejemplo previsto:** **mantenimiento, ruta B** —sector no usado en ejemplos de herramienta, y
**ruta distinta de la del ejemplo de la 13**, como pide **D-031**—.

### 14. Prueba de que la 13 y la 14 no son el mismo formulario

**Si el informe semanal pudiera producirse apilando siete partes diarios, sobraría uno de los
dos.** No puede, y esta tabla dice por qué:

| | **Informe diario** | **Informe semanal** |
|---|---|---|
| **Pregunta** | ¿Ha pasado algo que no debería esperar a mañana? | ¿Algo está cambiando, y hay algo esperando una decisión mía? |
| **Horizonte** | Un día cerrado | Los días juntos |
| **Detalle** | Hechos sueltos | Comparación y acumulación |
| **Qué anomalía muestra** | **La excepción de hoy** | **La repetición, la tendencia y lo que se acumula sin resolverse** |
| **Qué decisión puede provocar** | **Puede no provocar ninguna**, y leerlo sin hacer nada es un resultado correcto | Mantener, corregir, revisar un límite, ampliar o reducir un bloque |
| **Qué NO contiene** | Tendencias, comparaciones ni decisiones pendientes | El detalle de lo que ya se resolvió el día que ocurrió |

**La diferencia en una línea: el parte diario pregunta por un hecho; el semanal, por un patrón.**
Un hecho se ve en un día y un patrón no.

### 15. Arquitectura narrativa — **nueve movimientos**

Se evaluó la progresión propuesta en el encargo y **se conserva casi entera, con dos cambios
justificados**: el horizonte mensual **entra en el movimiento 5** en lugar de crear un movimiento
propio —porque no produce documento—, y **«ver no es decidir» pasa al movimiento 9**, donde hace
de bisagra hacia el capítulo 20 en lugar de quedarse como una advertencia suelta.

| | Movimiento | Qué contesta | Qué introduce |
|---|---|---|---|
| **1** | **La tentación nueva: delegar y pedir saberlo todo** | ¿Qué hago ahora que ya no apruebo cada decisión? | El riesgo que la etapa O ya registra: la supervisión convertida en control informal |
| **2** | **Operar y ver no son lo mismo** | ¿Por qué no vale con seguir mirando lo de siempre? | La diferencia entre mirar para hacer y mirar para saber |
| **3** | **Qué merece entrar: la prueba de la señal** | ¿Cómo elijo? | **La prueba falsable**, y las dos clases de contenido del tablero |
| **4** | **Qué se queda fuera** | ¿Qué quito? | Lo que se mira por costumbre; lo que no tiene origen identificable |
| **5** | **El día, la semana y el mes** | ¿Cada cuánto miro qué? | Las tres preguntas distintas, y que **el mes no crea documento** |
| **6** | **El tablero apunta, no copia** | ¿Y si necesito el detalle? | Trazabilidad sin duplicación |
| **7** | **El parte del día** | ¿Qué necesito saber hoy? | **Herramienta 13** |
| **8** | **El parte de la semana** | ¿Qué necesito ver junto? | **Herramienta 14** |
| **9** | **Ver no es decidir, y lo que viene después** | ¿Y cuando algo de esto me preocupe? | La frontera con el 20 y el puente |

**Apertura.** Tipo a fijar en 3.18B, **con una condición**: no puede ser una pregunta heredada
contestada de frente —agotada en 13, 14, 15 y 16— ni la variante del 17 ni la del 18. **Dirección
recomendada:** abrir con **la petición que suena razonable y deshace lo anterior** —«mándame un
resumen de todo lo que pase»—, que es el material del movimiento 1 y un tipo no usado.

### 16. Mensaje central, acotado

**Se auditó la formulación propuesta en el encargo** —«usted no necesita volver a saberlo todo
para no perder el control»— y **«control» es correcto en el vocabulario vigente**: la Parte IV lo
define como **visibilidad, límites, capacidad de revisión y criterios de intervención**, y este
capítulo construye **la primera de las cuatro**. Pero la frase, sola, **puede leerse como que un
tablero conserva el control por sí mismo**, y eso no es cierto: conserva **una** de las cuatro
condiciones.

**Formulación adoptada, en dos frases y ninguna universal:**

> **Menos información no es menos visibilidad, si lo que queda deja ver un cambio, una excepción y
> una decisión que espera.**
>
> **Y volver a saberlo todo no es recuperar el control: es volver a la operación con otro
> nombre** —que es exactamente el riesgo que la etapa O registra—.

### 17. Lo que el capítulo tiene prohibido prometer

**Ninguna de estas, ni ninguna equivalente:** que el tablero **garantiza** el control · que **tres
cifras** bastan para cualquiera · que un parte diario sirve **sin adaptación** · que recibir
información **sustituye** la responsabilidad · que **más datos** dan mejores decisiones · que
**menos datos** dan mejores decisiones · que la automatización **elige sola** qué importa · que
una tecnología **decide qué debe ver** la persona propietaria · que un panel informático es
**requisito** · que existe una **frecuencia universal** · que el tablero **elimina** la necesidad
de volver al detalle · que **toda desviación** exige intervención.

### 18. Tecnología, plataforma y ADN Empresarial

**La tecnología puede preparar la información**; **qué merece atención sale del negocio y de
límites ya escritos**, no de un sistema. **Cero marca, cero proveedor, cero arquitectura técnica,
cero agente, cero Gemelo de IA como solución nueva.**

**Y un permiso vigente que se deja deliberadamente sin usar, para que conste.**
`editorial/16-libro-metodo-y-plataforma.md` §5.2 **autoriza al capítulo 19 una (1) frase de
categoría C** —mención identificable de la plataforma— y categoría B. **El encargo de esta etapa
fija cero plataforma, y se diseña con cero.** No hay contradicción: **la tabla fija un techo, no un
mínimo**, y escribir cero cumple. **Queda anotado que el permiso existe y no se consume**, como se
hizo con las previsiones de sector.

**ADN Empresarial:** conexión natural y breve, si cabe —**el tablero no contiene el ADN; muestra
algunas señales de cómo está funcionando lo ya transferido**—. **No se reexplican las ocho capas**
y **no se convierte el tablero en repositorio de nada**.

### 19. Caso: **NO se crea C-14**

**Los trece existentes se revisaron.** El capítulo enseña **una elección** —qué señales— y **una
distinción** —día frente a semana—, no una trayectoria: **una microescena basta**, y el precedente
está en los capítulos 16 y 17. **C-13 es reciente** (capítulo 18) y crear otro caso formal dos
capítulos seguidos no aporta mecanismo.

**Lo que sí habrá, porque el catálogo lo exige** (criterio 7 de diseño): **un ejemplo breve y
ficticio en cada herramienta, de sectores distintos** —comercio minorista en la 13, mantenimiento
en la 14—. **Esos ejemplos no son casos y no se registran como C-14 ni C-15**, igual que los
ejemplos de las herramientas 9 a 12.

**Casos: siguen en 13. Reparto intacto: 7 ruta A / 6 ruta B y 7 mujeres / 6 hombres.**

### 20. Puente al capítulo 20

El capítulo cierra cambiando la pregunta, **y no la contesta**:

> *Ya veo lo suficiente. **¿Y qué hago cuando lo que veo no me gusta?***

### 21. Extensión, clasificación y controles

**Objetivo: 2.000 palabras. Tope por D-030: 2.300.** Es alcanzable porque **las herramientas 13 y
14 son archivos del catálogo con vida propia**: el capítulo **muestra su forma y su uso**, no sus
instrucciones completas —igual que hicieron el 13 con las herramientas 10 y 11 y el 15 con la
12—. **Reparto previsto:** movimientos 7 y 8, unas 250 palabras cada uno; los otros siete, entre
170 y 220.

| Clase | Qué hay | Necesita fuente |
|---|---|---|
| **A — doctrina del método** | La definición de tablero; la prueba de la señal; las tres preguntas de los tres horizontes; «ver no es decidir»; el tablero apunta y no copia | **No** |
| **B — instrucción práctica** | Los cuatro campos de la 13 y los cinco de la 14 | **No** |
| **C — afirmación factual externa** | **Ninguna prevista** | — |
| **D — afirmación jurídica** | **Ninguna** | — |

**Barrido de universalidades sobre esta propia arquitectura**, hecho antes de cerrarla: lo que
queda son **prohibiciones del método y negaciones** —«el libro no elige ninguna», «prohibido
convertir tres en máximo», «ninguna sostiene una frase que este capítulo necesite»— e
**instrucciones**. **Se retiraron las predicciones**: no se afirma que pocas señales funcionen
mejor, ni que un tablero corto se lea más, ni que una cadencia sea superior a otra. **Y las
palabras «cada día», «cada semana» y «cada mes» se usan como horizontes de lectura, nunca como
obligación de frecuencia para una señal concreta.**

**Antropomorfismo:** la arquitectura no atribuye a un informe ni a un sistema los verbos *decidir,
elegir, autorizar, aprobar ni juzgar*. **Un informe muestra, resume, compara, señala y deja
constancia**; un sistema ya autorizado **puede preparar** la información.

### 22. Señal de paso a 3.18B: las trece contestadas

**1.** ¿Qué pregunta recibe del 18? *«Entonces, ¿qué miro?»* — apartado 3. **2.** ¿Qué contesta el
19? **Qué mirar** — apartados 4 y 5. **3.** ¿Qué queda para el 20? **Cuándo intervenir** —
apartado 9. **4.** ¿Qué es el tablero? — apartado 4. **5.** ¿Qué no es? — apartado 4. **6.**
¿Diario frente a semanal? — apartado 14, con tabla. **7.** ¿El mensual? — apartado 7: **relectura,
sin herramienta nueva**. **8.** ¿Trazabilidad? — apartado 10. **9.** ¿Las dos rutas? — apartado
11: **más corto, no distinto**. **10.** ¿Investigación? — apartado 2: **cero**. **11.** ¿La
contradicción D→O? — apartado 1: **no la hay; queda V-72 registrada**. **12.** ¿Sin inventar KPIs,
umbrales ni frecuencias? — apartados 5, 6 y 17. **13.** ¿El puente? — apartado 20.

**Ninguna queda abierta.**
