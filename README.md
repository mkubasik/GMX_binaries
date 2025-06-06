# GMX_binaries
Compilations of GROMACS for GPU Hardware of Google Colab (T4, as of 6/6/2025).

To run these resources, a Google gmail account is required.  As of 6/6/2025, gmail accounts provide access to Colab as well as Google Drive.

To run a Gromacs tutorial of protein simulation, scaffolded in a Jupyter notebook on Colab, open the notebook "GMX_FirstTutorial" right here on GitHub.  There is a link in the file that will load this notebook into Google Colab.

This notebook will load and position precompiled gromacs binaries on a Colab instance running metered T4 GPU acceration.  If the command "gmx --version" of the notebook fails to provide output, then Gromacs is not installed properly.  Two options:

* Please try again...sometimes Google's resources fail to perform on a first try.
* Alternatively, it is possible updates to the Colab ecosystem are incompatible with the posted binaries.  If you suspect an incompatibility, the notebook "Compile_Gromacs..." may be downloaded to recompile Gromacs.  It may take an hour or more to compile Gromacs on Colab, consuming a great deal of a day's free GPU access.  



