# Reidentification_using_yolo_v5/V4_and_deepshort

# Person re-identification(re-id):

It aims at matching people across non-overlapping camera views distributed at distinct location.

# Person-Detection

The real-time detection of humans is emerging as a significant trend, to successfully detecting a person in an image or video means you are building an application that will do object detection and image classification.Yolo v5 is a object detection framework which is implemented in pytorch. It lets you detect objects in image data is a little different than the popular visual classification tools currently being used across many industries.

# The How and What of Human Detection

What can you accomplish applying object detection tools to your images and video? Computer vision person detection accomplishes three distinct tasks:

1.Picks objects out of background images, 2.Proposes the objects as belonging to a certain class — humans, in this case — using a probability score, 3.Defines the boundaries of the proposed people with x-y origins and height and length values.

# Yolo v5

CNN-based Object Detectors are primarily applicable for recommendation systems. YOLO (You Only Look Once) models are used for Object detection with high performance. YOLO divides an image into a grid system, and each grid detects objects within itself. They can be used for real-time object detection based on the data streams. They require very few computational resources.

# Deep Short multi-target tracking algorithm

The predecessor of Deep SORT algorithm is SORT, the full name is Simple Online and Realtime Tracking. To briefly introduce, the biggest feature of SORT is the target detection method based on Faster R-CNN, and the use of Kalman filter algorithm + Hungarian algorithm, which greatly improves the speed of multi-target tracking, while achieving the accuracy of SOTA.

# Requirements

Operating System: Linux or macOS, Python: 3.6+, Pytorch: 1.5+ & torchvison that matches the Pytorch installation. You can install both together at pytorch.org, OpenCV for Visualization.
