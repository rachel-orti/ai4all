# Fairness

## Overview

This Git repository contains code & links related to a presentation from Rachel Orti and Melanie Shilpa Rao at Devoxx France 2019, "L'Intelligence Artificielle pour tous" (Artificial Intelligence for all).

## Installation Guide

You can run the Jupyter notebooks using a Jupyter Notebook server that is provided in the current repository.

### Launch the Jupyper Notebook server

**Requirements:** You must have Docker installed.

- From the <code>fairness/docker</code> folder, use the following command to launch the Jupyter Notebook server with <code>docker-compose</code>:

> docker-compose up

> *NB:* Use <code>docker-compose down</code> to stop all the Docker container.

- The Jupyter Notebook server is then available at the following URL: [http://localhost:8888](http://localhost:8888)

### Run the Jupyter notebooks

Some notebooks are provided in the <code>fairness/docker/notebook/resources/jupyter/work</code> folder:

- AIF360_COMPAS.ipynb
- WIT_COMPAS.ipynb

They are directly accessible at the following URL when the Jupyper Notebook server is up and running: [http://localhost:8888/work](http://localhost:8888/work)

## Useful links about Fairness in AI 

TODO: add remaining links

### Examples
* [Project Norman](http://norman-ai.mit.edu/)
* [COMPAS - Investigation ProPublica](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
* [Gender Shades](http://gendershades.org/)

### Tools
* AI Fairness 360 Toolkit (IBM):  
    * [Overview](https://aif360.mybluemix.net/)
    * [Github](https://github.com/IBM/AIF360)
* What-If (Google):
    * [Overview](https://pair-code.github.io/what-if-tool/)
    * [Github](https://github.com/tensorflow/tensorboard/tree/master/tensorboard/plugins/interactive_inference)
