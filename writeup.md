# Writeup: Track 3D-Objects Over Time

Please use this starter template to answer the following questions:

### 1. Write a short recap of the four tracking steps and what you implemented there (filter, track management, association, camera fusion). Which results did you achieve? Which part of the project was most difficult for you to complete, and why?
Filter - A kalman filter with camera fusion was implemented to predict the measurements based upon the laser and camera input. Track Management was implemented to create new tracks, associate measurements to tracks. 
The most difficult part for me was the sensor fusion as it involved so many transformations. This additional data I expect to get better data.
### 2. Do you see any benefits in camera-lidar fusion compared to lidar-only tracking (in theory and in your concrete results)? 
Yes, this adds redundancy in case one system goes down.

### 3. Which challenges will a sensor fusion system face in real-life scenarios? Did you see any of these challenges in the project?
I can imagine sensors going bad. No, I did not see this represented.

### 4. Can you think of ways to improve your tracking results in the future?
Integrate sensors from another domain like radar.
