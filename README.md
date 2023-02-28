# Face-Recognition
The target of this project is to implement an “Emotion Recognition Strategy”.
First of all, we start by choosing and defining a dataset. In this case, we used fer2013.csv, made by more than 30000 values divided in 3 different columns:
-The first one, defined as “emotion”, is composed by 7 different numbers (from 0 to 6), each one, in our representation, stays for a particular emotion. In our case, 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad,
5=Surprise, 6=Neutral;
-The second column, called “pixels”, contains a list of integers, that represents a specific image;
-The last one, called Usage, describes the effective usage of the dataset,divided in 3 different categories: Training, PublicTest and PrivateTest.
In the instruction of the Project, it was given a free choice in what architecture could be used, like SVM, CNN etc….
Personally, I tried both SVM and CNN, and I find better results with this last one. Obviously, I tried several combinations of different CNN-based architecture until I found the one that satisfy the requirements of a good precision and, not for a second choice, a good efficiency.
