# Humanitarian-aid-Clustering-countries-of-the-world

Data science project containing data cleaning, exploratory data analysis and machine learning - identifying countries in need of humanitarian aid - clustering problem

# Requirements

The project was developed using python 3.6.9

### Packages

Following packages were used:

- Pandas 1.0.5
- Numpy 1.18.5
- Sklearn 0.22.2.post1
- Plotly 4.4.1
- Matplotlib 3.2.2
- Seaborn 0.10.1
- Sklearn_extra 0.1.0b2

### Software

Project was created using Google Colaboratory and this is recommended environment for reviewing and executing the code. Google Colaboratory already have most of required packages installed (code for installing sklearn_extra - only one missing - is already provided in the notebook). Google Colab is accessible via google drive, so there is no need to install any software. Otherwise you can use Jupyter Notebook. This option may require to adjust display options for plotly graphics and to install more missing libraries with pip install command.

### Data

Dataset used in the project is attached to the repository files. Please download 'Country-data.csv' directly from repository and upload it to your Google Colaboratory notebook working files using 'Upload to session storage' button in 'Files' section.

### Code

Project code is avalaible in 'Humanitarian_aid_to_underdeveloped_countries.ipynb' file. To execute the code please add file to the google drive and open it in Google Colaboratory or open the file directly from github using 'Open in colab' button. Then please upload the dataset (please see above) and use 'Run all' option in 'Runtime' menu.

# Project description

The goal of the project was to identify countries in the worst socio-economic situation, therefore in need of humanitarian aid. Dataset used in the project contains socio-economic indicators like for example GDP per capita, children mortality, spendings on health care, life expectation, inflation level.

The project consists of five parts: data cleaning, feature engineering, exploratory data analysis, machine learning and summary.

# Summary

Both clustering models used in the project (K-medoids, agglomerative clustering) indicated exactly the same 48 countries as countries in need of humanitarian aid. Most of the indicated countries are in Africa, some in Asia. All of them are charaterised with the lowest results in socio-economic indicators. Full list of countries included in underdeveloped cluster can be found in 'Countries.txt' file.
