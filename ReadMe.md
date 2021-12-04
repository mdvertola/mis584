# Environment Setup
1. Make sure to have anaconda CLI installed
2. Run commmand `conda activate`
    1. this should display a (base) in front of your user
3. `cd` to the location where this project is located
4. Run command `conda env create -f env.yml`
5. Double check that packages are installed without errors



# External Dependencies
## GraphViz is both a python package and native program and must be installed seperately

### Mac Install
1. Ensure that `homebrew` is installed
2. If intel Mac
    1. run `brew install graphviz`
3. If M1 Mac
    1. run `arch -arm64 brew install graphviz`

### Windows Install
1. Download links can be found here:
    1. `https://graphviz.org/download/`


# Running the Code
1. Run command `conda activate mis584`
2. Run command `jupyter notebook`

