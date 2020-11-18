# Image Classification using shift Feature


----
## Description
MNIST Digit classification using shift feature and SVM

----
## Dataset
1. mnist digit dataset
----

## Requirements
* Python 3.5
* Matplotlib
* Pandas
* Numpy
* opencv 4.4.0 
* sklearn
----
## Installation of Required opencv version
```
$ pip install opencv-contrib-python
```




## Run Model in steps
---
*Image Shift Feature Extraction*
--------------------------
```
In the Ipynb file image features are extracted and then saved in .pkl format 
```
*Training of SVM CLassifier*
--------------------------
```
Extracted Features are used for Classification using SVM and training time and accuracy of model is stored  for comparision 
```

## Accuracy V/s Threshold (no. of keypoints)
---
![alt text](https://github.com/udaram/Image-Caption-Generator/blob/master/TestResults/Screenshot%20from%202019-09-11%2013-24-39.png)

## Time V/s Threshold (no. of keypoints)
---
![alt text](https://github.com/udaram/Image-Caption-Generator/blob/master/TestResults/Screenshot%20from%202019-09-11%2013-24-39.png)

## Accuracy of Final Model
---
Accuracy of Final Model 0.821780247635761

## Confusion Matrix for Final Model
---
![alt text](https://github.com/udaram/Image-Caption-Generator/blob/master/TestResults/Screenshot%20from%202019-09-11%2013-24-39.png)

## Conclusion
---
<p>
From above graph between accuracy vs threshold and time vs threshold we can easily conclude <br>
1. that with increase in no. of key-points accuracy of model increases. <br>
2. With increase of no. of key-points time (training time) for SVM increases<br>
</p>

