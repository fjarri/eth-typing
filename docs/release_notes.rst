Release Notes
=============

.. towncrier release notes start

v3.1.0 (2022-06-22)
-------------------

Features
~~~~~~~~

- Setup towncrier to generate release notes from fragment files to ensure a higher standard
  for release notes. (`#16 <https://github.com/ethereum/eth-typing/issues/16>`__)
- Add new ``BLSPrivateKey`` type for BLS private key (`#23 <https://github.com/ethereum/eth-typing/issues/23>`__)
- Add ``__all__`` property to ``__init__.py`` with appropriate types to explicitly export (`#28 <https://github.com/ethereum/eth-typing/issues/28>`__)
- Add ``GrayGlacier`` to ``ForkName`` enum (`#30 <https://github.com/ethereum/eth-typing/issues/30>`__)


Miscellaneous changes
~~~~~~~~~~~~~~~~~~~~~

- `#32 <https://github.com/ethereum/eth-typing/issues/32>`__


v3.0.0 (2021-11-15)
-------------------

- Update ``ForkName`` enum to include ``Berlin``, ``London``, and ``ArrowGlacier``
- Update Python support to include python 3.8-3.10
- Remove Python 3.5 support

v2.2.0 (2019-10-31)
-------------------

- Update ``ForkName`` enum to include ``ConstantinopleFix`` and ``Istanbul``

v2.1.0 (2019-10-31)
-------------------

- Add BLS types

v2.0.0 (2019-10-31)
-------------------

- Expose Type Hints as per PEP 561

v1.0.0 (2018-06-08)
-------------------

- Added annotations from ``py-evm``.

v0.3.1 (2018-06-07)
-------------------

- Removed ``eth-utils`` requirement.

v0.3.0 (2018-06-07)
-------------------

- Updated ``eth-utils`` requirement.

v0.2.0 (2018-06-07)
-------------------

- Launched repository, claimed names for pip, RTD, github, etc.
