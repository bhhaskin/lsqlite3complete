# lsqlite3complete
lsqlite3complete is a thin wrapper around the SQLite3 engine, included and statically linked (unlike lsqlite3 which links dynamically). It supports creating and manipulating SQLite3 databases, with most functions accessed through an object-oriented interface to database or SQL statement objects.

This repository publishes an alternative LuaRocks package that keeps the static SQLite dependency bundled and pulls the SQLite source zip from GitHub instead of lua.sqlite.org, avoiding that site's bot detection that breaks CI downloads.

lsqlite3complete and the upstream lsqlite3 binding are available under the MIT license. See `LICENSE` for the full text and pointers to SQLite's public-domain dedication.
