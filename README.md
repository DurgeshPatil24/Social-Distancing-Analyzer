# Social-Distancing-Analyzer
#Overview
Social distancing is deliberately increasing the physical space between people to avoid spreading illness. Staying at least six feet away from other people lessens your chances of catching COVID-19. This project uses OpenCV and YOLO to monitor/analyze whether people are maintaining social distancing or not.

 - This project uses YOLO for object detection.
 - Once the objects(people) are detected it then draws a bounding box around them.
 - Using the centroid of the boxes we then measure the distances between them.
 - For the distance measure, Euclidean Distance was used.
 - A box is colored RED if unsafe and GREEN if safe.



#Limitations and Future Scope:-
 - This project does not take into account the camera perspective.\
 - It does not leverage a proper camera calibration (Distances are not measure accurate).\


#Requirements: 
The project doesn't include the "yolov3.cfg"(https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg) and "yolov3.weights"(https://pjreddie.com/media/files/yolov3.weights). You have to have those for maximum precision of project or else for less precision or accuracy "yolov3-tiny.cfg" and "yolov3-tiny.weights"(https://pjreddie.com/media/files/yolov3-tiny.weights) will also work. 

#OUTPUT:















<img width="642" alt="Screen Shot 2021-10-29 at 12 15 46 AM" src="https://user-images.githubusercontent.com/52505088/139374703-664319a3-bd32-44a9-b40e-3dae834937bd.png">
