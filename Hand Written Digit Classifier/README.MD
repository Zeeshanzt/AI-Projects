# Hand Written Digit Classification

## Data Source
  It consists of a training set of 60,000 handwritten digits with corresponding labels, and a test set of 10,000 images. The images have been normalised and centred. The dataset is frequently used in machine learning research, and has become a standard benchmark for image classification models.
  
## Techniques/ Tools Used
### Normalization
  There is use of normalization for the feature scaling for better training of the model on training dataset.
  
### Convolutional Neural Network
  There is use of 6 Layered Neural Netwrork containing MaxPool, Dropout, Dense and Flatten Layers for creating the classifier for the classification.
 
### Optimizer Function
  Adam optimizer was used for the auto tuning of hyper parameters during the training on the dataset.

### Data Visualization
  Use of Matplotlib and Numpy for the plotting of the validation set and training set losses.

## Results
  The Neural Network was trained only for 5 epochs so the training accuracy was 99.08%.
  
  ![image](https://user-images.githubusercontent.com/64379996/182150677-933ff502-a8d9-4ac6-8084-716d70464cfa.png)
