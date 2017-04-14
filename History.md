
1.0.0 / 2017-03-21
==================

Major rewrite switching to Rustler based NIFs.

Changes include:

- Support for column families
- Implementation of `Enumerable` and `Collectable` for both `ColumnFamily.t` and
  `DB.t`
- Drop support for `stream_keys/1`. Use `stream/1` with a map instead.
- Support for streaming from arbitrary locations (see `stream/1` docs).
- Support for deletion