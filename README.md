- A straightforward feedforward neural network with two completely connected layers is what we define in this example. When a weight matrix and bias vector are used to link each input and output unit the layer is said to be completely linked.

- The first layer produces 512 features after receiving the flattened picture (28×28 pixels) as input. Ten classes, or the numbers 0 through 9, are produced by the second layer using the 512 characteristics as input.

- To generate the completely linked layers and provide them as network object characteristics, we utilize the nn.Linear class. In order to give the network some non-linearity and aid in its ability to learn intricate patterns. We additionally apply the [ReLU](https://www.geeksforgeeks.org/activation-functions/) activation function to the first layer using the F.relu function.

- The input picture is only flattened in the forward approach which then applies the first layer the ReLU function and the second layer. A tensor of ten logits for each class is the network output.
