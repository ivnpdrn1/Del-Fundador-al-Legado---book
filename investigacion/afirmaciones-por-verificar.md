# Afirmaciones por verificar

Registro de toda afirmación que necesita respaldo y todavía no lo tiene. Cada entrada
corresponde a una marca `[POR VERIFICAR]` en el texto de trabajo.

**Regla absoluta: ninguna entrada abierta puede sobrevivir a la Etapa 4.** Al cerrar la
revisión integral, cada línea de este archivo debe estar resuelta como *verificada*,
*reformulada* o *suprimida*.

**Estado a 2026-09-06: 0 afirmaciones abiertas. 0 marcas `[POR VERIFICAR]` en el
manuscrito.**

---

## 1. Afirmaciones del manuscrito

*Sin entradas abiertas.* Las ocho afirmaciones con fuente de la introducción y del
capítulo 1 están cerradas y registradas en `editorial/05-control-de-fuentes.md`,
apartado 3.

| ID | Afirmación | Cap. | Por qué necesita fuente | Pregunta asociada | Estado |
|---|---|---|---|---|---|
| — | — | — | — | — | — |

**Estados posibles:** `abierta` · `verificada` · `reformulada sin cifra` · `suprimida`

### 1.1 Afirmaciones que se decidió no escribir

Se registran porque la tentación volverá en capítulos posteriores y conviene que la
decisión conste.

| Afirmación descartada | Dónde se habría usado | Motivo | Estado |
|---|---|---|---|
| Porcentajes de supervivencia de empresas familiares entre generaciones. | Intro, 21 | Fuente primaria no legible; problemas metodológicos conocidos. D-016. | `suprimida` |
| Una cifra mundial única de proporción de empresas familiares. | Intro | No existe cifra comparable entre países: más de 90 definiciones (F-001). | `reformulada sin cifra`, sustituida por dos cifras con definición y ámbito declarados. |
| Proporción de empresas familiares en América Latina. | Intro | No se localizó estadística regional. Vacío declarado en el texto. | `suprimida`, con el vacío dicho al lector. |

## 2. Asuntos abiertos del proyecto

Cuestiones que no son afirmaciones del manuscrito, pero que están sin resolver y afectan
a decisiones del proyecto. Se registran aquí para que no se pierdan.

| ID | Asunto | Origen | Por qué importa | Estado |
|---|---|---|---|---|
| A-01 | Disponibilidad del título *Del Fundador al Legado*: comprobar que no colisiona con un libro ya publicado en español ni con una marca registrada en los mercados previstos. | `00-concepto-editorial.md` §6 | Un conflicto obligaría a usar uno de los cinco títulos de respaldo. Cuanto antes se sepa, menor el coste. | **abierto.** Sube de prioridad: con D-014 los mercados están definidos y la comprobación ya puede hacerse. |
| A-02 | Obligaciones legales, contractuales y de protección de datos derivadas de prestar los servicios de los niveles 4 a 8 del modelo de negocio. | `10-modelo-de-negocio.md` §3, problema 4 | No afecta al libro, pero sí a cualquier decisión comercial. Requiere profesionales de la jurisdicción. | abierto |
| A-03 | Fiabilidad de las cifras de continuidad entre generaciones que circulan sobre empresas familiares. | `plan-de-investigacion.md` Q-02 | Son las cifras más citadas del sector y las de origen más dudoso. | **CERRADO 2026-09-06.** No se localizó fuente primaria legible. Ninguna cifra generacional entra en el libro (D-016). |
| A-04 | Versión vigente de los marcos de continuidad, seguridad de la información y gestión de riesgos de inteligencia artificial que se citen. | `plan-de-investigacion.md` Q-03, Q-04 | Citar una versión derogada dañaría la credibilidad del capítulo 16. | **CERRADO en parte 2026-09-06.** Comprobadas y vigentes: ISO 22301:2019, ISO 31000:2018 (confirmada en 2023), ISO/IEC 42001:2023, NIST AI RMF 1.0, OCDE revisada en 2024, Reglamento (UE) 2024/1689. Se recomprueba en la Etapa 5 (V-13). |
| A-05 | Definición de "empresa familiar" que se adoptará en el libro, y su compatibilidad con la de las fuentes que se citen. | `plan-de-investigacion.md` Q-01 | Sin una definición explícita, cualquier cifra sobre el sector es ambigua. | **CERRADO 2026-09-06.** Se adopta la definición del grupo de expertos de la Comisión Europea (D-015), enunciada en lenguaje llano en la introducción y en el glosario. Cada cifra citada declara su propia definición. |
| A-06 | Mercados y jurisdicciones de publicación previstos. | Alcance editorial | Determina qué advertencias legales deben incluirse y qué ámbitos geográficos deben cubrir los datos. | **CERRADO 2026-09-06 por decisión del autor.** Español internacional, lector hispanohablante internacional, distribución principal por Amazon KDP. Enfoque jurisdiccionalmente neutral. Desarrollado en `editorial/12-alcance-jurisdiccional.md` (D-014). |
| A-07 | Ausencia de estadística oficial sobre empresas familiares en América Latina. | Q-01, 2026-09-06 | El libro se dirige de forma destacada a lectores latinoamericanos y no puede ofrecerles un dato de su región. Se declara el vacío, pero convendría seguir buscando en institutos nacionales de estadística. | **abierto.** Prioridad baja: el argumento no depende de la cifra. |
| A-08 | Accesibilidad de las normas ISO para el lector. | Q-03, 2026-09-06 | ISO 22301 e ISO 31000 son de pago. El libro no puede suponer que el lector las adquiera, y debe decirlo al citarlas. | **abierto.** Se resuelve al redactar los capítulos 4 y 16. |

## 3. Procedimiento

1. Al escribir una afirmación sin fuente, se marca `[POR VERIFICAR]` en el texto y se
   añade una fila en el apartado 1 en el mismo bloque de trabajo.
2. Al verificarla, se registra la fuente en `fuentes-verificadas.md`, se anota su ID aquí
   y el estado pasa a `verificada`.
3. Si tras una búsqueda razonable no aparece fuente sólida, hay dos salidas, ambas
   legítimas: reformular sin cifra o suprimir. **No hay una tercera.** Cuando se aplique,
   se anota en el apartado 1.1 para que la decisión conste y no se reabra.
4. Los asuntos del apartado 2 se revisan al cerrar cada etapa.
