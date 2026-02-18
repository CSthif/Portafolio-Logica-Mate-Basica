# Semana 2 — Ejercicios prácticos
## Módulo 3. Fundamentos de conjuntos (Parte I)

**Fuente:** Módulo 3 (prácticas de páginas 11 y 12).

---

## Ejercicio 1 (Página 11)

**Enunciado:**  
Si \(U=\{1,2,3,4,5\}\), \(A=\{2,5\}\) y \(B=\{1,5\}\), calcule:
- \(A^c\)
- \(\overline{A \cup B}\)
- \(B-A\)

### Datos
- \(U=\{1,2,3,4,5\}\)
- \(A=\{2,5\}\)
- \(B=\{1,5\}\)

### Procedimiento

**1) Complemento de A:**  
Por definición, \(A^c = U - A\).  
Entonces:
- \(U - A = \{1,2,3,4,5\} - \{2,5\} = \{1,3,4\}\)

**2) Complemento de la unión:**  
Primero se calcula \(A \cup B\):
- \(A \cup B = \{2,5\} \cup \{1,5\} = \{1,2,5\}\)

Luego el complemento:
- \(\overline{A \cup B} = U - (A \cup B) = \{1,2,3,4,5\} - \{1,2,5\} = \{3,4\}\)

**3) Diferencia \(B-A\):**  
Elementos que están en \(B\) y no están en \(A\):
- \(B-A = \{1,5\} - \{2,5\} = \{1\}\)

### Resultado
- \(A^c = \{1,3,4\}\)
- \(\overline{A \cup B} = \{3,4\}\)
- \(B-A = \{1\}\)

---

## Ejercicio 2 (Página 11)

**Enunciado:**  
Si \(U=\{0,2,4,6,8,9\}\), \(A=\{0,2,8\}\), \(B=\{2,8,9\}\) y \(C=\{0,4,8,9\}\), calcule:

\(\overline{A \cap B} - (A \cup C)\)

---

### Datos
- \(U=\{0,2,4,6,8,9\}\)
- \(A=\{0,2,8\}\)
- \(B=\{2,8,9\}\)
- \(C=\{0,4,8,9\}\)

---

### Procedimiento

**1) Calcular \(A \cap B\):**

La intersección son los elementos comunes:

- \(A \cap B = \{2,8\}\)

---

**2) Calcular el complemento \(\overline{A \cap B}\):**

Por definición:

- \(\overline{A \cap B} = U - (A \cap B)\)
- \(= \{0,2,4,6,8,9\} - \{2,8\}\)
- \(= \{0,4,6,9\}\)

---

**3) Calcular \(A \cup C\):**

Unir ambos conjuntos:

- \(A \cup C = \{0,2,8\} \cup \{0,4,8,9\}\)
- \(= \{0,2,4,8,9\}\)

---

**4) Calcular la diferencia final**

\[
\overline{A \cap B} - (A \cup C)
\]

- \(\{0,4,6,9\} - \{0,2,4,8,9\}\)
- Eliminamos 0, 4 y 9
- Queda:

- \(\{6\}\)

---

### Resultado

\[
\overline{A \cap B} - (A \cup C) = \{6\}
\]


---

## Ejercicio 3 (Página 11)

**Enunciado:**  
Considere los conjuntos \(A=\{1,2\}\) y \(B=\{1,2,3\}\). Calcule:
- \(P(B-A)\)
- \(P(B)-P(A)\)

### Datos
- \(A=\{1,2\}\)
- \(B=\{1,2,3\}\)

### Procedimiento

**1) Calcular \(B-A\):**  
\(B-A\) son los elementos de \(B\) que no están en \(A\):
- \(B-A = \{1,2,3\} - \{1,2\} = \{3\}\)

Ahora el conjunto potencia:
- \(P(\{3\}) = \{\varnothing,\{3\}\}\)

**2) Calcular \(P(B)-P(A)\):**  
\(P(B)\) son todos los subconjuntos de \(\{1,2,3\}\).  
\(P(A)\) son todos los subconjuntos de \(\{1,2\}\).

Los subconjuntos que están en \(P(B)\) pero **no** están en \(P(A)\) son los que incluyen el elemento **3**:
- \(\{3\}, \{1,3\}, \{2,3\}, \{1,2,3\}\)

### Resultado
- \(P(B-A)=\{\varnothing,\{3\}\}\)
- \(P(B)-P(A)=\{\{3\},\{1,3\},\{2,3\},\{1,2,3\}\}\)


---

## Ejercicio 4 (Página 12)

**Enunciado:**  
Suponga \(U=\{a,b,c,d,e,f,g,h,i\}\) y
\(A=\{a,b,c,d,e\}\), \(B=\{d,e,f,g\}\), \(C=\{e,f,g,h,i\}\),
\(D=\{a,c,e,g,i\}\), \(E=\{b,d,f,h\}\), \(F=\{a,e,i\}\).
Determine:
- \(E^c \cap F\)
- \((E \cup F)^c\)
- \((D \Delta F)^c \cup B\)
- \(P(F)\)
- \(|P(F)|\)

### Datos
- \(U=\{a,b,c,d,e,f,g,h,i\}\)
- \(E=\{b,d,f,h\}\)
- \(F=\{a,e,i\}\)
- \(D=\{a,c,e,g,i\}\)
- \(B=\{d,e,f,g\}\)

### Procedimiento

**1) \(E^c \cap F\):**  
Primero \(E^c = U - E = \{a,c,e,g,i\}\).  
Luego:
- \(E^c \cap F = \{a,c,e,g,i\} \cap \{a,e,i\} = \{a,e,i\}\)

**2) \((E \cup F)^c\):**  
\(E \cup F = \{b,d,f,h\} \cup \{a,e,i\} = \{a,b,d,e,f,h,i\}\)  
Entonces:
- \((E \cup F)^c = U - (E \cup F) = \{c,g\}\)

**3) \((D \Delta F)^c \cup B\):**  
Como \(F \subseteq D\), entonces:
- \(D \Delta F = (D-F) \cup (F-D) = (D-F) \cup \varnothing = D-F\)
- \(D-F = \{a,c,e,g,i\} - \{a,e,i\} = \{c,g\}\)

Luego:
- \((D \Delta F)^c = U - \{c,g\} = \{a,b,d,e,f,h,i\}\)

Finalmente:
- \((D \Delta F)^c \cup B = \{a,b,d,e,f,h,i\} \cup \{d,e,f,g\} = \{a,b,d,e,f,g,h,i\}\)

**4) \(P(F)\) y 5) \(|P(F)|\):**  
\(F=\{a,e,i\}\) tiene 3 elementos, por tanto \(|P(F)|=2^3=8\).  
Listamos todos los subconjuntos:
- \(P(F)=\{\varnothing,\{a\},\{e\},\{i\},\{a,e\},\{a,i\},\{e,i\},\{a,e,i\}\}\)

### Resultado
- \(E^c \cap F = \{a,e,i\}\)
- \((E \cup F)^c = \{c,g\}\)
- \((D \Delta F)^c \cup B = \{a,b,d,e,f,g,h,i\}\)
- \(P(F)=\{\varnothing,\{a\},\{e\},\{i\},\{a,e\},\{a,i\},\{e,i\},\{a,e,i\}\}\)
- \(|P(F)|=8\)

