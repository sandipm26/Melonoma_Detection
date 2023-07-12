# Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma 
has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the 
International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, 
and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:
	- Actinic keratosis
	- Basal cell carcinoma
	- Dermatofibroma
	- Melanoma
	- Nevus
	- Pigmented benign keratosis
	- Seborrheic keratosis
	- Squamous cell carcinoma
	- Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The final model takes care of class imbalance by adding more augmented pictures along with dropout,normalization,regularization
- After 30 epochs, we have achieved 66% of training accuracy and 45% of validation accuracy
- After 30 epochs, we have 0.97 of training loss and 1.61 of validation loss
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas 1.3.5
- numpy 1.21.5
- tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the lectures and live session conducted by Upgrad & IIIT Bangalore.



## Contact
Created by [@sandipm26] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->