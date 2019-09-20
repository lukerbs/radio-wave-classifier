# Introduction
This repository contains code as part of my internship at GSI Technology in 2019. This contains:
* Custom ResNet neural network architecture in Keras for Signal Classification
    * Code training a resnet from scratch 
    * Code for loading training data
    * Code for extracting hamming fingerprints from signal embeddings
    * Code for visualizing signal embeddings in t-SNE
* Introduction to Facebook Artificial Intelligce Similarity Search (FAISS)

# Getting Started
* To start training from scratch, go to the notebook here:
* Here is a link to a blog I wrote describing the code: https://medium.com/gsi-technology/residual-neural-networks-in-python-1796a57c2d7

# Extracting and Visualizing Embeddings
* Once you have trained your ResNet go to **faiss_hamming.ipynb** to extract binary fingerprints and run similarity search on the signals.

# References:
This work was inspired by the paper *Over the Air Deep Learning Based Signal Classification* by Tim O'Shea et. al.
