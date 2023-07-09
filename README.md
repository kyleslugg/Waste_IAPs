# NYCHA Individual Action Plans: Waste Management

This repository contains a Jupyter notebook that combines text documents, images, and data tables to create consolidation-by-consolidation waste management plans for NYCHA properties. This is accomplished by generating LaTeX code.

Data used to create tables, as well as analysis and overview text for each consolidation, is contained in this repository. Images -- including maps of waste assets and context maps for each consolidation -- are not, due to size limitations. These are instead hosted on Box; maps can be accessed <a href='https://app.box.com/s/zxev8wv686w87fiua8riyemv7oqcg7zq'>here</a>. Prior to runtime, the linked directory should be downloaded and placed in the project folder.

## Key Notebooks:

- IAP_LaTeX_Automation.ipynb: Contains the full workflow for processing waste asset data (minus geospatial tasks), producing LaTeX scripts, and compiling PDFs from all component parts
- Waste_Asset_Maps.ipynb: Contains a description of the workflow used to create waste asset maps incorporated into the reports.
