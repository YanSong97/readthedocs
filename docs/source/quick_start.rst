.. _quick-start:

Quick Start
===========

If you have not installed L-MALib yet, please refer to :ref:`installation` before running. We give a case of running 
`Policy Space Response Oracle (PSRO) <https://arxiv.org/pdf/1711.00832.pdf>`_ to 
solve `Leduc Holdem <https://en.wikipedia.org/wiki/Texas_hold_%27em>`_, 

PSRO Learning
-------------
**Policy Space Response Oracle (PSRO)** is a population-based MARL algorithm which cooperates game-theory and MARL algorithm to solve multi-agent tasks in the scope of meta-game. At each iteration, the algorithm will generate some policy combinations and executes independent learning for each agent. Such a nested learning process comprises rollout, training, evaluation in sequence, and works circularly until the algorithm finds the estimated Nash Equilibrium. 

.. note:: If you want to use alpha\-rank to estimate the equilibrium, you need to install open\-spiel before that. Follow the :ref:`installation` to get more details.


Run the pre-defined config
^^^^^^^^^^^^^^^^^^^^^^^
.. code-block:: shell
    bash run.sh    
