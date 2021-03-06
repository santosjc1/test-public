Read the Docs tutorial
======================

Cassiano updated

The tutorial is aimed at people interested in learning
how to use Read the Docs to host their documentation projects.
You will fork a fictional software library
similar to the one developed in the :doc:`official Sphinx tutorial <sphinx:tutorial/index>`.
No prior experience with Sphinx is required,
and you can follow this tutorial without having done the Sphinx one.

The only things you will need to follow are
a web browser, an Internet connection, and a GitHub account
(you can `register for a free account <https://github.com/signup>`_ if you don't have one).
You will use Read the Docs Community, which means that the project will be public.

Getting started
---------------

Preparing your project on GitHub
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To start, `sign in to GitHub <https://github.com/login>`_
and navigate to `the tutorial GitHub template <https://github.com/astrojuanlu/tutorial-template/>`_,
where you will see a green :guilabel:`Use this template` button.
Click it to open a new page that will ask you for some details:

* Leave the default "Owner", or change it to something better for a tutorial project.
* Introduce an appropriate "Repository name", for example ``rtd-tutorial``.
* Make sure the project is "Public", rather than "Private".

After that, click on the green :guilabel:`Create repository from template` button,
which will generate a new repository on your personal account
(or the one of your choosing).
This is the repository you will import on Read the Docs,
and it contains the following files:

``README.rst``
  Basic description of the repository, you will leave it untouched.

``pyproject.toml``
  Python project metadata that makes it installable.
  Useful for automatic documentation generation from sources.

``lumache.py``
  Source code of the fictional Python library.

``docs/``
  Directory holding all the Sphinx documentation sources,
  including some required dependencies in ``docs/requirements.txt``,
  the Sphinx configuration ``docs/source/conf.py``,
  and the root document ``docs/source/index.rst`` written in reStructuredText.

.. figure:: /_static/images/tutorial/github-template.png
   :width: 80%
   :align: center
   :alt: GitHub template for the tutorial

   GitHub template for the tutorial
