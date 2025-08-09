# Factores Socioeconómicos y Probabilidad de Empleo Femenino  
**Análisis causal y probabilístico utilizando DAGs y Redes Bayesianas**  

## 📌 Descripción  
Este proyecto analiza cómo distintas variables socioeconómicas influyen en la probabilidad de que una mujer esté empleada.  
Se utiliza como fuente de datos la **Encuesta Nacional de Empleo, Desempleo y Subempleo (ENEMDU) - Ecuador 2024**, con un enfoque de **modelado causal** y **redes bayesianas**.  

El análisis se estructura en tres fases principales:  
1. **Preprocesamiento de datos** y selección de variables socioeconómicas.  
2. **Descubrimiento de estructura causal (DAG)** mediante algoritmos de aprendizaje.  
3. **Construcción de redes Bayesianas** para estimar probabilidades condicionales y explorar escenarios hipotéticos.  

---

## 📊 Variables utilizadas  
- **Estado civil**  
- **Raza**  
- **Escolaridad** (años de estudio)  
- **Número de personas en el hogar**  
- **Ingreso de la pareja**  
- **Edad**
- **Zona geográfica**

---

## 📂 Estructura del repositorio  
├── data/              # Datos procesados o scripts para descarga
├── notebooks/         # Jupyter Notebooks con análisis paso a paso
├── src/               # Scripts de Python para procesamiento y modelado
├── figures/           # Imágenes del DAG, gráficos y visualizaciones
├── README.md          # Este archivo
└── requirements.txt   # Librerías necesarias


├── slides/ # Diapositivas con presentación de resultados
├── README.md # Este archivo
└── requirements.txt # Librerías necesarias
