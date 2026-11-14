# Image Feature Extraction in Digital Image Processing (IEEE Report)

This repository contains an academic report formatted in **IEEE Conference style** covering real-world problem solving using **Digital Image Processing (DIP)** techniques and an analytical mapping of suitable image features (*Corners, Lines, Textures, Contours, and Color Spectral features*).

---

## 📋 Assignment Overview

> *"Make a summary for several cases that can be solved by digital image processing techniques and then identify what features are suitable for these cases. Make a report in IEEE format at least 2 pages. Upload reports in PDF form to your GitHub/GitLab and paste the link of GitHub/GitLab here."*

---

## 👤 Author & Course Details

* **Name:** Farhan Rizky Alkarim
* **Student ID (NIM):** 25/568476/PA/23997
* **Course:** Pengolahan Citra Digital (Digital Image Processing)
* **Topic:** Image Feature Extraction (Corner and Line)
* **Department:** Department of Computer Science and Electronics, FMIPA, Universitas Gadjah Mada

---

## 🔍 Summary of Case Studies & Selected Features

The report analyzes **five practical domains** and justifies the selection of mathematical and geometric image features for each scenario:

| No. | Application Case Study | Suitable Image Features | Core Algorithms / Methods | Key Technical Justification |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Autonomous Driving** (Lane & Intersection Detection) | **Lines & Corners** | Hough Transform, Harris Corner Detector | Robust against dashed/occluded lane markings via parameter voting ($\rho, \theta$) and detects sharp road junctions. |
| **2** | **Biometric Fingerprint Matching** | **Corners (Minutiae) & Texture** | Ridge Bifurcation/Termination, Gabor/Spectral Analysis | Ridge endings and bifurcations exhibit multi-directional intensity gradients analogous to corner keypoints. |
| **3** | **Structural Health Monitoring** (Concrete/Road Cracks) | **Directional Lines & Texture** | Polar Hough Transform, GLCM | Quantifies crack orientation and length while distinguishing rough pavement texture from structural fractures. |
| **4** | **Medical Imaging Pathology** (MRI/CT Tumor Segmentation) | **Contours, Blobs & Texture** | Active Contours (Snakes), DoG, GLCM, LBP | Captures irregular organic tumor boundaries and heterogeneous cellular tissue textures without rigid corners. |
| **5** | **Satellite Remote Sensing** (Land Cover Classification) | **Color Spectral & Multi-scale Texture** | Color Histograms, LBP, GLCM | Separates vegetation, water bodies, and urban structures across large-scale spatial resolutions. |

---
