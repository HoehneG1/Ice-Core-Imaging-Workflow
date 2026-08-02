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
flowchart TD

A[Archived or Newly Collected Ice Core Section]
    --> B[Core Preparation]

B --> C[Light Table Stabilization<br/>~10 minute warm-up]

C --> D[Manual Visual Stratigraphy Logging<br/>1 mm Depth Resolution]

D --> E[Digital Image Acquisition]

E --> F1[Transmitted Imaging<br/>Backlit<br/>Bubbles, Layering, Transparency]
E --> F2[Reflected Imaging<br/>Sidelit<br/>Fractures, Surface Features]

F1 --> G[RAW Image Storage<br/>Olympus ORF Files]
F2 --> G

G --> H[RAW Processing<br/>RawTherapee 5.12]

H --> I[Lens Correction<br/>White Balance Verification<br/>Exposure Evaluation]

I --> J[Export 16-bit TIFF Files]

J --> K[Fiji/ImageJ 1.54P]

K --> L[Image Registration and Stitching]

L --> M[Digital Core Mosaic Generation]

M --> N[Quality Control]

N --> O1[Alignment Verification]
N --> O2[Exposure Consistency]
N --> O3[Scale Verification]
N --> O4[Stratigraphic Feature Preservation]

O1 --> P[Metadata Association]
O2 --> P
O3 --> P
O4 --> P

P --> Q[Archival Dataset]

Q --> R1[RAW Images]
Q --> R2[Processed TIFF Images]
Q --> R3[Digital Mosaics]
Q --> R4[Visual Stratigraphy Logs]
Q --> R5[Metadata Tables]

R1 --> S[Repository Transfer<br/>COLDEX / Polar Programs<br/>Globus]
R2 --> S
R3 --> S
R4 --> S
R5 --> S
```
---

# Workflow Overview
```mermaid
flowchart LR

A[Ice Core Section]
--> B[Visual Stratigraphy Logging]
--> C[Standardized Imaging]
--> D[RAW Processing]
--> E[Fiji/ImageJ Stitching]
--> F[Digital Mosaic]
--> G[Quality Control]
--> H[Metadata + Archive]
--> I[Future Analysis]

C --> C1[Backlit]
C --> C2[Sidelit]

H --> H1[Globus Repository]
```


---

# Conference Resources

## Poster

📄 **Full-Resolution Digital Poster (PDF)**  
[https://github.com/HoehneG1/Ice-Core-Imaging-Workflow/blob/main/COLDEX%20REU%20Poster_Hoehne.pdf]

## Workflow Documentation

📄 **Complete Imaging and Processing Workflow (PDF)**  
[Insert workflow PDF link here]

---

# Repository Contents

This repository contains:

📁 **docs/**  
- Complete visual stratigraphy workflow documentation  
- Imaging and processing methods  

📁 **figures/**  
- Workflow diagrams  
- Example mosaic products  

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
NSF COLDEX REU Researcher  
[LinkedIn](https://www.linkedin.com/in/ghoehne/)

**Grayton Simanson**  
NSF COLDEX REU Researcher  
[LinkedIn](https://www.linkedin.com/in/gray-simanson-600a13217/)

📬 *Interested in adapting this low-cost setup for your own repository or field season? Feel free to contact us or reach out during the poster session!*

