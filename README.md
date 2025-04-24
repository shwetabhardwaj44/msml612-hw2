# MSML 612- HW2

## :sparkles: Homework 2: CNNs for Image Classification

We usually use a classic CNN as a feature extractor, since the classic CNN with the parameters pre-trained under ImageNet is available publicly. Given a user provided image, we can extract a feature from some layer in the classic CNN, and then, leverage the feature in different down stream applications.

![A sample Framework](framework.png)

## :scroll:  In this homework, you need to:

1. Choose a dataset (FashionMNISTLinks to an external site. or CIFAR-10Links to an external site.) and choose a classic CNN (VGG, Alex, ResNet…).

2. Choose a feature and extract this feature from each image in the dataset. You need to decide which feature (one or multiple channel in a conv layer, or the neurons in a FC layer, etc.)

3. Visualize the extracted features from all images using TSNE.

4. Quantify the intra-class and inter-class variances of your chosen feature.

5. Report the above in your write-up. Describe what issues you faced and how you resolved them too.

**Note:

Images in FashionMNIST have only one channel, you can repeat the one channel into a 3-channel image.
You may need to resize the input images.

## :briefcase: Rubrics of Weightage:

1. Explain choice of CNN, dataset, and feature : 20%

2. Working CNN code : 15%

3. Visualization of the features : 25%

4. Quantify intra- and inter-class variance : 25% 

5. Quality of write-up (clarity, details, etc.) : 15%



