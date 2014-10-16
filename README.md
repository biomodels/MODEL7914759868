# MODEL7914759868: Sachse2008_FibroblastInteractingMyocytes

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL7914759868.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL7914759868.git@20140916`

## Usage

Importing the model package.

`import MODEL7914759868 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Electrophysiological modeling of fibroblasts and their interaction with myocytes.**   
Sachse FB, Moreno AP, Abildskov JA. _Ann Biomed Eng._ year volume page
[17999190](http://www.ncbi.nlm.nih.gov/pubmed/17999190) ,  
**Abstract:**   
Experimental studies have shown that cardiac fibroblasts are electrically
inexcitable, but can contribute to electrophysiology of myocardium in various
manners. The aim of this computational study was to give insights in the
electrophysiological role of fibroblasts and their interaction with myocytes.
We developed a mathematical model of fibroblasts based on data from whole-cell
patch clamp and polymerase chain reaction (PCR) studies. The fibroblast model
was applied together with models of ventricular myocytes to assess effects of
heterogeneous intercellular electrical coupling. We investigated the
modulation of action potentials of a single myocyte varying the number of
coupled fibroblasts and intercellular resistance. Coupling to fibroblasts had
only a minor impact on the myocyte's resting and peak transmembrane voltage,
but led to significant changes of action potential duration and upstroke
velocity. We examined the impact of fibroblasts on conduction in one-
dimensional strands of myocytes. Coupled fibroblasts reduced conduction and
upstroke velocity. We studied electrical bridging between ventricular myocytes
via fibroblast insets for various coupling resistors. The simulations showed
significant conduction delays up to 20.3 ms. In summary, the simulations
support strongly the hypothesis that coupling of fibroblasts to myocytes
modulates electrophysiology of cardiac cells and tissues.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **sachse, moreno, abildskov.(2008) - version05**
](http://www.cellml.org/models/sachse_moreno_abildskov_2008_version05)  
The original CellML model was created by:  
**Lloyd, Catherine, May**   
c.lloyd@auckland.ac.nz  
The University of Auckland  
Auckland Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


