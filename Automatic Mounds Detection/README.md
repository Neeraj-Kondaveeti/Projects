
# 🏔️ Automatic Mound Detection using Machine Learning

This project aims to automatically detect archaeological mounds from Digital Terrain Model (DTM) data using supervised machine learning techniques. By combining geospatial processing with classification models, we automate the identification of topographic anomalies that resemble man-made mounds.

---

## 📌 Project Overview

Archaeological mound detection traditionally requires manual interpretation of topographic maps or satellite imagery. In this project, we automate that process using:
- Digital Terrain Model (DTM) data as input
- Feature extraction (elevation, slope, curvature)
- A trained machine learning model (e.g., Random Forest)
- Output as spatial prediction layers or labeled maps

---

## 🧠 Technologies Used

- **Languages & Libraries**: Python, NumPy, Pandas, scikit-learn, Matplotlib
- **Geospatial Tools**: Rasterio, GeoPandas, Folium, QGIS
- **ML Techniques**: Feature extraction, Random Forest classification, model evaluation
- **Data Format**: GeoTIFF (DTM), CSV, Shapefiles, and optionally .geojson

---

## 📁 Folder Structure

```
automatic-mound-detection/
├── data/
│   ├── raw/                # Original DTM and labeled mound data
│   └── processed/          # Cleaned, transformed datasets
├── notebooks/
│   └── mound_detection_analysis.ipynb  # Main Jupyter notebook
├── src/
│   ├── preprocess.py       # Data preprocessing and feature extraction
│   ├── model.py            # ML model training and evaluation
│   └── predict.py          # Inference and prediction mapping
├── results/
│   ├── plots/              # Visualizations
│   └── predictions/        # Output rasters or shapefiles
├── models/                 # Saved model files
├── run.py                  # Main script to run the pipeline
├── requirements.txt
├── LICENSE
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/automatic-mound-detection.git
cd automatic-mound-detection
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Prepare Data
- Add raw DTM raster files in `data/raw/`
- Add labeled mound data (as shapefiles or CSV)

### 4. Run Notebook or Script
```bash
# Option 1: Run Jupyter notebook
jupyter notebook notebooks/mound_detection_analysis.ipynb

# Option 2: Run full pipeline
python run.py
```

---

## 📊 Results

- 📈 Model Accuracy: ~XX% (based on Random Forest evaluation)
- 📍 Output: GeoTIFF mask / shapefile showing predicted mound locations
- 🗺️ Visualizations available in `/results/plots/`

Example:

![Example Map](results/plots/mound_overlay_example.png)

---

## 🧪 Sample Dataset

> Due to size constraints, we provide a small sample dataset in `data/sample/`. For full-scale testing, refer to the sources mentioned below or request access to larger terrain datasets.

---

## 📚 References

- Digital Elevation Model: SRTM or local DTM sources
- Archaeological datasets provided by research collaborators or open data portals

---

## 🤝 Contributors

- Neeraj Kondaveeti  
- [Your team members, if any]

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌐 Acknowledgements

Special thanks to faculty mentors and researchers who guided the feature engineering and geospatial processing phases of this project.
