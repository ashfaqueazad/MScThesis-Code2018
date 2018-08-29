# MScThesis-Code2018
Contains code related to the thesis "Object Detection and Defense against Adversarial Images"

Contained within these are:

•	Code for object detection using YOLO v2 608 x 608.

•	Defense system :

  o	Defense model against adversarial attacks.
  
    	Also calculates the accuracy of the Defense model.
    
  o	Code showing the creation of α’ attack.*
  
  o	Using L-BFGS-B to attack ResNet50 and generate adversarial image. 
  
    	Also checks the impact of using rotation (in our case flipping an image horizontally) and median filter (with window size of 3 x 3) upon images, both adversarial and unperturbed. 

* α’ is an adversarial image capable of attacking two pre-trained image classifiers at a single time.
