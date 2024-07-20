# Regresión lineal: predecir los gastos médicos de pacientes
---

## Descripción del Proyecto

Para este proyecto utilizaremos los datos presentados en [este](https://www.kaggle.com/mirichoi0218/insurance) dataset de Kaggle en el cual se presentan datos de seguros médicos.


## Contenido

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Contenido](#contenido)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Resultados](#resultados)
- [Conclusión](#conclusión)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Requisitos

- Python 3.x
- Librerías:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - plotly
  - scikit-learn
  - regressors
  - pickle

## Instalación

1. Puedes descargar el archivo y correrlo en Google Colab

## Uso
Carga los datos:

```python
import pandas as pd

df = pd.read_csv('/content/drive/MyDrive/machine_learning/data/insurance.csv')
```

## Resultados
Los resultados del modelo se presentan mediante gráficos de dispersión, matrices de correlación y gráficos de residuos para visualizar la precisión y las predicciones del modelo.

## Conclusión
El modelo inicial tiene un coeficiente de determinación (R²) de aproximadamente 0.50, lo cual es aceptable para la predicción de gastos hospitalarios. Se recomienda seguir afinando el modelo inicial y probar con diferentes características y técnicas para mejorar la precisión.

## Contribuciones
Las contribuciones son bienvenidas. Para grandes cambios, por favor abre un issue primero para discutir lo que te gustaría cambiar.
