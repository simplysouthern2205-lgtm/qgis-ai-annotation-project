![Annotation Example](maps/annotated_example.png)


[README.md.txt](https://github.com/user-attachments/files/26191657/README.md.txt)
# Satellite Image Annotation Project (AI Training)


## Project Overview
This project demonstrates geospatial annotation used for training AI models on satellite imagery. It simulates real-world workflows used in GIS and machine learning for detecting roads and buildings.

---

## Sample Data
Raw satellite images used for annotation:

- data/images/image1.png  
- data/images/image2.png  
- data/images/image3.png  

---

## What I Did
- Collected satellite-style imagery for analysis
- Created structured annotation data using GeoJSON
- Labeled roads (LineString) and buildings (Polygon)
- Organized data into a clean, reusable dataset format

---

## Annotation Details
- Annotated multiple satellite images
- Included metadata such as image IDs and confidence scores
- Structured data for machine learning workflows

**Example fields:**
- `type` → feature category (road, building)  
- `image_id` → source image reference  
- `confidence` → annotation confidence score  

---

## Tools Used
- GeoJSON  
- GIS concepts (vector data, coordinates)  
- Manual annotation (simulating tools like QGIS)

---

## Dataset Structure

qgis-ai-annotation-project
│
├── data
│ ├── images
│ │ ├── image1.png
│ │ ├── image2.png
│ │ └── image3.png
│ │
│ └── annotations
│ └── annotations.geojson
│
├── maps
│ └── annotated_example.png
│
├── docs
│ └── workflow.md
│
└── README.md


---

## Use Case
This dataset structure can be used to train AI models for:
- Road detection  
- Building detection  
- Urban mapping  
- Geospatial analysis  

---

## Note
This is a sample project created for portfolio purposes to demonstrate geospatial annotation and AI training workflows.
