# Dehaze-Enhanced-Training-for-Missile-Detection-Using-YOLOv8
This project enhances missile detection using YOLOv8 by applying image dehazing as a preprocessing step. Dehazing improves image clarity in foggy or smoky conditions, boosting detection accuracy. The model is trained and tested on both original and dehazed images from a Roboflow dataset.


---

# 🎯 Problem Statement

### 📉 Limitations of Traditional Object Detection in Real-World Scenarios
- Environmental factors like haze and fog severely degrade image clarity.
- Object detection models (like YOLO) trained on clear images often fail in such conditions.
- Reduced visibility leads to lower detection confidence and missed objects (e.g., missiles).

---

# ✅ Proposed Solution

### 🌫️ Dehazing + 🔍 YOLOv8 = 🎯 Enhanced Detection

We introduce a preprocessing pipeline using **image dehazing techniques** prior to YOLOv8 training and inference to enhance feature visibility.

**Workflow:**
