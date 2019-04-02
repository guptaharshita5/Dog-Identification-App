# Dog-Identification-App

https://medium.com/@guptaharshita5/write-an-algorithm-for-a-dog-identification-app-ea2f8d689834

# Objective:
The objective of this project is to build a pipeline to process real-world, user-supplied images. In this project there is an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

# Project Overview:
The goal is to classify images of dogs according to their breed. In this project we have developed an algorithm that could be used as part of a mobile or web app. At the end of this project, your code will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling. 

# Approach:
Below are the points of summary of steps and challenges encountered during the project. However ,a more detailed walk-through along with source code is available via the iPython notebooks
•	Data exploration — .ipynb version, .html version
•	Keras+Tensorflow implementation — .ipynb version, .html version
•	PyTorch implementation — .ipynb version, .html version
# PyTorch vs. Keras+Tensorflow
1.	PyTorch dataloader  
o	Makes creation of class labels seamless
o	No need for manual one-hot encoding
	mapping between OHE vector indexes and their associated classes happens automagically
o	Creating a custom series of augmentations is a snap!
2.	PyTorch strikes a good balance between simplicity and flexibility. I can see why many researchers prefer it. PyTorch also feels more like pure Python, whereas Tensorflow has some syntax and conventions that are unique to Tensorflow. "Sessions" anyone? In general, Tensorflow feels more lower level and nailing the syntax can be cumbersome. However, using Keras helps abstract away much of that complexity while still providing adequate customizations.
3.	Tensorflow seems much more efficient and production ready.
o	Support. Tensorflow has a larger and more established support community. That said, I was able to find all of the PyTorch resources I needed; it often just took more digging.
o	Cost. The efficiencies of Tensorflow's static graph computation make much cheaper to run on AWS. Training the Tensorflow model was 1/10 the cost of my PyTorch model.
4.	PyTorch is more flexible
o	The trade-off for Tensorflow's efficiency is less flexibility. For ML exploration and overall modularity, PyTorch's dynamic computational graph provides a lot more flexibility. Tensorflow feels a bit monolithic by comparison.
5.	PyTorch seems much easier to debug.
o	The dynamic computational graph results in cleaner and more specific stack traces. Also, the syntax is simpler.
 


# Steps to develop the project:
	1) Import datasets
	2) Detect humans
	3) Detect Dogs
	4) Create a CNN to Classify Dog Breeds (from Scratch)
	5) Use a CNN to Classify Dog Breeds (using Transfer Learning)
	6) Create a	 CNN to Classify Dog Breeds (using Transfer Learning)
	7) Write your Algorithm
	8) Test Your Algorithm

# Libraries used in the project:
	1) Keras
	2) numpy
	3) sklearn
	4) glob
	5) matplotlib

# Conclusion:
In this project we have applied the deep learning and neural network to predict that a particular image is a breed of the dog .If it is not then it shows the message likewise” Hum... seems this neither dog, nor human; must be something else”. , I have made important design decisions about the user experience for our app. By completing this lab, I understood the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.
