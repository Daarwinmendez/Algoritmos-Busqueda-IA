# 🧠 Algoritmos de Búsqueda en la Inteligencia Artificial

Este notebook presenta un abordaje introductorio a los **algoritmos de búsqueda clásica** en Inteligencia Artificial, implementados completamente **desde cero y sin librerías externas**.

### 📌 Objetivo

Explorar cómo funcionan internamente algunos de los algoritmos más representativos de la IA, como:

- 🔍 **DFS** – Búsqueda en Profundidad  
- 🌐 **BFS** – Búsqueda en Amplitud  
- 💰 **UCS** – Búsqueda de Costo Uniforme  

El enfoque está orientado a la comprensión práctica de sus estructuras y lógica de ejecución, utilizando:

- `Stack` (pila)
- `Queue` (cola)
- `PriorityQueue` (cola de prioridad)

Además, se incluye una clase `Graph` que permite cargar grafos desde archivos `.txt`, soportando:
- Grafos dirigidos o no dirigidos
- Grafos ponderados (con pesos)

---

### 🧪 ¿Por qué es importante?

Estos algoritmos se utilizan como base en múltiples aplicaciones reales, tales como:

- 🚗 Planificación de rutas y logística
- 🎮 Motores de juego y simuladores
- 🤖 Agentes inteligentes y robótica
- 📊 Optimización de decisiones
- 🔎 Exploración de espacios de búsqueda complejos

Dominar su implementación manual permite construir una base sólida para luego aplicar técnicas más avanzadas como:
- A* y búsquedas heurísticas
- Algoritmos genéticos
- Aprendizaje por refuerzo

---

### 📂 Estructura del proyecto

```bash
.
├── Algoritmos_de_Busqueda_C2_2025.ipynb   # Notebook principal con las clases y pruebas
├── graph1.txt                  # Grafo para DFS y BFS (sin pesos)
├── graph2.txt                  # Grafo para UCS (con pesos)
└── README.md                   # Este archivo

```

### ▶️ ¿Cómo usar?

1. Sube o edita los archivos `graph1.txt` y `graph2.txt` con tus grafos personalizados.
2. Ejecuta el notebook en Google Colab o Jupyter Notebook.
3. Cambia los nodos de inicio y final en las líneas:

```python
dfs = DFS(graph1, start='A', end='F')
bfs = BFS(graph1, start='A', end='F')
ucs = UCS(graph2, start='A', end='M')
```
