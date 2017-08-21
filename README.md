# machine-learning-using-Python
==

### Requirements:
* Anaconda 4.4.0 is required for this class. 
* ***Python*** [Installation Instructions for Mac, Windows and Linux users is provided here](https://docs.continuum.io/anaconda/install/)
  * You will have the option to select Python 3.6 or Python 2.7. I recommend Python 3.6.
  If you already have Python installed on your machine you need to make sure the new Anaconda/Python Path is given to the your system in the .bashrc or .bash_profile to avoid conflict among the Pythons on your machine.
 
* Python libraries required:**Skitlearn**, **Numpy/scipy**, **Keras**, **Tensorflow**.

**==> You can install the following packages for the Anaconda:**
* ***pip*** (*should be installed on recent Python distributions*) -  [Installation instructions](http://python-packaging-user-guide.readthedocs.io/installing/#install-pip-setuptools-and-wheel). For windows users: If pip is not recognized make sure it is added to the path - [Follow instruction on this error here](http://stackoverflow.com/questions/23708898/pip-is-not-recognized-as-an-internal-or-external-command)
* ***Numpy/scipy***:    ```pip install numpy``` - [Installation instructions](http://www.scipy.org/scipylib/building/index.html)
* ***Tensorflow***:  ```conda install -c conda-forge tensorflow``` -[Installation instructions](https://www.tensorflow.org/install/#anaconda_installation)
* ***Keras***:  ```conda install -c conda-forge keras```-[Installation instructions] (https://anaconda.org/conda-forge/keras)


### Download class materials
* **From Git**:
  * ***git***: [Installation instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  * ```git clone https://github.com/nhanteh/machine-learning-using-Python.git```

### Run IPython Notebook
**Anaconda distribution:**
* Copy the IPython Notebook launcher from the menu to the desktop.
* Right click on the new launcher and change the ```Start in``` field by pasting the full path of the folder which will contain all the notebooks: ```/path/to/Deep-Learning-Workshop```.
* Double-click on the IPython Notebook desktop launcher (icon shows [IPy]) to start the Jupyter Notebook App.

**Command line:**
* ```cd /path/to/Deep-Learning-Workshop```
* ```ipython notebook``` (```ipython/jupyter``` has to be in your ```PATH```)
