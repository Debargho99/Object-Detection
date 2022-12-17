<h1 align="center">
  Object Detection and Tracking
</h1>

<div align="center">
  <img src="https://github.com/yehengchen/ObjectDetection/blob/master/img/objectdetection.gif" width="60%" height="60%">
</div>

*Object detection is a computer technology related to computer vision and image processing that deals with detecting instances of semantic objects of a certain class (such as humans, buildings, or cars) in digital images and videos.*

***

## Environment

I have tested on Ubuntu 16.04/18.04. The code may work on other systems.

[[Ubuntu-Deep-Learning-Environment-Setup]](https://github.com/yehengchen/Ubuntu-Deep-Learning-Environment-Setup)

* ##### Ubuntu 16.04 / 18.04 
* ##### ROS Kinetic / Melodic
* ##### GTX 1080Ti / RTX 2080Ti
* ##### python 2.7 / 3.6


## Installation

Clone the repository

```
git clone https://github.com/yehengchen/Object-Detection-and-Tracking.git
```

***
## [OneStage]
### [YOLO-SORT](https://github.com/yehengchen/ObjectDetection/blob/master/OneStage/yolo): Real-Time Object Detection and Tracking

* __How to train a YOLO model on custom images: YOLOv3 - [[Here]](https://github.com/yehengchen/ObjectDetection/tree/master/OneStage/yolo/yolov3) / YOLOv4 - [[Here]](https://github.com/yehengchen/Object-Detection-and-Tracking/tree/master/OneStage/yolo/Train-a-YOLOv4-model)__




***
<img src="https://github.com/yehengchen/video_demo/blob/master/video_demo/output_49.gif" width="60%" height="60%">

* #### YOLOv4 + Deep_SORT - Pedestrian Counting & Social Distance - [[Here]](https://github.com/yehengchen/Object-Detection-and-Tracking/tree/master/OneStage/yolo/deep_sort_yolov4)
* #### YOLOv3 + Deep_SORT - Pedestrian&Car Counting - [[Here]](https://github.com/yehengchen/ObjectDetection/tree/master/OneStage/yolo/deep_sort_yolov3)

***
<img src="https://github.com/yehengchen/video_demo/blob/master/video_demo/sort_1.gif" width="60%" height="60%">

* #### YOLOv3 + SORT - Pedestrian Counting - [[Here]](https://github.com/yehengchen/ObjectDetection/tree/master/OneStage/yolo/yolov3_sort)
***

### [Darknet_ROS](https://github.com/yehengchen/YOLOv3-ROS/tree/master/darknet_ros): Real-Time Object Detection and Grasp Detection

<img src="https://github.com/yehengchen/YOLOv3-ROS/blob/master/darknet_ros/yolo_network_config/weights/output.gif" width="60%" height="60%">

* #### YOLOv3 + ROS Kinetic - For small Custom Data - [[Here]](https://github.com/yehengchen/YOLOv3_ROS)
***

<img src="https://github.com/yehengchen/YOLOv3-ROS/blob/master/yolov3_pytorch_ros/models/output.gif" width="60%" height="100%">

* #### YOLOv3 + ROS Melodic - Robot Grasp Detection - [[Here]](https://github.com/yehengchen/YOLOv3_ROS/tree/master/yolov3_pytorch_ros)

* #### Parts-Arrangement-Robot - [[Here]](https://github.com/yehengchen/Parts-Arrangement-Robot)
***

<img src="https://github.com/yehengchen/video_demo/blob/master/video_demo/chair_pin.gif" width="60%" height="100%">

* #### YOLOv3 + OpenCV + ROS Melodic - Object Detection (Rotated) - [[Here]](https://github.com/yehengchen/YOLOv3-ROS/tree/master/yolov3_grasp_detection_ros)



