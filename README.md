# covid19pm_India

Version 1.0
Last update: 2019 May 07
Codes for generating graphs used in 'Robust association between short-term ambient PM2.5 exposure and COVID prevalence in India'

# Structure
The folder follows the following structure:
```bash
data
    ├─ Admin2_Topo.json
    ├─ dbins.csv
plots
    ├─ figure1.png
    ├─ figure3.png
    ├─ figure4a.png
    ├─ figure4b.png
    ├─ figure4c.png
    ├─ figure6a.png
    ├─ figure6b.png
source
    ├─ bubble map_plot.ipynb    
    ├─ errorplots.ipynb

```
# Admin2_Top.json
Shapefile for Indian States (Source: https://github.com/datameet/maps/tree/master/States, converted to TopoJSON using https://mapshaper.org/)

# dbins.csv
Case wise state bins used as an input for the bubblemap plot

# bubble map_plot.ipynb 
Jupyter Notebook for generating the bubble map plot

# errorplots.ipynb
Jupyter notebbok for generating the errorplots

