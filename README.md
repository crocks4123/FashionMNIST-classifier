
# Fashion MNIST Clothing Classification with Neural Networks

This mini project is dedicated to the classification of clothing articles using deep neural networks. It leverages the Fashion MNIST dataset, consisting of 70,000 grayscale images with a 28x28 resolution and categorized into 10 distinct clothing types.

Our neural network model comprises three layers, starting with a flattening layer followed by two additional layers. The first layer serves as a hidden layer, featuring 128 neurons with Rectified Linear Unit (ReLU) activation. The final layer employs the softmax activation function, providing a probability distribution for classifying the clothing items accurately.

This project was a simple and enjoyable endeavor that I undertook for the purpose of gaining a better understanding of constructing neural network architectures from the ground up. Instead of relying on transfer learning and pre-trained models, I aimed to build the network from scratch. It also provided me with insights into determining the optimal number of neurons for each layer to enhance the overall performance of the model.



## Architecture of Neural Network

| Layer Type        | Number of Neurons  | Activation Function |
|-------------------|--------------------|---------------------|
| Input Layer       | 784                | N/A                 |
| Hidden Layer      | 128                | ReLU                |
| Output Layer      | 10                 | Softmax             |



## FAQ

#### Dataset Source

You can run this code directly in your IDE or visit the link below 

```
from tensorflow import keras
data = keras.datasets.fashion_mnist
```


Source:
https://keras.io/api/datasets/fashion_mnist/


## License

[MIT](https://choosealicense.com/licenses/mit/)

