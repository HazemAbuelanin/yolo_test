
human_detect_ever - v4 2024-05-06 6:52pm
==============================

This dataset was exported via roboflow.com on May 6, 2024 at 3:53 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 679 images.
Human are annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Randomly crop between 0 and 33 percent of the image
* Random Gaussian blur of between 0 and 3.1 pixels
* Salt and pepper noise was applied to 4.14 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random Gaussian blur of between 0 and 2 pixels
* Salt and pepper noise was applied to 0.45 percent of pixels


