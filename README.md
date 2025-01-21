# Fashion_MNIST_Classifier_Deep_Learning_Project

This project demonstrates building and training a fully connected Artificial Neural Network (ANN) to classify images from the Fashion-MNIST dataset. Unlike the classic MNIST dataset, Fashion-MNIST contains images of clothing items such as shirts, trousers, and shoes, making it more complex and diverse.

## Key Steps in the Project

### 1. Loading the Dataset
- The project starts by importing essential libraries like TensorFlow and Keras.
- The Fashion-MNIST dataset, available in Keras, is loaded and split into training and testing sets.

### 2. Preprocessing
- Images are preprocessed to prepare them for the neural network.
- This includes normalizing pixel values to a range of 0–1, making it easier for the network to learn from the data.

### 3. Defining the Neural Network
- A fully connected ANN is constructed using Keras.
- Key components include:
  - **Input Layer:** Accepts the input images.
  - **Hidden Layers:** One or more layers with neurons and non-linear activation functions.
  - **Output Layer:** Contains 10 neurons, each representing a clothing category.
- The architecture is designed with activation functions to introduce non-linearity and enable the network to learn complex patterns.

### 4. Training
- The neural network is trained using the training dataset.
- Training involves:
  - Feeding input images and their corresponding labels to the network.
  - Calculating errors in predictions.
  - Adjusting network weights to minimize errors using an optimizer and loss function.
- Metrics such as accuracy are tracked to monitor the training progress.

### 5. Testing
- After training, the network's performance is evaluated on the testing dataset (unseen images).
- Accuracy is used to measure how well the network generalizes to new data.

This project showcases the entire pipeline of building, training, and evaluating an ANN for image classification using Fashion-MNIST.
