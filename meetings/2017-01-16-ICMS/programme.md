---
layout: page
title: Programme of the workshop
---

This is the tentative programme for the 
[Computational Mathematics with Jupyter](http://opendreamkit.org/meetings/2017-01-16-ICMS/) workshop.
It’s possible that there will be some minor changes in the order of activities, so please check it
for updates!

We will hold presentations and tutorials during morning sessions, and
concurrent coding and documentation sprints during afternoon sessions
(except swapping them places on Thursday). Actitivies that will take 
place in the afternoons and their schedule will be decided at the 
beginning of the workshop depending on how many people will sign up 
to the proposed coding and documentation sprints. At the end of 
each day we will hear brief reports from group activities.

## Monday, 16th January

* Welcoming and introductions

### Presentations and tutorials (morning)

* Mike Croucher : **Is your research software correct?**

* Raniere Silva: **Software Sustainability on Computational Mathematics**

* Alexander Konovalov: **Reproducible computational experiments 
using [GAP Docker containers](https://hub.docker.com/u/gapsystem/)**

### Sprints 

* Finalising the schedule of concurrent coding and documentation sprints

* **Installation and setup**: if you haven't installed all relevant software
prior to the workshop, we will help you with this (for example, install 
[Jupyter](http://jupyter.org/) to follow the forthcoming Jupyter tutorial;
install releases or development versions of GAP, SageMath, etc.)


## Tuesday, 17th January

### Presentations and tutorials (morning)

* Thomas Kluyver: **Introduction to [Jupyter](http://jupyter.org/)**

* Vidar T. Fauske: **Notebooks in Version Control - diffing and merging with [nbdime](https://github.com/jupyter/nbdime)**

* Yuvi Panda: **Deploying [JupyterHub](https://github.com/jupyterhub/jupyterhub) in various ways**

### Sprints (afternoon)

* **Lecture notes hackathon** (lead: Mike Croucher): bring your lecture notes,
and we will help to convert them to Jupyter notebooks

* **Further practicalities** of [Jupyter](http://jupyter.org/), 
[nbdime](https://github.com/jupyter/nbdime),
[JupyterHub](https://github.com/jupyterhub/jupyterhub) and other tools


## Wednesday, 18th January

### Presentations and tutorials (morning)

* Markus Pfeiffer and Manuel Martins: **Interactive computational discrete mathematics 
with [GAP Jupyter interface](https://github.com/gap-packages/jupyter-gap)**

* Mike Croucher: **[An introduction to SageMathCloud for lecturers](https://github.com/mikecroucher/SMC_tutorial)**

* Christian Lawson-Perfect: **[Numbas](http://www.numbas.org.uk/) - free web-based e-assessment system for mathematics**

### Sprints (afternoon)

* **Contributing to [STACK](https://moodle.org/plugins/qtype_stack)** (lead: Chris Sangwin):
STACK is a computer aided assessment package for mathematics, which provides a 
new question type for the Moodle quiz. Using it, one could use the computer 
algebra system [Maxima](http://maxima.sourceforge.net/) to validate answers

* **Improving documentation for [An introduction to SageMathCloud for lecturers](https://github.com/mikecroucher/SMC_tutorial)**
(lead: Mike Croucher): follow-up activity for the morning talk

## Thursday, 19th January

**Remark**: in the morning, all OpenDreamKit Steering Committee members will be 
at the meeting [here](http://opendreamkit.org/2017/01/19/EdinburghSteeringCommittee/),
so we will have coding sprints first, and then presentations and tutorials in 
the afternoon.

### Sprints (morning)

* To be selected.

### Presentations and tutorials (afternoon)

* Jeroen Demeyer: **IPywidgets and interact functions**

* Sylvain Corlay: **Custom widget libraries and extending [JupyterLab](https://github.com/jupyterlab/jupyterlab)**


## Friday, 20th January

### Presentations and tutorials (morning)

* Hans Fangohr: **Introduction to [NBVAL](https://github.com/computationalmodelling/nbval)** (a `py.test` plugin to validate Jupyter Notebooks)

* Hans Fangohr and Marijan Beg: **A case study of computational science in Jupyter notebooks: [JOOMMF](https://joommf.github.io)**

* Mark Quinn: **Using SageMathCloud for teaching undergraduate physics**

### Sprints (afternoon)

* To be selected.


## Coding and documentation sprints yet to be scheduled

We will schedule these sprints during our planning session on Monday, 
dependently on how many participants will be interested to join them.
Some of these sprints may be recurring for several days.

* **Developing [Software Carpentry lesson on SageMath](http://alex-konovalov.github.io/sage-lesson/)**
(leads: Alexander Konovalov, Raniere Silva): we would like to make progress with establishing
the Software Carpentry lesson on SageMath, which is being at the early development stage in 
[this repository](https://github.com/alex-konovalov/sage-lesson). If there will be an interest,
we can also look at the [Software Carpentry lesson on GAP](http://alex-konovalov.github.io/gap-lesson/)

* **Tools for computations in semigroups** (lead: James Mitchell)

* **Introduction to [Symbolic Computation Software Composability Protocol (SCSCP)](http://www.symbolic-computing.org/scscp)**
(lead: Alexander Konovalov): SCSCP is a remote procedure call protocol
supported by several computer algebra systems and another software tools.
I coudl demonstrated how to use it, and provide further guidelines for using
it in your code

## Desirable tutorials

Please get in touch if you're able to cover this in your talk/tutorial/sprint:

- **Publishing notebooks** with [GitHub](https://github.com/blog/1995-github-jupyter-notebooks-3), 
[nbviewer](https://nbviewer.jupyter.org/), [mybinder](http://mybinder.org/)

- **Using [nbgrader](http://nbgrader.readthedocs.io/en/stable/) to create and grade assigments**

As an option, we may just have sprints where we will try to make use of these
tools, following their documentation, and report our experiences.
