# machine-learning
hands-on machine learning with scikit-learn, keras &amp; tensorflow

# creating and activating an isolated environment
$ python3 -m pip install --user -U virtualenv
$ cd {project-directory}
$ python3 -m virtualenv my_env

$ source my_env/bin/activate

# install modules and dependencies
$ python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn
$ python3 -m ipykernel install --user --name=python3

# open jupyter notebook
$ jupyter notebook

# convert json ipython notebook (.ipynb) to .py file
$ jupyter nbconvert --to script housing.ipynb