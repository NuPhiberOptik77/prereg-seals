# prereg-seals

Fingerprints of a pre-registration, published before any confirmatory data existed. The documents and code stay private until the results are released. The fingerprints let anyone check later that they were not changed after the results came in.

| What | SHA-256 |
|---|---|
| Pre-registration (`docs/prereg.md`) | `56f1868cebf1bb08ef21e8a0d6b22732bd836543918973362ea88c3a2ca6f71a` |
| Pre-registration after amendment A1, a corrected file name, made at 2026-11-05T10:24:34Z before any run | `247e4d36a30aeded93af6845102405589e1f344b011fcd11bdf5986e491490e5` |
| Verdict rules (`docs/verdict-rules.md`) | `64d0dacc1281dc17f66b32f9b3b96854d43187d87ec29bf5979f8e1aa1df343e` |
| Code tree (every `.py` and `.c` file in `src/xdt`, `native`, `experiments`, `tests`) | `484849f98d86d2565e81c19f33734b0ceae561149456d4ea3604456c613c72ab` |

Sealed at 2026-11-05T10:23:31Z. The first confirmatory run starts after this commit.

To check a released document, compute its SHA-256 and compare it with the table. The code tree value is the SHA-256 of the sorted JSON map from file path to file SHA-256, as defined in `src/xdt/ledger.py`. The time of this commit is recorded by GitHub.

A fingerprint proves timing and integrity. It says nothing about whether the results are good.
