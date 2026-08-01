# python-urban-planners

Practical Python notebooks for urban planners, built around real Indian urban datasets and run in Google Colab. Each project is a self-contained notebook that goes from raw data to a map or analysis using established geospatial tools.

Conventions follow Spatial Thoughts' [Python Foundation for Spatial Analysis](https://courses.spatialthoughts.com/python-foundation.html) and the University of Helsinki's [Automating GIS Processes (AutoGIS)](https://autogis-site.readthedocs.io/) course.

## Projects

| # | Project | What it covers | Open |
|---|---------|----------------|------|
| 01 | GBA 369 Wards | Load, explore, reproject to UTM 43N, and build an area choropleth of Bengaluru's ward boundaries | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soniadas123/python-urban-planners/blob/main/01-gba-wards/gba_wards.ipynb) |

## Data

Datasets are read directly from their source URLs, so no large files are committed to the repo. Ward boundaries come from [OpenCity](https://data.opencity.in), an urban data portal for Indian cities.

## Running the notebooks

Colab (recommended): click the Open in Colab badge for a project. The first cell installs what it needs, so there is nothing to set up locally.

Local: create the conda environment once, then launch JupyterLab.

    conda env create -f environment.yml
    conda activate urban-planners
    jupyter lab

## License

Released under the MIT License. See [LICENSE](LICENSE).
