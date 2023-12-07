# About
This folder contains a jupyter notebook that downloads the "Basisdaten für Tarife der Schweizer Verteilnetzbetreiber" from [ElCom](https://www.elcom.admin.ch/elcom/en/home/topics/electricity-tariffs/basic-data-for-tariffs-of-the-swiss-distribution-network-operato.html) through [LINDAS](https://lindas.admin.ch/?lang=en).

The notebook
- Constructs a SPARQL query
- Requests the data from LINDAS
- Does some filtering, cleansing and transformation on the data
- Computes additional fields
- Saves the results as csv file

# Results
The published data for Kanton Basel-Landschaft can be found [here](https://data.bl.ch/explore/dataset/12340/table/)

# Gettin Started
- The relevant notebook is called elcom-strompreise.ipynb
- The pipfile contains all necessary libraries required to run the notebook

## Authors and acknowledgment
- Author: Johannes Hool ([Fach- und Koordinationsstelle OGD Basel-Landschaft](https://www.baselland.ch/politik-und-behorden/direktionen/finanz-und-kirchendirektion/statistisches-amt/ogd))