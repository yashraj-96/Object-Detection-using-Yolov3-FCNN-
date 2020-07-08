# Object-Detection-using-Yolov3-FCNN-
Yolov3 is a Fully Convolutional Neural Network which facilitates faster object detection. In this project, pre-trained Yolov3 weights from their official website are fetched, and used for training the Tensorflow model. These pre-trained weights are trained over 80 classes of images, which can detect almost every basic object in real-time. 

# Running a custom GPU environment

In Computer Vision , computational requirements are high. If Yolov3 is said to be computing faster , that definitely requires a high processing hardware to function at its best.
There are two (.yml) files above that correspond to GPU and CPU respectively. These files are used to create a environment in Anaconda , wherein , we have a seperate environment dedicated to GPU , that is the detection will carry out on GPU processing , whereas , if a system doesn't have it, it can run in CPU environment.

These environments can be activated in Anacaonda prompt.

# Yolov3 weights

The pre=trained weights can be downloaded from the Yolo webiste itself. There are two varaints , Yolov3 and Yolov3_tiny which is trained on less number of classes but provides high FPS in output video being produced.

# Running the final code

The 'detect.py' file can be made to run in prompt directlty which would save the image with detections respectively. The 'detect.py' file is used for object detections in image , whereas , the 'detect_video.py' file is used for object detections in a video fie.
