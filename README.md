# Assignments for the ACT API

This repository contains a [jupyter](http://jupyter.org) workbook with a short introduction and assignements to familiarize with the
[ACT api](https://github.com/mnemonic-no/act-platform).

You can find the solution to the assignments in the [solution branch](https://github.com/mnemonic-no/act-workshop-api/blob/solution/api-notebook.ipynb).

# Setup

Clone the repository:

```
git clone https://github.com/mnemonic-no/act-workshop-api
cd act-workshop-api
```

You will need python3 and the following python libraries:

* act-api
* ipykernel
* jupyter

### Install using pipenv
```
$ sudo pip3 install pipenv
$ pipenv install
$ pipenv install act-api ipykernel jupyter
```

### or Install using pip:

```
$ sudo pip3 install act-api ipykernel jupyter
```

# Start notebook

### After installation with pipenv
```
pipenv run jupyter notebook
```

### Or with jupyter installed globally

```
jupyter notebook
```

If jupyter fails to open a browser automatically, you might need to pass the `--no-browser` argument and copy the link manually to your browser.

```
jupyter notebook --no-browser
```

# Platforms tested

* Debian, using python 3.5
* [Linux subsystem (Ubuntu)](https://docs.microsoft.com/en-us/windows/wsl/install-win10) on windows. (Requires installation of python3-pip - `sudo apt install python3-pip`)
