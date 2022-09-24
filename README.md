# yolov3-on-coustom-data
Here i have taken the darknet framework and trained on human head data for detecting humans head i have taken only one output class.
YOLOv3 has been trained already on the coco dataset which has 80 classes that it can predict. we grabed these pretrained weights so that we can run YOLOv3 on these pretrained classes and then we prepare our own custom dataset and trained model on custom dataset.
In order to create a custom YOLOv3 detector we will need the following:

*   Labeled Custom Dataset
*   Custom .cfg file
*   obj.data and obj.names files
*   train.txt file 

In order to create a custom object detector you need a good dataset of images and labels so that the detector can be efficiently trained to detect objects.

