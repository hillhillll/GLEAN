# GLEAN

Group Level Exploratory Analysis of Networks                              
Adam Baker 2015

GLEAN is a MATLAB pipeline for identifying patterns of covariation from M/EEG band-limited power using a Hidden Markov Model (HMM) or Independent Component Analysis (ICA), written for [SPM12](http://www.fil.ion.ucl.ac.uk/spm/software/spm12/).

Please refer to the [wiki](../../wiki/Home) for more information.

### Update notes

Previous versions of GLEAN did not have the package folder `+glean`. Legacy code can be updated by replacing underscores with a dot. For example

	glean_run

becomes

	glean.run


Previous versions also included an internal copy of [HMM-MAR](https://github.com/OHBA-analysis/HMM-MAR/) and [MEG-ROI-nets](https://github.com/OHBA-analysis/MEG-ROI-nets). These now need to be set up as prerequisites for GLEAN.

### Setup

To set up from GitHub, perform the following

- Clone this repository
- Clone `https://github.com/OHBA-analysis/osl-external`
- Add this repository to your path e.g.

		addpath('some_directory/GLEAN')

- Run

	glean_startup
	
