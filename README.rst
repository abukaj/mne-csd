.. -*- mode: rst -*-

|Travis|_ |AppVeyor|_ |Codecov|_ |CircleCI|_ |ReadTheDocs|_

.. |Travis| image:: https://travis-ci.org/Neuroinflab/mne-csd.svg?branch=master
.. _Travis: https://travis-ci.org/Neuroinflab/mne-csd

.. |AppVeyor| image:: https://ci.appveyor.com/api/projects/status/4qrnsuohh5g53i5u?svg=true
.. _AppVeyor: https://ci.appveyor.com/project/Neuroinflab/mne-csd

.. |Codecov| image:: https://codecov.io/gh/Neuroinflab/mne-csd/branch/master/graph/badge.svg
.. _Codecov: https://codecov.io/gh/Neuroinflab/mne-csd

.. |CircleCI| image:: https://circleci.com/gh/Neuroinflab/mne-csd.svg?style=svg
.. _CircleCI: https://circleci.com/gh/Neuroinflab/mne-csd/tree/master

.. |ReadTheDocs| image:: https://readthedocs.org/projects/mne-csd/badge/?version=latest
.. _ReadTheDocs: https://mne-csd.readthedocs.io/en/latest/?badge=latest


mne-csd - A template for mne-python compatible extensions
======================================================================

.. _mne-python: https://martinos.org/mne/stable/index.html

**mne-csd** is a template project for mne-python_ compatible
extensions.

*Thank you for cleanly contributing to the mne-python ecosystem!*

.. _documentation: https://mne-csd.readthedocs.io/en/latest/quick_start.html

Refer to the documentation_ to modify the template for your own mne-python
extension or follow this quick reference::

    $ git clone https://github.com/Neuroinflab/mne-csd.git mne-foo
    $ cd mne-foo
    $ # update mne_project_template_bootstrap.sh
    $ bash mne_project_template_bootstrap.sh
    $ rm mne_project_template_bootstrap.sh
    $ rm -rf .git
    $ git init && git add . && git commit -m 'Initial commit'
    $ git remote add origin https://github.com/your_remote/mne-foo.git
    $ git push origin master
    $ # Activate all CIs

Notice that appveyor badge image needs to be updated manually. Go where ``_AppVeyor:`` pints
in the resulting `README.rst` after bootstraping and substitute `4qrnsuohh5g53i5u` with
the relevant information from `settings` -> `badges` in appveyor's website of your project.
