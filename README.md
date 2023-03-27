# README
### Analysis scripts for [*Disentangling the Effects of Metabolic Cost and Accuracy on Movement Vigor*](https://www.biorxiv.org/content/10.1101/2023.02.08.527734v2)

### Setup
+ Some data files are git Large File Storage (LFS) objects
  + Once repository is cloned, move into directory and run: `git lfs fetch --all` 
  + LFS objects should be retrieved
+ Currently setup as an R project
  + Including \*.Rproj file in parent directory should allow scripts to run without any changes
+ Line 17 of ***Mass_Tests_Small.Rmd***: `pacman::p_load(<PACKAGES>)` should install and load all packages
  + If there are errors, may need to close \*.Rmd file and install packages indvidually using: `install.packages('<PACKAGE_NAME>')`

### Run analysis
+ Once packages are installed, run ***Mass_Tests_Small.Rmd*** 
  + NOTE: this may take some time to complete  
+ Pre-compiled HTML doc is also included here: ***[Mass_Tests_Small.html](Mass_Tests_Small.html)***

### Additional information
+ If ***Mass_Tests_Small.Rmd*** runs successfully, compiled HTML doc of the same name will be generated
