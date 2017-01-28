# How_to_do_Sentiment_Analysis
This is the code for 'How to Do Sentiment Analysis' #3 - Intro to Deep Learning by Siraj Raval on Youtube


##Overview

This is the code for [this](https://youtu.be/si8zZHkufRY) video on Youtube by Siraj Raval. It uses [TFLearn](http://tflearn.org/) to train a Sentiment Analyzer on a set of IMDB [Movie ratings](https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset). Once trained, given some input text, it will be able to classify it as either positive or negative. The neural network that is built for this is a [recurrent network](https://en.wikipedia.org/wiki/Recurrent_neural_network). It uses a technique called [LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) which I'll really deep dive into in later videos.

##Dependencies

* tflearn

Use [this](http://tflearn.org/installation/) guide to install TFLearn. Or just use the Amazon Web Services prebuilt [AMI](https://aws.amazon.com/marketplace/pp/B01EYKBEQ0/ref=_ptnr_wp_blog_post) to run this in the cloud


##Usage

Run ``demo.py`` in terminal and it should start training

##Challenge

The challenge for this video is to use TFLearn to train a recurrent net, like the one in this example, on [this](https://www.kaggle.com/egrinstein/20-years-of-games) dataset of video game reviews from IGN.com. Then, given some input text it should be able to classify it. You can use [pandas](http://pandas.pydata.org/) to parse this dataset. Right now each review has a label that's either Amazing, Great, Good, Mediocre, painful, or awful. Using the existing labels is *extra credit*. The baseline is that you can just convert the labels so that there are only 2 (positive or negative). 


##Credits

Credits for this code go to the [author](https://github.com/aymericdamien) of TFLearn. I've merely created a wrapper to get people started.
