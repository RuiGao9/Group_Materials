[![DOI](https://zenodo.org/badge/452388873.svg)](https://doi.org/10.5281/zenodo.15871796)
![Visitors Badge](https://visitor-badge.laobi.icu/badge?page_id=RuiGao9.Group_Materials)<br>

# TSEB Model Installation Using an Old Style - Backup
This repository serves as a backup of the previous method used to install the TSEB model for our research. It is based on the version available at https://github.com/hectornieto/pyTSEB, as published around 2021.
Please consider citing the original work as referenced in the included CITATION.cff file below.
The original setup included two key folders, which are preserved here:
- pyTSEB-master.zip
- pypro4sail-master.zip
```
cff-version: 1.2.0
message: "If you use this software, please cite it as below."
authors:
- family-names: "Nieto"
  given-names: "Hector"
  orcid: "https://orcid.org/0000-0003-4250-6424"
- family-names: "Guzinski"
  given-names: "Radoslaw"
  orcid: "https://orcid.org/0000-0003-0044-6806"
- family-names: "Kustas"
  given-names: "William P."
  orcid: "https://orcid.org/0000-0001-5727-4350"

title: "pyTSEB: A python Two Source Energy Balance model for estimation of evapotranspiration with remote sensing data"
version: 2.2
doi: 10.5281/zenodo.594732
date-released: 2018-03-04
url: "https://github.com/hectornieto/pyTSEB"
```

## TSEB model installation
Since much of our research involved working with ArcGIS Pro, we frequently relied on its built-in functions. As a result, we installed and ran the TSEB model within the ArcGIS Pro environment.
Steps for model installation in the ArcGIS Pro environment.
1. Create a compatible Python environment.
Copy the existing ArcGIS Pro Python environment to the `envs` folder of your Anaconda installation. This ensures compatibility with ArcGIS Pro's Python setup.

ArcGIS Pro to the "envs" folder of the Anaconda.
- Download the TSEB model from the website: https://github.com/hectornieto/pyTSEB or download `pyTSEB-master.zip` from this repository.
- Copy all filles (TSEB) into the environment folder you just created, or into a folder that you can better organize your folders/files.
- Install the TSEB model inside the environment by type `python setup.py install` in anaconda prompt (under the environnment you have just installed). Be carefull, you need to navigate to that environment folder path via the terminal.
- The library called "pyPro4Sail" can refer the previous process, and the resource can be found here: https://github.com/hectornieto/pyPro4Sail, or download `pypro4sail-master.zip` from this repository.
- Finished, and you should be good to run TSEB models.

- Considering using ArcGIS Pro;
- Considering easier for developing via Python;

Created by January 26th, 2022 <br>
1st update by January 26th, 2022 <br>
2nd update by August 14th, 2025 <br>

Brief introduction of this repository:<br>
This repository is prepared for our research group to run the [TSEB](https://github.com/hectornieto/pyTSEB) model after the successful installation.

# Model installation
Installation varies from person to person. One option you could consider. <br>
Before the installation, required software are: <br>
- Anaconda
- ArcGIS Pro <br>

Steps for model installation.
- Create an environment which is the same as the one of ArcGIS Pro: copy the environment from ArcGIS Pro to the "envs" folder of the Anaconda.
- Download the TSEB model from the website: https://github.com/hectornieto/pyTSEB.
- Copy all filles (TSEB) into the environment folder you just created.
- Install the TSEB model inside the environment by type "python setup.py install" in anaconda prompt (under the environnment you have just installed). Be carefull, you need to navigate to that environment folder path.
- The library called "pyPro4Sail" can refer the previous process, and the resource can be found here: https://github.com/hectornieto/pyPro4Sail.
- Finished, and you should be good to run TSEB models.

# Run model
Instead of the details of running the TSEB model, demo data is provided in this repository.
- "1_Demo_Data", this folder contains image data for you to try to run the model.
- "2_Decimal_Data.xlsx", this XLSX file contains decimal observations for you to run the model.

# Inputs for the TSEB-PT model
The flowchart below is just a big picture showing the structure to gain the inputs for the TSEB-PT model. The process to gain the inputs for TSEB-PT varies from person to person. Hopefully, this flowchart can help you make your own way for the input preparation conveniently.
![image](https://user-images.githubusercontent.com/51354367/153303524-212734e0-a07b-4169-a4ea-f63a83727422.png)


Recommendations, suggestions, and comments are much appreciated to send to Rui at rui.gao@usu.edu.
