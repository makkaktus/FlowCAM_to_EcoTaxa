# FlowCAM_to_EcoTaxa
Python pipeline for FlowCAM data to make it EcoTaxa friendly : )
Modified code from the VisibleOcean blog: https://sarigiering.co/posts/from-flowcam-to-ecotaxa/

The code was prepared in Jupyter notebook style, but can be united and run as a regular python script.
INPUT: FlowCAM images (mosaics of many images) + .lst file (generated during acquisition, containing all objects properiteis) 
+ excel sheet with metadata if needed (required for ecotaxa)
OUTPUT: .zip file prepared to be uploadat to EcoTaxa

there is an example of how the excel file may look like
this pipeline works for single file
it can be modified to iterate throughout more files

Author of the original morphocut pipeline: 
Dr Sari Giering (VisibleOcean blog)

Author of this complete pipeline:
Adam Makatun
adam.makatun@ug.edu.pl
Laboratory of Plankton Biology
University of Gdańsk
