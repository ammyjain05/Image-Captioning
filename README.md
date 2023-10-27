# Image-Captioning

This project's goal is to forecast descriptions for an input image. The dataset comprises 8,000 images, each accompanied by five captions. Both image and text captions are used to extract features for input, which are then combined to predict the following word in the caption. Convolutional Neural Networks (CNN) are employed for image analysis, while Long Short-Term Memory (LSTM) networks are utilized for text processing. The model's performance is assessed using the BLEU Score metric.

# Dataset 
Download link: https://www.kaggle.com/adityajn105/flickr8k

# Neural Network

InceptionV3
RESNET50 
Encoder Decoder Architecture
CNN-LSTM Network

BLEU-1 Score: 0.544 BLEU-2 Score: 0.319

# Libraries

tensorflow
keras
numpy
matplotlib
nltk
