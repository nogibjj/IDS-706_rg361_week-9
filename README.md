# Data Manipulation in a Cloud Hosted Workbook
[![CI](https://github.com/nogibjj/IDS-706_rg361_week-9/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/IDS-706_rg361_week-9/actions/workflows/cicd.yml)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/revanth7667/cecde66ae9c28996867bba6a81533882/ids-706_rg361_week-9.ipynb)

## Advantages of Cloud Hosted Notebooks, with Google Colab as example:

1. ``Free and cloud-based``: Colab is a free, cloud-based platform that allows you to run Python code without having to install any software on the local machine.
2. ``Easy to use``: Colab has a user-friendly interface that makes it easy to write, run, and share Python code.
3. ``Integrated with Google Drive``: Colab is integrated with Google Drive, which means you can easily save and share your notebooks with others.
4. ``Access to powerful hardware``: Colab provides access to powerful hardware, including GPUs and TPUs, which can significantly speed up the execution of your code.
5. ``Support for popular libraries``: Colab comes pre-installed with many popular Python libraries, including NumPy, Pandas, and Matplotlib, making it easy to get started with data analysis and machine learning.
``Collaboration:`` Colab allows you to collaborate with others in real-time, making it a great tool for team projects.

## Contents

## Contents
### 1. README.md
   contains the information about the repository and instructions for using it
   
### 2. requirements.txt
   contains the list of packages and libraries which are required for running the project. These are intalled and used in the virtual environment and Github actions.
   
### 3. .github/workflows
   different github actions are used to automate the following 4 actions whenever a change is made to the files in the repository:
   - ``install`` : installs the packages and libraries mentioned in the requirements.txt
   - ``test`` : uses ``pytest`` with ``nbval``  to test the jupyter notebook
   - ``format.yml`` : uses ``black`` with ``nbqa`` to format the jupyter notebooks 
   - ``lint.yml`` : uses ``ruff`` with ``nbqa`` to lint the upyter notebooks
   
### 4. Makefile
   contains the instructions and sequences for the processes used in github actions and .devcontainer for creating the virtual environment
   
### 5. .devcontainer
   contains the ``dockerfile`` and ``devcontainer.json`` files which are used to build and define the setting of the virtual environment (codespaces - python) for running the codes.


### 6. resources 
   contains the other files which are used in README

