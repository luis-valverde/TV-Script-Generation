# TV Scripts Generation

## Table Of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Neccessary Files](#neccessary-files)
- [How to Run](#how-to-run)

## Introduction

This repository contains all my work for the Udacity's Deep Learning Nanodegree Program.

The goal in this project was to perform sentiment analysis using a Recurrent Neural Network (RNN) to generate a TV
script that resembles a training set.

To accomplish this, I applied data pre-processing techniques (lookup table and tokenize punctuation).
Then, implemented an RNN with PyTorch using a Long Short-Term Memory (LSTM) network to avoid the long-term dependency
problem and trained the neural network on the pre-processed data tracking the loss to avoid overfitting.
Finally, I modified model hyperparameters (learning rate, batch size, layers in RNN) to achieve a better loss and
faster converge.

## Project Overview

Automated text generation is becoming increasingly common. From robot journalism to product descriptions, their use has
become more and more ubiquitous. As demand continues to grow for individual online content, automated text generation
is to become increasingly important.

In this project, you'll generate your own Seinfeld TV scripts using RNNs. You'll be using part of the Seinfeld dataset
of scripts from 9 seasons. The Neural Network you'll build will generate a new ,"fake" TV script, based on patterns it
recognizes in this training data.

## Requirements

This project uses the following software and Python libraries:

- [Python](https://www.python.org/downloads/release/python-364/)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn (v0.17)](https://scikit-learn.org/0.17/install.html)
- [Matplotlib](https://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the
[Anaconda](https://www.anaconda.com/distribution/) distribution of Python, which already has the above packages and
more included.

## Neccessary Files

This repository contains three files needed to solve the project.

1. **dlnd_tv_script_generation.ipynb:** This is the main file where I performed the work on the project.
2. **dlnd_tv_script_generation.html:** This is an HTML report of the Jupyter notebook.
3. **data/Seinfeld_Scripts.txt:** Seinfeld dataset of scripts from 9 seasons.
4. **helper.py:** Utilities functions to use in the project.
5. **problem_unittests.py:** Unit tests to verify correct functionality of the algorithms created.

## How to Run

In the Terminal or Command Prompt, navigate to the folder on your machine where you've put the project files, and then
use the command:

```bash
jupyter notebook dlnd_tv_script_generation.ipynb
```

 to open up a browser window or tab to work with your notebook.
 Alternatively, you can use the command:

 ```bash
jupyter notebook
```

or

```bash
ipython notebook
```

and navigate to the notebook file (dlnd_tv_script_generation.ipynb) in the browser window that opens.
