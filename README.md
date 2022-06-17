# Head-Pose-Estimation
Estimate the head pose in yaw, pitch and roll

## Steps followed:


##### 1- Getting Face landmarks by Mediapipe and create features dataset.
##### 2- Cropping Images to create another dataset with just a face.
##### 3- Making pipeline to Normalize data using standard scalar then dimentionality reduction using pca and the model.
##### 4- Using MultiOutputRegressor and SVR Model to predict the yaw, pitch and roll.
##### 5- Testing the model in images from the dataset.
##### 6- Finally test the model with a  live video and get an Mean absolute error score equal to 0.073.
