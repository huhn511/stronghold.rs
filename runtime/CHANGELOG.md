# Changelog

## [0.3.0]

-   Add functionality to enable the guarded memory allocator in the zone when
    running on POSIX (Linux, MacOS targets). The major contribution is a toggleable
    memory allocator that can be used to work around rust's enforcement of only
    one `#[global_allocator]`.
        - [7e68346](https://www.github.com/iotaledger/stronghold.rs/commit/7e6834669e0d458bbf152d0b8a0c18791b2a856e) Add a changelog message on 2021-01-04
-   Address two new clippy warnings: `needless_lifetimes` (addressed in the vault)
    and `unnecessary_cast` (ignored in the runtime since they are necessary for
    portability: `0 as libc::c_char` is not necessarily the same as `0_u8`).
        - [1614243](https://www.github.com/iotaledger/stronghold.rs/commit/161424322af84bd4626aac5a3f96b0c529d7b39a) Add a changelog message on 2021-01-04

## [0.2.0]

-   Add `arm` architecture mmap and linker for USB Armory.
    -   [2b20e85](https://www.github.com/iotaledger/stronghold.rs/commit/2b20e85fee1997a1739c66a12df14e4573eae60a) feat(target): arm-unknown-linux-gnueabihf target for usbarmory ([#90](https://www.github.com/iotaledger/stronghold.rs/pull/90)) on 2020-12-20
-   Alpha release of Stronghold: "Saint-Malo"
    -   [4b6f4af](https://www.github.com/iotaledger/stronghold.rs/commit/4b6f4af29f6c21044f5063ec4a8d8aff643f81a7) chore(release) ([#105](https://www.github.com/iotaledger/stronghold.rs/pull/105)) on 2020-12-24
    -   [06c6d51](https://www.github.com/iotaledger/stronghold.rs/commit/06c6d513dfcd1ba8ed6379177790ec6db28a6fea) fix(changelog): Alpha Release ([#106](https://www.github.com/iotaledger/stronghold.rs/pull/106)) on 2020-12-24
