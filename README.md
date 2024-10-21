# ClasificacionVinos
# Análisis de Vinos con Random Forest

Este proyecto utiliza un conjunto de datos de vinos para construir un modelo de clasificación utilizando el algoritmo de Random Forest. Se realizan varias etapas de procesamiento de datos, visualización, optimización de hiperparámetros y registro del modelo con MLflow.

## Contenido

- Carga de datos
- Verificación de datos faltantes
- Identificación y tratamiento de valores atípicos
- Balanceo de clases
- Escalado de características
- Optimización de hiperparámetros con GridSearchCV
- Entrenamiento del modelo
- Evaluación del modelo
- Registro del modelo con MLflow
- Predicción de nuevas muestras

## Requisitos

Asegúrate de tener instaladas las siguientes bibliotecas:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `mlflow`

Puedes instalar estas bibliotecas usando `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlflow
```
## Uso
Clona este repositorio en tu máquina local:

```bash
git clone <URL del repositorio>
```
Navega al directorio del proyecto:

```bash
cd nombre_del_directorio
```
Ejecuta el script de análisis:

```bash
python nombre_del_script.py
```
## Descripción del Código
Carga de Datos: Se carga el conjunto de datos desde una URL pública y se definen los nombres de las columnas.

Verificación de Datos Faltantes: Se verifica si hay valores nulos en el conjunto de datos.

Identificación de Valores Atípicos: Se utilizan boxplots para identificar visualmente los valores atípicos.

Tratamiento de Outliers: Se aplican técnicas basadas en el rango intercuartílico (IQR) para eliminar los valores atípicos.

Balanceo de Clases: Se visualiza la distribución de las clases en el conjunto de datos.

Separación de Características y Etiquetas: Se separan las características (X) de la etiqueta (y) para el entrenamiento y prueba.

Escalado de Características: Se escalan las características utilizando StandardScaler.

Optimización de Hiperparámetros: Se utiliza GridSearchCV para encontrar los mejores hiperparámetros para el modelo de Random Forest.

Entrenamiento del Modelo: Se entrena el modelo utilizando los datos escalados.

## Contribuciones
Las contribuciones son bienvenidas. Si tienes sugerencias o mejoras, siéntete libre de crear un issue o enviar un pull request.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

Evaluación del Modelo: Se generan métricas de rendimiento, como el informe de clasificación y la matriz de confusión.

Registro del Modelo con MLflow: Se registra el modelo y sus parámetros utilizando MLflow.

Predicción de Nuevas Muestras: Se realizan predicciones para nuevas muestras y se imprimen los resultados.

### Notas
- Asegúrate de reemplazar `<URL del repositorio>` con la URL real del repositorio donde se encuentra el código.
- Cambia `nombre_del_directorio` y `nombre_del_script.py` con los nombres correctos según tu estructura de archivos.
