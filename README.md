# You Only Look Once (YOLO) Object Detection and Classification Algorithm - Miles Grant

YOLO is an object detection algorithm that has many applications in cyber-physical systems such as self-driving cars. The algorithm draws bounding boxes around objects in an image and classifies them.

## Citation
Rahmad Sadli - December 2019 </br>
Machine Learning Space - [The beginner’s guide to implementing YOLOv3 in TensorFlow 2.0 ](https://machinelearningspace.com/yolov3-tensorflow-2-part-1/)

## Requirements
```
tensorflow
keras
numpy
ipynb
opencv-python
```
## How to classify an image
1. Download [`yolov3.weights`](https://pjreddie.com/media/files/yolov3.weights) and put it in the `weights` directory
2. Put the image to be classified in the `img` directory.
3. Change the `img_path` variable in the "Setup" block of `image.ipynb`
4. Run `image.ipynb`
5. The classified image will be saved as `img/out.jpg`
