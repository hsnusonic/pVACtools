pVACtools
=========

pVACtools is a cancer immunotherapy tools suite consisting of the following
tools:

**pVACseq**
   A cancer immunotherapy pipeline for identifying and prioritizing neoantigens from a list of tumor mutations.

**pVACfuse**
   A tool for detecting neoantigens resulting from gene fusions.

**pVACvector**
   A tool designed to aid specifically in the construction of DNA-based
   cancer vaccines.

.. image:: images/pVACtools_main-figure_v2e.png
    :align: center
    :alt: pVACtools immunotherapy workflow


.. toctree::
   :maxdepth: 2

   pvacseq
   pvacfuse
   pvacvector

.. toctree::
   :maxdepth: 1

   install
   frequently_asked_questions
   contact

New in version |release|
------------------------

This is a hotfix release. It fixes the following issues:

- IEDB changed the format of combinatorial class II alleles to use ``/`` as a
  delimiter instead of ``-``. DP alleles were previously fixed in pull request
  `#85 <https://github.com/griffithlab/pVACtools/pull/85>`_ but this failed to
  address DQ alleles. This version fixes this oversight.

Coming soon
-----------

**pVACclient**
   A browser-based user interface that assists
   users in launching, managing, reviewing, and visualizing the results of
   pVACtools processes.

**pVACapi**
    The pVACapi will provide a HTTP REST interface to the pVACtools
    suite.

Citation
--------

Jasreet Hundal, Beatriz M. Carreno, Allegra A. Petti, Gerald P. Linette, Obi
L. Griffith, Elaine R. Mardis, and Malachi Griffith. `pVACseq: A genome-guided
in silico approach to identifying tumor neoantigens <http://www.genomemedicine.com/content/8/1/11>`_. Genome Medicine. 2016,
8:11, DOI: 10.1186/s13073-016-0264-5. PMID: `26825632
<http://www.ncbi.nlm.nih.gov/pubmed/26825632>`_.

License
-------
This project is licensed under `NPOSL-3.0 <http://opensource.org/licenses/NPOSL-3.0>`_.
