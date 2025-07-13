[![DOI](https://zenodo.org/badge/452388873.svg)](https://doi.org/10.5281/zenodo.15871796)
![Visitors Badge](https://visitor-badge.laobi.icu/badge?page_id=RuiGao9.Group_Materials)<br>

# Group Materials
Created by January 26th, 2022 <br>
Last updates by January 26th, 2022 <br>

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
