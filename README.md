# CONTENT-AWARE-IMAGE-RESIZING
This project focuses on Content-Aware Image Resizing, a smart image scaling technique that resizes images while preserving important content and minimizing distortion. It uses seam carving to intelligently remove or insert pixels along paths of least importance, ensuring key elements in the image remain intact.

Aspect Ratio Adjustment: Automatically adjusts images to standard aspect ratios like 16:9 or 4:3.
Custom Seam Removal: Allows users to manually specify the number of vertical and horizontal seams to remove.
Efficient Seam Carving Algorithm: Dynamically identifies low-energy seams to minimize distortion.
Interactive Output: Displays the original and resized image dimensions, seam details, and reduction amounts.
🔧 Technologies Used:

Programming Language: Python.
Libraries: OpenCV, NumPy, and Matplotlib for image processing and visualization.
Development Tools: Google Colab / Jupyter Notebooks for development and experimentation.
📂 Project Structure:

seam_carving.py: Core implementation of the seam carving algorithm.
main.py: Interface for users to input images and parameters for resizing.
data/: Folder containing sample images for testing.
outputs/: Resized images with detailed metadata.
📊 Results:

Demonstrated seamless resizing for images of various resolutions and complexities.
Provides users with metrics such as:
Original Dimensions: Width × Height.
New Dimensions: Adjusted Width × Height.
Width/Height Reduction: Number of seams removed.
