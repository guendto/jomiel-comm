# jomiel-comm

[![pypi-pyversions](https://img.shields.io/pypi/pyversions/jomiel-comm?color=%230a66dc)][pypi]
[![pypi-v](https://img.shields.io/pypi/v/jomiel-comm?color=%230a66dc)][pypi]
[![pypi-wheel](https://img.shields.io/pypi/wheel/jomiel-comm?color=%230a66dc)][pypi]
[![pypi-status](https://img.shields.io/pypi/status/jomiel-comm?color=%230a66dc)][pypi]
[![code-style](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi]: https://pypi.org/project/jomiel-comm
[black]: https://pypi.org/project/black

The [Python] library for communicating with [jomiel].

[jomiel]: https://github.com/guendto/jomiel/

## Requirements

`jomiel-comm` is written for [Python] 3.6 and later.

[python]: https://www.python.org/about/gettingstarted/

## Installation

```shell
pip install jomiel-comm
```

Install from the repository, e.g. for development:

```shell
git clone https://github.com/guendto/jomiel-comm
cd jomiel-comm
pip install -e .  # Install a project in editable mode
```

Or, if you'd rather not install in "editable mode":

```shell
pip install git+https://github.com/guendto/jomiel-comm
```

## License

`jomiel-comm` is licensed under the [Apache License version 2.0][aplv2].

[aplv2]: https://www.tldrlegal.com/l/apache2

## Acknowledgements

`jomiel-comm` uses [pre-commit] and its many hooks to lint and format
the project files. See the .pre-commit-config.yaml file for details.

[pre-commit]: https://pre-commit.com/
