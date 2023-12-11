# DynImagic

This Python script extracts dominant colors from an image using k-means clustering, visualizes them along with their RGB values and generates individual images with the same pattern.

## Dependencies
- OpenCV
- NumPy
- IPython (for displaying images in Jupyter notebooks)

## Usage
1. Clone the repository or download the `Dominant_Colors_Script.py` file.
2. Install the required dependencies:
   ```bash
   pip install opencv-python numpy
Replace the image path in the script ('/content/Image/0.jpg') with the path to your desired image.
Run the script.
The script performs the following tasks:

1. Load and Preprocess Image
Uses OpenCV to read the input image.
Converts the image from BGR to RGB color space.
2. K-Means Clustering for Dominant Colors
Reshapes the image into a 2D array of pixels.
Applies k-means clustering to group similar colors together.
Finds the centers of the clusters, representing dominant colors.
3. Visualization
Creates color bars for each dominant color and displays them horizontally.
Adds RGB values as text to each color bar.
4. Display and Save Results
Displays the original image and the visualization of dominant colors.
Saves the results as images (original_image.jpg and dominant_colors.jpg).
