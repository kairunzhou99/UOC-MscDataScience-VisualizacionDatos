
# PEC 2 - Visualización de Datos

## 1. Descripción

Este repositorio contiene tres visualizaciones desarrolladas para la PEC 2 de la asignatura **Visualización de Datos** de la Universitat Oberta de Catalunya (UOC).

El objetivo es explorar diferentes técnicas de representación gráfica, comprender sus características, ventajas y limitaciones, y aplicarlas a conjuntos de datos abiertos para comunicar información de manera clara y efectiva.

Las técnicas utilizadas son:

1. **Cartograms:** representación geográfica de la población mundial.
2. **Parallel Coordinates Plot:** análisis multidimensional del dataset Iris.
3. **Bullet Graphs:** seguimiento de los objetivos de energías renovables de la Unión Europea.

---

## 2. Cartograms

**Herramientas:** R, ggplot2, sf y cartogram.  
**Fuentes:** Our World in Data y Natural Earth.  
**Periodo:** 2023.

Esta visualización representa la distribución de la población mundial mediante un cartograma, donde la superficie de cada país se modifica proporcionalmente a su población.

Se compara un mapa geográfico convencional con un cartograma para mostrar las diferencias entre la extensión territorial y el peso demográfico de los países.

**Objetivo:** identificar las desigualdades en la distribución de la población mundial y demostrar cómo la distorsión geográfica puede facilitar la interpretación de determinados datos.

### Visualización

![Cartograma de población mundial](cartograma_poblacion_2023_v3.png)

---

## 3. Parallel Coordinates Plot

**Herramientas:** Python y Plotly.  
**Fuente:** UCI Machine Learning Repository.  
**Dataset:** Iris (150 observaciones).

Esta visualización utiliza un gráfico de coordenadas paralelas para comparar cuatro características de tres especies de flores Iris:

- Longitud del sépalo.
- Anchura del sépalo.
- Longitud del pétalo.
- Anchura del pétalo.

Cada flor está representada mediante una línea que atraviesa los cuatro ejes paralelos. Los colores permiten identificar las especies Setosa, Versicolor y Virginica.

**Objetivo:** analizar las relaciones entre múltiples variables cuantitativas e identificar patrones que permitan diferenciar las especies.

La visualización es interactiva y permite seleccionar intervalos de valores en los distintos ejes.

### Visualización interactiva

[**Abrir Parallel Coordinates Plot**](parallel_coordinates_plot.html)

---

## 4. Bullet Graphs

**Herramienta:** Tableau Desktop.  
**Fuente:** Eurostat.  
**Periodo:** 2023–2025.

Esta visualización compara el porcentaje de energías renovables en el consumo final bruto de energía de la Unión Europea con el objetivo del **42,5 % establecido para 2030**.

Los Bullet Graphs utilizan tres elementos principales:

- **Barras horizontales:** representan los porcentajes observados.
- **Líneas de referencia:** indican el objetivo europeo para 2030.
- **Bandas de fondo:** muestran intervalos de referencia ilustrativos, que no representan objetivos oficiales.

**Objetivo:** evaluar visualmente el progreso de la Unión Europea hacia su objetivo de energías renovables.

### Visualización

![Bullet Graph de energías renovables](bullet_graph_energias_renovables.png)

---

## 5. Fuentes de datos

| Técnica | Fuente | Enlace |
|---|---|---|
| Cartograms | Our World in Data | [Acceder](https://ourworldindata.org/) |
| Cartograms | Natural Earth | [Acceder](https://www.naturalearthdata.com/) |
| Parallel Coordinates | UCI Machine Learning Repository | [Dataset Iris](https://archive.ics.uci.edu/dataset/53/iris) |
| Bullet Graphs | Eurostat | [Datos de energías renovables](https://ec.europa.eu/eurostat/databrowser/view/nrg_ind_ren/default/table?lang=en) |

## 6. Herramientas utilizadas

| Herramienta | Aplicación |
|---|---|
| R | Procesamiento de datos geográficos y creación de cartogramas |
| ggplot2 y cartogram | Visualización geográfica |
| Python | Preparación y análisis de datos |
| Plotly | Visualización interactiva multidimensional |
| Tableau Desktop | Creación de Bullet Graphs |
| GitHub Pages | Publicación de las visualizaciones |

---

## 7. Referencias

- [The Data Visualisation Catalogue](https://datavizcatalogue.com/)
- [Data Viz Project](https://datavizproject.com/)
- [From Data to Viz](https://www.data-to-viz.com/)
- [Chartmaker Directory](https://chartmaker.visualisingdata.com/)
