# Urban Heat Island Monitoring and Priority Analysis Platform

## About
Welcome to the **Urban Heat Island Monitoring and Priority Analysis Platform**, an innovative geospatial solution to combat urban heat islands (UHI). Leveraging satellite imagery, street-level mapping data, and advanced computational tools, this platform provides real-time monitoring and actionable insights for urban heat mitigation.

## Features
- **High-Resolution Geospatial Analysis**: Utilize Google Earth Engine (GEE) and OpenStreetMap to identify areas affected by the UHI effect.
- **Rooftop Digitization**: Pinpoint key rooftops and urban surfaces for targeted mitigation strategies.
- **Real-Time Monitoring**: Deliver insights on land surface temperature variations through an interactive website.
- **Effective Mitigation Solutions**: Prioritize high-impact areas and recommend sustainable practices to reduce UHI effects.

---

## Repository Structure
```
.
├── app/                    # Source code for Flask applications
│   ├── uhi_analysis.py       # Analysis module for UHI monitoring
│   ├── rooftop_mapping.py    # Rooftop digitization and priority analysis
├── data/                   # Sample datasets and scripts for data handling
├── static/                 # Static files (maps, visualizations)
├── templates/              # HTML templates for Flask apps
├── requirements.txt        # Python dependencies
├── README.md               # Documentation
```

---

## Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip (Python package installer)
- Google Earth Pro

---

## Installation

Clone this repository:
```bash
git clone https://github.com/yourusername/Urban-Heat-Island-Monitoring.git
cd Urban-Heat-Island-Monitoring
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```

---

## Usage
### Urban Heat Island Monitoring
1. Navigate to the `app/` directory:
   ```bash
   cd app
   ```
2. Run the Flask app for UHI monitoring:
   ```bash
   python uhi_analysis.py
   ```
3. Open your browser and visit `http://localhost:5000`.
4. Upload satellite imagery or geospatial data to view heat maps and temperature variations.

### Rooftop Priority Analysis
1. Run the rooftop digitization module:
   ```bash
   python rooftop_mapping.py
   ```
2. Access the platform to visualize key rooftops and areas suitable for green initiatives like rooftop gardens or reflective surfaces.

---

## How It Works
The platform combines multiple geospatial tools to provide comprehensive urban heat island analysis:

1. **Data Integration**:
   - High-resolution satellite imagery is processed using Google Earth Engine.
   - OpenStreetMap provides detailed street-level mapping.

2. **Analysis**:
   - Land Surface Temperature (LST) data is analyzed to identify hotspots.
   - Rooftop digitization identifies critical areas for heat mitigation strategies.

3. **Visualization**:
   - An intuitive web interface displays heat maps, rooftop priorities, and mitigation recommendations in real-time.

---

## Dependencies
The dependencies are listed in `requirements.txt` and include:
- Flask
- Google Earth Engine Python API
- OpenCV
- pandas
- matplotlib
- geopandas

To install dependencies, use:
```bash
pip install -r requirements.txt
```

---

## Tools
- **OpenStreetMap**: Provides detailed geospatial mapping.
- **Google Earth Engine**: Processes satellite imagery for land surface temperature analysis.
- **Python & Flask**: Backend development and web interface.
- **Java**: For integration with Google Earth Pro.

---

## Outcomes
This project delivers:
1. High-impact visualization and analysis of urban heat island effects.
2. Sustainable urban planning solutions like rooftop gardens, reflective materials, and vegetation corridors.
3. A user-friendly platform to empower policymakers, urban planners, and researchers.

---

Experience the power of data-driven urban cooling with the **Urban Heat Island Monitoring and Priority Analysis Platform**.
