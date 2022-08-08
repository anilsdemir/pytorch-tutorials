# Pytorch Tutorials
- Pytorch tutorials for self-development.

## Fresh Install

If this is the first time you are cloning this repo here is what you need to do:
- Create a virtual environment and activate it

### For Local
- Install virtualenv:
  - `pip install virtualenv`
- Create a virtual environment and activate it
  - `virtualenv --python=/usr/bin/python3.9 pytorch-tutorials-venv`
  - `source pytorch-tutorials-venv/bin/activate`
- Install pip-tools: `pip install pip-tools`
- Change directory to `requirements/`:
  - Install required packages: `pip install -r base-requirements.txt`
- Install pre-commit hooks: `pre-commit install`
