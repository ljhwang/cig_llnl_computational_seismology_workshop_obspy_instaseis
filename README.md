# ObsPy and Instaseis Tutorials for the CIG/LLNL Workshop in Computational Seismology

## Installation

You basically need a version of Python (best 3.5 or 3.6), ObsPy (http://obspy.org), the Jupyter notebooks (http://jupyter.org/), and Instaseis (http://instaseis.net).

We strongly recommend you install via `conda`. Follow these instructions here to install `conda` as well as `ObsPy`: https://github.com/obspy/obspy/wiki/Installation-via-Anaconda

Once this is installed, you can install the Jupyter notebooks and Instaseis with:

```bash
$ conda install -c conda-forge instaseis jupyter basemap-data-hires
```

Please note that we currently have no Windows packages for `instaseis` so please just installing it it if you are running windows.

Alternatively you can also use a bundled `conda` installer that comes with ObsPy and the Jupyter notebook: https://github.com/obspy/obspy/wiki/Installation-via-ObsPy-bundled-Anaconda-installer

In that case only Instaseis has to be installed in addition to it:

```bash
$ conda install -c conda-forge instaseis
```

## Running the Notebooks

Make sure the correct `conda` environment is active.

```bash
$ source activate NAME_OF_ENV
```

Then launch the notebooks from within the repository folder.

```bash
$ git clone https://github.com/krischer/cig_llnl_computational_seismology_workshop_obspy_instaseis.git
$ cd cig_llnl_computational_seismology_workshop_obspy_instaseis
$ juypter notebook
```
