# Hands-on sessions for the advanced users

The used Gammapy version will be the **v2.0**. See the installation page
[here](https://docs.gammapy.org/2.0/getting-started/index.html#recommended-setup).

**Disclaimer** : still under construction!

## Table of contents
1. [Gammapy in depth](#intro)
2. [IRFs and Data reduction](#data)
3. [Joint analysis - Source detection and model selection](#detection)
4. [Timing analysis](#time)
5. [Diffuse emisison and source population models](#diffuse)
6. [Joint analysis - Custom models and multi-instrument systematics](#mia)
7. [Nested sampling](#nested)
8. [Machine-learning representation of physical models](#ml)

<a name="intro"></a>
## Session of Wednesday, 9h30/10h45
**Gammapy in depth** : the data analysis workflow, the GADF data format, makers and estimators, models and catalogs, 
multi-processing (multi-core and multi-CPU), etc.

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

[link to the notebook](1_Introduction.ipynb).

[Link to open problems](Open_problems.md).

<a name="data"></a>
## Session of Wednesday, 11h15/12h30
**IRFs and Data reduction** : observation handling, IRFs, safe mask, exclusion masks, background fitting, diffuse emission

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

IACTs data reduction (H.E.S.S. example)
[Link to the notebook](2a_hess_data_reduction.ipynb).

Fermi-LAT dataset creation and analysis setup
[Link to the notebook](2b_fermi_lat_dataset_creation).


<a name="catalog"></a>
## Session of Wednesday, 14h00/15h45
**Joint analysis - Source detection and model selection**

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

Multi-instrument TS maps, source detection using pattern recognition techniques
[Link to open problems](3a_joint_analysis_source_detection.ipynb).

Alternative hypotheses testing, model selection
[Link to open problems](3b_joint_analysis_model_selection.ipynb).


<a name="mia"></a>
## Session of Wednesday, 16h15/18h
**Timing analysis** : handling light curves

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

Link to the notebook

<a name="diffuse"></a>
## Session of Thursday, 9h30/10h45
**Diffuse emisison and source population models**

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

Link to the notebooks.

<a name="mia"></a>
## Session of Thursday, 11h15/12h30
**Joint analysis - Custom models and multi-instrument systematics**: joint crab analysis, limitations to combine different instruments,
systematics, Priors

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

Link to the notebooks.

<a name="nested"></a>
## Session of Thursday, 14h00/15h45
**Nested sampling** : joint crab analysis, nested sampling

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

Link to the notebooks.

<a name="ml"></a>
## Session of Thursday, 16h15/18h
**Machine-learning representation of physical models** : Custom models, ML surrogate model training

Made by Quentin Remy (MPIK, Heidelberg) and Régis Terrier (APC, Paris). Location : room CIAS, Observatoire de Meudon

[Link to open problems](8_ML_NaimaSurrogate.ipynb).
