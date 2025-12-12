# LEGO Image Analysis – Object Detection & Segmentation

##  Overview
This project applies computer vision techniques to detect and segment LEGO bricks from images. The workflow includes preprocessing, thresholding, contour detection, and shape/size analysis.

##  Key Objectives
- Convert raw LEGO images into clean binary masks.
- Detect individual LEGO pieces using OpenCV.
- Extract shape, color, and size information.
- Prepare images for potential classification or counting.

##  Methods Used
- Grayscale conversion  
- Global and adaptive thresholding  
- Morphological operations  
- Contour detection  
- Bounding box extraction  

## Tools & Technologies
- Python
- OpenCV
- NumPy
- Matplotlib

## Results
- Successfully isolated LEGO pieces from background
- Generated contour maps and segmented outputs
- Created a foundation for machine learning classification

##  How to Run
1. Upload `lego_image.jpg` (or replace with your own)
2. Open the notebook and run cell-by-cell
3. View the segmented outputs

##  Future Improvements
- Train a CNN to classify LEGO brick types
- Add automatic piece counting
- Improve segmentation under poor lighting conditions
