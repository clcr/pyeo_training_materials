# How this notebook works

You are currently in an envrionment set up for this training course.
It comes pre-installed with Python 3.6, Pyeo - our satellite image
processing library - and some example inputs.
Any files your create or download will persist for the training course.
If you would like to keep any past this, please contact an instructor.
You can create new Python3 notebooks from the previous screen, in the top-right corner.

# How to use an Jupyter notebook
A notebook is a way of running small snippets of a programming language.
Each notebook is divided into 'cells'; when run, these cells will 
show any output underneath. A change made in one cell affects the entire
notebook; for example, if you say `x=5` in one cell, `x` will be 5 in
all cells run after that.

To run a cell, either click the 'run' button at the top of the notebook
or press 'ctrl' and 'enter'. 

##

## Existing files
### stub.ipynb
This is the abslute minimum you will need to access Pyeo. Please
feel free to build on or copy this notebook as required.

### kinangop.ini
This is an example .ini file for rolling\_s2\_composite\_change
\_detection. It contains:
* The credentials you will use for querying and downloading images from
ESA's servers
* The date ranges (in yyyymmdd) for the initial base layer and 
set of changes you want to run
* The maximum amount of cloud cover (according to ESA) that each
image can have
* The paths on your machine to the working folder, model, .json file, log
and Sen2Cor directory.

### kinangop\_rough.json
A geojson file outlineing a forest region in Kinangop, Kenya.
You can create these at www.geojson.io or export them from
most GIS programs.
