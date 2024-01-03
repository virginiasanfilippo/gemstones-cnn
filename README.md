# **Gemstones Classification using CNN** :gem:
### Vision and Perception Course Final Project 
#### by Virginia Sanfilippo

Classification project using a CNN on [Kaggle Gemstones Images Dataset](https://www.kaggle.com/datasets/lsind18/gemstones-images).

The dataset contains 3,219 labeled images of 87 different types of gemstones, in various shapes - round, oval, square, rectangle, heart.

![img_1](https://github.com/virginiasanfilippo/gemstones-cnn/assets/61556610/e55c1753-c8f7-4ce4-801e-473168a641c2)

Augmentation methods were applied to the dataset in order to increase the number of samples, along with overfitting reducing methods.

The model was trained both with a simple CNN model and with a pre-trained network, MobileNet, using Adam and Crossentropy Loss, reaching a 60% accuracy with the CNN and a 70% accuracy with MobileNets. 

The graph shows the accuracy on training (orange) and validation set (blue).

![Schermata da 2020-12-17 18-26-46mio combo con batches di 10](https://github.com/virginiasanfilippo/gemstones-cnn/assets/61556610/f39a3c25-f18d-4580-886e-836ae932f16a)

Analyzing the results the low accuracy can be blamed on the relatively small number of samples and on the similarities between some of the classes.

![similarities](https://github.com/virginiasanfilippo/gemstones-cnn/assets/61556610/957a4c9c-6049-452d-a92f-ccbd460843b1)
