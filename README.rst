Sequanix
########
Sequanix is a graphical user interface (GUI) that can be used to run Snakemake workflows.


.. image:: https://github.com/sequana/sequana//actions/workflows/main.yml/badge.svg?branch=master
    :target: https://github.com/sequana/sequana//actions/workflows/main.yml
    
.. image:: https://coveralls.io/repos/github/sequana/sequana/badge.svg?branch=master
    :target: https://coveralls.io/github/sequana/sequana?branch=master 

.. image:: http://readthedocs.org/projects/sequana/badge/?version=master
    :target: http://sequana.readthedocs.org/en/latest/?badge=master
    :alt: Documentation Status

.. image:: http://joss.theoj.org/papers/10.21105/joss.00352/status.svg
   :target: http://joss.theoj.org/papers/10.21105/joss.00352
   :alt: JOSS (journal of open source software) DOI


:Python version: 3.6, 3.7.3 (below for now)
:Documentation: `On readthedocs <http://sequana.readthedocs.org/>`_
:Issues: `On github <https://github.com/sequana/sequana/issues>`_
:How to cite: Citations are important for us to carry on developments.
    For Sequana library (including the pipelines), please use

    Cokelaer et al, (2017), 'Sequana': a Set of Snakemake NGS pipelines, Journal of
    Open Source Software, 2(16), 352, `JOSS DOI doi:10.21105/joss.00352 <https://joss.theoj.org/papers/10.21105/joss.00352>`_
    
    For the **genome coverage** tool (sequana_coverage):  Dimitri Desvillechabrol,
    Christiane Bouchier, Sean Kennedy, Thomas Cokelaer
    http://biorxiv.org/content/early/2016/12/08/092478

    For **Sequanix**: Dimitri Desvillechabrol, Rachel Legendre, Claire Rioualen,
    Christiane Bouchier, Jacques van Helden, Sean Kennedy, Thomas Cokelaer.
    Sequanix: A Dynamic Graphical Interface for Snakemake Workflows 
    Bioinformatics, bty034, https://doi.org/10.1093/bioinformatics/bty034
    Also available on bioRxiv (DOI: https://doi.org/10.1101/162701)


**Sequana** includes a set of pipelines related to NGS (new generation sequencing) including quality control, variant calling, coverage, taxonomy, transcriptomics. We also ship **Sequanix**, a graphical user interface for Snakemake pipelines. 

**Please see the** `documentation <http://sequana.readthedocs.org>`_ for an
up-to-date status and documentation.



Notes
######

Fix OpenGL for mac Big Sur: https://stackoverflow.com/a/64021312/11988671
