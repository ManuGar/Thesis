# Democratizing Deep Learning methods by means of AutoML tools

## UFOD: A Unified Framework for Object Detection

UFOD is an open-source framework that enables the training and comparison of object detection models on 
custom datasets using different underlying frameworks and libraries. Currently, the most well-known object detection 
frameworks have been included in UFOD, and new tools can be easily incorporated thanks to UFOD's high-level API.

[Webpage](https://github.com/ManuGar/UFOD)

## FrImCla
FrImCla is an open-source framework for Image Classification using traditional and deep learning techniques. It supports a wide variety of deep learning and classical computer vision models. 

[Webpage](https://github.com/ManuGar/FrImCla)

## CLoDSA

CLoDSA is an open-source image augmentation library for object classification, localization, detection and semantic segmentation. It supports a wide variety of augmentation techniques and allows the user to easily combine them. 

[Webpage](https://github.com/ManuGar/CLoDSA)

## MotilityJ
MotilityJ is an application for the segmentation of motility images.

[Webpage](https://github.com/joheras/MotilityJ)

## Epiretinal Membrane Detection

An epiretinal membrane (ERM) is an eye disease that can lead to visual distortion and, in some cases, to loss of vision. Screening retinal fundus images allows ophthalmologists to early detect and diagnose this disease; however, the manual interpretation of images is a time-consuming task. In spite of the existence of several computer vision tools for analysing retinal fundus images, they are mainly focused on the diagnosis of diabetic retinopathy and glaucoma. In this work, we have conducted a thorough study of several deep learning architectures, and a variety of techniques to train them, in order to build a model for automatically diagnosing ERM. As a result, we have built several models that can be ensembled to achieve a F1-score of 86.82%. The lessons learned in this work can serve as a basis for the construction of deep learning models for diagnosing other eye diseases.

[Webpage](https://github.com/CoVUR/ERM)

## Neural Style Transfer and Unpaired Image-to-Image Translation
Background and objectives. Domain shift is a generalisation problem of machine learning models that occurs when the data distribution of the training set is different to the data distribution encountered by the model when it is deployed. This is common in the context of biomedical image segmentation due to the variance of experimental conditions, equipment, and capturing settings. In this work, we address this challenge by studying both neural style transfer algorithms and unpaired image-to-image translation methods in the context of the segmentation of tumour spheroids.
Methods. We have illustrated the domain shift problem in the context of spheroid segmentation with 4 deep learning segmentation models that achieved an IoU over 97% when tested with images following the training distribution, but whose performance decreased up to an 84\% when applied to images captured under different conditions. In order to deal with this problem, we have explored 3 style transfer algorithms (NST, deep image analogy, and STROTSS), and 6 unpaired image-to-image translations algorithms (CycleGAN, DualGAN, ForkGAN, GANILLA, CUT, and FastCUT). These algorithms have been integrated into a high-level API that facilitates their application to other contexts where the domain-shift problem occurs.
Results. We have considerably improved the performance of the 4 segmentation models when applied to images captured under different conditions by using both style transfer and image-to-image translation algorithms. In particular, there are 2 style transfer algorithms (NST and deep image analogy) and 1 unpaired image-to-image translations algorithm (CycleGAN) that improve the IoU of the models in a range from 0.24 to 76.07. Therefore, reaching a similar performance to the one obtained with the models are applied to images following the training distribution.

[Webpage](https://github.com/ManuGar/ImageStyleTransfer)
