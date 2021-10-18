# Determine sample areas from images
This is the code I used to measure the areas of samples of Si|ZnO:Al|Ag, as is useful in performing contact resistivity measurements.
Images should include a €0.05 coin as reference (this is hardcoded at the moment).

The project is currently split up into two parts:
- pipeline.ipynb :: This is where the image segmentation happens.
- gatherData.ipynb :: Data management scripts, applies the analysis in pipeline, adds user interface, shows debugging info.

Although currently a badly documented (but functioning) mess, if you find yourself measuring contact resistivities and are interested in using my scripts, do not hesitate to message me!

Some non-priority todos for when I've finished my thesis:
* TODO Document project
* TODO Get project on PyPi for easy reuse
* TODO Factor out IP-camera dependence



