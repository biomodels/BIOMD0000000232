# BIOMD0000000232: Nazaret2009_TCA_RC_ATP

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000232.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000232.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000232 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Mitochondrial energetic metabolism: a simplified model of TCA cycle with ATP production.**   
Nazaret C, Heiske M, Thurley K, Mazat JP _J. Theor. Biol._ 2009
Jun;258(3):455-64 [19007794](http://www.ncbi.nlm.nih.gov/pubmed/19007794) ,  
**Abstract:**   
Mitochondria play a central role in cellular energetic metabolism. The
essential parts of this metabolism are the tricarboxylic acid (TCA) cycle, the
respiratory chain and the adenosine triphosphate (ATP) synthesis machinery.
Here a simplified model of these three metabolic components with a limited set
of differential equations is presented. The existence of a steady state is
demonstrated and results of numerical simulations are presented. The relevance
of a simple model to represent actual in vivo behavior is discussed.


