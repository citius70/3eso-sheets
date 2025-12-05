# II: Fórmulas y Funciones de Agregación

Este bloque se centran en la habilidad esencial de la hoja de cálculo: el procesamiento de datos. Los alumnos aprenderán a utilizar expresiones matemáticas básicas (fórmulas) y funciones predefinidas para resumir y calcular información.

---

## 1. Fórmulas: La Base de los Cálculos

Una **Fórmula** es una expresión completa construida por el usuario que combina funciones, referencias de celdas, filas, columnas y rangos para alcanzar un resultado específico.

### I. Sintaxis y Operadores Aritméticos

Toda fórmula en Google Sheets debe comenzar obligatoriamente con el signo de **igual (`=`)**.

| Operación | Símbolo (Operador) | Uso | Cita de Origen |
| :--- | :--- | :--- | :--- |
| **Suma** | `+` | Para la adición. | |
| **Resta** | `-` | Para la sustracción. | |
| **Multiplicación** | `*` | Para multiplicar cifras. | |
| **División** | `/` | Para dividir cifras. | |
| **Exponente** | `^` | Para elevar un número a una potencia. | |

**Fórmulas Compuestas y Jerarquía:**
Se pueden realizar operaciones complejas combinando varios operadores y referencias a celdas. Google Sheets utiliza el orden de operaciones **PEMDAS** (Paréntesis, Exponentes, Multiplicación, División, Adición, Sustracción) para determinar la secuencia correcta de los cálculos.

*Ejemplo de operaciones complejas:*

* "Restar las dos primeras cifras y, el resultado, multiplicarlo por la tercera cifra".
* "Multiplicar las dos primeras cifras y, el resultado, dividirlo por la tercera cifra".

### II. Formato Numérico en los Cálculos

Cuando se realizan cálculos (como la división), es importante aplicar formatos para la correcta visualización de los datos:

* **Formato Decimal:** Permite limitar el resultado a un número específico de cifras después de la coma. Por ejemplo, un resultado puede mostrarse con **dos decimales, únicamente** (ej. 130,67).
* **Formato Moneda:** Se utiliza para indicar que un valor representa dinero, añadiendo el símbolo de la moneda (ej. **€** en la tabla de dinero ahorrado mensual).

---

## 2. Funciones: Automatización de Cálculos

Una **Función** es una fórmula prediseñada que está incorporada en la aplicación, la cual se utiliza para calcular valores y manipular datos. Las funciones simplifican procesos estándar al automatizar los cálculos.

El uso de funciones básicas es el método más simple para comenzar a agregar o resumir grandes cantidades de datos.

### I. Funciones de Agregación Fundamentales

Estas funciones son esenciales para obtener resúmenes rápidos de un conjunto de datos. Se aplican sobre un **rango** de celdas.

| Función | Uso y Propósito | Ejemplo de Aplicación (Basado en las Fuentes) | Citas de Origen |
| :--- | :--- | :--- | :--- |
| **SUMA** (`=SUMA(rango)`) | **Suma** todos los números en un rango de celdas. | Calcular el **TOTAL** de dinero ahorrado por Juan, o el **TOTAL** de trabajadores por empresa o por año. | |
| **PROMEDIO** (`=PROMEDIO(rango)`) | Calcula el valor **medio** (media aritmética) de los números en un rango. | Calcular la **MEDIA** de dinero ahorrado por una persona. | |
| **MÁXIMO** (`=MAX(rango)`) | Encuentra el valor **más alto** o máximo en un rango. | Calcular el ahorro **MÁXIMO** de un mes para una persona. | |
| **MÍNIMO** (`=MIN(rango)`) | Encuentra el valor **más bajo** o mínimo en un rango. | Calcular el ahorro **MÍNIMO** de un mes para una persona. | |
| **CONTAR** (`=COUNT(rango)`) | Cuenta cuántas celdas en un rango contienen **números**. | Se utiliza para determinar, por ejemplo, el número de alumnos aprobados y suspensos. (Se puede usar `COUNTA` para contar todas las celdas que no están vacías, incluyendo texto). | |

### II. Eficiencia: El Puntero de Relleno

El **Puntero de Relleno** (*Fill Handle*) es una herramienta fundamental para copiar fórmulas sin tener que reescribirlas manualmente.

* **¿Cómo se ve?** Es un pequeño signo de más (`+`) que aparece en la esquina inferior derecha de una celda o rango seleccionado.
* **¿Para qué sirve?** Al arrastrar el puntero de relleno, se puede **copiar la fórmula** a las celdas vecinas.
* **Listas Ordenadas:** Si se seleccionan al menos dos celdas que contienen una secuencia numérica (ej. 1, 2), al arrastrar el puntero de relleno, Google Sheets automáticamente **continuará la secuencia** (ej. 3, 4, 5...). Si se selecciona una serie de celdas con números arbitrarios, Google Sheets repetirá el patrón.

---

**Analogía para la Diferencia entre Fórmula y Función:**

Una **Función** (como `SUMA`) es como un electrodoméstico ya construido, por ejemplo, una batidora. Está lista para usarse. Una **Fórmula** es la receta completa (el signo **`=`**) que utiliza ese electrodoméstico junto con otros ingredientes (referencias de celda y operadores) para obtener el resultado final (el plato terminado). En este bloque, aprendemos a hacer las "recetas" más sencillas.
