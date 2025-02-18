# Automated Mechanisms and Kinetics (AutoMeKin)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/emartineznunez/AutoMeKin/blob/main/notebooks/AutoMeKin.ipynb) [![Download AutoMeKin](https://img.shields.io/sourceforge/dm/automekin.svg)](https://sourceforge.net/projects/automekin/files/latest/download) [![Sylabs - AutoMeKin](https://img.shields.io/badge/Sylabs-AutoMeKin-2ea44f)](https://cloud.sylabs.io/library/emartineznunez/default/automekin) [![DOI](https://zenodo.org/badge/476189550.svg)](https://zenodo.org/doi/10.5281/zenodo.10674957)





### This is the official repository of the automated reaction discovery program **AutoMeKin**[^1].

<p align="left">
   <img src="logo.png" alt="alt text" width="200" height="100">
</p>


AutoMeKin (formerly tsscds) has been designed to discover reaction mechanisms in an automated fashion. Transition states are located using MD simulations and Graph Theory algorithms. Monte Carlo simulations afford kinetic results. The only input is a starting structure in XYZ format. The method is described in these two publications: [1](https://onlinelibrary.wiley.com/doi/abs/10.1002/jcc.23790) [2](https://pubs.rsc.org/en/content/articlelanding/2015/cp/c5cp02175h#!divAbstract). At present [MOPAC2016](https://github.com/openmopac/mopac), [Entos Qcore](https://software.entos.ai/qcore/documentation/) and [Gaussian (G09/G16)](https://gaussian.com/) are interfaced with AutoMeKin. The program has been tested on the following Linux distros: CentOS 7, Red Hat Enterprise Linux and Ubuntu 20.04 LTS.

## Content
- [Installation and documentation](#inst)
- [Main developer](#dev)
- [Simple examples in Colab](#colab)
- [Web for submitting simple examples](#web)

## Installation and documentation <a name="inst"></a>
The installation instructions and much more are [detailed here](https://emartineznunez.github.io/AutoMeKin)

## Main developer<a name="dev"></a>

[Emilio Martínez-Núñez](https://emartineznunez.github.io/) (Santiago de Compostela, Spain) emilio.nunez@usc.gal

## Simple example in Colab<a name="colab"></a>
You can have a look at this [Notebook](https://colab.research.google.com/github/emartineznunez/AutoMeKin/blob/main/notebooks/AutoMeKin.ipynb) to install it, test a simple example and more...

This second [Notebook](https://colab.research.google.com/github/emartineznunez/AutoMeKin/blob/main/notebooks/AutoMeKin2.ipynb) can be used to try some further tests.

## Web site for submitting simple examples<a name="web"></a>
You can also test our [web site](https://rxnkin.usc.es/amk/), where you can submit a simple example.

[^1]: For enquiries please contact: emilio.nunez@usc.gal
