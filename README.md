# 🐝 Honeybee Functional Connectivity in East Africa

## 🌍 A Circuit-Theory-Based Framework for Pollinator Conservation

This repository contains spatial datasets and derived geospatial products from the study:

> Meltus, Q. J., et al. (2024). *A circuit-theory-based framework for modeling honeybee (*Apis mellifera*) functional connectivity to guide conservation corridors across East Africa using ecological drivers.*

These datasets support a movement-based, ecological connectivity framework for pollinator conservation across Kenya, Uganda, and Tanzania.

---

## 🧭 Overview

Maintaining pollinator connectivity in rapidly transforming landscapes is critical for ecosystem stability and food security. This work integrates species distribution modeling, remote sensing phenology, and landscape fragmentation into a circuit-theory-based resistance framework to identify functional honeybee corridors across East Africa.

The outputs provide a spatially explicit foundation for:
- Conservation corridor design
- Restoration prioritization
- Transboundary ecological planning
- Pollinator-focused landscape management

---

## 📦 Repository Contents

This repository contains the following key spatial datasets:

### 🧱 Composite Resistance Surface
A unified landscape resistance layer integrating:
- Honeybee habitat suitability (MaxEnt model)
- Flowering Index (FI)
- Floral fragmentation index (Frag)

📌 Interpretation:  
Represents **movement cost for honeybee dispersal across landscapes**

---

### 🌸 Flowering Index (FI)
A phenology-derived metric of floral resource availability based on MODIS NDVI time series.

Key characteristics:
- Captures seasonal flowering pulses
- Derived using harmonic regression of NDVI (2000–2025)
- Includes wet and dry seasonal stratification
- Combines peak vegetation productivity and amplitude variability

📌 Interpretation:  
Represents **spatiotemporal floral resource intensity**

---

### 🧩 Fragmentation Index (Frag)
A scale-dependent landscape structure metric computed at 1 km resolution.

Key characteristics:
- Based on floral patch continuity
- Range: 0 (connected) → 1 (highly fragmented)
- Reflects structural barriers to movement

📌 Interpretation:  
Represents **local landscape isolation and structural resistance**

---

## 🌍 Study Region

The spatial extent covers East Africa:
- 🇰🇪 Kenya  
- 🇺🇬 Uganda  
- 🇹🇿 Tanzania  

Key ecological zones include:
- Eastern Afromontane forests  
- Lake Victoria basin  
- Miombo woodlands  
- Semi-arid savanna ecosystems  

---

## 🧠 Methodological Framework

This dataset is built on a multi-layer ecological modeling framework:

### Core Components
- 🌿 MaxEnt habitat suitability modeling  
- 🌸 MODIS NDVI-derived phenological analysis  
- 🌧️ CHIRPS precipitation-based seasonality classification  
- 🧱 Landscape fragmentation analysis  
- ⚡ Circuit theory (Circuitscape) connectivity modeling  

### Integrated Model
All layers were combined into a composite resistance surface:

- Habitat suitability → ecological preference  
- Flowering index → resource availability  
- Fragmentation → movement constraints  

📌 Outcome:  
A **probabilistic, multi-path connectivity surface** representing realistic pollinator movement.

---

## 🚀 Key Outputs

This repository enables reconstruction and reuse of:

- Functional honeybee movement corridors  
- High-resistance ecological bottlenecks  
- Conservation vs restoration corridor classification  
- Transboundary connectivity hotspots  
- Landscape permeability gradients  

---

## 📊 Applications

These datasets can be used for:
- Pollinator corridor planning
- Landscape restoration prioritization
- Biodiversity conservation strategies
- Agroecological landscape design
- Connectivity modeling for other mobile species

---

## 📁 Data Format

- File type: GeoTIFF (.tif)
- Projection: WGS84 (EPSG:4326)
- Resolution: 1 km harmonized spatial grid

---

## 💻 Usage Example

### Clone repository
```bash
git clone https://github.com/[your-username]/honeybee-connectivity-east-africa.git
