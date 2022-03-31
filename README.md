# Music adaptations recognition using deep learning


ABSTRACT

The purpose of this work is the identification of musical adaptations with the use of deep learning and more specifically with the use of pre-trained convolutional neural networks.

Initially, the dataset was created using the python language and its various libraries (numpy,pandas,matplotlib). The first step was to break the songs into shorter pieces to increase the amount of data that would be used by the models. There was a lot of experimentation during this process and various durations ranging from 10 to 30 seconds were tested. The audio signals of these tracks were then converted into spectrograms and stored in jpg image format. Finally, to complete the dataset, these images were randomly divided into 2 folders which constitute the training set and the validation set. All of the above are made with python

The transfer learning technique was used for the training of the networks, according to which, the pre-trained models are used with some configurations in order to achieve faster results. The models tested in this process were VGG16, DenseNet and Inceptionv3 because they have already been used for similar classification problems with proven results. Finally, through some unsuccessful examples of transfer learning (because of the small amount of data) we come up with ways in which we could improve this process for better results.
