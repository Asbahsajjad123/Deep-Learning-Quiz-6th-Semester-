Project Overview

This project is designed to extract individual slips/receipts from a single image containing multiple slips. The system uses Computer Vision and Deep Learning preprocessing concepts to detect the boundaries of each slip and separate them into individual images.

The main goal of this project is to automatically identify the borders of different slips and extract them from one combined image.

Objectives
Detect individual slips from a single image.
Detect the borders/contours of each slip.
Extract each detected slip separately.
Apply image preprocessing techniques to improve detection.
Save the extracted slips as separate image files.
Use concepts related to Computer Vision and Deep Learning preprocessing.
Technologies Used
Python
Google Colab
OpenCV
NumPy
Matplotlib
Computer Vision techniques
Computer Vision Concepts Used

The project uses the following image processing concepts:

Image Reading
The input image is loaded using OpenCV.
Grayscale Conversion
The RGB image is converted into a grayscale image to simplify processing.
Noise Reduction
Image filtering is applied to reduce unwanted noise.
Thresholding
Thresholding is used to separate the slips from the background.
Edge Detection
Edges of the slips are detected using image processing techniques.
Contour Detection
Contours are detected to identify the boundaries of individual slips.
Bounding Boxes
Bounding rectangles are created around detected slips.
Image Cropping
Each detected region is cropped from the original image.
Individual Slip Extraction
The cropped slips are saved as separate image files.
Input

The input is a single image containing multiple slips/receipts.

Example:

input_image.jpg

The image contains approximately five individual slips that need to be separated.

Processing Steps

The project follows these steps:

Upload the input image in Google Colab.
Read the image using OpenCV.
Resize the image if required.
Convert the image into grayscale.
Apply Gaussian Blur to reduce noise.
Apply thresholding or edge detection.
Detect contours.
Filter contours according to their size and shape.
Draw bounding boxes around the detected slips.
Crop each detected slip.
Save each slip separately.
Display the final extracted slips.
Output

The final output contains individual images of the detected slips.

For example:

slip_1.jpg
slip_2.jpg
slip_3.jpg
slip_4.jpg
slip_5.jpg

The extracted slips are separated from the original combined image using their detected borders.
