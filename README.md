# BIOMD0000000475: PRR_model

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000475.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000475.git@20140916`


# Model Notes
Mechanistic model of the Post-Replication Repair (PRR), the pathway involved
in the bypass of DNA lesions induced by sunlight exposure and UV radiation.
PRR acts through two different mechanisms, activated by mono- and poly-
ubiquitylation of the DNA sliding clamp, called Proliferating Cell Nuclear
Antigen (PCNA). This model has been defined according to the stochastic
formulation of chemical kinetics [Gillespie DT, J Phys Chem 1977,
81(25):2340-2361], which requires to specify the set of molecular species
occurring in the pathway and their respective interactions, formally described
as a set of biochemical reactions. The volume considered for this system is 1
.666667e-17L; this value can be used to convert the model into the
deterministic formulation.


