<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Digital Earths Global Hackathon: Land-Atmosphere and Hydrology Applications Cookbook

[![nightly-build](https://github.com/ProjectPythia/land-atmosphere-interactions-and-hydrology-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/land-atmosphere-interactions-and-hydrology-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/land-atmosphere-interactions-and-hydrology-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook contains a collection of computational notebooks for land-atmosphere and hydrology applications from the NSF NCAR node of the 2025 Digital Earths Global Hackathon.

## Authors

[Erik Janzon](@ejanzon), [Yifan Cheng](@Charlotte1891), [Aashish Panta](@aashishpanta0), and [Katelyn FitzGerald](@kafitzgerald)

### Contributors

<a href="https://github.com/ProjectPythia/land-atmosphere-interactions-and-hydrology-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/land-atmosphere-interactions-and-hydrology-cookbook" />
</a>

## Structure

Includes our work in progress notebooks for the time being.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/land-atmosphere-interactions-and-hydrology-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/land-atmosphere-interactions-and-hydrology-cookbook.git
   ```

1. Move into the `land-atmosphere-interactions-and-hydrology-cookbook` directory
   ```bash
   cd land-atmosphere-interactions-and-hydrology-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate land-atmosphere-interactions-and-hydrology-cookbook-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
