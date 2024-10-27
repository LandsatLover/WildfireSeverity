
# 🔥 Tenerife Wildfire Burn Severity Estimation

![image](https://github.com/user-attachments/assets/ad8a3a21-1406-48f4-91c1-c9df6e063b92)


**Tenerife Wildfire Burn Severity** is a geospatial project focused on estimating and visualizing the burn severity of a wildfire that occurred in Tenerife, Canary Islands, on August 15, 2023. The project leverages QGIS and the Qgis2threejs plugin to create an interactive 3D map, showcasing burn severity through various severity classes. Using NBR ratio and the K-means algorithm to extract the burned-unburned mask and classifying the result by quantiles from Low severity to High severity. Other indexes can be applied to compare the severity, as they can be the burned area index (BAI) or medium infra-red burn index (MIRBI) but for this landscape NBR has demonstrated the best performance. The terrain elevation plays a crucial role in the fire evolution, as we can see in areas where is a steep slope.


The plugin also allows you to take a camera tour of the entire scene, customizing the points where the camera has to pass.

## 🎨 Preview

[Live Demo](https://landsatlover.github.io/WildfireSeverity/)

## 🚀 Features
- 🌍 Interactive 3D map powered by Qgis2threejs and three.js
- 🔥 Burn severity classification using the NBR index and K-means clustering
- 🌐 Multiple layers and map controls for customized exploration
- 📍 North arrow and navigation controls for better orientation
- 📊 Burn severity categories from Low to Extreme

## 📂 Project Structure
- `index.html`: Main HTML file with map and legend structure
- `Qgis2threejs.js`: JavaScript file that manages 3D rendering using Qgis2threejs
- `Qgis2threejs.css`: CSS for styling the map and 3D viewer components
- `visor.html`: 3D viewer embedded page generated from QGIS
- `sever_incendios.qgz`: QGIS project file used for generating the 3D scene and data processing
- `scene.js`: Generated scene file containing spatial data for the burn severity visualization

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/LandsatLover/WildfireSeverity.git
   ```
2. Open `index.html` in your browser to view the map and start exploring the burn severity zones.

## 🔄 Future Updates
Planned improvements include:

- 📈 Advanced 3D charts and statistics for burn severity analysis
- 🗂️ Layer selector to toggle between different severity classes and additional datasets

## 📫 Connect with Me
- **Email**: [rubenambientalesupv@gmail.com](mailto:rubenambientalesupv@gmail.com)
- **LinkedIn**: [Rubén Vicente Martínez](https://www.linkedin.com/in/rubenvicentemartinez)
