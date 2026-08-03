# Standardizing Quantitative Visual Stratigraphy for Digital Archiving of Ice Cores

## Project Overview

This repository documents the development of a low-cost, reproducible workflow for creating high-resolution digital visual stratigraphy records of ice cores.

The workflow integrates standardized digital photography, RAW image processing, image stitching, manual stratigraphic logging, and metadata documentation to create depth-referenced digital archives suitable for long-term curation and future scientific analysis.

The workflow was developed using archived ice core sections from the Allan Hills Blue Ice Area, Antarctica, and is designed to be transferable to both archived and newly collected ice cores.

---

## Project Information

**Authors**  
Gary Hoehne  
Grayton Simanson  

**Advisors**  
Richard Nunn  
Curt LaBombard  

**Development Dataset**  
AH2416 — Allan Hills Blue Ice Area, Antarctica  

**Program**  
NSF COLDEX Research Experience for Undergraduates (REU)

---

```mermaid
flowchart LR

A[Ice Core Section]
--> B[Visual Stratigraphy Logging]
--> C[Standardized Imaging]

C --> C1[Transmitted Imaging<br/>Backlit]
C --> C2[Reflected Imaging<br/>Sidelit]

C1 --> D[RAW Processing]
C2 --> D[RAW Processing]

D --> E[Fiji/ImageJ Stitching]
--> F[Digital Mosaic Generation]
--> G[Quality Control]
--> H[Metadata + Archive]
--> I[Future Analysis]

H --> H1[Globus Repository]
```


---

# Conference Resources

## Poster

📄 **Full-Resolution Digital Poster (PDF)**  
[2026 Coldex Poster](https://github.com/HoehneG1/Ice-Core-Imaging-Workflow/blob/main/COLDEX%20REU%20Poster_Hoehne.pdf)

## Workflow Documentation

📄 **Complete Imaging and Processing Workflow (PDF)**  
[Workflow Version 1.0]

---

# Repository Contents

This repository contains:

📁 **docs/**  
- [Complete visual stratigraphy workflow documentation](https://github.com/HoehneG1/Ice-Core-Imaging-Workflow/blob/main/Workflow%201.pdf)  
- Imaging and processing methods  

📁 **figures/**  
- Workflow diagrams  
- [Example mosaic products](https://github.com/HoehneG1/Ice-Core-Imaging-Workflow/tree/main/Mosaics) 

📁 **templates/**  
- Visual stratigraphy logging templates  
- Metadata templates  

📁 **examples/**  
- Example processed mosaics  
- Example visual stratigraphy products  

---

# Workflow Summary

The workflow consists of:

1. Standardized ice core preparation and imaging
2. Dual-illumination photography:
   - Transmitted (backlit)
   - Reflected (sidelit)
3. RAW image processing and calibration
4. Image stitching and digital mosaic generation
5. Visual stratigraphy documentation at 1 mm resolution
6. Quality control and metadata preservation
7. Preparation for long-term archival and future analysis

---

# Future Applications

The resulting digital visual stratigraphy records provide a foundation for integration with additional ice core datasets, including:

- Hyperspectral imaging (HSI)
- Electrical conductivity measurements (ECM)
- Stable isotope measurements
- Geochemical analyses
- Automated image-based feature detection

---

## Contact and Collaboration

This workflow was developed through the NSF COLDEX Research Experience for Undergraduates (REU) program. Questions regarding digital visual stratigraphy methods, workflow development, or potential collaboration are welcome.

**Gary Hoehne**  
NSF COLDEX REU Student  
[Email](mailto:ghoehne1@southernct.edu) | [LinkedIn](https://www.linkedin.com/in/ghoehne/)

**Grayton Simanson**  
NSF COLDEX REU Student  
[Email](mailto:g_simanson2024@coloradocollege.edu) | [LinkedIn](https://www.linkedin.com/in/gray-simanson-600a13217/)


