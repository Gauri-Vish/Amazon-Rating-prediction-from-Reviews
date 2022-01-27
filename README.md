# Amazon-Rating-prediction-from-Reviews
Using Reviews from Amaxon reviews dataset and predicting the ratings based on the review

Hello There!
This is first nlp-ml prediction model that I have tried on Amazon reviews Dataset to predict the ratings based on the reviews. Surely we do get rating data directly but many a times the reviews and corresponding ratings do not match! Considering this thing I tried to make a model.

I have used RandomForest Classifier with tuned parameters using GridsearchCV

This Dataset was imbalanced and hence I did oversampling using SMOTE and that increased the prediction percentage quite significantly
There were two datasets provided one with 5000 rows and other one with 19000+ , both imbalanced ( I did a mistake of combining them and then oversampling which gave me MemoryError ofcourse duh!) So I took only those data which were less in number and merged and then oversampled and that worked efficiently(Aha moment for me!)

This model gave me prediction  accuracy  rate 92%! (fair enough)

Wokring on deployment will do it soon!
