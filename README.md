# BA-780-Fall25-Teamproject-MBTA-crime-analysis
This repository contains my individual **public submission** for the team project.  
It includes the **final Jupyter notebook** and a summary of our analysis of **crime patterns near MBTA stations** across multiple time periods.


### 📘 Overview  
This project measures how crime concentrates around MBTA stations in Boston and turns the results into clear, practical steps for safer transit for riders and staff. Our goal is to focus effort where it matters most and show measurable progress. 

---

## 🧑‍🤝‍🧑 Team Contributors  
- **Yanlun Li** (repo owner)  
- **Abbinaya Kalidhas**  
- **Fei Han**  
- **Kai Tran**  
- **Mohamad Gong**  
- **Rita Feng**

---

## 🧾 Executive Summary

### **Purpose and Methods**  
We combine **Boston Police incident reports from 2016–2025** with **MBTA station locations** and generate **1-, 3-, and 5-minute walking isochrones** to measure how crime concentrates near transit.  
Spatial joins link incidents to these rings, and we analyze trends by **offense type**, **time**, **station**, **line**, and **district**.

### **Key Findings**  
- Citywide crime fell roughly **30–35% during 2020–23** and has only partially rebounded in **2024–25**.  
- About **40% of incidents** occur within a **five-minute walk** of stations, with the **three-minute ring** carrying the largest share.  
- **Larceny and theft** are overrepresented near stations compared with the citywide baseline.  
- Stations on the **Silver and Green lines**—particularly *Park Street*, *Union Park Street*, and *Nubian*—record the highest counts across all rings. 
- Incidents **cluster between midday and early evening** on weekdays.

![Citywide Offense Composition by Year](figures/Offense%20Category.png)

### **Recommendations**  
- Focus visible patrols and environmental improvements within the **three-minute walkshed** of high-volume transfer stations.  
- Develop **dashboards** that integrate crime, ridership, and time-of-day data to aid deployment decisions.  
- Coordinate efforts between **MBTA Transit Police** and **Boston Police districts** around shared hotspots.  
- Refresh this analysis annually to track changes and report progress.

---
