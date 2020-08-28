# DeepLearning_CNN with Tensorflow 2.0 and Keras

As a beginner in Deep Learning and CNN , I tried to use the Google Colab to experiment with few of the popular architectures of Convolutional neural network .
I have started with a simple CNN model ,then progressed to transfer learning with VGG net, then moved on to building a resnet50 network from scratch(using TF2.0 & keras API), implemented the mobilenet version 1. Hope this could help a beginner in CNN and motivate him/her to experiment with various CNN architectures.

The code includes:
1.TF2_0_Cifar10.ipynb - an example for usage of keras functional apis for implementing a CNN model.

2.TF2_0_TransferLearningVGG16_1.ipynb - the convolutional blocks(excluding the Dense layers) of VGG16 have been used for getting the features from the dataset,
those features have been used as the input feature for the custom Dense layer. Its an example of using VGG16 for transfer learning.

3. TF2_0_TransferLearningVGG16_2.ipynb - In this code I freeze all the conv blocks of VGG16( usual approach for transfer learning), and only train the custom Dense layers.

4.TF2_0_TransferLearningVGG16_3.ipynb -In this code I freeze all the conv layers of VGG16 except the last conv layer. Last conv layer of VGG16 gets trained along with the custom Dense layer. 

5.TF20_ResNet50.ipynb -Implementation of ResNet50 from scratch using keras APIs. Its a basic implementation only for the understanding of the resnet architecture. 

6.TF2_0_MobileNetv1_TransferLearning.ipynb - Transfer learning with mobilenet version 1. Excluding Dense layers all other layer is freezed.

7.TF2_0_MobileNetV1_FromScratch.ipynb - An implementation of mobilenet version 1 from scratch using Keras APIs.


Note: 
1.Cifar-10 dataset has been used for training and validation.
2. GPU  has been selected in google colab runtime.

If you are looking into the codes and come across any bugs in the codes, please comment.

Thanks for reading
