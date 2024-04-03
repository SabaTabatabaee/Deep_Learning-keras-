# Neural Network
<img src="http://cocl.us/general_neural_network" alt="Neural Network General" width="600px">

 These steps taken in training a neural networks are:
 1. Initialize the weights and biases
 2. Iteratively repeat following steps:
    
    1.Calculate network output using forward propagation
    
    2.Calculate error between ground truth and estimated or predicted output
    
    3.Update weights and biases through backpropagation
    
    4.Repeat the above three steps until the number of iterations/epoches is reached or error between ground truth and predicted output is below a predefined threshold
 
Activation functions can be :
1. Binary step function
2. Linear function
3. Sigmoid function
4. Hyperbolic function $\frac{e^z - e^{-z}}{e^z + e^{-z}}$
5. ReLU (Rectified linear unit) $max(z,0)$ recommended activation function in hidden layers
6. Leaky ReLU
7. Softmax function $\frac{e^{z_i}}{\sum_{k} e^{z_k}}$ recommended activation function in output layer

# Description of codes:
$NeuralNet_FWD.ipynb$   :   getting familiar yourself with $Feed Forward$ step

$simple_keras.ipynb$   :    a simple regression and classification neural models with keras


