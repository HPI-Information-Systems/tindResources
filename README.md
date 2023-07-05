# tindResources
This repository links all codebases and artifacts relevant to the paper submission "Efficient Discovery of Temporal Inclusion Dependencies".

## Code:
* Implementation of all Algorithms (scala): https://github.com/leonbornemann/temporalINDDiscovery
* Creation of Plots (jupyter notebook): https://github.com/leonbornemann/temporalINDEvaluation

## Input Data:
* Original Historical Data From Wikipedia is available [here](https://dumps.wikimedia.org/)
* Original Table Histories (with matched columns) are available [here](https://drive.google.com/file/d/1pgqBeax3nd5sNnKRaoEs1kkSsG7G1C09/view?usp=drive_link)
* Complete Input data for our experiments with pre-processing and filters applied is available [here](https://drive.google.com/file/d/1RboxrljEYS2TjvOBdW3NP-pkDXHbGVJh/view?usp=sharing)
* IDs of randomly chosen queries are available [here](https://drive.google.com/file/d/1KFMExBT1mYZ3eTe2xdB07RJPEDdpPukx/view?usp=drive_link)
* Annotated Gold Standard of INDs (labelled as genuine or not): available soon

## Evaluation Data:
This data can be re-created using the executable main objects of the scala implementation, but is published here for convenience
* Statistics about the performance of the different tIND approaches on the gold standard available [here](https://drive.google.com/file/d/1ZKFPef-U75OcUNfreG0uFJ75G1xuG7wp/view?usp=sharing). This is the necessary input for the Jupyter notebook that perofrms the genuineness-evaluation.
* Statistics about the runtime with various parameter settings avilable [here](https://drive.google.com/file/d/10MnH4qDFdhWoWdwSyXo6UujTj1O7yVZW/view?usp=sharing). This is the necessary input for the Jupyter notebook that performs the runtime evaluation.

