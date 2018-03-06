Mulitlayer Perceptron (MLP)
=====================

Goal: 
-----

    a. Find out suitable hyper-parameters that the average accuracy on the validation set is at least 97%.
    b. Plot a figure:
        x-axis is the training time (epochs);
        y-axis is the accouracy measured on both training and validation sets.

Model: 
------
    
    Training dataset : 50000 samples
    Validation dataset : 10000 samples
    
    Input: 784 units
    Hidden layer 1 : 500 units
    Hidden layer 2 : 250 units
    Output : 10 units
    

Initialize weights :
--------------------

    Initialize to be Glorot distribution

    
Results:
--------

    
![](https://github.com/zhangdiBeijing/LearningRepresentation/blob/master/MLP/images/average-loss-with-3-setups.png)


    a. Initialize to be zeros
    
        Average loss started from a relatively small value and  decreased slowly to converge.

    b. Initialize to be Normal distribution
    
        Average loss started from a high value and decreased sharply in the early epochs.
        Then it converged nearly to the same values with situation a.

    c. Initialize to be Glorot distribution
    
        Average loss began with the smallest point and decreased slowly to converge. 
        Using this setup, model can converge to zero with best performance.






