# Notmuch Python Bindings

Python binding of the notmuch mail search and indexing library. This module
makes the functionality of the notmuch library (`https://notmuchmail.org`\_)
available to python. Successful import of this module depends on
a libnotmuch.so|dll being available on the user's system.

## Installation

The intention of this repository is to make these bindings easily available for
dependency management. It is originally taken from
`https://git.notmuchmail.org/git/notmuch/bindings/python`.

### PyPI

Install the build project from [PyPI](https://pypi.org/).

```shell
$ pip install notmuch
```

```shell
$ poetry add notmuch
```

### Git

Reference the pure sources from
[GitHub](https://github.com/weilbith/notmuch-python-bindings).

```shell
pip install from git+https://github.com/weilbith/notmuch
```

```shell
poetry add --git=https://github.com/weilbith/notmuch
```

---

## Documentation

If you have downloaded the full source tarball, you can create the documentation
with sphinx installed, go to the docs directory and "make html". A static
version of the documentation is available at:

https://notmuch.readthedocs.io/projects/notmuch-python/
