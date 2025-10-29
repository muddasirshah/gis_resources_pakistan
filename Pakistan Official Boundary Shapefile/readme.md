# 🇵🇰 Pakistan Official Boundary Shapefile

This repository contains the **official administrative boundary shapefile of Pakistan**, including both **district** and **province-level** boundaries.  
The same dataset is also hosted as a **Google Earth Engine (GEE) asset** for easy integration into geospatial workflows.

---

## 📂 Repository Contents

| File | Description |
|------|--------------|
| `Pakistan_Official_Boundary.shp` | Main shapefile containing the district and province boundaries. |
| `Pakistan_Official_Boundary.dbf` | Attribute table containing district and province names. |
| `Pakistan_Official_Boundary.shx` | Shapefile index. |
| `Pakistan_Official_Boundary.prj` | Projection information. |

---

## 🗺️ Description

The shapefile represents the **official administrative boundaries** of Pakistan, suitable for GIS, remote sensing, and spatial data analysis applications.  
It contains two key attributes:

| Column | Description |
|---------|-------------|
| `DISTRICT` | Name of the district. |
| `PROVINCE` | Name of the province each district belongs to. |

---

## 🌐 Google Earth Engine Asset

The same boundary data is available as a hosted asset in **Google Earth Engine (GEE)**:
var Pakistan = ee.FeatureCollection("projects/ee-muddasir-shah/assets/Pakistan_Official_Boundary");
