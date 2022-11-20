# **机器学习课程设计**

## 项目简介

###  项目名称

初始项目:  基于CNN完成minst数据集手写识别任务

拓展项目:  ResNet18和Resnet50完成CIFAR-10分类任务

### 项目环境

项目编译环境是ModelArts的 notebook，采用的框架是华为的mindspore框架和pytroch

采用的模型是卷积神经网络的经典模型Lenet-5,Resnet-18,和Resnet-50

### 项目拓展
拓展项目框架是pytorch，模型是Resnet-18和Resnet-50

## 项目结构

### 树型结构图

![](C:\Users\24557\Desktop\11.png)

### 结构说明

Lenet-5Model.ipynb是源代码文件

model.ckpt是训练评估后的模型

MNIST_Data是项目的数据集，

enet5和lenet5_2是训练过程中callback保存的模型

img10是外部的图片数据集用于验证模型

#### Resnet18ForCIFAR-10为拓展项目目录

data文件夹为数据集目录

renet.ckpt为训练完保存的模型

Resnet18ForCIFAR-10.ipynb为 源代码(jupyter)

#### Resnet50ForCIFAR-10为拓展项目目录

data文件夹为数据集目录

resnet.onnx为训练完保存的模型

Resnet50ForCIFAR-10.ipynb为 源代码(jupyter)


