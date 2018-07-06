# MiniDataChalgAtmosphere
Directory to buid a mini data challenge to estimate atmospheric parameters

- author Sylvie Dagoret-Campagne
- - affiliation : LAL/IN2P3/CNRS
- creation date April 12th 2018
- update July 6th 2018


## Notebook to do the job

### 1) Generate atmospheric conditions for a given field given its cadence program
- ***GenerateCadenceAtmProgram.ipynb***	

### 2) Generate atmospheric simulation into a fits file
- ***MiniDataChallengeSteer\_Atmosphere.ipynb***

### Control of the production (deprecated)
- ***MiniDataChallengeSteer.ipynb	***
- ***MiniDataChallengeSteer2.ipynb***
- ***MiniDataChallengeSteer_AuxTel.ipynb***	



### Example to show the chain from SED to magnitudes (deprecared)
-***ShowColorPlot\_libcolors.ipynb***
the calculation of mafnitudes will be done in the framework of lsstsim


## subdirectorues


### atmparamsim:
tool to generate atmospheric parameter simulation for LSST site

### libradtransim
interface to libradtran simulation

### lsstphotometry
tool to calculate LSST photometry


### LSSTFiltersKG (deprecated, use now LSST SIMS)
LSST filters	

### cadence
Tool to extract from a LSST observation program cadence the relevant parameters into a csv file				

##pysynphotsed
SED based on pysynphot
now use pickles


### to remember:

git remote set-url origin git@github.com:LSSTDESC/MiniDataChalgAtmosphere.git





