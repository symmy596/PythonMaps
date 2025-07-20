# Pyvista Contour Lines

Example for creating an interactive contour line topography plot with pyvista. 


![alt text](https://github.com/symmy596/PythonMapsExamples/blob/main/pyvista_contour_lines/resources/output.png) 


#### Data

- [Topography](https://www.ngdc.noaa.gov/mgg/global/relief/ETOPO1/data/bedrock/grid_registered/georeferenced_tiff/)
- [Natural Earth Country Boundaries](https://github.com/nvkelso/natural-earth-vector/blob/master/10m_cultural/ne_10m_admin_0_countries.shps)


### Install Packages

To be able to run the examples, demos and exercises, you must have the following packages installed:

The following libraries are required to run the workshop

- geopandas==0.10.2
- rasterio==1.2.10
- matplotlib==3.5.1
- pandas==1.4.2
- shapely==1.8.0
- numpy==1.21.5
- gdal==3.5.2
- pyvista==0.45.3
- trame==3.10.2
- ipyvtklink==0.2.3
- ipygany==0.5.0

If you are using Anaconda, you can use the Anaconda Prompt (Windows) or Terminal.app (macOS) to create an environment with the necessary packages:

1. Open the Anaconda Prompt or Terminal.app using the below instructions:
    - **Windows**: Click Start and search for "Anaconda Prompt". Click on the application to launch a new Anaconda Prompt window.
    - **macOS**: Open Spotlight Search (using Cmd+Space) and type "Terminal.app". Click on the application to launch a new Terminal.app window.   

2. Create a new Anaconda virtual environment by executing the below command in the application window you opened in step 1 above.

    ```
    conda create -n pythonmaps-tutorial -c conda-forge jupyterlab geopandas==0.10.2 rasterio==1.2.10 matplotlib==3.5.1 pandas==1.4.2 shapely==1.8.0 numpy==1.21.5 gdal==3.5.2 pyvista==0.45.3 trame==3.10.2 ipyvtklink==0.2.3 ipygany==0.5.0
    ```

