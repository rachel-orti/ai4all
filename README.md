# Artificial Intelligence for all

## Overview

This Git repository contains related material to a presentation from Rachel Orti and Melanie Shilpa Rao at Devoxx France 2019, "L'Intelligence Artificielle pour tous" (Artificial Intelligence for all). 

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

## Useful links about fairness in AI 

### General articles about bias in AI
* [Are Algorithms Building the New Infrastructure of Racism?](http://nautil.us/issue/55/trust/are-algorithms-building-the-new-infrastructure-of-racism)
* [Artificial Intelligence and Privacy](https://www.datatilsynet.no/globalassets/global/english/ai-and-privacy.pdf)
* [Bias detectives: the researchers striving to make algorithms fair](https://www.nature.com/articles/d41586-018-05469-3)
* [How to prevent bias in machine learning](https://becominghuman.ai/how-to-prevent-bias-in-machine-learning-fbd9adf1198)
* [Responsible AI Practices](https://ai.google/education/responsible-ai-practices?category=fairness)
* [Algorithmes : biais, discrimination et équité](https://www.telecom-paristech.fr/wp-content-EvDsK19/uploads/2019/02/Algorithmes-Biais-discrimination-equite.pdf)
* [Algocratie: l'inégalité Programmée](https://www.youtube.com/watch?v=oJHfUv9RIY0&feature=youtu.be)

### Examples
* [Project Norman](http://norman-ai.mit.edu/)
* COMPAS:
    * [ProPublica Investigation](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
    * [AI is convicting criminals and determining jail time, but is it fair?](https://www.weforum.org/agenda/2018/11/algorithms-court-criminals-jail-time-fair/)
* [Gender Shades](http://gendershades.org/)
    * [2nd Study Results](https://dam-prod.media.mit.edu/x/2019/01/24/AIES-19_paper_223.pdf)

### Movements & organisations
* [Trustable AI](https://trustable.ai/)
* [Partnership on AI](https://www.partnershiponai.org/)
* [Microsoft FATE](https://www.microsoft.com/en-us/research/group/fate/)
* [Algorithmic Justice League](https://www.ajlunited.org/)
* [Algorithm Watch](https://algorithmwatch.org)
    * [TEDTalk How I'm fighting bias in algorithms](https://www.ted.com/talks/joy_buolamwini_how_i_m_fighting_bias_in_algorithms)
* [Fair by Design](http://www.fairbydesignfund.com/)
* [AlgoTransparency](https://algotransparency.org)
* [Data For Good](https://dataforgood.fr/)
    * [On cherche à éveiller la conscience éthique des développeurs et data scientists](https://tgf.usbeketrica.com/article/on-cherche-a-eveiller-la-conscience-ethique-des-developpeurs-et-data-scientists)
 * [AI Now Institue](https://ainowinstitute.org/)

### Tools
* AI Fairness 360 Toolkit (IBM):  
    * [Overview](https://aif360.mybluemix.net/)
    * [Github](https://github.com/IBM/AIF360)
* What-If (Google):
    * [Overview](https://pair-code.github.io/what-if-tool/)
    * [Github](https://github.com/tensorflow/tensorboard/tree/master/tensorboard/plugins/interactive_inference)
* [Audit AI](https://github.com/pymetrics/audit-ai)(Pymetrics)
* [AI Openscale](https://cloud.ibm.com/docs/services/ai-openscale)(IBM)
* [Teach & Test AI](https://www.accenture.com/us-en/insights/technology/testing-AI)(Accenture)
* [Lime](https://github.com/marcotcr/lime) 
* Activation Atlas (Google):
    * [Overview](https://distill.pub/2019/activation-atlas/)
    * [Github](https://github.com/distillpub/post--activation-atlas) 
