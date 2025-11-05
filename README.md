# 🇵🇱 AGH Habitat-PL
*A starter repository for the course **Machine Learning for Space Applications** (AGH 2025/26)*

---

## 🎯 Project goal
Students will build an **AI pipeline to classify natural habitats across Poland** using **Google Satellite Embeddings** and open geospatial reference data (e.g., CORINE, Natura 2000).  
Each lab adds one methodological layer — from data access to deep learning and spatial validation.

---

## 🧪 Lab 1 — Data Access & Visualization

**Objective:**  
Learn to authenticate Google Earth Engine (GEE) via the Python API (in Colab),  
load the *Satellite Embedding V1* dataset, clip it to Poland, visualize the embeddings as pseudo-RGB,  
and explore their structure through simple projections.

---

### 🧰 Environment setup (Colab)
```python
!pip install -q git+https://github.com/<your-team>/agh-habitat-pl.git
