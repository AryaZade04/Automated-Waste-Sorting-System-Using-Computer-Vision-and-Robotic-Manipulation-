# 🤖 Automated Waste Sorting System Using Computer Vision and Robotic Manipulation

This project presents a **computer vision-based waste detection and classification system** combined with a **virtual robotic arm** simulation. It identifies different waste types using color and texture features and sorts them into appropriate bins using robotic manipulation logic.

---

## 📌 Table of Contents

- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [How It Works](#-how-it-works)
- [Usage](#-usage)
- [Input Options](#-input-options)
- [Output](#-output)
- [Simulated Robotic Arm](#-simulated-robotic-arm)
- [Screenshots](#-screenshots)
- [Limitations](#-limitations)
- [Future Work](#-future-work)
- [License](#-license)

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

## ⚙️ Installation

Install the required dependencies:

```bash
pip install opencv-python-headless numpy matplotlib scikit-learn pandas pillow

## 🔍 How It Works
Load an image containing waste materials.

Segment waste items using HSV-based color ranges.

Extract features (average HSV, texture variance).

Classify each item as plastic, paper, metal, glass, or organic.

Simulate a robotic arm that:

Moves to the item

Picks it up

Places it in the correct bin

Generate output image and statistical visualizations.

## ▶️ Usage
Run in Local Python Environment
bash
Copy
Edit
python pbl_2.py
Run in Google Colab
Upload the Waste_sorting_using_robotic_arm.ipynb notebook to Google Colab and run all cells.

## 🖼️ Input Options
On running the script, you can choose:

Use built-in sample images

Upload your own images (Colab only)

Use webcam input (local only)

Generate test images (recommended for demo)

## 🧾 Output
Detected waste items with bounding boxes and confidence scores

Sorted waste categories

Real-time simulation of robotic movement

Summary bar chart of all waste types processed

Sorting logs in waste_sorting_log.txt

Example log:

csharp
Copy
Edit
2025-05-02 14:22:30 - Detected Plastic with confidence 0.91
2025-05-02 14:22:35 - Detected Paper with confidence 0.85
## 🤖 Simulated Robotic Arm
The VirtualRobotArm class simulates a 2D robotic arm:

Moves to detected object location

Picks it up

Moves to the category-specific bin

Releases the item

Positions are printed to the console and visualized in execution.

🖼️ Screenshots
Add your own screenshots here if you wish.

css
Copy
Edit
Original Image               Detected Waste
[IMG HERE] ----------------> [IMG WITH BOXES]
⚠️ Limitations
Detection accuracy limited by HSV segmentation

No real object detection model (like YOLO or SSD) used

Robotic arm is simulated; no hardware integration yet

Color-based features might fail under different lighting

🔮 Future Work
Integrate real-world deep learning detection models (e.g., YOLOv8)

Deploy to Raspberry Pi + robotic hardware

Expand detection robustness with dataset training

Real-time edge processing and IoT bin updates

🪪 License
This project is open-source and for educational use only. No warranties or production deployment implied.

👨‍💻 Author
Developed by Arya, 2025.
For academic and project demonstration purposes.


