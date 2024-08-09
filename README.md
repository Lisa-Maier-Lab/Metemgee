# Metemgee

Jacobo de la Cuesta-Zuluaga. August 2024.

`Metemgee` is the workflow for the obtention of taxonomic and
functional profiles of the Maier Lab. For functional profiles,
it implements the `nf-core` pipeline `taxprofiler` available
[here](https://nf-co.re/taxprofiler). For functional profiling,
it uses `mifaser`, found [here](https://bitbucket.org/bromberglab/mifaser).

The notebooks walk you through the download of the software, the
creation of files and the execution of the pipelines.

## Requirements for Running the Notebooks
### Jupyter Notebook
To successfully execute the notebooks in this repository, you 
will need to have Jupyter Notebook installed on your system. 
You can run Jupyter Notebooks in two ways:

* Using VSCode (Recommended): you can also run Jupyter Notebooks
    within Visual Studio Code, which provides a user-friendly 
    interface for working with notebooks. If you use this, make
    sure to install the `Remote - SSH` and `Jupyter` extensions

* Standalone Installation: You can install Jupyter Notebook 
    independently on your machine. This allows you to open 
    and run notebooks directly from your local environment.

### Conda
In addition to Jupyter Notebook, you will need to have the 
ability to create and manage Conda environments. Conda is a 
package and environment management system that allows you to 
install dependencies and manage different project environments
easily.

### IRkernel

To execute R notebooks, you must also have the IRkernel available
in the Conda environment you create to run the notebooks. 

## Why `Metemgee`?
I was trying to come up with a clever name for this repo and it
proved harder than I thought. Googling around I accidentaly found
this Guyanese dish called _metemgee_, made of cassava, sweet potatoes
and plantains, cooked in seasoned coconut milk. I haven't tried
it yet, but it sounds so so good. Besides, 'metemgee' kinda sounds
like 'meta-g', so I'm going with that.
