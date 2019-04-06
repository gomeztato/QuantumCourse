# QuantumCourse
Notebooks and other stuff for a Quantum Course

This repository contains the materials of the course about Introduction to Quantum Programming that I teach under demand. Please, feel free to send me any comments or corrections so I can improve them. You can use them freely on your own courses (Please, try to cite it! <img src="https://zenodo.org/badge/165638085.svg"/>)

These notebooks are based on [ProjectQ](http://projectq.ch) and need the next Python packages installed:

* numpy
* matplotlib
* CIL
* scipy

It includes a set of Notebooks to learn some basics about Quantum Programming, with implementations of modern algorithms. Many of them are based on examples comming from ProjectQ and other sites or from publications. In each notebook, the references to the paper or to the original programs are included when needed.

Also, it includes a modification of the Quantum Simulator [QUIRK](https://algassert.com/quirk) to change the colors, so the main Quantum gates have the same colors that the [IBM Q Experience](https://quantumexperience.ng.bluemix.net/qx/community) Composer. 

**List of notebooks**

* [First ProjectQ program](Notebooks/ProjectQ_first_program.ipynb). This Notebook is based on the ProjectQ compiler tutorial. The exercise is an example of [superdense coding](https://en.wikipedia.org/wiki/Superdense_coding).
* [Executing QFT on IBM Q Experience from ProjectQ](Notebooks/ProjectQ_first_program_IBM.ipynb). A simple example about how to connect to IBM Quantum Experience from ProjectQ.
* [Some basic algorithms using ProjectQ](Notebooks/Some_basics.ipynb). A set of important operations or subroutines for Quantum Compuring and some technical details about ProjectQ.
* [Deutsch-Jozsa algorithm](Notebooks/Deutsch-Jozsa_algorithm.ipynb). An example of Deutsch-Jozsa algorithm.
* [Quantum Fourier Transform](Notebooks/QFT.ipynb). A simple example about what QFT is and how to make it correctly in ProjectQ.
* [Phase Estimation Algorithm](Notebooks/Phase_estimation.ipynb). An example of phase estimation algorithm.
* [Grover's algorithm](Notebooks/Grover.ipynb). A simple example of Grover's algorithm
* [Shor's algorithm](Notebooks/Shor.ipynb). A simple example of Shor's algorithm.
* [HHL algorithm](Notebooks/HHL_algorithm-Coles.ipynb). A simple example of HHL algorithm to solve a sistem of linear equations.
* [VQE algorithm](Notebooks/VQE.ipynb). The most basic example of Variational Quantum Eigensolver for the $H_2$ molecule.
* [QAOA algorithm for optimisation](Notebooks/QAOA.ipynb). Example of the QAOA algorithm using ProjectQ.


