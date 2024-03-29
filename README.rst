=============================
Dummy Repo
=============================

.. image:: https://img.shields.io/pypi/v/dummy-repo.svg
   :target: https://pypi.org/project/dummy-repo/
   :alt: Current PyPI Version

.. image:: https://img.shields.io/pypi/pyversions/dummy-repo.svg
   :target: https://pypi.org/project/dummy-repo/
   :alt: Supported Python Versions

.. image:: https://img.shields.io/pypi/l/dummy-repo.svg
   :target: https://www.apache.org/licenses/LICENSE-2.0
   :alt: Apache Software License Version 2.0

.. image:: https://img.shields.io/travis/Midnighter/dummy-repo/master.svg?label=Travis%20CI
   :target: https://travis-ci.org/Midnighter/dummy-repo
   :alt: Travis CI

.. image:: https://ci.appveyor.com/api/projects/status/github/Midnighter/dummy-repo?branch=master&svg=true
   :target: https://ci.appveyor.com/project/Midnighter/dummy-repo
   :alt: AppVeyor

.. image:: https://codecov.io/gh/Midnighter/dummy-repo/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/Midnighter/dummy-repo
   :alt: Codecov

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/ambv/black
   :alt: Black

testing

Post Template-Instantiation Steps
=================================

1. Start working with git.

   .. code-block:: console

       git init

2. Check for an updated versioneer.

   .. code-block:: console
   
       pip install versioneer
       versioneer install

   You probably have to remove the mess in ``src/dummy_repo/__init__.py``.

3. Commit all the files.

   .. code-block:: console

       git add .
       git commit

4. Create a repository on `GitHub <https://github.com/>`_ if you haven't done
   so yet and link it to `Travis CI <https://travis-ci.org/>`_.
5. Browse through the architecture decision records (``docs/adr``) if you want
   to understand details of the package design.
6. Remove this section from the readme and describe what your package is all 
   about.
7. When you're ready to make a release, perform the following steps.

   1. On `Travis CI <https://travis-ci.org/>`_ set the secure environment 
      variables ``PYPI_USERNAME``, ``PYPI_PASSWORD``, and ``GITHUB_TOKEN``.
   2. Tag your latest commit with the desired version and let Travis handle 
      the release.

      .. code-block:: console

          git tag 0.1.0
          git push origin 0.1.0

Install
=======

It's as simple as:

.. code-block:: console

    pip install dummy-repo

Copyright
=========

* Copyright (c) 2019, Moritz E. Beber.
* Free software distributed under the `Apache Software License 2.0 
  <https://www.apache.org/licenses/LICENSE-2.0>`_.
