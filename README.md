# Data-Augmentation-Module-in-OpenCV
This repository summarize the current progress and future plans for the GSoC22 project "[Efficient Data Augmentation Module in OpenCV for DL Training](https://summerofcode.withgoogle.com/programs/2022/projects/hmRrB6GQ)"

**Student:** Chuyang Zhao  
**Mentors:** Shiqi Yu, Jia Wu

- Pull Request: https://github.com/opencv/opencv_contrib/pull/3335
- Documentation: Waiting for merge
- Tutorial: Waiting for merge

## Introduction
Data augmentation techniques are widely used in deep learning training to expand the training samples and overcome overfitting problem. imgaug module in OpenCV is implemented in pure C++ and powered with efficient OpenCV image processing operations, so it runs much faster and more efficient than Python-based implementations.

With the binding generator provided by OpenCV, imgaug can be used not only from C++, but also from different languages like Python, Java, etc. Conversely, you can also adopt your code easily from other languages to C++, which is especially useful when you want to deploy a model with its data preprocessing pipeline from Python to production environment in C++.

Computer vision tasks currently supports:

- [x] Classification  
- [x] Object Detection  
- [ ] Keypoint Detection  
- [ ] Semantic Segmentation


## References
[1] [TorchVision: Datasets, Transforms and Models specific to Computer Vision](https://github.com/pytorch/vision) (License BSD)  
[2] [Data Augmentation For Object Detection](https://github.com/Paperspace/DataAugmentationForObjectDetection) (License MIT)
