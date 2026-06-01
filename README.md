# Hi, I'm Zihao Huang 👋

**Geospatial Python engineer** building reliable land-cover simulation and raster validation workflows.

`land-cover simulation` · `GeoTIFF validation` · `AOI smoke checks` · `Dask/PyTorch pipelines`

I work on practical geospatial systems where model behavior, raster correctness, and reproducible validation all matter. My focus is turning large spatial simulation runs into inspectable, testable, and reusable Python workflows.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Dask](https://img.shields.io/badge/Dask-FC6E6B?style=flat-square&logo=dask&logoColor=white)
![xarray](https://img.shields.io/badge/xarray-1f6f8b?style=flat-square)
![rasterio](https://img.shields.io/badge/rasterio-4B8BBE?style=flat-square)
![GDAL](https://img.shields.io/badge/GDAL-5CAE58?style=flat-square)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

## 🧭 How I Work

**1. Make assumptions visible**  
Scenario settings, base-year rasters, class transitions, and demand targets should be explicit inputs, not hidden state.

**2. Test locally before scaling**  
AOI smoke checks and windowed runs catch raster issues before expensive full-region simulations.

**3. Leave evidence behind**  
Diff rasters, summary metrics, and boundary checks make model outputs easier to inspect, compare, and explain.

## 📌 Project Directions

### 🌍 Land-cover simulation workflows

Scenario-driven simulation pipelines for spatial land-cover change.

- **Builds:** year-by-year rasters, demand-driven transitions, scenario outputs
- **Focus:** reproducibility, explicit assumptions, comparison-ready artifacts

### 🛰️ Raster validation and AOI smoke checks

Fast localized checks for large GeoTIFF workflows.

- **Builds:** AOI triplets, mismatch summaries, diff rasters
- **Focus:** catching raster regressions before full-raster runs

### ⚙️ Windowed CA and Dask pipelines

Scalable CA-style simulation over tiled raster windows.

- **Builds:** chunk-aware processing, demand allocation traces, boundary diagnostics
- **Focus:** performance, edge behavior, debuggable simulation steps

## 🤝 Collaboration

I am interested in collaborations around geospatial simulation, raster processing, and reliable Python tooling for spatial data workflows.

Good fits:

- Land-cover simulation and scenario modeling
- GeoTIFF validation, raster comparison, and AOI smoke testing
- Python pipelines where correctness, reproducibility, and performance all matter

- GitHub: [@ZihaoNova](https://github.com/ZihaoNova)
- Project issues and discussions will be linked here as public repositories are published.
