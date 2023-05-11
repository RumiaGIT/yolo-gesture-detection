# YOLO Gesture Detection

A small project, using a PyTorch-based model known as YOLOv5 to perform object detection for several hand gestures in images.
Said model is trained and tested on a custom dataset.
In addition, opencv is used in tandem with the model to perform live detection as well.

Examples:

![Testing Dataset](https://raw.githubusercontent.com/RumiaGIT/yolo-gesture-detection/master/images/example.png 'Example Predictions')

![Live Detection](https://raw.githubusercontent.com/RumiaGIT/yolo-gesture-detection/master/images/livedetection.gif 'Live Detection')

## Contents
~~~
/data:                         Dataset used during the project.
/images:                       Images and examples used in the Jupyter Notebook and readme.
/yolov5:                       The YOLOv5 model and all its utilities.
README.md:                     You're reading it.
yolo_gesture_detection.ipynb:  Code for the creation, training, testing, and evaluation of a YOLOv5 model.
yolov5s.pt:                    A small YOLOv5 model, downloaded from the PyTorch hub.
~~~
