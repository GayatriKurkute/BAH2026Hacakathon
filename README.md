# 🛰️ CloudClear AI — Generative Cloud Removal for LISS-IV Imagery

> **Bharatiya Antariksh Hackathon 2026** | *ISRO & Hack2Skill*  
> **"Restoring visibility when India needs it most."**

---

## 📌 Project Overview

During the Indian monsoon season, **60%–80% of optical satellite imagery** (such as ISRO's LISS-IV) is occluded by dense cloud cover, shadows, and atmospheric haze. This causes critical blackout periods during severe flood events (e.g., a 9-day blackout during the 2018 Kerala Floods) and compromises Kharif crop monitoring (July–September).

**CloudClear AI** is an end-to-end, generative AI pipeline engineered specifically to solve monsoon-induced satellite occlusions. Rather than applying simple visual filters, CloudClear AI performs **geometrically accurate surface reconstruction** by fusing multi-modal satellite data to produce trusted, clear surface maps.

---

## 👥 Team Information — **TEAM PRITHVI**

* **Team Leader:** Gayatri Sanjay Kurkute (*VIT Bhopal University*)
* **Team Member 1:** Khushi Mishra (*VIT Bhopal University*)
* **Team Member 2:** Hitesh Laxman Patel (*VIT Bhopal University*)
* **Team Member 3:** Deep Ganesh Patel (*VIT Bhopal University*)

---

## 💡 Key Features & Core Capabilities

1. **Automated Cloud & Shadow Masking:** Deep learning segmentation isolating clouds, cloud shadows, and atmospheric haze.
2. **Generative Surface Reconstruction:** Combines state-of-the-art Inpainting (LaMa - Large Mask Inpainting) and GANs to reconstruct missing terrain geometry.
3. **Multi-Modal Data Fusion (Monsoon-Proof USP):** Fuses optical LISS-IV imagery with **Sentinel-1 Synthetic Aperture Radar (SAR)** structural edges and historical baselines to "see through" dense clouds.
4. **Decision-Maker’s Trust Score (0–100):** A mathematical confidence score calculated per pixel block so disaster response teams know exact output reliability.
5. **Interactive GIS Dashboard:** Web interface enabling side-by-side before/after comparison and GeoTIFF export.

---

## ⚙️ Technical Pipeline