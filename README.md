# Deep learning utilization through Pytorch, Keras and Tensorflow 

## Pytorch

## Keras

- Keras_MNISTdataset: Classification task on the mnist dataset (recognition of numbers on picture) first by using a neural network with dense layers then by using convolutionnal layers.
- Semantic segmentation: Segmentation task ie labelling each pixel of an image with a corresponding class of what is being represented. From professional seismic imaging we try to predict which areas in the surface of the Earth contain huge amount of salts. We use a training set having both seismic imaging and the segmentation of area with salts for the corresponding image. To do so we set up a U-NET which is a encoder-decoder like architecture: First path is the contraction path (also called as the encoder) which is used to capture the context in the image. The encoder is just a traditional stack of convolutional and max pooling layers. The second path is the symmetric expanding path (also called as the decoder) which is used to enable precise localization using transposed convolutions. Thus it is an end-to-end fully convolutional network (FCN), i.e. it only contains Convolutional layers and does not contain any Dense layer because of which it can accept image of any size.
- TD Capryo - Keras: classifcation task on the cifar-10 dataset (recognizing images between 10 classes) using CNNS


## Tensorflow
