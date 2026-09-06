# Capítulos

Esta carpeta contendrá el manuscrito por capítulos, en archivos independientes.

**Estado actual: vacía por diseño.** En la Etapa 1 (Fundamentos) no existe autorización
para redactar capítulos. Los archivos de cada parte se crearán únicamente cuando el
autor apruebe expresamente el paso a la Etapa 2 (Muestra editorial) y a la Etapa 3
(Producción).

## Convención de nombres

```
capitulos/00-introduccion.md
capitulos/parte-01/01-cuando-el-propietario-tambien-es-el-sistema.md
capitulos/parte-01/02-el-conocimiento-que-nunca-fue-escrito.md
...
capitulos/parte-05/25-la-empresa-que-puede-continuar.md
capitulos/99-conclusion.md
```

- Numeración de dos dígitos, correspondiente al número de capítulo del índice maestro.
- Título en minúsculas, sin tildes ni signos, separado por guiones.
- Un capítulo por archivo. No se agrupan capítulos.

## Encabezado obligatorio de cada capítulo

Cada archivo de capítulo comenzará con este bloque de control:

```markdown
---
capitulo: 00
parte: 0
titulo: ""
etapa_metodo: ""        # L / E / G / A / D / O
estado: borrador        # borrador | revisado | aprobado
palabras: 0
casos_usados: []        # identificadores de la tabla de control de casos
recursos_producidos: []
afirmaciones_por_verificar: []
ultima_actualizacion: ""
---
```

Ese bloque alimenta `revision/control-de-capitulos.md` y `revision/control-de-casos.md`.

## Orden de producción previsto

Ver `editorial/10-plan-de-produccion.md`.
