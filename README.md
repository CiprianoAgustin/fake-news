# Detector de fake news usando Machine Learning

Un ejemplo completo de construcción de un proyecto de aprendizaje automático de principio a fin, desde la idea inicial hasta la implementación.

Este repositorio acompaña a la serie de publicaciones del blog que describen cómo construir una aplicación de detección de fake news. Los artículos incluidos aquí son los siguientes:

- [Configuración Inicial y Herramientas](https://medium.com/@agustin.e.cipriano/creating-a-comprehensive-machine-learning-project-getting-started-8886181fd3f): Describe la ideación del proyecto, cómo configurar tu repositorio y las herramientas iniciales del proyecto.

## Features

* **Random forest** - [Scikit-learn](https://scikit-learn.org/stable/).
* **RoBERTa** - [HuggingFace Transformers](https://huggingface.co/transformers/) y [PyTorch Lightning](https://github.com/PyTorchLightning/pytorch-lightning).
* **Versionado de datos** y configuración de pipelines de entrenamiento/validación usando [DVC](https://github.com/iterative/dvc).
* **EDA** - [Pandas](https://pandas.pydata.org/).
* **Experiment tracking** y **logging** - [MLFlow](https://mlflow.org/).
* **CI** - [Github actions](https://github.com/features/actions).
* **Tests** - [PyTest](https://docs.pytest.org/en/stable/) y [Great Expectations](https://greatexpectations.io/).
* **Error** y **model feature analysis** - [SHAP](https://github.com/slundberg/shap).
* **Server** - [FastAPI](https://fastapi.tiangolo.com/) y [Gunicorn](https://gunicorn.org/).
* **Chrome** para interacción con el modelo en el [browser](https://chrome.google.com/webstore/category/extensions?hl=en).