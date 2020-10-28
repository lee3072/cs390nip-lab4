--------------------------------------------------------------------------------
# CS390NIP Lab 4 GANs
--------------------------------------------------------------------------------

Written by Sri Cherukuri, Anthony Niemiec, and Maxwell J. Jacobson.


This code is for CS390NIP: Neural Image Processing at Purdue University.


--------------------------------------------------------------------------------
# Report
--------------------------------------------------------------------------------

Name: Seung Heon Lee


Email: lee3072@purdue.edu


## Hyperparameters


Learning Rate: 0.0002 (Both Generator and Discrimiator)


Epochs: 60000


BatchSize: 32 (Both Generator and Discrimiator)


Activation function hidden layers: LeakyReLU (Both Generator and Discrimiator) [alpha: 0.2] 
* LeakyReLU multiplies alpha value if the ouput is lower than 0




Activation function last: sigmoid (Discriminator) 
* NOTE: sigmoid to adjust output range to 0 to 1, which is possiblity of image being true


Activation function last: tanh (Generator) 
* NOTE: tanh to adjust output range to -1 to 1, which is pixel value range


Optimization Algorithm: Adam (Both Generator and Discrimiator)


Loss Function: binary_crossentropy (Both Generator and Discrimiator)


Number of layers: 3 (Discriminator)


Number of layers: 4 (Generator)

--------------------------------------------------------------------------------