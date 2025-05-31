# Student Performance EDA  
**Note:** English translation is available below.

Este repositorio contiene un análisis exploratorio de datos (EDA) realizado sobre el dataset **Students Performance in Exams**, tomado de Kaggle:  
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data

El archivo **StudentsPerformance.csv** está incluido en este repositorio para facilitar la reproducción de los análisis. Si deseas explorar otros enfoques y notebooks hechos por la comunidad, puedes visitar directamente la página del dataset en Kaggle.

## Contenido del repositorio

- Notebook principal (Jupyter Notebook): `StudentPerformance_EDA.ipynb`
- Dataset: `StudentsPerformance.csv`
- Archivos generados: reportes de Sweetviz y Pandas Profiling (opcional si se incluyen)

## Cómo usar este proyecto

### Usando Jupyter Notebook (local)

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/johnpl765/EDA-Students-Performance-in-Exam.git
   ```

2. Abre Jupyter Notebook y navega hasta la carpeta clonada.

3. Asegúrate de que el archivo `StudentsPerformance.csv` esté en la misma carpeta que el notebook.

4. Ejecuta las celdas del notebook paso a paso.

### Usando Google Colab

1. Abre Google Colab: https://colab.research.google.com/

2. Sube el notebook `StudentPerformance_EDA.ipynb` al entorno de Colab.

3. Sube el archivo `StudentsPerformance.csv` al entorno temporal de Colab usando el panel lateral ➔ pestaña `Archivos` ➔ botón `Subir`.

4. Asegúrate de que el código para leer el archivo apunte al nombre exacto, por ejemplo:
   ```python
   df = pd.read_csv('StudentsPerformance.csv')
   ```

   Esto leerá el archivo cargado en el entorno de Colab.

## Sobre el dataset

Este dataset contiene información sobre estudiantes, incluyendo variables demográficas y sus puntuaciones en matemáticas, lectura y escritura. Es ideal para explorar relaciones entre factores sociales y desempeño académico, y es ampliamente usado para practicar EDA y modelado supervisado.

## Créditos

- Dataset original: [Students Performance in Exams - Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data)
- Análisis y código: desarrollado en este repositorio para fines educativos y de práctica.

Esperamos que te sirva para tus proyectos y aprendizaje.

------------------------------------------------------------------------------------------

# Student Performance EDA

This repository contains an Exploratory Data Analysis (EDA) performed on the **Students Performance in Exams** dataset, sourced from Kaggle:  
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data

The file **StudentsPerformance.csv** is included in this repository to make it easier to reproduce the analyses. If you want to explore other approaches and notebooks created by the community, you can visit the dataset page directly on Kaggle.

## Repository contents

- Main notebook (Jupyter Notebook): `StudentPerformance_EDA.ipynb`
- Dataset: `StudentsPerformance.csv`
- Generated files: Sweetviz and Pandas Profiling reports (optional if included)

## How to use this project

### Using Jupyter Notebook (local)

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/johnpl765/EDA-Students-Performance-in-Exam.git
   ```

2. Open Jupyter Notebook and navigate to the cloned folder.

3. Make sure the file `StudentsPerformance.csv` is in the same folder as the notebook.

4. Run the notebook cells step by step.

### Using Google Colab

1. Open Google Colab: https://colab.research.google.com/

2. Upload the notebook `StudentPerformance_EDA.ipynb` to the Colab environment.

3. Upload the file `StudentsPerformance.csv` to the temporary Colab environment using the side panel ➔ `Files` tab ➔ `Upload` button.

4. Ensure the code reads the correct file name, for example:
   ```python
   df = pd.read_csv('StudentsPerformance.csv')
   ```

   This will read the file uploaded to the Colab environment.

## About the dataset

This dataset contains information about students, including demographic variables and their scores in math, reading, and writing. It is ideal for exploring relationships between social factors and academic performance, and it is widely used for practicing EDA and supervised modeling.

## Credits

- Original dataset: [Students Performance in Exams - Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data)
- Analysis and code: developed in this repository for educational and practice purposes.

We hope this helps you with your projects and learning.
