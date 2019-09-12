# MobileNetV2_YOLOV3_ncnn <br/>
## MobileNetV2_YOLOV3 for the ncnn framework <br/>
<br/>
Papers <br/>
https://ai.googleblog.com/2018/04/mobilenetv2-next-generation-of-on.html <br/>
https://arxiv.org/pdf/1506.02640.pdf <br/>
Training set: VOC2007 <br/>
Size: 352x352 <br/>
<br/>
Special made for a bare Rapsberry see: https://qengineering.eu/opencv-c-examples-on-raspberry-pi.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
<br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/MobileNetV2_YOLOV3_ncnn/archive/master.zip <br/>
$ unzip -j master.zip <br/>
 <br/>
Remove master.zip and README.md as they are no longer needed. <br/>
 <br/>
$ rm master.zip <br/>
$ rm README.md <br/>
 <br/>
Your *MyDir* folder must now look like this <br/>
 <br/>
dog.jpg <br/>
mobilenet_yolov3.bin <br/>
mobilenet_yolov3.param <br/>
MobiYO.cpb <br/>
MobiYO.cpp <br/>
 <br/>
Run MobiYO.cpb with Code::Blocks <br/>
Remember, you need also have a working OpenCV 4 on your Raspberry.  <br/>
 <br/>
![output image]( https://qengineering.eu/images/outcome.png )

