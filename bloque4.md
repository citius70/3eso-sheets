# IV: Análisis Avanzado y Visualización de Datos

## 1. Funciones de Búsqueda y Extracción de Datos

En ocasiones, necesitamos buscar un dato específico dentro de una gran tabla y traer un valor relacionado.

### I. Función BUSCARV (VLOOKUP)

La función **BUSCARV** (o VLOOKUP) se utiliza para **buscar un valor** en la primera columna de un rango y devolver un valor de una columna diferente en esa misma fila. Esta función es fundamental para automatizar la extracción de datos de tablas grandes.

**Aplicaciones basadas en Ejercicios:**

* **Búsqueda Geográfica:** Después de calcular la **Densidad** (habitantes/km2) para varias Comunidades Autónomas, podemos configurar una celda para que, al ingresar el nombre de una Comunidad (ej. Madrid), la función **BUSCARV** devuelva automáticamente su densidad correspondiente (ej. 841,17).
* **Clasificación Climática:** Se puede utilizar **BUSCARV** para buscar un **Índice de Aridez** (calculado a partir de datos de precipitaciones y temperatura, como en el caso de Pontevedra) y devolver el **Tipo de clima** asociado (ej. Húmedo) que se encuentra en una tabla de rangos predefinidos.

## 2. Análisis Asistido por IA: La Función Explorar

Google Sheets incluye una potente herramienta que utiliza **aprendizaje automático** (Machine Learning o IA) para ayudar a analizar datos sin necesidad de escribir fórmulas complejas. Esta herramienta se conoce como la función **Explorar** (*Explore feature*).

### I. Uso y Características

* **Acceso Rápido:** La función Explorar se encuentra en la esquina inferior derecha de la interfaz de Google Sheets, representada por un icono de una estrella de cuatro puntas con un brillo. También se puede acceder a ella mediante el menú superior (*Herramientas > Explorar*).
* **Asistente Personal:** Actúa como un analista de datos personal que genera gráficos, resume información y responde preguntas en lenguaje sencillo.
* **Análisis Automático:** Al abrir el panel Explorar, la IA escanea los datos seleccionados y sugiere proactivamente gráficos relevantes, información clave, tablas dinámicas y soluciones de formato.

### II. Preguntas en Lenguaje Natural (NLQ)

La característica más poderosa de Explorar es su motor de **Preguntas en Lenguaje Natural**.

* **Formulación de Consultas:** Se puede escribir una pregunta en lenguaje cotidiano (ej. "¿cuáles fueron las ventas totales por región?") y Explorar procesará la consulta para ofrecer una respuesta instantánea, a menudo generando una visualización o un gráfico.
* **Generación de Gráficos Instantánea:** El sistema selecciona automáticamente el tipo de gráfico adecuado (barras, líneas, circular, etc.) para representar la respuesta a la pregunta formulada.
* **Formato Fácil:** Explorar puede aplicar formatos profesionales, como **colores alternos** a las filas de la tabla, con un solo clic.

**Requisito de Datos:** Para que Explorar funcione correctamente, es crucial que los datos estén **limpios y organizados**, con **encabezados claros** y **sin celdas combinadas**.

## 3. Tablas Dinámicas (Pivot Tables)

Las Tablas Dinámicas son herramientas flexibles y potentes para resumir grandes conjuntos de datos de forma dinámica.

* **Propósito:** Permiten analizar la misma información desde múltiples perspectivas sin necesidad de crear una hoja de cálculo nueva para cada análisis.
* **Creación:** Se insertan seleccionando los datos de origen y yendo a **Insertar > Tabla dinámica**.
* **Editor:** El editor de Tablas Dinámicas permite arrastrar campos a diferentes áreas: **Filas**, **Columnas**, **Valores** (la métrica que se va a agregar, como `SUMA` o `PROMEDIO`) y **Filtros**.
* **Ventajas:** Permiten crear informes de resumen complejos en segundos y la hoja de cálculo se encarga de todo el trabajo de agregación automáticamente. Los datos en la tabla dinámica se actualizan si los datos de origen cambian.

La visualización de datos es una fase crítica del análisis que transforma las tablas numéricas en información clara y comprensible. A continuación, se amplía el punto de **Visualización de Datos (Gráficos)**, detallando su creación, tipos y la ayuda de la inteligencia artificial:

---

## 4. Visualización de Datos (Gráficos)

Los gráficos son herramientas esenciales para **comprender tendencias y patrones en los datos de un vistazo**. Permiten a los usuarios transformar grandes cantidades de números en visualizaciones sencillas y potentes.

### I. Creación e Inserción

El proceso básico para generar un gráfico a partir de una tabla de datos es directo:

1. **Selección de Datos:** Para crear un gráfico, se deben **seleccionar todos los datos de origen** que se desean visualizar. Es importante incluir los **encabezados de columna** en la selección.
2. **Inserción Manual:** El gráfico se inserta haciendo clic en **Insertar > Gráfico**.
3. **Resultado Inicial:** Por defecto, Google Sheets a menudo convierte los datos en un **gráfico de barras**. Además, la herramienta **Explorar** (*Explore feature*) puede escanear los datos y generar instantáneamente gráficos o resúmenes estadísticos que se pueden **insertar directamente en la hoja** con un solo clic.

### II. Tipos de Gráficos y sus Aplicaciones

Google Sheets soporta una variedad de tipos de gráficos, cada uno adecuado para diferentes tipos de análisis:

| Tipo de Gráfico | Propósito y Uso (Basado en las Fuentes) | Citas de Origen |
| :--- | :--- | :--- |
| **Gráficos de Barras / Columnas** | Se utilizan comúnmente para comparar valores entre categorías o mostrar tendencias. La herramienta Explorar a menudo sugiere gráficos de barras. Se pueden usar para mostrar el **Número de Trabajadores** de diferentes empresas a lo largo de varios años. | |
| **Gráficos Circulares (Tarta)** | Muestran la contribución proporcional de cada parte al todo. Se utilizan, por ejemplo, para visualizar el **número de alumnos aprobados y suspensos** en una asignatura. | |
| **Gráficos Radiales** | Son útiles para **comparar las estadísticas o habilidades de dos sujetos** distintos en múltiples categorías. Por ejemplo, se usan para comparar habilidades como Pases, Regates, Centros, o Remates de cabeza entre dos sujetos (ej. Messi y Ronaldo). | |
| **Otros Tipos** | También existen gráficos de **líneas** (ideales para mostrar tendencias temporales, como "ventas totales a lo largo del tiempo") y **diagramas de dispersión** (scatter plots). | |

### III. Edición y Personalización

Una vez que el gráfico está en la hoja, los usuarios tienen control total para modificar su apariencia y contenido:

* **Editor de Gráficos:** El gráfico se puede editar utilizando el **Editor de Gráficos** (*Chart editor*).
* **Ajustes:** El editor permite ajustar **colores, títulos** o **etiquetas de los ejes**. Esto es importante para hacer que la visualización final sea clara y profesional.
* **Cambio de Tamaño y Posición:** El gráfico puede ser **redimensionado** haciendo clic y arrastrando los puntos que rodean su borde, y puede ser **recolocado** arrastrándolo a la posición deseada en la hoja.

### IV. Visualización Asistida por IA (Función Explorar)

La función **Explorar** (*Explore feature*) utiliza el aprendizaje automático (Machine Learning) para generar gráficos y visualizar datos.

* **Sugerencias Automáticas:** La IA escanea los datos y **sugiere proactivamente gráficos relevantes** (como gráficos de barras o circulares).
* **Consultas en Lenguaje Natural (NLQ):** Los usuarios pueden hacer preguntas específicas sobre los datos en **lenguaje cotidiano** (ej. "¿cuáles fueron las ventas totales por región?") y el sistema **genera la visualización adecuada de forma instantánea**. El sistema selecciona automáticamente el tipo de gráfico que mejor responde a la pregunta.
* **Personalización:** Los gráficos generados por la función Explorar son objetos estándar de Google Sheets y se pueden seguir **personalizando con el Editor de Gráficos**.

**Requisito de Datos para Gráficos y Explorar:**
Para que la visualización sea efectiva y la función Explorar trabaje correctamente, los datos deben estar **limpios y organizados**. Es fundamental utilizar **encabezados claros** y **evitar las celdas combinadas** (*merged cells*), ya que confunden a la IA sobre la estructura real de la tabla.
