# View Metadata

View Metadata (VMD) is a CLI tool used for inspecting, parsing, and serializing metadata of files.

## Features

VMD:

- inspects one or more paths provided,
- detects filesystem types (block devices, character devices, directories, FIFOs, files, junctions, mount points, sockets, and symbolic links),
- as well as MIME types and encodings through the `magic` Python package,
- reports relevant metadata,
- formats for human parsing, and optionally serializes to JSON.

## Usage

VMD can be utilized by running `vmd` followed by parameters.

### VMD Help Menu

```
usage: vmd [-h] [-j JSON] [-m] [-q] [-v] paths [paths ...]

positional arguments:
  paths

options:
  -h, --help       show this help message and exit
  -j, --json JSON  path to json file
  -m, --metric     format size (metric)
  -q, --quiet      quiet (no output)
  -v, --verbose    be verbose (show additional information)
```
