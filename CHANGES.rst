Changes
=======

0.5 (unreleased)
----------------

- New option ``-r``, ``--randomsource``. We support a pluggable system
  to define alternative sources of randomness. Currently supported
  sources: ``"system"``.
- Rename `SRC_DIR` to `WORDLISTS_DIR` (reflecting what it stands for).
- Use also flake8 with tox.
- Pass `options` to `get_passphrase()` instead of a bunch of single args.


0.4 (2015-03-30)
----------------

- Add --delimiter option (thanks to Rodolfo Gouveia).


0.3.1 (2015-03-29)
------------------

- Turned former `diceware` module into a Python package. This is to
  fix `bug #1 Wordlists aren't included during installation
  <https://github.com/ulif/diceware/issues/1>`_, this time really.
  Wordlists will from now on be stored inside the `diceware` package.
  Again many thanks to `conorsch <https://github.com/conorsch>`_ who
  digged deep into the matter and also came up with a very considerable
  solution.
- Use readthedocs theme in docs.


0.3 (2015-03-28)
----------------

- Fix `bug #1 Wordlists aren't included during installation
  <https://github.com/ulif/diceware/issues/1>`_ . Thanks to `conorsch
  <https://github.com/conorsch>`_
- Add --version option.


0.2 (2015-03-27)
----------------

- Minor documentation changes.
- Updated copyright infos.
- Add support for custom wordlists.


0.1 (2015-02-18)
----------------

- Initial release.
