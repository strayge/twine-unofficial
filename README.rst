.. image:: https://img.shields.io/pypi/v/twine-unofficial.svg
   :target: https://pypi.org/project/twine-unofficial

.. image:: https://img.shields.io/pypi/pyversions/twine-unofficial.svg
   :target: https://pypi.org/project/twine-unofficial

.. image:: https://img.shields.io/readthedocs/twine
   :target: https://twine.readthedocs.io

twine-unofficial
================

This is a fork of the `official twine`_ project, with the following
changes, rejected by the maintainers:

- Upload command now supports ``--skip-tls-check`` option to disable
  TLS certificate verification. This is useful for uploading to
  repositories with self-signed certificates.

  Closed issue: `#463 <https://github.com/pypa/twine/pull/463>`_,
  rejected PR: `#387 <https://github.com/pypa/twine/issues/387>`_.

Installation
------------

.. code:: shell

   $ pip install twine-unofficial

Versioning
----------

Fork versioning is based on the official version, with the following
format: ``{official-version}.{fork-version}``.

twine
=====

Twine is a utility for `publishing`_ Python packages on `PyPI`_.

It provides build system independent uploads of source and binary
`distribution artifacts <distributions_>`_ for both new and existing
`projects`_.

See our `documentation`_ for a description of features, installation
and usage instructions, and links to additional resources.

Contributing
------------

See our `developer documentation`_ for how to get started, an
architectural overview, and our future development plans.

Code of Conduct
---------------

Everyone interacting in the Twine project's codebases, issue
trackers, chat rooms, and mailing lists is expected to follow the
`PSF Code of Conduct`_.

.. _`official twine`: https://github.com/pypa/twine
.. _`publishing`: https://packaging.python.org/tutorials/packaging-projects/
.. _`PyPI`: https://pypi.org
.. _`distributions`:
   https://packaging.python.org/glossary/#term-Distribution-Package
.. _`projects`: https://packaging.python.org/glossary/#term-Project
.. _`documentation`: https://twine.readthedocs.io/
.. _`developer documentation`:
   https://twine.readthedocs.io/en/latest/contributing.html
.. _`PSF Code of Conduct`: https://github.com/pypa/.github/blob/main/CODE_OF_CONDUCT.md
