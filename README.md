# snkr-finder
> this repository / module are used to develop the fastai API version of Sneaker Finder:  a tool to help find sneakers similar to what you like!


WARNING!!!  WORK IN PROGRESS.. PROCEED WITH EXTREME CAUTION 

- Andy 13Feb, 2021

## Install

`pip install snkr-finder`

which makes teh snkrfinder module...

- snkrfinder.core -> snkrfinder (utils)

- snkrfinder.data -> snkrfinder.data

- snkrfinder.model -> snkrfinder.model

- snkrfinder.viz -> snkrfinder.viz



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
from snkrfinder.model import *
```


    Traceback (most recent call last):


      File "/home/ergonyc/anaconda3/envs/fastai/lib/python3.8/site-packages/IPython/core/interactiveshell.py", line 3417, in run_code
        exec(code_obj, self.user_global_ns, self.user_ns)


      File "<ipython-input-5-3761a38ed1f5>", line 1, in <module>
        from snkrfinder.model import *


      File "/home/ergonyc/Projects/Project2.0/snkr-finder/nbs/snkrfinder/model.py", line 160
        return df2
        ^
    SyntaxError: 'return' outside function


