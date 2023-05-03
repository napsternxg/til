---
layout: default
title: Python
has_children: true
permalink: /python
---

# Libs

* Make Tree diagrams in Python - https://github.com/c0fec0de/anytree

# Stdlib
* Import python modules from a file - https://stackoverflow.com/questions/436198/what-is-an-alternative-to-execfile-in-python-3/24261031#24261031
* Comprehensive introduction to AsyncIO in Python - https://bbc.github.io/cloudfit-public-docs/

# Interactive notebook based pages

* Use `nbinteract` to create web pages which run python code and ipywidgets using binder. 
  - https://www.nbinteract.com/tutorial/tutorial_monty_hall.html
  
# Jupyter Notebook

* HTML output in Jupyter notebooks: http://matthewrocklin.com/blog/2019/07/04/html-repr
  
# Plotly Express

* Seaborn style plotly plots with Dash support
  - https://medium.com/@plotlygraphs/introducing-plotly-express-808df010143d


# API creation

* FastAPI for API creation. 
  - https://fastapi.tiangolo.com/python-types/
  
# Misc.
* pydantic for validating JSON data - https://pydantic-docs.helpmanual.io
* Toytree - Canvas tree visualization using python (super cool graphics) - https://toytree.readthedocs.io/en/latest/Cookbook.html
* Overriding instance level functions in python: https://stackoverflow.com/a/42154067
```python
import types
def new_some_fn(self, *args, **kwargs):
  pass
obj.some_fn = types.MethodType(new_some_fn, obj)```
