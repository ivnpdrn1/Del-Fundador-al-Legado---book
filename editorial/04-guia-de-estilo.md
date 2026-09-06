# 04 — Guía de estilo

**Etapa:** 1 — Fundamentos
**Estado:** vigente. Aplica a todo el manuscrito y a todos los materiales del proyecto.

---

## 1. Lengua

- **Español internacional.** Vocabulario comprensible en España y en América sin marcas
  regionales fuertes.
- **Tratamiento: usted.** El lector tiene entre cincuenta y setenta y cinco años y se le
  habla con respeto. El tuteo se descarta en todo el libro.
- Se evitan: "coger" en su acepción peninsular, "platicar", "chévere", "vale", "guay",
  "carro" frente a "coche" y cualquier término cuyo significado cambie según el país.
  Cuando exista duda, se elige la palabra neutra: "automóvil", "conversar", "de acuerdo".
- Números: se escriben con letras del cero al diez y con cifras a partir de once, salvo
  en tablas. Separador de miles: punto. Separador decimal: coma.
- Moneda: **no se usan cifras monetarias concretas** en ningún ejemplo. Se escribe
  "un monto equivalente a dos meses de compras" o "una cifra que la empresa consideraría
  significativa". Motivo doble: evita la caducidad y evita cualquier dato que pudiera
  vincularse a una organización real.
- Fechas en los documentos del repositorio: formato AAAA-MM-DD.

## 2. Tono

Cálido, serio y respetuoso. La regla de comprobación es la siguiente: **si el fundador
leyera el párrafo en voz alta delante de su equipo, ¿se sentiría bien tratado?** Si la
respuesta es no, se reescribe.

**Se escribe así:**

- Se reconoce el mérito antes de señalar el problema.
- Se explica el porqué antes de pedir una acción.
- Se admite la dificultad en lugar de minimizarla.
- Se ofrece siempre un primer paso pequeño.
- Se dice lo que puede salir mal.

**No se escribe así:**

- "El fundador debe entender que…" (condescendencia).
- "Si no actúa ahora, lo perderá todo" (alarmismo).
- "Es muy sencillo, solo tiene que…" (minimización).
- "Las empresas modernas ya no funcionan así" (juicio generacional).
- "La inteligencia artificial se encargará de eso" (magia).

## 3. Estructura de capítulo

Cada capítulo incluye, cuando sea pertinente, y en este orden:

1. Apertura narrativa o situación reconocible. Entre 150 y 300 palabras.
2. Explicación sencilla del problema.
3. El principio central, enunciado en una frase destacada.
4. Caso ficticio o compuesto, de un sector distinto al del capítulo anterior.
5. Riesgos frecuentes.
6. Errores que deben evitarse.
7. Acciones prácticas.
8. Preguntas para el fundador. Entre cuatro y seis, todas respondibles.
9. Una herramienta, lista o ejercicio.
10. Indicadores de progreso.
11. Señales que permiten avanzar a la etapa siguiente.
12. Cierre de una o dos frases conectado con el capítulo siguiente.

No todos los apartados aparecen en todos los capítulos, pero 3, 7, 8 y 12 son
obligatorios en los veinticinco.

## 4. Párrafos y frases

- Párrafos de tres a seis líneas. Un párrafo de más de ocho líneas se parte.
- Frases de menos de treinta palabras como norma general.
- Una idea por párrafo.
- Las listas no sustituyen a la explicación. Toda lista de más de cinco elementos va
  precedida de un párrafo que dice qué se está listando y para qué sirve.
- No se encadenan dos listas sin texto entre ellas.
- La voz activa es la norma. La pasiva se admite cuando el sujeto es irrelevante.

## 5. Vocabulario del proyecto

**Formas para designar al lector.** Deben alternarse, sin usar siempre la misma:
fundador, fundadora, propietario, propietaria, dirigente, persona al frente de la
empresa, líder empresarial, quien construyó la empresa.

**Género.** No se emplea el masculino genérico de forma sistemática ni se recurre a
desdoblamientos constantes, que entorpecen la lectura. Se alterna deliberadamente entre
formas masculinas y femeninas a lo largo del libro y se prefieren fórmulas neutras
—"la persona al frente de la empresa", "quien decide", "la dirección"— cuando la frase lo
permita. La alternancia de género en los casos se controla en
`revision/control-de-casos.md`.

**Términos técnicos.** Todo término técnico se define en una frase la primera vez que
aparece y se registra en `editorial/glosario.md`. Si un término no puede definirse en una
frase comprensible, no se usa.

**Anglicismos.** Se evitan cuando existe equivalente en español:

| No usar | Usar |
|---|---|
| workflow | flujo de trabajo |
| dashboard | tablero de indicadores |
| compliance | cumplimiento |
| know-how | conocimiento práctico |
| stakeholder | parte interesada |
| onboarding | incorporación |
| deadline | fecha límite |
| feedback | retroalimentación, respuesta, observaciones |
| core business | actividad principal |
| backup | copia de seguridad |
| prompt | instrucción |
| machine learning | aprendizaje automático |

Se admiten sin traducir, por ser de uso común y sin equivalente asentado: software,
hardware, internet, correo electrónico. "Software" se prefiere a "programa informático"
cuando la repetición lo exija.

**Términos con significado fijo en este libro.** No se usan con otro sentido:

| Término | Significado exacto |
|---|---|
| Modo sombra | Nivel 2. El sistema observa y registra, no recomienda ni ejecuta. |
| Nivel de autonomía | Permiso concedido a la tecnología, del 0 al 6. Nunca capacidad. |
| Excepción | Desviación autorizada de la regla, con motivo, vigencia y revisor. |
| Criterio | El porqué de una decisión, distinto del procedimiento. |
| Dependencia | Grado en que la operación requiere a una persona concreta. |
| Delegar | Transferir decisión y autoridad, con límites y evidencia. No es repartir tareas. |
| Supervisar | Vigilar el resultado sin intervenir en la ejecución. |
| Digitalizar | Pasar información y procesos a soporte electrónico. **No es** inteligencia artificial. |

## 6. Prohibiciones de contenido

Además de las reglas de confidencialidad de `editorial/09-reglas-de-casos-ficticios.md`:

- No se prometen resultados absolutos ni cifras de mejora.
- No se presenta la inteligencia artificial como infalible, autónoma ni mágica.
- No se recomienda automatizar antes de haber ordenado datos y procesos.
- No se confunde digitalización con inteligencia artificial.
- No se confunde supervisión con control absoluto.
- No se supone que el sucesor deba ser un hijo o una hija.
- No se supone que todas las familias funcionen igual.
- No se emiten juicios sobre modelos familiares, religiosos ni culturales.
- No se presenta ninguna afirmación legal, fiscal o laboral como universal.
- No se citan cifras ni estudios sin fuente verificada y consultada.
- No se rellena extensión con repeticiones.

## 7. Casos y ejemplos

- Todos los casos son ficticios o composiciones educativas.
- Cada caso se registra en `revision/control-de-casos.md` antes de escribirse.
- Extensión de un caso: entre 150 y 400 palabras. Un caso más largo se convierte en
  biografía y aumenta el riesgo de parecerse a alguien real.
- No se repite el mismo personaje en más de dos capítulos.
- No se repite sector en capítulos consecutivos.
- Se alterna el género de las personas protagonistas.
- Cada caso enseña un único punto, enunciado explícitamente al cerrarlo.

## 8. Citas, datos y afirmaciones

- Toda cifra, estudio o afirmación factual lleva fuente consultada directamente y
  registrada en `investigacion/fuentes-verificadas.md`.
- Una afirmación sin fuente verificada se marca en el texto de trabajo con
  `[POR VERIFICAR]` y se anota en `investigacion/afirmaciones-por-verificar.md`.
  Ningún `[POR VERIFICAR]` puede sobrevivir a la Etapa 4.
- Se distinguen explícitamente cuatro tipos de enunciado y se escriben de forma
  reconocible:
  - **Hecho verificado:** "Según [fuente], …"
  - **Inferencia del autor:** "De esto se sigue que…"
  - **Recomendación:** "Recomiendo que…"
  - **Propuesta propia del libro:** "En este libro llamamos…"
- No se atribuyen frases, estudios ni datos a autores o instituciones sin comprobación
  directa.

## 9. Formato de los archivos

- Markdown, codificación UTF-8, saltos de línea LF.
- Un encabezado `#` de nivel 1 por archivo.
- Líneas de texto de hasta 100 caracteres, para que los diff de Git sean legibles.
- Comillas españolas o inglesas dobles, de forma coherente; no se mezclan.
- Rayas de diálogo y guiones largos con el signo correspondiente, no con dos guiones.
- Los nombres de archivo van en minúsculas, sin tildes ni eñes, separados por guiones.

## 10. Comprobación antes de dar por bueno un capítulo

Diecisiete preguntas. Un capítulo que falle en cualquiera vuelve a revisión.

1. ¿Aporta una idea que no esté ya en otro capítulo?
2. ¿Se entiende sin conocimientos tecnológicos?
3. ¿Respeta la experiencia del fundador en todo momento?
4. ¿Ofrece algo que el lector pueda hacer esta semana?
5. ¿Evita promesas irreales?
6. ¿Mantiene la supervisión humana en todos los ejemplos?
7. ¿Protege la información sensible del lector?
8. ¿Es imposible identificar una empresa real a partir del texto?
9. ¿Distingue hechos, ejemplos, inferencias y recomendaciones?
10. ¿Enlaza con el capítulo anterior y anuncia el siguiente?
11. ¿Contradice algo dicho antes?
12. ¿Repite argumentos ya expuestos?
13. ¿Usa los términos fijos con su significado exacto?
14. ¿Toda afirmación factual tiene fuente consultada?
15. ¿Presenta los límites de la inteligencia artificial?
16. ¿Está libre de publicidad y de recomendaciones de marca?
17. ¿Deja al lector un paso más cerca, y no solo más preocupado?
