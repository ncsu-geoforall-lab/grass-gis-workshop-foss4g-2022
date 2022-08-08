# Unleash the power of GRASS GIS with Jupyter (FOSS4G 2022 workshop)



This is a set of Jupyter Notebooks for FOSS4G 2022 workshop. 

## How to run the notebooks
You do not need to install anything, the notebooks are hosted on mybinder.org.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ncsu-geoforall-lab/grass-gis-workshop-foss4g-2022/main?urlpath=lab%2Ftree%2Fworkshop_part_1.ipynb)

If binder does not start even after couple tries, there are backup solutions below that work for the workshop only:

### Notebooks hosted on our server ()
After you obtain a username, go to:

    http://....ncsu.edu:8080

Use your username and create a new password. You should see a Jupyter Lab, create new Terminal from the Launcher tab:

    git clone https://github.com/ncsu-geoforall-lab/grass-gis-workshop-foss4g-2022.git
    mv grass-gis-workshop-foss4g-2022/*.ipynb .
    rm -rf grass-gis-workshop-foss4g-2022/
    
Then execute (from your home folder):

    cp -R /data/grass-gis-workshop-foss4g-2022/* .
    
Then find `workshop_part_1.ipynb` on the left side and double click at it.

## Abstract
Whether you are considering using GRASS GIS for your next project or you are a GRASS GIS power user who wants to learn new tips and tricks, this workshop is for you. We will explain and practice GRASS GIS concepts like location, computational region, or mask and demonstrate them on examples of efficient raster, vector, and imagery processing. We will go through several options to parallelize your workflows that are applicable for various computing platforms including your laptop and HPC. Finally, this workshop will be run in a JupyterLab environment, taking advantage of the latest GRASS GIS Python features for Jupyter, including pretty 2D, 3D, webmap, and temporal visualizations.

## Authors

* Anna Petrasova, NCSU Center for Geospatial Analytics
* Caitlin Haedrich, NCSU Center for Geospatial Analytics
* Vaclav Petras, NCSU Center for Geospatial Analytics

## License

This material is dual licensed under GNU FDL 1.3 and CC BY-SA 4.0.

