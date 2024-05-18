# Manchester United vs Newcastle United Shot Statistics Scraper

Welcome to the Manchester United vs Newcastle United Shot Statistics Scraper! This repository contains a Python script for scraping detailed shot statistics from a football match between Manchester United and Newcastle United. The data can be used for analysis, visualization, or integrating into other football-related projects.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project aims to provide an easy-to-use script for scraping detailed shot statistics from a specific football match between Manchester United and Newcastle United. The collected data includes information such as player names, shot locations, shot types, and outcomes.

## Features

- Scrapes detailed shot statistics from a specified match
- Outputs data in a structured JSON format
- Easy to configure and extend for other matches or additional statistics
- Lightweight and fast

## Requirements

- Python 3.7+
- BeautifulSoup4
- Requests
- Pandas (optional, for data manipulation)

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/match-shots-stats-scraper.git
    cd match-shots-stats-scraper
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the required libraries installed (see [Installation](#installation)).
2. Run the scraper script:
    ```bash
    python scraper.py
    ```
3. The script will output the scraped data to a JSON file in the `output` directory.

## Project Structure

