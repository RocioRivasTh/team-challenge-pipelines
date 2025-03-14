# Team Challenge: Pipelines

## Descripción
Este es el repositorio para el Team Challenge de Pipelines en Scikit-learn.

## Integrantes del equipo
- Concha
- Katia
- Nicolas
- Ángela
- Rocio

## Estructura del repositorio

team-challenge-pipelines
- src/
- data/ → Dataset de entrenamiento y prueba
- models/ → Modelos entrenados
- result_notebooks/ → Notebooks con código final
- notebooks/ → Notebooks de prueba (opcional)
- utils/ → Funciones auxiliares (opcional)

- README.md → Documentación
- .gitignore → Archivos ignorados
- requirements.txt → Dependencias del proyecto


## Explicación del Código

El código del proyecto está implementado en Jupyter Notebooks, principalmente en los archivos Pipelines_I.ipynb y Pipelines_II.ipynb. Estos notebooks contienen el flujo de trabajo para:

- Carga y exploración de datos: Se importan las librerías necesarias y se carga el dataset.

Preprocesamiento de datos:

- Manejo de valores nulos.

- Transformación de variables categóricas.

- Normalización y escalado de datos.

Construcción del Pipeline:

- Se definen los pasos del pipeline, incluyendo preprocesamiento y modelado.

- Se usan Pipeline y ColumnTransformer de Scikit-learn.

Entrenamiento y Evaluación del Modelo:

- Se dividen los datos en conjuntos de entrenamiento y prueba.

- Se entrena el modelo utilizando cross-validation.

- Se evalúa el rendimiento del modelo con métricas como accuracy, precision, recall y f1-score.

Cómo Ejecutar el Proyecto

1. Clonar el Repositorio

git clone <URL_DEL_REPOSITORIO>
cd team-challenge-pipelines

2. Crear y Activar un Entorno Virtual

python -m venv venv
source venv/bin/activate  # En macOS/Linux
venv\Scripts\activate  # En Windows

3. Instalar Dependencias

pip install -r requirements.txt

4. Ejecutar los Notebooks

Abrir Jupyter Notebook y ejecutar Pipelines_I.ipynb y Pipelines_II.ipynb.

5. Guardar Modelos Entrenados

Los modelos entrenados se guardan en la carpeta models/ para su posterior uso o evaluación.
