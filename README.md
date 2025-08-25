
# Objective: The objective of this experiment is to utilize OpenCV to calibrate a camera.

# Data Acquisition Process:
![calib_0](https://github.com/user-attachments/assets/0eb710fd-d301-4f32-a0f9-8452228aaeb1)

![calib_1](https://github.com/user-attachments/assets/36fa03f1-517d-4cab-9438-a5578643cc82)


![calib_290](https://github.com/user-attachments/assets/c55d2af6-75cd-47dd-9cc4-7e1b32a331c5)

# Methodology: 
In data acquisition, a total of 290 images were captured at different angles using a phone
camera (Pixel 6) for calibration purposes. For setting up the dimension of the Charuco board, I specified
the number of inner corners in the checkerboard (horizontal and vertical).For example : (11, 8) Charuco
board.After configuring the checkerboard dimensions, I proceeded to prepare the object and image points
required for calibration. The output is the result of corner detection for each image, indicating whether
corners were found or not.


# Results
The output is the result of corner detection for each image, indicating whether corners were
found or not. I successfully identified the corners in more than 50 images.


# For code and documentaion
https://colab.research.google.com/drive/1J2lGj0GAMR9PY8GIfNZ8h1AWtu3-2ahw

# Undistored Image

![undistorted_image_charuco](https://github.com/user-attachments/assets/333e1181-44a9-423f-9703-4f9e642cf05d)



   
