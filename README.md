# Simple-Face-Recognition-Using-OpenCV

 - OpenCV (Open-Source Computer Vision Library) is an open source and
   most popular computer vision and machine learning software library. 
   Originally written in C/C++, it now provides bindings for Python.
   
 - OpenCV library has more than 2500 optimized algorithms to perform
   various Computer Vision tasks such as detect and recognize faces,
   identify objects, classify human actions in videos, track camera
   movements, track moving objects, extract 3D models of objects,
   produce 3D point clouds from stereo cameras, stitch images together
   to produce a high resolution image of an entire scene, find similar
   images from an image database, remove red eyes from images taken
   using flash, follow eye movements, recognize scenery and establish
   markers to overlay it with augmented reality, etc.
 - OpenCV uses cascades to detect faces. Like a series of waterfalls,
   the OpenCV cascade breaks the problem of detecting faces into
   multiple stages. For each block, it does a very rough and quick test.
   If that passes, it does a slightly more detailed test, and so on. The
   algorithm may have 30 to 50 of these stages or cascades, and it will
   only detect a face if all stages pass.

## Installation & Setup:


### Requirements : 

 - [Python3](https://www.python.org/downloads/)
 - [PIP](https://bootstrap.pypa.io/get-pip.py) 
 - [OpenCV Library](https://pypi.org/project/opencv-python/)

#### Setup

 - Install Python3 version that matches your OS and add it your system PATH. Use the following command to check if its installed 
  `python --version`
- Check if pip is installed by running the following command 
   `pip --version`
- Install OpenCV Library
   `pip install opencv-python`

### Usage 
