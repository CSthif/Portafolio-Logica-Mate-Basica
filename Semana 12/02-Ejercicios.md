# Semana 12 – Ejercicios prácticos
## Módulo 5. Funciones (parte II)

**Fuente:** Ejercicio de simulación de Montaña Rusa - AI Studio, Módulo 5. Funciones

---

## Simulador La Montaña Rusa

Aplicación de los conceptos de monotonía en un entorno físico real. Se crea una trayectoria que simule una montaña rusa y se analiza su comportamiento.

---

## Definición de la función por partes

La trayectoria de la montaña rusa se modela mediante la función por partes r(x), compuesta por las siguientes funciones en sus respectivos intervalos:

- **f(x) = −x² + 2x** en [0, 3]
- **g(x) = x − 6** en (3, 7]
- **h(x) = x² − 16x + 64** en (7, 10]  →  equivalente a (x − 8)²
- **p(x) = 14 − x** en (10, 14]
- **q(x) = 0** en (14, 18]

---

## 1. ¿En qué intervalos la función es creciente (el vagón sube)?

Una función es creciente cuando, al aumentar el valor de x, aumenta el valor de y (la pendiente es positiva).

**Análisis por tramo:**

- **f(x) = −x² + 2x:** Es una parábola que abre hacia abajo. Su vértice está en x = −b/(2a) = −2/(−2) = 1. Por lo tanto, **sube en [0, 1]**.

- **g(x) = x − 6:** Es una recta con pendiente positiva (m = 1). **Sube en todo su intervalo: (3, 7]**.

- **h(x) = (x − 8)²:** Es una parábola que abre hacia arriba. Su vértice (mínimo) está en x = 8. Empieza a subir después del vértice, es decir, **sube en [8, 10]**.

**Intervalos de crecimiento combinados:**

**I_creciente = [0, 1] ∪ (3, 7] ∪ [8, 10]**

---

## 2. ¿En cuáles es decreciente (el vagón baja)?

La función es decreciente cuando el valor de y disminuye al aumentar x (pendiente negativa):

- **f(x):** Baja después de su vértice (x = 1) hasta el final de su tramo: **[1, 3]**.

- **h(x):** Baja desde el inicio de su tramo hasta su vértice en x = 8: **(7, 8]**.

- **p(x) = 14 − x:** Es una recta con pendiente negativa (m = −1). **Baja en todo su intervalo: (10, 14]**.

- **q(x) = 0:** Es una función constante, no es creciente ni decreciente (tramo plano).

**Intervalos de decrecimiento combinados:**

**I_decreciente = [1, 3] ∪ (7, 8] ∪ (10, 14]**

---

## 3. Coordenadas (x, y) del vértice máximo (punto más alto de la atracción)

Se comparan los valores máximos locales de cada tramo:

- **Vértice de f(x):** En x = 1, f(1) = −(1)² + 2(1) = 1. Punto **(1, 1)**.

- **Final del tramo g(x):** En x = 7, g(7) = 7 − 6 = 1. Punto **(7, 1)**.

- **Final del tramo h(x):** En x = 10, h(10) = (10 − 8)² = 4. Punto **(10, 4)**.

- **Inicio del tramo p(x):** En x = 10, p(10) = 14 − 10 = 4. Punto **(10, 4)**.

---

### El punto más alto (Vértice Máximo) es:

**(10, 4)**

Este punto corresponde al final de la segunda subida e inicio de la bajada más pronunciada de la montaña rusa.

---

## Tabla de valores de transición

| x | Función | y = r(x) | Descripción |
|---|---------|----------|-------------|
| 0 | f(x) | 0 | Inicio del recorrido |
| 1 | f(x) | 1 | Primera cima (vértice de f) |
| 3 | f(x) | −3 | Fin del primer tramo |
| 3 | g(x) | −3 | Inicio de la subida lineal |
| 7 | g(x) | 1 | Fin de la subida lineal |
| 8 | h(x) | 0 | Valle (vértice de h) |
| 10 | h(x) | 4 | **Punto más alto** |
| 14 | p(x) | 0 | Fin de la bajada final |
| 18 | q(x) | 0 | Fin del recorrido (zona plana) |
