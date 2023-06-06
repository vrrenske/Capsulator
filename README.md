# Capsulator

Code used for the analysis of microscopy data in:

Anne-Stephanie Rueff, Renske van Raaphorst, Surya D. Aggarwal, Javier Santos-Moreno, Geraldine Laloux, Yolanda Schaerli, Jeffrey N Weiser, Jan-Willem Veening (2023) **Rewiring capsule production by CRISPRi-based genetic oscillators demonstrates a functional role of phenotypic variation in pneumococcal-host interactions**
*bioRxiv* 2023.06.03.543575; doi: https://doi.org/10.1101/2023.06.03.543575

Most datasets are too large to be reposited here; please send me a message (renske.vanraaphorst@uclouvain.be) if you are interested in the dataset.

### Manual Tracking
Contains the results from manual tracking using Fiji (done by ASR) as excel files, output animations of both tracked cells and the R notebook containing the code for creating these animations.

### Microfluidics_capsulator
Contains the code used to analyze the output of TrackMate (edges, spots & tracks) to follow the capsulator over time. `ACF_function` is used to calculate acf, `plotting graphs over time.Rmd` for plotting cell lineages.

### Microfluidics_crisprlator
Contains the code used to analyze the output of TrackMate (edges, spots & tracks) to follow the capsulator over time. 

### VL4315
Contains the analysis for the relationship between capsule & expression of YFP, CFP & RFP in strain VL4315.

