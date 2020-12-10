# ObjectDetectionWithYOLO
OpenCv algorithm to detect objects with YOLO 

**YOLO (You Only Look Once)** is a very powerful and a fast algorithm in object detection. 

# step 0

- Download this file abd save it insode yolo folder : [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)

- Create a folder **images** and have some pictures inside it to test the object detection.

# step 1
Open Terminal and navigate to project directory, make sure python3 is isntalled, if yes type this command to install necessary dependencies:
~~~
pip3 install -r requirements.txt
~~~ 
Go and grub a cup of coffee as it may take a while.

# step 2
to execute the image detection: 
~~~
python3 ObjectDetecet.py --image images/apples-and-oranges.png
~~~

don't forget 'q' to quit the window frame
