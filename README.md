# Simulación Computacional y Análisis de Resultados

## Tarea 3 — Simulación Estocástica

### 1. Descripción del proyecto

Este proyecto consiste en una simulación Monte Carlo de tiempos de espera en un servicio de atención al cliente, desarrollada en Python mediante un notebook de Google Colab.

El objetivo es generar datos aleatorios, realizar un análisis estadístico e interpretar la incertidumbre de los resultados para comprender cómo la simulación estocástica puede apoyar la toma de decisiones.

### 2. Problema de estudio

Una empresa desea conocer el comportamiento de los tiempos de espera de sus clientes antes de recibir atención.

Debido a que estos tiempos pueden variar entre clientes, se utiliza una simulación Monte Carlo para generar una muestra de 1,000 tiempos de espera y estimar el tiempo promedio, la variabilidad y la incertidumbre asociada a la media.

### 3. Metodología

La simulación se desarrolla bajo los siguientes supuestos:

- Se utiliza una distribución exponencial para representar los tiempos de espera.
- La media teórica de los tiempos de espera es de 8 minutos.
- Se generan 1,000 observaciones aleatorias.
- Se utiliza la semilla aleatoria 42 para garantizar la reproducibilidad.
- Cada observación representa a un cliente y se considera independiente de las demás.

Los datos generados son hipotéticos y se utilizan exclusivamente con fines académicos.

### 4. Análisis estadístico

El notebook calcula los siguientes estadísticos:

| Estadístico | Descripción |
|---|---|
| Media | Tiempo promedio de espera de los clientes simulados. |
| Desviación estándar | Medida de la variabilidad de los tiempos de espera. |
| Mínimo | Menor tiempo de espera observado. |
| Máximo | Mayor tiempo de espera observado. |
| Intervalo de confianza del 95 % | Rango estimado para la media poblacional. |

El intervalo de confianza se calcula utilizando la distribución t de Student, considerando la desviación estándar muestral y el tamaño de la muestra.

### 5. Resultados

El notebook presenta:

- Una tabla con los resultados del análisis estadístico.
- Un histograma de la distribución de los tiempos de espera.
- La media simulada y la media teórica para facilitar su comparación.
- Una interpretación de los resultados y una conclusión sobre la utilidad de la simulación.

### 6. Herramientas utilizadas

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- SciPy

### 7. Cómo ejecutar el proyecto

1. Descarga el archivo `Tarea_3_Simulacion_Monte_Carlo.ipynb` de este repositorio.
2. Abre [Google Colab](https://colab.research.google.com/).
3. Selecciona **Archivo → Subir notebook**.
4. Carga el archivo descargado.
5. Selecciona **Entorno de ejecución → Ejecutar todas**.
6. Consulta los resultados estadísticos, la gráfica y la conclusión generada.

El notebook contiene el código documentado y puede ejecutarse sin necesidad de cargar archivos de datos externos.

### 8. Conclusión

La simulación Monte Carlo permite estudiar el comportamiento de los tiempos de espera mediante la generación de datos aleatorios y el análisis de sus propiedades estadísticas.

El uso de una semilla fija garantiza la reproducibilidad del experimento, mientras que el intervalo de confianza permite expresar la incertidumbre de la estimación de la media.

Los resultados pueden utilizarse como una primera aproximación para evaluar el desempeño de un servicio de atención al cliente y analizar posibles medidas para reducir los tiempos de espera.

Sin embargo, para tomar decisiones operativas reales, sería necesario utilizar datos históricos y considerar factores como los horarios de mayor demanda, la capacidad de atención y la variabilidad del servicio.

---

**Curso:** Simulación Estocástica  
**Actividad:** Tarea 3. Simulación Computacional y Análisis de Resultados  
**Modalidad:** Individual  
**Lenguaje:** Python  
**Entorno de ejecución:** Google Colab
