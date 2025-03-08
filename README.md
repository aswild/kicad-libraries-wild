# My KiCad Symbols

This is my `Wild` KiCad symbol and footprint libraries.
Things I use will be added here and referenced by other projects.

## Setup

Just add `Wild.kicad_sym` as a symbol library called `Wild`, and the path to `Wild.pretty` as a footprint library.

You can also set the KiCad environment variable `WILD_DIR` to the path to this repository, which will configure the 3D model paths in the footprints.


## License

My original work here is released under the Creative Commons Attribution-ShareAlike 4.0 license (CC-BY-SA-4.0).

Many of the symbols and footprints here are derivative works of the main KiCad library, see https://kicad.org

### Paw-Connect Footprints

The Paw-Connect footprints are from LeoDJ at https://github.com/LeoDJ/Paw-Connect, released under the CC-BY-4.0 license.

I have made the following modifications here:
  * Re-save the files using KiCad 9.0
  * Allow vias in the central keep-out rule area, so that a via can be connected to pad 4
