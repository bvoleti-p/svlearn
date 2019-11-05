# svlearn

### Utils module wraps boilerplate code used to perform routine ML related tasks

Installation

	pip install svlearn==version

Example

	pip install svlearn==0.0.3.dev1

Upgrade to latest version

	pip install --upgrade svlearn
	
Upgrade to specific version

	pip install --upgrade svlearn==version

Usage

	import pandas as pd
	from svlearn import utils
	df = pd.read_csv("test.csv")
	utils.about_dataframe(df)
	
Documentation
