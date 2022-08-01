# Animal Classification

## Data Source
  For the purpose of training dataset on animal images, *CIFAR* dataset was used which contained 1000 images each having 32*32*3 dimensions.
  
## Techniques/ Tools Used
### Normalization
  There is use of normalization for the feature scaling for better training of the model on training dataset.
  
### Convolutional Neural Network
  There is use of 10 Layered Neural Netwrork containing MaxPool, Dropout, Dense and Flatten Layers for creating the classifier for the classification.
 
### Optimizer Function
  Adam optimizer was used for the auto tuning of hyper parameters during the training on the dataset.

### Data Visualization
  Use of Matplotlib for the plotting of the validation set and training set losses.

##Results
  The Neural Network was trained only for 5 epochs so the training accuracy was 66.76%.
