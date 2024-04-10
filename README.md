![Datoso](https://github.com/laromicas/datoso/blob/master/bearlogo.png)

# Datoso Seed Tdc

Datoso is a WIP Python command line tool to download and organize your Dat Roms.
As today the tool supports dat-omatic, redump, and translated-english dats.
It merges all the dats in a tree folder structure thought to use with Emulators rather than dats.
The dat file format must be compatible with [ROMVault](https://www.romvault.com/).

Total DOS Collection (TDC) is a project to collect and preserve all DOS games ever released.

## Installation

Datoso requires python 3.10+.

Use pip (recommended to use a virtual environment):

``` bash
# Install datoso base (doesn't do much without real plugins)
pip install datoso_seed_tdc

```

## Usage

Check [Datoso](https://github.com/laromicas/datoso) for usage.


## Developing a seed

Clone this repository and execute init.sh
``` bash
$ git clone https://github.com/laromicas/datoso_seed_tdc

$ cd datoso_seed_tdc
$ ./init.sh [new_name]   #e.g. ./init.sh newnointro

```
This creates a new folder with the name `datoso_seed_newnointro` with a scaffold to begin.

## TODO

-   Tests

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
