# VOTable Astronomical Data Conversion

A Python-based data-processing script for reading astronomical data from a VOTable (`.vot`) file and converting it into a Pandas DataFrame and CSV format.

## Overview

This project demonstrates how to work with astronomical catalog data stored in the Virtual Observatory Table (VOTable) format.

The script:

- Reads a VOTable using `Astropy`
- Converts the table into a Pandas DataFrame
- Displays the astronomical catalog data
- Exports the data to a CSV file
- Preserves catalog information such as object names, identifiers, coordinates, probabilities, and stellar parameters

## Data Processing

The workflow consists of three main steps:

1. Load the VOTable using `astropy.io.votable`
2. Convert the astronomical table into a Pandas DataFrame
3. Export the processed data as a CSV file


## Technologies

- Python
- Astropy
- Pandas
