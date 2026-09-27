 MOVIE REVIEW SENTIMENT ANALYSIS

This project is about Movie Review Sentiment Analysis. It uses Machine Learning to find out whether a movie review is positive or negative. The project has two parts: the Main Notebook and the GUI Prototype.

#Data Preparation

First, the IMDb movie review dataset is loaded. The data is checked for missing values and duplicate reviews. Duplicate data is removed, and the positive and negative reviews are studied.

#Text Preprocessing

The computer cannot directly understand normal text. So, TF-IDF is used to change the movie reviews into numbers. These numbers help the machine learning model understand the important words in the reviews.

#Model Training

The data is divided into different parts for training and testing. Three machine learning models are used:

* Naive Bayes
* Logistic Regression
* Linear SVC

These models are trained using the movie review data.

#Model Evaluation

The models are checked to see how well they predict the reviews. Accuracy,Precision,Recall,and F1 Score are used for evaluation. The model that performs best is selected as the final model.

#Model Saving

The final model and TF-IDF tool are saved in a file named sentiment_analysis_model.pkl`. This allows us to use the trained model later without training it again.

#GUI Prototype

A simple GUI (Graphical User Interface)** is created using Gradio. It allows users to enter a movie review in a text box. The saved model is loaded into the GUI.

#Sentiment Prediction

When the user enters a movie review, the system processes the review and gives a result. It predicts whether the review is positive or negative. The result is shown as “Predicted Sentiment.” If the user does not enter anything, the system asks them to enter a review.

#Conclusion
Overall, the project successfully uses Machine Learning to predict whether a movie review is positive or negative. The Main Notebook is used to train and test the model, while the GUI Prototype makes it easy for users to enter a review and get the predicted sentiment.
