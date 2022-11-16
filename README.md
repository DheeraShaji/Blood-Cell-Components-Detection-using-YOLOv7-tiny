# Blood-Cell-Components-Detection-using-YOLOv7-tiny

Dataset: https://universe.roboflow.com/object-detection/bccd.   
This is a dataset of blood cells photos.    
There are 877 images across three classes: white blood cells), red blood cells, and Platelets.  
No. of images in train set: 766.  
No. of images in val set: 74.  
No of images in test set: 37.  

Steps followed in implementing YOLOv7:    
1. Clone the YOLOv7 github repository at any location you want it.  [https://github.com/WongKinYiu/yolov7](url) 
2. Inside YOLOv7 directory, install the requirements.txt file and roboflow.
3. Download the pretrained weights.  https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7-tiny.pt
4. Set GPU.  
5. Set dataset configuration file.   
6. Train the model.   
7. Evaluate the model.   
8. Get inference with the trained weights.   
