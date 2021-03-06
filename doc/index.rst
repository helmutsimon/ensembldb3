.. _contents:

########################################
Welcome to ``ensembldb3`` documentation!
########################################

**Contents**

.. toctree::
    :maxdepth: 1

    install
    licenses
    admin
    accounts_species
    genome
    variation
    compara
    advanced

.. todolist::

********
Overview
********

``ensembldb3`` provides python 3 compatible bindings to the Ensembl_ MySQL databases. It also includes capabilities for administering these databases locally. Specifically, tools for downloading MySQL dumps, installing those locally and removing old releases.

See the `EnsemblDb3 project page <https://github.com/cogent3/ensembldb3>`_ for the latest version of the code.

*******
History
*******

``ensembldb3`` began it's existence in 2009 as ``cogent.db.ensembl``, a part of Cogent3. With the port of Cogent3 to Python 3 (resulting in `Cogent3 <https://github.com/cogent3/cogent3>`_), it was decided to split the Ensembl querying code out into it's own project. This will make it easier to increase features and improve the project visibility.

.. todo::

    outline a few papers that have used the Cogent3 version

************
Contributing
************

We would greatly appreciate assistance in updating the project to PEP8, or anything else you think needs doing.

Please post a ticket, or comment on an existing one, indicating your intention so we can assist. Then it's the usual "fork", "pull request" dance.

If you discover a bug, especially something that worked in Cogent3 but not in ``ensembldb3``, please `post a ticket <https://github.com/cogent3/ensembldb3/issues>`_!

When posting a ticket, please provide a minimum working example to reproduce the issue. Also include the versions of the library and other tools (e.g. attach the result of ``$ pip freeze > libs.txt``).


********
Citation
********

For now, please continue to cite the Cogent3 paper --  `Knight et al., 2007, Genome Biol, 8, R171 <http://genomebiology.com/2007/8/8/R171>`_.

.. todo::
    
    on publication of the preprint

.. _`Nature 2009 457:480-4`: http://www.ncbi.nlm.nih.gov/pubmed/19043404?ordinalpos=6&itool=EntrezSystem2.PEntrez.Pubmed.Pubmed_ResultsPanel.Pubmed_DefaultReportPanel.Pubmed_RVDocSum
.. _Ensembl: http://ensembl.org
.. _Ensembl_download: http://asia.ensembl.org/info/data/ftp/index.html
