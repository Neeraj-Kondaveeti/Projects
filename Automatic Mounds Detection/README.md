
# 🏺 Automatic Mound Detection using YOLO and Digital Terrain Models (DTM)

This project presents a machine learning-based approach to identifying archaeological mounds using Digital Terrain Model (DTM) data and the YOLO (You Only Look Once) object detection framework. By combining modern deep learning with historical geospatial data, the system aims to streamline and improve the accuracy of mound detection, helping archaeological and heritage research.

---

## 📌 Abstract

Traditional mound identification methods, including manual LIDAR inspection and DEM analysis, often suffer from false positives due to the inclusion of non-terrain features like buildings. This project employs DTM instead of DEM, as DTM removes surface structures, thereby improving precision. The YOLOv5 model with transfer learning is used to detect mound-like features from hillshaded DTM imagery.

---

## 🧠 Technologies Used

- **Deep Learning Framework**: YOLOv5 (You Only Look Once)
- **Languages & Libraries**: Python, OpenCV, PyTorch, LabelImg
- **Geospatial Tools**: QGIS for hillshading, LIDAR Explorer for DTM
- **Data Augmentation**: Image rotation, mirroring
- **Annotation Format**: YOLO (.txt), converted from XML using LabelImg

---

## 📁 Folder Structure

```
automatic-mound-detection-yolo/
├── data/
│   ├── raw/                  # Original DTM images
│   ├── augmented/            # Augmented images (rotated/mirrored)
│   └── labels/               # YOLO .txt annotations
├── model/
│   └── best.onnx             # Trained YOLOv5 model weights
├── results/
│   ├── predictions/          # Output predictions from test set
│   └── metrics/              # Precision, Recall, Loss graphs
├── scripts/
│   ├── extract_text_from_xml.py         # XML to TXT converter and preprocessing
│   ├── data augmentation.py              # Training script using YOLOv5
│   └── predictions.py            # Inference script
├── data.yaml                 # YOLO dataset config
├── README.md
```

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/automatic-mound-detection-yolo.git
cd automatic-mound-detection-yolo
```

### 2. Prepare the Dataset
- Download DTM images from [National Map Lidar Explorer](https://apps.nationalmap.gov/viewer/)
- Apply hillshade function using QGIS
- Annotate images with [LabelImg](https://github.com/tzutalin/labelImg)
- Convert `.xml` annotations to YOLO `.txt` format using `preprocess.py`


### 3. Run Inference
```bash
python predictions.py --weights model/best.onnx --source data/test/
```

---

## 📊 Results Summary

- **Precision:** 0.573
- **Recall:** 0.559
- **mAP@0.5:** High confidence across mound detection
- The model provides a balanced performance, with visual validation confirming accurate bounding boxes.

---

## 🧪 Dataset

- **Sources**:
  - Native American Mounds Map
  - National Map Lidar Explorer (DTM Data)
- **Samples**: 200 base images, 400+ augmented
- **Augmentations**: Rotations (90°, 180°, 270°), Horizontal/Vertical flips

---

## 📚 References

- Richards-Rissetto et al., “A 3D point cloud deep learning approach using LiDAR to identify ancient Maya archaeological sites,” 2021.
- Riley, M.A., “Automated detection of prehistoric burial mounds from DEMs,” 2009.
- Berganzo-Besga et al., “Curriculum learning strategy for archaeological mound detection from historical maps,” Scientific Reports, 2023.

---

## 🤝 Contributors

-  Lalith Vardhan Rongali
- Erik Walter Klem
- Neeraj Kondaveeti  
- Kavya Govindaraju
- Sahithi Vangala
- Sai Ruthvik Reddy Mitta
- Uha Kruthi Kommi

---

## 🌐 Future Work

- Expand training dataset using GAN-generated synthetic mound images
- Apply model across large-scale state data (e.g., Indiana)
- Generate probability heatmaps to visualize detection confidence
