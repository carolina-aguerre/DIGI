# Atlas de iniciativas y políticas de Internet en América Latina

**DiGI · Diploma en Gobernanza de Internet — Edición 2026**

Este atlas reúne el mapeo colaborativo que realizan los participantes de la DiGI durante el bloque virtual del programa. Cada ficha corresponde al análisis de una iniciativa, institución o política de gobernanza de Internet, relevada por un participante de la cohorte.

El mapeo se construye semana a semana. Cada nueva entrega suma fichas al atlas y enciende un nuevo punto en el mapa. Así, la cohorte puede ver cómo crece el panorama regional a medida que avanza el programa.

## Un proyecto educativo

Este sitio es parte de un **ejercicio formativo** del Diploma en Gobernanza de Internet. Su propósito es pedagógico: que los participantes practiquen el relevamiento y el análisis de iniciativas y políticas, y que puedan compartir y comparar sus hallazgos con el resto de la cohorte.

### Sobre el contenido

Las fichas son producciones de los participantes, elaboradas en el marco de un trabajo académico, y reflejan su lectura y su interpretación de cada caso. Por eso conviene tener en cuenta lo siguiente:

- La información puede estar **incompleta, desactualizada o contener imprecisiones** propias de un trabajo en proceso de aprendizaje.
- Los análisis, las valoraciones y las recomendaciones son **de los participantes** y no representan una posición institucional de la DiGI, de su equipo docente ni de las organizaciones mencionadas.
- Los datos no fueron verificados de forma exhaustiva. Para usos formales, de investigación o de política pública, recomendamos **consultar las fuentes oficiales** de cada iniciativa.

Si encontrás un error o querés sugerir una corrección, podés abrir un *issue* en este repositorio.

## Qué contiene

El atlas se organiza por semanas del programa, y cada semana aparece recién cuando tiene sus primeras fichas:

| Semana | Mapeo |
|---|---|
| 1.1 | Iniciativas nacionales de gobernanza de Internet |
| 1.2 | Iniciativas de gobernanza por tipo, alcance e inclusividad de actores |
| 2 | Políticas de conectividad e inclusión digital |

Las fichas se pueden filtrar por país o alcance, y también buscar por nombre de la iniciativa o del participante.

## Cómo funciona

1. Los participantes completan un formulario de Google por cada ejercicio de mapeo.
2. Las respuestas se guardan en una planilla de Google Sheets.
3. El sitio lee la planilla en vivo y arma las fichas automáticamente. No hace falta volver a publicarlo cuando llegan respuestas nuevas.

El sitio es un único archivo, `index.html`, publicado con GitHub Pages. No usa servidor ni base de datos, y no recopila datos de quienes lo visitan.

### Configuración

En la sección `CONFIG` del `index.html`:

- `SHEET_ID`: ID de la planilla de respuestas.
- `WEEKS`: lista de semanas, cada una con el `gid` de su pestaña en la planilla.

Para agregar una nueva semana hay que sumar su esquema de columnas y una línea en `WEEKS` con el `gid` correspondiente.

La planilla tiene que estar compartida como **"Cualquier persona con el enlace: Lector"** para que el sitio pueda leerla.

## Créditos

- **Dirección académica:** Carolina Aguerre
- **Contenido:** participantes de la cohorte DiGI 2026
- **Diseño instruccional y desarrollo del atlas:** Sofía Alamo

---

*Proyecto educativo sin fines comerciales. Las fichas pertenecen a sus autores y se publican con fines formativos.*
