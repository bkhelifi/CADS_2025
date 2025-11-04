# Timing analysis

See `exercise.ipynb` notebook in this folder.

## Prerequisites

### Dependencies

For this tutorial, we will need a few extra python packages (such as `astroquery` to query Virtual Observatory services). We recommend using `pixi` to manage the analysis environment (https://pixi.sh/latest/).

Make sure you are in the directory where the `pixi.toml` and `pixi.lock` files are located. Then to prepare the environment do:

```
pixi install
```

Then you can open JupyterLab with:

```
pixi run jupyter lab
```

Alternatively, you can use mamba/conda installers like [miniforge](https://github.com/conda-forge/miniforge).

### Dataset

For this exercise, we will make use of a subset of the data from the CTAO internal Science Data Challenge that can be downloaded from [this Google Drive link](https://drive.google.com/drive/folders/1DcYodVFFJR6V09Kli9ytZJSQdgOwCegm?usp=drive_link).

It is recommended to place the folder at the root of the school repository as it will be shared among different tutorials. From this directory it should be located at `../../CTA-SDC-school` and contain:

```
CTA-SDC-school/
├── CALDB/
├── hdu-index.fits.gz
├── obs-index.fits.gz
└── products_SDC/
```
