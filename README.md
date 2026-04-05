# Análisis de Datos: Fórmula 1 (2018-2023)

Este repositorio contiene un análisis exploratorio de datos (EDA) sobre la **Fórmula 1**, desarrollado íntegramente en **R** y presentado mediante **Quarto**. El objetivo es identificar patrones de fiabilidad, rendimiento de pilotos y el impacto de condiciones climáticas en la competición.

**[VER REPORTE INTERACTIVO AQUÍ](https://github.com/00felipeporta/analisis_formula1_2018_2023)**

---

## Vista Previa del Proyecto
<img width="561" height="343" alt="image" src="https://github.com/user-attachments/assets/0799fd18-e0a0-4554-9c9f-7d11fb46736a" />

---

## Resumen del Análisis
El proyecto aborda preguntas clave del mundo del automovilismo:
- **Fiabilidad por Escudería:** Comparativa de estados de finalización, con foco especial en Mercedes.
- **Rendimiento en el Podio:** Distribución de victorias y puestos entre los pilotos líderes (Verstappen, Hamilton, Bottas).
- **Influencia Climática:** Análisis de cómo la lluvia y la temperatura de pista afectan los tiempos de carrera.

---

## Herramientas y Tecnologías
- **Lenguaje:** R
- **Reporting:** Quarto (HTML interactivo con `embed-resources`)
- **Librerías principales:**
  - `tidyverse` (Manipulación de datos)
  - `ggplot2` (Visualización avanzada)
  - `janitor` (Limpieza de datos)
  - `knitr` (Formateo de tablas)

---

## Estructura del Repositorio
- `index.html`: El reporte final renderizado (página web).
- `formula1.qmd`: Código fuente en Quarto.
- `carreras.csv`, `conductores.csv`, `constructores.csv`, `resultados.csv`.: Datasets utilizados para el análisis.
- `README.md`: Descripción del proyecto.

---

## Conclusiones Clave
1. **Consistencia de Mercedes:** A pesar de los incidentes, la escudería muestra un porcentaje de finalización superior a la media.
2. **Impacto de Lluvia:** Se evidencia una dispersión significativamente mayor en los tiempos de finalización bajo condiciones de pista mojada.
3. **Correlación Térmica:** Existe una relación lineal positiva robusta entre la temperatura ambiente y la de pista, fundamental para la estrategia de neumáticos.

---

## Contacto
Si tenés alguna duda o querés conectar para hablar sobre análisis de datos:
- **GitHub:** 00felipeporta - https://github.com/00felipeporta
