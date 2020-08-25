# Movie Reviews Classification
* Created a Machine learning model that can classify reviews of a movie as positve or neagtive.
* Made use of the IMDB reviews dataset.
* Made use of the tensorfl and keras to build the machine learning model:
* The model is a convolution neural network with six different layers.
* here is description of the network:
```_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
embedding_1 (Embedding)      (None, 450, 32)           320000    
_________________________________________________________________
conv1d (Conv1D)              (None, 450, 32)           3104      
_________________________________________________________________
max_pooling1d (MaxPooling1D) (None, 225, 32)           0         
_________________________________________________________________
flatten (Flatten)            (None, 7200)              0         
_________________________________________________________________
dense (Dense)                (None, 250)               1800250   
_________________________________________________________________
dense_1 (Dense)              (None, 1)                 251       
=================================================================
Total params: 2,123,605
Trainable params: 2,123,605
Non-trainable params: 0
_________________________________________________________________
```
* Achieved an accuracy of 88.29% after training the neural network on the dataset.
