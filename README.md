# FaceMaskDetection
Detecting people with/without face masks using FasterRCNN


Used Dataset: https://www.kaggle.com/andrewmvd/face-mask-detection

About the data:
Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization. With this dataset, it is possible to create a model to detect people wearing masks, not wearing them, or wearing masks improperly.
This dataset contains 853 images belonging to the 3 classes, as well as their bounding boxes in the PASCAL VOC format.
The classes are:

With mask;
Without mask;
Mask worn incorrectly.

FasterRCNN model with Adam optimizer is implemented in the notebook, as well as helper function for drawing boxes. 


Result of the model:

![image](https://user-images.githubusercontent.com/25666677/140797978-f594cefa-c446-4e65-9294-1f63980e089a.png)
