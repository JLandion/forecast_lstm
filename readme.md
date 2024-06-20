
# Estructura del Proyecto

El proyecto consta principalmente de tres archivos y una carpeta que contiene los archivos de datos:

## Archivos:

1. **data_loader.py**: Este script se encarga de realizar consultas a las bases de datos y generar archivos CSV en la carpeta 'data'.

2. **eda_and_model.ipynb**: Este notebook contiene el desarrollo preliminar del proyecto, desde la carga de datos hasta la validación para un mercado específico.

3. **eda_and_models_optuna.ipynb**: En este notebook se desarrolla el proceso para todos los mercados y explotaciones. Se utiliza la librería Optuna para la optimización de hiperparámetros. Aquí se muestra el proceso completo de entrenamiento y validación de las redes neuronales entrenadas.

### Carpeta 'data':

En esta carpeta se almacenan todos los datos necesarios o generados durante el proyecto. Su estructura es la siguiente:

- **datasets/**: Contiene los conjuntos de datos preparados para el entrenamiento en el notebook.
- **models/**: Contiene los datos de los hiperparámetros obtenidos mediante Optuna, así como los resultados de los pesos de los modelos.

# Instrucciones de Uso

1. Ejecutar el script 'data_loader.py' para obtener los datos necesarios si se tiene acceso a la base de datos.
2. Abrir y ejecutar el notebook 'eda_and_model.ipynb' para realizar un análisis preliminar y validación para un mercado específico.
3. Utilizar el notebook 'eda_and_models_optuna.ipynb' para desarrollar y optimizar modelos para todos los mercados y explotaciones.

Recordar mantener actualizados los datos en la carpeta 'data' según sea necesario durante el desarrollo del proyecto.