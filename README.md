# skin-lesions-classifier
Skin Lesions Classification using Computer Vision and Convolutional Neural Networks

## Project description
Today, skin cancer is a public health and economic issue, in fact several researches state that skin diseases are one of the most common human illnesses, affecting every age, gender and pervading many cultures, summing up to between 30% and 70% of people in the United States. The recommended way to detect early skin diseases is to be aware of new or changing skin growths. One of the most adopted techniques for skin lesion analysis is the so-called ABCD analysis, that consists of scanning the skin area of interest for asymmetry (A), border irregularity (B), colors variegation (C), diameter (D).
The emergence of powerful machine learning techniques such as deep learning has enabled the development of intelligent medical image analysis systems that, through the use of Artificial and Convolutional Neural Networks, have been proved to have remarkable performance in comparison to standard methods.
Given this background, this project will guide its efforts in applying deep learning and some image processing techniques to images of the HAM10000 dataset in order to develop an advanced skin lesion classification system: after applying some preprocessing techniques to enhance contrast and remove hairs, images are processed using two distinct pipelines. The first one uses the AlexNet convolutional neural network (CNN) for image classification, while in the second one we firstly find the region representing the lesion using the marker-based watershed segmentation algorithm, and then we perform feature extraction based on the ABCDT analysis, an extension of the classical ABCD analysis, so that the extracted features can be used for image classification using the SVM machine learning model.
