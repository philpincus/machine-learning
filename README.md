# machine-learning
Hands-On Machine Learning with Scikit-Learn, Keras &amp; TensorFlow

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