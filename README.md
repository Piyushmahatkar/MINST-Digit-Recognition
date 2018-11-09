# MINST-Digit-Recognition
Digit Recognition using 2 layer convolutional Neural Network on Keras - Tensorflow

### Overview:

Resulting accuracy on 5th epoch:
Training Accuracy: 98.20%
Test accuracy: 99.04%
Train on 60000 samples, validation on 10000 samples

### Future Updates: 

Parameter tuning needed. filter sizes need to change, code can be optimized for computation. Soon I will upload a new code, with better amalgam of networks and parameters.

### Model Summary

### Layer (type)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                 Output Shape&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;              Param   

conv2d_1 (Conv2D)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;            (None, 22, 22, 100)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       5000  
conv2d_2 (Conv2D)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;            (None, 19, 19, 10)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;        16010     
max_pooling2d_1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (MaxPooling2 (None, 9, 9, 10)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          0         
dropout_1 (Dropout)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          (None, 9, 9, 10)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          0         
flatten_1 (Flatten)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          (None, 810)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;               0         
dense_1 (Dense)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;              (None, 128)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;               103808   
dropout_2 (Dropout)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          (None, 128)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;               0         
dense_2 (Dense)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;              (None, 10)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                1290      


Total params: 126,108
Trainable params: 126,108
Non-trainable params: 0

