# kkssh

Kkssh is a user-friendly SSH client that simplifies the process of connecting to remote servers. With a built-in hostname prompt, you no longer need to memorize or search for the correct hostname.

## Install
Python 3.10.10

```bash
pip install --upgrade kkssh
```

## Usage

```bash
kkssh -c ~/.ssh/config HOST
```

## Develop

```bash
python setup.py sdist
twine upload dist/*
```
