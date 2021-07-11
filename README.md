# Colorizing-gray-image
## Description
 Colorization of grayscale images has become a more researched area in recent years, thanks
to the advent of deep convolutional neural networks. We attempt to apply this concept to
colorization of black and white images without any problem. In this project we have
described a method of colorizing a grayscale image in detail. The object and texture content
of the image can be as similar as it can be to the target image. Although we can never be
perfectly sure that matching of objects from target to image is absolutely correct. Hence to
improve this we partially colorize the given image at those points where we are absolutely
sure. To implement it, we propose convolutional neural network architectures trained. With
AI technology, we can implement it in a systematic way without any problem occurring.

## Software used
System and Server: Python 3.8, SQLite <br/>
Website: XAMPP, PHP 5.5 <br/>
Apps: Android Studio <br/>

## Syetem requirements for backend AI module
tensorflow==2.3.1 <br/>
keras==2.4.3 <br/>
numpy==1.18.5 <br/>
opencv-python <br/>
uvicorn <br/>
fastapi <br/>
uuid <br/>
pydantic <br/>
sqlalchemy <br/>

## Design
### Architecture :
Using U-net architecture to keep the features from every layers and prevent losin on any content information. <br/>
The network structure are shown below:
<img src="./img/d1.jpg">

### Training method:
Using COCO2017 image dataset, resize to 256*256, the decolorized version of it will be the input to the training model and the result will be compared with the original colourful image's pixels.

## Result
The training result's accuracy over period if shown below:
<img src="./img/r0.jpg">

## Outputs
The output from the system:
<img src="./img/r1.jpg">
