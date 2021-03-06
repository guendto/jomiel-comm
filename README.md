# jomiel-comm

[![pypi-pyversions](https://img.shields.io/pypi/pyversions/jomiel-comm?color=%230a66dc)][pypi]
[![pypi-v](https://img.shields.io/pypi/v/jomiel-comm?color=%230a66dc)][pypi]
[![pypi-wheel](https://img.shields.io/pypi/wheel/jomiel-comm?color=%230a66dc)][pypi]
[![pypi-status](https://img.shields.io/pypi/status/jomiel-comm?color=%230a66dc)][pypi]
[![code-style](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi]: https://pypi.org/project/jomiel-comm
[black]: https://pypi.org/project/black

The [Python] library for communicating with [jomiel].

## Requirements

`jomiel-comm` is written for [Python] 3.6 and later.

## Installation

```shell
pip install jomiel-comm
```

## Building packages from repo

```shell
git clone https://github.com/guendto/jomiel-comm
cd jomiel-comm
git tag -s KEYID -am 'jomiel-comm version VERSION (INITIALS)' TAGNAME
pip install pep517
python -m pep517.build [-s|-b] .
```

The packages are created under the dist/ dir.

## License

`jomiel-comm` is licensed under the [Apache License version 2.0][aplv2].

## Acknowledgements

`jomiel-comm` uses [pre-commit] and its many hooks to lint and format
the project files. See the .pre-commit-config.yaml file for details.

[python]: https://www.python.org/about/gettingstarted/
[aplv2]: https://www.tldrlegal.com/l/apache2
[jomiel]: https://github.com/guendto/jomiel/
[pre-commit]: https://pre-commit.com/
[pypi]: https://pypi.org
