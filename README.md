# Factores Socioeconómicos y Probabilidad de Empleo Femenino  
**Análisis causal y probabilístico utilizando DAGs y Redes Bayesianas**  

## 📌 Descripción del proyecto
Este proyecto analiza cómo diferentes variables socioeconómicas afectan la probabilidad de que una mujer esté empleada en Ecuador.  
Para ello, se utiliza la base de datos **ENEMDU Anual 2024**, que contiene información a nivel de hogar y persona.  
El estudio emplea **DAGs (Grafos Acíclicos Dirigidos)** para identificar relaciones causales y **Redes Bayesianas** para calcular probabilidades condicionales.

---

## 🧾 Datos utilizados
- **Fuente**: Encuesta Nacional de Empleo, Desempleo y Subempleo (ENEMDU) - INEC (2024)  
- **Unidad de análisis**: Mujeres de **20 a 60 años** de edad.  
- **Variables principales**:  
  - Estado civil  
  - Raza  
  - Nivel de escolaridad  
  - Número de personas en el hogar  
  - Ingreso de la pareja
  - Edad
  - Zona geográfica

---

## 🔍 Metodología
1. **Construcción del DAG**:
   - Se aplicó un algoritmo de descubrimiento de estructura para determinar las relaciones causales más probables entre las variables.
   - Se realizaron dos modelos:  
     - **Modelo 1**: Conjunto inicial de variables. El ingreso de la pareja se calcula considerando únicamente al jefe/a del hogar y su cónyuge.
     - **Modelo 2**: Modelo 1 + El ingreso de la pareja incluye también combinaciones de hija–yerno e hijo–nuera presentes en el hogar.

2. **Análisis con Redes Bayesianas**:
   - Se utilizó el **Modelo 2** para construir la red bayesiana.
   - Se calcularon **probabilidades condicionales** de empleo femenino según las variables socioeconómicas.

3. **Visualización de resultados**:
   - Grafo causal (DAG).
   - Gráficas comparativas de probabilidades.

---

## 📂 Estructura del repositorio  

```plaintext

├── slides                    # Diapositivas con presentación de resultados
├── empleo_mujer.ipynb        # Script del proyecto
├── requirements.txt          # Librerías necesarias
├── README.md                 # Este archivo

