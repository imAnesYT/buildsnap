<h1 align="center">BuildSnap</h1>

<p align="center">
  <a href="https://pypi.org/project/buildsnap/">
    <img src="https://img.shields.io/badge/PyPI-0.1.1-blue.svg" alt="PyPI version">
  </a>
  <a href="https://pepy.tech/project/buildsnap">
  <img src="https://static.pepy.tech/badge/buildsnap" alt="Downloads">
</a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/python-3.6%2B-blue.svg" alt="Python"></a>

- A python CLI package for building installing and making packages setups...

## 🤖 Commands
```bash
buildsnap --help

buildsnap build
options:
--tar, --whl
--path, -p

Example:
buildsnap build --tar -p /sdcard/mypkg

buildsnap init
options
--name
--username

Example:
buildsnap init --name MyPKG --username User

buildsnap install
options:
--path, -p

Example:
buildsnap install --path /sdcard/MyPKG
```
## 🔵 Installation

```bash
pip install buildsnap
```
