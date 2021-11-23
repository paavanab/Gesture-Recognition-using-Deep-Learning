# Gesture-Recognition-using-Deep-Learning
Problem Statement:
As a data scientist at a home electronics company which manufactures state of the art smart televisions. We want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 
Thumbs up	:	Increase the volume.
Thumbs down	:	Decrease the volume.
Left swipe	:	'Jump' backwards 10 seconds.
Right swipe	:	'Jump' forward 10 seconds.
Stop		:	Pause the movie.
		
Understanding the Dataset
The training data consists of a few hundred videos categorized into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames (images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 

Objective
Our task is to train different models on the 'train' folder to predict the action performed in each sequence or video and which performs well on the 'val' folder as well. The final test folder for evaluation is withheld - final model's performance will be tested on the 'test' set.

Approach
1.	3D Convolutions
2.	 CNN + RNN Architecture
