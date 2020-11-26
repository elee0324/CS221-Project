# Introduction

As more and more people from many nations learn to speak English, an increasing amount of text is translated from foreign languages to English. We are building a system that facilitates this cross-cultural communication by identifying the source languages of translated texts from around the world. We have built a corpus of professionally-translated short stories in six different source languages, and our goal is for our model to classify brief passages of those stories by their original language.

# Files

The SplitData.py file takes in full chunks of text, cleans the text and splits it into 10 word text blocks, then separates it into training, validation, and testing sets (each with its own folder). It also creates files containing all of the features in the training dataset for uni-gram and bi-gram.

The cs221.py file trains, tests, and validates our KNN, logistic regression, and SVM models. We changed model variable in line 14 to be 1 for unigram or 2 for bigram.  Otherwise, we just ran to program to collect our results. We also changed the valPath (Line 133) to ÔTest_TestÕ and only ran the logistic unigram C = 10 with L2 regularization, in order to test our final model.

The rnn.py file contains our RNN model.

CS221_2_.pdf is our paper for the project, and 221_poster_2.pdf is our poster for the CS221 Fall 2019 poster session. 


