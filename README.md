# Integrated Pipeline Patrol Analytics System (IPPAS)

### Modernizing Aerial Pipeline Integrity Monitoring Through Geospatial Automation

**Author:** Ashley Mitchell  

**Location:** Pittsburgh, Pennsylvania  
**Date:** October 2025  
**Status:** Concept & White Paper Release

---

## 🛰️ Overview

**IPPAS** — *Integrated Pipeline Patrol Analytics System* — is a proposed open, modular framework for automating the analysis and reporting of aerial pipeline patrol data.  

Drawing on nearly a decade of flight operations experience (2012–2018) within the natural-gas transmission sector, IPPAS demonstrates how GPS flight tracks, leak-detection telemetry, and observer inputs can be fused into a unified geospatial integrity workflow.  

The project seeks to replace manual, time-intensive Word and Excel-based patrol reports with automated, verifiable outputs that align with **PHMSA Traceable–Verifiable–Complete (TVC)** standards.

---

## 📘 White Paper

📄 **[Integrated Aerial Pipeline Patrol Analytics: From GPS Tracks to Real-Time Leak Detection and HCA Intelligence (PDF)](docs/Mitchell_2025_Integrated_Aerial_Pipeline_Patrol_Analytics.pdf)**  

The included white paper outlines:

1. The historical context of aerial patrol workflows (2013–2019)  
2. Design architecture for a modular, Python-based analytics framework  
3. Case simulation of a 6-hour, 300-mile patrol  
4. Demonstrated efficiency gains (95%+ reporting time reduction)  
5. Recommendations for industry adoption and AI integration  

---

## 🔧 Concept Summary

| Component                 | Function                                                                |
|---------------------------|-------------------------------------------------------------------------|
| **Flight-Track Module**   | Processes GPS/ADS-B data to map coverage and identify off-line segments |
| **Leak-Telemetry Parser** | Synchronizes Apogee or similar leak-detector streams with flight data   |
| **Observer Interface**    | Tablet-based input for threats, encroachments, and photos               |
| **Analytics Engine**      | Automates report generation (GeoPackage, PDF, XLSX)                     |
| **Dashboard Integration** | Optional Streamlit/ArcGIS dashboard for visualization and QA/QC         |

All proposed modules rely exclusively on open-source tools such as **GeoPandas**, **Shapely**, **Folium**, **Pandas**, and **ReportLab**.

---

## 🧭 Purpose and Vision

- **Reduce reporting time** from 3–4 hours per patrol to under 10 minutes  
- **Provide quantitative coverage verification** for PHMSA audits  
- **Enhance leak-response time** through sensor-synchronized geolocation  
- **Create an open-standard data model** usable by both manned and unmanned patrols  
- **Encourage collaboration** among operators, regulators, and data scientists  

---

## 🤝 Collaboration

This repository is intended as a **public technical reference** and concept demonstration.  
Contributors are welcome to:

- Develop prototype Python modules or dashboards  
- Test workflow reproducibility on sample datasets  
- Propose data standards or extensions for unmanned aerial systems (UAS)

Please open a **Discussion** or **Issue** for feedback and collaboration ideas.

---

## 🧾 Citation

If referencing this work, please cite as:

> Mitchell, A. (2025). *Integrated Aerial Pipeline Patrol Analytics System (IPPAS):  
> From GPS Tracks to Real-Time Leak Detection and HCA Intelligence.*  
> DOI (forthcoming). GitHub Repository: https://github.com/ashleyreagan/IPPAS

---

## 🏷️ Keywords

`pipeline-integrity` `aerial-surveillance` `geospatial-analytics`  
`leak-detection` `aviation` `python` `PHMSA` `environmental-monitoring`

---

## 📜 License

Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International (CC BY-NC-SA 4.0)  
You are free to share and adapt this work for non-commercial purposes with attribution.

---

## ✍️ Author Contact

**Ashley Mitchell**  

Pittsburgh, Pennsylvania 
