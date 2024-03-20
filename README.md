
# Kidney Stone Detection using Image Analysis and Segmentation
This repository contains a Python script for detecting kidney stones in medical images using image analysis and segmentation techniques. The script utilizes various image processing algorithms to enhance the input image and perform segmentation to identify potential kidney stones.

Dependencies
Make sure you have the following dependencies installed in your Python environment:

OpenCV (cv2): Used for image loading, processing, and manipulation.
NumPy (np): Required for numerical computations and array manipulation.
Matplotlib (plt): Utilized for plotting and visualization.
Scikit-image (skimage): Necessary for various image processing tasks, especially morphology operations.
Math: The built-in Python math module is used for mathematical computations.

Usage
To use the script:

Clone or download this repository to your local machine.
Ensure you have Python installed along with the required dependencies.
Run the script by executing python kidney_stone_detection.py in your terminal or IDE.
The script will load the input image, perform image enhancement, and then apply segmentation techniques to identify kidney stones. The results will be displayed for visualization.

Script Overview
The script follows these main steps:

Pre-processing: Applies various pre-processing techniques to the input image, such as noise reduction and thresholding.

Enhancement: Enhances the pre-processed image using Gaussian and median filters to improve clarity and highlight potential kidney stones.

Segmentation: Utilizes segmentation techniques, including erosion and dilation, to isolate and identify kidney stones within the enhanced image.

Visualization: Displays the input image, enhanced image, and segmented regions to visualize the detection process.
