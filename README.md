## Python Programming for Data Science - Intermediate <img src="oudce_logo.png" align="right"/>


Materials for [Python Programming for Data Science - Intermediate](https://www.conted.ox.ac.uk/courses/python-programming-for-data-science-intermediate?code=O24P435COW) - **this page will be updated as the course progresses**.

The class workspace on **Slack** is https://pp4ds-ox-workspace.slack.com/ . I encourage you to ask questions should you have them in the Slack channel incase your classmates can help. Download Slack from: https://slack.com/get

If you do not wish to use slack you can use Canvas to contact me and other students. 

To use **Jupyter** yourself, I recommend you download and install **Anaconda**, a Python Data Science Platform, from: [here](https://www.anaconda.com) Make sure you download the **Python 3** version of Anaconda, ideally the latest version for Python 3.11. You can also install Jupyter if you have a standard Python distribution installed. Ask your tutors for assistance if you need to install Jupyter on your own machine.

To get the contents of this repository I recommend that you install **Git SCM**, a source code management software, that will help you keep up-to-date with the repository. I will be adding content as the course progresses and Git will allow you to pull new material as it becomes available.



### Cloning this repository to use it offline

If you want to run the notebooks on your own computer at home, apart from installing Jupyter/Anaconda as per above, you will need to install **Git**, which is a source code management software, from [here](https://git-scm.com/downloads). Windows users can also get Git here: https://gitforwindows.org/. Once installed, you need to open up the command-line ("Command Prompt" on Windows or "Terminal" on Mac OSX) to run some commands.

Change directory to somewhere sensible, such as `My Documents` or similar on Windows or `Documents` on Mac OSX. Assuming you're using `Documents`:

```
cd Documents
```

Then ask Git to clone this repository with the following command.
```
git clone https://github.com/grobles2/p4ds/
```
(or, in the unlikely case that you have SSH enabled use `git clone git@github.com:grobles2/p4ds`)

This will create a subdirectory called `p4ds` in your `Documents` folder. When you need to update the content at some later time after I have added some new files to the repository, you will need to open up the command-line again and do the following commands.
```
cd Documents/p4ds
git pull
```
What this does is to ask Git to check if there are any new changes in the online repository and to download those new files or updates to the existing files.

Either some lines of stuff should whizz by, or it will say `Already up to date.` if there are no new changes.

If this doesn't work, you may need to force the update, which will overwrite your local files. To do this (make sure any of your own work is renamed or moved outside of the `p4ds` folder first):
```
git fetch --all
git reset --hard origin/master
```

### Course Programme (inidicative)

**Week 1:** Introduction to the course. Basic overview of Machine Learning. Linear Regression example.

**Week 2:** Overview of a data-science pre-processing pipeline. Exploratory Data Analysis

**Week 3:** Data cleaning and preparation.

**Week 4:** Supervised Learning: regression.

**Week 5:** Supervised Learning: classification.

**Week 6:** Decision Trees. Ensemble Methods. Hyperparameter Tuning. 

**Week 7:** The Perceptron. Back-propagation. Fully-connected neural networks.

**Week 8:**  Dimensionality reduction and Unsupervised Learning. 

**Week 9:**  Deep Learning: fundamental concepts. Transformers and attention. 

**Week 10:**  Deep Learning: other architectures. GANs/Autoencoders. 


#### Adapted from  Massimiliano Izzo's programme 


