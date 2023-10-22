# Spotify Data Analysis

This Python script performs several operations on a CSV file containing Spotify song data. It loads the data, counts the total number of songs, counts the number of songs in a specific key, and determines the most common artist.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The only requirement is Python 3.x and the CSV module, which comes pre-installed with Python.

### Installing

Clone the repository to your local machine: 

- `git clone git@github.com:pawaspy/Spotify.git`

## Usage

Run the script with Python:

- `python spotify.py`

## Functions

- `load_data(file)`: This function loads data from a CSV file using the csv library's `DictReader` function. It returns a list of dictionaries, where each dictionary represents a row in the CSV file and the keys of the dictionary are the column names.

- `count_songs(data)`: This function returns the total number of songs in the data.

- `count_songs_in_key(data, key)`: This function counts the number of songs in a specific key.

- `most_common_artist(data)`: This function determines the most common artist in the data.

## Acknowledgments

- Thanks to Spotify for providing the data.
