# BIOMD0000000055: Locke2005_CircadianClock

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000055.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000055.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000055 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Locke2005 - Circadian Clock

SBML model of the interlocked feedback loop network

The model describes the circuit depicted in Fig. 4 and reproduces the
simulations in Figure 5A and 5B. It provides initial conditions, parameter
values and rules for the production rates of the following species: LHY mRNA
(cLm), cytoplasmic LHY (cLc), nuclear LHY (cLn), TOC1 mRNA (cTm), cytoplasmic
TOC1 (cTc), nuclear TOC1 (cTn),X mRNA (cXm), cytoplasmic X (cXc), nuclear X
(cXn), Y mRNA (cYm), cytoplasmic Y (cYc), nuclear Y (cYn), nuclear P (cPn).
This model was successfully tested on MathSBML and SBML ODE Solver.

Fig 5B is not in the right phase. However, the data is correct relative to the
light/dark bars at the top of the figure.

This model is described in the article:

[Extension of a genetic network model by iterative experimentation and
mathematical analysis.](http://identifiers.org/pubmed/16729048)

Locke JC, Southern MM, Kozma-Bognár L, Hibberd V, Brown PE, Turner MS, Millar
AJ

Molecular Systems Biology [2005; 1: 2005.0013]

Abstract:

Circadian clocks involve feedback loops that generate rhythmic expression of
key genes. Molecular genetic studies in the higher plant Arabidopsis thaliana
have revealed a complex clock network. The first part of the network to be
identified, a transcriptional feedback loop comprising TIMING OF CAB
EXPRESSION 1 (TOC1), LATE ELONGATED HYPOCOTYL (LHY) and CIRCADIAN CLOCK
ASSOCIATED 1 (CCA1), fails to account for significant experimental data. We
develop an extended model that is based upon a wider range of data and
accurately predicts additional experimental results. The model comprises
interlocking feedback loops comparable to those identified experimentally in
other circadian systems. We propose that each loop receives input signals from
light, and that each loop includes a hypothetical component that had not been
explicitly identified. Analysis of the model predicted the properties of these
components, including an acute light induction at dawn that is rapidly
repressed by LHY and CCA1. We found this unexpected regulation in RNA levels
of the evening-expressed gene GIGANTEA (GI), supporting our proposed network
and making GI a strong candidate for this component.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by: [BIOMD0000000055](http://www.ebi.ac.uk/biomodels-
main/BIOMD0000000055) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


