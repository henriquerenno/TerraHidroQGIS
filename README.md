# TerraHidroQGIS
TerraHidro plugin for QGIS Toolbox.

TerraHidroQGIS is a plugin for the QGIS Toolbox that aims to provide QGIS users a simple and easy Graphical User Interface (GUI) for executing all functions of the TerraHidro system, which is developed at the National Institute for Space Research (INPE) in Brazil for computational hydrological modeling based on topographic data.

The TerraHidroQGIS plugin offers different process groups: Basin Tools, DEM Tools, Drainage Tools, and Flow tools. Each group contains the functions that generate outputs related to basin, topography, drainage, and flow data. Each function interface requires the user to enter input/output data in the QGIS Toolbox standard.

Installation and configuration: 1. Copy all TerraHidroQGIS plugin content into the QGIS plugins location as a new folder (e.g., terrahidro); 2. Add an environment variable named TERRAHIDRO that points to the TerraHidro system folder (available at https://github.com/henriquerenno/TerraHidro); 3. Activate the TerraHidroQGIS plugin in QGIS.

Note: TerraHidroQGIS only works on QGIS >= 3.18.
