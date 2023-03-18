# Two-Dimensional-Classification-Involving-Non-Convex-Decision-Regions
Two-dimensional binary classification problem involving non-convex decision regions i.e., C1 &amp; C2. 
The proposed solution employs a Back Propagation and Counter Propagation Network to distinguish whether an input pattern belongs to class C1 or C2.

## Dataset Generation
The dataset can be defined as having the following chracteristics:

![Table](https://user-images.githubusercontent.com/97694796/226027259-2164c5c8-335e-4850-85d8-f03d5ce8e728.png)

Class C1 consists of pattern points marked inside the area marked C1 and class C2 consisits of pattern points inside the area marked C2.

![Dataset](https://user-images.githubusercontent.com/97694796/223731272-454b83ff-68ab-4fb8-81a9-f09ae8c4ad15.png)

## Back Propagation Network
Multi-layer perceptron (MLP) is a class of fully connected feedforward neural networks. It consists of at least three layers: input layer, hidden layer, and the output layer. Each node/neuron apart from the input layer uses a non-linear activation function. MLP utilizes backpropagation technique for learning weights, a type of supervised learning, and can distinguish non-linearly separable data. It is also referred to as a Back Propagation Network.

## Counter Propagation Network
A counter propagation network (CPN) is a mapping neural network, whilst its architecture is a combination of the self-organizing map of Kohnen and outstar structure of Grossberg. It consists of three layers: input, output, and the hidden layer. The hidden layer or the competitive layer implements a winner-takes-all mechanism to determine which output neuron is most like the input pattern. The neuron with the highest activation value is chosen as the winner, and its weight vector is updated. The output layer implements supervised learning, where it adjusts the weights between the hidden and output layer to produce the desired output for each input pattern.

## Data Preprocessing
The following preprocessing steps have been employed to transform the original dataset into the requisite form:
1) Feature & Target Data Frame
2) Label Encoding
3) Feature Scaling
4) Train & Test Split

## Model Evaluation
Both models have been evaluated based on a number of metrics:
1) Accuracy
2) Confusion Matrix
3) Binary Cross Entropy (MLP only)

A comparative analysis between the Back Propagation Network and the Counter Propagation Network on the problem at hand given the same dataset. We observe the optimal results produced by each model to objectively view their performance.

![Table](https://user-images.githubusercontent.com/97694796/226023213-2c1530cc-d36e-4da1-ad29-966c880e2ea2.png)

Overall, it was observed that the BPN performed significantly well when compared to the CPN, however, it took a considerable amount of time to train on the dataset. In addition, both models oscillate when varying number of epochs and are prone to overfitting.
