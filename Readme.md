This repository is an example used to understand the issue [nbviwer#837](https://github.com/jupyter/nbviewer/issues/837)

The first ipynb `Interact_seaborn.ipynb` works fine on the jupyter notebook but is not rendered by nbviewer, ~~because interact widget does not work on the nbviewer~~ because it has an old JSON format.

On the `bokeh.ipynb` file, there are some example of interactions :
+ Bokeh + JS: works on nbviewer
+ Bokeh + Interact: fails on nbviewer
+ Matplotlib + Interact: fails on nbviewer

Finally `bokeh_with_widget_save.ipynb` is exactly the same as `bokeh.ipynb` but on jupyter notebook I've done `menu > widgets > save widget state` and all the interact plots are finally there !
