# python3.12

Python 3.12.16 with pip (an older/other version beside python3): ssl, sqlite3, zlib, bz2, lzma, ctypes, readline, curses

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install python3.12
```

| | |
|---|---|
| Version | 3.12.16 |
| Licence | PSF-2.0 |
| Upstream | https://www.python.org |
| Needs | [`zlib`](https://github.com/Artfical/tpkg-zlib), [`openssl`](https://github.com/Artfical/tpkg-openssl), [`libffi`](https://github.com/Artfical/tpkg-libffi), [`bzip2`](https://github.com/Artfical/tpkg-bzip2), [`sqlite`](https://github.com/Artfical/tpkg-sqlite), [`readline`](https://github.com/Artfical/tpkg-readline), [`ncurses`](https://github.com/Artfical/tpkg-ncurses), [`ca-certificates`](https://github.com/Artfical/tpkg-ca-certificates) |
| Needs tOS build | 618 or newer |
| Size | 39512331 bytes (134333789 unpacked) |
| SHA-256 of the `.tpkg` | `14816872fb408581f7c16bfd0b47d82bd1d2009718e7e380025fe5b4ce152156` |

## Commands it adds

| Command | Runs |
|---|---|
| `python3.12` | `bin/python3.12` |
| `pip3.12` | `bin/pip3.12` |
| `pydoc3.12` | `bin/pydoc3.12` |

## Download

The package file (`python3.12-3.12.16.tpkg`) and the sources it was built from are the assets of the
[v3.12.16 release](https://github.com/Artfical/tpkg-python3.12/releases/tag/v3.12.16).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `Python-3.12.16.tar.xz`

Check a download: `sha256sum python3.12-3.12.16.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: PSF-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
