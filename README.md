# py_modules
A repository of scripts that make python look for modules similarly to node.

Until a pip wrapper can be completed, packages using py_modules should be installed with the py_modules prefix similar to the following.

pip install --install-option="--prefix=$(PWD)/py_modules" _PACKAGE_ 

or 

pip3 install --install-option="--prefix=$(PWD)/py_modules" _PACKAGE_ 
