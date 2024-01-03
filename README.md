# **Gemstones Classification using CNN** :gem:
### Vision and Perception Course Final Project 
#### by Virginia Sanfilippo

Classification project using a CNN on [Kaggle Gemstones Images Dataset](https://www.kaggle.com/datasets/lsind18/gemstones-images).

The dataset contains 3,219 labeled images of 87 different types of gemstones, in various shapes - round, oval, square, rectangle, heart.

![img_1](https://github.com/virginiasanfilippo/gemstones-cnn/assets/61556610/e55c1753-c8f7-4ce4-801e-473168a641c2)

Augmentation methods were applied to the dataset in order to increase the number of samples.

![img_2](https://github.com/virginiasanfilippo/gemstones-cnn/assets/61556610/88a3988f-3690-4f32-a287-b0ab99770b15)

The model was trained both with a simple CNN model and with a pre-trained network, MobileNet, using Adam and Crossentropy Loss, reaching a 60% accuracy with the CNN and a 70% accuracy with MobileNets. The model showed an overfitting problem, and analyzing the results the low accuracy can be blamed on the similarities between some of the classes.

![similarities](https://github.com/virginiasanfilippo/gemstones-cnn/assets/61556610/957a4c9c-6049-452d-a92f-ccbd460843b1)
