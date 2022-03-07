# Raman *Live* Tool Set
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/sfadschm/Raman-Live-Tool-Set)](https://github.com/sfadschm/Raman-Live-Tool-Set/releases)
[![GitHub license](https://img.shields.io/github/license/sfadschm/Raman-Live-Tool-Set)](https://github.com/sfadschm/Raman-Live-Tool-Set/blob/develop/LICENSE)

This is a LabView 2010 project for displaying and evaluating spectral data from mapping applications.

It is specifically designed to display a live data feed of spectral data assigned to *XY* coordinates provided from a parent/sibling VI and visualizes the progress of the mapping. 

The project is located at [GitHub](https://github.com/sfadschm/Raman-Live-Tool-Set).

Please take note of recent changes in the [*Changelog*](https://github.com/sfadschm/Raman-Live-Tool-Set/blob/develop/CHANGELOG.md) before switching to a new version.

## Credits
This project is derived from the famous `Raman Tool Set` library by Patrizio Candeloro ([**Analyst 138**, 7331, 2013](https://doi.org/10.1039/C3AN01665J)).

The original software can be found at [SourceForge](http://ramantoolset.sourceforge.net).

The functionality of the Raman *Live* Tool Set is largely reduced compared to the original software and does not include its various data processing and manipulating routines.

Instead, some convenience procedures have been implemented to ease viewing live data.

## Functionality
`XY-WI` data can be read from a tab-separated file or from a live data feed.

The data are evaluated by a selectable spectroscopic method and displayed as an interactive color-coded intensity map.

Single spectra can be selected for display from the map via mouse or keyboard navigation.

## Usage
Please refer to the [*User Guide*](https://github.com/sfadschm/Raman-Live-Tool-Set/blob/develop/docs/build) or the [*Wiki*](https://github.com/sfadschm/Raman-Live-Tool-Set/wiki) for an overview of data import, available evaluation methods and handling.

## License
This project is published unter the `MIT License`.

For more information, please refer to the [*License*](https://github.com/sfadschm/Raman-Live-Tool-Set/blob/develop/LICENSE).
