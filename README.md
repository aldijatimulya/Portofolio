# 🛰️ Aldi Jati Mulya — Remote Sensing & WebGIS Research Platform

**Live Website:** https://aldijatimulya.github.io/aldi-research-webgis/  
**WebGIS Dashboard:** https://aldijatimulya.github.io/aldi-research-webgis/webgis.html

---

## 📋 Tentang Platform

Platform portofolio dan dashboard WebGIS untuk riset penginderaan jauh, pemantauan iklim, kebencanaan, dan analisis spasial di wilayah Sumatera Selatan, Indonesia.

**Peneliti:** Aldi Jati Mulya, M.Si  
**Institusi:** Universitas Sriwijaya  
**GEE Project:** `wijaya-474816`

---

## 🗺️ Proyek Riset Terintegrasi

| Proyek | GEE App | Dataset | Area |
|--------|---------|---------|------|
| 🌵 Drought Classification | [drought-oki](https://wijaya-474816.projects.earthengine.app/view/drought-oki) | MODIS MOD13Q1 · CHIRPS | OKI |
| 🔥 dNBR Fire Severity | [fire-severity-oki](https://wijaya-474816.projects.earthengine.app/view/fire-severity-oki) | Landsat 8 C02 L2 | OKI |
| 🌡️ UHI & NDVI | *(coming soon)* | Landsat 8 C02 T1 | OKI |
| 💧 SEBAL Evapotranspirasi | [sebal-eta-perigi](https://wijaya-474816.projects.earthengine.app/view/sebal-eta-perigi) | Landsat 8 · ERA5-Land | Lokasi Perigi |
| 🌊 Flood Analysis | [flood-palembang](https://wijaya-474816.projects.earthengine.app/view/flood-palembang) | Sentinel-1/2 · SRTM | Palembang |
| 🌧️ CHIRPS Rainfall | [chirps-gambut](https://wijaya-474816.projects.earthengine.app/view/chirps-gambut) | CHIRPS Daily | Gambut Degree |
| 🛰️ MODIS LST | [modis-lst-oki](https://wijaya-474816.projects.earthengine.app/view/modis-lst-oki) | MODIS MOD11A2 | OKI |

---

## 📁 Struktur File

```
aldi-research-webgis/
├── index.html      → Halaman utama portofolio
├── webgis.html     → Dashboard WebGIS interaktif
├── 404.html        → Halaman error
└── README.md       → Dokumentasi ini
```

---

## 🚀 Cara Deploy (GitHub Pages)

1. Fork atau upload semua file ke repository GitHub
2. Masuk ke **Settings → Pages**
3. Source: **Deploy from branch → main → / (root)**
4. Klik **Save** → tunggu 1-2 menit
5. Website aktif di `https://username.github.io/nama-repo/`

---

## 🛠️ Teknologi

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Peta:** Leaflet.js, Google Earth Engine Apps (iframe embed)
- **Chart:** Chart.js
- **Analisis:** Google Earth Engine JavaScript API
- **Hosting:** GitHub Pages (gratis)
- **Font:** Google Fonts (Space Mono, DM Sans, Syne)

---

## 📊 GEE Datasets

```javascript
// NDVI & Drought
'MODIS/006/MOD13Q1'          // NDVI 250m 16-day
'UCSB-CHG/CHIRPS/DAILY'      // Rainfall 5km daily

// Fire Severity
'LANDSAT/LC08/C02/T1_L2'     // Landsat 8 SR 30m

// Flood Analysis  
'COPERNICUS/S1_GRD'          // Sentinel-1 SAR
'COPERNICUS/S2_SR_HARMONIZED'// Sentinel-2 SR
'USGS/SRTMGL1_003'           // DEM 30m

// LST
'MODIS/061/MOD11A2'          // LST 1km 8-day

// SEBAL ETa
'LANDSAT/LC08/C02/T1_L2'     // Landsat 8 SR
'ECMWF/ERA5_LAND/DAILY_AGGR' // ERA5-Land

// Assets
'projects/wijaya-474816/assets/OKI'
'projects/wijaya-474816/assets/Gambut_Degree'
'projects/wijaya-474816/assets/Palembang'
'projects/wijaya-474816/assets/Lokasi_Perigi'
```

---

## 📞 Kontak

- **LinkedIn:** [aldijatimulya](https://www.linkedin.com/in/aldijatimulya/)
- **GEE Project:** wijaya-474816
- **Lokasi:** Prabumulih, Sumatera Selatan, Indonesia

---

*© 2026 Aldi Jati Mulya · Remote Sensing & GIS Researcher*
