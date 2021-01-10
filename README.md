# COVID-19-Radiography-Results-Prediction-Using-CNNs
In this repository I have utilised **Convolutional Neural Networks** to predict whether the images detect a covid+ve patient, viral pneumonic patient and a normal patient. 
The dataset is Covid 19 Radiography  Database which has been updated as on 5 January 2021. The dataset has been imported from Kaggle with the following link:-
https://www.kaggle.com/tawsifurrahman/covid19-radiography-database/download
I have used two methodologies for this classification.
<br>
**1) CNN Using Keras Tuner**
<br>
I used **Keras tuner** for hyperparamter tuning and created a very simple convolutional neural network having only two convolutional layers and two dense layers.
It just took around 2 minutes to train and acheived accuracies of around 97% in training set and 95% in validation and test sets and acheived excellent results
in a very minimal time.
<br>
**2) Transfer Learning Using VGG16 Model**
<br>
So here I implemented the classification using **VGG16** Model. One layer was added after it so as to get our output and the pretrained model wasn't trained. 
It took around 27 minutes to run for a single epoch and acheived a test set accuracy of around 93%. It also acheived excellent results on precison,recall 
and f1 scores for each of the classes 
