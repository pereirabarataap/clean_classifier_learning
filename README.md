## DENOISE

Denoise is a unified method to perform classifier learning from noisy samples that leverages noise detection and sample weighting techniques.</br>
It consists of learning a noise-resilient classifier through a log-odds sample weighting strategy, in which the weights are derived from the noisy instances in a label noise detection step.</br>
We empirically validate the performance of our method in a controlled scenario where noise is artificially injected into a diverse set of datasets.</br>
</br>
To replicate our expeirments, simply run the <code>run_me.ipynb</code> jupyter notebook.</br>
A full run requires ~5Gb of free space for the different datasets and noise econfigurations being generated.</br>
The time it takes to complete the run is circa 2 days in a 256-thread machine.

### Dependencies
The experimental setup is implemented in Python3 within a conda environment, requiring the following installation snippets:
* <code>pip install openml;</code>
* <code>pip install xgboost;</code>
* <code>conda install tqdm --y;</code>
* <code>conda install numpy --y;</code>
* <code>conda install pandas --y;</code>
* <code>conda install plotly --y;</code>
* <code>conda install nodejs --y;</code>
* <code>conda install jupyter --y;</code>
* <code>conda install seaborn --y;</code>
* <code>conda install networkx --y;</code>
* <code>conda install ipywidgets --y;</code>
* <code>conda install jupyterlab --y;</code>
* <code>conda install matplotlib --y;</code>
* <code>conda install scikit-learn --y;</code>
* <code>jupyter nbextension enable --py widgetsnbextension;</code>
* <code>jupyter labextension install jupyterlab-plotly</code>
* <code>jupyter labextension install @jupyter-widgets/jupyterlab-manager;</code>
* <code>jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget;</code>
