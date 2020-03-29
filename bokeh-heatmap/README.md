# Bokeh Heatmap with Optimal Order of Variables


## Functions

This notebook contains functions to calculate the optimal order for creating
a heatmap for all possible selections of a large set of variables. The most important
function here is ``create_ordered_dict()``.

Moreover, it contains a function that creates the "optimal" heatmap for a selection of
variables, given a dataframe and a dictionary that maps variable selections into the
optimal order. The most important function here is ``make_optimal_heatmap()``.

## Examples

Examples can be found at the end of the notebook.

## Conda environment

```
conda env create -f environment.yml
conda activate bokeh-heatmap
```
