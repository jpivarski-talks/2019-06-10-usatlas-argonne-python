# https://github.com/jpivarski/2019-06-10-usatlas-argonne-python

Jim's tutorials for U.S. ATLAS Python training at Argonne:

   * Argonne National Lab
   * Building 360 Room A-224
   * 9:00am ‒ 4:30pm

To participate, either install all of the software on your laptop (with [conda](https://docs.conda.io/en/latest/miniconda.html), an isolated environment that you can remove with `conda remove --name usatlas-argonne-python --all`):

```bash
git clone https://github.com/jpivarski/2019-06-10-usatlas-argonne-python.git
cd 2019-06-10-usatlas-argonne-python
conda env create -f environment.yml         # create an isolated environment and install everything
conda activate usatlas-argonne-python       # switch to that environment (maybe "source activate...")
conda install jupyterlab
jupyter lab                                 # runs on your machine, controlled by your web browser
```

or click below to run everything in the cloud: [![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jpivarski/2019-06-10-usatlas-argonne-python/1.4?urlpath=lab)

_(If installation on your laptop fails, use the cloud option. Dependencies for "misc" notebooks not included.)_

## Resources

   * [Scikit-HEP](http://scikit-hep.org/)
   * [IRIS-HEP Awesome List](https://github.com/iris-hep/awesome-hep#awesome-hep)
   * [Python Libraries of Interest to Particle Physicists](https://github.com/hsf-training/PyHEP-resources#python-libraries-of-interest-to-particle-physics)
   * [HEP Software Foundation PyHEP Working Group](https://hepsoftwarefoundation.org/workinggroups/pyhep.html)
   * [PyHEP Gitter channel](https://gitter.im/HSF/PyHEP)
