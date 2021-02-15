# DENOISE

Denoise is a unified method to perform classifier learning from noisy samples that leverages noise detection and sample weighting techniques.
It consists of learning a noise-resilient classifier through a log-odds sample weighting strategy, in which the weights are derived from the noisy instances in a label noise detection step.
We empirically validate the performance of our method in a controlled scenario where noise is artificially injected into a diverse set of datasets (see Experiments folder).

## Dependencies
All experimental setup is implemented in Python3 and needs the following installation snippets to run properly:
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

