# Handling-Complex-Images---Happy-or-Sad-Dataset


This project involves building a Convolutional Neural Network (CNN) to classify emoji-like faces as either "Happy" or "Sad" with 99.9% accuracy. The dataset contains 80 images, evenly split between happy and sad faces. The project stops training once the accuracy threshold is met.

Table of Contents
Project Overview
Dataset
Model Architecture
Installation
Usage
Results
License

Project Overview
This assignment is part of a machine learning course and demonstrates the use of a CNN to classify images into two categories: Happy or Sad. The model will:

Load the images from the data/ folder.
Train a CNN to classify the images.
Stop training when the model reaches 99.9% accuracy.
Dataset
The dataset consists of 80 images in two categories:

Happy: 40 images located in data/happy/.
Sad: 40 images located in data/sad/.
Dataset Structure
kotlin
Copy code
.
└── data/
    ├── happy/
    │   ├── happy_image_1.png
    │   ├── happy_image_2.png
    │   └── ...
    └── sad/
        ├── sad_image_1.png
        ├── sad_image_2.png
        └── ...
Model Architecture
The model uses a Convolutional Neural Network (CNN) with the following architecture:

Convolutional layer(s)
MaxPooling layer(s)
Dense layer(s)
Output layer with a softmax activation function.
The model is trained using the Adam optimizer and categorical cross-entropy loss function.

Installation:

Prerequisites
Python 3.x
Jupyter Notebook
Libraries:
TensorFlow
NumPy
Matplotlib
Steps

Clone this repository:

git clone https://github.com/deaminaa/Handling-Complex-Images---Happy-or-Sad-Dataset.git
cd your_repo_name
Install the required Python packages:


pip install -r requirements.txt
(Note: If requirements.txt is missing, install the following manually)


pip install tensorflow numpy matplotlib
Place the dataset in the data/ directory, structured as mentioned in the Dataset section.

Usage
To train the model, open the Jupyter notebook (C1W4_Assignment.ipynb) and run all cells in order.


jupyter notebook C1W4_Assignment.ipynb
Training
The CNN will automatically stop training when it reaches an accuracy of 99.9%.
Evaluation
The notebook includes sections to evaluate the trained model on the dataset.
Results
Once the model reaches the accuracy threshold, the training will stop, and you will see the final accuracy and loss on the dataset.

License
This project is licensed under the MIT License - see the LICENSE file for details.
