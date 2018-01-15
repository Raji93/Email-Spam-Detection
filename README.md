# Email-Spam-Detection

This project aims at detecting Spam from a data set of emails.

While building the code,the data set used was divided into ham and Spam folders.The following are the steps performed as part of Spam detection.

Step 1:
-------
Read all the emails in given ham and spam folders.

Step 2:
-------
Build a function that returns a list of words present in a file given a fileName.

Step 3:
-------
Call the above function for all the emails present in both the above folders and create two separate lists.

Step 4:
-------
We will now use the lists created above to create a feature matrix. Our feature matrix is a binary feature matrix which indicates if a word is present in an email.


Step 5:
-------
Create a training set and test set from the existing emails data set.

Step 6:
-------
Perform Cross validation and using KNN find the best K value.

Step 7:
-------
Create a feature matrix for test set as we did fir training data.

Step 8:
-------
Implement Bernoulli Naive Bayes classification and Perform Laplace smoothning.

Step 9:
-------
Implement sVM Kernels
