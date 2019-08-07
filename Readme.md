
## Application for the recogntition of Mexican Plates and comparison to see if the car and plate matches with the stolen car registry. 

Demo of Plate Recognition 
Video source: https://firebasestorage.googleapis.com/v0/b/techlink-349b1.appspot.com/o/demo.MOV?alt=media&token=326fb2fb-9e95-42c7-addf-90c284b9f3d9

## Pre-requisites
1) Python 3.5
2) Numpy `pip3 install numpy`
3) Cython `pip3 install cython`
4) Optionally, OpenCV 3.x with Python bindings. (Tested on OpenCV 3.4.0)
    - You can use [this script](tools/install_opencv34.sh) to automate Open CV 3.4 installation (Tested on Ubuntu 16.04).
    - Performance of this approach is better than not using OpenCV.
    - Installations from PyPI distributions does not use OpenCV.
```
NOTE: OpenCV 3.4.1 has a bug which causes Darknet to fail. Therefore this wrapper would not work with OpenCV 3.4.1.
More details are available at https://github.com/pjreddie/darknet/issues/502
```

## Installation
Installation from PyPI distribution (as described below) is the most convenient approach if you intend to use yolo34py for your projects.

### Installation of CPU Only Version
```bash
pip3 install yolo34py
```

### Installation of GPU Accelerated Version
```bash
pip3 install yolo34py-gpu
```

