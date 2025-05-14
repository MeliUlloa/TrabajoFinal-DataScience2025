# Análisis de la Deforestación en Argentina 🌳

Este trabajo se enfoca en el análisis y visualización de la deforestación en Argentina entre los años 2001 y 2020. Con el aumento de la preocupación por la pérdida de bosques y su impacto ambiental, este análisis busca explorar patrones temporales y territoriales de la deforestación, con el objetivo de entender las provincias y departamentos más afectados.

## Objetivo

Analizar la evolución de la deforestación en Argentina entre los años 2001 y 2020 mediante técnicas de análisis de datos, con el fin de identificar las provincias y departamentos más afectados por la pérdida de cobertura vegetal. Asimismo, se busca explorar patrones temporales y territoriales que permitan comprender mejor la distribución y magnitud del fenómeno, utilizando herramientas de procesamiento, visualización y exploración de datos.


---

## Integrantes

- [Cruz Nicole]
- [Ulloa Soto Melina Gimena]

---

## Fuente de Datos

Los datos utilizados para este análisis provienen de [ Plataforma Trase](https://trase.earth/open-data/datasets/spatial-metrics-argentina-territorial-deforestation). Estos datos incluyen información sobre la cantidad de hectáreas deforestadas por provincia y año, desde 2001 hasta 2020.

---

## Estructura del Repositorio

El repositorio contiene los siguientes archivos:

- `README.md`: Documento que describe el proyecto.
- `dataset_deforestacion.csv`: Dataset con información de hectáreas deforestadas por provincia y año.
- `analisis_deforestacion.ipynb`: Jupyter notebook que contiene el análisis, visualización y predicción sobre la deforestación.
---

## Pasos de Limpieza de Datos

Los pasos que seguimos para limpiar y preparar los datos son los siguientes:

1. **Carga de los datos**: Importamos el dataset y verificamos su estructura inicial.
2. **Visualización inicial**: Realizamos una inspección visual de los primeros registros del dataset.
3. **Análisis de variables**: Identificamos y verificamos el tipo de cada variable (numérica, categórica, etc.).
4. **Revisión de nulos**: Comprobamos la existencia de valores nulos y los eliminamos o reemplazamos si es necesario.
5. **Eliminación de valores atípicos**: Usamos gráficos como boxplots para detectar y eliminar posibles valores atípicos.
6. **Normalización y escalado**: Aplicamos técnicas de escalado para garantizar que las variables numéricas tengan la misma escala y sean comparables.

---

## Metodología

El análisis se realizó utilizando **Python** y diversas librerías de análisis de datos como **Pandas**, **Numpy**, y **Matplotlib**. Se emplearon técnicas estadísticas para examinar los patrones de deforestación a lo largo del tiempo y por región.

Los pasos realizados fueron los siguientes:

- **Exploración de datos**: Se hizo un análisis descriptivo para comprender mejor la estructura y las distribuciones de los datos.
- **Visualización**: Se generaron gráficos que muestran la evolución de la deforestación en Argentina, utilizando **Matplotlib** y **Seaborn**.
- **Predicción**: Implementamos modelos predictivos para estimar la deforestación futura en algunas de las provincias más afectadas.

---

## Herramientas

El análisis fue realizado con las siguientes herramientas:

- **Google Colab**: Plataforma en línea para ejecutar el código de manera interactiva.
- **Pandas**: Librería de Python para el manejo y análisis de datos.
- **Matplotlib y Seaborn**: Herramientas de visualización de datos.
- **GitHub**: Para el control de versiones y la gestión del proyecto.

---

## Cómo Ejecutar el Proyecto

Para replicar este análisis en tu propio entorno, sigue estos pasos:

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
