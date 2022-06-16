# README #

### What is this repository for? ###

* This is the BioMechPro pipeline (with newly developed modules) for processing both the optical motion capture system in the Lopes lab and 
  the data from the wearable kinetic measurement system (Xsens + Moticon pressure insoles).
* This pipline is based on a developed framework in UT BE group. Orginal repo can be found here: https://bitbucket.org/ctw-bw/biomechpro/wiki/Home
* 1.0

### How do I set up? ###

* Check Wiki of the origional BioMechPro pipeline for basic operation [guidline](https://universiteittwente-my.sharepoint.com/:f:/r/personal/h_wang-2_utwente_nl/Documents/Research/BioMechPro_Intro?csf=1&web=1&e=TC5apc)
* Download this repository
* Download the experimental data from here: https://doi.org/10.5281/zenodo.6457662
* Add the folder and all subfolder into your Matlab path
* Open the 'DataProcessing_AllSubjsAllTrails.mat'
* Change the settings inside the GUI
* Run each module inside the GUI

### Outputs ###
* Processed dataset in the shared Zenodo project: https://doi.org/10.5281/zenodo.6457662

### Attentions ###
* To use this pipeline, there is no need to link Matlab and OpenSim, just provide the OpenSim installation path is fine
* OpenSim does not like 'space' in both file paths and names, please avoid it, in order to make IK and ID work

### Contribution guidelines ###
* push corrections
* Clone the development branch and push new modules

### Who do I talk to? ###
* Huawei Wang: h.wang-2@utwente.nl
