# Exosky: Visualizing the Night Sky from Exoplanets

![image](https://github.com/user-attachments/assets/33016bfa-7d17-40e5-9f4f-f6b5c6166254)


## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Datasets](#datasets)
- [MySQL Database](#mysql-database)
- [Data Profiling & Visualization](#data-profiling--visualization)
- [Jupyter Notebooks](#jupyter-notebooks)
- [Future Work](#future-work)


---

## Project Overview
**Exosky** allows students to explore the night sky from exoplanets, visualizing star fields based on data from NASA's Exoplanet Archive and the Gaia DR3 Star Catalog. Users can generate star charts, name constellations, and even explore the sky through virtual reality.

## Features
- Select an exoplanet and generate its unique "exosky."
- Interactive sky charts with adjustable star brightness, and grids.
- 3D point cloud visualizations of stars.
- Export star charts as PDFs or explore them in virtual reality.

## Datasets
This project uses two primary datasets:
1. **NASA Exoplanet Archive**: [Sample CSV](datasets/NASA_Exoplanet_sample.csv)
2. **Gaia DR3 Catalog**: [Sample CSV](datasets/Gaia_DR3_Catalog_sample.csv)

## MySQL Database 

The datasets are loaded into a MySQL database to facilitate efficient querying and manipulation. The database helps manage the vast number of records from the star catalogs and exoplanet archive.
Sample image of Database:
![Database Image](images/Database_ss.jpg)

### Database Schema
![Database Schema](images/Databse_ss_02.jpg)

## Data Profiling & Visualization
The project includes a set of data profiling and visualization notebooks that explore the datasets:
1. **Data Profiling**: Insights into the structure and quality of the data using Python tools like `pandas`, `seaborn`, and `matplotlib`.
   
   👉🏻 **Data Profiling Full Report**: [Download Data Profiling Report](https://raw.githubusercontent.com/<your-username>/<repository-name>/main/reports/data_profiling.html)
     
   ![image](https://github.com/user-attachments/assets/2012da01-8b53-4b20-9cc2-9682f8c6bef0)

3. **Data Visualization**: Plots and graphs representing different star properties, exoplanet characteristics, etc.
   <img width="803" alt="image_2024-09-19_22-48-05" src="https://github.com/user-attachments/assets/af45a046-da57-489e-88f5-a46adb94a694">
   <img width="746" alt="image_2024-09-19_22-48-10" src="https://github.com/user-attachments/assets/adf01e26-d4ff-43ff-a240-ebbd9e86362f">


## Jupyter Notebooks

Explore the data profiling and visualization work in these Jupyter notebooks:

- [Data Profiling Notebook](notebooks/nasa_app_innovation.ipynb): Profiling the datasets using `pandas` and generating insights.
- [Data Visualization Notebook](notebooks/nasa_app_innovation.ipynb): Visualizing star data from the exoplanet archive and Gaia catalog using `matplotlib` and `seaborn`.




## Future Work
- Some exciting future features that could enhance the Exosky experience:
- Real-time 3D visualizations with Three.js or Plotly.
- A public web interface for interactive star exploration.
- Incorporating additional datasets for more comprehensive sky visualizations.
