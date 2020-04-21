# speckle_contrast

Calculations of the speckle contrast factor in Bragg geometry using methods described in

X. M. Chen et al., Phys. Rev. Lett. 117, 167001 (2016)

https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.117.167001

To check quickly use mybinder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mpmdean/speckle_contrast/master?filepath=Calculate_speckle_contrast_factor.ipynb)


Run on your computer by installing [docker](https://www.docker.com/) and pip and then running

~~~
pip install jupyter-repo2docker
docker pull mpmdean/main
jupyter-repo2docker --editable --image-name jupyter/scipy-notebook .
~~~

The URL should run in any internet browser.  

Change the ending of the url from `tree` to `lab` to switch to the newer JupyterLab interface.


