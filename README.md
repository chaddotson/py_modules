# py_modules
A repository of scripts that make python look for modules similarly to node.


## Installing Packages
Until a pip wrapper can be completed, packages using py_modules should be installed with the py_modules prefix similar to the following.

pip install --install-option="--prefix=$(PWD)/py_modules" _PACKAGE_ 

or 

pip3 install --install-option="--prefix=$(PWD)/py_modules" _PACKAGE_

## Current Shortfalls
- source [PATH_TO_ACTIVATE]/activate must be ran from the directory containing the py_modules directory.
