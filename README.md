# Zemanta's Data Science summer school

### Virtual environment set up
```bash
mkdir .virtualenvs
pip install virtualenvwrapper
vim ~/.bashrc and add:
    export WORKON_HOME=$HOME/.virtualenvs
    export PROJECT_HOME=$HOME/Documents/py
    source /usr/local/bin/virtualenvwrapper.sh
```

### Jupyter notebook set up
```bash
mkvirtualenv summer
workon summer
pip install -r requirements.txt
ipython kernel install --user --name=summer
```
