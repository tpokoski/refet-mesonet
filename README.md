# Reference Evapotranspiration Comparison: State Mesonet vs pyFAO56
This Jupyter Notebook contains a script to compare a state's Mesonet calculation of reference evapotranspiration (ETr or ETo) with the reference ET calculated using the FAO-56 Penman-Monteith equation, via a python package pyfao56.

### Key Features: 
- Compares reference ET from state Mesonet with pyfao56
- Supports both hourly and daily data, and hourly or daily reference ET calculations
- Generates a correlation plot and some related statistics

### This script requires the following Python packages:
- pyfao56
- pandas
- numpy
- plotly.graph_objects

### Usage: 
- Download the notebook and the template inside the 'input' folder
- Add your data to the excel template. *make sure to pay attention to units*
- Edit the cell within the jupyter notebook with the necessary information
- Run the script, all outputs will be placed in wherever your output directory leads

Feel free to comment on any issues noticed or features to add. 

