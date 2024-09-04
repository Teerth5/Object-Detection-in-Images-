# Object-Detection-in-Images-

I have Implemented Object Detection using 2 Techniques 

1st Technique : Using Yolo v9 for object detecion on Custom dataset

YOLOv9 is very new. At the moment, we recommend using a fork of the main repository. The detect.py script contains a bug that prevents inference. This bug is patched in the fork.
Installing the roboflow package, which I will use to download our dataset from Roboflow Universe.
In the YOLOv9 paper, versions yolov9-s and yolov9-m are also mentioned, but the weights for these models are not yet available in the YOLOv9 repository.



2nd Technique : Using Tensorflow models mobilenet_v2 

About mobileNET_v2 : SSD-based object detection model trained on Open Images V4 with ImageNet pre-trained MobileNet V2 as image feature extractor.

Overview
SSD+MobileNetV2 network trained on Open Images V4.
Detections are outputted for 600 boxable categories.
Note: A slower but higher quality object detection module is available at https://kaggle.com/models/google/faster-rcnn-inception-resnet-v2/frameworks/TensorFlow1/variations/faster-rcnn-openimages-v4-inception-resnet-v2/versions/1.
