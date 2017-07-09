## Faced-Detection

## Introduction
Our System will detect the faces from the pictures present in our trained data, Our system uses Feature based approch for face detection. Face detection can be characterized into two parts such as, feature based and holistic approaches techniques. The most commonly used technique in face detection was feature based which was used to characterize a low-dimensional face representation in order to identify proportions of separations, zones, and various angles. The face representation used by this technique is pretty much attractive but this technique does not provide accurate results.

## Procedure

First we have to get multiple images of multiple person for the training of our system. From that images our system detects the faces and start processing. Once the face is detected, it is preprocessed the faces present in the images and create normalized and fixed-point input for Convolutional neural network. Now neural network plays its role of feature extractor.

## Algorithm

Convolutional neural network is used in this system. Its role of feature extractor here and creates low-dimensional representation of the face.

## Dataset

we get dataset from online source in which we have multiple pictures of multiple celeberaties and also we use are own pictures. approx there are 2500 pictures and we also add our own pictures
Installation/ Working Process

    Conda Installation
    Python Installation
        Intall Required packages
        Download Python 2.7.13
        Extract
        Compile Python Source
    Check Python Version
    Dlib
    Install dlib prerequisites
