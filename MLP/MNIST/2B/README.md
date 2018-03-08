Mulitlayer Perceptron (MLP)
=====================

Goal: 
-----

    a. Find out suitable hyper-parameters that the average accuracy on the validation set is at least 97%.
    b. Train the model for 100 epochs.
    c. Double model capacity (in terms of number of parameters)

First Model: 
------
    
    Training dataset : 50000 samples
    Validation dataset : 10000 samples
    
    Input: 784 units
    Hidden layer 1 : 500 units
    Hidden layer 2 : 250 units
    Output : 10 units

Second Model: 
------
    
    Training dataset : 50000 samples
    Validation dataset : 10000 samples
    
    Input: 784 units
    Hidden layer 1 : 900 units
    Hidden layer 2 : 400 units
    Output : 10 units
    

Initialize weights :
--------------------

    Initialize to be Glorot distribution

    
Hyper parameters :
-------------------

    Learning rate = 0.01
    Momentum = 0.9
    batch size = 40
    epochs = 100
    
    
![](https://github.com/zhangdiBeijing/LearningRepresentation/blob/master/MLP/images/error-of-first-model.png)
![](https://github.com/zhangdiBeijing/LearningRepresentation/blob/master/MLP/images/error-of-second-model(double-parameters).png)

Results :
---------

    The error of validation did not increase in two figures even though we double model capacity.
    It means the model did not appear to be overfitting with high variance.
    
    These may be benefited from some reasons:
        a. Large datasets with low noise
        b. Proper numbers of parameters
        c. Suitable hyper parameters
    
     








