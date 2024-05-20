# SMS Spam Detector 

## Overview
This project was for educational purposes and aims to develop and create a refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, you will create a Gradio app to host the application, enabling users to test text messages. The application will provide feedback to users, indicating whether the text is classified as spam or not, based on the model's performance. 

## Prerequisites

The starter files consist of the following files: 
- 'sms_text_classification_solution.ipynb'
- 'gradio_sms_text_classification.ipynb'
- 'SMSSpamCollection.csv'

## Installing
The repo is public and can be cloned at:

https://github.com/col-mustang/sms_spam_detector

## Technologies Used 
- Python
- Pandas
- scikit-learn
- gradio
- sklearn 

## Built With
- Visual Studio Code - The source code editor used for development.
- GitHub Copilot - AI assistant that helps in writing better code.
- ChatGPT - AI model for generating documentation and guidance.
- Perplexity - AI assistant that helps generate and write cleaner code.

## Features
- Allows users to input SMS text messages.
- Predicts whether the input text is spam or not.
- Provides an intuitive interface for users to interact with.

 ## Requirements
- Create the SMS Classification Function (50 points)

    - The features variable is set equal to the text message column of the DataFrame. (8 points)

    - The target variable is set equal to the "label" column of the DataFrame. (8 points)

    - The data is split into training and testing sets, and the test_size is set to 33%. (8 points)

    - A Pipeline is built using the TfidfVectorizer and LinearSVC to transform the test set and compare it to the training set. (8 points)

    - The model is fitted to the transformed training data and the model is returned. (8 points)

    - The SMSSpamCollection.csv is read into a DataFrame. (5 points)

    - The DataFrame is passed to the sms_classification function and the result is set equal to the "text_clf" variable. (5 points)

- Create the SMS Prediction Function (30 points)
    
    - A variable that holds the prediction of a new text is created. (8 points)

    - A conditional statement that determines if the text message is "ham" or “spam” is created. (12 points)

    - The conditional returns a message if the text is “ham”. (5 points)

    -T he conditional returns a message if the text is “spam”. (5 points)

- Create the Gradio Interface Application (20 points)

    - A Gradio Interface application is created with three parameters for the “function”, “outputs”, and “inputs”. (6 points)

    - The “outputs” parameter is a textbox that contains a label to let the user know what to type in the box. (4 points)

    - The “inputs” parameter is a textbox that contains a label to let the user know that the prediction will be displayed in the textbox. (4 points)

    - The Interface application can be shared with other users with a public URL. (2 points)

    - The Gradio Interface works as expected and there are no errors after a user submits a text message. (4 points)

## Contributing
This project benefits from the contributions of:
- edX Boot Camps LLC - Educational partner providing guidance and resources.

## Authors
* **edX Boot Camps** - *Initial work* 
* **Geoff McDaniel** - *Final work*