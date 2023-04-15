Gas demand prediction
===============
In the residential sector, natural gas is used almost exclusively for space heating, cooking
and water boilers. Residential gas demand therefore shows a strong seasonality driven by
its dependence on cold weather.

This repo build two type models to forecast gas demand: 
- Models to predict gas demand for Jan-Mar in 2017
- Models to interplate daily demand based on monthly demand and daily temperature

### Using poetry
This project uses [poetry 1.1.8](https://poetry.eustace.io/docs/) for dependencies and virtual environment management.

### Install poetry
Please install poetry by follow instruction: https://python-poetry.org/docs/

### Configure poetry
Set poetry virtual environment in project fold: 
```
poetry config virtualenvs.in-project true
```

### Install dependencies
```
poetry install
```

### Active the virtual enviorment
Please run the command in terminal
```
poetry shell
```
### Run notebook
You are now able to run the notebook.
```bash
jupyter notebook case_study.ipynb
```

