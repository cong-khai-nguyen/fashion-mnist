# Fashion-MNIST
Link to test out:
https://colab.research.google.com/drive/13AW44jN4X4twIz6ot80K5D7MzsKZ5lFR?usp=sharing
# Description
This is the first project I did that uses neural network model to determine or classify if a low resolution 28 by 28 pixels image is a t-shirt, trouser, pullover, dress, coat, sandal, shirt, sneaker, bag or an ankel boot. The model consists of 3 layers: the input layer, the hidden layer and the output layer. The input layer has 784 neurons coming from a 28x28 array representing an image when flatten. The hidden layer has 128 neurons which help to discover more relationships between different inputs and outputs than just  memorizing the bits in the image. Finally, the out layer has 10 neurons since there are ten categories. With 50 epochs, the accuracy of this model can reach up to 90%.

The data set can also be found here: [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)
# Install and Run the Project
This project requires installed Python libraries: scikit-learn, numpy, matplotlib, tensorflow, keras
Note: the fashion mnist data is included when we download keras. You can access it by including this import and function below:
```
from tensorflow import keras
df = keras.datasets.fashion_mnist
