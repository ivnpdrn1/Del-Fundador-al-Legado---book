# 09 — Reglas de casos ficticios y evaluación de riesgo de identificación

**Etapa:** 1 — Fundamentos
**Estado:** vigente y obligatorio. Ninguna excepción sin autorización expresa del autor.

Este documento protege a terceros y protege al proyecto. Es la norma de mayor rango del
repositorio: prevalece sobre cualquier consideración narrativa. Si un ejemplo mejora el
libro pero incumple una regla de este documento, el ejemplo se descarta.

---

## 1. Principio

Todos los casos del libro son **ficticios o composiciones educativas** construidas a
partir de patrones frecuentes en muchas organizaciones distintas. Ningún caso describe a
una empresa o a una persona determinada. El libro no es el resultado del análisis de una
compañía concreta y no debe presentarse nunca como tal, ni en el texto, ni en la
contraportada, ni en material promocional, ni en entrevistas.

## 2. Reglas obligatorias

### 2.1 Sectores

1. Existe una **lista de sectores excluidos** por decisión editorial. Esa lista se
   mantiene fuera del repositorio, porque enumerarla en un archivo público señalaría
   precisamente aquello que se pretende no señalar. El autor la conserva y la aplica al
   revisar.
2. Ningún caso emplea procesos, vocabulario, unidades de medida, turnos, roles ni
   controles característicos de un sector excluido.
3. Los casos se distribuyen entre los sectores admitidos del apartado 3. Ningún sector
   aparece en más de tres capítulos.

### 2.2 Personas

4. Todos los nombres son inventados y no coinciden con personas conocidas del entorno del
   autor.
5. Se alterna el género de las personas protagonistas a lo largo del libro; el reparto
   final debe quedar equilibrado.
6. No se especifica la edad exacta. Se usan franjas amplias: "cerca de los sesenta",
   "después de treinta años al frente".
7. No se describen composiciones familiares concretas y reconocibles. Se dice "un
   familiar", "una persona de su confianza", no "su hija menor, que estudió contabilidad".
8. Ningún personaje concentra más de tres rasgos distintivos. Un personaje con cinco o
   seis rasgos deja de ser un tipo y empieza a ser un retrato.
9. Ningún personaje aparece en más de dos capítulos, y nunca con una historia continuada
   que forme una biografía.

### 2.3 Lugares y cifras

10. No se mencionan ciudades, regiones, países ni referencias geográficas identificables.
    Se escribe "una ciudad de tamaño medio", "una zona industrial".
11. No se mencionan cifras financieras concretas: ni facturación, ni plantilla exacta, ni
    montos, ni porcentajes de crecimiento. Se usan magnitudes relativas.
12. No se mencionan fechas concretas ni periodos históricos que permitan situar un hecho.
13. No se describen incidentes específicos con detalles que los hagan únicos. Un incidente
    se cuenta por su mecanismo, no por sus particularidades.

### 2.4 Origen del material

14. No se emplea información privada, conversaciones previas, documentos internos ni
    datos de ninguna organización real conocida por el autor.
15. No se reproducen decisiones reales de ninguna propietaria, propietario o
    administrador.
16. Los casos se construyen desde el patrón hacia el ejemplo: primero se define el
    mecanismo que se quiere enseñar, después se inventa la situación mínima que lo ilustra.
    Nunca al revés.

### 2.5 Registro

17. Todo caso se registra en `revision/control-de-casos.md` **antes** de escribirse, con
    su evaluación de riesgo de semejanza.
18. Un caso con riesgo de semejanza calificado como alto no se escribe. Se rediseña o se
    descarta.

## 3. Sectores admitidos y reparto previsto

Reparto orientativo, sujeto a ajuste durante la producción. El control real está en
`revision/control-de-casos.md`.

| Sector admitido | Capítulos previstos |
|---|---|
| Distribución regional | 1, 13 |
| Manufactura ligera | 2, 15 |
| Comercio mayorista | 3, 18 |
| Servicios profesionales | 4, 20 |
| Agricultura | 5, 21 |
| Logística | 6, 19 |
| Mantenimiento | 7 |
| Construcción | 8, 23 |
| Comercio minorista | 9, 22 |
| Empresa familiar de alimentos | 10, 25 |
| Servicios técnicos | 11, 24 |
| Importación y distribución | 12, 14, 17 |

Cobertura: doce sectores para veinticinco capítulos, sin repetición en capítulos
consecutivos y con un máximo de tres apariciones por sector. Los capítulos 16 y la
conclusión no llevan caso.

## 4. Evaluación de riesgos de privacidad e identificación

Riesgos evaluados para el proyecto completo, con la medida aplicada en la Etapa 1.

| # | Riesgo | Probabilidad si no se controla | Impacto | Medida aplicada | Estado |
|---|---|---|---|---|---|
| R-1 | Que un caso permita identificar una organización real. | Media | Alto | Reglas 1–18 de este documento; registro previo obligatorio de cada caso. | Controlado por norma; se verifica en cada capítulo. |
| R-2 | Que el libro se presente como el análisis de una empresa concreta. | Baja | Alto | Nota editorial obligatoria en preliminares; prohibición explícita en material promocional. | Controlado. |
| R-3 | Que el vocabulario de un sector excluido se filtre en un ejemplo. | Media | Alto | Lista de sectores excluidos fuera del repositorio; revisión léxica específica antes de cada publicación. | Control implantado; revisión ejecutada en la Etapa 1 sin hallazgos. |
| R-4 | Que se publiquen credenciales, tokens o claves en el repositorio. | Baja | Alto | `.gitignore` con reglas de secretos; revisión de contenido antes de cada commit. | Controlado; revisión ejecutada, sin hallazgos. |
| R-5 | Que se copie material desde repositorios de otros proyectos del autor. | Baja | Alto | Repositorio aislado, clonado limpio y vacío; ningún archivo importado de otro origen. | Controlado; verificado en la Etapa 1. |
| R-6 | Que una plantilla induzca al lector a exponer datos personales de terceros. | Media | Medio | Aviso al pie de cada herramienta; capítulo 16 y lista de información restringida. | Pendiente de aplicar al redactar las herramientas. |
| R-7 | Que un personaje acumule rasgos hasta parecer un retrato. | Media | Medio | Regla 8, máximo de tres rasgos; regla 9, máximo dos capítulos. | Controlado por norma. |
| R-8 | Que el desequilibrio de género o de sector sugiera un modelo concreto. | Media | Bajo | Reparto planificado en el apartado 3 y control en la Etapa 4. | Controlado por norma. |
| R-9 | Que se atribuya al libro una recomendación legal o fiscal universal. | Media | Alto | Aviso de alcance en preliminares, en el capítulo 10, en el capítulo 16 y al pie de cada herramienta. | Controlado por norma. |
| R-10 | Que el repositorio, siendo público, revele el proceso de trabajo de un cliente. | Baja | Medio | El repositorio contiene únicamente material editorial propio; no se documentan clientes ni encargos. | Controlado. |

## 5. Revisión de privacidad antes de cada publicación

Lista ejecutada antes de cada `git push`. Se registra el resultado en
`PROJECT_STATUS.md`.

1. Búsqueda léxica de términos de sectores excluidos en todos los archivos modificados.
2. Búsqueda de nombres propios de personas y de empresas.
3. Búsqueda de topónimos.
4. Búsqueda de cifras monetarias y de porcentajes sin fuente.
5. Búsqueda de patrones de credenciales: claves, tokens, contraseñas, archivos `.env`.
6. Búsqueda de referencias a otros proyectos del autor.
7. Comprobación de que ningún archivo procede de otro repositorio.
8. Revisión de `git status` y del diff completo antes de confirmar.

**Resultado de la revisión de la Etapa 1:** ejecutada sobre la totalidad de los archivos
creados. Sin hallazgos. Detalle en `PROJECT_STATUS.md`.
