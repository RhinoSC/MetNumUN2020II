The PyData Toolbox
------------------

The numerical programming is among the fastest growing areas of application for
Python. The recent explosion of domain-specific tools for scientific computing
in Python can be daunting, but the vast majority of these libraries are built
on a small core of foundational libraries. Understanding these libraries -- how
they work, how they're used, and what problems they aim to solve -- is an
invaluable tool for effectively navigating the PyData ecosystem.

The primary goal of this talk is to provide an introduction to two of these
core libraries: Numpy and Pandas. We focus in particular on motivating the
design of numpy's `array` class, which serves as the foundational data
structure for numerical computing in Python.

First presented at Boston Algorithmic Trading on Tuesday, Aug 1st, 2017.

Video of the presentation: [https://youtu.be/YAHZa8xZWBU](https://youtu.be/YAHZa8xZWBU).

Running the Presentation
------------------------

This talk was delivered using Damian Avila's excellent
[RISE](https://github.com/damianavila/RISE/) extension for the Jupyter
Notebook, which allows users to convert a live, executable notebook into a
reveal.js presentation. Assuming you have the necessary system dependencies
(i.e. C and Fortran compiler toolchains), the `run.sh` script included in the
root of the repo should be sufficient to install, configure, and run the talk.

    $ git clone git@github.com:ssanderson/pydata-toolbox.git
    $ cd pydata-toolbox
    $ ./run.sh

`run.sh` will create a virtualenv named `venv` with all necessary dependencies
in the root directory of this project. It will then start an instance of the
Jupyter Notebook server with the RISE extension installed and enabled.
