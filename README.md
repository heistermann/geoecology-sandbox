# Geoecology Sandbox - ein Experimentierfeld für Python in der Geoökologie

![alt text](/img/surface-runoff.jpg "Surface runoff on agricultural field")

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/heistermann/geoecology-sandbox/HEAD)

## Quick start

Klicke auf das obige **launch binder**-Badge. Damit startet eine interaktive JupyterLab-Session in der Cloud — keine weitere lokale Softwareinstallation erforderlich. **Achtung:** Es kann mehrere Minuten dauern, bis die die Binder-Umgebung startet (sogar bis zu 10 Minuten).

## Inhalte

Aktuell enthält das Repository beispielhafte Notebooks zu den Themen Klimatologie, Hydrologie und Umweltsystemeanalyse. Es wird jedoch kontinuierlich erweitert. Eine systematische Einführung in Python ist *nicht* Gegenstand des Repositories.

## Wie kann ich die Notebooks bei mir lokal laufen lassen

1. Repository klonen (oder runterladen) und ins Verzeichnis `geoecology-sandbox` wechseln:
   ```bash
   git clone https://github.com/heistermann/geoecology-sandbox.git
   cd geoecology-sandbox
   ```
2. conda environment erstellen und aktivieren:
   ```bash
   conda env create -f environment.yml
   conda activate geoecology
   ```
3. JupyterLab starten:
   ```bash
   jupyter lab
   ```

## Packages included

| Category | Packages |
|---|---|
| Core science | `numpy`, `pandas`, `scipy` |
| Visualisation | `matplotlib`, `seaborn`, `folium` |
| Geospatial (vector) | `geopandas`, `shapely`, `pyproj`, `fiona` |
| Geospatial (raster) | `rasterio`, `rasterstats` |
| Machine learning / stats | `scikit-learn`, `statsmodels` |
| Notebooks | `jupyterlab`, `ipywidgets` |
