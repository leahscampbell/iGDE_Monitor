# iGDE Monitor
> Remote monitoring of groundwater-dependent ecosystems in shallow aquifers
* Contains all methods outlined in Rohde M. M., T. Biswas, I. W. Housman, L. S. Campbell, K. R. Klausmeyer, and J. K. Howard, 2021: A Machine Learning Approach to Predict Groundwater Levels in California Reveals Ecosystems at Risk. Frontiers in Earth Sciences, 9. https://doi.org/10.3389/feart.2021.784499

## Primary POCs
* Primary technical contacts
  * Ian Housman - ian.housman@gmail.com
  * Leah Campbell - lcampbell@contourgroupconsulting.com 
  
* Primary manuscript author
  * Tanushree Biswas - tanushree.biswas@tnc.org 

## Dependencies
* Python 3
* earthengine-api (Python package)
* geeViz (Python package)

## Using
* Ensure you have Python 3 installed
  * <https://www.python.org/downloads/>
  
* Ensure the Google Earth Engine api is installed and up-to-date
  * `pip install earthengine-api --upgrade`
  * `conda update -c conda-forge earthengine-api`

* Ensure geeViz is installed and up-to-date
  * `pip install geeViz --upgrade`

* Running scripts
  * Each script is intended to run sequentially to reproduce the methods used in Rohde et al 2021
