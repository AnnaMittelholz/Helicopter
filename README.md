
**[summary](#summary) | [contents](#contents) | [usage](#usage) | [running the notebooks](#running-the-notebooks) | [issues](#issues)**

[![License](https://img.shields.io/github/license/simpeg-research/mars-mag-2021.svg)](https://github.com/simpeg-research/mars-mag-2021/blob/main/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)

# Helicopter

## Summary

This notebook simulates and inverts 3 component magnetic field data collected over a crater on Mars in halfspace. We assume there is no inducing field and that the block is remanently magnetized.  

## Contents

There is one notebook in this repository:

- [mvi_CraterScenario.ipynb](mvi_CraterScenario)

## Usage

To run the notebooks locally, you will need to have python installed,
preferably through [anaconda](https://www.anaconda.com/download/). Please download 
Python 3.7 or greater. 

Once you have downloaded and installed anaconda, you can then clone this repository. 
From a command line (if you are on windows, please use the anaconda terminal that came with the installation)
run

```
git clone https://github.com/AnnaMittelholz/Helicopter.git
```

Then `cd` into the `Helicopter` directory:

```
cd Helicopter
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate mars-mag
```

You can then launch Jupyter. If you prefer the classic notebook, you can use:

```
jupyter notebook
```

or for JupyterLab

```
jupyter lab
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

<img src="https://em.geosci.xyz/_images/run_all_cells.png" width=80% align="middle">

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

If you are new to Python, I highly recommend taking a look at:
- [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/)
- [The Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)

## Issues

Please [make an issue](https://github.com/simpeg-research/mars-mag-2021/issues) if you encounter any problems while trying to run the notebooks.
