# Creating Virtual Environments

To create a virtual environment, decide upon a directory where you want to place it, and run the venv module as a
script with the directory path:
```
python -m venv tutorial-env
```
This will create the tutorial-env directory if it doesn’t exist, and also create directories inside it containing a
copy of the Python interpreter and various supporting files.
A common directory location for a virtual environment is .venv. This name keeps the directory typically hidden
in your shell and thus out of the way while giving it a name that explains why the directory exists. It also prevents
clashing with .env environment variable definition files that some tooling supports.
Once you’ve created a virtual environment, you may activate it.


On Windows, run:
```
tutorial-env\Scripts\activate
```

On Unix or MacOS, run:
```
source tutorial-env/bin/activate
```

To deactivate a virtual environment, type:
```
deactivate
```