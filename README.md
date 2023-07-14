# SpikeRasters
**Demonstration of using rasterization in matplotlib and the scour library to simplify working with spike raster plots.**

This code demonstrates how to make spike raster plots using Python's matplotlib library with the spikes rasterized within the saved figure. This can save a lot of time working with raster plots in figures in vector art programs such as Inkscape or Adobe Illustrator. 

Two notebooks are included. One demonstrates use of the scour library, which simplifies SVG files processed in Inkscape. The other demonstrates making a simple raster plot with the spikes rasterized and the file scrubbed by the scour library.

A PDF file is included that shows the activity of the example neuron over trials and is described in the spike raster notebook.

The notebooks run in jupyter and depend on only a few standard libraries (os, numpy, pandas, matplotlib, seaborn) and the scour library.

Information about scour is at https://github.com/scour-project/scour. The library can be installed using pip or conda: conda install -c conda-forge scour.

To work through the demos, unzip the data files into a subfolder in your working directory (called data), launch jupyter, and work through the notebooks.

-Mark Laubach, July 14 2023
