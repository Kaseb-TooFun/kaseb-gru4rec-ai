# Kaseb GRU4Rec Intent Forecaster  

  - Deep model based on Gated Recurrent Unit
  - Implemented in PyTorch 1.6

Dataset: The dataset is the YOOCHOOSE e-commerce dataset for RecSys 2015 Challenge consisting of 9.2 million user sessions. It contains the sequence of clicking events when the user is surfing on the e-commerce site.


Dataset details: Each record/line in the file has the following fields: Session ID, Time stamp, item ID, Price, Quantity


Goal: The task is to predict for each session in the test file, whether there is going to be a buying event in this session, and if there is, what are the items that will be bought.


Method: sequential learning using recurrent methods with Gated Recurrent Unit (GRU) which is a simplified version of LSTM.

Training loss is the error on the training set of data. Validation loss is the error after running the validation set of data through the trained network. Train/valid is the ratio between the two. Unexpectedly, as the epochs increase both validation and training error drop.
mrr: Mean Reciprocal Rank is a measure to evaluate systems that return a ranked list of answers to queries.
Recall: the fraction of the total amount of relevant instances that were actually retrieved.


Google's Cloud AutoML was announced in January 2018


automated ML capability in Azure Machine Learning: September 24, 2018


Amazon’s AutoGluon: December 2019


NNI (Neural Network Intelligence) is a lightweight but powerful toolkit to help users automate Feature Engineering, Neural Architecture Search, Hyperparameter Tuning and Model Compression.


<a href="#nni-has-been-released"><img src="assets/overview nni.svg" /></a>




