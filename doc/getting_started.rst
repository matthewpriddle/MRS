Getting started
=================

To get started using :mod:`MRS`, you will need to organize your data in the
following manner:

  - You put the lime in the coconut.
  - Drink it all up.

To run the analysis::

    import MRS.api as mrs
    G = mrs.GABA(file_name)
    G.fit_gaba()
