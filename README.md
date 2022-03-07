# Deep learning utilization through Pytorch, Keras and Tensorflow 

## Pytorch

- TP GAN DCGAN - pytorch: By using a DCGAN (type of GAN that explicitly uses convolutional and convolutional-transpose layers in the discriminator and generator) we want to generate handwritten digits using the MNIST dataset. In a second part we use a cGAN (a cGAN (conditionnal) is a supervised GAN aiming at mapping a label picture to a real one or a real picture to a label one) to generate facades from a template image. Our Generator there we'll have a U-NET architecture and the discriminator is a Patch GAN.
- TP image captionning - pytorch: By using an encoder-decoder architecture and a mecanism attention we want to produce a caption for an image (ie a describing sentence for an image). The encoder will be a pre-trained CNN like resnet or vgg and the decoder will use RNN cells like LSTM or GRU. 
- TP reinforcement learning - pytorch: We study the use of reinforcement learning on two games: cartpole and breakout with a dqn architecture. In the first game we only use dense layers and in the second one we use CNNs

## Keras

- Keras_MNISTdataset: Classification task on the mnist dataset (recognition of numbers on picture) first by using a neural network with dense layers then by using convolutionnal layers.
- Semantic segmentation: Segmentation task ie labelling each pixel of an image with a corresponding class of what is being represented. From professional seismic imaging we try to predict which areas in the surface of the Earth contain huge amount of salts. We use a training set having both seismic imaging and the segmentation of area with salts for the corresponding image. To do so we set up a U-NET which is a encoder-decoder like architecture: First path is the contraction path (also called as the encoder) which is used to capture the context in the image. The encoder is just a traditional stack of convolutional and max pooling layers. The second path is the symmetric expanding path (also called as the decoder) which is used to enable precise localization using transposed convolutions. Thus it is an end-to-end fully convolutional network (FCN), i.e. it only contains Convolutional layers and does not contain any Dense layer because of which it can accept image of any size.
- TD Capryo - Keras: classifcation task on the cifar-10 dataset (recognizing images between 10 classes) using CNNS

## Tensorflow

- TensorFlow cooking book examples: DeepDream (uses a convolutional neural network to find and enhance patterns in images via algorithmic pareidolia, thus creating a dream-like appearance reminiscent of a psychedelic experience in the deliberately over-processed images), StyleNet (Stylenet is a procedure with CNNs that attempts to learn an image style from one picture and apply it to a second picture while keeping the second image structure (or content)intact.), tic-tac-toe  (develop a dense layer based neural network to play tic-tac-toe).
