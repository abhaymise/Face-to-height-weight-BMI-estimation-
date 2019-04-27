# Face-to-height-weight-BMI-estimation

## Objective :
Give a human image , identify height and weight and BMI of the individual.

## Solution :
The solution has been inspired by the paper FACE2BMI. This paper shows that face can be an important estimator of your height and weight and hence the BMI. The dataset quoted in the papaer is not publicly available hence i could not use the mentioned dataset for my work. I gathered data from internet manualyy. I have used almost similar technique in which i have used the celebrity's face to estimate their height,weight and BMI.

## Solution workflow
Image ==> Face ==> Face embedding ==> Height

Image ==> Face ==> Face embedding ==> Weight

Image ==> Face ==> Face embedding ==> BMI

## Data Collection and Augmentation
The dataset consists of 5-20 images of bollywood celeberities. The various images has been taken under different conditions so that we have enough variations. The images that has been taken is downloaded using google serach engine results. Care has been taken care that all the images are latest. The label for each celeberity has been noted from the publicly available forums.
