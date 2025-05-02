# 🤖 Automated Waste Sorting System Using Computer Vision and Robotic Manipulation

An AI-powered system that automatically detects and classifies waste types using computer vision, and simulates a robotic arm to sort waste into appropriate bins. Designed for smart recycling and sustainable waste management.

---

## 📌 Features

- ✅ Detects and classifies **plastic**, **paper**, **metal**, **glass**, and **organic** waste.
- 🎯 Uses **color segmentation** and **feature extraction** (texture + HSV).
- 🦾 Simulates robotic arm pick-and-place sorting.
- 🖼️ Supports input via:
  - Sample synthetic images
  - Custom image uploads
  - Webcam (if available)
  - Generated test images
- 📊 Displays visual detection output and generates bar charts for analytics.
- 📁 Logs all sorting actions with confidence scores.

---

## 🛠️ Tech Stack

| Component        | Technology     |
|------------------|----------------|
| Language         | Python         |
| Computer Vision  | OpenCV         |
| Data Handling    | NumPy, Pandas  |
| Visualization    | Matplotlib     |
| Clustering       | scikit-learn   |
| Interface (Colab)| IPython, PIL   |

---

## 🖼️ Waste Categories

| Category | Color Code |
|----------|------------|
| Plastic  | Red        |
| Paper    | Cyan       |
| Metal    | Gray       |
| Glass    | Blue       |
| Organic  | Green      |

---

## 🚀 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/your-username/automated-waste-sorting-system.git
cd automated-waste-sorting-system
pip install -r requirements.txt

