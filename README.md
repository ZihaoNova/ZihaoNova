# Hi, I'm Zihao Huang 👋

Geospatial Python engineer building land-cover simulation, raster validation, and scalable spatial modeling workflows.

Currently focused on **🌍 land-cover simulation** · **🛰️ raster workflows** · **⚙️ Dask/PyTorch pipelines**

I work on practical geospatial systems where model behavior, raster correctness, and reproducible validation all matter. My goal is to turn large spatial simulation workflows into inspectable, testable, and reusable Python tools.

## 🧭 Focus

- Scenario-driven land-cover simulation and spatial change modeling
- GeoTIFF validation workflows with AOI-first smoke checks
- Windowed cellular automata over scalable Dask/PyTorch pipelines
- Reproducible artifacts for comparing, debugging, and explaining outputs

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Dask](https://img.shields.io/badge/Dask-FC6E6B?style=flat-square&logo=dask&logoColor=white)
![xarray](https://img.shields.io/badge/xarray-1f6f8b?style=flat-square)
![rasterio](https://img.shields.io/badge/rasterio-4B8BBE?style=flat-square)
![GDAL](https://img.shields.io/badge/GDAL-5CAE58?style=flat-square)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

## 🧩 How I Think About Geospatial Simulation

```mermaid
flowchart LR
    A["Scenario inputs"] --> B["Raster preprocessing"]
    B --> C["AOI smoke checks"]
    C --> D["CA / Dask simulation"]
    D --> E["Validation artifacts"]
    E --> F["Interpretable outputs"]

    C -. "fast feedback" .-> B
    E -. "debug evidence" .-> D
```

## 📌 Portfolio Notes

| Area | Problem | Approach | Quality signal |
| --- | --- | --- | --- |
| 🌍 Land-cover simulation workflows | Large scenario runs can hide assumptions and make output changes hard to explain. | Build simulation pipelines with explicit scenario inputs, year-by-year outputs, and inspectable intermediate artifacts. | Reproducible rasters, clear demand assumptions, and comparison-ready outputs. |
| 🛰️ Raster validation and AOI smoke checks | Full-raster checks are expensive, but silent raster regressions are costly. | Validate representative AOI windows first, then scale only when the local evidence is sound. | Fast GeoTIFF triplets, summaries, and focused mismatch analysis. |
| ⚙️ Windowed CA and Dask pipelines | Chunked spatial simulation can introduce boundary behavior and allocation drift. | Trace window demand, CA allocation, and chunk-level artifacts through the real pipeline path. | Boundary-aware diagnostics, scalable execution, and debuggable simulation steps. |

## ✅ What I Value

- Reproducible geospatial workflows over one-off scripts
- Fast localized validation before expensive full-raster runs
- Clear assumptions, typed interfaces, and inspectable artifacts
- Engineering choices that make spatial model behavior easier to explain

## 🤝 Collaboration

I am interested in geospatial simulation, raster processing, and reliable Python tooling for spatial data workflows.

- GitHub: [@ZihaoNova](https://github.com/ZihaoNova)
- Project issues and discussions will be linked here as public repositories are published.
