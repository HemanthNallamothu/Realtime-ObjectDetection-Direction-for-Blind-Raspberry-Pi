## Realtime-ObjectDetection-Direction-for-Blind-Raspberry-Pi

#### Instructions:

* The aim of this project is to help blind people by letting them know when an obstacle is detected and also sending an audio output. All of this is done in Real-time and without use of internet and Smart Phone.

* For our Hardware, we are using Raspberry Pi 4 with a Pi camera. The specifiations that we have are: 4GB RAM/32GB MicroSD/5MP Camera/Power cable and a Battery/Audio jack/HDMI cable to connect to our system.

* In the Program part we used Pre-Trained YOLO v3 model, which is a state-of-the-art, real-time object detection system. It consists of weights and configuration files.

* As for the main python librarys we are using Opencv2(Use contrib-python for additional modules) and gTTS API. All packages are either installed from Rasbian OS(from pip or terminal) or pre-installed in the device itself.

* As weights files are large see the link below depending on choice.

```
PS:  You can use either tiny-weights(for less accuracy and more fps) or weights(for more accuracy and less fps) depending on your choice.
```

Model1:  [Click Here](https://pjreddie.com/media/files/yolov3.weights)

Model2:  [Click Here](https://pjreddie.com/media/files/yolov3-tiny.weights)

#### Execution:

* Upload all files i.e .py/.weights/.cfg in the same directory of our Raspberry Pi device.
Raspberry Pi 4 is operated using Rasbian OS which can be installed as our OS or from virtual box which I recommend.

* Run the code from Thonny or use a button(only when code is set inside Kernel) connected to the hardware. We get an audio as our output.

#### Limitations:

* If you have executed the code then you can observe that the total execution and getting output takes more time(3-4 minutes). Also hardware gets heated up if you use continuously.
* To increase the throughput you can use tiny-weights and also use other models such as caffe ImageNet SSD model.


```
Project associates:

1. HemanthNallamothu     
2. TejPratap     
3. VamsiKrishna      
4. Yeshwant
```

```
Note: There will be some major changes in this project which I'll put in another Repo. It's concept is to use an app along with a USB connected camera. Pit detection will also be added to the model.
```
