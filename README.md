# Taller de Recursividad en Java

**Estudiante:** Viktor Manuelle Velasco Gonzalez

---

## Descripción del Taller

Este taller consiste en la implementación de 13 ejercicios en Java utilizando el paradigma de **recursividad**. Cada ejercicio resuelve un problema matemático o de procesamiento de datos mediante funciones que se llaman a sí mismas, siguiendo la estructura de:

- **Caso base:** condición que detiene la recursión.
- **Caso recursivo:** llamada a la misma función reduciendo el problema.

### Ejercicios implementados

1. **Factorial** — Leer un número entero y calcular su factorial.
2. **Sumatoria** — Leer un número entero y calcular la sumatoria hasta ese número.
3. **Sumatoria fraccionaria** — Calcular la sumatoria `1 + 1/2 + 1/3 + … + 1/n`.
4. **Invertir número** — Leer un número entero e invertirlo. Ej: `123 → 321`.
5. **Suma de dígitos** — Leer un número y sumar sus dígitos. Ej: `123 → 6`.
6. **Potencia** — Leer una base y un exponente, y calcular la potencia.
7. **Máximo Común Divisor (MCD)** — Calcular el MCD de dos números enteros usando el algoritmo de Euclides.
8. **Cociente de división entera** — Calcular el cociente de dos números mediante restas sucesivas.
9. **Multiplicación** — Multiplicar dos números mediante sumas sucesivas.
10. **Suma de vector** — Leer n valores, almacenarlos en un arreglo y sumar sus elementos.
11. **Suma de matriz** — Crear una matriz de tamaño m×n y sumar todos sus elementos.
12. **Serie de Fibonacci** — Leer un límite e imprimir la serie de Fibonacci hasta ese valor.
13. **Función de Ackermann** — Calcular el valor de la función de Ackermann para dos enteros m y n.

---

## Instrucciones para ejecutar los programas

### Requisitos previos

- Tener instalado **Java JDK 8 o superior**.
- Tener un compilador de Java disponible (`javac`) o un IDE como **IntelliJ IDEA**, **Eclipse** o **VS Code**.

### Pasos para compilar y ejecutar

**1. Compilar el archivo:**
```bash
javac NombreDelArchivo.java
```

**2. Ejecutar el programa:**
```bash
java NombreDelArchivo
```

**3. Seguir las instrucciones en consola**, ingresando los valores que el programa solicite.

### Ejemplo con el ejercicio de Factorial

```bash
javac Factorial.java
java Factorial
```
```
Ingresa un número entero para calcular su factorial: 5
5! = 120
```

### Ejemplo con el ejercicio de MCD

```bash
javac MCD.java
java MCD
```
```
Ingresa el primer número (M): 48
Ingresa el segundo número (N): 18
El MCD de 48 y 18 es: 6
```

---

## Estructura de archivos

```
taller-recursividad/
├── src/
│   ├── Factorial.java
│   ├── FactorialEntero.java
│   ├── InvertirNumero.java
│   ├── SumaDigitos.java
│   ├── Potencia.java
│   ├── MCD.java
│   ├── Cociente.java
│   ├── Multiplicacion.java
│   ├── SumaVector.java
│   ├── SumaMatriz.java
│   ├── Fibonacci.java
│   └── Ackermann.java
└── README.md
```

---

> **Nota:** Cada archivo `.java` debe compilarse y ejecutarse de forma independiente. El nombre del archivo debe coincidir exactamente con el nombre de la clase pública que contiene.
