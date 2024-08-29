# deep-learning-challenge
Overview:
To create a Neural Network that can determine which start-ups are a safe investment

Results
AlphabetSoupCharity
    inital setup, training and running of Neural Network model on inputted csv file
    -target: "IS_SUCCESSFUL"
    -features: All remaining columns 
    -dropped: "EIN", "NAME"
    Model Features==========================================================
    -neurons: 80, 30, 1
    -layers: 3
    -activation functions: relu, relu, sigmoid
    -75% goal? = NO
============================================================================
AlphabetSoupCharity_optimization1
    second setup, training and running of Neural Network model on inputted csv file
    -target: "IS_SUCCESSFUL"
    -features: All remaining columns 
    -dropped: "EIN", "NAME"
    Model Features==========================================================
    -neurons: 80, 30, 1
    -layers: 3
    -activation functions: relu, tanh, sigmoid
    -75% goal? = NO
============================================================================
AlphabetSoupCharity_optimization2
    third setup, training and running of Neural Network model on inputted csv file
    -target: "IS_SUCCESSFUL"
    -features: All remaining columns 
    -dropped: "EIN", "NAME"
    Model Features==========================================================
    -neurons: 80, 30, 1
    -layers: 3
    -activation functions: sigmoid, relu, sigmoid
    -75% goal? = NO
============================================================================
AlphabetSoupCharity_optimization2
    third setup, training and running of Neural Network model on inputted csv file
    -target: "IS_SUCCESSFUL"
    -features: All remaining columns 
    -dropped: "EIN", "NAME"
    -reduced: "APPLICATION_TYPE" reduced number of unique values using a cutoff value of 1000
    Model Features==========================================================
    -neurons: 80, 30, 1
    -layers: 3
    -activation functions: relu, relu, sigmoid
    -75% goal? = NO
============================================================================
Summary
    model was only able to acheive a 73% accuracy, additional neurons, the inclusion of another layer with a different activation function as well as more than 50 epochs could be implemented to hit to desired 75% accuracy target.