# Guía de Estudio: Extremos Relativos

## 1. Definición de Extremos Relativos

Un punto \( (x_0, f(x_0)) \) es un **extremo relativo** de una función \( f(x) \) si es un **máximo** o **mínimo local**.

- **Máximo Relativo**: \( f(x_0) \geq f(x) \) para todo \( x \) en un entorno de \( x_0 \).
- **Mínimo Relativo**: \( f(x_0) \leq f(x) \) para todo \( x \) en un entorno de \( x_0 \).

## 2. Condiciones Necesarias (Criterio de la 1ª Derivada)

Para encontrar los extremos relativos, primero calculamos la derivada de la función \( f'(x) \) y encontramos los puntos donde \( f'(x) = 0 \) o donde \( f'(x) \) no existe. Estos puntos son llamados **puntos críticos**.

### Puntos Críticos

Los **puntos críticos** son aquellos valores de \( x \) donde la derivada de la función se anula o no existe. Es decir:

\[
f'(x_0) = 0 \quad \text{o} \quad f'(x) \text{ no existe en } x_0
\]

### Pasos para Encontrar los Puntos Críticos

1. Calcula la derivada primera \( f'(x) \).
2. Resuelve la ecuación \( f'(x) = 0 \) para encontrar los puntos críticos.
3. Verifica si \( f'(x) \) no existe en algún punto para identificar otros posibles puntos críticos.

## 3. Criterio de la 2ª Derivada

El **criterio de la segunda derivada** se usa para clasificar los puntos críticos encontrados:

- Si \( f''(x_0) > 0 \), entonces \( x_0 \) es un **mínimo relativo**.
- Si \( f''(x_0) < 0 \), entonces \( x_0 \) es un **máximo relativo**.
- Si \( f''(x_0) = 0 \), el test es inconcluso y es necesario realizar un análisis adicional (por ejemplo, utilizando la **tabulación**).

## 4. Método de Tabulación para Graficar Extremos Relativos

### Paso 1: Crear una Tabla de Valores

Construir una tabla con valores de \( x \) alrededor del punto crítico \( x_0 \). Para ello:

1. Escoge valores de \( x \) cercanos a \( x_0 \) (a la izquierda y a la derecha).
2. Calcula \( f(x) \) para esos valores de \( x \).

La tabla tendrá la siguiente estructura:

| \( x \)        | \( f(x) \)    | \( f'(x) \)  | \( f''(x) \) |
|----------------|---------------|--------------|--------------|
| \( x_0 - h \)  | \( f(x_0 - h) \) | \( f'(x_0 - h) \) | \( f''(x_0 - h) \) |
| \( x_0 \)      | \( f(x_0) \)    | \( f'(x_0) \) | \( f''(x_0) \) |
| \( x_0 + h \)  | \( f(x_0 + h) \) | \( f'(x_0 + h) \) | \( f''(x_0 + h) \) |

### Paso 2: Análisis de los Valores

Para identificar si \( x_0 \) es un máximo o mínimo relativo:

- Si \( f(x_0) > f(x_0 - h) \) y \( f(x_0) > f(x_0 + h) \), entonces \( x_0 \) es un **máximo local**.
- Si \( f(x_0) < f(x_0 - h) \) y \( f(x_0) < f(x_0 + h) \), entonces \( x_0 \) es un **mínimo local**.

### Paso 3: Graficar

Una vez completada la tabla, coloca los valores de \( x \) y \( f(x) \) en un sistema de coordenadas. Observa la curva resultante para confirmar si el punto \( x_0 \) es un extremo relativo.

- **Eje X**: \( x_0 - h, x_0, x_0 + h \)
- **Eje Y**: \( f(x_0 - h), f(x_0), f(x_0 + h) \)

## 5. Ejemplos Prácticos

### Ejemplo 1: \( f(x) = x^3 - 3x + 2 \)

1. **Derivada**:

\[
f'(x) = 3x^2 - 3
\]

Resolviendo \( f'(x) = 0 \):

\[
3x^2 - 3 = 0 \quad \Rightarrow \quad x = \pm 1
\]

2. **Segunda Derivada**:

\[
f''(x) = 6x
\]

Evaluando en los puntos críticos:

- \( f''(1) = 6 > 0 \quad \Rightarrow \quad x = 1 \) es un **mínimo relativo**.
- \( f''(-1) = -6 < 0 \quad \Rightarrow \quad x = -1 \) es un **máximo relativo**.

#### Tabla de Valores para \( f(x) = x^3 - 3x + 2 \):

| \( x \)     | \( f(x) \)   | \( f'(x) \) | \( f''(x) \) |
|-------------|--------------|-------------|--------------|
| \( -2 \)    | \( -6 \)     | \( 15 \)    | \( -12 \)    |
| \( -1 \)    | \( 6 \)      | \( 0 \)     | \( -6 \)     |
| \( 0 \)     | \( 2 \)      | \( -3 \)    | \( 0 \)      |
| \( 1 \)     | \( 0 \)      | \( 0 \)     | \( 6 \)      |
| \( 2 \)     | \( 4 \)      | \( 9 \)     | \( 12 \)     |

**Análisis**:

- \( f(x_0) > f(x_0 - h) \) y \( f(x_0) > f(x_0 + h) \) para \( x_0 = -1 \): **máximo local**.
- \( f(x_0) < f(x_0 - h) \) y \( f(x_0) < f(x_0 + h) \) para \( x_0 = 1 \): **mínimo local**.

---

### Ejemplo 2: \( f(x) = x^2 - 4x + 4 \)

1. **Derivada**:

\[
f'(x) = 2x - 4
\]

Resolviendo \( f'(x) = 0 \):

\[
2x - 4 = 0 \quad \Rightarrow \quad x = 2
\]

2. **Segunda Derivada**:

\[
f''(x) = 2
\]

Evaluando en \( x = 2 \):

- \( f''(2) = 2 > 0 \quad \Rightarrow \quad x = 2 \) es un **mínimo relativo**.

#### Tabla de Valores para \( f(x) = x^2 - 4x + 4 \):

| \( x \)     | \( f(x) \)   | \( f'(x) \) | \( f''(x) \) |
|-------------|--------------|-------------|--------------|
| \( 0 \)     | \( 4 \)      | \( -4 \)    | \( 2 \)      |
| \( 1 \)     | \( 1 \)      | \( -2 \)    | \( 2 \)      |
| \( 2 \)     | \( 0 \)      | \( 0 \)     | \( 2 \)      |
| \( 3 \)     | \( 1 \)      | \( 2 \)     | \( 2 \)      |
| \( 4 \)     | \( 4 \)      | \( 4 \)     | \( 2 \)      |

**Análisis**:

- \( f(x_0) < f(x_0 - h) \) y \( f(x_0) < f(x_0 + h) \) para \( x_0 = 2 \): **mínimo local**.

---

### Ejemplo 3: \( f(x) = x^3 - 2x^2 - x + 2 \)

1. **Derivada**:

\[
f'(x) = 3x^2 - 4x - 1
\]

Resolviendo \( f'(x) = 0 \):

\[
3x^2 - 4x - 1 = 0
\]

Las soluciones son \( x \approx -0.2 \) y \( x \approx 2.2 \).

2. **Segunda Derivada**:

\[
f''(x) = 6x - 4
\]

Evaluando en los puntos críticos:

- \( f''(-0.2) = -4.4 < 0 \quad \Rightarrow \quad x = -0.2 \) es un **máximo relativo**.
- \( f''(2.2) = 8.4 > 0 \quad \Rightarrow \quad x = 2.2 \) es un **mínimo relativo**.

#### Tabla de Valores para \( f(x) = x^3 - 2x^2 - x + 2 \):

| \( x \)     | \( f(x) \)   | \( f'(x) \) | \( f''(x) \) |
|-------------|--------------|-------------|--------------|
| \( -1 \)    | \( 4 \)      | \( 15 \)    | \( -12 \)    |
| \( -0.2 \)  | \( 5.072 \)  | \( 1.52 \)  | \( -4.4 \)   |
| \( 0 \)     | \( 2 \)      | \( -3 \)    | \( -4 \)     |
| \( 1 \)     | \( 0 \)      | \( -3 \)    | \( 2 \)      |
| \( 2.2 \)   | \( -2.488 \) | \( -7.256 \)| \( 8.4 \)    |

**Análisis**:

- \( f(x_0) > f(x_0 - h) \) y \( f(x_0) > f(x_0 + h) \) para \( x_0 = -0.2 \): **máximo local**.
- \( f(x_0) < f(x_0 - h) \) y \( f(x_0) < f(x_0 + h) \) para \( x_0 = 2.2 \): **mínimo local**.

---

## 6. Consejos para Identificar el Comportamiento de la Curva

1. **Puntos Críticos**: Los puntos donde la derivada se hace cero o no existe son lugares donde la pendiente de la curva se iguala a cero, y pueden indicar un máximo, mínimo o punto de inflexión.
2. **Comportamiento de la Curva**: Al analizar la tabla de valores y graficar la función, observa cómo se comporta la curva alrededor de los puntos críticos para identificar si son máximos o mínimos locales.

---
