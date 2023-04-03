# Object Detection using YOLO algorithm 
YOLO is the part of Darknet project which is used for making real time object detection system.
For more info in Darknet and YOLO visit [link](https://pjreddie.com/darknet/)

## Installation
1. Clone the repo using `git clone https://github.com/ayushk-singh/Object-Detection/ `

2. Install the weight and config file from [YOLO Website](https://pjreddie.com/darknet/yolo/)

3. Add weight and config file name to weight_name and config_name variable

## Using Video as input source
- add video path in `cv2.VideoCapture()`

## Using Webcam as input source 
- To use webcam as input source replace `cv2.VideoCapture('test.mp4')` to `cv2.VideoCapture()`




