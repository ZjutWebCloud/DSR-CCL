# Description of the model file
1. The main model structure is implemented in file dsr_model.py<br>
2. dataset.py implements a hypergraph-based recommendation for modeling user-service and mashup-API interactions.<br>
3. Attention and related layers are implemented in Attention.py<br>
4. PredictLayer.py defines a neural network prediction layer for recommendation tasks.<br>
5. The training process is implemented in dsr-ccl_train.py, including data preprocessing, Data Augmentation, training and test set reading, metrics calling, and training process.<br>

## 📚 Datasets

| Statistics                                       |   value     | 
| -------------------------------------------------| ----------- | 
| # Users Interactions                             |   37993     | 
| # Mashups                                        |   6206      |
| # Web APIs                                       |   13329     |
| # Average length of service description document |   43.46     |         
| # Number of API services invoked                 |   3047      | 
| # Density                                        |   0.23      | 
| # Number of service interaction behavior types   |   3         | 

## 📝 Environment

We develop our codes in the following environment or install all dependencies listed in *requirements.txt*:

- CUDA==12.1

- python==3.9.21

- torch==2.3.1

- ## 🚀 How to run the codes

The command lines to train BGCL-KDE on the three datasets are as below. The un-specified hyperparameters in the commands are set as default.

##### Last.FM

```python
python dsr-ccl_train.py

