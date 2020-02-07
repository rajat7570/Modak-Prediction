# Modak-Recognisation :-
Coded in Google Colab plateform.
Steps and Approch:-
1) Collection of modak image data and other sweet data from google images.
2) Image Processing- Training image converted into 100*100 size and greyscale format.
3) Images is converted into numpy array with their labels so that we can feed them into out Convolutional Neural Networks.
4) Preparation of model.
5) Training and saving of Convo model.
6) Prediction on test image. Preparation of test image so that model will available to predict it.
7) Printing a graph showing the accuracy changes during the training phase
Since my training accuracy is so high but validation accuracy is moderate. So my model is likly to move towards overfiiting behaviour. 
This can be improved by using Data Augmentation(Data Orientation, mirror images, crops, etc.), early stoping and tuning dropout regularisation.

