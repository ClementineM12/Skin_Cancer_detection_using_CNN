# Skin_Cancer_detection_using_CNN
In this project, the aim is to classify dermoscopic images into two classes: "Malignant" and "Benign". 
Two approaches were employeed to achieve this goal. 
In the first approach, a set of features and descriptors is being calculated for each segmented binary image, 
including border pixel count, non-zero pixel count, circularity, degree of asymmetry, and color histogram. 
These features are used to train a classifier to categorize images into the two classes.
In the second approach, a pre-trained convolutional neural network (CNN) is being utilized to classify dermoscopic images. 
The CNN is trained on a set of images and evaluated on a different set of images. 
A balanced dataset was created to use in the models with turns of 2000, 4000 and 8000 samples to compare the results.
Overall, the pre-trained CNN achieved an accuracy of 65% with 400 images, while the classifier in order to achieve 
this result had to be trained with characteristicts given by 2000 images.
This indicates that the pre-trained CNN may be a more efficient approach, as it requires a 
smaller dataset and achieves comparable performance.
