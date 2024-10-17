# Keypoint Matching with SIFT and ORB

This project demonstrates how to use SIFT (Scale-Invariant Feature Transform) and ORB (Oriented FAST and Rotated BRIEF) algorithms for feature detection and matching between images. It also includes functionality to add Gaussian noise and apply perspective transformations to images.

## Requirements

Make sure you have the following libraries installed:

- OpenCV
- NumPy
- Matplotlib

You can install them using pip:

```bash
pip install opencv-python numpy matplotlib
```

## Example Output
The script will generate plots showing the matches for different scenarios, including:
- Matching original images
- Matching cropped images
- Matching perspective-transformed images
- Matching noisy images

## Conclusion
This project provides a basic framework for image matching using SIFT and ORB algorithms. You can extend it by adding more functionalities or optimizing the matching criteria.
- SIFT works better with transformations like scaling and rotation, while ORB is faster but may have reduced accuracy with transformations.
- You can modify the parameters for noise and perspective transformation to test different cases.
