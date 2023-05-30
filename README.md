# Prediction-and-Classification-of-tweets-which-represents-hatred-or-non-hatred
•	Scraped tweet data from Twitter using the "snscrape.modules.twitter" library, collecting information such as tweet ID, date and time, username, and the content of the tweets.
•	Developed a prediction and classification model using machine learning algorithms and LSTM for identifying tweets representing hatred or non-hatred with high accuracy.
•	Preprocessed and cleaned the data to improve sentiment analysis by removing noise and special characters.
•	Built an initial sentiment model using the Vedar Sentiment from the NLTK package.
•	Observed a significant difference between the training and testing accuracies, indicating overfitting in the model.
•	Achieved a significant improvement in model performance compared to the initial sentiment model, with an accuracy of 99.9% for Random Forest and 99.7% for Stacking classifier in identifying hatred or non-hatred tweets.
•	Reduced overfitting through feature engineering and scaling techniques, resulting in similar accuracy scores for training and testing data.
•	Implemented an LSTM model that achieved promising results with an accuracy of 77.29% on the training set and 73.12% on the validation set, demonstrating its capability to classify tweets into hatred or non-hatred categories while reducing overfitting.
