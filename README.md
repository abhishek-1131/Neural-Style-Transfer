# Neural-Style-Transfer

VGG-19 Pre-Trained Model

It is possible to separate the style representation and content representations in a CNN, learnt during a computer vision task. Following this concept, neural style transfer employs a pretrained CNN to transfer styles from a given image to another. This is done by defining a loss function that tries to minimise the differences between a content image, a style image and a generate image.

Working:
•	Loading in a pre-trained VGG Net\
•	Freezing the weights in selected layers, so that the model can be used as a feature extractor\
•	Loading in content and style images\
•	Extracting features from different layers of our model\
•	Calculating the gram matrix\
•	Defining the content, style, and total loss for iteratively updating a target image\

![nst1](https://user-images.githubusercontent.com/47984097/128694170-04d697cd-11cf-48ee-bb4f-f9ac77c81c38.png)

