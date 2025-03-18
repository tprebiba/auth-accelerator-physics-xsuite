# Get python and relevant packages in Linux
```console
$ wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ bash Miniconda3-latest-Linux-x86_64.sh -b  -p ./miniconda -f
$ source miniconda/bin/activate
$ pip install ipython numpy jupyterlab matplotlib pandas cpymad xsuite seaborn NAFFlib scipy xplt ipykernel
$ python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
$ jupyter lab
```