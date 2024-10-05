# ImageCaptioning

Intended to create a model, that takes an image and outputs a relevant caption regarding it.
Implemented \Transfer-Learning on VGG-16 to extract the feature vector of the image, from the second last dense layer, on FLICKR-8K, and train it sequentially through LSTM as time-series data by tokenizing and padding captions.
Given a image as input, passes it through VGG-16 to extract features and then the trained model predicts a suitable caption for it, with 0.58 BLEU-1scores for 1-gram!
