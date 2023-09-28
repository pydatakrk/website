# website

This is a test of pydatakrk website using mkdocs.


## Local development

```
pyenv local 3.11
python -m venv env
. env/bin/activate
pip install pip-tools
pip-sync requirements.txt
```

To update requirements

```
pip-compile requirements.in
```


To run local server

```
mkdocs serve
```


## Steps to reproduce the environment

```
mkdocs new  ...
```
