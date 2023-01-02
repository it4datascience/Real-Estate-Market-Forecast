# Real-Estate-Market-Forecast
Projekt uczenia maszynowego do predykcji cen nieruchomości. 
Rezultaty zostały przedstawione w interaktywnej aplikacji dostępnej pod adresem

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

* Css

* Pakiety: Dalex, sklearn, plotly, pytest

* Jupyter Notebook

* IDE Pycharm

* Hosting - Google Cloud Run

## App Pages
* Streszczenie 
[streszczenie.pdf](https://github.com/it4datascience/Real-Estate-Market-Forecast/files/10329583/streszczenie.pdf)
* Zbiór danych


https://user-images.githubusercontent.com/101253790/210186631-a9bf35b1-a267-4538-8501-1096ec079c7c.mov


* Zmienna objaśniana

![zmienna_objasniana_AdobeExpress](https://user-images.githubusercontent.com/101253790/210267566-503eb7f7-1a79-4ded-9eee-2dfc8db43a45.gif)


https://user-images.githubusercontent.com/101253790/210186622-47dc7345-7c2e-4872-a638-7b7d88c2c2a1.mov



* Modele ML


https://user-images.githubusercontent.com/101253790/210186633-95ae222b-9bd4-49b0-93f2-464ab847dc24.mov


* Predykcja


https://user-images.githubusercontent.com/101253790/210186635-c84f64dc-bec3-4d8d-8e36-9b22ef92fad1.mov



## Setup

## Acknowledgements
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

https://dalex.drwhy.ai

https://xgboost.readthedocs.io/en/stable/

https://dash.plotly.com
