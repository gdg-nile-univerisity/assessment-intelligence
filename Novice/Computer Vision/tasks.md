# Computer Vision Tasks - Novice Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Image Manipulation Basics

### Objective
Implement basic image manipulation operations using numpy.

### Requirements
1. Load an image and convert it to a numpy array
2. Implement the following operations:
   - Convert to grayscale
   - Rotate the image by 90 degrees
   - Flip the image horizontally and vertically
   - Crop a region of interest
3. Display the original and processed images
4. Save the processed images

### Hints
- Use PIL/Pillow for image loading and saving
- NumPy array operations for transformations
- Consider image dimensions and data types

---

## Task 2: Simple Image Filter

### Objective
Create a custom image filter that applies basic transformations.

### Requirements
1. Load a color image
2. Implement at least 3 different filters:
   - Brightness adjustment
   - Contrast enhancement
   - Simple blur effect
3. Create a function for each filter that takes an image and parameters
4. Display before/after comparisons
5. Allow users to adjust filter intensity

### Hints
- Work with pixel values directly using numpy
- Normalize values to stay within valid range (0-255)
- Consider working with different color channels

---

## Task 3: Basic Edge Detection

### Objective
Implement a simple edge detection algorithm.

### Requirements
1. Load a grayscale image (or convert from color)
2. Implement a basic edge detection using:
   - Gradient calculation (horizontal and vertical)
   - Threshold-based edge extraction
3. Display the original image and detected edges
4. Experiment with different threshold values
5. Document how your algorithm works

### Hints
- Use numpy array operations for gradient calculation
- Consider using convolution with simple kernels
- Compare results with different threshold values

---

## Evaluation Criteria

- **Correctness**: Implementation produces expected results
- **Code Quality**: Clean, readable, well-commented code
- **Documentation**: Clear explanations of approach and results
- **Creativity**: Unique insights or additional features
