# DeepSpaceML

For FRC Deep Space Tensorflow Object Detection. Used a modified tiny-yolo (v2) configuration from [darknet](https://pjreddie.com/darknet/) for training weights. Hatch.py was modified from [AlexeyAB's darknet fork](https://github.com/AlexeyAB/darknet). For demonstation purposes, opencv shows webcam feed, however can be removed for FRC deployment. Using [pynetworktables](https://robotpy.readthedocs.io/en/latest/install/pynetworktables.html), whether a box is detected is transmitted as well as the coordinates of drawn bounding boxes. For other frc teams, note the following change needed, change the 555 on line 10 to match your team number. 

Dependecies:
* Darknet
* Opencv
* Pynetworktables
