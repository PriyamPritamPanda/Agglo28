# Ecopolis: AI-Driven Urban Biodiversity Planner

Ecopolis is an AI-powered tool designed to assist urban planners in making decisions that preserve and enhance biodiversity in urban areas. By leveraging GIS data, climate variables, and land-use information, the tool predicts the impact of urban development on ecosystems and offers actionable recommendations for sustainable and biodiversity-friendly planning.

---

## Features

### 1. GIS-Based Biodiversity Visualization
- **GIS Data Handling**: Processes publicly available GIS data to map urban areas, vegetation, water bodies, and biodiversity hotspots.
- **Biodiversity Hotspots Visualization**: Displays areas of high biodiversity and regions at risk from urban development.
- **Interactive Interface**: A user-friendly web app allows users to zoom into city maps, click on regions, and view biodiversity metrics.

### 2. Impact Prediction Model
- Predicts the impact of urban development on local biodiversity using factors like climate data, land-use changes, and vegetation cover.
- Provides biodiversity risk scores for each development scenario.

### 3. Sustainability Recommendation System
- **Green Corridors**: Identifies areas suitable for green spaces to aid wildlife movement between habitats.
- **Native Vegetation Preservation**: Highlights areas to preserve or plant native vegetation.
- **Biodiversity-Friendly Infrastructure**: Suggests infrastructure changes, such as vertical gardens and green roofs.

### 4. User Interface for Urban Planning
- Allows users to:
  - Upload urban planning data (GIS files, climate data).
  - Visualize biodiversity hotspots and areas at risk.
  - Input urban development scenarios and view biodiversity impact predictions with actionable recommendations.

---

## Technology Stack

### Frontend
- **Dash** or **Flask**: Interactive web app interface for visualization and user interaction.
- **Leaflet.js**: For rendering dynamic GIS maps.

### Backend
- **Python**: Core language for data processing, modeling, and logic implementation.
- **Geopandas**: For spatial data processing and visualization.
- **Scikit-learn**: For building the impact prediction model.
- **Pandas and NumPy**: For data handling and preprocessing.

### Data Sources
- **GIS Data**: OpenStreetMap, USGS Earth Explorer.
- **Climate Data**: WorldClim, NOAA.
- **Land Use Data**: Publicly available classification datasets.

---

## Installation and Usage

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

---

