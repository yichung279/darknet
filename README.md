![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Darknet #
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

# Feature

## crop detections:
Crop all detections in image. 

Example:

There 4 horses in `data/horses.jpg`. Following command will crop all 4 horses `data/horses.jpg` and save as `results/hore_x.jpg`

* step1: `$ make` 

* step2: `./darknet detect cfg/yolov3.cfg yolov3.weights data/horses.jpg`

