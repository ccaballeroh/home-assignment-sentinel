## Instructions

1. To reproduce the environment using Anaconda run the following command in an Anaconda Prompt after cloning or downloading this repository and changing directories inside of it.

```
conda env create --file sentinel.yml
```

2. Or if using Windows:

```
conda create --name sentinel --file pkgs.txt
```
**NOTE:** If GPU is available you can install `conda install pytorch cudatoolkit=10.0 -c pytorch` instead of `cpuonly`.

The code in this repository is for an environment with CPU only for ease of reproducibility.

## Notebooks

* First an Exploratory data analysis of the texts is presented in [EDA](./EDA.ipynb).

* Secondly, a transformer-based Language Model is fine-tuned in a text classification task in [Classification](./Classification.ipynb).

