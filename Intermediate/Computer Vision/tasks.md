# Computer Vision Tasks - Intermediate Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Feature Detection and Matching

### Objective
Implement feature detection and matching between images.

### Requirements
1. Implement or use feature detectors:
   - SIFT, SURF, ORB, or Harris corners
   - Extract keypoints and descriptors
2. Match features between two images
3. Apply RANSAC for robust matching
4. Visualize matches with connecting lines
5. Calculate transformation matrix (homography)
6. Document accuracy and performance

### Hints
- Use OpenCV for feature detection
- Filter matches using distance ratio test
- Handle outliers with RANSAC
- Test with images from different viewpoints

---

## Task 2: Image Segmentation

### Objective
Implement image segmentation to separate objects from background.

### Requirements
1. Implement at least 2 segmentation methods:
   - Threshold-based (Otsu's method)
   - K-means clustering
   - Watershed algorithm or similar
2. Apply to multiple test images
3. Evaluate segmentation quality
4. Post-process results (morphological operations)
5. Compare different methods' performance
6. Visualize segmentation masks

### Hints
- Preprocess images (smoothing, color space conversion)
- Use appropriate number of clusters
- Consider edge detection as preprocessing
- Evaluate using metrics like IoU if ground truth available

---

## Task 3: Object Detection System

### Objective
Build a simple object detection system using classical CV techniques.

### Requirements
1. Choose an object category to detect
2. Implement detection pipeline:
   - Image preprocessing
   - Feature extraction
   - Sliding window or region proposals
   - Classification/detection
3. Use HOG features or similar descriptors
4. Implement non-maximum suppression
5. Test on multiple images
6. Report precision and recall
7. Visualize detections with bounding boxes

### Hints
- Start with well-defined objects (faces, simple shapes)
- Use pyramid approach for scale invariance
- Implement efficient window search
- Consider template matching for simple cases

---

## Evaluation Criteria

- **Correctness**: Algorithms work as intended
- **Code Quality**: Well-structured, documented code
- **Performance**: Efficient implementation
- **Analysis**: Thorough evaluation and comparison
- **Innovation**: Creative approaches to problems
