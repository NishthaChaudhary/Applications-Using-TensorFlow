# VideoGame-Sales-Prediction-System-Using-TensorFlow
TensorFlow is one of the most popular deep learning frameworks available. In this project, I have built some deep learning programs that uses TensorFlow as a framework.

After the TensorFlow is up and running, this project demonstrates how to create and train a machine learning model, as well as how to leverage visualization tools to analyze and improve the model.

Finally the project is deployed locally and in cloud.

## Objectives:
* What's TensorFlow?
* Hardware, software, and language requirements
* Creating a TensorFlow model
* Training a deep learning model with TensorFlow
* Visualizing the computational graph
* Adding custom visualizations to TensorBoard
* Exporting models for use with Google Cloud


## Tensorflow:

This is a software framework for building and deploying machine learning model. Specifically made to deal woth neural network models, such as:
1. Image recognition.
2. Speech Recogition
3. Image style Transfer
4. Language translation

TF is a low level tool kit. A high level Tensorflow wrapper for building NN with only few lines of codes is used--KERAS. 

Any data that you want to process with the TF has to be stored in a multi dimensional array (also called tensors).TF determines how these tensors flow through the system. 

## TesnsorFlow Requirements:

* Developmnet phase- when you are coding and training a NN
* Runtime (or inference) phase- when you are making predictions using the trained NN.

## Business Question

Estimate the sales of a new video game based on the similar features and historical results of past video games using the basic neural network.
Idea: Build and deploy a supervised deep learning model. Model will learn how to perform functions by looking at the labeled training data.

![image](https://user-images.githubusercontent.com/54689111/82715717-6b59d980-9c62-11ea-84e8-2932e77e9018.png)

Note: Create a TF Session object that runs operations on the graph and tracks the state of each node in the graph. Once it is created, we can ask it to run any opeation in the graph. To train the model- we run the training operation over and over, each time the training operations run, we'll pass a new training data that will be used for that training pass. Then check the current accuracy by calculating the loss function. Based on the loss function value, weight will be adjusted for each layer by back-propogation untill we get the expected output. While the training process is running, we can watch the accuracy graphically on a separate tool- Tensorboard (web based application that lets us visually monitor the system in real time)
