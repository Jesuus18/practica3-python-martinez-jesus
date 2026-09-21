# Práctica 3: Python — Jesús Martínez

Autor: Jesús Martínez.

## Descripción

Trabajamos los veinte ejercicios de listas, funciones, módulos, NumPy, diccionarios, pandas, condiciones y bucles. Usamos datos de ventas, empleados y sensores para practicar los cálculos y la selección de información.

## Entorno

- Python 3.12.10.
- JupyterLab 4.6.3.
- NumPy 2.5.3.
- pandas 3.0.6.

Las versiones de las dependencias están fijadas en [requirements.txt](requirements.txt).

## Estructura

| Ruta | Contenido |
| --- | --- |
| [notebooks/practica3_python.ipynb](notebooks/practica3_python.ipynb) | Notebook de los veinte ejercicios. |
| `data/` | Los tres CSV de partida: ventas, empleados y sensores. |
| [src/utilidades.py](src/utilidades.py) | Funciones para calcular importes y clasificar tickets. |
| [outputs/facturacion_por_region.csv](outputs/facturacion_por_region.csv) | Facturación neta por región del ejercicio 15. |
| [outputs/ingenieria_remoto_senior.csv](outputs/ingenieria_remoto_senior.csv) | Selección de empleados del ejercicio 18. |

## Cómo ejecutar la práctica

Abrimos PowerShell en la carpeta del repositorio y creamos el entorno con Python 3.12:

```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m jupyterlab notebooks/practica3_python.ipynb
```

En JupyterLab seleccionamos el kernel del entorno y usamos **Kernel > Restart Kernel and Run All Cells**. Al terminar guardamos el notebook para conservar las salidas.

El notebook trabaja desde `notebooks/`, con rutas relativas a `../data/`, `../src/` y `../outputs/`. Los ejercicios 15 y 18 generan los dos CSV de resultados.

## Capturas de apoyo

- [Comprobación del entorno](images/01-entorno.png).
- [Resultados finales y comparación de totales](images/02-resultados-finales.png).
