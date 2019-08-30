# Flowers-Recognition
A CNN model that detects 5 kinds of flowers.

```
Author - Atharva Pusalkar
Date created - 4th August 2019
```
Model details
```
Libraries used - TensorFlow, Keras, skimage, sklearn
Pretrained model used - VGG19
Optimizer - SGD
Loss Function - categorical_crossentropy
Callbacks - Early stopping
```
Dataset details
```
Classes - 5 (daisy, dandelion, rose, sunflower, tulip)
Number of train examples - 4109
Number of validation examples - 214
```
Output
```
Train accuracy - 99.22%
Train loss - 0.0267
Validation accuracy - 100%
Validation loss - 0.0015
```
Hyperparameters
```
Learning rate = 0.01
Learning rate decay=1e-6
Number of layers(excluding pretrained layers) - 8
Image dimensions - 150x150
Batch size - 64
Number of epochs - 30 (trained for 18 by early stopping)
```
Loss and accuracy over epochs - 
</br>
![Loss and Accuracy Plot](images/Plot.jpg?raw=true "Loss and Accuracy Plot")
</br>
Testcase -
</br>
![Prediction](images/Prediction.png?raw=true "Prediction")
</br>
Dataset can be downloaded from this link - https://www.kaggle.com/alxmamaev/flowers-recognition
</br>
To load the data set, unzip the downloaded file in the current working directory and run the image generator cells.
