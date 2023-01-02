# Real-Estate-Market-Forecast
Projekt uczenia maszynowego do predykcji cen nieruchomości. 

Rezultaty zostały przedstawione w interaktywnej aplikacji dostępnej pod adresem https://house-prices-forecast-eosstbkhha-zf.a.run.app

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [App Pages](#app-pages)
* [Setup](#setup)
* [Acknowledgements](#Acknowledgements)

## General Information

Celem projektu jest predykcja ceny sprzedaży nieruchomości oraz określenie jakie cechy najbardziej oddziałują na jej końcową wartość. 
W tym celu wytrenowane zostały algorytmy typu black-box tj.:
* AdaBoost,
* XGBoost,
* Lasy Losowe,

które zostały porównane z modelem typu white-box tj. 
* Drzewem Decyzyjnym. 

Przedstawione zostało kompleksowe rozwiązanie od przygotowania danych poprzez selekcję cech do analizy eksploracyjnej. Szczególny nacisk położono na zrozumienie predykcji dokonywanych przez porównywane modele - zarówno na poziomie lokalnym jak i globalnym. Wykorzystane zostały różne techniki wyjaśnienia modeli takie jak: 
* aproksymacja modelem zastępczym,
* wartości Shapley’a,
* zależności typu Break-Down, skumulowanych profili lokalnych.

Wyniki przedstawiono w interaktywnej aplikacji napisanej przy użyciu frameworka Dash.

## Technologies Used
* Python 3.10.2

* Dash

* Docker

* Css

* Pakiety: Dalex, sklearn, plotly, pytest

* Jupyter Notebook

* IDE Pycharm

* Hosting - Google Cloud Run

* Gunicorn

## App Pages
* Streszczenie 

![streszczenie](https://user-images.githubusercontent.com/101253790/210269132-af35b9cf-f35a-4a50-91dd-7c0e52aa1b8b.jpg)

* Zbiór danych

![zbior_danych](https://user-images.githubusercontent.com/101253790/210268642-cb354ba2-15ef-40d5-bc7a-e81e508eba17.gif)


* Zmienna objaśniana

![zmienna_objasniana](https://user-images.githubusercontent.com/101253790/210268244-b51366e1-a8ef-45b0-b884-be14214dc979.gif)

* Modele ML

![modele_ml](https://user-images.githubusercontent.com/101253790/210268667-df04a2d1-b9a0-498e-a567-eeff73975389.gif)

* Predykcja

![predykcja](https://user-images.githubusercontent.com/101253790/210268678-49447a2a-8dd6-4663-8a8f-a791054a1dc9.gif)

## Setup

pip install -r requirements.txt

## Acknowledgements
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

https://dalex.drwhy.ai

https://xgboost.readthedocs.io/en/stable/

https://dash.plotly.com
