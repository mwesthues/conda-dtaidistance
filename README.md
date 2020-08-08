# conda-dtaidistance
Recipe for building the [dtaidistance](https://github.com/wannesm/dtaidistance) package for Python 3.8.

## Build it yourself
### Prerequisite
Before building the conda package, you will need to install [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
followed by [conda-build](https://docs.conda.io/projects/conda-build/en/latest/install-conda-build.html).

### Condarize dtaidistance
* Clone this repository.
* Inside the directory containing the content from this repository, run `conda build .`.

## Use a built version
The condarized package (v1.2.2) is available via https://anaconda.org/mwesthues/dtaidistance. 
In your terminal, run:

```shell
conda create --name <environment_name> python=3.8 dtaidistance --channel mwesthues
```

where `<environment_name>` is a placeholder for the environment name of your choice.
