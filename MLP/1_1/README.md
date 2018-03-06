Mulitlayer Perceptron

Goal: 

    a. Build a Multilayer Perceptron (MLP) and train it on the MNIST hand-written digit dataset.
    b. Compare three setups by plotting the losses against the training time.

Model: 

    input: 784 units
    hidden layer 1 : 250 units
    hidden layer 2 : 250 units
    output : 10 units

Initialize weights in three methods:

    a. initialize to be zeros
    b. initialize to be Normal distribution
    c. initialize to be Glorot distribution
    
Result:

    a. initialize to be zeros
    
        Average loss started from a relatively small value and  decreased slowly to converge.

    b. initialize to be Normal distribution
    
        Average loss started from a high value and decreased sharply in the early epochs. Then it converged nearly to the same values with situation a.

    c. initialize to be Glorot distribution
    
        Average loss began with the smallest point and decreased slowly to converge. Using this setup, model can converge to the lower loss values.






