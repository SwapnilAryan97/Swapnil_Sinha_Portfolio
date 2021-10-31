# Swapnil Aryan Sinha's Portfolio

## [Project 1: Password Encryption and Storage](https://github.com/SwapnilAryan97/Hashing)
* Designed for students/developers who want a custom hashtable with built-in encryption for saving passwords.
* The hashtable is written in Java.
* The hashtable references a char array which stores the passwords in the order they were inserted in and the index in the character array at which the string is stored is kept in the hashtable.
* The strings are read as an input from a text file with numbers as instructions and strings as value. If a string is deleted from the hashtable, it will replace the string in the char array as a sequence of ‘*’. If load-factor  > 50%, table is rehashed.
* Each command is a numeric equivalent of the function named earlier plus one more (for comment). Command 10 is Insert, Command 11 is Deletion, and Command 12 is Search. Command 13 is Print, Command 14 is Create. Command 15 is Comment: the rest of the line marked by a 15 is ignored. Command 14 for create has an argument which is the value of N. Each one of 10, 11, and 12 has an argument which is a string.

## [Project 2: INGV - Volcanic Eruption Prediction](https://github.com/SwapnilAryan97/projects/blob/master/ingv-volcanic-eruption-prediction-using-xgboost.ipynb)
* Detecting volcanic eruptions before they happen is an important problem that has historically proven to be a very difficult.
* The data represent a classic signal processing setup that has resisted traditional methods.
* The objective is to predict the time for any volcanic eruption based on the data sent by various sensors around volcanoes.
* The shifts in the techtonic plates are measured by sensitive vibrational sensors and these vibrations in the form of raw data is injected into the model and an approximate time is projected.
* There is 29GB of data on which calculations have to be done.
* The data is transformed and dimentionality reduction is performed for our regression model.
* XGBoost regression is performed on the transformed data and the result is predicted and compared.

![](https://github.com/SwapnilAryan97/Swapnil_Sinha_Portfolio/blob/main/images/Unknown.png)

## [Project 3: Housing Price](https://github.com/SwapnilAryan97/Swapnil_Sinha_Portfolio/blob/main/images/Unknown.png)
* The dataset contains 81 attributes based on which cost of housing will be influenced.![image](https://user-images.githubusercontent.com/18083356/139595971-2d6d7458-2bdf-4927-9492-717650b6deba.png)

* The goal is to predict the sales price for each house in the dataset.
* Numerical and categorical data are computed seperatetly and normalized by passing it through a pipeline model to avoid data leakage.
* The data is then further preprocessed and passed through different regression models each through a smiliar pipeline structure. 
* The mean of all the models is taken and the final output is provided.

## [Project 4: Email Spam](https://github.com/SwapnilAryan97/projects/blob/master/EmailSpamDetection.ipynb)
* A Machine Learning Model that uses Natrual Language Processing to detect spam emails with 99.04% accuracy.
* A csv file containing manual entry of 5727 emails stating whether they're email spams or not.
* The data is then restructured and passed through an algorithm that categorizes which words are commonly used in spam mails.
* Logistic regression is then performed on the said data and a confusion matrix is created to check for faults.
* An accuracy of 99.04% is achieved with this model.

## [Project 5: Loan Default](https://github.com/SwapnilAryan97/projects/blob/master/LoanDefaultPrediction.ipynb)
* Calculated the probability of a customer to be in a loan default with an accuracy of 81.37% by programming an ML model using 3 classifier algorithms.
* Data is preprocessed (fill missing data, feature scaling, etc.) and the prediction is computed through Logistic Regression, KNN Classifier and Naive Bayes Classifier.
* Naibe Bayes Classifier and Logistic Regression end at a tie each with 81.37% accuracy.

## [Project 6: Sorting Algorithms](https://github.com/SwapnilAryan97/sorting_java)
* An open source code for developers who want high efficient sorting algorithms written in Java.
* The sorting algorithms implemented are: 
  - Merge Sort
  - Quick Sort
  - Radix Sort (2 variations)
  - Counting Sort
  - Selection Srot
  - Shell Sort
  - Bubble Sort
  - Insertion Sort
