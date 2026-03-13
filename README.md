# mrms_hovmoller
This Python notebook plots Multi-Radar Multi-Sensor (MRMS) data on a Hovmöller-type diagram, with longitude plotted on the x-axis and time plotted on the y-axis.

## How to get started...
`cd` to a convenient directory on your machine and run the following:
```
git clone https://github.com/ecaldon/mrms_hovmoller.git
cd mrms_hovmoller
```
Create and activate the conda environment on your machine using the environment.yml file.
```
conda env create -f environment.yml
conda activate hovmoller_diagram
```
Then you can run...
```
jupyter lab
```
You should be ready to run the notebook in your newly created environment! Go through the customization blocks to change the directories and settings to your specifications. Happy plotting!

## Recent updates...
**Major Update 3/13/26**
- New capability to use Level III files in addition to MRMS files
  - Automatically download Level III files from Amazon S3 bucket
- Separated plot customizations to aesthetic and data preferences to improve user experience
- Added rotation variable to colorbar labels for aesthetic preferences
- Added longitude bucket variable to customize number of longitude buckets for Level III radial data
- Added helpful custom colormaps
- Modified Markdown comments to aid user experience
- Added abililty to plot mode and median of latitude band in addition to mean
- Separated download data into separate block to improve debugging and user experience
