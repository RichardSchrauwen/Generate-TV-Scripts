# Generate-TV-Scripts
This repository contains one of my Deep Learning RNN projects.

In this Pytorch project a number of seasons of Seinfeld tv scripts is used as input to a Recurrent Neural Network (RNN).
After training the RNN it can generate completely new dialogues, many cases not making much sense. I liked the original Seinfeld episoses more.

Steps involved:
1. Prepare input
2. Helper functions for preprocessing and batching
3. Define the RNN:
   - Embedding layer
   - Long Short Term Memory (LSTM) layer
   - Fully connected Linear layer
   - Sigmoid activation function
