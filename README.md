# Moved to Almond
This repository has been moved under the Almond organization.

The new location ist https://github.com/almond-sh/examples. All further development will happen there.

This archived copy is only kept here for some time to avoid breaking binder links.

---

# Almond Examples [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sbrunk/almond-examples/master)

A collection of [Jupyter](http://jupyter.org/) notebooks showing what you can do with the [Almond](http://almond-sh.github.io/almond/stable/docs/intro) Scala kernel.

## Run interactively on Binder
The easiest way to get started is to [run the examples on Binder](https://mybinder.org/v2/gh/sbrunk/almond-examples/master
). All your need is a browser!

Binder is an amazing service that allows you to create an executable environment out of a Git repository containing
Jupyter notebooks. That way, you can play with the examples and try new things without having to install anything locally.

## See Notebook Output in nbviewer
You can view the notebooks directly on GitHub, as it has a basic renderer for Jupyter notebooks. It doesn't execute any JavaScript though, which severly limits its ability to show dynamically generated plots i.e. from plotly and vegas.

A much better option is to render them through [nbviewer](https://nbviewer.jupyter.org/). nbviewer supports loading notebooks directly from a repo on GitHub.

**[List of all notebooks in this project in nbviewer](https://nbviewer.jupyter.org/github/sbrunk/almond-examples/tree/master/)**

## Running locally
An even better way to learn about Jupyter and Almond is to run it locally so you can try things out for yourself.

To run these notebooks locally:
1. Install [Jupyter Notebook](http://jupyter.org/install)
2. Install an [Almond kernel](http://almond-sh.github.io/almond/stable/docs/quick-start-install)
3. Clone the project and run `jupyter notebook` in the project directory
4. Open one of the example notebooks and play with it!
