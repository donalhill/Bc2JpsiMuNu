# Bc2JpsiMuNu
This repository contains notebooks for the analysis of Bc -> J/psi mu nu Monte Carlo. The notebooks were created using [Google Colab](colab.research.google.com), and they use ROOT MC files stored in my own [Google Drive](https://drive.google.com/drive/folders/1Q25PuAGMSjAmTNaOSblGBS0UZ3Z7yk8X?usp=sharing). To work with these files in Colab, you should copy them to a location on your own Google Drive.

Using Google Colab for analysis means we don't need to worry about any Python environment setup, and it also lets us run some commands on the command line to install packages we need such as [zfit](https://zfit.readthedocs.io/en/0.3.6/index.html). For further work, you are welcome to use Google Colab notebooks, Jupyter notebooks, or write your own Python scripts and executre them in a terminal.

## Overview of notebooks

The notebooks can be studied in the order they appear in the table below.

|Notebook |Content|
|-----|--------|
|[Bc2JpsiMuNu_RapidSim](https://github.com/donalrinho/Bc2JpsiMuNu/blob/main/Bc2JpsiMuNu_RapidSim.ipynb)| Load RapidSim MC, plot some variables, and calculate some new variables       |
|[Bc2JpsiMuNu_RapidSim_fit](https://github.com/donalrinho/Bc2JpsiMuNu/blob/main/Bc2JpsiMuNu_RapidSim_fit.ipynb)| Fit the truth-level 3D decay angle distribution using zfit, to measure helicity amplitudes       |
| [Bc2JpsiMuNu_RapidSim_LHCb](https://github.com/donalrinho/Bc2JpsiMuNu/blob/main/Bc2JpsiMuNu_RapidSim_LHCb.ipynb)| Load RapidSim MC generated inside LHCb acceptance, and calculate truth-level and reconstructed angles and q2 |
| [Bc2JpsiMuNu_RapidSim_LHCb_template_weights](https://github.com/donalrinho/Bc2JpsiMuNu/blob/main/Bc2JpsiMuNu_RapidSim_LHCb_template_weights.ipynb) | Calculate per-event weights to make templates for each angular term |
| [Bc2JpsiMuNu_RapidSim_LHCb_templates](https://github.com/donalrinho/Bc2JpsiMuNu/blob/main/Bc2JpsiMuNu_RapidSim_LHCb_templates.ipynb) | Use per-event weights to make 3D histogram templates for each angular term |

## Useful links

* [Python tutorials for high-energy physics](https://hsf-training.github.io/analysis-essentials/python/README.html)
* [scikit-hep for info on different high-energy physics software](https://scikit-hep.org)
* [scikit-learn for machine learning](https://scikit-learn.org)
* [ROOT for information on ROOT files and CERNs analysis software](https://root.cern)
* [zfit for maximum-likelihood fitting in Python](https://zfit.readthedocs.io/en/0.3.6/index.html)
* [The LHCb experiment](https://lhcb-outreach.web.cern.ch/)
