# Analisis de Datos

Repositorio del trabajo de analisis, exploracion y preprocesamiento de datos para la Evaluacion 2.

## Integrantes del equipo

- Juan David Palacio Calderón
- Sebastian Cuencar Cardona
- Julián Andrés Ramirez Bedoya
- Juan José Rúa David

## Objetivo

Desarrollar un flujo de trabajo de analisis de datos que incluya:

- exploracion inicial de datasets,
- limpieza y transformacion de variables,
- generacion de datasets procesados para etapas posteriores de modelado.

## Estructura del proyecto

```text
analisis_datos/
├─ dataset/
│  ├─ Evaluation.csv
│  ├─ netflix_titles.csv
│  ├─ Video Games Sales (1980-2024) - Raw.csv
│  └─ Video_Games_Sales_Cleaned.csv
├─ EDA/
├─ exploracion/
│  ├─ exploracion_evaluation_texto.ipynb
│  ├─ exploracion_netflix_titles.ipynb
│  └─ exploracion_videojuegos.ipynb
├─ preprocesamiento/
│  └─ fase3_preprocesamiento_videojuegos.ipynb
├─ requirements.txt
└─ README.md
```

## Requisitos

- Python 3.10 o superior
- pip actualizado

## Configuracion del entorno virtual

En PowerShell, desde la raiz del proyecto:

```powershell
python -m venv datos
.\datos\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Uso

1. Activa el entorno virtual `datos`.
2. Abre el proyecto en VS Code.
3. Ejecuta los notebooks de `exploracion/` para revisar el analisis exploratorio inicial.
4. Ejecuta `EDA/eda_videojuegos.ipynb` para la etapa de EDA.
5. Ejecuta `preprocesamiento/preprocesamiento_videojuegos.ipynb` para la etapa de preprocesamiento.