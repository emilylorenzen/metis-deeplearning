# Neural Net Review

### 1. Define the following technical terms used to describe neural networks:

- Linear combination: linear regression or linear combination of inputs such that f(x) = ax + b 
- Weights: learnable parameter of a neural network, affects the strength of the features on the output within the layers, strength of connection. The coefficients or slope. Connection between layers. 
- Bias: learnable parameter of neural network, correction for how far off predictions are from intended value. The constant or y-intercept. 
- Activation function: transformer of weights to be sent to another node where the ouput is non-linear
- Neuron/unit: a unit where weights and bias are calculated from the input and the activation function is implemented and the outputs to another layer of units
- Hidden layers: a collection of neurons between input and ouput
- Fully connected: all the nodes of one layer are connected to all the nodes of the next layer


### 2. What’s the purpose of activation functions? List as many examples as you can and define the functions (aim for 3 most important activations and more if you can!).

To make the output non-linear. Examples: tanh, sigmoid, ReLu, LeakyReLu, softmax

### 3. Describe how the parameters of a neural network model are trained.

Minimizes the loss function

### 4. What regularization methods are available to neural networks? Describe how they work.

Parameter penalities - L2 and L1

Dropout - removes weights/features

Early stopping - stops training before overfitting 

Decreasing batch size - fewer images introduced as inputs 

Learning rate - determines the step size  

### 5. Describe how convolutions operate on image inputs.

Apply a filter to a matrix of two-dimensinoal image data to find important local features/information. Reduces feature space, capture relationships between features. 

### 6. What is transfer learning? Start with a high level explanation and move to a concrete example of how it might be implemented.

Using a pre-trained model (or previously generated weights) as a starting point for a deep learning task. Example - for NLP, pre-determined weightings on word embeddings. 

7. Walk through all of the steps of a standard convolutional neural network model, e.g. the VGG16 architecture or a similar model

Input layer, convolutions, maxpooling, flatten, dense to match final output dimension. Compile. Fit. Predict.

8. What does max pooling accomplish in CNNs?

selects maximum from region of the image covered by the filter. Reduces the feature space to reduce parameters and computation. 

9. Doesn't allow connections between 