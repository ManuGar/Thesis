# Democratizing Deep Learning methods by means of AutoML tools

## UFOD: A Unified Framework for Object Detection

Object detection models based on deep learning techniques have been successfully applied in several contexts; however, non-expert users might find challenging the use of these techniques due to several reasons, including the necessity of trying different algorithms implemented in heterogeneous libraries, the configuration of hyperparameters, the lack of support of many state-of-the-art algorithms for training them on custom datasets, or the variety of metrics employed to evaluate detection algorithms. These challenges have been tackled by the development of UFOD, an automated machine learning framework that trains several object detection algorithms (using different underlying frameworks and libraries), compares them, and finally selects the best model or ensembles them. Currently, the most well-known object detection algorithms have been included in our system, and new methods can be easily incorporated thanks to a high-level API.

[Webpage](https://github.com/ManuGar/UFOD)

## FrImCla
Deep learning techniques are currently the state of the art approach to deal with image classification problems. Nevertheless, non-expert users might find challenging the use of these techniques due to several reasons, including the lack of enough images, the necessity of trying different models and conducting a thorough comparison of the results obtained with them, and the technical difficulties of employing different libraries, tools and special purpose hardware like GPUs. In this work, we present FrImCla, an open-source and free tool that simplifies the construction of robust models for image classification from a dataset of images, and only using the computer CPU. Given a dataset of annotated images, FrImCla automatically constructs a classification model {(both for single-label and multi-label classification problems)} by trying several feature extractors (based both on transfer learning and traditional computer vision methods) and machine learning algorithms, and selecting the best combination after a thorough statistical analysis. Thus, this tool can be employed by non-expert users to create accurate models from small datasets of images without requiring any special purpose hardware. In addition, in this paper, we show that FrImCla can be employed to construct accurate models that are close, or even better, to the state-of-the-art models.

[Webpage](https://github.com/ManuGar/FrImCla)

## CLoDSA

Background: Deep learning techniques have been successfully applied to bioimaging problems; however, these methods are highly data demanding. An approach to deal with the lack of data and avoid overfitting is the application of data augmentation, a technique that generates new training samples from the original dataset by applying different kinds of transformations. Several tools exist to apply data augmentation in the context of image classification, but it does not exist a similar tool for the problems of localization, detection, semantic segmentation or instance segmentation that works not only with 2 dimensional images but also with multi-dimensional images (such as stacks or videos). 

Results: In this paper, we present a generic strategy that can be applied to automatically augment a dataset of images, or multi-dimensional images, devoted to classification, localization, detection, semantic segmentation or instance segmentation. The augmentation method presented in this paper has been implemented in the open-source package CLoDSA. To prove the benefits of using CLoDSA, we have employed this library to improve the accuracy of models for Malaria parasite classification, stomata detection, and automatic segmentation of neural structures. 

Conclusions: CLoDSA is the first, at least up to the best of our knowledge, image augmentation library for object classification, localization, detection, semantic segmentation, and instance segmentation that works not only with 2 dimensional images but also with multi-dimensional images.

[Webpage](https://github.com/ManuGar/CLoDSA)

## MotilityJ
Background and objectives. Infectious diseases produced by antimicrobial resistant microorganisms are a major threat to human, and animal health worldwide. This problem is increased by the virulence and spread of these bacteria. Surface motility has been regarded as a pathogenicity element because it is essential for many biological functions, but also for disease spreading; hence, investigations on the motility behaviour of bacteria are crucial to understand chemotaxis, biofilm formation and virulence in general. To identify a motile strain in the laboratory, the bacterial spread area is observed on media solidified with agar. Up to now, the task of measuring bacteria spread was a manual, and, therefore, tedious and time-consuming task. The aim of this work is the development of a set of tools for bacteria segmentation in motility images. 

Methods. In this work, we address the problem of measuring bacteria spread on motility images by creating an automatic pipeline based on deep learning models. Such a pipeline consists of a classification model to determine whether the bacteria has spread to cover completely the Petri dish, and a segmentation model to determine the spread of those bacteria that do not fully cover the Petri dishes. In order to annotate enough images to train our deep learning models, a semi-automatic annotation procedure is presented. 

Results. The classification model of our pipeline achieved a F1-score of 99.85\%, and the segmentation model achieved a Dice coefficient of 95.66\%. In addition, the segmentation model produces results that are indistinguishable, and in many cases preferred, from those produced manually by experts. Finally, we facilitate the dissemination of our pipeline with the development of MotilityJ, an open-source and user-friendly application for measuring bacteria spread on motility images. 

Conclusions. In this work, we have developed an algorithm and trained several models for measuring bacteria spread on motility images. Thanks to this work, the analysis of motility images will be faster and more reliable. The developed tools will help to advance our understanding of the behaviour and virulence of bacteria.

[Webpage](https://github.com/joheras/MotilityJ)

## Epiretinal Membrane Detection

An epiretinal membrane (ERM) is an eye disease that can lead to visual distortion and, in some cases, to loss of vision. Screening retinal fundus images allows ophthalmologists to early detect and diagnose this disease; however, the manual interpretation of images is a time-consuming task. In spite of the existence of several computer vision tools for analysing retinal fundus images, they are mainly focused on the diagnosis of diabetic retinopathy and glaucoma. In this work, we have conducted a thorough study of several deep learning architectures, and a variety of techniques to train them, in order to build a model for automatically diagnosing ERM. As a result, we have built several models that can be ensembled to achieve a F1-score of 86.82%. The lessons learned in this work can serve as a basis for the construction of deep learning models for diagnosing other eye diseases.

[Webpage](https://github.com/CoVUR/ERM)

## Neural Style Transfer and Unpaired Image-to-Image Translation
Background and objectives. Domain shift is a generalisation problem of machine learning models that occurs when the data distribution of the training set is different to the data distribution encountered by the model when it is deployed. This is common in the context of biomedical image segmentation due to the variance of experimental conditions, equipment, and capturing settings. In this work, we address this challenge by studying both neural style transfer algorithms and unpaired image-to-image translation methods in the context of the segmentation of tumour spheroids.

Methods. We have illustrated the domain shift problem in the context of spheroid segmentation with 4 deep learning segmentation models that achieved an IoU over 97% when tested with images following the training distribution, but whose performance decreased up to an 84\% when applied to images captured under different conditions. In order to deal with this problem, we have explored 3 style transfer algorithms (NST, deep image analogy, and STROTSS), and 6 unpaired image-to-image translations algorithms (CycleGAN, DualGAN, ForkGAN, GANILLA, CUT, and FastCUT). These algorithms have been integrated into a high-level API that facilitates their application to other contexts where the domain-shift problem occurs.

Results. We have considerably improved the performance of the 4 segmentation models when applied to images captured under different conditions by using both style transfer and image-to-image translation algorithms. In particular, there are 2 style transfer algorithms (NST and deep image analogy) and 1 unpaired image-to-image translations algorithm (CycleGAN) that improve the IoU of the models in a range from 0.24 to 76.07. Therefore, reaching a similar performance to the one obtained with the models are applied to images following the training distribution.

[Webpage](https://github.com/ManuGar/ImageStyleTransfer)
