# Automatic Speech Recognizer(ASR) using Deep Neural Network(DNN)

## Introduction
This project is a simple Automatic Speech Recognizer(ASR) using Deep Neural Network(DNN). The project is implemented in Python using the Keras library. The project uses the following steps:

1. LibriSpeech dataset for training and testing the model. 
2. MFCC features of the audio files for training the model. 
3. The final model architecture combines two models which had a lower validation loss.
    The model structure allows for capturing temporal dependencies in both directions (forward and backward) using multiple layers of bidirectional GRUs and integrates regularization techniques (batch normalization, dropout) to enhance generalization. The model also makes use of residual connections which will help with gradient flow during training, making the network easier to train.
4. TCTC loss function for training the model.

