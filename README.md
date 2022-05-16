# Simplifying the usage and construction of deep image classification models

This repository summarizes all the projects created during the development of the thesis.

## DeepClas4Bio

DeepClas4Bio is a project that aims to facilitate the interoperability of bioimaging tools with deep learning frameworks. In particular, we have developed an extensible API that provides a common access point for classification models of several deep learning frameworks. This project groups the main deep learning frameworks, namely, Keras, Caffe, DeepLearning4J, MxNet and PyTorch.

Using DeepClas4Bio, the users could work with the main deep learning frameworks easily and transparently for their. Even the users can use the pretrained models included in the API for classify an image or they can train their own models and load it in the API to use it in a simple way.

[Webpage](https://github.com/adines/DeepClas4Bio)

## ATLASS

This repository includes the code, application, and notebooks for the work "AutoML using Transfer and Semi-Supervised Learning". The tools presented here can be employed to construct image classification models with small datasets using transfer learning. In addition, we present a new semi-supervised learning procedure for constructing image classification models with partially annotated datasets.

[Webpage](https://github.com/adines/ATLASS)

## Semi-Supervised Learning for Image Classification using Compact Networks in the Medical Context

The development of mobile and on the edge applications that embed deep convolutional neural models has the potential to revolutionise healthcare. However, most deep learning models require computational resources that are not available in smartphones or edge devices; an issue that can be faced by means of compact models that require less resources than standard deep learning models. The problem with such models is that they are, at least usually, less accurate than bigger models. We address the accuracy limitation of compact networks with the application of semi-supervised learning techniques, which take advantage of unlabelled data. In particular, we study the application of self-training methods, consistency regularisation techniques and quantization techniques. In addition, we have developed a Python library in order to facilitate the combination of compact networks and semi-supervised learning methods to tackle image classification tasks. We present a thorough analysis for the results obtained by combining 9 compact networks and 6 semi-supervised processes when applied to 10 biomedical datasets. In particular, we first compare the performance of the networks when training using only labelled data, and, we observe that there are not significant differences between FBNet, MixNet, MNasNet and ResNet18 compact networks and standard size models. Then, we study the impact of applying the different semi-supervised methods, and we can conclude that combining Data Distillation and MixNet, and Plain Distillation and ResNet18 the best results are obtained. Finally, we analyse the efficiency of each network and we can conclude that compact networks outperforms standard size networks.

[Webpage](https://github.com/adines/SemiCompact)


## A Topological Approach for Semi-Supervised Learning

Nowadays, Machine Learning and Deep Learning methods have become the state-of-the-art approach to solve data classification tasks. In order to use those methods, it is necessary to acquire and label a considerable amount of data; however, this is not straightforward in some fields, since data annotation is time consuming and might require expert knowledge. This challenge can be tackled by means of semi-supervised learning methods that take advantage of both labelled and unlabelled data. In this work, we present new semi-supervised learning methods based on techniques from Topological Data Analysis (TDA), a field that is gaining importance for analysing large amounts of data with high variety and dimensionality. In particular, we have created two semi-supervised learning methods following two different topological approaches. In the former, we have used a homological approach that consists in studying the persistence diagrams associated with the data using the Bottleneck and Wasserstein distances. In the latter, we have taken into account the connectivity of the data. In addition, we have carried out a thorough analysis of the developed methods using 3 synthetic datasets, 5 structured datasets, and 2 datasets of images. The results show that the semi-supervised methods developed in this work outperform both the results obtained with models trained with only manually labelled data, and those obtained with classical semi-supervised learning methods, reaching improvements of up to a 16\%.


[Webpage](https://github.com/adines/TTASSL)


## CLoDSA

CLoDSA is an open-source image augmentation library for object classification, localization, detection, semantic segmentation and instance segmentation. It supports a wide variety of augmentation techniques and allows the user to easily combine them. It can also be applied to lists of images like videos or z-stacks.

[Webpage](https://github.com/joheras/CLoDSA)


## MotilityJ

MotilityJ is an application for the segmentation of motility images.

[Webpage](https://github.com/joheras/MotilityJ)

## Epiretinal Membrane Detection
An epiretinal membrane (ERM) is an eye disease that can lead to visual distortion and, in some cases, to loss of vision. Screening retinal fundus images allows ophthalmologists to early detect and diagnose this disease; however, the manual interpretation of images is a time-consuming task. In spite of the existence of several computer vision tools for analysing retinal fundus images, they are mainly focused on the diagnosis of diabetic retinopathy and glaucoma. In this work, we have conducted a thorough study of several deep learning architectures, and a variety of techniques to train them, in order to build a model for automatically diagnosing ERM. As a result, we have built several models that can be ensembled to achieve a F1-score of 86.82%. The lessons learned in this work can serve as a basis for the construction of deep learning models for diagnosing other eye diseases

[Webpage](https://github.com/CoVUR/ERM)


