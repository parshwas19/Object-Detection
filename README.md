# Object-Detection

Creating accurate machine learning models capable of localizing and identifying multiple objects in a single image remains a core challenge in computer vision.<br>
So I tried making an Object detection model using Tensorflow.
After some research I came across a few blogs where I found some APIs which are mandatory to be installed in order to use Tensorflow models.
I followed steps from those blogs, tried my trial & error method as everything is never given anywhere and build this model.

![Output of my Model](https://github.com/parshwas19/Object-Detection/blob/main/screenshot/Screenshot1.png?raw=true)

I tested my model on different videos and took screenshots from those videos, In this ReadMe file , I have only included screenshots from those videos. But we can use this same model for images also. And I have also designed code to identify objects from a webcam too.

![Output of my Model](https://github.com/parshwas19/Object-Detection/blob/main/screenshot/Screenshot2.png?raw=true)

This was a super fast Timelapse video of traffic, then also this model is accurately identifying most of the objects.
<h3>Steps:- </h3>

1. My first step started with installing Tensorflow version "2.2.0" and creating a new virtual environment for this project.

2. For using Tensorflow for Object detection we have to clone a Tensorflow Object Detection API's repository, so my next step was to clone it from <a href="https://github.com/tensorflow/models" target="_blank">Tensorflow Object Detection Api Repository</a><br>
What is Tensor Flow Model: The TensorFlow Model Garden is a repository with a number of different implementations of state-of-the-art (SOTA) models and modeling solutions for TensorFlow users.

3. My next step was <a href="https://github.com/protocolbuffers/protobuf/releases" target="_blank">Protobuff Installation and Compilation </a>
  The Tensorflow Object Detection API uses Protobufs to configure model and training parameters.

4.  COCO API installation
  As of TensorFlow 2.x, the pycocotools package is listed as a dependency of the Object Detection API and so it becomes mandatory for us to install COCO API

5. After completing all those installation of APIs, I jumped to code and used those models and API to write a code and build an Object Detection Model.
  
For my PC found I SSD Mobilenet an efficient Algorithm to use, but it varies PC to PC. <br>
We can also use R-CNN , Faster R-CNN for this model. 

![Output of my Model](https://github.com/parshwas19/Object-Detection/blob/main/screenshot/Screenshot3.png?raw=true)

