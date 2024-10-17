# igc2kmz IGC to Google Earth converter

igc2kmz converts paraglider and hang glider track logs into Google Earth KML format

Updated for Python 3.

## Features

* track colored by altitude, climb rate, ground speed and total energy
* shadow feature makes it easier to judge the track's altitude by eye
* animation of the flight
* photos automatically placed where they were taken and with an optional comment
* XC optimisation output
* altitude graph and high and low points labelled
* thermal and glide analysis
* time marks

## Example Usage

    igc2kmz.py -i <input-filename>.igc -o <output-filename>.kmz
