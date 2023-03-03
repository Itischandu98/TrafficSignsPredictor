# TrafficSignsPredictor
This is a machine learning model that has the ability to predict traffic signs. 

To accomplish this, the model uses a dataset consisting of a list of German traffic signs, each with a varying number of images. Prior to training, the data is preprocessed by converting the images into a fixed square shape and adjusting the lighting conditions by converting the images into grayscale and performing histogram equalization.

The model is a Convolutional Neural Network (CNN) that employs a 2D convolution layer with a Rectified Linear Unit (ReLU) activation function for the initial layers. The final layer uses the Softmax activation function to classify the outputs into different categories. The model is compiled using the Adam optimizer with an initial learning rate of 0.001 and the categorical cross-entropy loss function is used.

To optimize performance, suitable hyperparameters such as batch size and the number of epochs are chosen. Finally, the trained model is tested with a random image taken from the web.