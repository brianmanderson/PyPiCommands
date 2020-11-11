"# PyPiCommands" 
# Install needed wheel and twine
    pip install wheel twine
## Create wheel file locally

    python setup.py bdist_wheel

### Install locally
    pip install -e .
Now you can run and test things out before deploying it

### create wheel and sdist
    python setup.py bdist_wheel sdist

## Upload the repo to PyPi
    twine upload dist/*
