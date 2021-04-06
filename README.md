# Detectron2 Object Detection

Training custom model using detectron2 takes some amount of tweaking.

* register custom dataset and metadata.
* add augmentations.
* add code to evaluate your model.
* create hooks to print validation loss and save best model. 

This notebook does all of this, thus provides a good starting point for your project.

The notebook uses [Wgisd](https://github.com/thsant/wgisd) dataset of grapes and retinanet as baseline model.

![Detection](grape_detection.png)
