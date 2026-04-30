# 🏗️ Analizador de Esfuerzos en Columnas (Flexión Compuesta)

Este proyecto es una herramienta de ingeniería desarrollada en **Python** para calcular y visualizar el esfuerzo normal total ($\sigma$) en diferentes secciones transversales (Perfil L, Perfil I y Circular) sometidas a carga axial y momentos flectores combinados.

## 🚀 Características
- **Cálculo Automático**: Determina el centroide ($\bar{x}, \bar{y}$) y los momentos de inercia ($I_x, I_y$) de secciones complejas.
- **Análisis por Puntos**: Calcula el esfuerzo exacto en los puntos críticos de la geometría.
- **Visualización Gráfica**: Genera una pestaña emergente con el dibujo técnico de la sección, la ubicación del centroide y los resultados en MPa utilizando `Matplotlib`.
- **Flexión Compuesta**: Aplica la fórmula general:
  $$\sigma = -\frac{P}{A} + \frac{M_x \cdot y}{I_x} - \frac{M_y \cdot x}{I_y}$$

## 🛠️ Requisitos
Para ejecutar este programa, necesitas tener instalado Python y la librería para gráficas:

```bash
pip install matplotlib numpy
