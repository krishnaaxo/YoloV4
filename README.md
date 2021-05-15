# YoloV4
- Colab Link: [https://colab.research.google.com/drive/1yL5GKxql4pQ_VRrquc6oMZNss10TkJ_M?usp=sharing][colab]
- [colab]: https://colab.research.google.com/drive/1yL5GKxql4pQ_VRrquc6oMZNss10TkJ_M?usp=sharing
![Capture](https://user-images.githubusercontent.com/67067573/116483268-60f98400-a8a4-11eb-930e-0ca9dd0833c1.JPG)
## What is YOLO?
YOLO, as stated, stands for You Only Look Once, it is an object detection system in real-time that recognizes various objects in a single enclosure. Moreover, it identifies objects more rapidly and more precisely than other recognition systems. 
It can estimate up to 9000 and even more seen and unseen classes of objects. The real-time recognition system could recognize several objects from a particular image, frame a confined-edge box nearby objects, and quickly trained and implemented in a production system.

 

Also, It is an achievement in object detection research that yields in better, quicker, and adaptable computer vision algorithms. 

 

## How does YOLO work?
As completely based on Convolutional Neural Network(CNN), it isolates a particular image into regions and envisioned the confined-edge box and probabilities of every region. Concurrently, it also anticipates various confined-edge boxes and probabilities of these classes.  YOLO observes the intact image through training and test time in order to encode circumstantial information classes and their features quietly. 

## Specifying YOLOv4 
 

YOLOv4 outruns the existing methods significantly in both terms “detection performance” and “superior speed”. In reference to a paper published, the research team mentions it as a “speedily operating” object detector that can be trained smoothly and used in production systems. 

 

The main objective was “to optimize neural networks detector for parallel computations”, the team also introduces various different architectures and architectural selections after attentively analyzing the effects on the performance of numerous detector, features suggested in the previous YOLO models.

 

Three authors “Alexey Bochkovskiy, the Russian developer who built the YOLO Windows version”, “Chien-Yao Wang”, and “Hong-Yuan Mark Liao”, are accounted for in this work and the entire code is available at Github.

 

## YOLOv4 consists of;

Backbone: CSPDarknet53, 

Neck: Spatial Pyramid Pooling additional module, PANet path-aggregation, and 

Head: YOLOv3 
