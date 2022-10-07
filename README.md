# Calibrate your camera using a chessboard
This is part of my work in the MoCap Arena project in the eROBOTICA Lab! 
### Use OpenCV to find the intrisics parameters of your camera!
We choose a calibration target, which the distance between the points in the target are know. 
To proceed with the calibration, several pictures are taken of the calibration target in differents views.
Then, compare the know real-word distances in target by the their distances in the image plane to find the intrisic matrix and the distorcion coefficients of 
your camera. **That process is what we call by camera calibration!**

### Some good pratices are: 
- Use a light source behind your camera
- Prepare a large dataset of images, you may need to delete some of then
- Make sure that the calibration target cover at least a half of the image

### To create a calibration target: 
If you dont have a calibration target, you will have to create your own! You can use the that OpenCV Python program available [here](https://docs.opencv.org/4.x/da/d0d/tutorial_camera_calibration_pattern.html)
or go to [calib.io](https://calib.io/pages/camera-calibration-pattern-generator) and made your own calibration target

#### To procede with the calibration, check the instructions in the Jupyter Notebook!
 
