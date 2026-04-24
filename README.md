# Taipei–Tokyo Flight Recommender

This is a pandas-based flight recommendation prototype for Taipei–Tokyo routes.

The project uses a manually compiled dataset of flights between Taipei and Tokyo. The dataset includes information such as airline, flight number, departure airport, arrival airport, departure time, arrival time, aircraft type, seat information, and on-time performance.

The goal of this project is to demonstrate how pandas can be used to clean, transform, score, and rank flight options based on multiple factors.

## Features

- Load flight data from a CSV file
- Clean and process flight information using pandas
- Convert flight attributes into numerical scores
- Evaluate flights based on departure time, seat comfort, aircraft type, and punctuality
- Rank flight options by a final recommendation score

## Dataset

The dataset is located at:

```text
data/taipei_tokyo_flights.csv
```

The flight information is manually compiled for educational and demonstration purposes.

## Project Status

This project is currently a proof of concept.
At this stage, it focuses only on Taipei–Tokyo routes.

Possible future improvements include:

* Adding more routes
* Including ticket price data
* Improving user preference weights control
* Improving the interactive interface
* Automating data updates

## Tech Stack

* Python
* pandas
* Google Colab
* CSV

## Purpose

This project was created as a pandas data processing assignment and as an early prototype of a flight recommendation system.
