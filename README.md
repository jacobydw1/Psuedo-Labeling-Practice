# Psuedo-Labeling-Practice
This is a kaggle.com project that focused on practicing pseudo labeling to improve your model.
My prediction modeli isn't very accurate, but i'm still practicing and trying to figure out how psuedo-labeling works.

Pseudo labeling is the process of adding confident predicted test data to your training data. Pseudo labeling is a 5 step process. (1) Build a model using training data. (2) Predict labels for an unseen test dataset. (3) Add confident predicted test observations to our training data (4) Build a new model using combined data. And (5) use your new model to predict the test data and submit to Kaggle. Here is a pictorial explanation using sythetic 2D data.
