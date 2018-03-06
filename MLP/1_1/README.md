Mulitlayer Perceptron (MLP)
=====================

Goal: 
-----

    a. Build a Multilayer Perceptron (MLP) and train it on the MNIST hand-written digit dataset.
    b. Compare three setups by plotting the losses against the training time.

Model: 
------

    Training dataset : 50000 samples
    
    Input: 784 units
    Hidden layer 1 : 500 units
    Hidden layer 2 : 250 units
    Output : 10 units

Initialize weights in three methods:
------------------------------------

    a. Initialize to be zeros
    b. Initialize to be Normal distribution
    c. Initialize to be Glorot distribution
    

    
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






