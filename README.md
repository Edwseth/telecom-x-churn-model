# telecom-x-churn-model

Repositorio de ejemplo para analizar el churn de clientes de Telecom X. Incluye un conjunto de datos tratado y un notebook de Jupyter con pasos básicos de análisis y modelado.

## Estructura del proyecto
- `data/telecom_clientes_tratado.csv`: datos ya preprocesados con información de clientes y una columna objetivo `Churn`.
- `notebooks/01_modelado_churn.ipynb`: notebook que realiza un análisis exploratorio, codificación de variables y división de datos para un modelo de clasificación.

## Requisitos
Se recomienda utilizar un entorno virtual con Python 3.10 o superior e instalar las siguientes dependencias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Uso
1. Active el entorno virtual e instale las dependencias.
2. Ejecute `jupyter notebook` desde la raíz del repositorio.
3. Abra `notebooks/01_modelado_churn.ipynb` y ejecute las celdas en orden para reproducir el análisis.

## Notas
- El dataset utiliza los nombres de columnas `Charges.Monthly` y `Charges.Total` para los cargos mensuales y totales.
- No se incluyen pruebas automatizadas; sin embargo, se recomienda revisar y adaptar el notebook según los requerimientos del proyecto.
