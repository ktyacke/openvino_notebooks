# PaddlePaddle to OpenVINO™ IR Tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/openvinotoolkit/openvino_notebooks/HEAD?filepath=notebooks%2F103-paddle-to-openvino%2F103-paddle-to-openvino-classification.ipynb)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/main/notebooks/103-paddle-to-openvino/103-paddle-to-openvino-classification.ipynb)

In this notebook you will learn how to convert [PaddlePaddle](https://www.paddlepaddle.org.cn) models to OpenVINO IR. The tutorial demonstrates the use of [model conversion API](https://docs.openvino.ai/2023.0/openvino_docs_model_processing_introduction.html) to convert a MobileNet V3 [PaddleClas](https://github.com/PaddlePaddle/PaddleClas) model, pre-trained on the [ImageNet](https://www.image-net.org) dataset, to OpenVINO IR. It also shows how to perform classification inference on an image, using [OpenVINO Runtime](https://docs.openvino.ai/nightly/openvino_docs_OV_UG_OV_Runtime_User_Guide.html) and compares the results of the PaddlePaddle model with the OpenVINO IR model. 

Additional detail on why or when you may want to use this model or specific capability...

![PaddlePaddle Classification](https://user-images.githubusercontent.com/77325899/127503530-72c8ce57-ef6f-40a7-808a-d7bdef909d11.png)



## Notebook Contents
1. Preparation
    - Imports
    - Settings
2. Show Inference on PaddlePaddle Model
3. Convert the Model to OpenVINO IR Format
4. Select inference device
5. Show Inference on the OpenVINO Model
6. Timing and Comparison
7. Select inference device
8. References


## Installation Instructions
If you have not yet configured your OpenVino environment, please follow the instructions located in the [Installation Guide](../../README.md), otherwise proceed to the notebook.

## Additional resources
* White paper
* Blog post(s)
* Video(s)
* Additional docs

## What to try next
* [Introduction to Performance Tricks](https://github.com/openvinotoolkit/openvino_notebooks/tree/main/notebooks/109-performance-tricks)
* [Optimize Preprocessing](https://github.com/openvinotoolkit/openvino_notebooks/tree/main/notebooks/118-optimize-preprocessing)
* [Background Removal](https://github.com/openvinotoolkit/openvino_notebooks/tree/main/notebooks/205-vision-background-removal)
* [Defect Detection with Anomalib](https://github.com/openvinotoolkit/openvino_notebooks/tree/recipes/recipes/defect_detection_anomalib)


