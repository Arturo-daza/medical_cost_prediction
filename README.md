
<h1 align="center">
  Modelo de regresión lineal para predecir costos medicos
</h1>

<h4 align="center">Uso de scikit-learn para la regresión linear</h4>

<p align="center">
  <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='scikit-learn' src='https://img.shields.io/badge/scikit-learn-100000?style=for-the-badge&logo=scikit-learn&logoColor=FFFFFF&labelColor=FF6A00&color=1882EA'/></a> <a href='https://seaborn.pydata.org/' target="_blank"><img alt='seaborn' src='https://img.shields.io/badge/Seaborn-100000?style=for-the-badge&logo=seaborn&logoColor=white&labelColor=black&color=186FCD'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/478b5ba4-46cf-4d31-94e7-0b87621464d6/pb_life_How_to_increase_Health_insurance_cover_1592063367.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221106%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221106T052053Z&X-Amz-Expires=86400&X-Amz-Signature=0102361a953be50bbd1959bc3f6f691d5371bc92ddf4210b9ea5d296efca7204&X-Amz-SignedHeaders=host&x-id=GetObject)

## Caracteristicas clave

Este modelo de ML predice los costos medicos que adquiere un paciente. Esta predicción es un numero dado en dolares. El dataset es tomado de [Medical Cost Personal Datasets
](https://www.kaggle.com/datasets/mirichoi0218/insurance). Aqui unas caracteristicas del proyecto:

* La predicción esta basada en las caracteristicas de los pacientes:
  
  - age: edad del beneficiario principal
  - sex: género del contratante de seguro, femenino, masculino
  - imc: Índice de masa corporal, proporciona una comprensión del peso del cuerpo en relación con la altura, índice objetivo de peso corporal (kg/m^2) utilizando la relación de altura y peso, idealmente de 18.5 a 24.9
  - children: número de niños cubiertos por el seguro de salud / número de dependientes
  - smoker: fumar
  - region: área de residencia del beneficiario en los EE.UU, noreste, sureste, suroeste, noroeste.
  - charges: costos médicos individuales facturados por el seguro de salud.

* Uso de jupyter notebook
* Uso de herramientas **dataviz**
* Uso de los modulos y funciones de **Scikit-Learn**:
  -  `preprocessing.StandardScaler` :   Estandarización de datos 
  - `linear_model.LinearRegression` :   Modelo de regresión linear
  - `metrics` :  Uso de difentes metricas como el r2, el MSE y el MAE

## Como usar

Para clonar y corres esta aplicación, necesitaras [Git](https://git-scm.com).

```bash
# Clonar este repositorio
$ git clone https://github.com/Arturo-daza/medical-cost-prediction.git

# Entrar al repositorio
$ cd linear-algebra-in-python

# Instalar Jupyter Notebooks
$ pip install jupyterlab
$jupyter-lab
$pip install notebook

#Correr 
$jupyter notebook

## o correrlo desde visual studio code
$conda install ipykernel
$code .

```

## Creditos

Este modelo usa las siguientes fuentes abiertas:

- [Scikit-learn](https://scikit-learn.org/stable/)
- [Insurance US Census Bureau](https://www.census.gov/)
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)


## License

MIT

---

> GitHub [@Arturo-daza](https://github.com/Arturo-daza) &nbsp;&middot;&nbsp;

