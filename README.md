# 仓库健康度量和寿命预测

## 文件结构
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

## 数据集
[Repositories_with_label](https://www.gitlink.org.cn/api/attachments/d88dec86-1959-44b7-889f-5f602b6ab528)
[Repositories_with_statistics](https://www.gitlink.org.cn/api/attachments/0b3b1792-f60d-45fc-b4e3-767600d8eb63)

## 运行环境
依赖库：requirements.txt
```
# 安装依赖库
pip install -r ./requirements.txt
```

## 如何运行

data_process.ipynb\
处理原始数据，并生成预处理后的数据集

exploratory_data_analysis.ipynb\
探索性数据分析

machine_learning_models.ipynb\
应用多种特征重要性分析方法和传统机器学习模型进行特征分析、健康度量和预测等

deep_learning.ipynb\
训练了多种深度学习模型进行仓库寿命的预测




