# Solución Problema 3 - Control de Inventario y Reabastecimiento
**Curso:** Fundamentos de Programación (Código 213022)  
**Universidad:** Universidad Nacional Abierta y a Distancia (UNAD)  
**Fase:** Fase 5 - Evaluación Final POA  

---
## 📌 Enunciado del Problema
![Enunciado del Problema](<problema.png>)

## 📌 Descripción del Problema
El programa procesa una matriz de inventario de artículos donde cada elemento contiene:
* Código del artículo
* Nombre del artículo
* Stock actual
* Stock mínimo requerido

A partir de esta información, el sistema aplica la lógica de negocio para determinar automáticamente si un artículo requiere reabastecimiento y calcula la cantidad exacta a solicitar:
* **Si `Stock Actual < Stock Mínimo`**: $\text{Cantidad a pedir} = \text{Stock Mínimo} - \text{Stock Actual}$.
* **Si `Stock Actual >= Stock Mínimo`**: $\text{Cantidad a pedir} = 0$.

---

## 🛠️ Tecnologías y Paradigma
* **Lenguaje:** Python 3
* **Paradigma:** Programación Estructurada (uso de Funciones, Condicionales y Listas/Matrices)

---

## 🚀 Ejecución del Código
Para ejecutar la solución localmente, asegúrate de tener Python instalado y ejecuta:

```bash
python solucion_problema3.py
