# Crowd-monitor
Monitoring crowd and traffic flow with object detection and tracking 
This project uses INIVDIA Jetson Xavier with YOLO object detection and a tracking algorith to count the number of people and cars.The YOLO algorithm divides the input image frames into grid cells of 13X13, and each of the cells is responsible for predicting bounding boxes. 
For each of the bounding box YOLO classifies the object.In this project we are interested in cars and humans so it will output two classes:cars and Humans. 
The classes will come with confidence interval, and the objects that have high confidence interval will be fed into the tracking algorithm.
