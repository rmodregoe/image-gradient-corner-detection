# Image Gradient and Corner Detection with RANSAC

## Description
This project involves detecting image gradients, applying the Harris corner detection algorithm, and performing feature matching using RANSAC. The focus is on enhancing understanding of key image processing concepts such as gradients, corner detection, and geometric transformations.

## Included Files
1. **Images:**
   - `simA.jpg` - Input image for similarity transformation analysis.
   - `simB.jpg` - Similar to `simA` used for geometric transformations.
   - `transA.jpg` - Input image for translational case in RANSAC.
   - `transB.jpg` - Paired with `transA` for translational transformations.

2. **Code:**
   - `corner_detection.ipynb` - Jupyter Notebook with implementation details, algorithms for gradient calculation, corner detection, and feature matching.
   - Supporting Python scripts are integrated into the Jupyter Notebook.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/rmodregoe/image-gradient-corner-detection.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install numpy matplotlib opencv-python
   ```
3. Open `corner_detection.ipynb` in Jupyter Notebook to explore the implementation and visualize results.

## Key Results
1. **Gradient Analysis:**
   - Computed X and Y gradients of the images using Gaussian derivative filters.
   - Visualized gradient pairs for better insight.

2. **Corner Detection:**
   - Applied the Harris corner detection algorithm.
   - Visualized corner points on the images.

3. **RANSAC:**
   - Feature matching using RANSAC for both translational and similarity transformations.
   - Visualized feature matches with inliers identified by RANSAC.

## Requirements
- Python 3.8 or higher
- Libraries:
  - `numpy`
  - `opencv-python`
  - `matplotlib`

## License
This project is licensed under the MIT License.

## Contact
Created by Ricardo Modrego. For any inquiries, contact [r.modrego.e@gmail.com](mailto:r.modrego.e@gmail.com).
