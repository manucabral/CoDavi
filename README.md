# Codavi
[![](https://img.shields.io/badge/License-GPLv3-red.svg)](https://github.com/manucabral/COVID-19-Davi/blob/main/LICENSE)
[![nbviewer](https://img.shields.io/badge/jupyter_notebook-nbviewer-black.svg?style=flat-square)](https://nbviewer.jupyter.org/github/manucabral/Codavi/blob/main/Vacunación/DOSIS1-MasculineAndFeminineComparative.ipynb)
[![Python 3.6](https://img.shields.io/badge/python-3.9.1-blue.svg)](https://www.python.org/downloads/release/python-360/)

Visualización y estadísticas sobre el COVID-19 en toda la Argentina.

## Contiene
- [Vacunación](https://github.com/manucabral/Codavi/tree/main/Vacunación)
  - [Primera dosis](https://github.com/manucabral/Codavi/tree/main/Vacunación/Primera%20dosis)
    - [Comparación entre hombres y mujeres](https://github.com/manucabral/Codavi/blob/main/Vacunación/Primera%20dosis/DOSIS1-MasculineAndFeminineComparative.ipynb)
    - [Cantidad de vacunados por grupo etario](https://github.com/manucabral/Codavi/blob/main/Vacunación/Primera%20dosis/DOSIS1-GrupoEtarioComparativa.ipynb)
    - [Cantidad de vacunas aplicadas por marca](https://github.com/manucabral/Codavi/blob/main/Vacunación/Primera%20dosis/DOSIS1-VacunasAplicadas.ipynb)

## Fuente de datos
Todos los análisis y comparativas estan basados de los datos que provee el gobierno Argentino sobre el virus, estos datos lo puedes descargar [aquí](https://datos.gob.ar/dataset/salud-vacunas-contra-covid-19-dosis-aplicadas-republica-argentina---registro-desagregado).

Los datos son actualizados diariamente o semanalmente por el mismo gobierno del país.

## Requerimientos
- Python 3.9.1 (o una versión más reciente)
- Pandas
- Matplotlib

## Uso
Clonar y ejecutar el archivo main.py, o también puedes usar Jupyter Notebook para la visualización de datos.
```
git clone --recursive https://github.com/manucabral/Codavi.git
cd Codavi
python main.py
```
Ten en cuenta que Codavi descargará los datos y luego los eliminará, esto tomará poco tiempo.

