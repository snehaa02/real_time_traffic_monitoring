# real_time_traffic_monitoring
Developed a system that effectively detects, tracks, and counts vehicles, estimates their speeds, and identifies speed limit violations with 95% accuracy, promoting proactive traffic management and safety.

Achieved robust performance across diverse video datasets by effectively integrating YOLOv8's state-of-the-art pretrained model and implementing a centroid tracking 
algorithm, ensuring adaptability to real-world traffic scenarios.
This system can efficiently detect, track, and count vehicles moving in either direction and estimate the speed of the vehicles. It can also detect vehicle speed limit violations to ensure road traffic safety. I have Used the centroid tracking algorithm to track the vehicles. The centroid tracking algorithm works by tracking the centroids of the vehicles detected by YOLOv8.

The system was evaluated on the YOLOv8’s pretrained model (e.g., yolov8s.pt). All YOLOv8 models for object detection are already pre-trained on the COCO dataset, which is a huge collection of images of 80 different types. It was Tested on different videos, and average accuracy achieved by the system is up to 95%.
