![collaboratory logo](../../Misc-files/collaboratory2.png)

## [Collaboratory@Columbia](http://collaboratory.columbia.edu/)
### Columbia [Data Science Institute](http://datascience.columbia.edu/) and [Columbia Enterpreneuship](http://entrepreneurship.columbia.edu/)
## Winter 2019-2020 Data Science Bootcamp
### Day 1 Introduction to Machine Learning with Python/sklearn

- When: Wednesday January 15th, 2020
- Where: Room 903 [SSW](http://stat.columbia.edu/location-and-directions/)

- **Mandatory pre-assignment**: Read the ram_price data from the notebooks/data subfolder using pandas and visualize it using matplotlib in a jupyter notebook.
- **Start**: 9:00am

### Content

- [1 - Introduction to ML](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/01-introduction.html)
- [2 - Supervised Learning](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/02-supervised-learning.html)
- [3 - Preprocessing](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/03-preprocessing.html)
- [4 - Cross-validation and Grid-Search](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/04-cross-validation-grid-search.html)
- [5 - Linear Models for Regression](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/05-linear-models-regression.html)
- [6 - Linear Models for Classification](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/06-linear-models-classification.html)
- [7 - Trees and Forests](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/07-trees-forests.html)
- [8 - Gradient Boosted Trees](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/08-gradient-boosting.html)
- [9 - Pipelines](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/09-pipelines.html)
- [10 - Model Evaluation](https://ds-bootcamp-dsi-columbia.github.io/AY2019-2020-Winter-Collaboratory-Faculty/Bootcamp-materials/Day1-Machine-Learning/slides/10-model-evaluation.html)


### Prerequisites
 
+ Basics of linear algebra
+ Basics of statistics (mean, variance, etc.)
+ Basic programming skills in Python
+ Basic understanding of data structures and algorithms
+ Basic skills for working with data files (i/o operations on csv and tsv files, etc.)

### Installation Notes

This tutorial will require recent installations of

- [NumPy](http://www.numpy.org)
- [SciPy](http://www.scipy.org)
- [matplotlib](http://matplotlib.org)
- [pillow](https://python-pillow.org)
- [pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/) (>=0.22.1)
- [IPython](http://ipython.readthedocs.org/en/stable/)
- [Jupyter Notebook](http://jupyter.org)

You should be able to type:

    jupyter notebook

in your terminal window and see the notebook panel load in your web browser.
Try opening and running a notebook from the material to see check that it works.

For users who do not yet have these  packages installed, a relatively
painless way to install all the requirements is to use a Python distribution
such as [Anaconda](https://www.continuum.io/downloads), which includes
the most relevant Python packages for science, math, engineering, and
data analysis; Anaconda can be downloaded and installed for free
including commercial use and redistribution.
The code examples in this tutorial requires Python 3.5 or later.

After obtaining the material, we **strongly recommend** you to open and execute
a Jupyter Notebook `jupter notebook check_env.ipynb` that is located at the
top level of this repository. Inside the repository, you can open the notebook
by executing

```bash
jupyter notebook check_env.ipynb
```

inside this repository. Inside the Notebook, you can run the code cell by
clicking on the "Run Cells" button as illustrated in the figure below:

![](images/check_env-1.png)


Finally, if your environment satisfies the requirements for the tutorials, the executed code cell will produce an output message as shown below:

![](images/check_env-2.png)


### Getting started

#### Introductional Material

To get started here are some online resources for programming skills in Python and for setting up the required Python development environment.

+ [Jupyter notebook quickstart](https://jupyter.readthedocs.io/en/latest/content-quickstart.html) A guide on running Jupyter notebooks
+ [Jupyter with Python](http://opentechschool.github.io/python-data-intro/core/notebook.html) Working with Python kernels in Jupyter.
+ [Python Data Science handbook](https://github.com/jakevdp/PythonDataScienceHandbook) A free book in the form of Jupyter notebooks that introduced the core Python data science libraries ([launch interactive session](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb))
+ [A whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython) A free book introducing basic Python programming concepts


#### Installation Instructions
+ We’ll be using the [Anaconda Python distribution](https://www.anaconda.com/download/?lang=en-us#linuxQ)
+ Download and install the distribution from the link above
+ Start the Jupyter Notebook and open the [Check Environment IPython Notebook](./notebooks/Pre-assignment/check_env.ipynb). (see [Jupyter notebook quickstart](https://jupyter.readthedocs.io/en/latest/content-quickstart.html))
+ Run the file and make sure no errors are raised.
