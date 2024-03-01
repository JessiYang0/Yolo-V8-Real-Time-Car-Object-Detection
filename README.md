# Yolo-V8-Real-Time-Car-Object-Detection


https://github.com/JessiYang0/Yolo-V8-Real-Time-Car-Object-Detection/assets/63945492/8c9c6977-0fb3-413d-8498-92d36aa661f0

The goal is to count vehicles within a specific area in each frame to assess traffic density. This valuable data aids in identifying peak traffic periods, congested zones, and assists in urban planning. 

## Dataset
Training: 536 images
Validation: 90 images
Label: Contains YOLOv8 format labels 
standard input size of 640x640 pixels

## Setup
* * Load a pretrained YOLOv8n model from Ultralytics
* * The pre-trained model we've loaded is trained on the COCO dataset, which includes the 'car' and 'truck' classes among its 80 different categories — exactly what we need for our project
* * Perform inference on the provided image(s)
  
