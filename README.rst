``plaquette``: all-encompassing quantum error-correction software
=================================================================

``plaquette`` is a fully featured and easy-to-use library for studying quantum
error correction and fault tolerance.

The library features numerous quantum error correction codes, hardware-relevant
error models and versatile decoders that can be used together seamlessly,
and it is tailored to  accommodate both newcomers and experienced users alike!

**WARNING**: we are in the process of fully making this tool public, so expect
rough corners in the meantime! This is also why currently the project is
marked as "alpha" in the version specifier. Stay tuned. :)

Installation
------------

``plaquette`` is a pure Python package, so it can be easily installed via
``pip`` after you clone the repository::

   git clone git@github.com:qc-design/plaquette.git && cd plaquette && pip install .


Documentation
-------------

Live pre-compiled documention is available
`here <https://docs.plaquette.design/>`_.

Alternatively, the documentation can be built from the ``master`` branch by::

   cd docs
   make clean html

and the build files will be available in the ``docs/_build/html`` directory.

Need help? Want to contribute?
------------------------------

``plaquette`` is under heavy development, so it might have some rough corners that need
polishing. If you encounter something you think (or the docs say) should work but does
not, just open an `issue <https://github.com/qc-design/plaquette-mirror/issues/new>`_
or, if you also want to share a solution, a
`pull request <https://github.com/qc-design/plaquette-mirror/compare>`_! See
our `development standard <https://docs.plaquette.design/dev/index.html>`_ to
have an idea of how to match your suggestions to the codebase.

Want to simply share feedback or you're unsure how to do something? Open a new
`discussion <https://github.com/qc-design/plaquette-mirror/discussions/new/choose>`_!


Supporters
----------

``plaquette`` is developed and maintained by `QC Design <https://www.qc.design/>`_.
``plaquette`` is also supported by the German Ministry of Education and Research
(BMBF) via project `PhotonQ <https://www.photonq.de/>`_. An early prototype of
``plaquette`` was developed under the support of the BMBF project
`PhoQuant <https://www.quantentechnologien.de/forschung/foerderung/quantencomputer-demonstrationsaufbauten/phoquant.html>`_.