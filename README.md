# DynImagic

This Python script extracts dominant colors from an image using k-means clustering, visualizes them along with their RGB values and generates individual images with the same pattern.

## Description

The project involves extracting the dominant colors from a group image (`image_group.jpg`) and applying each dominant color to a single image (`image_single.jpg`). The color change is performed by replacing pixels in the single image that are close to the original dominant color.

## Requirements

- Python (version 3.x)
- OpenCV
- NumPy
- scikit-image

Install the required libraries using:

```bash
pip install opencv-python numpy scikit-image
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/color-changing-project.git
cd color-changing-project
```

2. Run the Python script:

```bash
python color_change_script.py
```

This will generate and display changed versions of `image_single.jpg` using the dominant colors from `image_group.jpg`.

## Files

- `color_change_script.py`: The main Python script for changing colors.
- `image_single.jpg`: The single image for color change.
- `image_group.jpg`: The group image containing dominant colors.


