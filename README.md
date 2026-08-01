# python-urban-planners

Practical Python notebooks for urban planners, built around real Indian urban datasets and run in Google Colab. Each project is a self-contained notebook that goes from raw data to a map or analysis using established geospatial tools.

References: Spatial Thoughts' [Python Foundation for Spatial Analysis](https://courses.spatialthoughts.com/python-foundation.html) and the University of Helsinki's [Automating GIS Processes (AutoGIS)](https://autogis-site.readthedocs.io/) course. This course material is heavily inspired from the above mentioned course. 

## Projects

| # | Project | What it covers | Open |
|---|---------|----------------|------|
| 01 | GBA 369 Wards | Load, explore, reproject to UTM 43N, and build an area choropleth of Bengaluru's ward boundaries | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rlfT1k_kT2rWGoGVewu0UuQEdsjljYPo?usp=sharing) |

## Data

Datasets are read directly from their source URLs, so no large files are committed to the repo. Ward boundaries come from [OpenCity](https://data.opencity.in), an urban data portal for Indian cities.

Click the Open in Colab button for a project. It opens in Colab in view-only mode, which needs only a Google account, no GitHub required. To run and experiment, use File, then Save a copy in Drive to get your own copy. The first cell installs everything the notebook needs.

Once the collab notebook opens, File>save a copy in Drive

    conda env create -f environment.yml
    conda activate urban-planners
    jupyter lab

## License

Released under the MIT License. See [LICENSE](LICENSE).
