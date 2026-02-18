# Semana 2 — Ejercicios prácticos
## Módulo 3. Fundamentos de conjuntos (Parte I)

**Fuente:** Módulo 3 (prácticas de páginas 11 y 12).

---

## Ejercicio 1 (Página 11)

**Enunciado:**  
Si U = {1,2,3,4,5}, A = {2,5} y B = {1,5}, calcule:
- A^c
- (A ∪ B)^c
- B - A

### Datos
- U = {1,2,3,4,5}
- A = {2,5}
- B = {1,5}

### Procedimiento

**1) Complemento de A:**  
A^c = U - A  

U - A = {1,2,3,4,5} - {2,5} = {1,3,4}

**2) Complemento de la unión:**  
A ∪ B = {2,5} ∪ {1,5} = {1,2,5}

(A ∪ B)^c = U - {1,2,5} = {3,4}

**3) Diferencia B - A:**  
B - A = {1,5} - {2,5} = {1}

### Resultado
- A^c = {1,3,4}
- (A ∪ B)^c = {3,4}
- B - A = {1}

---

## Ejercicio 2 (Página 11)

**Enunciado:**  
Si U = {0,2,4,6,8,9}, A = {0,2,8}, B = {2,8,9} y C = {0,4,8,9}, calcule:

(A ∩ B)^c - (A ∪ C)

---

### Datos
- U = {0,2,4,6,8,9}
- A = {0,2,8}
- B = {2,8,9}
- C = {0,4,8,9}

---

### Procedimiento

**1) A ∩ B**

A ∩ B = {2,8}

**2) Complemento**

(A ∩ B)^c = U - {2,8}  
= {0,4,6,9}

**3) A ∪ C**

A ∪ C = {0,2,8} ∪ {0,4,8,9}  
= {0,2,4,8,9}

**4) Diferencia final**

{0,4,6,9} - {0,2,4,8,9}  
= {6}

### Resultado

(A ∩ B)^c - (A ∪ C) = {6}

---

## Ejercicio 3 (Página 11)

**Enunciado:**  
Considere A = {1,2} y B = {1,2,3}. Calcule:
- P(B - A)
- P(B) - P(A)

### Datos
- A = {1,2}
- B = {1,2,3}

### Procedimiento

**1) B - A**

B - A = {3}

P({3}) = { ∅, {3} }

**2) P(B) - P(A)**

Subconjuntos de B que contienen el elemento 3:

{3}, {1,3}, {2,3}, {1,2,3}

### Resultado
- P(B - A) = { ∅, {3} }
- P(B) - P(A) = { {3}, {1,3}, {2,3}, {1,2,3} }

---

## Ejercicio 4 (Página 12)

**Enunciado:**  
Sea U = {a,b,c,d,e,f,g,h,i}  
A = {a,b,c,d,e}  
B = {d,e,f,g}  
C = {e,f,g,h,i}  
D = {a,c,e,g,i}  
E = {b,d,f,h}  
F = {a,e,i}

Calcule:
- E^c ∩ F
- (E ∪ F)^c
- (D Δ F)^c ∪ B
- P(F)
- |P(F)|

---

### Procedimiento

**1) E^c ∩ F**

E^c = U - E = {a,c,e,g,i}

E^c ∩ F = {a,e,i}

---

**2) (E ∪ F)^c**

E ∪ F = {a,b,d,e,f,h,i}

Complemento:

(U - (E ∪ F)) = {c,g}

---

**3) (D Δ F)^c ∪ B**

Como F ⊆ D:

D Δ F = D - F  
= {c,g}

Complemento:

(D Δ F)^c = {a,b,d,e,f,h,i}

Unión con B:

{a,b,d,e,f,h,i} ∪ {d,e,f,g}  
= {a,b,d,e,f,g,h,i}

---

**4) P(F)**

F = {a,e,i}

P(F) = {
∅,
{a},
{e},
{i},
{a,e},
{a,i},
{e,i},
{a,e,i}
}

|P(F)| = 8

---

### Resultado Final

- E^c ∩ F = {a,e,i}
- (E ∪ F)^c = {c,g}
- (D Δ F)^c ∪ B = {a,b,d,e,f,g,h,i}
- P(F) tiene 8 elementos
