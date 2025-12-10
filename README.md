# Nagaad – Kismayo Investments Interactive Map

This repository hosts the **interactive web map of Nagaad (SURP-II) and SURP-I infrastructure investments in Kismayo City, Somalia**.  
The map visualizes **completed, ongoing, and design-ready investments**, enabling easy exploration, filtering, and sharing with stakeholders.

## 🌍 Live Map
👉 **Interactive Map:**  
https://nagaadproject.github.io/nagaad-kismayo-map/


---

## 🗺️ Map Content

The map includes the following layers for **Kismayo City**:

### ✅ SURP-II Investments
- **Completed roads and bridges**
- **Ongoing drainage and building works**
- **Design-ready (Ready Investments)**

### ✅ Key Infrastructure (selective)
- Airport
- Hospital
- Stadium 
- IDPs   
_(Additional facilities may be added over time)_

---

## 🧭 How to Use the Map

- Use the **layer control (left panel)** to:
  - Toggle projects by **Package** and **Status**
- Click on any **road or facility** to:
  - View project details
  - Automatically zoom to the feature
- Switch between **basemaps** (street / satellite)
- Use the **reset/home button** to return to full city view

---

## 🛠️ Data & Technology

- **Data prep & styling:** QGIS  
- **Web export:** qgis2web (Leaflet)  
- **Format:** GeoJSON (EPSG:4326)  
- **Hosting:** GitHub Pages (static site)

This is a **static web map**: no backend or database is required.

---

## 🔄 Update Workflow (For Editors)

1. Update or append features in the Kismayo GeoJSON dataset
2. Reload data in QGIS
3. Re-export using **qgis2web**
4. Replace files in this repository
5. Commit changes → map auto-updates online

_No reconfiguration or redeployment required._

---

## 📌 Notes

- This map is intended for **planning, monitoring, and communication** purposes.
- Geometries represent approximate project alignments and may not reflect as-built drawings.
- The structure is designed to scale and will be replicated for **other cities**.

---

## 🤝 Credits & Ownership

Developed under the **Somali Urban Resilience Project (SURP-II / Nagaad)**  
Ministry of Public Works, Reconstruction & Housing (MPWR&H) – Somalia with the support of World Bank Team and Kismayo Municipality PIU.

Prepared by:  
**Monitoring & Evaluation Team / Nagaad Project**

---

## 📬 Contact

For corrections, updates, or replication for other cities, please contact the Nagaad Project Coordination Unit.

