# Hand Written Digit Classification

## Data Source
  We will use the Iris dataset. It consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals.
  
## Techniques/ Tools Used
### Normalization
  There is use of normalization for the feature scaling for better training of the model on training dataset.
  
### Convolutional Neural Network
  There is use of 13 Layered Neural Netwrork containing MaxPool, Dropout, Dense and Flatten Layers for creating the classifier for the classification.
 
### Optimizer Function
  Adam optimizer was used for the auto tuning of hyper parameters during the training on the dataset.

### Data Visualization
  Use of Matplotlib and Numpy for the plotting of the validation set and training set losses.
### Dropout Regularization and Early Stopping
  Inorder to avoid the over fitting of the trained model on the test and validation set, regularization was performed.
  ![image](https://user-images.githubusercontent.com/64379996/182178176-a8f4b307-0ac5-4eee-a583-98f87386795e.png)

  Concept of Early Stopping was used so that whenever started increasing then callback and stop the training before furhter increase in losses.
![image](https://user-images.githubusercontent.com/64379996/182178540-fa0c9c02-46a3-412c-9e39-95866af56921.png)

## Results
  The trained model was 90%+ accuracy on validation data and 100% on test set.
