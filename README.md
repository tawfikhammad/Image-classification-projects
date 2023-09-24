# Image-classification-projects

This repository contains image classification tasks: 

- [x]  [digit recognition classification](https://github.com/tawfikhammad/Image-classification-projects/tree/main/digit-recognizer).
- [x]  [rock-paper-scissors classification](https://github.com/tawfikhammad/Image-classification-projects/tree/main/rock%20paper%20scissors).
- [x]  [Intel image classification](https://github.com/tawfikhammad/Image-classification-projects/tree/main/Intel%20images%20classification)


The models are implemented using deep learning techniques and are trained on suitable datasets to achieve high accuracy.

---

## Introduction

The purpose of this repository is to provide pre-trained models and code for image classification tasks, specifically digit recognition and rock-paper-scissors classification. These models can be used for various applications, such as automatic digit recognition in handwritten documents or playing rock-paper-scissors with a computer.

---

## Installation

To use the models and code in this repository, follow these steps:

1. Clone the repository to your local machine:

   ````bash
   git clone https://github.com/your-username/Image-classification-projects.git


2. Install the required dependencies. Assuming you have Python and pip installed, run the following command:

   ````bash
   pip install -r requirements.txt


3. Setup the environment by downloading the necessary datasets and pre-trained models:

   ````bash
   python setup.py


   This command will download the required datasets and pre-trained models into the appropriate directories.

----

## Models

This repository currently provides the following models:

1. **Digit Recognizer**: This model is trained to recognize and classify handwritten digits from 0 to 9.

2. **Rock-Paper-Scissors Classifier**: This model is trained to classify images of human hand gestures representing rock, paper, or scissors.

3. **Intel images classification**: This model is trained to classify images of Natural Scenes around the world distributed under 6 categories.

---

## Dataset

The models in this repository were trained on the following datasets:

* **MNIST**: The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits. It is widely used for digit recognition tasks.

* **Rock-Paper-Scissors**: The rock-paper-scissors dataset consists of images of hands displaying rock, paper, or scissors gestures. It contains a total of X images, divided into training and test sets.

* **Intel images**: This is image data of Natural Scenes around the world that contains around 25k images of size 150x150 distributed under 6 categories.


The datasets used for training and evaluation are available for download from the following sources:

- MNIST: [https://www.kaggle.com/competitions/digit-recognizer/data](https://www.kaggle.com/competitions/digit-recognizer/data)
- Rock-Paper-Scissors: [https://www.kaggle.com/datasets/frtgnn/rock-paper-scissor](https://www.kaggle.com/datasets/frtgnn/rock-paper-scissor)
- Intel image classification: [https://www.kaggle.com/datasets/puneet6060/intel-image-classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)

---

## Results

The accuracy and performance of the models are as follows:

1. **Digit Recognizer**: Achieves an accuracy above `99.38%` on the MNIST test dataset.

2. **Rock-Paper-Scissors Classifier**: Achieves an accuracy of `98.3%` on the rock-paper-scissors test dataset.

3. **Intel images classification**: Achieves an accuracy of `91.3%` on the test dataset.

## License

The code and models in this repository are available under the [MIT License](./LICENSE). Feel free to use them for academic, research, or commercial purposes.
