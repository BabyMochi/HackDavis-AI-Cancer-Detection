# HackDavis-AI-Cancer-Detection

# Inspiration
Cancer is the second highest form of death among the global population. Nearly 1 out of 3 people in the US will be diagnosed with cancer in their lifetime. 1.8 million people were diagnosed with cancer in 2019, with 607,000 people's lives taken by the disease, including some of those close to us. While a cure for cancer still evades us, steps can be taken to reduce the impact that it has. As the World Health Organization stated, "Early detection of cancer dramatically increases chances for successful treatment." With this in mind, our team set out to save as many lives as possible by combining the technologies of machine learning, artificial intelligence, and computer vision to help spot and stop cancer.

## What it does:
Skin Cancer: Our app allows users to upload an image of a tumor in question to determine whether it is classifies as benign (harmless), or malignant (dangerous). The app also classifies which form of cancer the tumor resembles: melanoma (MEL), basal cell carcinoma (BCC), or actinic keratosis /Bowens disease (AKIEC). The potential for this project to have a global impact lies in the fact that any person in their home can take a picture of their own skin, run it through the program, and receive real-time feedback about the issue in question with higher accuracy than professional diagnosis. Model is trained through the use of a Convolutional Neural Network.

Brain Cancer: This aspect of the app is tailored more towards the professional audience (doctors and other health care workers) in that it allows the user to input MRI scans and detect signs of hemorrhage. Trained with a dataset consisting of thousands of pre-classified MRI scans, this model makes use of patterns unrecognizable to the human eye, ultimately making predictions 99.17% accuracy; a number far beyond the scope of human judgement. Model is trained through the use of a Convolutional Neural Network.

Breast Cancer: Trained with an Artificial Neural Network as opposed to the previous models which utilized computer vision, this algorithm is capable of using .csv files to train itself and make predictions. This model is used for those who have access to numeric and categorical data as opposed to image files, and boasts impressive run-times and accuracy. Training itself in under 10 seconds, this model breast cancer diagnoses with 97% precision. Not only that, but the model used can be generalized to make predictions on any .csv dataset. This neural network can be applied to the fields of health care, finance, sales, or any other that seeks to take advantage of Big Data to leverage business insights.

## How the regression models were built:
Combining a variety of Python libraries (Keras, TensorFlow, SkLearn, etc.) and Kaggle datasets, each model was trained on data, and the regression equations were exported then the equation was used to make a prediction about a user-defined piece of data. All datasets were preprocessed and split into test and training sets, and each model's accuracy was verified against the test sets. The Google Colaboratory remote GPU was used to train the Convolutional Neural Networks, with the local CPU being used to train the Artificial Neural Networks.

## Challenges:
Preprocessing data, imputing missing values, standardizing data, installing the necessary libraries, managing run-time issues, transferring large datasets, over fitting, and linking the back end with the front end.

## Accomplishments:
Our team is proud of the fact that all of our predictions were made with models that we trained by ourselves, and no pre-trained ML software was used at all. Furthermore, our application utilizes both Convolutional and Artificial Neural Networks, allowing it to recognize both image files and numeric/categorical data. We have also created a web application that allows for a user-friendly experience despite none of us having prior Flask experience. In addition, we've been able to utilize our different educational backgrounds to bring unique insights to the project. Most importantly however, is that this product serves to combat cancer and has the potential to possibly save a life.

## What we learned
We learned how to use Python Flask for front end and numerous machine learning algorithms for back end.

## What's next for ML Diagnose
A big limitation with this project was time and processing power. In the future, ML Diagnose will have more accuracy as we will be able to train with bigger datasets and a larger number of epochs/neural-network-layers.

Access to files on Google Drive
Brain Tumor CNN - https://drive.google.com/drive/folders/1gKv41n_n8I_Q3n79K7BRnGUSZtpRoy2z?usp=sharing
Skin Cancer CNN - https://drive.google.com/drive/folders/1-i04lh7KtMQQNSdfGCRMzWWdaVsOkKpi?usp=sharing
Breast Cancer ANN - https://drive.google.com/drive/folders/1Mp6BiXSbncNzAIDILMIWvOoi-BQ4xcVo?usp=sharing
Skin Cancer In-Depth CNN (beta) - https://drive.google.com/drive/folders/102Ezlt6plIZEIIIZw6Qvz9rzXhmcuBmI?usp=sharing

Built With
flask
google-colabs-remote-gpu
keras
numpy
pandas
pickle
python
scikit-learn
tensorflow
