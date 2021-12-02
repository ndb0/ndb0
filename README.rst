===================
Nilanjandev Bhaumik
===================
:Working in: Early Universe Cosmology
:Institution: IISc Bangalore
:Inspirepage: https://inspirehep.net/authors/1726209
:ORCid: 0000-0003-3541-7263

.. image:: https://img.shields.io/pypi/v/camb.svg?style=flat
        :target: https://pypi.python.org/pypi/camb/
.. image:: https://img.shields.io/conda/vn/conda-forge/camb.svg
   :target: https://anaconda.org/conda-forge/camb
.. image:: https://readthedocs.org/projects/camb/badge/?version=latest
   :target: https://camb.readthedocs.org/en/latest
.. image:: https://travis-ci.org/cmbant/camb.svg?branch=master
  :target: https://travis-ci.org/cmbant/camb/builds
.. image:: https://mybinder.org/badge.svg
  :target: https://mybinder.org/v2/gh/cmbant/camb/master?filepath=docs%2FCAMBdemo.ipynb

Description and installation
=============================

Nilanjandev Bhaumik(nilanjandevbhaumik@gmail.com)'s version setup ::
 :#prerequisite: clik 3.0 must be installed in the same python version and camb need to be run from inflation_CAMB's home folder
 :# steps to install camb: cd Fortran && make clean && make && cd .. && python setup.py clean && python setup.py build && python setup.py install
 :# setup clik and lcdm values: update clikpath and lcdm chains paths for particular datasets inside nilanjan.clik.py
 :# setup the gnmdc parameters: edit inside nilanjan.clik.py accordingly 
 :# allowed free parametrs for inflationary part: 7 ( set_initial_power_table1(self,n,V0,phi0,sigma,coff21,phase,coff16,logterm))
 :# run: python nilanjan.clik.py
 :#output or result: chi^2 values for clik or camspec likelihoods corrsomding to model parameters



CAMB is a cosmology code for calculating cosmological observables, including
CMB, lensing, source count and 21cm angular power spectra, matter power spectra, transfer functions
and background evolution. The code is in Python, with numerical code implemented in fast modern Fortran.

See the `CAMB python example notebook <https://camb.readthedocs.org/en/latest/CAMBdemo.html>`_ for a
quick introduction to how to use the CAMB Python package.



=============

.. raw:: html

    <a href="http://www.sussex.ac.uk/astronomy/"><img src="https://cdn.cosmologist.info/antony/Sussex.png" height="200px"></a>
    <a href="http://erc.europa.eu/"><img src="https://erc.europa.eu/sites/default/files/content/erc_banner-vertical.jpg" height="200px"></a>
    <a href="https://iisc.ac.in/"><img src="https://iisc.ac.in/wp-content/uploads/2020/08/IISc_Master_Seal_Black.jpg" height="200px"></a>
  

