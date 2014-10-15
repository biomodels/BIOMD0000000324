# BIOMD0000000324: Morris1981_MuscleFibre_Voltage

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000324.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000324.git@20140916`


# Model Notes


This is the full model (eq. 1 and 2) of the voltage oscillations in barnacle
muscle fibers described in the article:  
**Voltage oscillations in the barnacle giant muscle fiber.**   
Morris C, Lecar H. Biophys J. 1981 Jul;35(1):193-213.
PubmedID:[7260316](http://www.ncbi.nlm.nih.gov/pubmed/7260316); DOI:[10.1016/S
0006-3495(81)84782-0](http://dx.doi.org/10.1016/S0006-3495\(81\)84782-0)  
Abstract:  
Barnacle muscle fibers subjected to constant current stimulation produce a
variety of types of oscillatory behavior when the internal medium contains the
Ca++ chelator EGTA. Oscillations are abolished if Ca++ is removed from the
external medium, or if the K+ conductance is blocked. Available voltage-clamp
data indicate that the cell's active conductance systems are exceptionally
simple. Given the complexity of barnacle fiber voltage behavior, this seems
paradoxical. This paper presents an analysis of the possible modes of behavior
available to a system of two noninactivating conductance mechanisms, and
indicates a good correspondence to the types of behavior exhibited by barnacle
fiber. The differential equations of a simple equivalent circuit for the fiber
are dealt with by means of some of the mathematical techniques of nonlinear
mechanics. General features of the system are (a) a propensity to produce
damped or sustained oscillations over a rather broad parameter range, and (b)
considerable latitude in the shape of the oscillatory potentials. It is
concluded that for cells subject to changeable parameters (either from cell to
cell or with time during cellular activity), a system dominated by two
noninactivating conductances can exhibit varied oscillatory and bistable
behavior.

The model consists of the differential equations (1) and (2) given on pages
195 and 196 of the article. There is one typo in the equation for I in (1),
gL(VL) should be gL(V - VL). This was changed in the SBML file. As there are
no current values given, for reproducing the time courses in figure 6 an
applied current of 50 uA was assumed. The legend for the broken and the full
line in this figure seems to be confounded in the article.

Originally created by libAntimony v1.4 (using libSBML 3.4.1)


