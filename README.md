# Traffic Sign Classifier

## Before you run the code

### Background

As research continues in the development of self-driving cars, one of the key challenges is computer vision, allowing these cars to develop an understanding of their environment from digital images. In particular, this involves the ability to recognize and distinguish road signs—stop signs, speed limit signs, yield signs, and more.

In this project, you’ll use TensorFlow to build a neural network to classify road signs based on an image of those signs. To do so, you’ll need a labeled dataset: a collection of images that have already been categorized by the road sign represented in them.

Several such datasets exist, but for this project, we’ll use the German Traffic Sign Recognition Benchmark (GTSRB) dataset, which contains thousands of images of 43 different kinds of road signs.

### Getting started

1. [Download the GTSRB dataset](https://cdn.cs50.net/ai/2023/x/projects/5/gtsrb.zip) and unzip it.
2. Move the resulting `gtsrb` directory into this project’s `traffic` directory.
3. From inside the `traffic` directory, install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

The dependencies include OpenCV (`opencv-python`) for image processing, scikit-learn for machine-learning functions, and TensorFlow for neural networks.
