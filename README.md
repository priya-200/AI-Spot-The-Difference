# Spot-the-Difference AI

A Python project that uses **OpenCV** and **Structural Similarity Index (SSIM)** to detect and highlight even the **smallest differences** between two images. This tool automatically spots differences, marks them with bounding boxes and labels, and creates mask and filled images for clear visualization.

---

## Features

- Detects **minute changes** between two images
- Highlights differences with bounding boxes and numeric labels
- Generates mask and filled images showing difference regions
- Calculates similarity score between images
- Useful for various real-world applications like quality control, security, and medical imaging

---

## How It Works

1. **Image Loading & Preprocessing:**  
   Load input images and convert them to grayscale.

2. **Structural Similarity Index (SSIM) Calculation:**  
   Compare grayscale images to get a similarity score and difference map.

3. **Thresholding & Contour Detection:**  
   Apply threshold to the difference map and find contours outlining changed areas.

4. **Mark Differences:**  
   Draw rectangles and labels around detected differences on both images.  
   Create mask and filled images that visualize difference areas.

5. **Save Results:**  
   Output processed images and difference statistics.

---

## Installation

Make sure you have Python 3.x installed along with the required libraries:

```bash
pip install opencv-python numpy matplotlib scikit-image
```
## Real-World Applications
 - 🔧 Quality Control: Detect defects or changes in manufacturing parts

 - 🛡️ Security & Surveillance: Spot unauthorized edits or intrusions

 - 🏥 Medical Imaging: Track changes in patient scans over time

 - 📝 Document Verification: Detect alterations in official documents or images

---

## Results
 - Outputs images with highlighted differences

 - Provides a similarity score between the two input images

 - Creates mask and filled difference visualizations for easier analysis

