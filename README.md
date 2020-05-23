# Neural_Network

### Project Summary
This project was to build a neural network model to predict the success of a venture seeking funding by Alphabet Soup.  Before hot encoding, there were eight features in the data provided for the model.  The first model had a single hidden layer, 16 neurons (double the feature set), used the ReLu activation function, and ran for 100 epochs.  The model achieved a 73% accuracy score versus a target of 75%.  Subsequent models tested two and three hidden layers, up to 500 epochs, and used the ReLU, tanh, sigmoid, eLu, CReLu, and swish activation functions.  No model was able to achieve the target model performance.  The best model had three layers with 16, 8, and 4 neurons, used the swish activation function and ran for 100 epochs.  I tested a Random Forest Classifier model and achieved a 72% accuracy.  An Easy Ensemble model only achieved a 53% accuracy rate.  The Random Forest Classifier model is an excellent alternative to the neural network model as it is quicker and requires fewer lines of code.

### Resources
+ Python 3.7.7
+ TensorFlow 2.1.0
