# 08 — Niveles de autonomía y arquitectura conceptual

**Etapa:** 1 — Fundamentos
**Estado:** marco aprobado en el encargo, desarrollado aquí para uso editorial.

Este documento fija el vocabulario técnico del libro. Los capítulos 11 a 16 y 19 deben
usar estos términos con el significado exacto que aquí se define. La correspondencia con
los capítulos, en el apartado 5, refleja el orden de la Parte III vigente desde D-017. Cualquier desviación se
registra en `editorial/06-control-de-continuidad.md`.

---

## 1. La escala de siete niveles

La escala describe **qué se permite hacer a la tecnología**, no qué sabe hacer. Es una
escala de permisos, no de capacidad. Esa distinción debe explicarse al lector en el
capítulo 12, porque es la que le devuelve el control: el nivel lo decide la empresa.

### Nivel 0 — Operación dependiente y manual

Información dispersa entre papel, hojas de cálculo, correos y memoria. Procesos manuales.
Conocimiento concentrado en pocas personas. Las decisiones esperan al fundador.

*Señal de que se está aquí:* para responder una pregunta sobre el negocio hay que
preguntarle a alguien.

### Nivel 1 — Organización y digitalización

Los datos, documentos, funciones y procesos se ordenan. Se define una fuente única para
cada dato importante. Hay responsables y controles básicos.

*Señal:* la misma pregunta se responde consultando un sitio, y dos personas obtienen la
misma respuesta.

**Advertencia editorial obligatoria:** digitalizar no es inteligencia artificial. El
libro debe repetirlo aquí y en el capítulo 11, porque es la confusión más frecuente y la
más cara.

### Nivel 2 — Inteligencia artificial en modo sombra

El sistema observa, clasifica, resume, compara y registra. Aprende de las decisiones
humanas. No recomienda decisiones sensibles y no ejecuta ninguna acción.

*Propósito real del nivel:* no es entrenar a la máquina, es **ganarse la confianza del
fundador con evidencia**. Al final del periodo debe poder mostrarse una comparación entre
lo que el sistema señaló y lo que las personas decidieron.

*Señal:* existe un registro comparado y alguien lo ha revisado.

### Nivel 3 — Asistente informativo

Prepara informes, organiza pendientes, genera recordatorios, presenta indicadores,
detecta diferencias y emite alertas. No propone qué hacer.

*Riesgo propio:* exceso de alertas. Si el equipo aprende a ignorarlas, el nivel ha
fracasado aunque funcione.

### Nivel 4 — Asistente de recomendaciones

Propone acciones, explica sus razones, presenta la evidencia en la que se apoya y señala
su grado de incertidumbre. Toda recomendación requiere aprobación humana.

*Condición innegociable:* una recomendación que no puede explicarse no se acepta. Si la
herramienta no muestra en qué se basa, se queda en el nivel 3.

### Nivel 5 — Ejecución limitada

Ejecuta únicamente tareas de bajo riesgo, dentro de reglas autorizadas previamente por
escrito. Mantiene registro de todo lo que hace. Ante cualquier excepción, se detiene y
pide aprobación. Debe existir un modo de detener la automatización de forma inmediata.

*Criterio para clasificar una tarea como de bajo riesgo:* es reversible, su impacto
económico está acotado por escrito, no afecta a personas y no compromete a la empresa
frente a un tercero.

### Nivel 6 — Mano derecha digital supervisada

Coordina tareas ordinarias, prepara decisiones para que una persona las tome, da
seguimiento, informa de excepciones, escala los asuntos sensibles y mantiene informado al
propietario. Permanece bajo supervisión humana.

**El nivel 6 es el techo del libro.** No existe un nivel 7. La autonomía absoluta no se
propone en ningún capítulo, en ningún ejemplo y en ningún material derivado.

---

## 2. Reglas de la escala

1. Los niveles se recorren en orden. No se salta del 1 al 4.
2. El nivel se asigna **por tipo de tarea**, no a la empresa entera. Una misma
   organización puede estar en nivel 5 para conciliar documentos y en nivel 2 para todo
   lo que toque a personas.
3. Se puede retroceder. Retroceder de nivel es una decisión legítima y prevista, no un
   fracaso.
4. Cada nivel exige, antes de activarse: responsable con nombre, permisos definidos,
   registro de actividad y procedimiento escrito de detención.
5. Ningún nivel elimina la responsabilidad humana sobre el resultado.

---

## 3. Decisiones que deben conservar autorización humana

El libro sostiene que las decisiones siguientes deben permanecer bajo autorización de una
persona, con independencia del nivel de autonomía alcanzado en otras áreas:

- Pagos significativos, según el umbral que fije cada empresa.
- Endeudamiento y garantías.
- Firma de contratos.
- Contratación de personal.
- Despido y terminación de relaciones laborales.
- Cambios salariales.
- Acciones disciplinarias.
- Procesos legales y su estrategia.
- Manejo de información confidencial y de datos personales.
- Cambio de proveedores críticos.
- Decisiones que afecten a la seguridad física de personas.
- Excepciones fuera de los límites aprobados.
- Decisiones estratégicas.
- Acciones irreversibles.
- Operaciones con posible conflicto de interés.
- Cambios de propiedad.
- Distribución de utilidades.
- Decisiones fiscales o regulatorias.

**Advertencia obligatoria en el libro, junto a esta lista:**

> Esta lista es un punto de partida para la conversación, no una norma universal. Lo que
> puede delegarse, lo que debe aprobarse por escrito y lo que la ley reserva a
> determinadas personas cambia según el país, la forma jurídica de la empresa y el
> sector. Cada organización debe fijar sus propios límites con profesionales competentes
> en su jurisdicción.

La lista no debe presentarse nunca como asesoría legal. Se enuncia como criterio de
prudencia y se remite siempre a revisión profesional.

---

## 4. Arquitectura conceptual

Descripción de los componentes que puede tener una solución completa, en lenguaje
comprensible para un lector sin formación técnica. El libro los presenta como **piezas
que cumplen una función**, nunca como una lista de compra.

| Componente | Para qué sirve, en una frase |
|---|---|
| Sistema central de información confiable | Que cada dato importante tenga un solo sitio donde consultarse. |
| Procesos digitalizados | Que lo que hoy se hace de memoria deje rastro. |
| Repositorio documental | Que los documentos estén donde alguien más pueda encontrarlos. |
| Manual operativo | Que se sepa cómo se hace cada cosa. |
| Manual de criterio del fundador | Que se sepa por qué se hace así. |
| Permisos por responsabilidad | Que cada persona vea y pueda hacer lo que le corresponde. |
| Registros de auditoría | Que quede constancia de quién hizo qué y cuándo. |
| Tableros de indicadores | Que el estado del negocio se vea sin preguntar. |
| Alertas | Que lo importante busque a la persona, y no al revés. |
| Administración de excepciones | Que lo fuera de lo normal se registre, se autorice y caduque. |
| Agente privado de inteligencia artificial | Que alguien mire todo el tiempo lo que ninguna persona puede mirar todo el tiempo. |
| Canales seguros de consulta y de aprobación | Que preguntar y autorizar sea fácil y quede registrado. |
| Resumen diario, informe semanal, informe mensual | Que la supervisión tenga un ritmo en lugar de depender del ánimo. |
| Copias de seguridad y planes de continuidad | Que un fallo técnico no se convierta en un fallo del negocio. |
| Protección de datos | Que la información de personas y clientes se trate como corresponde. |
| Revisión humana | Que siempre haya alguien que responda por el resultado. |

### Regla sobre menciones de productos

Las herramientas concretas se mencionan solo como ejemplo, siempre acompañadas de la
categoría a la que pertenecen y de al menos una alternativa. El libro no recomienda
marcas, no incluye enlaces de afiliación y no describe configuraciones de un producto
determinado. Motivo doble: el libro debe seguir siendo útil dentro de cinco años, y no
debe convertirse en publicidad.

Toda mención de producto se registra en `editorial/05-control-de-fuentes.md` para poder
revisarla en bloque antes de publicar.

---

## 5. Correspondencia entre niveles, etapas y capítulos

Actualizada el 2026-09-06 tras el reordenamiento de la Parte III (D-017).

| Nivel | Etapa del método | Capítulos |
|---|---|---|
| 0 | Antesala de L | 1–5 |
| 1 | E y G | 6–10, 11 |
| 2 | A | 12, 13 |
| 3 | A | 13 |
| 4 | A | 14 |
| 5 | A y D | 15 |
| 6 | D y O | 15, 18, 19 |
| Transversal: seguridad, privacidad y auditoría | Todas | 16 |
