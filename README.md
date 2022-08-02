# Real-Time-Object-Detection
Python implementation of YoloV2 algorithm for Real Time Object Detection

## YOLO object detection: the YOLO algorithm:
To understand the YOLO algorithm, it is necessary to establish what is actually being predicted. Ultimately, we aim to predict a class of an object and the bounding box specifying object location. Each bounding box can be described using four descriptors:<br />

1. center of a bounding box (bxby)<br />
2. width (bw)<br />
3. height (bh)<br />
4. value cis corresponding to a class of an object (e.g., car, traffic lights, etc.)<br />

## Structural Representation of YOLO - Algo:

![fda](https://user-images.githubusercontent.com/69640722/182418321-c54b099d-42ad-4948-9377-3198c3dfc979.jpg)


### How to use:
1. Clone the repo
2. Clone the darknet repo using following command:
git clone https://github.com/pjreddie/darknet.git
3. Run the main.py

### Sample Result:
![ad](https://user-images.githubusercontent.com/69640722/182419817-04e289b7-620e-405c-a337-f92118a5964c.jpg)
