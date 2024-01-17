# Internship Scraper and Updater

This Python script scrapes internship listings from the [SimplifyJobs Summer 2024 Internships GitHub page](https://github.com/SimplifyJobs/Summer2024-Internships/blob/dev/README.md) and updates a spreadsheet with the latest information. It is designed to append new data without overwriting user modifications in the spreadsheet.

## Features

- **Scrapes GitHub README**: Automatically pulls the latest internship listings.
- **Spreadsheet Update**: Appends new listings to an existing spreadsheet, preserving manual changes.
- **Avoids Duplicates**: Ensures no duplicate entries upon multiple script runs.
- **User-Friendly Design**: Easy to set up and run with minimal user intervention.

## Prerequisites

- Python 3.x
- Libraries: `requests`, `beautifulsoup4`, `markdown2`, `openpyxl`, `pandas`

## Setup and Installation

1. Make sure Python 3.x is installed on your system.
2. Install the required libraries by running:
   ```pip install requests beautifulsoup4 markdown2 openpyxl pandas```
## Running
```python scraper.py```
<br />
Initially, the script populates the spreadsheet with the current listing startig from Dec 1.<br />
On subsequent runs, it only adds new or updated listings.

## Manual Edits:

Feel free to manually edit the spreadsheet. These changes won't be overwritten on script reruns.

## License
This project is released under the MIT License.
