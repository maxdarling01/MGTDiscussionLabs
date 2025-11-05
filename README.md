# MGTDiscussionLabs
The archive of MGT 661 discussion labs. The readme for the current lab will be placed at the top of this file.  

Dweek3: 
This project demonstrates a neural network classification workflow using TensorFlow/Keras on the Iris dataset. The goal is to classify iris flowers into one of three species based on four numeric features: sepal length, sepal width, petal length, and petal width. The dataset contains 150 samples with three classes: setosa, versicolor, and virginica.

The workflow starts with preprocessing, where features are standardized using StandardScaler and target labels are one-hot encoded for the softmax output layer. A Sequential neural network is built with two hidden layers of 64 and 32 neurons using relu activation, and an output layer of three neurons with softmax activation. The model is compiled with the adam optimizer and categorical_crossentropy loss and trained for 50 epochs with a batch size of 16. A validation set monitors performance during training, and training history is plotted to visualize learning progress.

Results show a validation accuracy of 1.0, meaning the model correctly classified all samples in the validation set. This demonstrates that even a simple neural network can learn patterns effectively on a small, well-separated dataset like Iris. The process illustrates how neural networks automatically adjust weights and biases to make accurate predictions and how preprocessing and proper architecture choices support effective training.
