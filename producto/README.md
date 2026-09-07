# Producto — plataforma digital del Método LEGADO

Arquitectura conceptual de una **plataforma digital guiada** que implementa el Método
LEGADO. Creada en la Etapa 2.5.

---

## Qué es esta carpeta y qué no es

**Es** el sitio donde vive el pensamiento de producto, separado del editorial para que no
lo contamine.

**No es** un repositorio de software. A fecha de hoy:

- no hay código;
- no hay stack elegido;
- no hay proveedores elegidos;
- no hay base de datos diseñada;
- no hay integraciones diseñadas;
- no hay marca comercial decidida;
- no hay precios.

Todo eso está **expresamente fuera de alcance** hasta que el autor lo autorice.

## Por qué existe separada de `editorial/`

Porque son dos disciplinas con dos riesgos opuestos. La editorial protege al lector; la de
producto tiende a invadirla. Mezclarlas en la misma carpeta habría sido la forma más rápida
de que el libro empezara a escribirse pensando en pantallas.

**La norma que gobierna la relación entre ambas no vive aquí**: vive en
`editorial/16-libro-metodo-y-plataforma.md`, con el resto de las normas del libro, y
prevalece sobre cualquier cosa escrita en esta carpeta.

## La regla de la que cuelga todo

> **El libro debe ser completo, útil y accionable aunque el lector nunca utilice la
> plataforma.**

Y su corolario:

> **El software se adapta al método. Nunca al revés.**

## Contenido

| Archivo | Qué contiene |
|---|---|
| `01-vision-y-principios.md` | Qué es la plataforma, los doce principios, el embudo de valor, el modelo de suscripción conceptual, propiedad de los datos, privacidad, profesiones reguladas y el backlog de investigación. |
| `02-mapa-libro-plataforma.md` | La matriz de los veintisiete capítulos: qué comprende el lector, qué genera, qué activo digital le corresponde y qué puede hacer la plataforma en cada punto. |
| `03-arquitectura-funcional.md` | Módulos, capas técnicas conceptuales, modelo del ADN Empresarial, onboarding, progreso, prueba de ausencia, asistente, progresión de la IA y madurez. |
| `04-mapa-herramientas.md` | Las dieciocho herramientas del libro, una a una, con su equivalente digital, su IA posible, su supervisión y su ruta. |

## Estado

**Arquitectura conceptual. Nada de esto está construido ni comprometido.** Las decisiones
registradas son D-050 a D-061 en `editorial/decisiones-editoriales.md`.
