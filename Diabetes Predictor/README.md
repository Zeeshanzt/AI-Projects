# Diabetes Predictor

## Data Source
  The Dataset was obtained from Sklearn datasets.
  
## Techniques/ Tools Used

### Tensorflow and ScikitLearn
  Both of them were used for data extraction ad model training.

### Normalization
  There is use of normalization for the feature scaling for better training of the model on training dataset.
  
### Convolutional Neural Network
  There is use of 13 Layered Neural Netwrork containing MaxPool, Dropout, Dense and Flatten Layers for creating the classifier for the classification.
 
### Optimizer Function
  Adam optimizer was used for the auto tuning of hyper parameters during the training on the dataset.

### Data Visualization
  Use of Matplotlib and Numpy for the plotting of the validation set and training set losses.
### L1 and L2 Regularization and Early Stopping
  Inorder to avoid the over fitting of the trained model on the test and validation set, ** L1 as well as L2 ** regularization was performed.
  ![image](https://user-images.githubusercontent.com/64379996/182179930-25876e6b-55dd-4859-94b0-5a7e136f07d4.png)

  Concept of Early Stopping was used so that whenever started increasing then callback and stop the training before furhter increase in losses.
### Callbacks
  There was use of callback after each epoch and different function accessing different stages of epoch were used.

## Results
  The trained model was working on just the loss of 0.5 after applying all techniques of tuning.
