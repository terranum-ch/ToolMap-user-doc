# ToolMap user documentation

[![Documentation Status](https://readthedocs.org/projects/toolmap/badge/?version=latest)](https://toolmap.readthedocs.io/en/latest/?badge=latest)

This repository contains the ToolMap user documentation and tutorials base files. The generated files are visible on ReadTheDocs here: http://toolmap.rtfd.io/

## Structure

Documentation files are written in reStructuredText and are stored in the `doc` folder.

## Local installation

This step is only needed in order to compile locally the documentation. the ReadTheDocs site is automatically updated when documentation is commited into the repository.

1. Install Python 3.X

2. Create a virtual environment using:

	    python -m venv env (recommanded)
	    source env/bin/activate (Unix)
	    env\Scripts\activate.bat (Windows)

3. Install the required packages using:

        pip install Sphinx

    > see the `requirements.txt` file for more information.

4. Generate the documentation locally using

		sphinx-build -b html doc html

5. Commit and push any change to update the documentation on ReadTheDoc
