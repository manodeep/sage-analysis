The Semi-Analytic Galaxy Evolution (**SAGE**) Analysis Package
==============================================================

This is the documentation for the Semi-Analytic Galaxy Evolution (**SAGE**)
analysis package. This package ingests, analyses, and plots the data products
of the **SAGE** model, located `here`_.  Please refer to the to the **SAGE**
`repo`_ for full documentation regarding how to run the base model.

.. _here: https://github.com/sage-home/sage-model
.. _repo: https://github.com/sage-home/sage-model

Installation
------------

The recommended installing method is through pip:

.. code::

    $ pip install sage-analysis

Maintainers
-----------

- Jacob Seiler (`@jacobseiler`_)

.. _@jacobseiler: https://github.com/jacobseiler

* :ref:`user-docs`
* :ref:`api-docs`

.. _user-docs:

.. toctree::
   :maxdepth: 2
   :caption: User Documentation

   introduction
   user/setting_up_sage
   user/analysing_sage
   user/history
   user/multiple_models
   user/custom_calculations
   user/custom_data_classes

.. _api-docs:

.. toctree::
   :maxdepth: 2
   :caption: API Reference

   api/model
   api/sage_hdf5
   api/sage_binary
   api/example_calcs
   api/example_plots
   api/utils
