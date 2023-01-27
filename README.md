# Unternehmenssoftware - Trustpilot Review Analyser

- Group 13

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

To view and run the notebook run the jupyter server from the command line or the code editor of your choice.

## Contents
- [Webscraper](trustpilot.ipynb)
- [Data Preparation and Exploitative Data Analysis](data_preparation_eda.ipynb)
- [Modelling](sentiment_prediction.ipynb)

## Data Source
[Trustpilot](https://www.trustpilot.com/)

Example: [Google on Trustpilot](https://www.trustpilot.com/review/www.google.com)

## Notes
- to avoid running into beeing blocked by trustpilot reduce items in website_list or max_pages
