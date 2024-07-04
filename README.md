# About the project
My first Machine Learning (ML) project using MNIST dataset. 

This was the assignment we had in the Machine Learning course at EC Utbildning. The assignment is written in Swedish. The assignment was to train an ML model to predict hand-written numbers with the MNIST dataset.

I was trying to get an accuracy score of at least 95% to be exceeded on the MNIST dataset. 

To model the MNIST dataset and get an accuracy score of at least 95%, machine learning models will be trained to recognize handwritten numbers. It is possible to use different algorithms and different models. This project has utilized training data and test data. Training data and test data are used in machine learning to evaluate the performance and generalization ability of a trained model. The entire training data of 60,000 handwritten digits has been used to train the model to make correct predictions and then the test data of 10,000 has been used to evaluate and its performance as well as ensure generalization and detect overfitting. By splitting test and training data, it is possible to build reliable and efficient machine learning models.

Models that have been applied to get an accuracy score of at least 95% are SVM, logistic regression and Randomized search. Accuracy score is used because it is a common and simple metric to evaluate the performance of a classification model, also easy to understand and interpret. It provides answers to how often the model's predictions match the actual observations.


The results can be summarized in the table below. All models give a high accuracy score of over 90%. The highest accuracy score is given by Randomized Search at 97% and this means that the model's predictions were 97% correct of all handwritten numbers (observations).
<img width="337" alt="mnist_result" src="https://github.com/FarhanaMos/ML_MNIST/assets/98036717/23c50268-da5e-4833-b955-a924687419df">
