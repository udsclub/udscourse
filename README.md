![Course promo](https://scontent-waw1-1.xx.fbcdn.net/v/t31.0-8/27174055_1561366943970550_3143910012865728824_o.jpg?oh=2e95138254b2fceb7586a34afae82a25&oe=5B0DFEE9)
# UDSClub ML Course
**Welcome to the course homepage**

**Please find installation guide described below**

## Set-up Your Environment
### Prerequisites:
##### Hardware:
- Laptop or PC :) 
- 2+ Cores, 
- 4+ Gb of RAM (ideally 8+ Gb) 
- Free disc space 3+ Gb

##### Software:
- Recent build of [Anaconda](https://www.anaconda.com/download/) for Python 

### Installations:
* Download and install latest [Anaconda](https://www.anaconda.com/download/) build for **Python 3.6+**
  * [Windows guide](https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444), works on Windows 8+
  * Linux (Ubuntu) guide: [This](https://medium.com/@GalarnykMichael/install-python-on-ubuntu-anaconda-65623042cb5a) or [this](https://www.digitalocean.com/community/tutorials/how-to-install-the-anaconda-python-distribution-on-ubuntu-16-04), works on Ubuntu 12.04 / 14.04 / 16.04
  * [Mac guide](https://medium.com/@GalarnykMichael/install-python-on-mac-anaconda-ccd9f2014072)
* Be sure to have Anaconda on PATH and make it your default Python interpreter
* Install/upgrade required packages via `pip install ...` in your Command Line / Terminal (admin privileges should be granted)
  * ```pip install -U pandas``` (22.0+)
  * ```pip install -U numpy``` (1.14.0+, if not installed as pandas dependency)
  * ```pip install -U scipy``` (1.0+)
  * ```pip install -U matplotlib``` (2.1.12+)
  * ```pip install -U lightgbm``` (2.1.0+) or use [official guide](https://github.com/Microsoft/LightGBM/tree/master/python-package)
  * ```pip install -U xgboost``` (0.7+) or use [official guide](https://github.com/dmlc/xgboost/blob/master/doc/build.md)
  * ```pip install -U scikit-learn``` (0.19.1+)
  * download and install proper version of GraphViz from [here](https://graphviz.gitlab.io/download/)
  * ```pip install -U pydot```
  * ```conda install nb_conda``` (to join it with jupyter notebooks)
* Check whether your environment is set up properly or not
  * `cd to-directory-containing-file-check_environment.py`
  * `python check_environment.py`
  * `jupyter notebook`

Profit! You are ready to create/view Jupyter `.ipynb` notebooks :)

P.s. for your convenience:
 * install [Git](https://git-scm.com/download/win) for Windows or use pre-installed on other OS
 * ```git clone https://github.com/udsclub/udscourse``` into suitable folder and stay up-to-date with regular content updates
