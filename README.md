# Grab Capstone Project (Data Analytics)

![forthebadge made-with-python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
![forthebadge made-with-python](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

This project collects, processes, and analyzes data from **National High School Graduation Exam** (THPT QG) to extract meaningful insights and provide student recommendations. The results of this project can be used in the future and can be applied to different examinations.

## Table of Contents
- [Technologies](#technologies)
- [Structure](#structure)
- [Installation](#installation)
- [Architecture](#architecture)
- [License](#license)

## Technologies 
This project was implemented using the following technologies:
- Python 3
- Jupyter Notebook
- MongoDB Atlas: a multi-cloud database service
- BeautifulSoup: a library for web scraping
- Pandas, NumPy, Math: libraries for data analysis and exploration
- Matplotlib, Seaborn: libraries for statistical visualization
- Geopandas: a library for distribution visualization with geospatial data
- Scikit-learn: a library for machine learning in Python
- Support Vector Machine (SVM), Decision Tree Regression: 2 Machine Learning algorithms used in this project

## Structure

```text
/
├── processing
│   ├── collect
│   │   └── *.py
│   ├── extract
│   │   └── *.py
│   ├── storage
├── analytics
│   ├── EDA.ipynb
│   ├── Prediction.ipynb
│   ├── NLP.ipynb
│   ├── Further_Research.ipynb
│   ├── Wiki_Scraping.ipynb
│   ├── storage
```

- The `processing` folder contains all the source code of the collection and extraction processes
  - The `collect` folder crawls and loads raw data to MongoDB.
  - The `extract` folder is used to extract data for development purposes, extract it into JSON and load it to MongoDB.
  - The `storage` folder is used to store data.
- The `analytics` folder contains all the source code of the data exploration, model implementation, and innovation processes
  - The `EDA.ipynb` explores data by visualization.
  - The `Prediction.ipynb` predicts the future scores using Decision Tree.
  - The `NLP.ipynb` classifies careers into majors using SVM.
  - The `Further_Research.ipynb` is used for innovation purposes.
  - The `Wiki_Scraping.ipynb` crawls date for `Further_Research.ipynb`.
  - The `storage` folder is used to store data.

## Installation
This project is designed to be run in Google Colab and Python IDE. After cloning the project, please follow these steps:

For the `processing` folder
* Run `crawler.py` to start the data_processing process
* Run other Python files in the `collect` folder 
* Run other Python files in the `extract` folder 

For the `analytics` folder
* Open the notebook in Google Colab.
* Upload the folder “analytics” to the following path `/content/drive/MyDrive/Colab Notebooks/`
* Click on "Runtime" in the top left corner of the screen.
* Select "Run all" to run all cells in the notebook.
* View the output in the notebook or download the files to your local machine.

## Architecture
This is the Data Architecture of the project
![arc](https://github.com/Project-UniLight/Data-Analysis/assets/95847972/71ddb6fc-3de8-4088-bec9-18050fbe87ec)


## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
