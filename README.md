# Understanding the structure of cities through the lens of data

### SDSS 2022 Workshop

### Martin Fleischmann<sup>1,2,3</sup> & James D. Gaboardi<sup>4</sup>
  
1. Geographic Data Science Lab, University of Liverpool
2. Urban and Regional Laboratory, Charles University
3. UrbanDataLab AG, Zurich
4. Oak Ridge National Laboratory

## Run online

Open in an interactive in-browser environment:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinfleis/sdss22-workshop/HEAD?labpath=demo-notebook.ipynb)

## Run locally

If you want to run the notebook locally, it is recommended to create a new `conda` environment based on the `environment.yml` file.

```
conda env create -f environment.yml
```

Alternatively, ensure that all required dependencies are available in your environment in their latest versions (as of September 22, 2022).

```
- momepy
- pygeos
- osmnx
- clustergram
- bokeh
- scikit-learn
- geopy
- ipywidgets
```

## Annotation

Martin & James will walk you through the fundamentals of analysis of the structure of cities. You will learn what can be measured, how to do that in Python, and how to use those numbers to capture the patterns that make up cities. Using a real-life example, you will learn every step of the method, from data retrieval to detection of individual patterns.

## Acknowledgement

The following acknowledgement applies to James D. Gaboardi (affiliation 4) only:

> This manuscript has been authored in part by UT-Battelle LLC under contract DE- AC05-00OR22725 with the US Department of Energy (DOE). The US government retains and the publisher, by accepting the article for publication, acknowledges that the US government retains a nonexclusive, paid-up, irrevocable worldwide license to publish or reproduce the published form of this manuscript, or allow others to do so, for US government purposes. DOE will provide public access to these results of federally sponsored research in accordance with the DOE Public Access Plan (http://energy.gov/downloads/doe-public-access-plan).
