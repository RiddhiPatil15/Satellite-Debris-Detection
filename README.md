# Satellite-Debris-Detection

## 📌 Overview  
This project implements a **computer vision pipeline** to detect and track **synthetic space debris** in satellite imagery.  
Using **EuroSAT satellite images** as realistic backgrounds, synthetic debris objects are overlaid to create a custom dataset.  
The system then applies **OpenCV-based thresholding and contour detection** to identify debris and evaluates detection accuracy against ground-truth annotations.

---

## 🚀 Features  
- ✅ Uses **EuroSAT dataset** as satellite background  
- ✅ Generates **synthetic debris dataset** (small white circular blobs) with bounding box annotations  
- ✅ Detects debris using **thresholding + contour detection** (CPU-friendly)  
- ✅ Logs detections into a **CSV file** (bounding boxes + counts)  
- ✅ Evaluates accuracy using **Intersection over Union (IoU)**  
- ✅ Visualizes original images vs detected debris  

---

## 🛠️ Tech Stack  
- **Python 3.9+**  
- **OpenCV** → Image processing & detection  
- **NumPy & Pandas** → Data handling  
- **Matplotlib** → Visualization  
