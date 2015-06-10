# Torch

## Cloning & Pulling Submodules

As this repo links to other repos by a different organisation, use the following command to clone both it and those it links to (the practicals):

	git clone --recursive https://github.com/cdt-data-science/torch-resources.git

If you have already cloned the repo and found the practical folders empty, simply run:

	git submodule update --init --recursive

The above command will recursively update all submodules to the latest version the authors have published to github.