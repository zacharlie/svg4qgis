# svg4qgis

Miscellaneous vector graphic elements designed for use with QGIS projects.

"RAW", or working SVGs stored in the *raw* directory. By default these are expected to be inkscape svgs. Stored here for maintenance and enhancement reasons.

SVGs which have been "parameterised" - that is to say, cleaned up, stored as plain svg and had the necessary parameters added for QGIS to edit the fill, stroke and transparency etc - will be stored in the *svg* directory.

## Using parameterise.py

Make a *processing* directory and save your "clean" svg there, then run parameterise.py to add the relevant parameters. Once added, move your updated svgs into the svg folder.

## svg-registry.json

File names and directory paths are commonly used as a form of metadata descriptor resulting in a horrible mess. Rather add some metadata to the registry so that other people can make sense of the purpose of your content along with info on it's function and use. Later on I may perhaps add a viewer which uses this to produce a nice visual catalog.
