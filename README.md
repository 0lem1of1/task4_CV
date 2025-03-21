### **Assignment: Cropped Segment Detection in an Image**

#### **Objective**
Write a Python program that detects a cropped segment in the original image and draws a bounding box around the detected region in the original image. Use computer vision techniques to solve this task.

---

#### **Instructions**
1. **Input**:
   - Use the provided original image (`simple_image.png`).
   - Use the cropped part of the image (`cropped_image.png`).

2. **Tasks**:
   - Load both images using Python libraries such as OpenCV or Pillow.
   - Detect the cropped segment in the original image using feature matching techniques.
   - Draw a bounding box around the detected region in the original image.

3. **Requirements**:
   - Use feature detection algorithms like SIFT, ORB, or any other method for feature extraction.
   - Match features between the original and cropped images.
   - Use homography to find the location of the cropped segment in the original image.
   - Draw a bounding box around the detected region.

4. **Output**:
   - Save and display the original image with the bounding box drawn around the detected cropped segment.

---

#### **Expected Deliverables**
- A Python script (`detect_cropped_segment.py`) implementing the solution.
- The output image (`output_with_bounding_box.png`) showing the bounding box around the detected cropped region.

---

#### **Hints**
- You can use OpenCV's `cv2.SIFT_create()` or `cv2.ORB_create()` for feature detection.
- Use `cv2.BFMatcher()` or `cv2.FlannBasedMatcher()` for feature matching.
- Compute homography using `cv2.findHomography()` and use RANSAC to filter outliers.
- Draw a bounding box using OpenCV's `cv2.rectangle()` function.

---

#### **Resources**
1. [OpenCV Documentation](https://docs.opencv.org/4.x/)
2. Tutorials on feature detection and matching:
   - [Feature Matching with OpenCV](https://docs.opencv.org/4.x/dc/dc3/tutorial_py_matcher.html)
3. Homography estimation:
   - [Homography Estimation Guide](https://docs.opencv.org/4.x/d9/dab/tutorial_homography.html)

---

#### **Submission**
Submit your Python script and output image via email or upload them to your course portal by **March 26, 2025**.

Good luck! 🎯

---
