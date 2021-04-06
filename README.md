# Detectron2 Object Detection

### The notebook is intended to be used with google colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/breathingcyborg/detectron2_object_detection/blob/main/detectron2_train_custom_object_detection_model.ipynb)

Training custom model using detectron2 takes some amount of tweaking.

* register custom dataset and metadata.
* add augmentations.
* add code to evaluate your model.
* create hooks to print validation loss and save best model. 

This notebook does all of this, thus provides a good starting point for your project.

The notebook uses [Wgisd](https://github.com/thsant/wgisd) dataset of grapes and retinanet as baseline model.

![Detection](grape_detection.png)
