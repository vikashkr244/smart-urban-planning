# 🏙 Smart Urban Planning via Satellite Imagery + Geospatial Data

## 📖 Overview
Smart Urban Planning is an end-to-end pipeline for detecting **illegal constructions**, **deforestation**, and **urban sprawl** using **satellite imagery** and **geospatial data**.

It leverages:
- 🛰 **Remote Sensing** — Sentinel-2, Landsat-8  
- 🌍 **GIS Layers** — Roads, Water, Vegetation  
- 🤖 **Deep Learning Models** — UNet & Siamese Networks  
- 🧭 **Visualization** — Streamlit, Leaflet, Mapbox  

---

## 🧠 Features
✅ Multi-temporal change detection  
✅ Automatic preprocessing (cloud masking, co-registration)  
✅ Urban growth heatmaps & metrics  
✅ Interactive dashboard with time-lapse video analytics  
✅ Docker + Kubernetes + CI/CD ready  

---

## ⚙️ Setup Instructions
```bash
git clone https://github.com/yourusername/smart-urban-planning.git
cd smart-urban-planning
python -m venv venv
source venv/bin/activate
pip install -r frontend/streamlit_app/requirements.txt
cd frontend/streamlit_app
streamlit run app.py
```

---

## 🧱 Folder Structure
```
smart-urban-planning/
├── src/                
├── data/               
├── models/             
├── frontend/           
├── scripts/            
├── tests/              
├── ci/                 
├── docs/               
└── infra/              
```

---

## 🧪 Running Tests
```bash
pytest tests/ -v
```

---

## 📄 License
Licensed under the **MIT License** — see [LICENSE](LICENSE).

---

## 🤝 Contributors
- **Vikash Kumar** — Data & Model Engineering  
- **Contributors Welcome!** Fork and submit a PR.
