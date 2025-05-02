# 🤖 Automated Waste Sorting System Using Computer Vision and Robotic Manipulation

This project presents a **computer vision-based waste detection and classification system** combined with a **virtual robotic arm** simulation. It identifies different waste types using color and texture features and sorts them into appropriate bins using robotic manipulation logic.

---

## 📌 Table of Contents

- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [How It Works](#-how-it-works)
- [Input Options](#-input-options)
- [Output](#-output)
- [Simulated Robotic Arm](#-simulated-robotic-arm)

---

## ✅ Features

- 📷 Waste detection using HSV color segmentation
- 🧠 Classification based on visual features and texture
- 🦾 Simulated robotic arm sorting logic
- 📊 Visual statistics and logs
- 🧪 Support for synthetic and uploaded images
- 📁 Test image generation

---

## 🧠 Technologies Used

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Pillow
- Google Colab support

---

## 🔍 How It Works

1. Load an image containing waste materials.
2. Segment waste items using HSV-based color ranges.
3. Extract features (average HSV, texture variance).
4. Classify each item as **plastic**, **paper**, **metal**, **glass**, or **organic**.
5. Simulate a robotic arm that:
   - Moves to the item
   - Picks it up
   - Places it in the correct bin
6. Generate output image and statistical visualizations.

---

## 🖼️ Input Options
1. On running the script, you can choose:
2. Use built-in sample images
3. Upload your own images (Colab only)
4. Use webcam input (local only)
5. Generate test images (recommended for demo)

---

## 🧾 Output
1. Detected waste items with bounding boxes and confidence scores
2. Sorted waste categories
3. Real-time simulation of robotic movement
4. Summary bar chart of all waste types processed
5. Sorting logs in waste_sorting_log.txt

---

 ## 🖼️ Screenshots

Below is an example output of the waste detection system:

| Original Image | Detected Waste |
|----------------|----------------|
|![Detected Waste Output](./waste_detection_output.png)|


This output shows:
- Left: Raw image with mixed waste
- Right: System-detected categories like `Paper`, `Plastic`, and `Glass` with confidence scores and bounding boxes.

  ---


## 🤖 Simulated Robotic Arm
1. The VirtualRobotArm class simulates a 2D robotic arm:
2. Moves to detected object location
3. Picks it up
4. Moves to the category-specific bin
5. Releases the item
6. Positions are printed to the console and visualized in execution.

---

## 👨‍💻 Author
Developed by Arya and team, 2025.
For academic and project demonstration purposes.

