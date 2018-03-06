Mulitlayer Perceptron
=====================

Goal: 
-----

    a. Build a Multilayer Perceptron (MLP) and train it on the MNIST hand-written digit dataset.
    b. Compare three setups by plotting the losses against the training time.

Model: 
------

    input: 784 units
    hidden layer 1 : 500 units
    hidden layer 2 : 250 units
    output : 10 units

Initialize weights in three methods:
------------------------------------

    a. initialize to be zeros
    b. initialize to be Normal distribution
    c. initialize to be Glorot distribution
    
    
![](https://github.com/zhangdiBeijing/LearningRepresentation/tree/master/MLP/images/average loss with 3 setups.png)
    
Results:
--------

    a. initialize to be zeros
    
        Average loss started from a relatively small value and  decreased slowly to converge.

    b. initialize to be Normal distribution
    
        Average loss started from a high value and decreased sharply in the early epochs.
        Then it converged nearly to the same values with situation a.

    c. initialize to be Glorot distribution
    
        Average loss began with the smallest point and decreased slowly to converge. 
        Using this setup, model can converge to zero with best performance.






