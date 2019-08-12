This repository is an example used to understand the issue [nbviwer#837](https://github.com/jupyter/nbviewer/issues/837)

The first ipynb `Interact_seaborn.ipynb` works fine on the jupyter notebook but is not rendered by nbviewer, because interact widget does not work on the nbviewer.

On the `bokeh.ipynb` file, there are some example of interactions :
+ Bokeh + JS: works on nbviewer
+ Bokeh + Interact: fails on nbviewer
+ Matplotlib + Interact: fails on nbviewer
