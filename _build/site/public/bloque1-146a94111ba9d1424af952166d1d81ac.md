# I. Estructura y Formatos Básicos

## 1. ¿Qué es Google Sheets?

:::{note} Google Sheets
**Google Sheets** (Hojas de Cálculo) es una aplicación de **hoja de cálculo** gratuita y basada en la web, provista por Google dentro del servicio **Google Drive**.
:::

Permite a los usuarios organizar, editar, analizar diferentes tipos de información, y es clave para el trabajo colaborativo, ya que múltiples usuarios pueden editar y dar formato a los archivos en tiempo real.

Una hoja de cálculo es el documento completo (o **Spreadsheet**) que contiene conjuntos de columnas y filas. Dentro de un documento, puede haber una o más **Worksheets** (hojas), que son conjuntos nombrados de filas y columnas.

## 2. Vocabulario Estructural

Para trabajar en Google Sheets, es esencial conocer los nombres de sus componentes principales, que forman una matriz o cuadrícula:

| Concepto             | Definición                                                                                                                                        | Ejemplos (Basados en las Tareas)           | Citas de Origen |
| :------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ | :----------------------------------------- | :-------------- |
| **Celda** (Cell)     | Es la unidad mínima y fundamental de información, o un solo punto de dato. Se identifica por la intersección de una columna y una fila.           | B4, A9, E12, D5, F18.                      |                 |
| **Columna** (Column) | Es la disposición vertical de celdas, identificada por letras (A, B, C...).                                                                       | Colorear la **columna C** de color verde.  |                 |
| **Fila** (Row)       | Es la disposición horizontal de celdas, identificada por números (1, 2, 3...).                                                                    | Colorear la **fila 8** de color gris.      |                 |
| **Rango** (Range)    | Es un conjunto rectangular de múltiples celdas adyacentes. Se define por las referencias de las celdas de las esquinas, separadas por dos puntos. | E3:G7 (rango de celdas coloreado de rosa). |                 |

:::{figure} images/bloque1.png
:label: fundamentos
Fundamentos de Google Sheets.
:::

## 3. Entrada y Manipulación de Datos

La forma en que se <em>introducen</em> y mueven los datos afecta la eficiencia del trabajo:

- **Entrada Básica:** Para añadir datos a una celda, simplemente se hace clic en ella y se escribe. Para facilitar la manipulación o el filtrado posterior, es una buena práctica que cada celda contenga solo un valor.
- **Navegación:** Después de escribir en una celda, se puede presionar la tecla `Enter` o `return` para guardar el dato y mover el cursor al inicio de la **siguiente fila**. Alternativamente, se puede presionar `Tab` para guardar el dato y moverse una celda a la **derecha** dentro de la misma fila.
- **El Puntero de Relleno (Fill Handle):** Es un pequeño signo de más (`+`) que aparece en la esquina inferior derecha de una celda seleccionada. Al arrastrar este puntero, se pueden copiar automáticamente datos, formatos o fórmulas a celdas adyacentes.

## 4. Formatos de Celda

El formato manual permite modificar directamente la apariencia de los datos, mejorando la **presentación** y la **legibilidad**.

### A. Formato de Contenido: Texto y Números

| Formato              | Uso Práctico                                                                            | Ejemplos de Contenido                                                                                                                 | Citas de Origen |
| :------------------- | :-------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------ | :-------------- |
| **Estilo de Fuente** | Destacar información importante. Se utilizan: **Negrita**, **Subrayado** y **Cursiva**. | Escribir **6798** en **negrita**. Escribir **"Fotografía" subrayada** en B10. Escribir el número **56** en **cursiva de color rojo**. |                 |
| **Alineación**       | Determinar la posición del contenido dentro de la celda.                                | **Centrar** la palabra **"Internet"** en la celda F18.                                                                                |                 |

### B. Formato de Estructura

Estos formatos se aplican a las celdas o rangos para organizar visualmente la hoja:

- **Relleno o Color de Fondo:** Permite colorear el fondo para agrupar o destacar visualmente los datos. Por ejemplo, se pide colorear la **celda B4 de color rojo**, la **fila 8 de gris**, o el **rango E3:G7 de rosa**.
- **Bordes (Borders):** Se usan para dibujar límites y delimitar secciones. Hay diferentes grosores, como el **borde grueso** (ej. celda E9 o J15) o el **borde fino** (ej. celda B10).

### C. Formatos Numéricos Especializados

Para el análisis correcto de los datos, es crucial aplicar el formato numérico que corresponda al tipo de información:

- **Formato Decimal:** Se usa para especificar la cantidad de cifras después de la coma. Por ejemplo, en operaciones matemáticas, se puede requerir que el resultado muestre **dos decimales, únicamente** (ej. 130,67).
- **Formato Moneda o Contabilidad:** Añade el símbolo de la moneda (ej. **€**) a los valores.
- **Formato Porcentaje:** Se usa para expresar valores como una fracción de 100 (ej. 21,00% para la tasa de IVA).

## 5. Diferencia Clave: Formato Manual vs. Formato Condicional

Es importante distinguir entre el formato que aplica manualmente en este bloque (ej. colorear una celda de rojo) y el formato avanzado que se aprenderá más adelante:

- **Formato Manual:** El estilo se aplica de forma directa y es estático; no cambia si el valor de la celda cambia.
- **Formato Condicional:** El formato (por ejemplo, el color) se aplica **automáticamente** solo si el valor de la celda cumple una **condición lógica o regla predefinida**. Por ejemplo, se utiliza el formato condicional para que las notas **iguales o superiores a 5 se muestren en verde**, mientras que las **inferiores a 5 se muestren en rojo**. Este es un ejemplo de lógica automática.

---

**Símil:**

Imagine Google Sheets como un archivador digital:

- La **Celda** es la ficha individual donde se escribe un dato.
- La **Fila** es una caja horizontal que contiene todas las fichas de un mismo objeto (por ejemplo, los datos de un alumno).
- La **Columna** es una caja vertical que contiene el mismo tipo de dato para todos los objetos (por ejemplo, todas las notas de Matemáticas).
- El **Formato** es la etiqueta de color o el tipo de letra que se usa para que la información sea fácil de encontrar y entender.
