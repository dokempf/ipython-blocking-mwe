Minimal examples for bug reports in `ipython_blocking`.

* In JupyterLab the prompt does not change from `[*]` to `[5]` after cell execution stops blocking https://github.com/kafonek/ipython_blocking/issues/12
  * Run in notebook (works): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dokempf/ipython-blocking-mwe/main?filepath=mwe.ipynb)
  * Run in Lab (does not work): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dokempf/ipython-blocking-mwe/main?filepath=..%2Flab%2Ftree%2Fmwe.ipynb)
* Doing *Run All* in Jupyter notebook leads unexpected ordering of cell execution https://github.com/kafonek/ipython_blocking/issues/13
  * Reproducer: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dokempf/ipython-blocking-mwe/main?filepath=runall.ipynb)
* Memory Leak https://github.com/kafonek/ipython_blocking/issues/7
  * Simple, library independent reproducer: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dokempf/ipython-blocking-mwe/main?filepath=memleak.ipynb)
