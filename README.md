# Object-Detection-and-Distance-Analysis

This programs helps you to detect and analyse objects and find the distance of objects without using sensors.
##Introduction
This repo contains object_detection.py which is able to perform the following task -

Object detection from live video frame, in any video file or in a image
Counting the number of objects in a frame
Measuring the distance of object using depth information
Inferece on Multiple Camera feed at a time
For object detection YOLO-V3 has been used which is able to detect 80 different objects. Some of those are-

person
car
bus
stop sign
bench
dog
bear
backpack and so on.

## Installation
    $ pip install -r requirements.txt
         or
    $ pip install opencv-python
    $ pip install numpy
    $ pip install pandas
    $ pip install matplotlib
    $ pip install Pillow
    $ pip install imutils
    
##For the installation of torch using "pip"

$ pip3 install torch===1.2.0 torchvision===0.4.0 -f https://download.pytorch.org/whl/torch_stable.html
or please follow the instructions from Pytorch

You need to clone the repository using gitbash (if gitbash is already installed) or you can download the zip file.

    $ git clone https://github.com/paul-pias/Object-Detection-and-Distance-Measurement.git
    
If you want to run object detection and distance measurement on a video file just write the name of the video file to variable id in "object_detection.py" or if you want to run it on your webcam just put 0 in id.
And If you want to test on images then run "Infer on Image.py"
