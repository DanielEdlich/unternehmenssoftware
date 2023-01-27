# Unternehmenssoftware - Trustpilot Review Analyser

## Setup
Create python environment:
```shell
conda create --name=htw_project python=3.10 -y
conda activate htw_project
```
Install libraries:
```shell
pip install -r requirements.txt --user
```
Run Jupiter Notebook Server
```shell
jupyter notebook
```

## Contents
- [Webscraper](trustpilot.ipynb)
- [Data Preparation and Exploitative Data Analysis](data_preparation_eda.ipynb)
- [Modelling](sentiment_prediction.ipynb)

## Data Source
[Trustpilot](https://www.trustpilot.com/)

Example: [Google on Trustpilot](https://www.trustpilot.com/review/www.google.com)