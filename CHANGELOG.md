## 2018-08-30, Version 0.6.0
### Commits
- [[`1070eb3166`](https://github.com/datrs/random-access-disk/commits/1070eb31665c3578842997557af292a9e702a033)] (cargo-release) version 0.6.0 (Yoshua Wuyts)
- [[`fb9ee81c81`](https://github.com/datrs/random-access-disk/commits/fb9ee81c81043619ecf6ea3a5d670373248cd677)] Random access always open (#13) (Szabolcs Berecz)
- [[`0a18b10972`](https://github.com/datrs/random-access-disk/commits/0a18b109722c73f7385f77fe7fb7c2d118f7bcae)] replace tempdir crate (deprecated) with tempfile crate, using tempfile::Builder to create a tempdir (#12) (Jacob Burden)
- [[`254d3ccf77`](https://github.com/datrs/random-access-disk/commits/254d3ccf7789e615a46815c0e43f0892aab96eff)] update changelog (Yoshua Wuyts)

### Stats
```diff
 .travis.yml         |  1 +-
 CHANGELOG.md        | 26 ++++++++++++++++++++++++-
 Cargo.toml          |  6 ++---
 benches/sync.rs     | 29 +++++++++++++++++++--------
 src/lib.rs          | 59 +++++++++++++++++++++++++-----------------------------
 tests/model.rs      | 10 +++++----
 tests/regression.rs | 16 ++++++++++-----
 tests/test.rs       | 35 +++++++++++++++++++++-----------
 8 files changed, 120 insertions(+), 62 deletions(-)
```


## 2018-08-23, Version 0.5.0
### Commits
- [[`647536ba06`](https://github.com/datrs/random-access-disk/commits/647536ba06ab55f810c7981e60d68481ec55044c)] (cargo-release) version 0.5.0 (Yoshua Wuyts)
- [[`556d70f09a`](https://github.com/datrs/random-access-disk/commits/556d70f09a0b23cf15107442f9cefec7669ad463)] upgrade random-access-storage (#9)
- [[`61af2acc13`](https://github.com/datrs/random-access-disk/commits/61af2acc135456d39eb05b92e1ad3a20e790e53c)] Fix typo in crates.io link (#10)
 (tomasol)
- [[`64f674e8e9`](https://github.com/datrs/random-access-disk/commits/64f674e8e9b7377b209775e5bf31238f6be213cb)] Rename Sync -> RandomAccessDisk in README.md (#11)
 (tomasol)
- [[`1860e0ce4d`](https://github.com/datrs/random-access-disk/commits/1860e0ce4d8b0de8fce189beaaad549d79b3d40f)] rm unused src/syc file (Yoshua Wuyts)
- [[`e5089b73ff`](https://github.com/datrs/random-access-disk/commits/e5089b73ffc2a75210fa2c2fab52ee0050486ec6)] fix rustfmt in travis.yml (Yoshua Wuyts)
- [[`7a4448f454`](https://github.com/datrs/random-access-disk/commits/7a4448f454bcc57f158d6c360a5d82727a6a74e9)] remove &* calls (Yoshua Wuyts)
- [[`522cd4219e`](https://github.com/datrs/random-access-disk/commits/522cd4219e8bfd37cb3403f1100d6024f5367f2b)] (cargo-release) start next development iteration 0.4.1-alpha.0 (Yoshua Wuyts)

### Stats
```diff
 .travis.yml    |   2 +-
 Cargo.toml     |   4 +-
 README.md      |   4 +-
 src/lib.rs     |  26 +++++++++-----
 src/sync.rs    | 105 +----------------------------------------------------------
 tests/model.rs |   5 +--
 tests/test.rs  |   5 +---
 7 files changed, 26 insertions(+), 125 deletions(-)
```


