[![DOI](https://zenodo.org/badge/452388873.svg)](https://doi.org/10.5281/zenodo.15871796)
![Visitors Badge](https://visitor-badge.laobi.icu/badge?page_id=RuiGao9.Group_Materials)<br>

# A Backup Way for TSEB Model Installation 
Subtitle - TSEB-Backup-Old-Style <br>
This repository serves as a backup of the previous method used to install the TSEB model for our research. It is based on the version available at https://github.com/hectornieto/pyTSEB, as published around 2021.<br>
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

Before the installation, required software are: <br>
- Anaconda
- ArcGIS Pro <br>

## TSEB model installation
Since much of our research involved working with ArcGIS Pro, we frequently relied on its built-in functions. As a result, we installed and ran the TSEB model within the ArcGIS Pro environment.
Steps for model installation in the ArcGIS Pro environment.
1. Create a compatible Python environment.
Copy the existing ArcGIS Pro Python environment to the `envs` folder of your Anaconda installation. This ensures compatibility with ArcGIS Pro's Python setup.
2. Download the TSEB model.
    - Option 1: download from the official repository: https://github.com/hectornieto/pyTSEB
    - Option 2: download `pyTSEB-master.zip` from this repository.
3. Organize the files.
Extract and copy all TSEB files to either:
    - The environment folder you just created, or
    - A project directory where you can better manage your code and data.
4. Install the TSEB model.
    - Open the Anaconda Prompt, and activate the environment you just created.
    - Navigate to the directory containing `setup.py` using `cd`.
    - Run the following command:
    ```
    python setup.py install
    ```
    (Note, make sure you're in the correct directory before running the command.)
5. Install the `pyPro4Sail` dependency.
Follow a similar process for installing `pyPro4Sail`:
    - Repository: https://github.com/hectornieto/pyPro4Sail
    - Or download `pypro4sail-master.zip` from this repository.
6. Done.
You should now be ready to run the TSEB model within your ArcGIS Pro-compatible Python environment.

# Demo for input prepartion for the TSEB-PT model
The flowchart below provides an overview of the general structure for preparing inputs for the TSEB-PT model using UAV imagery. The specific process for generating these inputs may vary depending on individual preferences and workflows. Hopefully, this flowchart serves as a helpful guide to support you in developing your own approach to input preparation.
![image](https://user-images.githubusercontent.com/51354367/153303524-212734e0-a07b-4169-a4ea-f63a83727422.png)

# Run model
Rather than focusing on the detailed steps for running the TSEB model, this repository provides demo data to help you get started:
- "1_Demo_Data": This folder contains image data you can use to test and run the model.
- "2_Decimal_Data.xlsx": This Excel file includes sample decimal-format observations for model input.

## Citation
If you use this reporitory in your work, please cite it using the following DOI:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15871797.svg)](https://doi.org/10.5281/zenodo.15871797)

BibTeX:
```bibtex
@misc{gao2025tseb,
  author       = {Rui Gao},
  title        = {A Backup Way for TSEB Model Installation – TSEB-Backup-Old-Style},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.15871797},
  url          = {https://doi.org/10.5281/zenodo.15871797}
}
```

## Repository update information:
Created by January 26th, 2022 <br>
1st update by August 1st, 2025 <br>

## Contact information if issues were found:
Rui Gao<br>
Rui.Ray.Gao@gmail.com<br>
RuiGao@UCMerced.edu<br>
Rui.Gao@USU.edu