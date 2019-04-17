# Artificial Intelligence for all

## Overview

This Git repository contains code & links related to a presentation from Rachel Orti and Melanie Shilpa Rao at Devoxx France 2019, "L'Intelligence Artificielle pour tous" (Artificial Intelligence for all).

## Installation Guide

You can run the Jupyter notebooks using a Jupyter Notebook server that is provided in the current repository.

### Launch the Jupyper Notebook server

**Requirements:** You must have Docker installed.

- From the <code>docker</code> folder, use the following command to launch the Jupyter Notebook server with <code>docker-compose</code>:

> docker-compose up

> *NB:* Use <code>docker-compose down</code> to stop the Docker container.

- The Jupyter Notebook server is then available at the following URL: [http://localhost:8888](http://localhost:8888)

### Run the Jupyter notebooks

Some notebooks are provided in the <code>docker/notebook/resources/jupyter/work</code> folder:

- <code>AIF360_COMPAS.ipynb</code> - Example of bias removal in dataset using the Reweighing bias mitigation algorithm implemented in the AI Fairness 360 Toolkit (IBM)
- <code>WIT_COMPAS.ipynb</code> - Example of bias removal in model using the What-If tool (Google)

They are directly accessible at the following URL when the Jupyper Notebook server is up and running: [http://localhost:8888/tree/work](http://localhost:8888/tree/work)

## Useful links about Fairness in AI 

TODO: add remaining links

### General articles about bias in AI
* [Are Algorithms Building the New Infrastructure of Racism?](http://nautil.us/issue/55/trust/are-algorithms-building-the-new-infrastructure-of-racism)

### Examples
* [Project Norman](http://norman-ai.mit.edu/)
* COMPAS:
    * [ProPublica Investigation](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
    * [AI is convicting criminals and determining jail time, but is it fair?](https://www.weforum.org/agenda/2018/11/algorithms-court-criminals-jail-time-fair/)
* [Gender Shades](http://gendershades.org/)

### Tools
* AI Fairness 360 Toolkit (IBM):  
    * [Overview](https://aif360.mybluemix.net/)
    * [Github](https://github.com/IBM/AIF360)
* What-If (Google):
    * [Overview](https://pair-code.github.io/what-if-tool/)
    * [Github](https://github.com/tensorflow/tensorboard/tree/master/tensorboard/plugins/interactive_inference)
