# Current working setup:

matlab R2024b
[Psychtoolbox v3.0.22](http://psychtoolbox.org/download.html) (+ [Gstreamer MSVC](https://gstreamer.freedesktop.org/download/#windows))
Statistic and Machine Learning toolbox (matlab app)
Image Processing toolbox (matlab app)

TO TEST:
matlab R2025a
[Psychtoolbox v3.0.19](https://github.com/Psychtoolbox-3/Psychtoolbox-3/tree/3.0.19.17)

# Commands to run experiment (copy paste into matlab once in dir folder)

cd Experiment/ExploreAndPredict_SSSAS_updated/SSSAS_task
A_NEWSUBJECT
B_LAUNCH_SESSION

# NHBcontrollability

This repository contains the code used to generate the main figures of the paper Stress-sensitive inference of task controllability by Romain Ligneul, Zachary Mainen, Verena Ly* and Roshan Cools*.
In order to display the figures using the scripts contained in the "StatsFigures" folder, you need to clone/download the repository and download the anonymized data by logging with your ORCID at the following address: https://data.donders.ru.nl/collections/di/dccn/DSC_3017049.01_905
The data folder must be placed in the root of this repository and named AnonymizedData.

The folders in "AnalysisFunctions" contain also the code used for computational modeling which is not necessary to generate the figures. The code used to analyze the fMRI data (from preprocessing to second-level analyses) is provided as is and may need a bit of work to run on a new machine. It also requires to download the anonymized data. Please get in touch if you are interested at romain.ligneul@gmail.com

The folder "Experiment" contains the task itself. You need to have Psychtoolbox 3 and GStreamer properly installed to run it. Sets of instructions are provided in English, Dutch and German.

The scripts rely on several external toolboxes which can be found in ExternalTools. The main ones are:

- the VBA toolbox (for VB model fitting): https://mbb-team.github.io/VBA-toolbox/
- the gramm toolbox (for plotting): https://github.com/piermorel/gramm
- the MI toolbox (for information theoretic computations): https://github.com/Craigacp/MIToolbox

Thanks to the authors of these open source tools for their amazing work.
