It uses KNN algorithm for face detection 
# K-NN

K nearest neighbors is a simple algorithm that stores all available cases and classifies new cases based on a similarity measure (e.g., distance functions). KNN has been used in statistical estimation and pattern recognition already in the beginning of 1970’s as a non-parametric technique. 
A case is classified by a majority vote of its neighbors, with the case being assigned to the class most common amongst its K nearest neighbors measured by a distance function. If K = 1, then the case is simply assigned to the class of its nearest neighbor. 

![knn_similarity](https://user-images.githubusercontent.com/23000971/33509095-c04a41c4-d724-11e7-8999-28dce74d4ed2.png)

## Code tutorial
https://youtu.be/yZ-hH89H5Tc
## Project demo
https://youtu.be/FH79poerjVc

## Haar-cascade Detection in OpenCV
OpenCV comes with a trainer as well as detector. If you want to train your own classifier for any object like car, planes etc. We use haarcascade_frontalface_default.xml to detect faces in image

## Collecting Face data 
For collecting data of differents faces "face_data.py" file is used and faces are stored in the form of Numpy array

## Face recognisation
For live face recognisation "face_rec.py" file is used which usses K-NN algorithm to check the given face 
