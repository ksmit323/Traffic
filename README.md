# Traffic Sign Recognition using Supervised Learning
This repository contains a Python program that uses supervised learning to identify traffic signs in a photograph. The program takes a photograph as input and applies a convolutional neural network to identify traffic signs in the image.

## Installation
To use the program, you will need to have Python 3.x installed on your computer. You can clone this repository and navigate to the project directory in your terminal or command prompt.

Install the dependencies by running the following command:
```
pip3 install -r requirements.txt
```

## Dataset
The program was trained using the [German Traffic Sign Recognition Benchmark (GTSRB)](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news) dataset, which contains thousands of images of traffic signs. The dataset was preprocessed and augmented to increase the size and diversity of the training set.

Install the GTSRB dataset to be analyzed [here](https://cdn.cs50.net/ai/2020/x/projects/5/gtsrb.zip).
Now, unzip the file. 


## Usage
To use the program, run the **'traffic.py'** and provide a a path to the dataset you want to analyze as a command-line argument.
```
python3 traffic.py gtsrb
```

## Training
The model was trained using a convolutional neural network (CNN) with multiple layers. The CNN was trained using a supervised learning approach, where the correct output (i.e., the type of traffic sign) was provided for each training image. The training process used the Adam optimizer and a categorical cross-entropy loss function.

## Evaluation
The trained model was evaluated using a test set of images from the GTSRB dataset. The accuracy of the model on the test set was 98%.
