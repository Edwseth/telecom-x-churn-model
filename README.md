# telecom-x-churn-model

## Descripción del proyecto
Análisis del churn de clientes de Telecom X utilizando técnicas de aprendizaje automático. Se parte de un dataset preprocesado y se desarrolla un flujo completo desde la exploración hasta la comparación de modelos.

## Herramientas utilizadas
- Python 3.10+
- pandas, numpy
- scikit-learn, imbalanced-learn
- xgboost
- matplotlib, seaborn
- Jupyter Notebook

## Pasos ejecutados en el análisis
1. Carga de datos
2. Exploración y limpieza
3. Codificación y preparación de variables
4. Análisis de correlación y visualizaciones
5. División de datos y escalado
6. Balanceo de clases con SMOTE
7. Entrenamiento de modelos (Logistic Regression, Random Forest, XGBoost)
8. Evaluación de modelos y ajuste de umbrales
9. Importancia de variables
10. Comparación y resultados
11. Conclusión estratégica

## Métricas alcanzadas por los modelos
Los resultados se calculan en el notebook. De forma general, XGBoost obtuvo el mejor desempeño, seguido de Random Forest y Regresión Logística.

## Conclusión estratégica breve
Los clientes con menor permanencia, contratos mensuales y altos cargos totales muestran mayor propensión a cancelar. Ofrecer incentivos para contratos a largo plazo y reforzar el soporte técnico puede reducir el churn.

## Instrucciones para ejecutar el notebook
1. Crear un entorno virtual e instalar las dependencias:
   ```bash
   pip install pandas numpy scikit-learn imbalanced-learn xgboost matplotlib seaborn jupyter
   ```
2. Ejecutar Jupyter Notebook en la raíz del repositorio:
   ```bash
   jupyter notebook
   ```
3. Abrir `notebooks/01_modelado_churn.ipynb` y seguir las secciones en orden.

