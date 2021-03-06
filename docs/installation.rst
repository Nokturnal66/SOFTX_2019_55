============
Installation
============

Install scopus from PyPI:

.. code-block:: console

    $ pip install pybliometrics

or the development version from the GitHub repository (requires git on your system):

.. code-block:: console

    $ pip install git+https://github.com/pybliometrics-dev/pybliometrics

To access the Scopus database using `pybliometrics`, get an API key from http://dev.elsevier.com/myapikey.html.  On first usage, `pybliometrics` prompts you for authentication details and stores them in `~/.scopus/config.ini`, where you can change it manually (see :doc:`Configuration </configuration>`).  If your institution subscribes to Scopus, you may need to be in your institution's network or you need to have an InstToken, which can also be saved in the configuration.  Non-subscribers only get limited access to two APIs.

See extended description and examples in the :doc:`Examples </examples>` section.
