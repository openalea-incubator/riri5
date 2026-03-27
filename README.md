=========================
README for RIRI5
=========================

This is RIRI5 model, an adaptation of the RIRI model in python for simple sky discretisations (diffuse sky) and multi-species canpies

See 
Sinoquet, H., Le Roux, X., Adam, B., Ameglio, T., & Daudet, F. A. (2001). RATP: a model for simulating the spatial distribution of radiation absorption, transpiration and photosynthesis within canopies: application to an isolated tree crown. Plant, Cell & Environment, 24(4), 395-406.
Louarn, G., Escobar-Gutiérrez, A., Migault, V., Faverjon, L., & Combes, D. (2014). “Virtual grassland”: an individual-based model to deal with grassland community dynamics under fluctuating water and nitrogen availability. The future of european grasslands, 242.



### Installation


First, **Conda** needs to be installed. It is a package manager that can be installed on Linux, Windows, and Mac. we recommand to install [miniforge](https://github.com/conda-forge/miniforge).

#### for user
Creating a new conda environment with riri5 and its dependencies installed
```bash
mamba create -n riri5 -c openalea3/label/dev -c openalea3 -c conda-forge openalea.riri5
```

#### for developer
```bash
mamba env create -f ./conda/environment.yml
```
This will create a conda environment with dependencies installed and install riri5 in editable state.

### 1.3 Running

To run a simulation example :

* 1. place yourself in folder `riri5\riri5\test`
  2. run from the console:
		```bash
        python test_riri_homogene.py
		python test_riri.py
        ```

## 2. Reading the docs

To build the user and reference guides:


## 3. Testing

The test allows to verify that the model implementation accurately 
represents the developer’s conceptual description of the model and its solution.


## Contact

For any question, send an email to <gaetan.louarn@inrae.fr>.


## Authors

**Gaëtan LOUARN**, **Didier Combes** - see file [AUTHORS](AUTHORS) for details

## License

This project is licensed under the CeCILL-C License - see file [LICENSE](LICENSE) for details
