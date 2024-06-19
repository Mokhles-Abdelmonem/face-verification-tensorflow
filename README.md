## Face Verification with TensorFlow

This is a simple face verification project using TensorFlow. 

**What it does:** 

* Compares an image to a reference image to see if they match (same person).

**Requirements:**

* Python 3+
* TensorFlow
* OpenCV (for image processing)
* matplotlib (for visializing data)

**How to use:**

1. Install tensorflow ,tensorflow-gpu, opencv-python matplotlib . 
2. Download a pre-trained face recognition model (find one online).
3. Run the verification script (`python verify.py reference_image.jpg your_image.jpg`). 
   - Replace the filenames with your actual image paths.
4. The script will tell you if the faces match.

**Note:** This is a basic example. You might need to adjust it for your needs.

