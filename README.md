# snkr-finder
> this repository / module are used to develop the fastai API version of Sneaker Finder:  a tool to help find sneakers similar to what you like!


WARNING!!!  WORK IN PROGRESS.. PROCEED WITH EXTREME CAUTION 

- Andy 13Feb, 2021

Also note that there are two versions of the repo... `snkr-finder` and `snkrfinder` which both create the snkrfinder module.

Confusing, yes.  But mostly for testing and expository learning about import dependencies and nbdev automation tools.

## Install

`pip install snkr-finder`

which makes teh snkrfinder module...

- snkrfinder.core -> snkrfinder (utils)

- snkrfinder.data -> snkrfinder.data

- snkrfinder.model -> snkrfinder.model (.core .cvae .transfer)

- snkrfinder.widget -> snkrfinder.widget



NOTE:  symbolic link in the nbs directory to enable the module loads in these notebooks.  i.e. `ln -s ../snkrfinder/ snkrfinder`

## How to use

There are several sets of tools:

- data ingestion / setup
- feature extraction
- "similarity" finding
- visualization
- widget/GUI
- transfer learning  (modeling)
- CVAE models to learn a compact latent space representaiton of sneakers for use in recommenders or generative design tools (snkr-math)

```python
from snkrfinder.core import *
```

```python
from snkrfinder.data import *
```

```python
from snkrfinder.model.core import *
from snkrfinder.model.transfer import *
from snkrfinder.model.cvae import *

```

```python
from snkrfinder.widgets import *
```

```python
# todo: fix /model/__init__.py to autoimport models modules...?
# todo: fix /__init__.py to autoimport core module...?

```
