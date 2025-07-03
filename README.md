# Metemgee

Jacobo de la Cuesta-Zuluaga. August 2024.

`Metemgee` is the workflow for the obtention of taxonomic and
functional profiles of the Maier Lab. For functional profiles,
it implements the `nf-core` pipeline `taxprofiler` available
[here](https://nf-co.re/taxprofiler). For functional profiling,
it uses `mifaser`, found [here](https://bitbucket.org/bromberglab/mifaser),
`paladin`, available [here](https://github.com/ToniWestbrook/paladin).
Alternatively, you can use an assembly-dependant method with the
`nf-core` pipeline `metadenovo`, found [here](https://nf-co.re/metatdenovo/1.2.0)

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
In addition to Jupyter Notebooks, you will need to have the 
ability to create and manage Conda environments. Conda is a 
package and environment management system that allows you to 
install dependencies and manage different project environments
easily.

If you are using this notebook on the M3 HPC you should have
the ability to create Conda environments. 

To create the VScode conda environment from the provided YAML file,
run the following command in your terminal:

```bash
conda env create -f envs/VScode.yaml
```

This command will set up a new environment with all the specified packages.
You only need to create the environment once.

To activate the environment after creation, use:

```bash
conda activate VScode
```

YAML files for other Conda environments necessary to execute the pipelines
are provided in the `/envs` folder. They are created and activated in a similar
way described above.

## Why `Metemgee`?
I was trying to come up with a clever name for this repo and it
proved harder than I thought. Googling around I accidentaly found
this Guyanese dish called _metemgee_, made of cassava, sweet potatoes
and plantains, cooked in seasoned coconut milk. I haven't tried
it yet, but it sounds so so good. Besides, 'metemgee' kinda sounds
like 'meta-g', so I'm going with that.
