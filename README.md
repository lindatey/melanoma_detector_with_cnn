# melanoma_detector_with_cnn
Melanoma detection model using customised convolutional neural network.
This project aims to build a multiclass classifcation model that is able to detect melanoma, a type of deadly skin cancer from a pool of images. 

## Table of Contents
Understanding Dataset
Language and libraries Used
Train Model
Test Model
Submission
Conclusion
Acknowledgements
* [Problem statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Problem statement
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths and identifying melanoma involved multiple steps and can be tedious. Currently, a biopsy of the suspicious skin area, called a lesion, is the only sure way for the doctor to know if it is cancer. In a biopsy, the doctor takes a small sample of tissue for testing in a laboratory and these process 
take days before doctor can conclude if the images provided is indeed melanoma or something else.

A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. As such, this project aims to build a CNN based model which can accurately detect melanoma based on image supplied.

## Conclusions
All belows model uses dataset that has been rescaled before CNN is applied.

- Conclusion 1 from the analysis
- The analysis started with a simple based model with only dense layer. With the base model, it was clear there was underfittin as the result curve from train and validation has a minor gap yet low accuracy. To handle this, data augmentation is planned for the next model.
  
- Conclusion 2 from the analysis
- With data augmentation being implemented, the gap between training and validation curve accuracy can be seen significantly removed. However the model is too simple that the accuracy was still too low (<50%) therefore was not acceptable.
  
- Conclusion 3 from the analysis
- Data imbalance treatment was done in the 3rd analysis using Augmentor library. Images were copied into OUTPUT folder in each of the trained class. This method works in adding more accuracy to the model.

- Conclusion 4 from the analysis
  Adjusting the epochs - By adding 1 more level of convulational layer, and using augmentator, the accuracy has increased.

## Technologies Used
- tensorflow
- keras
- pandas
- statistics
- matplotlib
- pickled

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@lindatey] - feel free to contact me!

