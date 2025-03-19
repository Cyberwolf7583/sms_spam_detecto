## SMS Spam Classification with Gradio ##

This project provides a simple and effective resolution for classifying SMS messages as either spam or non-spam (ham) through machine learning. It is based on Python, has an easy to use web interface powered by Gradio, and uses the scikit-learn library to support machine learning.

## Overview ##

The project involves three primary steps. First, SMS messages are loaded from a CSV file and preprocessed, which means the data is cleaned and organized to make it easier for analysis. Next, the prepared messages are transformed into numerical form using a method called TF-IDF, which emphasizes the importance of certain words. These numerical representations are then used to train a machine learning model called Linear Support Vector Classification (LinearSVC), teaching it how to recognize spam messages. Finally, the trained model is deployed through a simple, user-friendly web interface built with Gradio. Users can enter any SMS message on this website and instantly see whether the message is classified as spam or not.

## Usage ##

Enter an SMS message in the provided input box in the Gradio interface, and the application will classify it as spam or not spam.

## Example SMS Messages for Testing in the Gradio app ##

You are a lucky winner of $5000!

You won 2 free tickets to the Super Bowl.

You won 2 free tickets to the Super Bowl text us to claim your prize.

Thanks for registering. Text 4343 to receive free updates on medicare.


