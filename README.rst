
coverage_pth - install a .pth file to site-packages to enable coverage.py
==========================================================================

The instructions for `starting coverage.py automatically <https://coverage.readthedocs.io/en/latest/api_module.html#starting-coverage-py-automatically>`_
includes creating a ``.pth`` file with the contents:

.. code::

    import coverage; coverage.process_startup()

The project only contains this .pth file so you can easily have this enabled
via a pip install.
