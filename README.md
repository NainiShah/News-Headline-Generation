# News Headline Generator
We have built a web application using flask framework in python that generates headline for the given news body. This application can be used by bloggers, journalists etc. where they can easily come up with the summarized headline for the article/blog they are working upon. We attempt to reproduce the results in the paper:  [Generating News Headlines with Recurrent Neural Networks](https://arxiv.org/pdf/1512.01712.pdf)

## How to run
### Software:
* Install python: [Official website](https://www.python.org/downloads/)
* Install anaconda: [Official website](https://www.anaconda.com/download/)
* Install [Keras](https://keras.io/) 
* Install [Tensorflow](https://www.tensorflow.org/install/)
* Neural networks are computations heavy, GPU configuration is recommended.

### Data
We have used [All the news dataset from kaggle](https://www.kaggle.com/snapcrack/all-the-news/data)
Extract only title and content from the dataset. Later, we tokenized the title,content and saved it as a pickle file. We divided our data set into train, validation and test sets respectively.

## Train / test
Train() method inside “ ” notebook describes how the model is trained using Keras
Test() method inside “ ” generates headline from the body inputted via test file

 






