# DENOISE

Denoise is a unified method to perform classifier learning from noisy samples that leverages noise detection and sample weighting techniques.</br>
It consists of learning a noise-resilient classifier through a log-odds sample weighting strategy, in which the weights are derived from the noisy instances in a label noise detection step.</br>


## Experiments
We empirically validate the performance of our method in a controlled scenario where noise is artificially injected into a diverse set of datasets.</br>
The experimental setup is implemented in <code>Python3</code> within a <code>conda</code> environment.</br>
To replicate our experiments, simply run the <code>run_me.ipynb</code> jupyter notebook.</br>

### Requirements (Memory and Time)
A full run requires ~7Gb of free space for the different datasets and noise configurations being generated, as well as all the results.</br>
The time it takes to complete the run is circa 7 hours on a 256-thread machine.

### Dependencies (Packages)
* <code>pip install openml;</code>
* <code>pip install xgboost==1.2;</code> 
* <code>conda install tqdm --y;</code>
* <code>conda install numpy --y;</code>
* <code>conda install pandas --y;</code>
* <code>conda install nodejs --y;</code>
* <code>conda install jupyter --y;</code>
* <code>conda install seaborn --y;</code>
* <code>conda install ipywidgets --y;</code>
* <code>conda install jupyterlab --y;</code>
* <code>conda install matplotlib --y;</code>
* <code>conda install scikit-learn --y;</code>
* <code>jupyter nbextension enable --py widgetsnbextension;</code>
* <code>jupyter labextension install jupyterlab-plotly</code>
* <code>jupyter labextension install @jupyter-widgets/jupyterlab-manager;</code>
* <code>jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget;</code>
