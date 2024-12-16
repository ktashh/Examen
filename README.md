EXAMEN CIENCIA DE DATOS PARA LA ECONOMÍA

Proyecto de Análisis de Ingresos

Este proyecto tiene como objetivo analizar un conjunto de datos relacionado con los ingresos anuales, utilizando técnicas de Análisis Exploratorio de Datos (EDA) y Reducción de Dimensionalidad mediante PCA.

Descripción del Dataset
El dataset ingresos.txt contiene información sobre 1,816 individuos y 14 variables, que incluyen:

·estatura: Estatura en centímetros.

·peso: Peso en kilogramos.

·género: Masculino/Femenino.

·ingresos: Ingresos anuales en dólares.

·etnia: Clasificación étnica.

·educacion: Años de educación del individuo.

·educacion_madre: Años de educación de la madre.

·educacion_padre: Años de educación del padre.

·camina: Frecuencia de caminata al trabajo (escala de 1 a 8).

·ejercicio: Días a la semana que realiza ejercicio.

·fumador: Si fuma (1: Sí, 2: No).

·tenso: Días en estado de tensión.

·malhumorado: Días de la semana en dicho estado.

·edad: Edad del individuo.


Actividades Realizadas

1. Análisis Exploratorio de Datos (EDA):

·Descripción general del dataset.

·Transformación e imputación de datos faltantes.

·Visualización de distribuciones y correlaciones entre variables.

3. Reducción de Dimensionalidad con PCA:
·Aplicación del algoritmo PCA para reducir la complejidad del dataset.
·Visualización de los componentes principales y explicación de su varianza.

4. Gestión con Git y GitHub:
·Configuración del repositorio local con Git.
·Creación de ramas (main y pca_analysis) para estructurar el flujo de trabajo.
·Subida del proyecto a GitHub para un manejo eficiente del control de versiones.

Tecnologías Usadas
·Python
·Jupyter Notebook
·Scikit-learn
·Matplotlib
·Pandas
·Git y GitHub

Instrucciones para Reproducir el Proyecto
1. Clonar el repositorio desde GitHub:
git clone https://github.com/Usuario/Ciencias_de_Datos.git

2. Instalar las librerías necesarias:
pip install pandas scikit-learn matplotlib

3. Ejecutar el cuaderno analisis_datos.ipynb en Jupyter Notebook o Google Colab.

Conclusión
En este proyecto se realizó un análisis del conjunto de datos ingresos.txt, aplicando técnicas de Análisis Exploratorio de Datos (EDA) y reducción de dimensionalidad mediante el algoritmo PCA. El proceso permitió identificar patrones significativos y simplificar la estructura de los datos al concentrar la mayor parte de la varianza en un menor número de componentes principales.

Además, se implementó una gestión adecuada del flujo de trabajo utilizando Git y GitHub, facilitando la organización, el control de versiones y la colaboración en el desarrollo del proyecto. La estructura del repositorio y el uso de ramas garantizan un manejo eficiente de las etapas de desarrollo y análisis.
