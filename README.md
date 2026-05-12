# EX:03
# Histogram-Equalization-Using-OpenCV

# AIM

To write a Python program using OpenCV to perform histogram equalization for enhancing a color image in the HSV color space.

# SOFTWARE REQUIRED

Python 3.7 (Anaconda)
Jupyter Notebook (for interactive development and execution)

# EXPLANATION

Histogram equalization is an image enhancement technique used to improve the contrast of an image by spreading the intensity values over a wider range. In color images, directly applying histogram equalization to RGB channels may distort colors. Hence, the image is converted into the HSV (Hue, Saturation, Value) color space, where the Value (V) channel represents brightness information.

The histogram equalization operation is applied only to the V channel to enhance brightness and contrast while preserving the original color information. After equalization, the HSV image is converted back to the BGR format for display. OpenCV provides efficient functions for color conversion and histogram equalization.

# ALGORITHM

Step 1: Import the required libraries such as OpenCV, NumPy, and Matplotlib

Step 2: Read the input color image (parrot.jpg) using OpenCV

Step 3: Display the original image and plot its histogram

Step 4: Convert the BGR image into HSV color space

Step 5: Split the HSV image into H, S, and V channels

Step 6: Apply histogram equalization to the V channel using cv2.equalizeHist()

Step 7: Merge the modified V channel with H and S channels

Step 8: Convert the HSV image back to BGR color space

Step 9: Display the enhanced image and compare it with the original image
# RESULT

Thus, the histogram equalization process was successfully performed on the color image using OpenCV in the HSV color space, resulting in improved image contrast and enhanced visual quality.
