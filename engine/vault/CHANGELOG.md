# Changelog

## [0.2.1]

-   Address two new clippy warnings: `needless_lifetimes` (addressed in the vault)
    and `unnecessary_cast` (ignored in the runtime since they are necessary for
    portability: `0 as libc::c_char` is not necessarily the same as `0_u8`).
        - [1614243](https://www.github.com/iotaledger/stronghold.rs/commit/161424322af84bd4626aac5a3f96b0c529d7b39a) Add a changelog message on 2021-01-04

## [0.2.0]

-   Added the initial client logic and integrated it with the Riker actor model. Change includes a Client/Cache actor, a Bucket actor, a Snapshot actor, and a keystore actor.  All of the Stronghold APIs are available.
    -   [7c7320a](https://www.github.com/iotaledger/stronghold.rs/commit/7c7320ab0bc71749510a590f418c9bd70329dc02) add client changelog. on 2020-11-30
    -   [4986685](https://www.github.com/iotaledger/stronghold.rs/commit/49866854f32dde8589f37c6d9ea0c2e7ddb3c461) remove todos and update readme. on 2020-11-30
    -   [7f1e9ed](https://www.github.com/iotaledger/stronghold.rs/commit/7f1e9edf5f5c5e148376575057a55d1d1398708a) Chore/covector fix ([#61](https://www.github.com/iotaledger/stronghold.rs/pull/61)) on 2020-12-01
    -   [f882754](https://www.github.com/iotaledger/stronghold.rs/commit/f88275451e7d3c140bbfd1c90a9267aa222fb6d0) fix(client): readme and changelog ([#64](https://www.github.com/iotaledger/stronghold.rs/pull/64)) on 2020-12-01
-   Alpha release of Stronghold: "Saint-Malo"
    -   [4b6f4af](https://www.github.com/iotaledger/stronghold.rs/commit/4b6f4af29f6c21044f5063ec4a8d8aff643f81a7) chore(release) ([#105](https://www.github.com/iotaledger/stronghold.rs/pull/105)) on 2020-12-24
    -   [06c6d51](https://www.github.com/iotaledger/stronghold.rs/commit/06c6d513dfcd1ba8ed6379177790ec6db28a6fea) fix(changelog): Alpha Release ([#106](https://www.github.com/iotaledger/stronghold.rs/pull/106)) on 2020-12-24
