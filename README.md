# Example-Analysis
Repository for analysis example that can be reused in research projects

## Installation

In order to complete this tutorial, follow these steps:

1. cd to the path of your choice on your terminal and clone the repo to your computer: git clone https://github.com/BIAPT/Example-Analysis.git

2. You will need Python and Jupyter Notebook. 

* Python  *(this was based on 3.7.6 version and used via *miniconda*). For Python installation tutorials, refer to either [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) or [pip](https://docs.python.org/3/using/index.html)

* Jupyter NoteBook [Installation documentation](https://jupyter.org/install)

3. Install the packages listed in the [requirements.txt](https://github.com/brainhack-school2020/ADHDsubtypes_project/blob/master/requirement.txt) file. 
To install the packages required via conda follow these instructions based on this [Documentation](https://docs.anaconda.com/anaconda/user-guide/tasks/install-packages/). 
For installing packages rather via pip you can refer to [this](https://packaging.python.org/tutorials/installing-packages/) instead.
For pandas : ```conda install pandas``` 
*(For a specific version install for any package via conda add ```=(version)```)*, for example : ```conda install pandas=1.0.3 ``` 
For scipy :  ```conda install scipy```

## Questions or problems : write an issue !

"Issues are key to keep track of tasks, enhancements, and bugs for your projects. They’re kind of like email—except they can be shared and discussed with the rest of your team. On GitHub, trackers are called issues."

Refer to this [tutorial](https://guides.github.com/features/issues/) on issues and this [documentation](https://docs.github.com/en/github/managing-your-work-on-github/managing-your-work-with-issues) with complete instructions. 

## How to use the command line to git pull this repository.

A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. You can version control locally on your machine via Git or on the cloud-based hosting service which is GitHub. See this handbook for an introduction of use and basic principles [Git Handbook](https://guides.github.com/introduction/git-handbook/).

Here's a great tutorial recommanded for you to follow offering a slide presentation, a hands-on tutorial and presenting other great tutorials. 
https://emdupre.github.io/git-course/

## The use of python in Neuroscience 

Here's a list of good tutorials to get started with python.

First, if you are a student, GitHub offers free acces to the best developer tools in one place : [GitHub Student Developer Pack](https://education.github.com/pack). You'll have, among many other things, a free month access to DataCamp which is paticularly convenient if you're completely new to the language. 

"[Python in neuroscience](https://github.com/btel/python-in-neuroscience-tutorials)" is a collection of collaboratively-edited tutorials on computational neuroscience methods using Python language.

Many MOOCs offer thorough courses on python, like these ones:

*[Coursera](https://www.coursera.org/learn/python)

*[Udemy](https://www.udemy.com/course/complete-python-bootcamp-expert-course/)

## Analysis techniques available on MNE-Python with links to the proper documentation

This tutorial has the purpose of introducing you to available tools, as well as offering a good start up point for you to use MNE as an analysis proxy of preprocessed .set datasets acquired via EEGLAB. 

MNE-python offers a great variety of analysis techniques presented as tutorials or complete examples :

* [Time-frequency analysis](https://mne.tools/dev/auto_tutorials/intro/plot_10_overview.html#time-frequency-analysis)
* [Estimating evoked response](https://mne.tools/dev/auto_tutorials/intro/plot_10_overview.html#estimating-evoked-responses)
* Connectivity Analysis (see these [examples](https://mne.tools/dev/auto_examples/index.html); specifically here's, for example, one tutorial on [computinng all-to-all connectivity in sensor space](https://mne.tools/dev/auto_examples/connectivity/plot_sensor_connectivity.html#sphx-glr-auto-examples-connectivity-plot-sensor-connectivity-py)
* [Inverse problem and source analysis](https://mne.tools/dev/auto_tutorials/intro/plot_10_overview.html#inverse-modeling)
* Forward modeling : here's an [example](https://mne.tools/dev/auto_tutorials/source-modeling/plot_forward.html#tut-forward) to get started 
* Statistics of sensor data and source estimates: see [tutorials](https://mne.tools/dev/auto_tutorials/index.html)
* Machine Learning (Decoding, Encoding, and MVPA): [Examples](https://mne.tools/dev/auto_examples/index.html)

Among many other things ! Don't miss  see [documentation overview](https://mne.tools/dev/overview/index.html) !


