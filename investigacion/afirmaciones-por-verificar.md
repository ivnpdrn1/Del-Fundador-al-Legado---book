# Afirmaciones por verificar

Registro de toda afirmación que necesita respaldo y todavía no lo tiene. Cada entrada
corresponde a una marca `[POR VERIFICAR]` en el texto de trabajo.

**Regla absoluta: ninguna entrada abierta puede sobrevivir a la Etapa 4.** Al cerrar la
revisión integral, cada línea de este archivo debe estar resuelta como *verificada*,
*reformulada* o *suprimida*.

---

## 1. Afirmaciones del manuscrito

*Vacío. No existe manuscrito.*

| ID | Afirmación | Cap. | Por qué necesita fuente | Pregunta asociada | Estado |
|---|---|---|---|---|---|
| — | — | — | — | — | — |

**Estados posibles:** `abierta` · `verificada` · `reformulada sin cifra` · `suprimida`

## 2. Asuntos abiertos del proyecto

Cuestiones que no son afirmaciones del manuscrito, pero que están sin resolver y afectan
a decisiones del proyecto. Se registran aquí para que no se pierdan.

| ID | Asunto | Origen | Por qué importa | Estado |
|---|---|---|---|---|
| A-01 | Disponibilidad del título *Del Fundador al Legado*: comprobar que no colisiona con un libro ya publicado en español ni con una marca registrada en los mercados previstos. | `00-concepto-editorial.md` §6 | Un conflicto obligaría a usar uno de los cinco títulos de respaldo. Cuanto antes se sepa, menor el coste. | abierto |
| A-02 | Obligaciones legales, contractuales y de protección de datos derivadas de prestar los servicios de los niveles 4 a 8 del modelo de negocio. | `10-modelo-de-negocio.md` §3, problema 4 | No afecta al libro, pero sí a cualquier decisión comercial. Requiere profesionales de la jurisdicción. | abierto |
| A-03 | Fiabilidad de las cifras de continuidad entre generaciones que circulan sobre empresas familiares. | `plan-de-investigacion.md` Q-02 | Son las cifras más citadas del sector y las de origen más dudoso. Si no se localiza el estudio primario, no se usan. | abierto |
| A-04 | Versión vigente de los marcos de continuidad, seguridad de la información y gestión de riesgos de inteligencia artificial que se citen. | `plan-de-investigacion.md` Q-03, Q-04 | Citar una versión derogada dañaría la credibilidad del capítulo 16. | abierto |
| A-05 | Definición de "empresa familiar" que se adoptará en el libro, y su compatibilidad con la de las fuentes que se citen. | `plan-de-investigacion.md` Q-01 | Sin una definición explícita, cualquier cifra sobre el sector es ambigua. | abierto |
| A-06 | Mercados y jurisdicciones de publicación previstos. | Alcance editorial | Determina qué advertencias legales deben incluirse y qué ámbitos geográficos deben cubrir los datos. | abierto — requiere decisión del autor |

## 3. Procedimiento

1. Al escribir una afirmación sin fuente, se marca `[POR VERIFICAR]` en el texto y se
   añade una fila en el apartado 1 en el mismo bloque de trabajo.
2. Al verificarla, se registra la fuente en `fuentes-verificadas.md`, se anota su ID aquí
   y el estado pasa a `verificada`.
3. Si tras una búsqueda razonable no aparece fuente sólida, hay dos salidas, ambas
   legítimas: reformular sin cifra o suprimir. **No hay una tercera.**
4. Los asuntos del apartado 2 se revisan al cerrar cada etapa.
