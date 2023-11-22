# Weed-Classification

#Introduction

Image processing employs mathematical approaches and procedures to improve, analyse, or alter digital
images. Enhancement, restoration, segmentation, compression, and recognition are all components of image
processing (Jain, 1988). Brightness, contrast, and colour harmony are used to enhance photographs.
Restoring an image eliminates noise and restores clarity and detail. Image segmentation breaks an image
into parts in order to identify and extract objects of interest. Encoding photos using fewer bits reduces their
file size without diminishing their quality. Image recognition is the training of algorithms to identify certain
objects, patterns, or attributes in an image, enabling visual data analysis and decision-making. Image
processing is used in medical imaging, astronomy, robotics, and surveillance. Image processing is required
for digital photography, video production, and computer graphics (Bovik, 2009).

#Purpose

An examination of the classification capabilities of image processing is the focus of this paper. This report's
aims are to do pre-processing on picture data, extract image features, create image classifiers, and assess
the models.

#Scope

The report focus on pre-processing on all of the images, which includes scaling the images to 256 by 256
and extracting features based on the average rgb value from each image (train, val, test). The features from
the train dataset will be used for training the model, the features from the validation dataset will be used to
tune the hyperparameter, and the features from the test dataset will be fed to the trained model so that it can
make a prediction about the class that this image belongs to. Finally, the performance of the model will only
be evaluated on the test dataset. The results that were acquired from the classifiers and models will be
presented and analysed, suggestions will be made for the best models and classifiers based on the analysis,
and recommendations will be offered on how to increase the efficiency of the classifiers and models. In this
paper, the author made use of a variety of classifiers, including linear and non-linear ones, such as the
Support vector machine, Random forest, Logistic regression, K-Nearest neighbour, and Convolutional Neural
Network.


#Background Information

The author has been provided with a folder that is titled data weed classification examine classification
capabilities. The folder includes a Val set, a Test set, and a Train set; for further information, see table 1.
Table 1: Illustrate the information in the train, test, and val set of the data weed classification.
DataSet      Cleavers    Charlock    Total
Train          208         272        480
Val            90          58         148
Test           90          68         158


#Objectives

Create image classifiers as well as an access model by using Python to create a process for the processing
of image data. This pipeline include:
• Pre-processing, feature extraction, train classifiers with extracted features and labels from train, test,
and val set.
• Evaluate models with extracted features from test and val set with Visualisation.
• Discuss and analyse result.
• Present recommendations
