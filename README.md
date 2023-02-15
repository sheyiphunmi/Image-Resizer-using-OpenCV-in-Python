# Using Python to Create Image Filters


This repository contains a Python script that resizes images using OpenCV (cv2) library. The script defines a function called rescale_image that takes two parameters representing the input directory path and the output directory path. The function loads each image file from the input directory and resizes it so that its longest dimension (either height or width) is equal to the maximum of the two dimensions. The resized image is then saved to the output directory with the same filename.

The code includes a specific call to the rescale_image function that resizes all JPEG images in a specific input directory and saves the resized images to a specific output directory.

This script is useful for resizing images before using them in machine learning and computer vision applications.

