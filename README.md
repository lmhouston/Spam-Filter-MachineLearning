# Spam-Filter-MachineLearning
A spam filter derived from SMS data set (uses Machine Learning)

This Python script ues machine learning to train the computer to identify SMS spam that is like the data from this data set:
https://www.kaggle.com/uciml/sms-spam-collection-dataset/version/1

I adapted this script from one developed by pemagrg1 here: https://github.com/pemagrg1/text-classification/blob/master/text_classification.ipynb. While she developed code to analyze categories of news stories, I revised it to apply to the SMS spam data set. While she provides both a naive model and a logistic regression model, for my spam filter, the naive model met with greater success (98%) so I have only included that one.

The example I have entered into this script and asked to computer to predict is "We request customer re-register credit cards." This was part of a real email that made it past Google's spam filter and into my inbox a couple of weeks ago. While this script worked to successfully identify the message as spam, the script works better to predict SMS spam over email spam because of the nature of the data set it was trained against.

Overview:
THe script works as follows: installs needed libraries, stems the words of the SMS messages in the data set, trains and then tests the computer, and then asks it to predict "spam or ham" against a message I chose. It tested at 98% accuracy and accurately identified my sample phrase as spam.
