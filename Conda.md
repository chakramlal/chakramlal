Conda cheat sheet: https://bit.ly/3oH9mAg
Check conda version: conda info
Update conda to the current version:  conda update -n base conda
List all conda environments: conda env list
Create a new environment named ENVNAME with the latest Python version:  conda create -n ENVNAME python
Create a new environment named ENVNAME with the a specific Python version:  conda create -n ENVNAME python=3.8
Activate a name Conda environment: conda activate ENVNAME
Deactivate the current Conda environment: conda deactivate
List all package and version in the active environment:  conda list
Delete an entire environment: conda remove -n ENVNAME --all
Install package from conda-forge:  conda install PKGNAME -c conda-forge
Install package  by exact version number:  conda install PKGNAME==3.1.4 -c conda-forge
Remove a package from an environment:  conda uninstall PKGNAME -n ENVNAME