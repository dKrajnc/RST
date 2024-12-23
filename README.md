# Rule Set Table (RST)-based automated data preprocessing
This repository contains information about the RST concept, implemented by researchers of the Medical University of Vienna (MUV), Vienna, Austria. The development is conducted at the Center for Medical Physics and Biomedical Engineering (main developer: Denis Krajnc)
The RST concept provides a tabular data-based simple interface for clinicians who can provide simple preference rules for each typical data preprocessing algorithm incorporated into a data preprocessing pipeline. This way, each data preprocessing step can be influenced with optional or preferencial as well as with fixed rules.
The RST concept allows clinicians to incorporate domain knowledge into the process of automatically building a data preprocessing pipeline instead of manually preprocessing the given input data or instead of allowing the automated data preprocessing algorithm to perform any decision and acton based on mathematical / algorithmic rules.


## Intended Use
We explicitly state that the RST binary does not describe any product and it is not intended to be used in any real-life, especially not in clinical settings. This repository contains description and examples of a research tool for experimenting with data preprocessing approaches prior to conducting machine learning building processes on the data.
Therefore, the contents of this repository shall not be used either partly or fully for rendering clinical decisions or to be included in any product. We waive any liabilities for any damage caused by the executables.


## License
In case you wish to use our solution in a commercial environment please contact the Technology Transfer Office (TTO) of MUV: https://www.meduniwien.ac.at/technologietransfer

Contact the correspondig author (Laszlo Papp, PhD, e-mail: laszlo.papp@meduniwien.ac.at) in case you are interested in research collaborations regarding the utilization of RST.


### How to run the RST

To run the RST app, firstly download the BIN_MLDP_RST, Dataset and Settings directories.
1. Open Command prompt and navigate to the BIN_MLDP_RST directory.
2. Type in TestApplication.exe and add the following arguments:
   - path to the Settings directory (../settings/)
   - path to the dataset directory (../dataset/)
   - for single center studies, path to the fold directory - however, our example contains dual-center DLBCL study with independent validation dataset, hence this argument may contain empty string ("")
   - declare type of the study ("MULTI" in our case) or "SINGLE" for single-center studies
To succesfully run the example, the command line should look similarly to the following lines:
>>TestApplication.exe ../settigns/ ../dataset/ "" MULTI


## Citation
The manuscript which describes the scientific findings of the RST mechanism is currently under review.
