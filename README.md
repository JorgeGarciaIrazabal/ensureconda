# ensureconda

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/mariusvniekerk/condax/Python%20package)](https://github.com/mariusvniekerk/ensureconda/actions?query=workflow%3A%22Python+package%22)
[![Licence: MIT](https://img.shields.io/github/license/mariusvniekerk/ensureconda)](https://github.com/mariusvniekerk/ensureconda/blob/master/LICENSE-MIT)
[![PyPI](https://img.shields.io/pypi/v/ensureconda)](https://pypi.org/project/nsureconda)
[![code-style Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://https://github.com/psf/black)

## Installation

ensureconda is distributed on [PyPI](https://pypi.org) as a universal
wheel and is available on Linux, macOS and Windows and supports
Python 3.6+ and PyPy.

```bash
$ pip install ensureconda
```

## Usage

Ensureconda is a cli tool that will

1. Find a preexisting conda/mamba executable
2. Install one if nothing was found and installation is allowed.
3. Return the path of the executable found/installed on stdout

```
ensureconda --help
Usage: ensureconda [OPTIONS]

  Ensures that a conda/mamba is installed.

Options:
  --mamba / --no-mamba            Search for mamba
  --micromamba / --no-micromamba  Search for mamba/micromamba, Install if not
                                  present

  --conda / --no-conda            Search for conda
  --conda-exe / --no-conda-exe    Search for conda.exe / conda-standalone,
                                  install if not present

  --no-install
```


## License

ensureconda is distributed under the terms of the
[MIT License](https://choosealicense.com/licenses/mit).
