This Jupiter notebook file encompasses the analysis of an H&E image of a tissue section. It assumes that the image has been pre-analyzed with a segmentation code.
In this case I used QuPath (ver: QuPath-0.5.1). 
The file containing all the information about segmentation of the cells and their features is a txt file that is obtained by using "Show detection measurements" in QuPath. 
The notebbook is organized in several blocks. In each of them I analyse one of the five features that IN2SIGHT consortium has indentified as relevant to classify the 
cell type from the image. They are:

- Eccentricity of the nucleus
- Fractality of the nucleus (defined from the slope of the area versus perimeter)
- Granularity (S/N ratio of the spectroscopic signal)
- LogArea (ratio of the logarirthm of the cell to nucleus area)
- LinArea (ratio of the cell to nucleus area)



Reference:
Bankhead, P. et al. QuPath: Open source software for digital pathology image analysis. Scientific Reports (2017).
https://doi.org/10.1038/s41598-017-17204-5
