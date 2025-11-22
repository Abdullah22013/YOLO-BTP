
# YOLO-BTP

 This project aims at training the RadDet Dataset using YOLOv1 and YOLOv3 and achieving results similar to the RadDet research paper.

 This repository contains 2 .ipynb files namely "yolov1.ipynb" and "yolov3.ipynb", both of which contains the code and architecture of their specific YOLO version. 

Apart from the 2 .ipynb file the repo also contains the ground truth and predictions json files generated from the dataset and training the model on the RadDet dataset.

The dataset currently being used is the RadDet 1T Small (128x128) dataset.

Due to extensive size of the saved models(.pt) files, i have uploaded the saved models on a google drive. Drive link - [[Saved models]](https://drive.google.com/drive/folders/1WO5UjzpfHBy0rJlZKulcKCpGuco-FALS?usp=drive_link). The drive contains a number of saved models under different epoch values, patience values and with and without using the COCO evaluation method for calculating the mAP values. 

# Running the code

For running the code, preferrably use the python 3.10.12 version. Running the code is fairly easy, just run all the cells in the .ipynb file in sequential manner and the model will load all the functions and start training. The yolov1.ipynb file contains different sections for different parameters, there is different section for training and evaluating the model using COCO method and without using the COCO method, so run the cells carefully and according to your needs and specifications.





