# Installation

You must use conda environment : <https://docs.conda.io/en/latest/index.html>

## Users

### Create a new environment with riri5 installed in there

```bash

mamba create -n riri5 -c openalea3 -c conda-forge  openalea.riri5
mamba activate riri5
```

Install riri5 in a existing environment

```bash
mamba install -c openalea3 -c conda-forge openalea.riri5
```

### (Optional) Test your installation

```bash
mamba install -c conda-forge pytest
git clone https://github.com/openalea/riri5.git
cd riri5/test; pytest
```

## Developers

### Install From source

```bash
# Install dependency with conda
mamba env create -n phm -f conda/environment.yml
mamba activate riri5

# Clone riri5 and install
git clone https://github.com/openalea/riri5.git
cd riri5
pip install .

# (Optional) Test your installation
cd test; pytest
```
