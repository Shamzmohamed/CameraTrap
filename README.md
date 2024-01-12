# CameraTrap
• Camera traps are cameras which are equipped with a _motion detector_, an _infrared flash_ and a _brightness sensor_.  
• Camera can capture both _RGB_ and _IR_ images (day and night)  
• If the motion detector detects a movement a sequence of X photos is taken  
• If there is not enough daylight available (brightness sensor), an _IR flash_ is used  
• Camera traps are placed (often camouflaged) in the wild  
### Iteration-1 (Badger/Deer dataset - day images only):
1. Create a badger/deer dataset (BDD) from the day images of this species
2. Identify coherent sequences of images (over time) 
3. Locate the animals in the images (rough position)
4. Classify the animals (badger vs. deer)  
### Iteration-2 (BDD+):
1. Extend the BDD dataset with at least 2 additional species
2. Locate the animals in the images (alternative method)
3. Classify the animals into the min. 4 classes (alternative method)
- For this project to locate the animals in the images (annotate), I have used the MegaDetector, a computer vision model that detects animals in camera trap images
- MegaDetector is an object detection model that identifies animals, people, and vehicles in camera trap images (which also makes it useful for eliminating blank images). This model is trained on several hundred thousand bounding boxes from a variety of ecosystems.  
### Camera Trap Dataset:
Collected from Hoge Veluwe National Park (NL)  
• Biggest national park in the Netherlands
