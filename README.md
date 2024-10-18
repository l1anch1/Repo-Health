# Repository Health Metrics and Lifespan Prediction

## File Structure
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

## Execution Environment
Dependency libraries：requirements.txt
```
# Install dependency libraries
pip install -r ./requirements.txt
```

## Getting Started
```
data_process.ipynb
```
Process raw data and generate preprocessed datasets
```
exploratory_data_analysis.ipynb
```
Exploratory data analysis
```
machine_learning_models.ipynb
```
Apply various feature importance analysis methods and traditional machine learning models for feature analysis, health metrics, and prediction, etc.
```
deep_learning.ipynb
```
Train various deep learning models for repository lifespan prediction






