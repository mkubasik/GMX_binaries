

# GROMACS binaries for Google's Colab and RunPod.io
Compilations of GROMACS for GPU Hardware of Google Colab (T4, as of 6/6/2025) and RunPod.io hosting NVIDIA RTX series GPUs.

## Run on Colab (free)

To run these resources on Colab, a Google gmail account is required.  As of 6/6/2025, gmail accounts provide access to Colab as well as Google Drive.

To run a Gromacs tutorial of protein simulation, scaffolded in a Jupyter notebook on Colab, open the notebook "GMX_FirstTutorial" using this link:
<a href="https://colab.research.google.com/github/mkubasik/gmx_on_colab/blob/main/GMX_FirstTutorial.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

This notebook will load and position precompiled gromacs binaries on a Colab instance running metered T4 GPU acceration.  If the command "gmx --version" of the notebook fails to provide output, then Gromacs is not installed properly.  Two options:

* Please try again...sometimes Google's resources fail to perform on a first try.
* Alternatively, it is possible updates to the Colab ecosystem are incompatible with the posted binaries.  If you suspect an incompatibility, the notebook "Compile_Gromacs..." may be downloaded to recompile Gromacs.  It may take an hour or more to compile Gromacs on Colab, consuming a great deal of a day's free GPU access.
  A notebook to compile Gromacs on a T4 instance of Google's colab,according to the "Installation...Quick and Dirty Install", is linked here: 
  <a href="https://colab.research.google.com/github/mkubasik/gmx_on_colab/blob/main/Compile_Gromacs2025_2_Colab_GPU.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Run on RunPod.io

RunPod.io is a paid service providing cloud-based GPU computing.  Request a Pod using an NVIDIA RTX GPU, a RunPod Pytorch template (e.g. 2.4.0), and connect via Jupyter Lab.

Once Jupyter Lab is spun up, open a terminal.  Issue the git command "git clone https://github.com/mkubasik/GMX_on_Runpod".  There are two notebooks:
* One notebook initializes the Pod with resources.  Use provided URL and password to open a NEW Jupyter Lab browser tab.
* Open the Tutorial notebook IN THE NEW TAB, and gromacs should work.


