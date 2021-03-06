

.. _sphx_glr_auto_examples_chemtrails.py:


=============================
Chemtrails
=============================

The past trajectory of an animated plot can be visualized with the chemtrails
argument.  This displays a low opacity version of the trace behind the
current points being plotted.  This can be used in conjunction with the
precog argument to plot a low-opacity trace of the entire timeseries.



.. code-block:: python


    # Code source: Andrew Heusser
    # License: MIT

    # import
    import hypertools as hyp

    # load example data
    geo = hyp.load('weights_avg')

    # plot
    geo.plot(animate=True, chemtrails=True)

**Total running time of the script:** ( 0 minutes  0.000 seconds)



.. only :: html

 .. container:: sphx-glr-footer


  .. container:: sphx-glr-download

     :download:`Download Python source code: chemtrails.py <chemtrails.py>`



  .. container:: sphx-glr-download

     :download:`Download Jupyter notebook: chemtrails.ipynb <chemtrails.ipynb>`


.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.readthedocs.io>`_
