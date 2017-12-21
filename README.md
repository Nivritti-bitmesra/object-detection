# object-detection
A real time object detection model using SSD architecture.

The network is composed of a base VGG network followed by the added multibox conv layers.  
Each multibox layer branches into :
1) conv2d for class conf scores
2) conv2d for localization predictions
3) associated priorbox layer to produce default bounding boxes specific to the layer's feature map size.
    
See: https://arxiv.org/pdf/1512.02325.pdf for more details.

The pre-trained model can be downloaded from : 
https://www.superdatascience.com/computer-vision/

For testing our model, we use a live webcam feed to obtain real time object detection.
Some snapshots of predictions are :

![img1](/detections/det1.png)

![img2](/detections/det2.png)

![img3](/detections/det3.png)

![img4](/detections/det4.png)

Author - Animesh Sharma
