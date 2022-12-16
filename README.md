# LSTM-Attention Model for Music Generation

In this notebook, we will focus upon:
+ Data preparation steps for music generation.
+ We will use a subset of MIDI files from the dataset collected by reddit user ``u/midi_man``. The dataset is available here for reference: [reddit-link](https://www.reddit.com/r/WeAreTheMusicMakers/comments/3ajwe4/the_largest_midi_collection_on_the_internet/)
+ Sequence Preparation steps
+ Stacked LSTM with attention based model
+ Train and generate model


To start off, we first need to define and properly formulate the problem we want to solve. Since, this was a course project we could have chosen any problem. We finalized to work on classifying whether a sound could make a good tune. This was an extension of Human Activity Recognition problem, which using similar data, classifies the activities as running, walking, etc. In our case, we decided to have the some sound tunes.

Methodology
Data Cleaning -> Saving processed data

Adding features to classic ML models

Classic ML models used:

	1.Logistic regression
  
	2.K nearest neighbpours
  
	3.Linear SVC
  
	4.SVC with RBF kernel
  
	5.Random forest
  
	6.Gradient boosting
  
Deep learning models:

	1.LSTM

Input -> frequency and wavelength of different sounds in a song

Output -> various classification outputs

![image](https://user-images.githubusercontent.com/106107245/208173019-d619b581-4255-445c-a837-24b04c3c08bd.png)


Live Link

## https://colab.research.google.com/drive/1KjF2b4YG3ikIWIt-4pyRuFykWKMXR-zc?usp=sharing
