# LANL Executorlib Tutorial 
Tutorial to introduce executorlib at Los Alamos National Laboratory (LANL) on Wednesday May 27th 2026. 

| [Repository](https://github.com/pyiron/executorlib) | [Documentation](https://executorlib.readthedocs.io) | [DeepWiki](https://deepwiki.com/pyiron/executorlib) | [Publication](https://joss.theoj.org/papers/10.21105/joss.07782) | 
|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|------------------------------------------------------------------|

Additional links for this tutorial: 

| [Repository](https://github.com/pyiron-workshop/lanl-executorlib-tutorial/) | Website | [Mybinder](https://notebooks.mpcdf.mpg.de/binder/v2/gl/janj%2Flanl-executorlib-tutorial/HEAD) |
|-----------------------------------------------------------------------------|---------|----------|

The goal of the tutorial is to provide a general introduction to executorlib to simplify the submission of Python functions to a job scheduler, like Simple Linux Utility for Resource Management (SLURM). 

## Requirements
The participants should be familiar with:
* SLURM - the general usage of SLURM and specifically commands like `srun`, `sbatch` and `squeue`.
* Python - is the programming language we are going to use in this tutorial.
* `mpi4py` - as a first introduction to the Message Passing Interface (MPI), we are going to use the `mpi4py` library. 

## Computing Environment 
To accelerate the setup of the computing environment we are going to first use a shared environment which you can access from your webbrowser. In the later part you can configure `executorlib` with your High Performance Computing (HPC) cluster of choice. A detailed explanation of the executorlib installation is available as part of the [documentation](https://executorlib.readthedocs.io/en/latest/installation.html).
