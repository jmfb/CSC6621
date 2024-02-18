# CSC6621 - Applied Machine Learning

This repository contains all projects and assignments for the 2024 semester 2 course.

## Initialization

Install the latest versions of dependencies via chocolatey

```PowerShell
& choco install python
& choco install mingw
& choco install rust
```

Configure a python virtual environment for the class (from the project directory):

```PowerShell
& python -m venv csc6621
& ./csc6621/Scripts/activate.ps1
& python.exe -m pip install -U pip wheel
& pip install numpy scipy matplotlib pandas scikit-learn `
	seaborn patsy statsmodels jupyter `
	pyarrow `
	graphviz `
	xlrd
```

## Local Development

From the project directory:

```PowerShell
& ./csc6621/Scrtips/activate.ps1
& jupyter notebook
```

This will start the jupyter notebook web interface where you can do your development.
