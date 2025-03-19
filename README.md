# GitHub Repo Health Metrics and Lifespan Prediction


## Project Description
This project focuses on analyzing GitHub repository health metrics and predicting repository lifespan. By examining various factors such as commit frequency, issue resolution time, contributor diversity, and star number, we aim to develop a comprehensive health assessment framework. The prediction component utilizes machine learning and deep learning techniques to forecast repository activity patterns and potential lifespan, helping open-source maintainers and contributors make more informed decisions about project sustainability and resource allocation.


## Project Structure
```
RepoHealth  
|-- data  
|   |-- repositories_label.csv  
|   |-- repositories_merged.csv  
|   |-- repositories_statistics.csv  
|   |-- Repositories_with_label.csv  
|   |-- Repositories_with_statistics.csv
|  
|-- src  
|   |-- data_process.ipynb  
|   |-- exploratory_data_analysis.ipynb  
|   |-- machine_learning_models.ipynb
|   |-- deep_learning.ipynb
|
|-- images
|   |-- feature_importance
|   |-- prediction
```

## Datasets
[Repositories_with_label](https://www.gitlink.org.cn/api/attachments/d88dec86-1959-44b7-889f-5f602b6ab528)\
[Repositories_with_statistics](https://www.gitlink.org.cn/api/attachments/0b3b1792-f60d-45fc-b4e3-767600d8eb63)

## Environment Setup
Install dependencies:
```
pip install -r ./requirements.txt
```

## Get Started
1. Process raw data and generate preprocessed datasets
```
data_process.ipynb
```
2. Exploratory data analysis (EDA)
```
exploratory_data_analysis.ipynb
```
3. Apply various feature importance analysis methods and traditional machine learning models for feature analysis, health metrics, and prediction.
```
machine_learning_models.ipynb
```
4. Train various deep learning models for repository lifespan prediction
```
deep_learning.ipynb
```







