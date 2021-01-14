# Changelog

## [0.2.1]

-   Address two new clippy warnings: `needless_lifetimes` (addressed in the vault)
    and `unnecessary_cast` (ignored in the runtime since they are necessary for
    portability: `0 as libc::c_char` is not necessarily the same as `0_u8`).
        - Bumped due to a bump in vault.
        - [1614243](https://www.github.com/iotaledger/stronghold.rs/commit/161424322af84bd4626aac5a3f96b0c529d7b39a) Add a changelog message on 2021-01-04

## [0.2.0]

-   Alpha release of Stronghold: "Saint-Malo"
    -   [4b6f4af](https://www.github.com/iotaledger/stronghold.rs/commit/4b6f4af29f6c21044f5063ec4a8d8aff643f81a7) chore(release) ([#105](https://www.github.com/iotaledger/stronghold.rs/pull/105)) on 2020-12-24
    -   [06c6d51](https://www.github.com/iotaledger/stronghold.rs/commit/06c6d513dfcd1ba8ed6379177790ec6db28a6fea) fix(changelog): Alpha Release ([#106](https://www.github.com/iotaledger/stronghold.rs/pull/106)) on 2020-12-24
