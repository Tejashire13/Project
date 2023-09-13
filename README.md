# Project:
This report evaluates the performance of image classification kernels using
Convolutional Neural Networks (CNNs) accelerated by CUDA-enabled NVIDIA
GPU Libraries, specifically cuDNN. The study measures the impact of GPU
acceleration on both training time and accuracy. The results highlight the
advantages of using GPUs for image classification tasks and provide insights into
the relationship between training time and model accuracy. CNNs are important
deep learning (DL) models that have achieved great successes in large scale image
classifications. This can be attributed to the advanced architecture of CNNs large
labelled training samples and powerful computing devices such as GPUs. CNNs
are getting more complicated due to increased depth and parameters, such as
number of convolutional layers, fully-connected layers and few million parameters.
Also, training these large-scale CNNs requires thousands of iterations of forward
and backward propagations, and therefore is much time-consuming. In this project
we use GPU-optimized libraries such as cuDNN on CUDA enabled NVIDIA
GPUs, which are explored to accelerate CNNs performance for application data
sets. Our goal is to explore the reasons behind performance differences between
those implementations on data sets as well as accelerate “training CNNs on large
data sets” using Multi-Core Systems with multiple GPUs.
