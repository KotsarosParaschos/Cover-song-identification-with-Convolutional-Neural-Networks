# Cover-song-identification-with-Convolutional-Neural-Networks 
The goal of this project is to prove that we can use pre-trained convolutional neural networks to identify song covers.

For this project we picked 3 songs and downloaded 25 covers for each song in order to prepare the dataset. 

Dataset Preparation: 
The preparation of the dataset happens in two steps. The first step is to cut the mp3 of the songs into shorter pieces. We tried many different durations ranging from 10s to 30s. To do this we made a small python program with the help of the librosa library

Then with the help of another small python program we convert the mp3s to spectograms,save them as images and split the into training data and test data

CNN models:
The models we used for this project are Densenet,VGG16 and InceptionV3. We experimented a bit with adding and freezing some layers.

Results:
The ending results are promising but show that the dataset was too small for this project and that caused overfitting. The training accuracy of the models was very high (over 90%) but the validation accuracy never passed 65%. With more covers used the results could be better
