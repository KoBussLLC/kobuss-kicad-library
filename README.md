# kobuss-kicad-library

KiCad 5.1 Symbol, Footprint, and 3d model library

## Installation

Add the library as a Global or Project Library

1. Open KiCad and select Preferences > Configure Paths...
2. Add a path named `KIUSRLIB` and point it to a folder named something like `/home/camrbuss/Documents/kicad-usr-lib`
3. Clone this repository into the `KIUSRLIB` directory  
4. Add the footprint library by selecting: Preferences > Manage Footprint Libraries... > Add existing library to table
5. Enter `${KIUSRLIB}/kobuss-kicad-library/kobuss-footprint.pretty`
6. Add the symbols library by selecting: Preferences > Manage Symbol Libraries... > Add existing library to table
7. Enter `${KIUSRLIB}/kobuss-kicad-library/kobuss-symbols/kobuss.lib`

## License

[Creative Commons CC-BY-SA 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/legalcode)