# Análisis de Predicción de Rendimiento Estudiantil con SHAP y XGBoost

Este proyecto emplea el aprendizaje automático y SHAP (SHapley Additive exPlanations) para predecir y explicar el rendimiento académico de los estudiantes, usando información como el tiempo de estudio por semana, las ausencias, y el apoyo parental. El propósito es descubrir las características principales que afectan al desempeño estudiantil e interpretar claramente las predicciones efectuadas por los modelos.

## Propósito del Notebook

- **Exploración de Datos**: Analizar las características del dataset y comprender las relaciones entre ellas realizando un análisis exploratorio.
- **Modelado Predictivo**: Implementar modelos de aprendizaje automático, incluyendo XGBoost y Random Forest, para predecir el rendimiento académico (`GradeClass`).
- **Interpretabilidad**: Usar SHAP para interpretar las predicciones de los modelos, ofreciendo visualizaciones que muestran cómo cada característica afecta a las predicciones.

## Cómo Ejecutar el Notebook

### Prerrequisitos

Tener Python 3.x instalado en el sistema. Las principales dependencias que se necesitan están listadas en la sección siguiente.

### Instalación de Dependencias

Se pueden instalar las dependencias necesarias usando `pip`. Ejecutar el siguiente comando en la terminal:

```bash
pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn
```
## Ejecución

1. **Clonar este repositorio**: 
   ```bash
   git clone https://github.com/<usuario>/<repositorio>.git
   cd <repositorio>
   ```

2. **Navegar al directorio de notebooks**:
   ```bash
   cd notebooks
   ```

3. **Ejecutar el notebook**:
   - Abrir los archivos notebook en `notebooks/` en Jupyter Notebook o Jupyter Lab.
   - Ejecutar las celdas de código en secuencia. Los notebooks estan diseñados para cargar los datos, entrenar los modelos, y generar visualizaciones interpretativas usando SHAP.

### Estructura del Proyecto

- `data/external/`: Tiene el dataset usado en este análisis.
- `notebooks/`: Tiene los notebooks que incluyen el análisis exploratorio, modelado, y visualizaciones SHAP.
  - `AE.ipynb`: Análisis exploratorio de los datos.
  - `RandomForest.ipynb`: Implementación del modelo Random Forest y análisis con SHAP.
  - `XGBoost.ipynb`: Implementación del modelo XGBoost y análisis con SHAP.

### Dataset

El dataset usado en este proyecto es **Student Performance Dataset** disponible en Kaggle. Debe colocarse en la carpeta `data/external/` bajo el nombre `Student_performance_data_.csv`.

### Visualizaciones y Análisis

El notebook genera varias visualizaciones clave:
- **Summary Plot de SHAP**: Muestra la importancia global de las características en las predicciones.
- **Dependence Plot de SHAP**: Analiza cómo una característica específica influye en las predicciones del modelo.
- **Force Plot de SHAP**: Proporciona una explicación detallada de cómo cada característica contribuye a una predicción específica.

### Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

### Contacto

Para preguntas o soporte, contacta con [mariodeleonm1@gmail.com](mailto:mariodeleonm1@gmail.com).




