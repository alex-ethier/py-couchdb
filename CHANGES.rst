Version 1.4
-----------

- Fixed invalid url parsing on use session (thanks to KodjoSuprem)
- Fixed invalid encode method call (thanks to Kristoffer Berdal)
- Switch to basic auth method as default auth method.
- Add new method "one" for more clean way to obtain a first value
    for a query a view (thanks to Kristoffer Berdal for the initial idea)
- Add flat and as_list parameters to query, one and all methods.

Version 1.3
-----------

- Added replication methods thanks to Bruno Bord (@brunobord)

Version 1.2
-----------

- All methods that can receive document, do not modify id (inmutable api?)
- Add delete_bulk methods.
- A lot of fixes and improvements on tests.

Version 1.1
-----------

- Add python view server (imported from https://github.com/lilydjwg/couchdb-python3 with some changes).
- Now compatible with pypy.


Version 1.0
-----------

- Initial version.
