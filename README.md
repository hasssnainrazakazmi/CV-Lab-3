CV-Lab-3: Histogram EqualizationProject OverviewThis repository contains a Python-based implementation of Histogram Equalization using OpenCV. The primary objective of this task is to take a grayscale image with poor contrast and redistribute its pixel intensities to span the full range of available values (0–255), resulting in a clearer and more visually balanced image.Student Name: Syed Hassnain Raza Student ID: 23108142 Course: Computing Vision - Lab 3 Core FeaturesGrayscale Conversion: Reads input images directly in grayscale mode for processing.Contrast Enhancement: Utilizes the cv2.equalizeHist() function to improve image global contrast.Statistical Visualization: Generates side-by-side comparisons of original and equalized images along with their respective histograms to visualize pixel distribution changes.Technical Implementation
The project follows a structured 4-step workflow:


Image Upload: Interactive file upload via Google Colab.


Preprocessing: Reading the image using cv2.IMREAD_GRAYSCALE.


Histogram Equalization: Applying the equalization algorithm to the image array.


Visualization: Using matplotlib to plot the transformation results.
