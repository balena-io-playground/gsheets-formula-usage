# Google Sheets formula usage

Scrape formulas from Google sheets.

## Usage

```
Usage: gsheets-fu [OPTIONS] SPREADSHEET_ID

  Find formulas used in a given Google spreadsheet.

Options:
  --help  Show this message and exit.
```

## Prerequisites

- [Enable the Google Sheets API](https://developers.google.com/sheets/api/quickstart/python#step_1_turn_on_the) and save the  resulting `credentials.json` file to your working directory.
- Install the included Python package using [Poetry](https://github.com/balena-io/process/blob/master/process/Python_Coding_Guide.md#create-the-environment) or `pip`.
