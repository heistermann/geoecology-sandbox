# geoecology-sandbox
Sandbox for teaching Python and Geoecology.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/heistermann/geoecology-sandbox/HEAD)

## Quick start

Click the **Binder** badge above to launch an interactive JupyterLab session in the cloud — no local installation required.

## Repository layout

```
environment.yml          # Conda environment (used by Binder)
notebooks/
  01_introduction.ipynb  # Introductory notebook: data exploration, plotting, mapping
data/
  species_observations.csv  # Sample tree-species observation dataset
```

## Running locally

1. Clone the repository and change into it:
   ```bash
   git clone https://github.com/heistermann/geoecology-sandbox.git
   cd geoecology-sandbox
   ```
2. Create and activate the conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate geoecology
   ```
3. Start JupyterLab:
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
