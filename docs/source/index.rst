.. svlearn documentation master file, created by
   sphinx-quickstart on Mon Nov  4 22:03:53 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Documentation for svlearn package
=================================

Click :doc:`here </utils>` for list of all functions in Utils module

Installation::

	pip install svlearn==version

Example::

	pip install svlearn==0.0.3.dev1

Upgrade to latest version::

	pip install --upgrade svlearn
	
Upgrade to specific version::

	pip install --upgrade svlearn==version

Usage::

	import pandas as pd
	from svlearn import utils
	df = pd.read_csv("test.csv")
	utils.about_dataframe(df)
	
Documentation

https://svlearn.readthedocs.io/en/latest/

pypi Project URL

https://pypi.org/project/svlearn/

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   
   modules.rst