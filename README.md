![GMIT Logo](http://password.gmit.ie/images/logo.png "GMIT Logos")
# Machine Learning and Statistics

Repository for the Tasks assessment for Machine Learning and Statistics module @ GMIT - 2020

Author: Maciej Izydorek Email: G00387873@gmit.ie Github: [mizydorek](https://github.com/mizydorek)

#

#### Tasks

*Four tasks will be listed here at different times during the semester. You should complete all tasks in a single jupyter notebook. This, along with relevant files like a README, should be in a single git repository synced with a hosting provider like GitHub [1]. That URL should then be submitted using the link on the Moodle page.*

1. Square root of 2

>Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library1 or otherwise. You should research the task ﬁrst and include references and a description of your algorithm.

2. Chi-Square test

>The Chi-squared test for independence is a statistical hypothesistestlikea t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.

3. STDEV.p vs STDEV.S

>The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)). However, Microsoft Excel has two diﬀerent versions of the standard deviation calculation, STDEV.P and STDEV.S. The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x). Research these Excel functions, writing a note in a Markdown cell about the diﬀerence between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to ﬁgure out the terminology in the previous sentence. 

4. K-means clustering on the iris dataset

>Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.

#### Contents of repository

The repository contains:

* `README.md` file
* `numpy.random.ipynb` — jupyter notebook contains solution to the assignment
* `requirements.txt` — contains list of packages need to run the notebook
* `.gitignore` — contains list of files that have to be ignore
* `assessment.pdf` — contains the instructions for the Tasks assessment for Machine Learning and Statistics 

#### Required software

The following software is required to run the notebook:

* `git` — open source software to download the repository onto computer[3]
* `python` — Python Programming Language
* `Numpy. Pandas. SciPy. Matplotlib. Seaborn. Jupyter` — python packages used to make an investigation into the numpy.random package[5,6,7,8,9] 

* `Anaconda` — Individual edition of Anaconda can be install to get all of the relevant software.[4]

or alternatively the following command will install the packages according to the configuration file

```
$ pip install -r requirements.txt
```

#### Instructions for downloading repository

At github repository [Machine Learning and Statistics](https://github.com/mizydorek/Machine-Learning-Tasks-2020) click on the green `Code` button to copy the link. Open command line(windows) or terminal(osx/linux), navigate to the selected directory and enter the command `git clone` folowed copied the URL. Alternatively copy the whole command below:

```
git clone https://github.com/mizydorek/Machine-Learning-Tasks-2020.git
```

The whole repository will be cloned down onto current working directory.

#### How to run the jupyter notebook

From there run `jupyter notebook` command on the command line/terminal. This will open Jupyter in the browser. The notebook containing solution that is called `numpy.random.ipynb` can be opened by clicking on it.
Once opened, select `Restart and Run All` from Kernel sub-menu to run the jupyter notebook.

#### Viewing the Notebook 

The notebook can be viewed online either on the [github](https://github.com/mizydorek/Machine-Learning-Tasks-2020/blob/main/tasks.ipynb) or by accessing through Jupyter Notebooks viewer  [nbviewer](https://nbviewer.jupyter.org/github.com/mizydorek/Machine-Learning-Tasks-2020/blob/main/tasks.ipynb).

#### References 

[1] Python (https://www.python.org/downloads/) 

[2] Project Jupyter. Jupyter notebook. (http://jupyter.org/)

[3] Software Freedom Conservancy. Git. (https://git-scm.com/)

[4] Anaconda. Individual Edition. (https://www.anaconda.com/products/individual)

[5] NumPy developers. Numpy. (http://www.numpy.org/)

[6] Pandas (https://pandas.pydata.org/)

[7] SciPy (https://www.scipy.org/)

[8] Matplotlib (https://matplotlib.org/)

[9] Seaborn (https://seaborn.pydata.org/)

[10] GMIT. Quality assurance framework. (https://www.gmit.ie/general/quality-assurance-framework)