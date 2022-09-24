# Understanding the structure of cities through the lens of data

### SDSS 2022 Workshop 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7109016.svg)](https://doi.org/10.5281/zenodo.7109016)



### [Martin Fleischmann](https://martinfleischmann.net)<sup>1,2,3</sup> & [James D. Gaboardi](https://www.ornl.gov/staff-profile/james-d-gaboardi)<sup>4</sup>

1. Geographic Data Science Lab, University of Liverpool
2. Urban and Regional Laboratory, Charles University
3. UrbanDataLab AG, Zurich
4. Oak Ridge National Laboratory

## Annotation

Martin & James will walk you through the fundamentals of analysis of the structure of cities. You will learn what can be measured, how to do that in Python, and how to use those numbers to capture the patterns that make up cities. Using a real-life example, you will learn every step of the method, from data retrieval to detection of individual patterns.

## Setting up to follow the tutorial

### Run online

Open in an interactive in-browser environment: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinfleis/sdss22-workshop/HEAD?labpath=demo-notebook.ipynb)

### Run locally

#### Step 1: download the tutorial material

If you are a git user, you can get the tutorial materials by cloning this repo:

```bash
git clone https://github.com/martinfleis/sdss22-workshop.git
cd sdss22-workshop
```

Otherwise, to download the repository to your local machine as a zip-file, click the
`download ZIP` on the repository page
<https://github.com/martinfleis/sdss22-workshop> (green button "Code"). After
the download, unzip on the location you prefer within your user account (e.g. `My
Documents`, not `C:\`).

#### Step 2: install the required Python packages

To follow the tutorial, we recommend to create a `conda` environment to ensure you have
all the required packages installed (the [environment.yml](environment.yml) file list
the required packages).

If you do not yet have `conda` installed, you can install miniconda
(<https://conda.io/miniconda.html>) or the (larger) Anaconda distribution
(<https://www.anaconda.com/download/>).

Using conda, we recommend to create a new environment with all packages using the
following commands (after cloning or downloading this Github repo and navigating to the
directory, see above):

```bash
# setting the configuation so all packages come from the conda-forge channel
conda config --add channels conda-forge
conda config --set channel_priority strict
# creating the environment
conda env create --file environment.yml
# activating the environment
conda activate sdss2022
```

In case you do not want to install everything and just want to try out the course
material, use the environment setup by Binder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinfleis/sdss22-workshop/main?urlpath=lab/) and open the notebook right away.

#### Step 3: starting Jupyter Lab

The tutorial itself is a [Jupyter notebook](http://jupyter.org/), an interactive
environment to write and run code.

In the terminal, navigate to the `sdss22-workshop` directory (downloaded or
cloned in the previous section)

Ensure that the correct environment is activated.

```bash
conda activate sdss2022
```

Start a jupyter notebook server by typing

```bash
jupyter lab
```

## Acknowledgement

The following acknowledgement applies to James D. Gaboardi (affiliation 4) only:

> This manuscript has been authored in part by UT-Battelle LLC under contract DE- AC05-00OR22725 with the US Department of Energy (DOE). The US government retains and the publisher, by accepting the article for publication, acknowledges that the US government retains a nonexclusive, paid-up, irrevocable worldwide license to publish or reproduce the published form of this manuscript, or allow others to do so, for US government purposes. DOE will provide public access to these results of federally sponsored research in accordance with the DOE Public Access Plan (<http://energy.gov/downloads/doe-public-access-plan>).
