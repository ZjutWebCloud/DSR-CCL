# Description of the model file
1.The main model structure is implemented in file dsr_model.py<br>
-2.dataset.py implements a hypergraph-based recommendation for modeling user-service and mashup-API interactions.<br>
-3.Attention and related layers are implemented in Attention.py
-4.PredictLayer.py defines a neural network prediction layer for recommendation tasks.
-5.The training process is implemented in dsr-ccl_train.py,including data preprocessing, Data Augmentation, training and test set reading, metrics calling, and training process.

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

