.. _installation:

Installation Guides
===================

The installation of MALib is very easy. We've tested MALib on Python 3.7, 3.8 and 3.9. This guide is based on 
ubuntu 18.04 or above.

We strongly recommend using `conda <https://docs.conda.io/en/latest/miniconda.html>`_ to manage your dependencies, and avoid version conflicts. Here we show the example of building python 3.7 based conda environment.

.. code-block:: shell

    conda create -n l_malib python==3.7 -y
    conda activate l_malib
    pip install -e .




External Environments
---------------------

External environments are integrated in L-MALib, such as `Google Research Football 
<https://github.com/google-research/football>`_ and `Poker <https://github.com/Farama-Foundation/PettingZoo>`_. You can intall them by 
following the official guides on their project homepage.



Development requirements
------------------------

For users who wanna contribute to our repository, run ``pip install -e .[dev]`` to complete the development dependencies, also refer the contributing guide.

