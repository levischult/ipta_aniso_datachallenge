# IPTA Anisotropy Data Challenge
Repo containing scripts, notebooks, and datasets for validating anisotropy analyses in discovery

Hello! Welcome and thank you for your interest in helping test the next generation of anisotropy search software! We have a lot to test, so check [this spreadsheet](https://docs.google.com/spreadsheets/d/1hOY8cTVAbK4HB3_8zVXUWulZvwcu5ylcfTzf06Grm-w/edit?usp=sharing) and get in touch on the IPTA Slack (#ipta_dr3_anisotropy)

## 1 - installation
1. Clone this repo
2. Clone [Levi's fork of discovery](https://github.com/levischult/discovery) which is the home for the anisotropy tools as of now.
3. Set up a conda/mamba virtual environment
  - mamba create --name=jhpds_0 python=3.12
  - mamba activate jhpds_0
  - pip install jax[cuda12]
  - pip install jax-healpy
  - cd discovery
  - pip install -e .
  - pip install git+https://github.com/nanograv/enterprise_extensions@master
  - mamba install ipykernel numpyro sympy corner
  - pip install git+https://github.com/GersbachKa/defiant


## 2 - Example Notebooks:
  - examples/ has notebooks to demonstrate how to set up broad/narrowband models.
  - ORF cookbook notebook demonstrates each basis currently implemented.

## 3 - Pick a model to test!
  - There are a [multitude of combinations to test](https://docs.google.com/spreadsheets/d/1hOY8cTVAbK4HB3_8zVXUWulZvwcu5ylcfTzf06Grm-w/edit?usp=sharing)! Broad/Narrow and any of the many bases.
  - Contact Levi or Serena to claim or comment on the sheet linked above!
