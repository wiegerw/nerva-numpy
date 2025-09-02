nerva_numpy documentation
=========================

A tiny, educational set of neural network components built on JAX.

Install and build
-----------------

.. code-block:: bash

    # from repository root
    python -m pip install -U sphinx sphinx-rtd-theme
    # build HTML docs into docs_sphinx/_build/html
    sphinx-build -b html docs_sphinx docs_sphinx/_build/html

API reference
-------------

.. autosummary::
   :toctree: _autosummary
   :recursive:

   nerva_numpy
   nerva_numpy.activation_functions
   nerva_numpy.datasets
   nerva_numpy.layers
   nerva_numpy.learning_rate
   nerva_numpy.loss_functions
   nerva_numpy.matrix_operations
   nerva_numpy.multilayer_perceptron
   nerva_numpy.optimizers
   nerva_numpy.softmax_functions
   nerva_numpy.training
   nerva_numpy.utilities
   nerva_numpy.weight_initializers
