# INTRODUCTION
## Requirements:

Python  3.5

PyQt5	5.9.2	

opencv-python	3.4.0.12

tensorflow-gpu	1.5.0	

CUDA 8.0

easydict

## Use:

1. run train_and_detection/win_entry.py

2. "open model" --> (summary/cnn3d_17)

3. "open video"

## Model and TestVideo:

链接: https://pan.baidu.com/s/1O2h2lsNYtgtdDGYQI7aG3Q 密码: gzdq

## Train:

run train_and_detection/train.py

## Reference:

[1]Learning Spatio-Temporal Representation with Pseudo-3D Residual,ICCV2017

## Spatio-Temporal Deep Neursl Network Based Video Smoke Detection
### 1.model
 **2Dto3D：**

 ![index](https://github.com/xjg0124/Video_Smoke_Detection/raw/master/img/2Dto3D.png)

 **3D：**

 ![index](https://github.com/xjg0124/Video_Smoke_Detection/raw/master/img/3D.png)

 **conv3d block(A,B,C)：**

 ![index](https://github.com/xjg0124/Video_Smoke_Detection/raw/master/img/3Dblock.png)

 **3D_DenseNet：**

 ![index](https://github.com/xjg0124/Video_Smoke_Detection/raw/master/img/3D_DenseNet.png)

 **Result1：**

 ![index](https://github.com/xjg0124/Video_Smoke_Detection/raw/master/img/Result1.png)

 **Result2：**

 ![index](https://github.com/xjg0124/Video_Smoke_Detection/raw/master/img/Result2.png)


### PS：  
### A simple example train or test 3DCNN：  
A simple example as follows：  
https://github.com/TianzhongSong/3D-ConvNets-for-Action-Recognition  
Change /models/densenet_3d.py，and replace 3 * 3 * 3 Conv with 1 * 3 * 3 Conv and 3 * 3 * 1 Conv, modify in accordance with 3D_DenseNet，then you can train your own model.

