# 🖥️ Simulador de Algoritmos de Asignación de Memoria

::: {align="center"}
![Memory
Allocation](https://img.shields.io/badge/Memory-Allocation-0078d4?style=for-the-badge)
![Best
Fit](https://img.shields.io/badge/Algorithm-Best%20Fit-2e7d32?style=for-the-badge)
![Worst
Fit](https://img.shields.io/badge/Algorithm-Worst%20Fit-c62828?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Herramienta interactiva para visualizar y comparar estrategias de asignación de memoria en Sistemas Operativos
:::

------------------------------------------------------------------------

# 🎓 Introducción

Este simulador interactivo permite visualizar en tiempo real el
comportamiento de los algoritmos:

-   **Best Fit (Mejor Ajuste)**
-   **Worst Fit (Peor Ajuste)**

en un entorno de memoria simulada.

El objetivo es comprender cómo cada estrategia afecta:

-   La fragmentación externa\
-   La utilización de memoria\
-   La cantidad de procesos asignados\
-   La eficiencia general del sistema

------------------------------------------------------------------------

# 🧠 Contexto: Gestión de Memoria

En un sistema operativo, la memoria RAM se divide en bloques o
particiones.\
Cuando un proceso necesita ejecutarse, el sistema debe decidir dónde
colocarlo.

    ┌─────────────────────────────────────┐
    │            MEMORIA RAM              │
    ├─────────────────────────────────────┤
    │ Bloque 1: 200 KB   [LIBRE]          │
    │ Bloque 2: 150 KB   [Proceso A]      │
    │ Bloque 3: 300 KB   [LIBRE]          │
    │ Bloque 4: 100 KB   [Proceso B]      │
    │ Bloque 5: 250 KB   [LIBRE]          │
    └─────────────────────────────────────┘

------------------------------------------------------------------------

# 🎯 Algoritmos Implementados

## 1️⃣ Best Fit (Mejor Ajuste)

Selecciona el bloque libre más pequeño que pueda contener el proceso.

### Ventajas

-   Minimiza el desperdicio inmediato.
-   Conserva bloques grandes.

### Desventajas

-   Genera fragmentos pequeños.
-   Puede aumentar la fragmentación externa.

------------------------------------------------------------------------

## 2️⃣ Worst Fit (Peor Ajuste)

Selecciona el bloque libre más grande disponible.

### Ventajas

-   Genera fragmentos grandes reutilizables.
-   Puede retrasar la fragmentación inicial.

### Desventajas

-   Consume rápidamente bloques grandes.
-   No siempre optimiza la utilización total.

------------------------------------------------------------------------

# 📊 Métricas Mostradas

Fragmentación Externa:

    Fragmentación = Memoria libre total − Mayor bloque libre

Memoria Utilizada (%)

Procesos Asignados

------------------------------------------------------------------------

# 🧠 Reflexión

El simulador permite analizar cómo diferentes estrategias de asignación
impactan la eficiencia del sistema.

No existe un algoritmo universalmente superior; su rendimiento depende
del patrón de procesos y del contexto de uso.

------------------------------------------------------------------------

# 📚 Referencias

Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). Operating System
Concepts (10th ed.). Wiley.\
Tanenbaum, A. S., & Bos, H. (2015). Modern Operating Systems (4th ed.).
Pearson.\
Stallings, W. (2018). Operating Systems: Internals and Design
Principles. Pearson.

------------------------------------------------------------------------

# 🤖 Cláusula de Uso de Inteligencia Artificial

Se utilizó inteligencia artificial como herramienta de apoyo para
mejorar la estructura y redacción del documento.\
La implementación y el análisis corresponden al trabajo del autor.
