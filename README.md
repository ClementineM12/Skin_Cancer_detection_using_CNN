# Skin Cancer Detection using CNN

In this project, the aim is to classify dermoscopic images into two classes: "Malignant" and "Benign".

## Approaches

Two approaches were employed to achieve this goal.

### Approach 1: Feature-Based Classification

In the first approach, a set of features and descriptors is calculated for each segmented binary image, including:

- Border pixel count
- Non-zero pixel count
- Circularity
- Degree of asymmetry
- Color histogram

These features are used to train a classifier to categorize images into the two classes.

### Approach 2: Convolutional Neural Network (CNN) Classification

In the second approach, a pre-trained convolutional neural network (CNN) is utilized to classify dermoscopic images. The CNN is trained on a set of images and evaluated on a different set of images.

Overall, the pre-trained CNN achieved an accuracy of 65% with 400 images, while the classifier required specific characteristics of 2000 images to achieve the same result. This indicates that the pre-trained CNN may be a more efficient approach, as it requires a smaller dataset and achieves comparable performance.


