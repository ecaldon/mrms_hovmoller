# mrms_hovmoller
This Python notebook plots Multi-Radar Multi-Sensor (MRMS) data on a Hovmöller-type diagram, with longitude plotted on the x-axis and time plotted on the y-axis.

## How to get started...
Create and activate the conda environment on your machine using the environment.yml file.
```
conda env create -f environment.yml
conda activate hovmoller_diagram
```
Next, download the `Hovmoller_Diagram.ipynb` file (and files in the `rap` directory for some RAP files to immediately play with) into a convenient directory on your machine. `cd` to this directory in your terminal and then run
```
conda activate hovmoller_diagram
jupyter lab
```
You should be ready to run the notebook in your newly created environment! Go through the customization blocks to change the directories and settings to your specifications. Happy plotting!
