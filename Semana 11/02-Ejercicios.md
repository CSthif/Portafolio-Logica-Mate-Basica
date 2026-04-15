# Semana 11 – Ejercicios prácticos
## Módulo 5. Funciones (Parte I)

**Fuente:** Función lineal – Actividad para portafolio (presentación de clase)

---

## 1. Determine el criterio de una función lineal para un contexto específico

**Contexto elegido:** Costo de suscripción a un servicio de almacenamiento en la nube.

Un servicio de almacenamiento en la nube cobra una tarifa base de **$5 al mes** más **$0.10 por cada GB** de almacenamiento utilizado.

La función lineal que modela este contexto es:

**C(x) = 0.10x + 5**

Donde:
- **C(x):** costo mensual en dólares
- **x:** cantidad de gigabytes (GB) utilizados
- **m = 0.10:** pendiente (costo por cada GB adicional)
- **b = 5:** intercepto con el eje y (tarifa base mensual)

---

## 2. Representación gráfica

La gráfica de la función C(x) = 0.10x + 5 es una **línea recta** con las siguientes características:

- Inicia en el punto (0, 5), que corresponde a la tarifa base sin uso de almacenamiento.
- Tiene una pendiente positiva de 0.10, lo que significa que por cada GB adicional, el costo sube $0.10.
- La recta es ascendente de izquierda a derecha.

*Nota: La gráfica fue elaborada en GeoGebra utilizando el enlace proporcionado en la presentación de clase.*

---

## 3. Mínimo y máximo valor de x según el contexto

- **x_mín = 0 GB:** No se puede tener almacenamiento negativo. Si el usuario no almacena nada, paga solamente la tarifa base.
- **x_máx = 2000 GB:** Este sería el límite máximo del plan de almacenamiento ofrecido por el servicio.

Por lo tanto, el dominio contextual es: **[0, 2000]**

---

## 4. Resultados de los valores extremos

Evaluando la función en los valores extremos:

- **C(0) = 0.10(0) + 5 = 5**
  → Si no se utiliza almacenamiento, el costo es de $5 (tarifa base).

- **C(2000) = 0.10(2000) + 5 = 200 + 5 = 205**
  → Si se utilizan 2000 GB, el costo máximo es de $205.

---

## 5. Pares ordenados interesantes

| x (GB) | C(x) ($) | Interpretación |
|---|---|---|
| 0 | 5 | Solo tarifa base, sin almacenamiento |
| 50 | 10 | Uso ligero, costo bajo |
| 100 | 15 | Uso moderado |
| 500 | 55 | Uso considerable |
| 1000 | 105 | Uso alto, más de $100 mensuales |
| 2000 | 205 | Límite máximo del plan |

Estos pares ordenados permiten visualizar cómo el costo escala de forma proporcional al almacenamiento utilizado.

---

## 6. Comportamiento de la función

La función C(x) = 0.10x + 5 es **creciente** en todo su dominio.

Esto se debe a que la pendiente **m = 0.10 > 0**, lo que indica que a medida que aumenta la cantidad de gigabytes utilizados (x), el costo mensual (C(x)) también aumenta.

En el contexto real, esto tiene sentido: entre más almacenamiento se use, mayor será el cobro mensual.

---

## 7. Otras características relevantes

- **Dominio (contexto):** [0, 2000] — cantidad de GB que puede utilizar el usuario.
- **Rango (contexto):** [5, 205] — rango de precios posibles del servicio.
- **Intersección con el eje y:** (0, 5) — representa la tarifa base sin uso de almacenamiento.
- **Pendiente positiva (m = 0.10):** indica una relación directa entre el almacenamiento utilizado y el costo. Es decir, más almacenamiento implica mayor costo.
- **Función continua:** en el contexto digital, aunque los GB son unidades discretas, el modelo lineal permite estimar costos para cualquier cantidad dentro del dominio.
- **No tiene intersección con el eje x en el dominio:** dado que C(x) = 0 implicaría x = -50, lo cual no tiene sentido en este contexto (no existen GB negativos).
