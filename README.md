# jwst-0.9.6_notebooks

This repository contains Jupyter notebooks demonstrating the use of the JWST calibration pipeline (jwst-0.9.6) for MIRI data within python.

jwst-0.9.6 is the FINAL release of Build 7.1.3 of the JWST calibration pipeline can be installed into an Anaconda environment as follows:

conda create -n jwst --override-channels -c http://ssb.stsci.edu/astroconda-dev -c defaults python=3.6 jwst=0.9.6

The CRDS context should be set to jwst_0468.pmap for this build. Also, standard CRDS environment variables should be set. E.g., for bash:

export CRDS_PATH=/path/to/your/crds

export CRDS_SERVER_URL="https://jwst-crds.stsci.edu"

export CRDS_CONTEXT="jwst_0468.pmap"
