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

## App Pages
* Streszczenie 
* Zmienna objaśniana
* Modele ML
* Predykcja

## Setup

## Acknowledgements
https://www.kaggle.com/c/house-prices-advanced-regression-techniques
https://dalex.drwhy.ai
https://xgboost.readthedocs.io/en/stable/
https://dash.plotly.com
