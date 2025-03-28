Changelog
=========


0.5 (unreleased)
----------------

- Removed ``setup.py``.

- Added year parameter to prevent leap year parsing failures. Updated
  tests.

0.4 (2021-04-04)
----------------

- Removed support for Python 3.6.

- Turn namedtuples ``Message`` and ``PriorityValue`` into dataclasses.

- Added type hints.


0.3 (2021-03-03)
----------------

- Removed support for end-of-life Python versions 2.7, 3.3, 3.4, and
  3.5.

- Added support for Python 3.6, 3.7, 3.8, and 3.9.


0.2.2 (2016-03-01)
------------------

- Fixed ``datetime.strptime`` failing on February 29th. (Tests introduce
  a test dependency on FreezeGun).


0.2.1 (2015-09-08)
------------------

- Added missing files to distribution.


0.2 (2015-09-07)
----------------

- Data is required to be a byte string.

- Raise custom exception on message parsing errors instead of using
  assertions.

- Raise exception if message is too long instead of truncating and
  processing it.


0.1.1 (2015-08-10)
------------------

- Fixed packaging issue.


0.1 (2015-08-10)
----------------

- Published first official release.
