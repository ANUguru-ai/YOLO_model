# YOLO_model

We present YOLO, a new approach to object detection. Prior work on object
detection repurposes classifiers to per- form detection. Instead, we frame object
detection as a re- gression problem to spatially separated bounding boxes and associated
class probabilities. A single neural network pre- dicts bounding boxes and class
probabilities directly from full images in one evaluation. Since the whole detection
pipeline is a single network, it can be optimized end-to-end directly on detection
performance. Our unified architecture is extremely fast. Our base YOLO model processes
images in real-time at 45 frames per second. A smaller version of the network,
Fast YOLO, processes an astounding 155 frames per second while still achieving
double the mAP of other real-time detec- tors. Compared to state-of-the-art detection
systems, YOLO makes more localization errors but is less likely to predict false
positives on background. Finally, YOLO learns very general representations of objects.
It outperforms other de- tection methods, including DPM and R-CNN, when
gener- alizing from natural images to other domains like artwork.

This project comprises of detection of waste materials using Supervised machine learning approach. YOLO darknet is a machine learning frame work used for implementing the model. The data collected in the form of images are applied to the input of Neural Nets producing image predictions as output. The network is real-time implemented using Rasberri pi 4.The machine learning method is more accurate and faster as  compared to other existing networks like SSD mobile net and faster-Rcnn.YOLO frame work is best in training the sample output, which is a  leading neural network architecture.The model is  used to classify exact five categories such as plastic, paper, metal,  glass, cardboard and collected almost 200 images among each class.The model is trained to 5000 epochs to get better accuracy.This yolo model is tested in yolo-tiny cfg ) which can withstand 320 fps in real time leads to faster detection .

