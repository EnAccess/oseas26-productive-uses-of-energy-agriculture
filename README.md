<p align="center">
  <a href="https://github.com/EnAccess/oseas26-productive-uses-of-energy-agriculture">
    <img
      src="https://drive.google.com/uc?id=1gtL_p7l3HbOcCzc09A7KW5d7B5qn-BDs"
      alt="Assessment and Mapping of Productive Uses of Energy (Agriculture)"
      width="640"
    >
  </a>
</p>
<p align="center">
    October 26-27 | Open Source in Energy Access Symposium Hackathon | Kigali, Rwanda
</p>

---

# Assessment and Mapping of Productive Uses of Energy (Agriculture)

Leverage GeoAI and openly accessible geospatial datasets to identify, map, and
assess productive uses of energy (PUE) within agricultural value chains.

## Abstract and goal

This task aims to leverage GeoAI and openly accessible geospatial datasets to
identify, map, and assess productive uses of energy (PUE) within agricultural
value chains. Teams will develop machine learning and computer vision models
capable of detecting, classifying, and mapping agricultural energy infrastructure
across a selected region.

As an entry point, participants can build on existing irrigation detection
datasets and methodologies to locate irrigated agricultural areas and associated
energy-dependent systems. These analyses can then be enhanced through crop
identification and yield estimation techniques, enabling estimates of
post-harvest processing and storage energy requirements for different crop types.

A key focus of the challenge is the identification of critical agricultural energy
assets. This includes:

- **Cold-chain and storage infrastructure** — refrigeration units, chillers, cold
  rooms, and temperature-controlled warehouses that support food preservation and
  reduce post-harvest losses.
- **Agro-processing infrastructure** — mills, hullers, oil presses, grain dryers,
  and other facilities that add value to agricultural products and often
  represent significant productive energy loads.

By combining remote sensing, geospatial analytics, and predictive modeling, teams
can help reveal where these assets are concentrated, where gaps exist, and where
energy access interventions may have the greatest economic impact.

## Expected outcomes

Three core deliverables:

- **The Model / Pipeline:** An open-source ML/GeoAI algorithm capable of
  detecting, classifying, or predicting the locations of agricultural processing
  or storage facilities.
- **Interactive Map / Dashboard:** A visual representation of the mapped assets,
  highlighting high-density clusters of productive energy use or critical energy
  gaps.
- **Documentation:** A brief and clear write-up describing the datasets used, the
  modeling approach, the validation methodology, accuracy metrics, and
  recommendations for scaling the solution across larger geographies or
  additional agricultural value chains.

## Required knowledge

### Stack

- **Python:** GeoPandas for vector data processing; Rasterio / GDAL for raster
  analysis.
- **Google Earth Engine** for large-scale satellite processing.
- **PostGIS** for spatial database management.
- **YOLOv8 / YOLOv11 and XGBoost** for ML and computer vision to detect and
  classify agricultural energy assets.

### Programming languages

- Python
- SQL
- JavaScript / TypeScript

### Helpful experiences

- Geospatial Analysis & Remote Sensing — for example Python, remote sensing
  analytics (e.g. Google Earth Engine), PostGIS, QGIS, GeoJSON, GeoParquet, or
  spatial SQL.
- Machine Learning & Computer Vision — for example PyTorch or TensorFlow, object
  detection models (YOLO, Detectron2), image segmentation, feature engineering,
  model evaluation and validation.
- Data Science & Analytics — for example Python, Pandas and GeoPandas, data
  cleaning and integration, statistical analysis, and predictive modeling.
- Knowledge of energy and agriculture — for example productive uses of energy,
  irrigation, agro-processing units, cold chains.
- Dashboard and mapping development skills.

## Person of contact supporting this challenge

- Nathan Williams
- Santiago Sinclair Lecaros
- Akansha Saklani

## Getting started

- Join the OSEAS Discord server: <https://community.oseas.org/>
- Introduce yourself in the `#introductions` channel and join the relevant
  channels for this challenge.
- For physical participants: bring a computer (and required adapters) for some
  hacking.
- Read the documentation:
  - [Energy Access Explorer](https://www.energyaccessexplorer.org)
  - [EAE GitHub](https://github.com/energyaccessexplorer)
  - [EAE Technical Note](https://www.wri.org/research/energy-access-explorer-data-and-methods?ap3c=IGaj6AgspJqgeKwBAGaj6AgmzCZ5Iv70Fr7H6ahniwtFr1FOgg)

We will provide examples of user queries with expected output (as training
datasets) to the registered participants.
