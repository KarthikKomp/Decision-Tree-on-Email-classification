# Decision-Tree-on-Email-classification

""" 
    This is the code to accompany the (decision tree) mini-project 3.

    Use a Decision Tree to identify emails from the Enron corpus by author.
"""

features_train and features_test are the features for the training
and testing datasets, respectively
labels_train and labels_test are the corresponding item labels

The Enron corpus's (famous for its financial scandal in the year 2001) data was recently released by the CALO Project 
(A Cognitive Assistant that Learns and Organizes: https://www.cs.cmu.edu/~./enron/) contains a huge set of emails which were sent by the senior level management in the organisation.

Before the final project of "Finding the persons of Interest" in the scandal, we try to develop a proof of concept for classifying and predicting the name of the author by making the machine learn several emails sent by each author. 
Once the machine process all the emails during preprocessing & training, we try to compute the accuracy of the algorithm for this particular data set by seperating a portion of data & its labels for testing.

Mini-Project 1 & 2 focussed on SVM & Naive Bayees algorithms performance and amount of time taken to learn and predict (refer to this link for more details on project 1: 
https://github.com/KarthikKomp/Support_Vecto_Machiner-vs-Naive_Bayes). 

In the current python project, we try to compute the time & performance taken to learn and predict the author of the emails using the decision tree algorithm.

#Output for the decision tree algorithm!


no. of Chris training emails: 7936

no. of Sara training emails: 7884

Output values for a range of inputs: [0 0 1 ..., 1 0 0]

Accuracy scores: 0.966439135381

Time taken for training: 105.79 s 

Time taken for prediction: 17.926 s

Total number of emails processed: 15,820
