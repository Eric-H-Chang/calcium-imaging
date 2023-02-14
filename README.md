# calcium-imaging
This is a set of tools for calcium imaging and analysis of Miniscope data from peripheral ganglia. Code and processes developed by Tomás S. Huerta, Bilal Haider, Richard Adamovich-Zeitlin, and Eric H. Chang.

As of February 2023, this project contains three documents: a modified CaImAn pipeline for ganglion analysis, a post analysis pipeline to export calcium traces with their respective response components, and a Guide to aid with preprocessing steps and basic troubleshooting. Use of this pipeline requires proper installation of CaImAn and the caiman_data folder. Please refer to the caiman documentation for instructions to install the caiman_data folder and all other dependencies. https://caiman.readthedocs.io/en/master/

The two Jupyter notebook files should be placed in the “caiman_data/demos/notebooks” folder, and must be run in a caiman anaconda environment. Depending on the length of the recordings being analyzed, this pipeline can be very demanding on hard drive space. Therefore, it is recommended to have ample storage (several terabytes) available prior to processing large datasets.
