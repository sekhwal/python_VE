python_VE
Python Virtual Environments in Ubuntu

Creating a Python Virtual Environment
	conda create -n python_env python=3.10.4
	
Using the Virtual Environment
	conda activate python_env

Listing Virtual Environments
	conda env list

Listing Packages Installed in a Virtual Environment
	conda list

Installing Packages to a Virtual Environment
	Approach 1: List the packages on the terminal
		pip3 install numpy==1.22.3 pandas==1.4.2

  Approach 2: List the package list from a text file
	create a text file using nano editor
		nano requirement.txt
		cat requirement.txt
			scipy
			matplotlib
			scikit-learn
		pip install -r requirement.txt
Test the installed packages
	creating a python file
	touch test.py
	python test.py
